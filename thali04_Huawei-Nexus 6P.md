#### Test 85202518d111121_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of system
09-16 10:41:17.258   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-16 10:41:17.736  5578  5578 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 10:41:17.741  5578  5578 D AndroidRuntime: CheckJNI is OFF
09-16 10:41:17.769  5578  5578 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 10:41:17.815  5578  5578 I Radio-JNI: register_android_hardware_Radio DONE
09-16 10:41:17.830  5578  5578 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-16 10:41:17.843   927  3259 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-16 10:41:17.885   927  3259 I ActivityManager: Start proc 5587:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-16 10:41:17.890  5578  5578 D AndroidRuntime: Shutting down VM
,09-16 10:41:18.233   927  3892 I WindowManager: Screenshot max retries 4 of Token{d66394b ActivityRecord{d971a1a u0 com.test.thalitest/.MainActivity t4}} appWin=Window{bc6d272 u0 Starting com.test.thalitest} drawState=2
,09-16 10:41:18.301  5587  5587 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-16 10:41:18.334  5587  5587 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-16 10:41:18.361  5587  5587 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 5283-5305)
,09-16 10:41:18.361  5587  5587 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-16 10:41:18.384  5587  5587 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ae587bc}
,09-16 10:41:18.385  5587  5587 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-16 10:41:18.385  5587  5587 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-16 10:41:18.389  5587  5587 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-16 10:41:18.390  5587  5587 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-16 10:41:18.431  5587  5587 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-16 10:41:18.440  5587  5587 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-16 10:41:18.440  5587  5587 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 10:41:18.441  5587  5587 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-16 10:41:18.441  5587  5587 I Adreno  : Build Date                       : 12/06/15
09-16 10:41:18.441  5587  5587 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-16 10:41:18.441  5587  5587 I Adreno  : Local Branch                     : mybranch17112971
09-16 10:41:18.441  5587  5587 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-16 10:41:18.441  5587  5587 I Adreno  : Remote Branch                    : NONE
09-16 10:41:18.441  5587  5587 I Adreno  : Reconstruct Branch               : NOTHING
,09-16 10:41:18.502   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f362017:true
,09-16 10:41:18.535   709   709 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26240]" dev="sockfs" ino=26240 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 10:41:18.535   709   709 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[26240]" dev="sockfs" ino=26240 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 10:41:18.550  5587  5587 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-16 10:41:18.560  5587  5587 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-16 10:41:18.585   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32319]" dev="sockfs" ino=32319 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 10:41:18.585   408   408 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32319]" dev="sockfs" ino=32319 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 10:41:18.589  3895  3895 W Binder_D: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15108]" dev="sockfs" ino=15108 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-16 10:41:18.589  3895  3895 W Binder_D: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15108]" dev="sockfs" ino=15108 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 10:41:18.597  5587  5611 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-16 10:41:18.629  5587  5624 I OpenGLRenderer: Initialized EGL, version 1.4
,09-16 10:41:18.725   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +487ms (total +864ms)
,09-16 10:41:18.755  5587  5587 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5587
,09-16 10:41:18.858  5587  5587 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-16 10:41:19.206  5587  5627 D jxcore_app_log: JniHelper::setJavaVM(0xf523c000), pthread_self() = -563607248
,09-16 10:41:19.222  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 10:41:19.222  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 10:41:19.222  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 10:41:19.222  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 10:41:19.222  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-16 10:41:19.223  5587  5627 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44907bd added. We now have 1 listener(s)
,09-16 10:41:19.231  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-16 10:41:19.234  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:41:19.235  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 10:41:19.235  5587  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-16 10:41:19.241  5587  5627 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79e6c80 added. We now have 1 listener(s)
09-16 10:41:19.241  5587  5627 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 10:41:19.248   927  3083 D WifiService: New client listening to asynchronous messages
,09-16 10:41:19.249  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 10:41:19.249  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 10:41:19.249  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-16 10:41:19.249  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 10:41:19.249  5587  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-16 10:41:19.259  5587  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:41:19.259  5587  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-16 10:41:19.267  5587  5627 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-16 10:41:19.267  5587  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:41:19.267  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:41:19.267  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:41:19.267  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:41:19.267  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:41:19.267  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:19.267  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:41:19.267  5587  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:41:19.267  5587  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-16 10:41:19.267  5587  5627 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 10:41:19.268  5587  5627 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 10:41:19.520  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:41:19.529  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:41:19.535  5587  5587 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 10:41:19.937  5587  5596 I art     : Background sticky concurrent mark sweep GC freed 76145(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 2.403ms total 229.299ms
,09-16 10:41:20.259  5587  5633 W jxcore-log: Initializing JXcore engine
09-16 10:41:20.259  5587  5633 W jxcore-log: JXcore engine is ready
,09-16 10:41:20.294   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 10:41:20.339  5633  5633 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=5667 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-16 10:41:20.339  5633  5633 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[17506]" dev="sockfs" ino=17506 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-16 10:41:20.339  5633  5633 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 10:41:20.342  5633  5633 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32287]" dev="sockfs" ino=32287 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-16 10:41:20.361  5587  5633 W jxcore-log: Starting JXcore engine
,09-16 10:41:20.434  5587  5633 W jxcore-log: Platform android
09-16 10:41:20.434  5587  5633 W jxcore-log: 
,09-16 10:41:20.434  5587  5633 W jxcore-log: Process ARCH arm
09-16 10:41:20.434  5587  5633 W jxcore-log: 
,09-16 10:41:20.540  5587  5633 I jxcore-log: JXcore Cordova bridge is ready!
09-16 10:41:20.540  5587  5633 I jxcore-log: 
09-16 10:41:20.541  5587  5633 W jxcore-log: JXcore engine is started
,09-16 10:41:20.552  5587  5627 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 10:41:20.556  5587  5587 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 10:41:23.319   927  5333 D NetlinkSocketObserver: NeighborEvent{elapsedMs=320264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:41:24.170   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:41:26.342   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 10:41:29.373   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 10:41:30.414  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 10:41:30.414  5587  5633 I jxcore-log: 
,09-16 10:41:30.416  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 10:41:30.416  5587  5633 I jxcore-log: 
,09-16 10:41:30.419  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:41:30.419  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:41:30.419  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:41:30.419  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:41:30.419  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:41:30.419  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:30.419  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:41:30.419  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:41:30.421  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:41:30.423  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 10:41:30.423  5587  5633 I jxcore-log: 
09-16 10:41:30.424  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 10:41:30.424  5587  5633 I jxcore-log: 
,09-16 10:41:30.674  5587  5633 I jxcore-log: Running unit tests
09-16 10:41:30.674  5587  5633 I jxcore-log: 
,09-16 10:41:30.675  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 10:41:30.675  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f9de32 added. We now have 2 listener(s)
09-16 10:41:30.676  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:41:30.676  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 10:41:30.676  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 10:41:30.676  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 10:41:30.676  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c30783 added. We now have 2 listener(s)
09-16 10:41:30.676  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:41:30.677  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 10:41:30.678  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:41:30.681  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:41:30.681  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:41:30.681  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:41:30.681  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:41:30.681  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:41:30.681  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:30.681  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:41:30.681  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:41:30.682  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:30.683  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:41:30.683  5587  5633 D executeNativeTests: Running unit tests
,09-16 10:41:30.689  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:41:30.694  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:41:30.721  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 10:41:30.721  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 added. We now have 3 listener(s)
,09-16 10:41:30.722  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:41:30.722  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 10:41:30.722  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 10:41:30.722  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:41:30.722  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e added. We now have 3 listener(s)
09-16 10:41:30.722  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:41:30.722  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 10:41:30.724  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:41:30.726  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:41:30.726  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:41:30.726  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:41:30.726  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:41:30.726  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:41:30.726  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:30.726  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:41:30.726  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:41:30.727  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:30.727  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:41:30.728  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-16 10:41:30.728  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 10:41:30.728  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 10:41:30.728  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 10:41:30.729  5587  5633 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-16 10:41:30.729  5587  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 10:41:30.729  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 10:41:30.729  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-16 10:41:30.729  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 10:41:30.729  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 10:41:30.730  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:30.730  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:30.730  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:30.730  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:30.731  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:30.731  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:41:30.731  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 10:41:30.731  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 removed from the list
09-16 10:41:30.731  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:30.731  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e removed from the list
09-16 10:41:30.733  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:41:30.740  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:41:30.740  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:30.740  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:30.741  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:30.741  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:30.741  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:30.741  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:30.741  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:30.741  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:30.742  5587  5633 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 10:41:30.742  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:30.742  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:30.742  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:30.742  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:30.743  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:30.743  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:30.743  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:30.743  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:30.743  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:30.743  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:30.743  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:30.743  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:30.743  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:30.743  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:30.743  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:30.743  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 10:41:30.743  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:30.743  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 10:41:30.746  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 10:41:30.747  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 10:41:30.747  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 10:41:30.747  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 10:41:30.747  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 10:41:30.747  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 10:41:30.747  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:30.747  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:41:30.747  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:30.747  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:30.747  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:30.747  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:30.747  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:30.747  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:30.747  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:30.747  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:30.747  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:30.747  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:30.747  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:30.747  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:30.748  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:30.748  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:30.748  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:30.748  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:30.748  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 10:41:30.749  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:41:30.751  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:41:30.751  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:41:30.751  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:41:30.751  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:41:30.751  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:41:30.751  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:30.751  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:41:30.751  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:41:30.752  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:30.752  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:41:30.752  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-16 10:41:30.752  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 10:41:30.752  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 10:41:30.752  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:41:30.752  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 10:41:30.756  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 10:41:30.756  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:41:30.756  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 10:41:30.758  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 10:41:30.759  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:41:30.759  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 10:41:30.759  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 10:41:30.760  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-16 10:41:30.763  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-16 10:41:30.763  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 10:41:30.763  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-16 10:41:30.763  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 10:41:30.763  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:41:30.766  4561  4574 D BtGatt.GattService: registerClient() - UUID=9032951b-4805-42ac-be79-a63832c4c59d
,09-16 10:41:30.766  4561  4623 D BtGatt.GattService: onClientRegistered() - UUID=9032951b-4805-42ac-be79-a63832c4c59d, clientIf=5
,09-16 10:41:30.767  5587  5597 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 10:41:30.768  4561  4783 D BtGatt.GattService: start scan with filters
,09-16 10:41:30.772  4561  4626 D BtGatt.ScanManager: handling starting scan
,09-16 10:41:30.772  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 10:41:30.772  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 10:41:30.772  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 10:41:30.772  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 10:41:30.773  4561  4626 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:41:30.774  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 10:41:30.774  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 10:41:30.774  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:41:30.775  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 10:41:30.776  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 10:41:30.780  4561  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-16 10:41:30.780  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:30.780  4561  4626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 10:41:30.785  4561  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 10:41:30.785  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:30.786  4561  4626 D BtGatt.ScanManager: Starting BLE batch scan
09-16 10:41:30.786  4561  4626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 10:41:30.795  4561  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 10:41:30.795  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:41:30.801  4561  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 10:41:30.801  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:41:31.276  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 10:41:31.277  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:41:31.277  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:41:31.822   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:41:31.823   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:41:35.780  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 10:41:35.780  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:35.780  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 10:41:35.780  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:35.780  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 10:41:35.781  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-16 10:41:35.781  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 10:41:35.781  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 10:41:35.781  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:41:35.782  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 10:41:35.782  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 10:41:35.783  5587  5633 D BluetoothAdapter: STATE_ON
09-16 10:41:35.784  4561  4793 D BtGatt.GattService: stopScan() - queue size =1
,09-16 10:41:35.786  4561  4574 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 10:41:35.788  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 10:41:35.788  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 10:41:35.789  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 10:41:35.789  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 10:41:35.789  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-16 10:41:35.790  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 10:41:35.790  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 10:41:35.791  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 10:41:35.791  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 10:41:35.792  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:41:35.794  4561  4561 D BtGatt.ScanManager: awakened up at time 332739
,09-16 10:41:35.798  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 10:41:35.798  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:41:35.799  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:35.799  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:41:35.799  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:41:35.799  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:41:35.799  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:35.799  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:35.799  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:35.799  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:35.799  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:35.800  4561  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 10:41:35.800  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:35.801  4561  4626 D BtGatt.ScanManager: stopping BLe Batch
,09-16 10:41:35.810  4561  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 10:41:35.810  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:35.811  4561  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 10:41:35.836  4561  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-16 10:41:35.836  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:35.836  4561  4623 D BtGatt.GattService: current time is 332781211052
09-16 10:41:35.837  4561  4623 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -88, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 10:41:35.839  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-16 10:41:35.840  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-16 10:41:35.840  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-16 10:41:35.840  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 10:41:35.840  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 10:41:35.841  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-16 10:41:36.300  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 10:41:40.801  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 10:41:40.807  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:41:40.820  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:41:40.820  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:41:40.820  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:41:40.820  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:41:40.820  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:41:40.820  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:40.820  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:41:40.820  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:41:40.825  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:41:40.825  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:41:40.825  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-16 10:41:40.826  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-16 10:41:40.826  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 10:41:40.826  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:41:40.826  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 10:41:40.830  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:41:40.835  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 10:41:40.835  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 10:41:40.835  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:41:40.843  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 10:41:40.844  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 10:41:40.844  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 10:41:40.848  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 10:41:40.848  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 10:41:40.848  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 10:41:40.849  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:41:40.851  4561  4794 D BtGatt.GattService: registerClient() - UUID=43234ad9-9d4c-44b9-84f7-132f53131a3f
,09-16 10:41:40.852  4561  4623 D BtGatt.GattService: onClientRegistered() - UUID=43234ad9-9d4c-44b9-84f7-132f53131a3f, clientIf=5
09-16 10:41:40.852  5587  5597 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 10:41:40.853  4561  4793 D BtGatt.GattService: start scan with filters
,09-16 10:41:40.857  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 10:41:40.857  4561  4626 D BtGatt.ScanManager: handling starting scan
09-16 10:41:40.857  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 10:41:40.857  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 10:41:40.857  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 10:41:40.860  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 10:41:40.860  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 10:41:40.860  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:41:40.861  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 10:41:40.864  4561  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 10:41:40.864  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:40.864  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
09-16 10:41:40.865  4561  4626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 10:41:40.867  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:40.867  5587  5633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-16 10:41:40.867  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:40.867  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 10:41:40.867  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:40.867  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 10:41:40.868  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 10:41:40.868  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 10:41:40.868  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 10:41:40.868  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:41:40.868  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 10:41:40.868  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 10:41:40.869  5587  5633 D BluetoothAdapter: STATE_ON
09-16 10:41:40.870  4561  4783 D BtGatt.GattService: stopScan() - queue size =1
09-16 10:41:40.871  4561  4576 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 10:41:40.871  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 10:41:40.871  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 10:41:40.871  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 10:41:40.871  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 10:41:40.871  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 10:41:40.871  4561  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 10:41:40.871  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:40.872  4561  4626 D BtGatt.ScanManager: Starting BLE batch scan
09-16 10:41:40.872  4561  4626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-16 10:41:40.873  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:41:40.873  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 10:41:40.873  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 10:41:40.873  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 10:41:40.874  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 10:41:40.875  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:40.875  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:41:40.875  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:41:40.875  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:40.876  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:40.876  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:40.876  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:40.876  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:40.876  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:41:40.876  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:41:40.876  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 10:41:40.877  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:40.877  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:40.878  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:40.878  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:40.878  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:40.878  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:40.879  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 10:41:40.881  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:41:40.886  4561  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 10:41:40.886  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:41:40.886  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:41:40.886  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:41:40.886  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:41:40.886  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:41:40.886  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:41:40.886  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:40.886  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:41:40.886  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:41:40.890  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:41:40.890  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:41:40.891  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:41:40.891  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 10:41:40.891  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 10:41:40.891  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:41:40.891  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 10:41:40.891  4561  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 10:41:40.891  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:41:40.893  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:41:40.894  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 10:41:40.894  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 10:41:40.896  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:41:40.899  4561  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 10:41:40.899  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:40.899  4561  4626 D BtGatt.ScanManager: stopping BLe Batch
09-16 10:41:40.900  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 10:41:40.901  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 10:41:40.901  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 10:41:40.904  4561  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 10:41:40.904  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 10:41:40.904  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:40.904  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 10:41:40.904  4561  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 10:41:40.904  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 10:41:40.904  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:41:40.906  4561  4783 D BtGatt.GattService: registerClient() - UUID=5a322131-7c4a-48a1-b7ee-b935ad62ca6c
09-16 10:41:40.907  4561  4623 D BtGatt.GattService: onClientRegistered() - UUID=5a322131-7c4a-48a1-b7ee-b935ad62ca6c, clientIf=5
09-16 10:41:40.907  5587  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 10:41:40.907  4561  4793 D BtGatt.GattService: start scan with filters
,09-16 10:41:40.909  4561  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 10:41:40.909  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:40.910  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 10:41:40.910  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-16 10:41:40.910  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-16 10:41:40.910  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 10:41:40.911  4561  4626 D BtGatt.ScanManager: handling starting scan
09-16 10:41:40.912  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:41:40.912  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 10:41:40.912  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:41:40.913  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 10:41:40.915  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
09-16 10:41:40.915  4561  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 10:41:40.916  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:41:40.916  4561  4626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 10:41:40.920  4561  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 10:41:40.920  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:40.921  4561  4626 D BtGatt.ScanManager: Starting BLE batch scan
09-16 10:41:40.921  4561  4626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 10:41:40.930  4561  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 10:41:40.930  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:41:40.934  4561  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 10:41:40.934  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:41:41.413  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 10:41:41.413  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:41:41.413  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:41:44.173   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:41:44.489   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 10:41:45.915  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 10:41:45.916  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:45.916  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 10:41:45.916  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:45.916  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 10:41:45.916  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 10:41:45.917  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-16 10:41:45.917  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 10:41:45.917  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:41:45.917  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 10:41:45.917  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 10:41:45.919  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:41:45.921  4561  4783 D BtGatt.GattService: stopScan() - queue size =1
,09-16 10:41:45.924  4561  4793 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 10:41:45.925  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 10:41:45.926  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 10:41:45.926  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 10:41:45.926  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 10:41:45.926  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 10:41:45.930  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:41:45.930  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 10:41:45.930  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 10:41:45.930  4561  4561 D BtGatt.ScanManager: awakened up at time 342875
09-16 10:41:45.930  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 10:41:45.931  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:41:45.932   927  5333 D NetlinkSocketObserver: NeighborEvent{elapsedMs=342877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
09-16 10:41:45.935  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:41:45.936  4561  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 10:41:45.936  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:45.936  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:41:45.937  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 10:41:45.937  4561  4626 D BtGatt.ScanManager: stopping BLe Batch
,09-16 10:41:45.943  4561  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 10:41:45.943  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:41:45.943  4561  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 10:41:45.962  4561  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-16 10:41:45.962  4561  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:41:45.962  4561  4623 D BtGatt.GattService: current time is 342907081430
09-16 10:41:45.962  4561  4623 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -87, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -79, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -82, 90, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -82, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-16 10:41:45.963  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-16 10:41:45.963  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 10:41:45.963  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 10:41:45.963  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 10:41:45.964  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 10:41:45.964  4561  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-16 10:41:46.437  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 10:41:46.438  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:46.438  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:41:46.823   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:41:47.528   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 10:41:47.825   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:41:48.826   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:41:49.828   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:41:50.829   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:41:50.936  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 10:41:50.937  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:41:50.937  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:41:50.937  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 10:41:50.937  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.937  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 10:41:50.938  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.938  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:41:50.938  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:50.938  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 10:41:50.938  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:50.940  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.940  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:50.943  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 10:41:50.943  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.943  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:41:50.943  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.945  5587  5633 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-16 10:41:50.947  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:50.947  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:50.947  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:41:50.947  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:50.947  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.948  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.948  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.948  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.948  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.948  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 10:41:50.949  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.949  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.949  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.949  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:50.953  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:50.953  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.953  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.953  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.956  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 10:41:50.956  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:50.956  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:50.957  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:41:50.957  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:50.957  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.957  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.957  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.957  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.957  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.957  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:50.957  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.957  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.957  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.957  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.959  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 10:41:50.959  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.959  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.959  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.960  5587  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-16 10:41:50.960  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:50.961  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:50.961  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:50.961  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:50.961  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:41:50.961  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.961  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.961  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.961  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.961  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:50.961  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.961  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.961  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.961  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:50.963  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:50.963  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.963  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.963  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.964  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-16 10:41:50.965  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:50.965  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:50.965  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:50.965  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:50.965  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.965  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:50.965  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.965  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.965  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.965  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:50.966  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.966  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.966  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.966  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.967  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:50.967  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.967  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.968  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:50.969  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 10:41:50.969  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 10:41:50.969  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 10:41:50.969  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 10:41:50.969  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-16 10:41:50.969  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 10:41:50.969  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 10:41:50.970  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-16 10:41:50.970  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 10:41:50.970  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:50.970  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:41:50.970  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:41:50.970  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:50.970  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:41:50.970  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.970  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.970  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.971  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.971  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 10:41:50.971  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.971  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.971  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.971  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.973  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:50.973  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.973  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.973  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.974  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 10:41:50.975  5587  5633 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 10:41:50.975  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 10:41:50.978  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 10:41:50.978  5587  5633 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-16 10:41:50.978  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 10:41:50.978  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 10:41:50.978  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 10:41:50.978  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 10:41:50.978  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: ,[<no peer name> 24:1410:1410:1410:1410:1410]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 10:41:50.979  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 10:41:50.980  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 10:41:50.980  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 10:41:50.980  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 10:41:50.980  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 10:41:50.980  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 10:41:50.980  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 10:41:50.980  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 10:41:50.980  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-16 10:41:50.980  5587  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 10:41:50.981  5587  5633 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-16 10:41:50.981  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 10:41:50.981  5587  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 10:41:50.981  5587  5633 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-16 10:41:50.981  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 10:41:50.981  5587  5633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 10:41:50.981  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-16 10:41:50.984  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-16 10:41:50.985  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 10:41:50.985  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 10:41:50.986  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-16 10:41:50.986  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-16 10:41:50.986  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-16 10:41:50.986  5587  5633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 10:41:50.987  5587  5633 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-16 10:41:50.987  5587  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-16 10:41:50.987  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:50.988  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:50.988  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:50.988  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:50.988  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.988  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.988  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-16 10:41:50.989  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.989  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.989  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.989  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:50.989  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.990  5587  5634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 10:41:50.990  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.990  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.990  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.991  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-16 10:41:50.991  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-16 10:41:50.991  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:50.991  5587  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-16 10:41:50.991  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.991  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.991  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.989  4576  4576 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31248]" dev="sockfs" ino=31248 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 10:41:50.989  4576  4576 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31248]" dev="sockfs" ino=31248 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 10:41:50.992  5587  5633 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-16 10:41:50.993  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:50.993  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:50.993  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:50.993  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:50.993  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.993  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.993  5587  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-16 10:41:50.993  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.993  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.993  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.993  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:50.993  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.993  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.994  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.994  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.995  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:50.995  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.995  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.995  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.996  5587  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-16 10:41:50.996  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:50.996  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:50.996  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:50.996  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:50.997  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.997  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.997  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:50.997  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.997  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.997  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:50.997  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.997  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.997  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:50.997  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:50.998  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:50.998  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:50.998  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:50.998  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:50.999  5587  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-16 10:41:50.999  5587  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-16 10:41:50.999  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 10:41:50.999  5587  5633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-16 10:41:50.999  5587  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 10:41:50.999  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-16 10:41:50.999  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 10:41:50.999  5587  5633 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-16 10:41:50.999  5587  5633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 10:41:50.999  5587  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 10:41:50.999  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 10:41:51.000  5587  5633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-16 10:41:51.000  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:51.000  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:51.000  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:51.000  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:51.000  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:51.000  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:51.000  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:51.000  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:51.000  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:51.000  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:51.000  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:51.000  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:51.000  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:51.000  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:51.001  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:51.001  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:51.001  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:51.001  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:51.002  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:51.002  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:51.002  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:51.002  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:51.002  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:51.002  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:51.002  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:51.002  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:51.002  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:51.830   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:41:56.003  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:41:56.004  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:56.004  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:56.004  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.004  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.004  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
,09-16 10:41:56.004  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:56.005  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:56.005  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:56.005  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 10:41:56.005  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.005  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.006  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:56.006  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:56.006  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:56.006  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:56.006  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.006  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.006  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:41:56.007  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.010  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:56.010  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:56.010  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:56.011  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:56.016  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-16 10:41:56.017  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:41:56.019  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-16 10:41:56.023  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-16 10:41:56.023  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 10:41:56.024  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 10:41:56.024  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-16 10:41:56.024  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 10:41:56.025  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:56.025  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 10:41:56.025  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 10:41:56.025  5587  5637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 10:41:56.025  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-16 10:41:56.025  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.026  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 10:41:56.026  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 10:41:56.026  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:56.026  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:56.026  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 10:41:56.026  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 10:41:56.026  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:41:56.027  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.027  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:56.025  4793  4793 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31253]" dev="sockfs" ino=31253 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 10:41:56.025  4793  4793 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31253]" dev="sockfs" ino=31253 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 10:41:56.029  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:41:56.030  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:41:56.030  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:56.030  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:41:56.030  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:56.030  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:41:56.030  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:56.030  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:56.030  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 10:41:56.030  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.030  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.031  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:56.031  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:56.031  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:56.031  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:56.031  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:41:56.031  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.031  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.032  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.032  5587  5637 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 10:41:56.032  5587  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-16 10:41:56.032  5587  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 10:41:56.033  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 10:41:56.035  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:56.035  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:56.035  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:41:56.036  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:56.039  5587  5633 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-16 10:41:56.040  5587  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 10:41:56.040  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-16 10:41:56.040  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 10:41:56.040  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 10:41:56.041  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:56.041  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:41:56.041  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:41:56.041  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:56.041  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.041  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.043  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
,09-16 10:41:56.043  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:56.043  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:56.043  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:56.043  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.043  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.043  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.043  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:41:56.045  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:56.046  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:56.046  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:56.046  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:56.052  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 10:41:56.052  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:56.052  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:56.052  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:56.052  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.053  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.053  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:56.053  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:41:56.053  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:56.053  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:56.053  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.053  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.053  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.053  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.054  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 10:41:56.054  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:56.054  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:56.054  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:56.055  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:41:56.056  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:41:56.056  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:41:56.056  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:41:56.056  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:41:56.056  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.056  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9a2a9 not in the list
09-16 10:41:56.056  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:41:56.056  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
09-16 10:41:56.056  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:41:56.056  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:41:56.056  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.056  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:41:56.056  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:41:56.058  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:41:56.058  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:41:56.058  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:41:56.058  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ff02e not in the list
,09-16 10:41:56.059  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-16 10:41:56.059  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 10:41:56.059  5587  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-16 10:41:56.059  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 10:41:56.059  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-16 10:41:56.060  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-16 10:41:56.062  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 10:41:56.062  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-16 10:41:56.063  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-16 10:41:56.063  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 10:41:56.063  5587  5633 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-16 10:41:56.063  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 10:41:56.063  5587  5633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-16 10:41:56.063  5587  5633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-16 10:41:56.064  5587  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-16 10:41:56.064  5587  5633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-16 10:41:56.064  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-16 10:41:56.065  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-16 10:41:56.066  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-16 10:41:56.066  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-16 10:41:56.067  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:41:56.067  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afc4b60 added. We now have 3 listener(s)
09-16 10:41:56.067  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:41:56.070  5587  5633 D BluetoothAdapter: enable(): BT is already enabled..!
09-16 10:41:56.071   927  3895 D WifiService: setWifiEnabled: true pid=5587, uid=10077
,09-16 10:41:56.071   927  3895 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 10:41:56.121  4561  4768 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-16 10:41:56.121  4561  4771 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-16 10:41:56.532  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 10:41:56.831   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:41:57.832   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:41:58.833   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:41:59.834   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:00.835   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:01.077  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 10:42:01.077  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a38819 added. We now have 4 listener(s)
,09-16 10:42:01.078  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 10:42:01.090  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:42:01.090  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a38819 removed from the list
09-16 10:42:01.090  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 10:42:01.090  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:42:01.090  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:01.092  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:42:01.092  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d6ec0de added. We now have 4 listener(s)
,09-16 10:42:01.092  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:42:01.097  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:42:01.097  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d6ec0de removed from the list
09-16 10:42:01.097  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:42:01.097  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:01.097  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:01.098  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:42:01.099  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ff2bf added. We now have 4 listener(s)
09-16 10:42:01.099  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:42:01.101   927  3681 D WifiService: setWifiEnabled: false pid=5587, uid=10077
09-16 10:42:01.101   927  3681 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 10:42:01.105   927  3082 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-16 10:42:01.105   927  3082 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-16 10:42:01.105   927  3082 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 10:42:01.105   927  3082 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 10:42:01.111  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:42:01.111  4561  4619 D BluetoothAdapterState: Current state: ON, message: 23
09-16 10:42:01.112  4561  4619 D BluetoothAdapterProperties: Setting state to 13
,09-16 10:42:01.112  4561  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 10:42:01.113  4561  4619 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 10:42:01.114  4561  4619 I BluetoothAdapterState: Entering PendingCommandState
09-16 10:42:01.116  4561  4623 D BluetoothAdapterProperties: Scan Mode:20
,09-16 10:42:01.117  4561  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-16 10:42:01.122  4561  4561 D BluetoothMapService: onReceive
09-16 10:42:01.123  4561  4561 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 10:42:01.123  4561  4561 D BluetoothMapService: STATE_TURNING_OFF
09-16 10:42:01.123  4561  4561 D BluetoothMapService: MAP Service closeService in
09-16 10:42:01.123  4561  4561 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 10:42:01.123  4561  4561 D ObexServerSockets0: shutdown(block = true)
09-16 10:42:01.124  4561  4561 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-16 10:42:01.124  4561  4561 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 10:42:01.124  4561  4796 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,09-16 10:42:01.124  4561  4771 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-16 10:42:01.125  4561  4797 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 10:42:01.125  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.125  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:42:01.125  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.125  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.125  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:01.125  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.125  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:01.125  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:01.125  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:01.126  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.126  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:01.126  4561  4561 I BtOppRfcommListener: stopping Accept Thread
09-16 10:42:01.126  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:42:01.126  4561  5303 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 10:42:01.127  4561  5303 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 10:42:01.127   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-16 10:42:01.127   927  5334 D DhcpClient: Clearing IP address
,09-16 10:42:01.130  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:01.133  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:01.134   506   920 D CommandListener: Setting iface cfg
09-16 10:42:01.136  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.136  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:01.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:01.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:01.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:01.137  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.137  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:01.138   927   940 I ActivityManager: Start proc 5641:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-16 10:42:01.139  4561  4561 D HeadsetService: Received stop request...Stopping profile...
,09-16 10:42:01.141  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.141  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.141  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.141  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.141  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:01.141  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.141  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:01.141  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:01.141  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:01.142  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.142  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:01.142   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:01.143  3247  3262 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:01.143   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:01.143   927   927 D BluetoothHeadset: Proxy object disconnected
,09-16 10:42:01.143  3618  3638 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:01.145  4561  4561 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:01.145  4561  4561 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:01.145  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 10:42:01.145  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:01.146  4561  4561 D A2dpService: Received stop request...Stopping profile...
09-16 10:42:01.146  4561  4788 D A2dpStateMachine: Exit Disconnected: -1
09-16 10:42:01.146  3709  5387 V NativeCrypto: Read error: ssl=0x7f61e42700: I/O error during system call, Connection timed out
09-16 10:42:01.148  3709  5387 V NativeCrypto: SSL shutdown failed: ssl=0x7f61e42700: I/O error during system call, Broken pipe
09-16 10:42:01.148  3247  3247 D HeadsetProfile: Bluetooth service disconnected
09-16 10:42:01.148  3247  3247 D BluetoothA2dp: Proxy object disconnected
,09-16 10:42:01.149   927   927 D BluetoothA2dp: Proxy object disconnected
09-16 10:42:01.150   927  3259 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-16 10:42:01.150   927  5332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-16 10:42:01.150  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:01.152   927  5332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-16 10:42:01.153   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-16 10:42:01.153   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-16 10:42:01.153  4561  4561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 10:42:01.153  4561  4561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 10:42:01.153  4561  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 10:42:01.154  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-16 10:42:01.154  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:01.154  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:01.154  4561  4623 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 10:42:01.154  4561  4561 D HidService: Received stop request...Stopping profile...
09-16 10:42:01.154  4561  4561 D HidService: Stopping Bluetooth HidService
09-16 10:42:01.155   927  3084 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-16 10:42:01.156  4561  4561 D HealthService: Received stop request...Stopping profile...
09-16 10:42:01.155  3247  3247 D BluetoothInputDevice: Proxy object disconnected
09-16 10:42:01.157  3247  3247 D HidProfile: Bluetooth service disconnected
09-16 10:42:01.158   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 10:42:01.158   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-16 10:42:01.158  4561  4561 D PanService: Received stop request...Stopping profile...
,09-16 10:42:01.161  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:01.162  3247  3247 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-16 10:42:01.161   533   533 E Parcel  : Reading a NULL string not supported here.
09-16 10:42:01.162  3247  3247 D PanProfile: Bluetooth service disconnected
09-16 10:42:01.163  4561  4561 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:01.163  4561  4561 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:01.163  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:01.163  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 10:42:01.164  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.164  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.164  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.164  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.164  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:01.164  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.164  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:01.164  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:01.164  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:01.164  4561  4561 D BluetoothMapService: Received stop request...Stopping profile...
09-16 10:42:01.164  4561  4561 D BluetoothMapService: stop()
09-16 10:42:01.164  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 10:42:01.165  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 10:42:01.166   927   927 D RttService: SCAN_AVAILABLE : 1
,09-16 10:42:01.166   927  3190 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 10:42:01.166  4561  4561 D BluetoothMapAppObserver: deinitObservers()
,09-16 10:42:01.166  4561  4561 D BluetoothMapAppObserver: removeReceiver()
,09-16 10:42:01.167  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.167  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.167  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.167  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.167  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:01.167  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.167  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:01.167  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:01.167  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:42:01.167  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.167  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:01.167   927  3084 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-16 10:42:01.168  4561  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 10:42:01.168  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:01.169  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:01.169  4561  4768 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 10:42:01.169  4561  4768 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 10:42:01.169  4561  4768 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 10:42:01.169  4561  4768 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 10:42:01.170  3576  3745 W QCNEJ   : |CORE| network lost: 100
09-16 10:42:01.170  4561  4561 D SapService: Received stop request...Stopping profile...
09-16 10:42:01.170  4561  4561 V SapService: stop()
09-16 10:42:01.170  3576  3745 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-16 10:42:01.171   927  3082 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 10:42:01.171  4561  4561 V BluetoothAdapterState: isTurningOff()=true
,09-16 10:42:01.171  4561  4561 V BluetoothAdapterState: isTurningOn()=false
,09-16 10:42:01.171  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 10:42:01.171  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false,
09-16 10:42:01.172  4561  4561 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-16 10:42:01.172   927  5335 D DhcpClient: Receive thread stopped
,09-16 10:42:01.172  4561  4561 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-16 10:42:01.172  4561  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 10:42:01.173  4561  4561 V BluetoothAdapterState: isTurningOff()=true
,09-16 10:42:01.173  4561  4561 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:01.173  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 10:42:01.173  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 10:42:01.173  4561  4561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-16 10:42:01.173  4561  4561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-16 10:42:01.173  4561  4561 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:01.174  4561  4561 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:01.174  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:01.174  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:01.174  4561  4561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 10:42:01.174  4561  4561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 10:42:01.174  4561  4623 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 10:42:01.174  3247  3247 D BluetoothMap: Proxy object disconnected
09-16 10:42:01.174  3247  3247 D MapProfile: Bluetooth service disconnected
09-16 10:42:01.178  4561  4561 D BluetoothMapService: MAP Service closeService in
,09-16 10:42:01.178  4561  4561 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:01.178  4561  4561 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:01.178  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:01.178  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:01.179  4561  4561 D BluetoothMapService: cleanup()
09-16 10:42:01.179  4561  4561 D BluetoothMapService: MAP Service closeService in
09-16 10:42:01.180  4561  4561 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:01.180  4561  4561 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:01.180  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:01.180  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:01.180   927  3082 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 10:42:01.180  4561  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-16 10:42:01.181  4561  4619 D BluetoothAdapterProperties: Setting state to 15
09-16 10:42:01.181  4561  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 10:42:01.181  4561  4619 I BluetoothAdapterState: Entering BleOnState
09-16 10:42:01.181  3247  3262 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 10:42:01.182   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:01.182  3247  3878 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 10:42:01.183   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:01.183  3618  3933 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:01.183  3247  3261 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:01.183  3247  3262 D BluetoothMap: onBluetoothStateChange: up=false
09-16 10:42:01.184  3247  3878 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 10:42:01.184  3247  3261 D BluetoothPan: onBluetoothStateChange on: false
,09-16 10:42:01.185   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:01.185   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 10:42:01.185  4561  4619 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 10:42:01.185  4561  4619 D BluetoothAdapterProperties: Setting state to 16
09-16 10:42:01.185  4561  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 10:42:01.186  4561  4619 D BluetoothAdapterProperties: onBleDisable
09-16 10:42:01.186  4561  4619 I BluetoothAdapterState: Entering PendingCommandState
09-16 10:42:01.186  4561  4620 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 10:42:01.187  4561  4623 D BluetoothAdapterProperties: Scan Mode:20
09-16 10:42:01.188   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 10:42:01.188  4561  4768 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 10:42:01.188  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:01.193  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.193  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.193  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.193  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.193  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:01.193  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.193  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:01.193  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:01.193  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:01.194  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.194  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:01.196  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.196  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.196  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.196  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.196  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:01.196  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.196  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:01.196  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:01.196  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:01.197  5641  5641 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-16 10:42:01.198  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do ,the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.198  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.198  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.198  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.198  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:01.198  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.198  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:01.198  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:01.198  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:01.199  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:01.201  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:01.201  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:01.205   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 10:42:01.205   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-16 10:42:01.206   506   920 D TetherController: Setting IP forward enable = 0
09-16 10:42:01.206   927  3084 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-16 10:42:01.206   927  3084 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-16 10:42:01.208   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 10:42:01.210   927  3082 D DhcpClient: doQuit
09-16 10:42:01.210   927  3082 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 10:42:01.210   927  5334 D DhcpClient: onQuitting
09-16 10:42:01.211  3767  3767 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 10:42:01.211  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:01.214  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.215  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.215  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.215  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.215  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:01.215  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.215  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:01.215  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:01.215  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:01.216  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 10:42:01.216  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 10:42:01.219  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.219  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.219  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.219  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.219  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:01.219  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.219  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:01.219  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:01.219  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:01.220  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.220  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:01.223  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.223  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:01.223  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:01.223  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:01.223  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:01.223  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:01.223  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:01.223  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:01.223  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:01.224  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:01.224  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 10:42:01.225  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:01.227  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:01.227  5224  5224 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f76f868 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-16 10:42:01.228  4922  4922 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-16 10:42:01.231  5012  5028 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 10:42:01.231  5012  5028 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 10:42:01.231  5012  5028 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 10:42:01.231  5012  5028 E SarControlService: no key has been found,reset the power
09-16 10:42:01.231  5012  5051 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 10:42:01.231  5012  5051 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 10:42:01.231  5012  5051 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-16 10:42:01.232  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 10:42:01.232  5039  5039 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 10:42:01.234  5012  5051 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 10:42:01.234  5012  5051 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 10:42:01.235  5012  5051 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-16 10:42:01.236  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 10:42:01.236  5039  5039 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 10:42:01.237  5039  5055 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@412138e HexData = [00000000ea03000000000000ffffffff]
09-16 10:42:01.237  5039  5055 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 10:42:01.237  5039  5055 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-16 10:42:01.237  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 10:42:01.238  5012  5022 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-16 10:42:01.245  5039  5055 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@412138e HexData = [00000000eb03000000000000ffffffff]
,09-16 10:42:01.245  5039  5055 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 10:42:01.245  5039  5055 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-16 10:42:01.246  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 10:42:01.246  5012  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 10:42:01.248  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 10:42:01.249  3767  3767 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-16 10:42:01.253   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9db2fdf:true
,09-16 10:42:01.254  3709  3709 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 10:42:01.256  3767  3767 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-16 10:42:01.267   927  3542 I ActivityManager: Start proc 5670:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-16 10:42:01.283  5641  5641 D LocalBluetoothProfileManager: Adding local MAP profile
09-16 10:42:01.283  3767  3767 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 10:42:01.289  5641  5641 D BluetoothMap: Create BluetoothMap proxy object
,09-16 10:42:01.300  5641  5641 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-16 10:42:01.302  3767  3767 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 10:42:01.315  5670  5670 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-16 10:42:01.326  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,09-16 10:42:01.329   927  3509 I ActivityManager: Killing 4970:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-16 10:42:01.393  4561  4623 I bt_hci  : shut_down
,09-16 10:42:01.397  4561  4628 D bt_hwcfg: hw_epilog_process
,09-16 10:42:01.397  4561  4628 I bt_vendor: low_power_mode_cb
,09-16 10:42:01.399  4561  4628 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-16 10:42:01.399  4561  4628 I bt_vendor: epilog_cb
09-16 10:42:01.399  4561  4628 I bt_hci  : epilog_finished_callback
,09-16 10:42:01.402  4561  4623 I bt_hci_h4: hal_close
,09-16 10:42:01.403  4561  4623 I bt_userial_vendor: device fd = 54 close
,09-16 10:42:01.408   927  3082 D wifi    : In wifi stop Hal
,09-16 10:42:01.408  4408  4408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 10:42:01.408   927  3082 D wifi    : halHandle = 0x7f60c1cd80, mVM = 0x7f7d28d140, mCls = 0x100b4a
09-16 10:42:01.408   927  3760 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 10:42:01.408   927  3760 D WifiHAL : Got a signal to exit!!!
09-16 10:42:01.408   927  3760 I WifiHAL : Exit wifi_event_loop
09-16 10:42:01.408   927  3082 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-16 10:42:01.408   927  3082 E WifiHAL : Event processing terminated
09-16 10:42:01.409   927  3082 D wifi    : In wifi cleaned up handler
09-16 10:42:01.409   927  3082 I WifiHAL : Internal cleanup completed
09-16 10:42:01.410  3771  4152 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 10:42:01.410  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:01.411  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:01.413  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:01.430   927  3760 D wifi    : set interface wlan0 flags (DOWN)
,09-16 10:42:01.430   927  3082 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 10:42:01.511  4561  4620 D bt_stack_manager: event_shut_down_stack finished.
,09-16 10:42:01.511  4561  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 10:42:01.512  4561  4619 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-16 10:42:01.513  4561  4561 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 10:42:01.513  4561  4561 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 10:42:01.513  4561  4561 D BtGatt.GattService: stop()
09-16 10:42:01.513  4561  4561 D BtGatt.AdvertiseManager: advertise clients cleared
,09-16 10:42:01.515  4561  4561 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:01.515  4561  4561 V BluetoothAdapterState: isTurningOn()=false
,09-16 10:42:01.515  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:01.515  4561  4561 V BluetoothAdapterState: isBleTurningOff()=true
09-16 10:42:01.515  4561  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 10:42:01.515  4561  4619 D BluetoothAdapterProperties: Setting state to 10
,09-16 10:42:01.515  4561  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 10:42:01.516  4561  4619 I BluetoothAdapterState: Entering OffState
,09-16 10:42:01.517   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-16 10:42:01.523  4561  4561 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-16 10:42:01.523  4561  4561 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-16 10:42:01.523  4561  4561 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 10:42:01.524  4561  4620 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 10:42:01.535  4561  4620 D bt_stack_manager: event_clean_up_stack finished.
,09-16 10:42:01.539  4561  4561 I art     : System.exit called, status: 0
,09-16 10:42:01.539  4561  4561 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 10:42:01.565  5670  5670 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 10:42:01.565  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-16 10:42:01.570  5670  5670 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 10:42:01.570  5670  5670 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 10:42:01.570  5670  5670 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 10:42:01.570  5670  5670 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:583)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 10:42:01.570  5670  5670 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 10:42:01.570  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 10:42:01.571  5670  5670 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 10:42:01.571  5670  5670 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 10:42:01.571  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 10:42:01.576  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 10:42:01.579   927  3509 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-16 10:42:01.580   927  3509 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-16 10:42:01.580   927  3509 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-16 10:42:01.580   927  3509 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-16 10:42:01.580   927  3509 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-16 10:42:01.603   927  3509 I ActivityManager: Start proc 5701:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-16 10:42:01.604  5641  5641 D DockEventReceiver: finishStartingService: stopping service
09-16 10:42:01.604   927  3259 W ActivityManager: Spurious death for ProcessRecord{9daa5aa 5701:com.android.bluetooth/1002}, curProc for 4561: null
09-16 10:42:01.605   927  3894 I ActivityManager: Killing 5361:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
09-16 10:42:01.633   927   944 D Tethering: InitialState.processMessage what=4
09-16 10:42:01.653   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 10:42:01.703  5701  5701 D AdapterServiceConfig: Adding HeadsetService
,09-16 10:42:01.703  5701  5701 D AdapterServiceConfig: Adding A2dpService
09-16 10:42:01.704  5701  5701 D AdapterServiceConfig: Adding HidService
09-16 10:42:01.704  5701  5701 D AdapterServiceConfig: Adding HealthService
09-16 10:42:01.704  5701  5701 D AdapterServiceConfig: Adding PanService
09-16 10:42:01.704  5701  5701 D AdapterServiceConfig: Adding GattService
09-16 10:42:01.704  5701  5701 D AdapterServiceConfig: Adding BluetoothMapService
09-16 10:42:01.704  5701  5701 D AdapterServiceConfig: Adding SapService
09-16 10:42:01.706   927   938 I ActivityManager: Killing 5374:com.android.chrome/u0a39 (adj 15): empty #17
,09-16 10:42:01.760  3709  3709 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 10:42:01.779  4026  4026 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-16 10:42:01.784  4026  5358 I iu.UploadsManager: num queued entries: 0
,09-16 10:42:01.784  4026  5358 I iu.UploadsManager: num updated entries: 0
,09-16 10:42:01.789  4026  4026 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 10:42:01.791  4026  4026 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 10:42:01.792  4026  5358 I iu.SyncManager: NEXT; no task
,09-16 10:42:01.803   927  3308 I ActivityManager: Start proc 5715:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-16 10:42:01.836   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:42:01.841  5715  5715 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-16 10:42:01.844  5715  5715 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 10:42:01.850  5715  5715 D SprintDMHelper: simOperator: 
,09-16 10:42:01.850  5715  5715 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 10:42:01.862   927  3894 I ActivityManager: Start proc 5727:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-16 10:42:01.862   927  3894 I ActivityManager: Killing 5391:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-16 10:42:01.890  5670  5696 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-16 10:42:01.965  4408  5742 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 10:42:01.966   927  3308 I ActivityManager: Start proc 5743:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-16 10:42:01.967   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec6c8c7:true
,09-16 10:42:01.972   927  3894 I ActivityManager: Killing 5224:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-16 10:42:02.035  5743  5743 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-16 10:42:02.202   927  3308 I ActivityManager: Killing 4636:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-16 10:42:02.238   927  3542 I ActivityManager: Start proc 5757:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-16 10:42:02.260   506   920 E Netd    : netlink response contains error (No such file or directory)
,09-16 10:42:02.261   927  3084 E NetdConnector: NDC Command {52 network destroy 100} took too long (1054ms)
,09-16 10:42:02.262   927  3084 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 10:42:02.262   927  3080 E NetdConnector: NDC Command {53 bandwidth setglobalalert 2097152} took too long (1050ms)
09-16 10:42:02.263   927  3079 E NetdConnector: NDC Command {54 bandwidth gettetherstats} took too long (608ms)
09-16 10:42:02.263   506   920 D TetherController: Setting IP forward enable = 0
,09-16 10:42:02.272  5757  5757 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-16 10:42:02.280   927  3509 I ActivityManager: Killing 5449:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-16 10:42:06.130   927  3892 D WifiService: setWifiEnabled: true pid=5587, uid=10077
,09-16 10:42:06.131   927  3892 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 10:42:06.140   506   920 D SoftapController: Softap fwReload - Ok
,09-16 10:42:06.145   506   920 D CommandListener: Setting iface cfg
09-16 10:42:06.145   506   920 D CommandListener: Trying to bring down wlan0
,09-16 10:42:06.147   506   920 D CommandListener: Clearing all IP addresses on wlan0
,09-16 10:42:06.152   927  3082 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 10:42:06.723   927  3082 D wifi    : set interface wlan0 flags (UP)
,09-16 10:42:06.726   927  3082 I WifiHAL : Initializing wifi
09-16 10:42:06.726   927  3082 I WifiHAL : Creating socket
09-16 10:42:06.727   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 10:42:06.730   927  3082 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-16 10:42:06.730   927  3082 D wifi    : Did set static halHandle = 0x7f60c1cd80
09-16 10:42:06.730   927  3082 D wifi    : halHandle = 0x7f60c1cd80, mVM = 0x7f7d28d140, mCls = 0x1a3a
09-16 10:42:06.731   927  3082 D wifi    : array field set
09-16 10:42:06.731   927  3082 I WifiNative-HAL: interface[0] = wlan0
09-16 10:42:06.733   927  5780 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547084160384
09-16 10:42:06.733   927  5780 D wifi    : waitForHalEvents called, vm = 0x7f7d28d140, obj = 0x1a3a, env = 0x7f62ec7d80
,09-16 10:42:06.794  5781  5781 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 10:42:06.812  5781  5781 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 10:42:06.820  5781  5781 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 10:42:06.820  5781  5781 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 10:42:06.834   927  3082 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 10:42:06.842  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 10:42:06.842  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:06.842  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:06.842  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:06.842  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:06.842  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:06.842  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:06.842  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:06.842  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:06.842  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:06.843  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:06.845  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:06.845  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:06.845  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:06.845  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:06.845  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:06.845  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:06.845  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:06.845  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:06.845  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 10:42:06.845  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:06.846  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:06.847  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:06.847  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:06.847  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:06.847  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:06.847  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:06.847  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:06.847  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:06.847  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:06.847  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:06.847  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:06.848  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:06.848   927  3082 D WifiConfigStore: Loading config and enabling all networks 
09-16 10:42:06.849  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:06.850  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:06.851  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:06.862   927  3082 D WifiConfigStore: loaded 0 passpoint configs
,09-16 10:42:06.862   927  3082 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 10:42:06.862   927  3082 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-16 10:42:06.863   927  3082 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-16 10:42:06.864   927  3082 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 10:42:06.864   927  3082 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 10:42:06.864   927  3082 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 10:42:06.864   927  3082 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 10:42:06.866   927  3082 D WifiNative-HAL: Setting external_sim to 1
,09-16 10:42:06.867  4408  4408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 10:42:06.867   927  3082 D wifi    : setting dfs flag to true, 0x7f62f3f560
09-16 10:42:06.867   927  3082 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 10:42:06.867   927  3082 D wifi    : setting scan oui 0x7f62f3f560
,09-16 10:42:06.867   927  3082 D WifiHAL : Sending mac address OUI
09-16 10:42:06.871   927  3082 E native  : do suspend false
,09-16 10:42:06.878   927  3082 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-16 10:42:06.878   927   927 D RttService: SCAN_AVAILABLE : 3
09-16 10:42:06.878   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 10:42:06.878   927  3190 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 10:42:06.879   506   920 D CommandListener: Setting iface cfg
,09-16 10:42:06.883   927  3081 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-16 10:42:06.883   927  3081 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 10:42:06.890   927  3081 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 10:42:06.894   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=363839 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,09-16 10:42:06.895   927  3081 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 10:42:10.048  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 10:42:10.054  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 10:42:10.060  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 10:42:10.064  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 10:42:10.112   927  3082 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 10:42:10.113   927  3082 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-16 10:42:10.113   927  3082 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 10:42:10.126   927  3082 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 10:42:10.173   927  3082 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 10:42:10.175  5781  5781 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 10:42:10.601  5781  5781 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 10:42:10.638  5781  5781 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 10:42:10.639  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 10:42:10.649   927  3082 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 10:42:10.649   927  3082 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 10:42:10.650   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-16 10:42:10.665   927  3082 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 10:42:10.679   506   920 D CommandListener: Setting iface cfg
,09-16 10:42:10.683   927  3082 D WifiStateMachine: Start Dhcp Watchdog 2
,09-16 10:42:10.690   927  5787 D DhcpClient: Receive thread started
,09-16 10:42:10.694   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 10:42:10.694   927  3082 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-16 10:42:10.694   927  3084 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-16 10:42:10.781   927  3082 E native  : do suspend false
,09-16 10:42:10.801   927  5786 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 10:42:10.813   927  5787 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172473, domain null
,09-16 10:42:10.814   927  5786 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172473 seconds
,09-16 10:42:10.816   927  5786 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 10:42:10.834   927  5787 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 10:42:10.835   927  5786 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-16 10:42:10.838   506   920 D CommandListener: Setting iface cfg
,09-16 10:42:10.842   927  3082 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 10:42:10.849   927  5786 D DhcpClient: Scheduling renewal in 86399s
,09-16 10:42:10.861   927  3082 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-16 10:42:10.863   927  3082 D WifiConfigStore: No blacklist allowed without epno enabled
,09-16 10:42:10.865   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-16 10:42:10.867   927  3084 D ConnectivityService: Adding iface wlan0 to network 101
,09-16 10:42:10.873   927  3082 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 10:42:10.919   927  3084 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-16 10:42:10.919   927  3084 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-16 10:42:10.921   927  3084 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-16 10:42:10.926   927  3084 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-16 10:42:10.928   927  3084 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-16 10:42:10.936   927  3084 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 10:42:10.941   927  3084 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-16 10:42:10.942   927  3084 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-16 10:42:10.942   927  3084 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-16 10:42:10.943   927  3084 D ConnectivityService:    accepting network in place of null
09-16 10:42:10.943   927  3082 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-16 10:42:10.943   927  3082 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 10:42:10.943   927  3084 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 10:42:10.956   927  5785 D NetlinkSocketObserver: NeighborEvent{elapsedMs=367901, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:42:10.965   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 10:42:10.987   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 10:42:10.991   927  3084 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-16 10:42:10.991   927  3084 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 10:42:10.991  3576  3745 W QCNEJ   : |CORE| network available: 101
09-16 10:42:10.992   927  3084 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-16 10:42:10.994   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 10:42:10.995  3576  3745 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-16 10:42:10.996  3576  3745 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-16 10:42:10.997  3576  3745 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-16 10:42:10.999  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 10:42:10.999  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:10.999  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:10.999  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:10.999  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:10.999  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:10.999  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:10.999  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:10.999  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:10.999  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:10.999  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:11.001  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.001  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:11.001  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:11.001  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:11.001  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:11.001  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:11.001  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:11.001  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:11.001  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:11.001  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.001  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:42:11.006  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 10:42:11.006  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:11.006  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:11.006  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:11.006  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:11.006  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:11.006  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:11.006  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:11.006  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:11.006  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.006  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:42:11.009  5012  5028 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 10:42:11.009  5012  5028 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 10:42:11.009  5012  5028 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-16 10:42:11.009  5012  5028 E SarControlService: no key has been found,reset the power
,09-16 10:42:11.010  5012  5051 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 10:42:11.010  5012  5051 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 10:42:11.010  5012  5051 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 10:42:11.010  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 10:42:11.010  5039  5039 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 10:42:11.011  5012  5051 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 10:42:11.011  5012  5051 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 10:42:11.012  5012  5051 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 10:42:11.012  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 10:42:11.012  5039  5039 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 10:42:11.013  4922  4922 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-16 10:42:11.016  5039  5055 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@412138e HexData = [00000000ec03000000000000ffffffff]
09-16 10:42:11.016  5039  5055 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 10:42:11.017  5039  5055 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-16 10:42:11.017  5039  5055 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@412138e HexData = [00000000ed03000000000000ffffffff]
09-16 10:42:11.018  5039  5055 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 10:42:11.018  5039  5055 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-16 10:42:11.018  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 10:42:11.019  5012  5022 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 10:42:11.019  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-16 10:42:11.022  5012  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 10:42:11.026  4026  4026 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-16 10:42:11.035  4026  5358 I iu.UploadsManager: num queued entries: 0
,09-16 10:42:11.035  4026  5358 I iu.UploadsManager: num updated entries: 0
09-16 10:42:11.036  4026  5358 I iu.SyncManager: NEXT; no task
,09-16 10:42:11.037   927  5784 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-16 10:42:11.037  4026  4026 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 10:42:11.039  4026  4026 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 10:42:11.041  5715  5715 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 10:42:11.044  5715  5715 D SprintDMHelper: simOperator: 
09-16 10:42:11.044  5715  5715 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 10:42:11.138   927  3639 D WifiService: setWifiEnabled: false pid=5587, uid=10077
,09-16 10:42:11.138   927  3639 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 10:42:11.140   927  3082 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-16 10:42:11.140   927  3082 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-16 10:42:11.140   927  3082 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 10:42:11.140   927  3082 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 10:42:11.150   927  5784 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 14:42:11 GMT], X-Android-Received-Millis=[1474036931149], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474036931079]}
,09-16 10:42:11.150   927  5786 D DhcpClient: Clearing IP address
,09-16 10:42:11.150   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-16 10:42:11.151   927  3084 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 10:42:11.151   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-16 10:42:11.151   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-16 10:42:11.152   506   920 D CommandListener: Setting iface cfg
09-16 10:42:11.152   927  3084 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 10:42:11.157  3709  5797 V NativeCrypto: SSL handshake aborted: ssl=0x7f733cbd80: I/O error during system call, Connection timed out
,09-16 10:42:11.161  4408  5801 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-16 10:42:11.163   927  3542 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,09-16 10:42:11.163   927  5784 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,09-16 10:42:11.164   927  5784 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-16 10:42:11.167   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 10:42:11.168   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-16 10:42:11.173   533   533 E Parcel  : Reading a NULL string not supported here.
09-16 10:42:11.177   927  5784 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-16 10:42:11.178   927  3082 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-16 10:42:11.180   927  3084 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
09-16 10:42:11.181  ,4408  5801 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
09-16 10:42:11.181  4408  5801 W Babel_NetworkConnectionCheckingService: 	... 21 more
09-16 10:42:11.181  4408  5801 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-16 10:42:11.181   927   927 D RttService: SCAN_AVAILABLE : 1
09-16 10:42:11.182  3576  3745 W QCNEJ   : |CORE| network lost: 101
09-16 10:42:11.182   927  3190 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-16 10:42:11.182   927  3082 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 10:42:11.182  3576  3745 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-16 10:42:11.185   927  5787 D DhcpClient: Receive thread stopped
,09-16 10:42:11.201   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 10:42:11.219   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 10:42:11.219   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-16 10:42:11.219   927  3084 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-16 10:42:11.219   927  3084 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 10:42:11.221   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-16 10:42:11.226  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.226  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:11.226  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:11.226  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:11.226  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:11.226  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:11.226  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:11.226  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:11.226  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:11.226  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.226  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:11.228   927  3082 D DhcpClient: doQuit
,09-16 10:42:11.228  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.228  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:11.228  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:11.228  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:11.228  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:11.228  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:11.228  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:11.228  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:11.228  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:11.229  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.229  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:11.229   927  5786 D DhcpClient: onQuitting
09-16 10:42:11.230   927  3082 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 10:42:11.230  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 10:42:11.231  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:11.231  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:11.231  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:11.231  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:11.231  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:11.231  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:11.231  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:11.231  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:11.231  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.231  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:11.231  5781  5781 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 10:42:11.233  4922  4922 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-16 10:42:11.234  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.234  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:11.234  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:11.234  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:11.234  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:11.234  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:11.234  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:11.234  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:11.234  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:11.234  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.234  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:11.236  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.236  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:11.236  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:11.236  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:11.236  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:11.236  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:11.236  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:11.236  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:11.236  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active, network type is Wi-Fi: false
09-16 10:42:11.236  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.236  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 10:42:11.238  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.238  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:11.238  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:11.238  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:11.238  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:11.238  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:11.238  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:11.238  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:11.238  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:11.238  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:11.238  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:11.243  5012  5028 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 10:42:11.243  5012  5028 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 10:42:11.244  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-16 10:42:11.244  5012  5028 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 10:42:11.244  5012  5028 E SarControlService: no key has been found,reset the power
09-16 10:42:11.244  5012  5051 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 10:42:11.244  5012  5051 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 10:42:11.244  5012  5051 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 10:42:11.244  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 10:42:11.245  5039  5039 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 10:42:11.246  5012  5051 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 10:42:11.246  5012  5051 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 10:42:11.246  5012  5051 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-16 10:42:11.246  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-16 10:42:11.246  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 10:42:11.246  5039  5039 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-16 10:42:11.262  5039  5055 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@412138e HexData = [00000000ee03000000000000ffffffff]
09-16 10:42:11.262  5039  5055 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 10:42:11.262  5039  5055 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-16 10:42:11.262  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 10:42:11.262  5012  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-16 10:42:11.263  5039  5055 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@412138e HexData = [00000000ef03000000000000ffffffff]
09-16 10:42:11.263  5039  5055 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-16 10:42:11.263  5039  5055 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-16 10:42:11.264  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 10:42:11.264  5012  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 10:42:11.265  4026  4026 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-16 10:42:11.266  5781  5781 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 10:42:11.270  4026  5358 I iu.UploadsManager: num queued entries: 0
,09-16 10:42:11.270  4026  5358 I iu.UploadsManager: num updated entries: 0
09-16 10:42:11.271  4026  5358 I iu.SyncManager: NEXT; no task
09-16 10:42:11.273  4026  4026 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 10:42:11.274  4026  4026 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 10:42:11.275   506   920 E Netd    : netlink response contains error (No such file or directory)
,09-16 10:42:11.276   927  3084 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-16 10:42:11.276  5715  5715 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-16 10:42:11.276  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-16 10:42:11.276   927  3084 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 10:42:11.283  5715  5715 D SprintDMHelper: simOperator: 
09-16 10:42:11.283  5715  5715 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 10:42:11.292  4408  5819 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 10:42:11.379   927  3082 D wifi    : In wifi stop Hal
09-16 10:42:11.379   927  3082 D wifi    : halHandle = 0x7f60c1cd80, mVM = 0x7f7d28d140, mCls = 0x1a3a
09-16 10:42:11.379   927  5780 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-16 10:42:11.379   927  5780 D WifiHAL : Got a signal to exit!!!
,09-16 10:42:11.379   927  5780 I WifiHAL : Exit wifi_event_loop
09-16 10:42:11.380   927  3082 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-16 10:42:11.380   927  3082 E WifiHAL : Event processing terminated
,09-16 10:42:11.380   927  3082 D wifi    : In wifi cleaned up handler
09-16 10:42:11.380   927  3082 I WifiHAL : Internal cleanup completed
,09-16 10:42:11.382  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:11.382  3771  4152 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 10:42:11.383  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:11.383  4408  4408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 10:42:11.386  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:11.411   927  5780 D wifi    : set interface wlan0 flags (DOWN)
,09-16 10:42:11.411   927  3082 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 10:42:11.617   927   944 D Tethering: InitialState.processMessage what=4
,09-16 10:42:11.624   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 10:42:11.836   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:11.993   927  3084 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-16 10:42:12.837   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:13.839   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:14.840   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:15.841   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:16.175   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f68e9e:true
,09-16 10:42:16.176  5701  5701 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 10:42:16.181  5701  5701 I bt_bluedroid: init
,09-16 10:42:16.181  5701  5821 I BluetoothAdapterState: Entering OffState
,09-16 10:42:16.185  5701  5822 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 10:42:16.185  5701  5822 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 10:42:16.185  5701  5822 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 10:42:16.186  5701  5822 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-16 10:42:16.187  5701  5701 I bt_bluedroid: get_profile_interface socket
,09-16 10:42:16.190  5701  5701 I bt_bluedroid: get_profile_interface sdp
09-16 10:42:16.191  5701  5825 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 10:42:16.193  5701  5825 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 10:42:16.200  5701  5712 I bt_bluedroid: config_hci_snoop_log
,09-16 10:42:16.202   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 10:42:16.211  5701  5821 D BluetoothAdapterState: Current state: OFF, message: 0
,09-16 10:42:16.211  5701  5821 D BluetoothAdapterProperties: Setting state to 14
,09-16 10:42:16.211  5701  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 10:42:16.214  5701  5821 D BluetoothBondStateMachine: make
,09-16 10:42:16.217  5701  5826 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 10:42:16.221  5701  5821 I BluetoothAdapterState: Entering PendingCommandState
,09-16 10:42:16.223  5701  5701 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 10:42:16.227  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:16.228  5701  5701 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 10:42:16.229  5701  5701 D BtGatt.GattService: Received start request. Starting profile...
09-16 10:42:16.229  5701  5701 D BtGatt.GattService: start()
,09-16 10:42:16.229  5701  5701 I bt_bluedroid: get_profile_interface gatt
,09-16 10:42:16.231  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:16.231  5701  5701 D BtGatt.AdvertiseManager: advertise manager created
,09-16 10:42:16.239  5701  5701 V BluetoothAdapterState: isTurningOff()=false
,09-16 10:42:16.239  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:16.239  5701  5701 V BluetoothAdapterState: isBleTurningOn()=true
09-16 10:42:16.239  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:16.239  5701  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 10:42:16.241  5701  5821 I bt_bluedroid: bt_bluedroid
,09-16 10:42:16.242  5701  5822 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-16 10:42:16.242  5701  5822 I bt_hci  : start_up
,09-16 10:42:16.249  5701  5822 I bt_vendor: alloc value 0xf3e78871
09-16 10:42:16.249  5701  5822 I bt_vendor: init
,09-16 10:42:16.249  5701  5822 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 10:42:16.250  5701  5822 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 10:42:16.365  5701  5822 D bt_hci  : start_up starting async portion
09-16 10:42:16.365  5701  5829 I bt_hci  : event_finish_startup
09-16 10:42:16.366  5701  5829 I bt_hci_h4: hal_open
09-16 10:42:16.366  5701  5829 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 10:42:16.368  5701  5829 I bt_userial_vendor: device fd = 54 open
,09-16 10:42:16.362  5830  5830 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 10:42:16.382  5701  5829 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 10:42:16.384  5701  5829 D bt_hwcfg: Chipset BCM4358A3
,09-16 10:42:16.384  5701  5829 D bt_hwcfg: Target name = [BCM4358A3]
,09-16 10:42:16.385  5701  5829 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 10:42:16.779  5701  5829 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 10:42:16.779  5701  5829 D bt_hwcfg: Settlement delay -- 100 ms
09-16 10:42:16.779  5701  5829 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 10:42:16.841   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:42:16.913  5701  5829 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 10:42:16.913  5701  5829 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-16 10:42:16.915  5701  5829 I bt_hwcfg: vendor lib fwcfg completed
,09-16 10:42:16.915  5701  5829 I bt_vendor: firmware callback
,09-16 10:42:16.915  5701  5829 I bt_hci  : firmware_config_callback
,09-16 10:42:16.925  5701  5832 I bt_btu  : btu_task pending for preload complete event
,09-16 10:42:16.925  5701  5832 I bt_btu_task: Bluetooth chip preload is complete
09-16 10:42:16.925  5701  5832 I bt_btu  : btu_task received preload complete event
,09-16 10:42:16.931  5701  5832 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 10:42:16.932  5701  5832 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 10:42:16.932  5701  5832 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 10:42:16.932  5701  5832 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-16 10:42:16.932  5701  5832 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 10:42:16.932  5701  5832 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 10:42:16.932  5701  5832 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 10:42:16.932  5701  5832 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 10:42:16.933  5701  5832 I         : BTE_InitTraceLevels -- TRC_GAP
,09-16 10:42:16.933  5701  5832 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 10:42:16.933  5701  5832 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 10:42:16.933  5701  5832 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 10:42:16.933  5701  5832 I         : BTE_InitTraceLevels -- TRC_SMP
,09-16 10:42:16.933  5701  5832 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-16 10:42:16.933  5701  5832 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 10:42:17.016  5701  5832 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3df6549
,09-16 10:42:17.017  5701  5832 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3df6549 
,09-16 10:42:17.038  5701  5825 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 10:42:17.039  5701  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 10:42:17.040  5701  5825 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 10:42:17.042  5701  5825 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 10:42:17.045  5701  5825 D BluetoothAdapterProperties: Scan Mode:20
,09-16 10:42:17.045  5701  5825 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-16 10:42:17.046  5701  5825 D bt_hci  : do_postload posting postload work item
09-16 10:42:17.046  5701  5829 I bt_hci  : event_postload
09-16 10:42:17.046  5701  5829 I bt_vendor: sco_config_cb
09-16 10:42:17.046  5701  5829 I bt_hci  : sco_config_callback postload finished.
09-16 10:42:17.050  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:17.052  5701  5829 I bt_vendor: low_power_mode_cb
09-16 10:42:17.052  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:17.054  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:17.056  5701  5825 D bt_bte_conf: Device ID record 1 : primary
,09-16 10:42:17.056  5701  5825 D bt_bte_conf:   vendorId            = 000f
09-16 10:42:17.056  5701  5825 D bt_bte_conf:   vendorIdSource      = 0001
09-16 10:42:17.056  5701  5825 D bt_bte_conf:   product             = 1200
09-16 10:42:17.056  5701  5825 D bt_bte_conf:   version             = 1436
09-16 10:42:17.056  5701  5825 D bt_bte_conf:   clientExecutableURL = 
09-16 10:42:17.056  5701  5825 D bt_bte_conf:   serviceDescription  = 
09-16 10:42:17.056  5701  5825 D bt_bte_conf:   documentationURL    = 
09-16 10:42:17.056  5701  5825 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 10:42:17.057  5701  5822 D bt_stack_manager: event_start_up_stack finished
09-16 10:42:17.057  5701  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-16 10:42:17.057  5701  5821 D BluetoothAdapterProperties: Setting state to 15
09-16 10:42:17.058  5701  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-16 10:42:17.060  5701  5821 I BluetoothAdapterState: Entering BleOnState
,09-16 10:42:17.063  5701  5821 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-16 10:42:17.063  5701  5821 D BluetoothAdapterProperties: Setting state to 11
09-16 10:42:17.063  5701  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-16 10:42:17.070  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:17.073  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:17.073  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:17.074  5701  5701 D HeadsetService: Received start request. Starting profile...
,09-16 10:42:17.074  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:17.076  5701  5701 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 10:42:17.077  5701  5701 D HeadsetStateMachine: make
,09-16 10:42:17.082  5701  5821 I BluetoothAdapterState: Entering PendingCommandState
,09-16 10:42:17.086  5701  5701 D HeadsetStateMachine: max_hf_connections = 1
,09-16 10:42:17.086  5701  5701 I bt_bluedroid: get_profile_interface handsfree
09-16 10:42:17.086  5701  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 10:42:17.086  5701  5825 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-16 10:42:17.089  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:17.090  5701  5701 D A2dpService: Received start request. Starting profile...
,09-16 10:42:17.090  5701  5701 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 10:42:17.091  5701  5701 I bt_bluedroid: get_profile_interface avrcp
,09-16 10:42:17.097  5701  5701 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 10:42:17.097  5701  5701 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 10:42:17.097  5701  5701 D A2dpStateMachine: make
09-16 10:42:17.098  5701  5701 I bt_bluedroid: get_profile_interface a2dp
,09-16 10:42:17.099  5701  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-16 10:42:17.100  5701  5841 D A2dpStateMachine: Enter Disconnected: -2
,09-16 10:42:17.101  5701  5701 I BluetoothHidServiceJni: classInitNative: succeeds
09-16 10:42:17.101  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:42:17.102  3709  3709 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 10:42:17.103  5701  5701 D HidService: Received start request. Starting profile...
,09-16 10:42:17.103  5641  5641 D BluetoothInputDevice: Proxy object connected
,09-16 10:42:17.103  5701  5701 I bt_bluedroid: get_profile_interface hidhost
09-16 10:42:17.103  5701  5701 D HidService: setHidService(): set to: null
09-16 10:42:17.103  5701  5825 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3dd756d
09-16 10:42:17.103  5701  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-16 10:42:17.104  5701  5701 I BluetoothHealthServiceJni: classInitNative: succeeds
09-16 10:42:17.104  5641  5641 D HidProfile: Bluetooth service connected
09-16 10:42:17.104  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:42:17.105  5701  5701 D HealthService: Received start request. Starting profile...
09-16 10:42:17.106  5701  5701 I bt_bluedroid: get_profile_interface health
,09-16 10:42:17.107  5701  5701 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-16 10:42:17.108  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:17.109  5701  5701 D PanService: Received start request. Starting profile...
,09-16 10:42:17.109  5641  5641 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 10:42:17.109  5701  5701 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 10:42:17.109  5701  5701 I bt_bluedroid: get_profile_interface pan
,09-16 10:42:17.110  5641  5641 D PanProfile: Bluetooth service connected
,09-16 10:42:17.110  5701  5825 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-16 10:42:17.111  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:17.113  5641  5641 D BluetoothMap: Proxy object connected
09-16 10:42:17.113  5701  5701 D BluetoothMapService: Received start request. Starting profile...
09-16 10:42:17.113  5701  5701 D BluetoothMapService: start()
09-16 10:42:17.113  5641  5641 D MapProfile: Bluetooth service connected
09-16 10:42:17.114  5641  5641 D BluetoothMap: getConnectedDevices()
09-16 10:42:17.114  5641  5641 D BluetoothMap: Bluetooth is Not enabled
,09-16 10:42:17.115  5701  5701 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 10:42:17.116  5701  5701 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-16 10:42:17.117  5701  5701 D BluetoothMapAppObserver: createReceiver()
09-16 10:42:17.118  5701  5701 D BluetoothMapAppObserver: initObservers()
09-16 10:42:17.118  5701  5701 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 10:42:17.123  5701  5701 V SapService: SapBinder()
09-16 10:42:17.124  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:17.124  5701  5701 D SapService: Received start request. Starting profile...
,09-16 10:42:17.124  5701  5701 V SapService: start()
,09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isTurningOff()=false
,09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:17.127  5701  5839 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:17.127  5701  5701 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:17.128  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:17.128  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:17.128  5701  5701 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:17.128  5701  5701 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:17.128  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:17.128  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 10:42:17.129  5701  5701 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:17.129  5701  5701 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:17.129  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:17.129  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:17.129  5701  5701 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:17.129  5701  5701 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:17.129  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:17.129  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:17.130  5701  5701 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:17.130  5701  5701 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:17.130  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 10:42:17.130  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 10:42:17.131  5701  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-16 10:42:17.131  5701  5821 D BluetoothAdapterProperties: ScanMode =  20
09-16 10:42:17.131  5701  5821 D BluetoothAdapterProperties: State =  11
09-16 10:42:17.132  5701  5821 D BluetoothAdapterProperties: Setting state to 12
09-16 10:42:17.132  5701  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 10:42:17.132  5701  5821 I BluetoothAdapterState: Entering OnState
09-16 10:42:17.133  3247  5808 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 10:42:17.134  5701  5825 D BluetoothAdapterProperties: Scan Mode:21
09-16 10:42:17.134  5701  5825 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-16 10:42:17.135   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:17.136  3247  3262 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 10:42:17.136  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:17.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:17.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:17.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:17.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:17.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:17.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:17.136  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 10:42:17.137   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 10:42:17.137  5641  5653 D BluetoothPan: onBluetoothStateChange on: true
,09-16 10:42:17.138  5641  5652 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 10:42:17.138  3247  3247 D BluetoothA2dp: Proxy object connected
09-16 10:42:17.139  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:17.140  3618  3638 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:17.140  5641  5653 D BluetoothMap: onBluetoothStateChange: up=true
09-16 10:42:17.140  3247  3878 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:17.141  3247  5808 D BluetoothMap: onBluetoothStateChange: up=true
09-16 10:42:17.142  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:17.142  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:17.142  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:17.142  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:17.142  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:17.142  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:17.142  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:17.142  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:17.142  3247  3247 D BluetoothMap: Proxy object connected
09-16 10:42:17.143  3247  3261 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 10:42:17.143  3247  3247 D MapProfile: Bluetooth service connected
09-16 10:42:17.143  3247  3247 D BluetoothMap: getConnectedDevices()
09-16 10:42:17.144  5701  5701 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 10:42:17.144  5641  5652 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 10:42:17.144  5701  5701 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 10:42:17.144  3247  5808 D BluetoothPan: onBluetoothStateChange on: true
09-16 10:42:17.144  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:17.145  3247  3247 D BluetoothInputDevice: Proxy object connected
09-16 10:42:17.145  5701  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 10:42:17.146  3247  3247 D HidProfile: Bluetooth service connected
,09-16 10:42:17.146   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:17.146   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 10:42:17.147   927   927 D BluetoothA2dp: Proxy object connected
09-16 10:42:17.148  3247  3247 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 10:42:17.148  3247  3247 D PanProfile: Bluetooth service connected
09-16 10:42:17.149  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:17.149  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:17.149  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:17.149  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:17.149  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:17.149  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:17.149  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:17.149  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:17.149  5701  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 10:42:17.150  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:17.150   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 10:42:17.152  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:17.152  5701  5701 D ObexServerSockets: Succeed to create listening sockets 
,09-16 10:42:17.152  5701  5701 D ObexServerSockets0: startAccept()
09-16 10:42:17.152  5701  5701 D ObexServerSockets0: prepareForNewConnect()
09-16 10:42:17.153  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:17.154  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:17.154  5641  5641 D LocalBluetoothProfileManager: Adding local A2DP profile
09-16 10:42:17.156  5701  5701 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 10:42:17.156  5701  5701 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 10:42:17.157  5701  5846 D ObexServerSockets0: Accepting socket connection...
09-16 10:42:17.157  5701  5701 D BluetoothMapService: onReceive
09-16 10:42:17.158  5701  5847 D ObexServerSockets0: Accepting socket connection...
09-16 10:42:17.158  5701  5701 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 10:42:17.158  5701  5701 D BluetoothMapService: STATE_ON
,09-16 10:42:17.159  5641  5641 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-16 10:42:17.160  5701  5848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 10:42:17.161  5701  5848 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 10:42:17.161  5701  5848 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-16 10:42:17.165  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 10:42:17.168  5641  5641 D BluetoothA2dp: Proxy object connected
,09-16 10:42:17.172  3709  3709 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 10:42:17.182  3247  3247 D BluetoothPbap: Proxy object connected
09-16 10:42:17.182  3247  3247 D PbapServerProfile: Bluetooth service connected
,09-16 10:42:17.183  5641  5641 D DockEventReceiver: finishStartingService: stopping service
09-16 10:42:17.184  5641  5641 D BluetoothPbap: Proxy object connected
09-16 10:42:17.184  5701  5701 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 10:42:17.184  5701  5701 D ObexServerSockets0: prepareForNewConnect()
09-16 10:42:17.185  5641  5641 D PbapServerProfile: Bluetooth service connected
,09-16 10:42:17.189  5701  5852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 10:42:17.202  5701  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 10:42:17.204  5701  5856 I BtOppRfcommListener: Accept thread started.
,09-16 10:42:17.237   927   927 D BluetoothHeadset: Proxy object connected
,09-16 10:42:17.237   927   944 D BluetoothHeadset: Proxy object connected
09-16 10:42:17.238  3247  3878 D BluetoothHeadset: Proxy object connected
09-16 10:42:17.238  3247  3247 D HeadsetProfile: Bluetooth service connected
09-16 10:42:17.238   927   927 D BluetoothHeadset: Proxy object connected
09-16 10:42:17.238   927   927 D BluetoothHeadset: Proxy object connected
,09-16 10:42:17.238  3618  3933 D BluetoothHeadset: Proxy object connected
,09-16 10:42:17.240  3618  3643 D BluetoothHeadset: Proxy object connected
,09-16 10:42:17.241  3247  5808 D BluetoothHeadset: Proxy object connected
09-16 10:42:17.241  3247  3247 D HeadsetProfile: Bluetooth service connected
,09-16 10:42:17.246   927   944 D BluetoothHeadset: Proxy object connected
,09-16 10:42:17.262  5641  5653 D BluetoothHeadset: Proxy object connected
,09-16 10:42:17.263  5641  5641 D HeadsetProfile: Bluetooth service connected
,09-16 10:42:18.949   927  3084 D ConnectivityService: handlePromptUnvalidated 101
,09-16 10:42:21.152  5701  5821 D BluetoothAdapterState: Current state: ON, message: 23
,09-16 10:42:21.152  5701  5821 D BluetoothAdapterProperties: Setting state to 13
,09-16 10:42:21.152  5701  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 10:42:21.154  5701  5821 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 10:42:21.156  5701  5821 I BluetoothAdapterState: Entering PendingCommandState
,09-16 10:42:21.161  5701  5701 D BluetoothMapService: onReceive
,09-16 10:42:21.161  5701  5701 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 10:42:21.161  5701  5701 D BluetoothMapService: STATE_TURNING_OFF
09-16 10:42:21.162  5701  5701 D BluetoothMapService: MAP Service closeService in
09-16 10:42:21.162  5701  5701 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 10:42:21.162  5701  5701 D ObexServerSockets0: shutdown(block = true)
09-16 10:42:21.164  5701  5846 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-16 10:42:21.167  5701  5825 D BluetoothAdapterProperties: Scan Mode:20
09-16 10:42:21.168  5701  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-16 10:42:21.169  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:21.170  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:21.170  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:21.170  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:21.170  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:21.170  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:21.170  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:21.170  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:21.170  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:21.170  5701  5701 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-16 10:42:21.170  5701  5701 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-16 10:42:21.171  5701  5834 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-16 10:42:21.171  5701  5847 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-16 10:42:21.174  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:21.175  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:21.178  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:21.178  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:21.178  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:21.178  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:21.178  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:21.178  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:21.178  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:21.178  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:21.178  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:21.178  5701  5701 I BtOppRfcommListener: stopping Accept Thread
09-16 10:42:21.179  5701  5856 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 10:42:21.179  5701  5856 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 10:42:21.180  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:21.180  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:21.182  5701  5701 D HeadsetService: Received stop request...Stopping profile...
09-16 10:42:21.184  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:21.184  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:21.184  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:21.184  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:21.184  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:21.184  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 10:42:21.184  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:21.184  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:21.184  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:21.184   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:21.184  3247  3262 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:21.185   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:21.185   927   927 D BluetoothHeadset: Proxy object disconnected
,09-16 10:42:21.185  5587  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 10:42:21.185  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:21.186  5701  5701 D A2dpService: Received stop request...Stopping profile...
09-16 10:42:21.186  5701  5841 D A2dpStateMachine: Exit Disconnected: -1
09-16 10:42:21.187  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:21.188  3247  3247 D HeadsetProfile: Bluetooth service disconnected
09-16 10:42:21.188  3618  3638 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:21.188  3247  3247 D BluetoothA2dp: Proxy object disconnected
09-16 10:42:21.188  5701  5701 D HidService: Received stop request...Stopping profile...
09-16 10:42:21.188  5701  5701 D HidService: Stopping Bluetooth HidService
09-16 10:42:21.189  3247  3247 D BluetoothInputDevice: Proxy object disconnected
09-16 10:42:21.189  3247  3247 D HidProfile: Bluetooth service disconnected
09-16 10:42:21.189  5641  5652 D BluetoothHeadset: Proxy object disconnected
09-16 10:42:21.189  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:21.190   927   927 D BluetoothA2dp: Proxy object disconnected
09-16 10:42:21.191  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:21.191  5701  5701 D HealthService: Received stop request...Stopping profile...
,09-16 10:42:21.192  5701  5701 D PanService: Received stop request...Stopping profile...
09-16 10:42:21.194  5701  5701 D BluetoothMapService: Received stop request...Stopping profile...
09-16 10:42:21.194  3247  3247 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 10:42:21.194  5701  5701 D BluetoothMapService: stop()
09-16 10:42:21.194  3247  3247 D PanProfile: Bluetooth service disconnected
09-16 10:42:21.195  5701  5701 D BluetoothMapAppObserver: deinitObservers()
09-16 10:42:21.195  5701  5701 D BluetoothMapAppObserver: removeReceiver()
09-16 10:42:21.196  3247  3247 D BluetoothMap: Proxy object disconnected
09-16 10:42:21.196  3247  3247 D MapProfile: Bluetooth service disconnected
,09-16 10:42:21.198  5701  5701 D SapService: Received stop request...Stopping profile...
,09-16 10:42:21.198  5701  5701 V SapService: stop()
,09-16 10:42:21.201  5701  5701 V BluetoothAdapterState: isTurningOff()=true
,09-16 10:42:21.201  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:21.202  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:21.202  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 10:42:21.203  5701  5701 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 10:42:21.203  5701  5701 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-16 10:42:21.203  5701  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:21.203  5701  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:21.203  5701  5701 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:21.203  5701  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:21.203  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:21.203  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:21.203  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:21.203  5701  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 10:42:21.203  5701  5825 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 10:42:21.204  5701  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:21.204  5701  5701 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:21.204  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:21.204  5701  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:21.204  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:21.205  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 10:42:21.205  5701  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 10:42:21.205  5701  5832 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 10:42:21.205  5701  5832 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 10:42:21.205  5701  5832 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 10:42:21.205  5701  5701 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 10:42:21.205  5701  5832 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 10:42:21.205  5701  5701 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 10:42:21.205  5701  5701 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:21.205  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:21.205  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:21.205  5701  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 10:42:21.205  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:21.206  5701  5701 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 10:42:21.206  5701  5825 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-16 10:42:21.206  5701  5701 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-16 10:42:21.206  5701  5701 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:21.206  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:21.206  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:21.206  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:21.207  5701  5701 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 10:42:21.207  5701  5701 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 10:42:21.207  5701  5701 D BluetoothMapService: MAP Service closeService in
09-16 10:42:21.207  5701  5701 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:21.207  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:21.207  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:21.208  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:21.208  5701  5701 D BluetoothMapService: cleanup()
,09-16 10:42:21.208  5701  5701 D BluetoothMapService: MAP Service closeService in
09-16 10:42:21.208  5701  5701 V BluetoothAdapterState: isTurningOff()=true
09-16 10:42:21.208  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:21.208  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:21.209  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:21.209  5701  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-16 10:42:21.209  5701  5821 D BluetoothAdapterProperties: Setting state to 15
09-16 10:42:21.209  5701  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 10:42:21.209  5701  5821 I BluetoothAdapterState: Entering BleOnState
09-16 10:42:21.210  3247  3878 D BluetoothPbap: onBluetoothStateChange: up=false
,09-16 10:42:21.213  5641  5653 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 10:42:21.214   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:21.215  3247  5808 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 10:42:21.215   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:21.216  5641  5652 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:21.217  5641  5653 D BluetoothPan: onBluetoothStateChange on: false
09-16 10:42:21.217  5641  5652 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 10:42:21.218  3618  3933 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:21.218  5641  5653 D BluetoothMap: onBluetoothStateChange: up=false
,09-16 10:42:21.219  3247  3262 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-16 10:42:21.220  3247  3261 D BluetoothMap: onBluetoothStateChange: up=false
09-16 10:42:21.220  3247  3878 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 10:42:21.221  5641  5652 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 10:42:21.221  3247  5808 D BluetoothPan: onBluetoothStateChange on: false
09-16 10:42:21.222   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 10:42:21.222   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 10:42:21.222  5701  5821 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 10:42:21.222  5701  5821 D BluetoothAdapterProperties: Setting state to 16
09-16 10:42:21.222  5701  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 10:42:21.223  5701  5821 D BluetoothAdapterProperties: onBleDisable
09-16 10:42:21.223  5701  5821 I BluetoothAdapterState: Entering PendingCommandState
09-16 10:42:21.223  5701  5822 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-16 10:42:21.225  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:21.227  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:21.227  5701  5825 D BluetoothAdapterProperties: Scan Mode:20
09-16 10:42:21.227  5701  5832 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 10:42:21.227  5701  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 10:42:21.228  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:21.230  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:21.232  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:21.233  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:21.234  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 10:42:21.238  5641  5641 D HeadsetProfile: Bluetooth service disconnected
,09-16 10:42:21.241  3709  3709 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 10:42:21.242  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,09-16 10:42:21.252  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 10:42:21.256  3709  3709 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 10:42:21.257  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,09-16 10:42:21.436  5701  5825 I bt_hci  : shut_down
,09-16 10:42:21.441  5701  5829 D bt_hwcfg: hw_epilog_process
,09-16 10:42:21.441  5701  5829 I bt_vendor: low_power_mode_cb
,09-16 10:42:21.444  5701  5829 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-16 10:42:21.444  5701  5829 I bt_vendor: epilog_cb
09-16 10:42:21.444  5701  5829 I bt_hci  : epilog_finished_callback
,09-16 10:42:21.449  5701  5825 I bt_hci_h4: hal_close
,09-16 10:42:21.450  5701  5825 I bt_userial_vendor: device fd = 54 close
,09-16 10:42:21.567  5701  5822 D bt_stack_manager: event_shut_down_stack finished.
,09-16 10:42:21.567  5701  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 10:42:21.572  5701  5821 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 10:42:21.572  5701  5701 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 10:42:21.573  5701  5701 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 10:42:21.573  5701  5701 D BtGatt.GattService: stop()
09-16 10:42:21.573  5701  5701 D BtGatt.AdvertiseManager: advertise clients cleared
,09-16 10:42:21.577  5701  5701 V BluetoothAdapterState: isTurningOff()=false
,09-16 10:42:21.577  5701  5701 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:21.577  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:21.578  5701  5701 V BluetoothAdapterState: isBleTurningOff()=true
09-16 10:42:21.578  5701  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 10:42:21.579  5701  5821 D BluetoothAdapterProperties: Setting state to 10
09-16 10:42:21.579  5701  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-16 10:42:21.580  5701  5821 I BluetoothAdapterState: Entering OffState
09-16 10:42:21.581   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-16 10:42:21.600  5701  5701 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-16 10:42:21.600  5701  5701 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-16 10:42:21.600  5701  5701 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 10:42:21.603  5701  5822 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 10:42:21.610  5701  5701 I art     : System.exit called, status: 0
,09-16 10:42:21.610  5701  5701 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 10:42:21.638   927  3639 I ActivityManager: Process com.android.bluetooth (pid 5701) has died
,09-16 10:42:26.150  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 10:42:26.150  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:42:26.156  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:42:26.156  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ff2bf removed from the list
09-16 10:42:26.156  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:42:26.157  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:26.157  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:42:26.159  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:42:26.159  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85b8cd5 added. We now have 4 listener(s)
09-16 10:42:26.159  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 10:42:26.164  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:42:26.164  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85b8cd5 removed from the list
,09-16 10:42:26.164  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:42:26.164  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:26.164  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:26.166  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:42:26.166  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a20cea added. We now have 4 listener(s)
09-16 10:42:26.167  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 10:42:31.177  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:31.213   927   944 I ActivityManager: Start proc 5866:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-16 10:42:31.329  5866  5866 D AdapterServiceConfig: Adding HeadsetService
,09-16 10:42:31.330  5866  5866 D AdapterServiceConfig: Adding A2dpService
09-16 10:42:31.330  5866  5866 D AdapterServiceConfig: Adding HidService
09-16 10:42:31.330  5866  5866 D AdapterServiceConfig: Adding HealthService
09-16 10:42:31.330  5866  5866 D AdapterServiceConfig: Adding PanService
09-16 10:42:31.331  5866  5866 D AdapterServiceConfig: Adding GattService
,09-16 10:42:31.331  5866  5866 D AdapterServiceConfig: Adding BluetoothMapService
09-16 10:42:31.331  5866  5866 D AdapterServiceConfig: Adding SapService
,09-16 10:42:31.347   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5ab095e:true
,09-16 10:42:31.347  5866  5866 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 10:42:31.352  5866  5866 I bt_bluedroid: init
,09-16 10:42:31.353  5866  5878 I BluetoothAdapterState: Entering OffState
,09-16 10:42:31.356  5866  5879 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 10:42:31.357  5866  5879 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 10:42:31.357  5866  5879 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 10:42:31.357  5866  5879 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-16 10:42:31.358  5866  5866 I bt_bluedroid: get_profile_interface socket
,09-16 10:42:31.361  5866  5866 I bt_bluedroid: get_profile_interface sdp
,09-16 10:42:31.361  5866  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 10:42:31.364  5866  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 10:42:31.367  5866  5877 I bt_bluedroid: config_hci_snoop_log
,09-16 10:42:31.369   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 10:42:31.374  5866  5878 D BluetoothAdapterState: Current state: OFF, message: 0
,09-16 10:42:31.374  5866  5878 D BluetoothAdapterProperties: Setting state to 14
09-16 10:42:31.375  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-16 10:42:31.376  5866  5878 D BluetoothBondStateMachine: make
,09-16 10:42:31.379  5866  5883 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 10:42:31.382  5866  5878 I BluetoothAdapterState: Entering PendingCommandState
,09-16 10:42:31.383  5866  5866 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 10:42:31.385  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:42:31.386  5866  5866 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 10:42:31.387  5866  5866 D BtGatt.GattService: Received start request. Starting profile...
09-16 10:42:31.387  5866  5866 D BtGatt.GattService: start()
09-16 10:42:31.387  5866  5866 I bt_bluedroid: get_profile_interface gatt
,09-16 10:42:31.388  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:42:31.388  5866  5866 D BtGatt.AdvertiseManager: advertise manager created
,09-16 10:42:31.394  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,09-16 10:42:31.395  5866  5866 V BluetoothAdapterState: isTurningOn()=false
09-16 10:42:31.395  5866  5866 V BluetoothAdapterState: isBleTurningOn()=true
09-16 10:42:31.395  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:31.395  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-16 10:42:31.396  5866  5878 I bt_bluedroid: bt_bluedroid
09-16 10:42:31.397  5866  5879 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-16 10:42:31.397  5866  5879 I bt_hci  : start_up
,09-16 10:42:31.404  5866  5879 I bt_vendor: alloc value 0xf3eeb871
,09-16 10:42:31.404  5866  5879 I bt_vendor: init
09-16 10:42:31.404  5866  5879 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 10:42:31.404  5866  5879 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 10:42:31.514  5866  5879 D bt_hci  : start_up starting async portion
09-16 10:42:31.515  5866  5886 I bt_hci  : event_finish_startup
09-16 10:42:31.515  5866  5886 I bt_hci_h4: hal_open
09-16 10:42:31.515  5866  5886 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 10:42:31.512  5887  5887 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 10:42:31.517  5866  5886 I bt_userial_vendor: device fd = 54 open
,09-16 10:42:31.532  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 10:42:31.535  5866  5886 D bt_hwcfg: Chipset BCM4358A3
,09-16 10:42:31.535  5866  5886 D bt_hwcfg: Target name = [BCM4358A3]
09-16 10:42:31.535  5866  5886 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 10:42:31.842   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:32.046  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 10:42:32.047  5866  5886 D bt_hwcfg: Settlement delay -- 100 ms
09-16 10:42:32.047  5866  5886 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 10:42:32.181  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 10:42:32.181  5866  5886 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-16 10:42:32.185  5866  5886 I bt_hwcfg: vendor lib fwcfg completed
,09-16 10:42:32.185  5866  5886 I bt_vendor: firmware callback
09-16 10:42:32.185  5866  5886 I bt_hci  : firmware_config_callback
,09-16 10:42:32.194  5866  5889 I bt_btu  : btu_task pending for preload complete event
,09-16 10:42:32.195  5866  5889 I bt_btu_task: Bluetooth chip preload is complete
09-16 10:42:32.196  5866  5889 I bt_btu  : btu_task received preload complete event
,09-16 10:42:32.203  5866  5889 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 10:42:32.203  5866  5889 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 10:42:32.203  5866  5889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 10:42:32.203  5866  5889 I         : BTE_InitTraceLevels -- TRC_AVDT
09-16 10:42:32.203  5866  5889 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-16 10:42:32.203  5866  5889 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 10:42:32.203  5866  5889 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 10:42:32.203  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTM
,09-16 10:42:32.204  5866  5889 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 10:42:32.204  5866  5889 I         : BTE_InitTraceLevels -- TRC_PAN
,09-16 10:42:32.204  5866  5889 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 10:42:32.204  5866  5889 I         : BTE_InitTraceLevels -- TRC_GATT
,09-16 10:42:32.204  5866  5889 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 10:42:32.204  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-16 10:42:32.204  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 10:42:32.302  5866  5889 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e69549
,09-16 10:42:32.302  5866  5889 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e69549 
,09-16 10:42:32.336  5866  5882 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 10:42:32.339  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 10:42:32.339  5866  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-16 10:42:32.342  5866  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 10:42:32.345  5866  5882 D BluetoothAdapterProperties: Scan Mode:20
09-16 10:42:32.345  5866  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 10:42:32.346  5866  5882 D bt_hci  : do_postload posting postload work item
09-16 10:42:32.346  5866  5886 I bt_hci  : event_postload
,09-16 10:42:32.346  5866  5886 I bt_vendor: sco_config_cb
09-16 10:42:32.346  5866  5886 I bt_hci  : sco_config_callback postload finished.
09-16 10:42:32.349  5866  5882 D bt_bte_conf: Device ID record 1 : primary
09-16 10:42:32.349  5866  5882 D bt_bte_conf:   vendorId            = 000f
,09-16 10:42:32.349  5866  5882 D bt_bte_conf:   vendorIdSource      = 0001
09-16 10:42:32.349  5866  5882 D bt_bte_conf:   product             = 1200
09-16 10:42:32.349  5866  5882 D bt_bte_conf:   version             = 1436
09-16 10:42:32.350  5866  5882 D bt_bte_conf:   clientExecutableURL = 
09-16 10:42:32.350  5866  5882 D bt_bte_conf:   serviceDescription  = 
09-16 10:42:32.350  5866  5882 D bt_bte_conf:   documentationURL    = 
09-16 10:42:32.350  5866  5882 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 10:42:32.350  5866  5879 D bt_stack_manager: event_start_up_stack finished
09-16 10:42:32.351  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-16 10:42:32.352  5866  5878 D BluetoothAdapterProperties: Setting state to 15
09-16 10:42:32.352  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-16 10:42:32.352  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:32.354  5866  5878 I BluetoothAdapterState: Entering BleOnState
,09-16 10:42:32.357  5866  5886 I bt_vendor: low_power_mode_cb
,09-16 10:42:32.357  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:32.361  5866  5878 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-16 10:42:32.361  5866  5878 D BluetoothAdapterProperties: Setting state to 11
09-16 10:42:32.361  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-16 10:42:32.367  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:32.368  5866  5866 D HeadsetService: Received start request. Starting profile...
09-16 10:42:32.371  5866  5866 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 10:42:32.371  5866  5866 D HeadsetStateMachine: make
09-16 10:42:32.372  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:32.381  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:32.383  5866  5866 D HeadsetStateMachine: max_hf_connections = 1
09-16 10:42:32.383  5866  5866 I bt_bluedroid: get_profile_interface handsfree
09-16 10:42:32.384  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 10:42:32.385  5866  5882 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-16 10:42:32.387  5866  5878 I BluetoothAdapterState: Entering PendingCommandState
09-16 10:42:32.388  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:32.389  5866  5866 D A2dpService: Received start request. Starting profile...
,09-16 10:42:32.389  5866  5866 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 10:42:32.390  5866  5866 I bt_bluedroid: get_profile_interface avrcp
,09-16 10:42:32.396  5866  5866 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 10:42:32.396  5866  5866 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 10:42:32.396  5866  5866 D A2dpStateMachine: make
09-16 10:42:32.397  5866  5866 I bt_bluedroid: get_profile_interface a2dp
,09-16 10:42:32.398  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-16 10:42:32.399  5866  5898 D A2dpStateMachine: Enter Disconnected: -2
,09-16 10:42:32.400  5866  5866 I BluetoothHidServiceJni: classInitNative: succeeds
,09-16 10:42:32.401  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:42:32.402  5866  5866 D HidService: Received start request. Starting profile...
,09-16 10:42:32.403  5866  5866 I bt_bluedroid: get_profile_interface hidhost
,09-16 10:42:32.403  5866  5882 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e4a56d
09-16 10:42:32.403  5866  5866 D HidService: setHidService(): set to: null
09-16 10:42:32.403  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-16 10:42:32.405  5866  5866 I BluetoothHealthServiceJni: classInitNative: succeeds
09-16 10:42:32.405  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:42:32.406  5866  5866 D HealthService: Received start request. Starting profile...
09-16 10:42:32.406  3709  3709 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 10:42:32.407  5866  5866 I bt_bluedroid: get_profile_interface health
,09-16 10:42:32.409  5866  5866 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-16 10:42:32.410  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:32.410  5866  5866 D PanService: Received start request. Starting profile...
,09-16 10:42:32.411  5866  5866 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 10:42:32.411  5866  5866 I bt_bluedroid: get_profile_interface pan
09-16 10:42:32.411  5866  5882 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-16 10:42:32.413  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:42:32.414  5866  5866 D BluetoothMapService: Received start request. Starting profile...
09-16 10:42:32.414  5866  5866 D BluetoothMapService: start()
,09-16 10:42:32.416  5866  5866 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 10:42:32.416  5866  5866 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-16 10:42:32.416  5866  5866 D BluetoothMapAppObserver: createReceiver()
,09-16 10:42:32.417  5866  5866 D BluetoothMapAppObserver: initObservers()
09-16 10:42:32.417  5866  5866 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 10:42:32.421  5866  5866 V SapService: SapBinder()
,09-16 10:42:32.421  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
09-16 10:42:32.421  5866  5866 D SapService: Received start request. Starting profile...
09-16 10:42:32.421  5866  5866 V SapService: start()
,09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,09-16 10:42:32.422  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:32.423  5866  5894 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:32.423  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:32.424  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-16 10:42:32.424  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-16 10:42:32.424  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-16 10:42:32.424  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-16 10:42:32.424  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-16 10:42:32.424  5866  5878 D BluetoothAdapterProperties: ScanMode =  20
09-16 10:42:32.424  5866  5878 D BluetoothAdapterProperties: State =  11
09-16 10:42:32.424  5866  5878 D BluetoothAdapterProperties: Setting state to 12
09-16 10:42:32.424  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 10:42:32.425  3247  5808 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 10:42:32.427  5866  5882 D BluetoothAdapterProperties: Scan Mode:21
09-16 10:42:32.427  5866  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 10:42:32.427  5866  5878 I BluetoothAdapterState: Entering OnState
,09-16 10:42:32.428  5641  5653 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-16 10:42:32.433   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 10:42:32.433  3247  3262 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 10:42:32.433  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:32.433  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:32.433  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:32.433  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:32.433  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:32.433  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:32.433  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:32.433  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:32.435  3247  3247 D BluetoothA2dp: Proxy object connected
,09-16 10:42:32.435   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:32.436  5641  5653 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:32.436  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:32.436  5641  5652 D BluetoothPan: onBluetoothStateChange on: true
,09-16 10:42:32.439  5641  5653 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 10:42:32.441  5866  5866 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 10:42:32.441  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:32.441  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:32.441  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:32.441  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:32.441  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:32.441  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:32.441  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:32.441  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 10:42:32.441  3618  3643 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:32.441  5866  5866 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 10:42:32.441  5641  5652 D BluetoothMap: onBluetoothStateChange: up=true
09-16 10:42:32.442  5866  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 10:42:32.443  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:32.444  3247  3878 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:32.444  5641  5641 D BluetoothA2dp: Proxy object connected
,09-16 10:42:32.444  5866  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 10:42:32.445  3247  3261 D BluetoothMap: onBluetoothStateChange: up=true
09-16 10:42:32.446  5866  5866 D ObexServerSockets: Succeed to create listening sockets 
09-16 10:42:32.446  5866  5866 D ObexServerSockets0: startAccept()
09-16 10:42:32.446  5866  5866 D ObexServerSockets0: prepareForNewConnect()
09-16 10:42:32.446  3247  3262 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 10:42:32.447  5866  5866 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 10:42:32.447  5866  5866 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 10:42:32.447  5641  5653 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 10:42:32.448  3247  3247 D BluetoothMap: Proxy object connected
09-16 10:42:32.448  3247  3247 D MapProfile: Bluetooth service connected
09-16 10:42:32.448  3247  3247 D BluetoothMap: getConnectedDevices()
,09-16 10:42:32.448  5866  5904 D ObexServerSockets0: Accepting socket connection...
,09-16 10:42:32.449  5866  5905 D ObexServerSockets0: Accepting socket connection...
09-16 10:42:32.449  3247  3261 D BluetoothPan: onBluetoothStateChange on: true
09-16 10:42:32.450  3247  3247 D BluetoothInputDevice: Proxy object connected
,09-16 10:42:32.450  3247  3247 D HidProfile: Bluetooth service connected
09-16 10:42:32.452  3247  3247 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 10:42:32.452  3247  3247 D PanProfile: Bluetooth service connected
09-16 10:42:32.452   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 10:42:32.452   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 10:42:32.453   927   927 D BluetoothA2dp: Proxy object connected
09-16 10:42:32.454  5866  5866 D BluetoothMapService: onReceive
09-16 10:42:32.454  5866  5866 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 10:42:32.454  5866  5866 D BluetoothMapService: STATE_ON
09-16 10:42:32.455  5641  5641 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 10:42:32.455   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 10:42:32.455  5641  5641 D PanProfile: Bluetooth service connected
09-16 10:42:32.455  5641  5641 D BluetoothMap: Proxy object connected
09-16 10:42:32.455  5641  5641 D MapProfile: Bluetooth service connected
,09-16 10:42:32.455  5641  5641 D BluetoothMap: getConnectedDevices()
09-16 10:42:32.456  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:32.457  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:42:32.457  5866  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 10:42:32.459  5866  5906 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 10:42:32.459  5866  5906 D BluetoothSdpJni: SDP Create record success - handle: 1
09-16 10:42:32.459  5641  5641 D BluetoothInputDevice: Proxy object connected
09-16 10:42:32.459  5641  5641 D HidProfile: Bluetooth service connected
,09-16 10:42:32.464  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 10:42:32.471  3709  3709 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 10:42:32.471  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,09-16 10:42:32.477  5641  5641 D BluetoothPbap: Proxy object connected
,09-16 10:42:32.477  5641  5641 D PbapServerProfile: Bluetooth service connected
09-16 10:42:32.477  3247  3247 D BluetoothPbap: Proxy object connected
09-16 10:42:32.477  3247  3247 D PbapServerProfile: Bluetooth service connected
09-16 10:42:32.477  5866  5866 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 10:42:32.477  5866  5866 D ObexServerSockets0: prepareForNewConnect()
,09-16 10:42:32.484  5866  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 10:42:32.496  5866  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 10:42:32.497  5866  5914 I BtOppRfcommListener: Accept thread started.
,09-16 10:42:32.533   927   927 D BluetoothHeadset: Proxy object connected
,09-16 10:42:32.534  3247  3262 D BluetoothHeadset: Proxy object connected
09-16 10:42:32.534  3247  3247 D HeadsetProfile: Bluetooth service connected
09-16 10:42:32.534   927   927 D BluetoothHeadset: Proxy object connected
09-16 10:42:32.534   927   927 D BluetoothHeadset: Proxy object connected
,09-16 10:42:32.534  3618  3638 D BluetoothHeadset: Proxy object connected
,09-16 10:42:32.535  5641  5653 D BluetoothHeadset: Proxy object connected
09-16 10:42:32.536   927   944 D BluetoothHeadset: Proxy object connected
09-16 10:42:32.537  5641  5903 D BluetoothHeadset: Proxy object connected
09-16 10:42:32.538  5641  5641 D HeadsetProfile: Bluetooth service connected
,09-16 10:42:32.539  5641  5641 D HeadsetProfile: Bluetooth service connected
,09-16 10:42:32.542  3618  3933 D BluetoothHeadset: Proxy object connected
,09-16 10:42:32.543  3247  3878 D BluetoothHeadset: Proxy object connected
,09-16 10:42:32.544  3247  3247 D HeadsetProfile: Bluetooth service connected
,09-16 10:42:32.553   927   944 D BluetoothHeadset: Proxy object connected
,09-16 10:42:32.843   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:33.844   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:34.845   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:35.846   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:36.192  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:36.192  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:36.192  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:36.192  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 10:42:36.192  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:36.192  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:36.192  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:36.192  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 10:42:36.197  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 10:42:36.198  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:42:36.199  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a20cea removed from the list
,09-16 10:42:36.199  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 10:42:36.199  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:36.199  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:36.201  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:42:36.201  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ceafbdb added. We now have 4 listener(s)
09-16 10:42:36.201  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 10:42:36.205   927  3509 D WifiService: setWifiEnabled: false pid=5587, uid=10077
09-16 10:42:36.206   927  3509 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 10:42:36.847   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:42:41.218  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:41.221   927  3895 D WifiService: setWifiEnabled: true pid=5587, uid=10077
,09-16 10:42:41.221   927  3895 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 10:42:41.229   506   920 D SoftapController: Softap fwReload - Ok
,09-16 10:42:41.235   506   920 D CommandListener: Setting iface cfg
09-16 10:42:41.235   506   920 D CommandListener: Trying to bring down wlan0
,09-16 10:42:41.237   506   920 D CommandListener: Clearing all IP addresses on wlan0
,09-16 10:42:41.245   927  3082 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 10:42:41.919   927  3082 D wifi    : set interface wlan0 flags (UP)
09-16 10:42:41.923   927  3082 I WifiHAL : Initializing wifi
09-16 10:42:41.923   927  3082 I WifiHAL : Creating socket
09-16 10:42:41.924   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 10:42:41.929   927  3082 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-16 10:42:41.930   927  3082 D wifi    : Did set static halHandle = 0x7f60c1cd80
09-16 10:42:41.930   927  3082 D wifi    : halHandle = 0x7f60c1cd80, mVM = 0x7f7d28d140, mCls = 0x10180a
,09-16 10:42:41.930   927  3082 D wifi    : array field set
09-16 10:42:41.930   927  3082 I WifiNative-HAL: interface[0] = wlan0
09-16 10:42:41.933   927  5919 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547084160384
09-16 10:42:41.933   927  5919 D wifi    : waitForHalEvents called, vm = 0x7f7d28d140, obj = 0x10180a, env = 0x7f62ec94c0
,09-16 10:42:41.995  5920  5920 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 10:42:42.017  5920  5920 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 10:42:42.035   927  3082 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 10:42:42.044  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:42.048  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:42.056  5920  5920 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-16 10:42:42.056  5920  5920 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 10:42:42.077   927  3082 D WifiConfigStore: Loading config and enabling all networks 
,09-16 10:42:42.081  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:42.081  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:42.081  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:42.081  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:42.081  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:42.081  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:42.081  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:42.081  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 10:42:42.083  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 10:42:42.086  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:42.086  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:42.086  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:42.086  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:42.086  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:42.086  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 10:42:42.086  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 10:42:42.086  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 10:42:42.089  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 10:42:42.093   927  3082 D WifiConfigStore: loaded 0 passpoint configs
,09-16 10:42:42.093   927  3082 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 10:42:42.093   927  3082 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 10:42:42.094   927  3082 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 10:42:42.095   927  3082 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-16 10:42:42.095   927  3082 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 10:42:42.096   927  3082 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-16 10:42:42.096   927  3082 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 10:42:42.099   927  3082 D WifiNative-HAL: Setting external_sim to 1
,09-16 10:42:42.099  4408  4408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 10:42:42.099   927  3082 D wifi    : setting dfs flag to true, 0x7f629aef80
09-16 10:42:42.099   927  3082 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 10:42:42.099   927  3082 D wifi    : setting scan oui 0x7f629aef80
09-16 10:42:42.100   927  3082 D WifiHAL : Sending mac address OUI
,09-16 10:42:42.103   927  3082 E native  : do suspend false
,09-16 10:42:42.113   927  3082 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-16 10:42:42.114   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 10:42:42.114   927   927 D RttService: SCAN_AVAILABLE : 3
09-16 10:42:42.114   927  3190 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 10:42:42.115   506   920 D CommandListener: Setting iface cfg
,09-16 10:42:42.119   927  3081 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,09-16 10:42:42.119   927  3081 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 10:42:42.129   927  3081 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 10:42:42.134   927  3081 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 10:42:42.134   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=399079 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-16 10:42:45.320  5920  5920 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 10:42:45.329  5920  5920 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 10:42:45.335  5920  5920 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 10:42:45.340  5920  5920 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 10:42:45.364   927  3082 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-16 10:42:45.366   927  3082 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-16 10:42:45.366   927  3082 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 10:42:45.378   927  3082 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 10:42:45.410   927  3082 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 10:42:45.413  5920  5920 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 10:42:45.854  5920  5920 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 10:42:45.889  5920  5920 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 10:42:45.890  5920  5920 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 10:42:45.896   927  3082 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 10:42:45.896   927  3082 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 10:42:45.896   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-16 10:42:45.909   927  3082 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 10:42:45.918   506   920 D CommandListener: Setting iface cfg
,09-16 10:42:45.923   927  3082 D WifiStateMachine: Start Dhcp Watchdog 3
,09-16 10:42:45.930   927  5925 D DhcpClient: Receive thread started
,09-16 10:42:45.933   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:42:45.933   927  3082 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-16 10:42:45.933   927  3084 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-16 10:42:46.013   927  3082 E native  : do suspend false
,09-16 10:42:46.025   927  5924 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 10:42:46.044   927  5925 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-16 10:42:46.044   927  5924 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-16 10:42:46.047   927  5924 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 10:42:46.061   927  5925 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 10:42:46.061   927  5924 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-16 10:42:46.065   506   920 D CommandListener: Setting iface cfg
,09-16 10:42:46.070   927  3082 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 10:42:46.074   927  5924 D DhcpClient: Scheduling renewal in 86399s
,09-16 10:42:46.085   927  3082 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-16 10:42:46.087   927  3082 D WifiConfigStore: No blacklist allowed without epno enabled
,09-16 10:42:46.089   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-16 10:42:46.091   927  3084 D ConnectivityService: Adding iface wlan0 to network 102
,09-16 10:42:46.097   927  3082 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 10:42:46.146   927  3084 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-16 10:42:46.146   927  3084 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-16 10:42:46.149   927  3084 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-16 10:42:46.151   927  3084 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-16 10:42:46.153   927  3084 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-16 10:42:46.160   927  3084 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:42:46.165   927  3084 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-16 10:42:46.166   927  3084 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-16 10:42:46.166   927  3084 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-16 10:42:46.166   927  3084 D ConnectivityService:    accepting network in place of null
,09-16 10:42:46.166   927  3082 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-16 10:42:46.166   927  3082 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 10:42:46.167   927  3084 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 10:42:46.172   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=403117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:42:46.192   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 10:42:46.215   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 10:42:46.218   927  3084 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-16 10:42:46.218   927  3084 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-16 10:42:46.218  3576  3745 W QCNEJ   : |CORE| network available: 102
,09-16 10:42:46.220   927  3084 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-16 10:42:46.220   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-16 10:42:46.224  3576  3745 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-16 10:42:46.225  3576  3745 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-16 10:42:46.225  3576  3745 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-16 10:42:46.232  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:46.232  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:46.232  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:46.232  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:46.232  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:46.232  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:46.232  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:46.232  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:42:46.235  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:46.235  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:46.235  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:46.235  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:46.235  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:46.235  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:46.235  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:46.235  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:42:46.237  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:46.239  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:46.239  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:42:46.239  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ceafbdb removed from the list
09-16 10:42:46.239  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:42:46.239  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:46.239  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:46.240  5012  5028 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 10:42:46.240   927  5922 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-16 10:42:46.240  5012  5028 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 10:42:46.240  5012  5028 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-16 10:42:46.240  5012  5028 E SarControlService: no key has been found,reset the power
09-16 10:42:46.241  5012  5051 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 10:42:46.241  5012  5051 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 10:42:46.241  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 10:42:46.241  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:46.241  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:46.241  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:46.241  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:46.241  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:46.241  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:46.241  5587  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:46.241  5012  5051 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 10:42:46.241  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 10:42:46.241  5039  5039 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 10:42:46.243  4922  4922 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-16 10:42:46.243  5587  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:46.243  5587  5934 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-16 10:42:46.243  5587  5934 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-16 10:42:46.244  5012  5051 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 10:42:46.244  5012  5051 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 10:42:46.244  5012  5051 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 10:42:46.244  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 10:42:46.244  5039  5039 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 10:42:46.250  5039  5055 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@412138e HexData = [00000000f003000000000000ffffffff]
09-16 10:42:46.250  5039  5055 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 10:42:46.250  5039  5055 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-16 10:42:46.251  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 10:42:46.251  5012  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 10:42:46.254  5039  5055 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@412138e HexData = [00000000f103000000000000ffffffff]
09-16 10:42:46.254  5039  5055 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 10:42:46.254  5039  5055 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-16 10:42:46.255  5039  5039 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 10:42:46.256  5012  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 10:42:46.268  4026  4026 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-16 10:42:46.283  4026  4026 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 10:42:46.285  4026  4026 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-16 10:42:46.286  5715  5715 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-16 10:42:46.290  5715  5715 D SprintDMHelper: simOperator: 
09-16 10:42:46.290  5715  5715 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-16 10:42:46.297   927  5922 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 14:42:46 GMT], X-Android-Received-Millis=[1474036966294], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474036966263]}
09-16 10:42:46.297   927  3084 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-16 10:42:46.297   927  3084 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-16 10:42:46.298   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-16 10:42:46.299   927  3084 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 10:42:46.323  4026  5358 I iu.UploadsManager: num queued entries: 0
09-16 10:42:46.324  4026  5358 I iu.UploadsManager: num updated entries: 0
,09-16 10:42:46.325  4026  5358 I iu.SyncManager: NEXT; no task
,09-16 10:42:46.402  4408  5941 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-16 10:42:48.954   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:42:49.253  5587  5947 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-16 10:42:49.253  5587  5934 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-16 10:42:49.254  5587  5934 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-16 10:42:49.254  5587  5947 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-16 10:42:49.254  5587  5934 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 10:42:49.255  5587  5947 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 10:42:49.255  5587  5934 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 10:42:49.257  5587  5947 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 10:42:49.260  5587  5949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: OutgoingSocketThread/Sender)
,09-16 10:42:49.260  5587  5934 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-16 10:42:49.262  5587  5947 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-16 10:42:49.266  5587  5950 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: IncomingSocketThread/Sender)
,09-16 10:42:49.267  5587  5951 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Receiver)
09-16 10:42:49.267  5587  5952 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver)
09-16 10:42:49.268  5587  5951 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: OutgoingSocketThread/Receiver)
,09-16 10:42:49.268  5587  5951 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-16 10:42:49.268  5587  5951 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-16 10:42:49.268  5587  5952 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver)
09-16 10:42:49.269  5587  5952 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-16 10:42:49.269  5587  5952 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-16 10:42:52.251  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-16 10:42:52.253  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-16 10:42:52.258  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a1722f2 Bundle[{}]
,09-16 10:42:52.260  5587  5633 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 10:42:52.260  5587  5633 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-16 10:42:52.262  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-16 10:42:52.263  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-16 10:42:52.264  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-16 10:42:52.265  5587  5633 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-16 10:42:52.270  5587  5633 I System.out: Running OutgoingSocketThread
,09-16 10:42:52.273  5587  5953 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-16 10:42:52.273  5587  5953 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-16 10:42:54.171   927  3084 D ConnectivityService: handlePromptUnvalidated 102
,09-16 10:42:55.284  5587  5954 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-16 10:42:55.284  5587  5953 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-16 10:42:55.284  5587  5953 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-16 10:42:55.284  5587  5954 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-16 10:42:55.284  5587  5953 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 10:42:55.284  5587  5954 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 10:42:55.287  5587  5954 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 10:42:55.288  5587  5953 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 10:42:55.293  5587  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Sender)
09-16 10:42:55.294  5587  5954 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-16 10:42:55.294  5587  5953 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-16 10:42:55.297  5587  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
,09-16 10:42:55.297  5587  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: OutgoingSocketThread/Receiver)
,09-16 10:42:55.299  5587  5959 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: OutgoingSocketThread/Receiver)
,09-16 10:42:55.299  5587  5959 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-16 10:42:55.299  5587  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-16 10:42:55.299  5587  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Receiver)
09-16 10:42:55.301  5587  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: IncomingSocketThread/Receiver)
09-16 10:42:55.301  5587  5958 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-16 10:42:55.301  5587  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-16 10:42:56.848   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:57.130   927  3082 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 22, 23 -> obsolete
,09-16 10:42:57.850   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:58.282  5587  5633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-16 10:42:58.284  5587  5633 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-16 10:42:58.284  5587  5633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
09-16 10:42:58.289  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 10:42:58.290  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2c2678 added. We now have 3 listener(s)
,09-16 10:42:58.293  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:42:58.294  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 10:42:58.294  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 10:42:58.294  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 10:42:58.294  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2552151 added. We now have 4 listener(s)
09-16 10:42:58.294  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 10:42:58.296  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 10:42:58.301  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:42:58.308  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:42:58.308  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:58.308  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:58.308  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:58.308  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:58.308  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:58.308  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:58.308  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:42:58.310  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:42:58.311  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:42:58.311  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:42:58.311  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:42:58.311  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:42:58.311  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:42:58.312  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:58.312  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:42:58.312  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 10:42:58.312  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2c2678 removed from the list
09-16 10:42:58.312  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:42:58.312  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2552151 removed from the list
,09-16 10:42:58.314  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:58.317  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:58.318  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 10:42:58.318  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:58.319  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:58.319  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:58.321  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:42:58.321  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:42:58.321  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:42:58.321  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2552151 not in the list
09-16 10:42:58.321  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:58.321  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:58.322  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:42:58.322  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:42:58.322  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:42:58.322  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2552151 not in the list
09-16 10:42:58.322  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:42:58.323  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:58.323  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:42:58.323  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2c2678 not in the list
09-16 10:42:58.323  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 10:42:58.323  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6137ab7 added. We now have 3 listener(s)
09-16 10:42:58.325  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:42:58.326  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 10:42:58.326  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 10:42:58.326  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:42:58.326  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6393224 added. We now have 4 listener(s)
09-16 10:42:58.326  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:42:58.327  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 10:42:58.331  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:42:58.337  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:42:58.337  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:42:58.337  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:42:58.337  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:42:58.337  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:42:58.337  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:42:58.337  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:42:58.337  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:42:58.339  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:42:58.339  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:42:58.340  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:42:58.340  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 10:42:58.340  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 10:42:58.340  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:42:58.340  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 10:42:58.342  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:58.344  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 10:42:58.344  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 10:42:58.346  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:42:58.348  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 10:42:58.349  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 10:42:58.349  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 10:42:58.352  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 10:42:58.352  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 10:42:58.353  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 10:42:58.353  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:42:58.358  5866  5896 D BtGatt.GattService: registerClient() - UUID=cdcf437d-bdbe-41c3-a88f-5bca387e255e
09-16 10:42:58.359  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=cdcf437d-bdbe-41c3-a88f-5bca387e255e, clientIf=5
,09-16 10:42:58.359  5587  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 10:42:58.360  5866  5876 D BtGatt.GattService: start scan with filters
,09-16 10:42:58.364  5866  5885 D BtGatt.ScanManager: handling starting scan
09-16 10:42:58.364  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 10:42:58.364  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 10:42:58.364  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 10:42:58.364  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 10:42:58.366  5866  5885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e16fda7
,09-16 10:42:58.366  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:42:58.367  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 10:42:58.367  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:42:58.368  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 10:42:58.371  5587  5633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 10:42:58.371  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 10:42:58.371  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 10:42:58.371  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:42:58.371  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 10:42:58.371  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 10:42:58.371  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 10:42:58.371  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 10:42:58.371  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:42:58.371  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 10:42:58.371  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 10:42:58.372  5587  5633 D BluetoothAdapter: STATE_ON
09-16 10:42:58.373  5866  5877 D BtGatt.GattService: stopScan() - queue size =1
09-16 10:42:58.373  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 10:42:58.373  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:42:58.374  5866  5895 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 10:42:58.374  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 10:42:58.374  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 10:42:58.375  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 10:42:58.375  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 10:42:58.375  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 10:42:58.375  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 10:42:58.376  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:42:58.376  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 10:42:58.376  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 10:42:58.376  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 10:42:58.377  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:42:58.378  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:42:58.378  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:42:58.378  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:42:58.380  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 10:42:58.381  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:42:58.381  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
09-16 10:42:58.381  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 10:42:58.391  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 10:42:58.391  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:42:58.397  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 10:42:58.397  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:42:58.404  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 10:42:58.404  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:42:58.405  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
,09-16 10:42:58.410  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 10:42:58.410  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:42:58.410  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 10:42:58.415  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 10:42:58.415  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:42:58.851   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:42:58.879  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 10:42:58.880  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:42:58.880  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:42:59.852   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:00.853   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:01.378  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 10:43:01.379  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:43:01.379  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:43:01.379  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 10:43:01.380  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:43:01.380  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 10:43:01.380  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-16 10:43:01.380  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6137ab7 removed from the list
09-16 10:43:01.380  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:01.380  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6393224 removed from the list
,09-16 10:43:01.381  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 10:43:01.381  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:43:01.383  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:01.383  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:43:01.386  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:43:01.386  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 10:43:01.386  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:01.386  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6393224 not in the list
09-16 10:43:01.387  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:43:01.387  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:43:01.392  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 10:43:01.392  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:43:01.393  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:01.393  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6393224 not in the list
09-16 10:43:01.393  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:43:01.393  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:43:01.393  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:01.394  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6137ab7 not in the list
09-16 10:43:01.395  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 10:43:01.396  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@409a989 added. We now have 3 listener(s)
09-16 10:43:01.399  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:43:01.399  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 10:43:01.399  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 10:43:01.400  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:43:01.400  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb1d8e added. We now have 4 listener(s)
09-16 10:43:01.400  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:43:01.402  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 10:43:01.407  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:43:01.415  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:43:01.415  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:43:01.415  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:43:01.415  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:43:01.415  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:43:01.415  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:01.415  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:43:01.415  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:43:01.419  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:43:01.419  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:43:01.420  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 10:43:01.421  5587  5633 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-16 10:43:01.421  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-16 10:43:01.421  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 10:43:01.422  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 10:43:01.422  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 10:43:01.422  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:43:01.423  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 10:43:01.424  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-16 10:43:01.425  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 10:43:01.425  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 10:43:01.425  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-16 10:43:01.425  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:43:01.425  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 10:43:01.426  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:43:01.427  5587  5960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 10:43:01.431  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 10:43:01.431  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 10:43:01.432  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:43:01.433  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-16 10:43:01.432  5877  5877 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33857]" dev="sockfs" ino=33857 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 10:43:01.436  5587  5960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 10:43:01.432  5877  5877 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33857]" dev="sockfs" ino=33857 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 10:43:01.437  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 10:43:01.439  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-16 10:43:01.439  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 10:43:01.442  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-16 10:43:01.442  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 10:43:01.443  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-16 10:43:01.444  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 10:43:01.444  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 10:43:01.444  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-16 10:43:01.445  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:43:01.451  5866  5876 D BtGatt.GattService: registerClient() - UUID=91046a46-c4ab-470d-820a-33a34d2b1d27
09-16 10:43:01.451  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=91046a46-c4ab-470d-820a-33a34d2b1d27, clientIf=5
,09-16 10:43:01.451  5587  5598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 10:43:01.454  5866  5884 D BtGatt.AdvertiseManager: message : 0
,09-16 10:43:01.457  5866  5884 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 10:43:01.470  5866  5882 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 10:43:01.477  5866  5882 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 10:43:01.478  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-16 10:43:01.479  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 10:43:01.481  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 10:43:01.482  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-16 10:43:01.482  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 10:43:01.483  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 10:43:01.483  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 10:43:01.483  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 10:43:01.483  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-16 10:43:01.485  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-16 10:43:01.487  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 10:43:01.487  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 10:43:01.854   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:43:01.988  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 10:43:01.989  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 10:43:01.989  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:43:04.487  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 10:43:04.487  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-16 10:43:04.488  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 10:43:04.488  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 10:43:04.488  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 10:43:04.488  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 10:43:04.489  5587  5960 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-16 10:43:04.489  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 10:43:04.489  5587  5960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 10:43:04.489  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 10:43:04.489  5587  5960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 10:43:04.489  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 10:43:04.490  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 10:43:04.490  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 10:43:04.490  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 10:43:04.490  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:43:04.490  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 10:43:04.493  5587  5633 D BluetoothAdapter: STATE_ON
09-16 10:43:04.493  5587  5633 D BluetoothLeScanner: could not find callback wrapper
09-16 10:43:04.493  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 10:43:04.493  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-16 10:43:04.495  5866  5884 D BtGatt.AdvertiseManager: message : 1
,09-16 10:43:04.497  5866  5884 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 10:43:04.511  5866  5882 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 10:43:04.512  5866  5882 D BtGatt.GattService: Client app is not null!
,09-16 10:43:04.515  5866  5895 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 10:43:04.516  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 10:43:04.516  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 10:43:04.516  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-16 10:43:04.516  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-16 10:43:04.517  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-16 10:43:04.521  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:43:04.522  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 10:43:04.522  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 10:43:04.523  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:43:04.525  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:43:04.525  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 10:43:04.525  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:04.526  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:43:04.526  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 10:43:04.526  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@409a989 removed from the list
09-16 10:43:04.526  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:04.526  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:43:04.526  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb1d8e removed from the list
,09-16 10:43:04.526  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:43:04.526  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:43:04.526  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:43:04.527  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:04.527  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:04.528  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:04.530  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:43:04.530  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:43:04.531  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:04.531  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb1d8e not in the list
09-16 10:43:04.531  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:04.531  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:04.533  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:43:04.533  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 10:43:04.533  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:04.533  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb1d8e not in the list
09-16 10:43:04.533  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:43:04.533  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:04.533  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:04.533  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@409a989 not in the list
09-16 10:43:04.534  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 10:43:04.534  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4de91cb added. We now have 3 listener(s)
,09-16 10:43:04.537  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 10:43:04.537  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 10:43:04.537  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 10:43:04.538  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:43:04.538  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1321da8 added. We now have 4 listener(s)
,09-16 10:43:04.538  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:43:04.539  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 10:43:04.543  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:43:04.549  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:43:04.549  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:43:04.549  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:43:04.549  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:43:04.549  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:43:04.549  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:04.549  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:43:04.549  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:43:04.552  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:04.552  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:43:04.553  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:43:04.553  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 10:43:04.553  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 10:43:04.553  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:43:04.553  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 10:43:04.557  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:43:04.559  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 10:43:04.559  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 10:43:04.561  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:43:04.565  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 10:43:04.566  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 10:43:04.566  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 10:43:04.571  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 10:43:04.572  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 10:43:04.572  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 10:43:04.573  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:43:04.577  5866  5896 D BtGatt.GattService: registerClient() - UUID=4c4feb41-423c-4228-8934-8edf3f40bfc8
,09-16 10:43:04.578  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=4c4feb41-423c-4228-8934-8edf3f40bfc8, clientIf=5
09-16 10:43:04.578  5587  5597 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 10:43:04.579  5866  5895 D BtGatt.GattService: start scan with filters
,09-16 10:43:04.582  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 10:43:04.583  5866  5885 D BtGatt.ScanManager: handling starting scan
09-16 10:43:04.583  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 10:43:04.583  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 10:43:04.583  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 10:43:04.587  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 10:43:04.587  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 10:43:04.587  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:43:04.590  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 10:43:04.591  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-16 10:43:04.591  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:43:04.591  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 10:43:04.599  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 10:43:04.599  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:43:04.599  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
09-16 10:43:04.599  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 10:43:04.611  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 10:43:04.611  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:43:04.617  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 10:43:04.617  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:43:05.027  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 10:43:05.088  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 10:43:05.089  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:43:05.089  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:43:07.601  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 10:43:07.601  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:43:07.601  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 10:43:07.602  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 10:43:07.602  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 10:43:07.602  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 10:43:07.602  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 10:43:07.602  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 10:43:07.603  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:43:07.603  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 10:43:07.603  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 10:43:07.607  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:43:07.610  5866  5895 D BtGatt.GattService: stopScan() - queue size =1
09-16 10:43:07.611  5866  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 10:43:07.613  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 10:43:07.613  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-16 10:43:07.613  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 10:43:07.614  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 10:43:07.614  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 10:43:07.617  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:43:07.618  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 10:43:07.618  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 10:43:07.618  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 10:43:07.620  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:43:07.623  5866  5866 D BtGatt.ScanManager: awakened up at time 424567
09-16 10:43:07.626  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 10:43:07.626  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:43:07.627  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:07.627  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:43:07.627  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:43:07.627  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 10:43:07.627  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:43:07.627  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4de91cb removed from the list
09-16 10:43:07.627  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:07.627  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1321da8 removed from the list
09-16 10:43:07.627  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:43:07.627  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:07.628  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:07.628  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:07.631  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 10:43:07.631  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:43:07.631  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
09-16 10:43:07.631  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 10:43:07.631  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 10:43:07.631  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 10:43:07.632  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1321da8 not in the list
,09-16 10:43:07.632  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:07.632  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:07.633  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:43:07.634  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:43:07.634  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:07.634  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1321da8 not in the list
09-16 10:43:07.634  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 10:43:07.634  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:07.634  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:07.634  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4de91cb not in the list
09-16 10:43:07.635  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 10:43:07.635  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9ae7fd added. We now have 3 listener(s)
09-16 10:43:07.637  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:43:07.638  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 10:43:07.638  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 10:43:07.638  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:43:07.638  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8520cf2 added. We now have 4 listener(s)
09-16 10:43:07.638  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:43:07.639  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 10:43:07.639  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 10:43:07.639  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:43:07.640  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 10:43:07.643  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:43:07.651  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:43:07.651  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:43:07.651  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:43:07.651  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:43:07.651  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:43:07.651  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:07.651  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:43:07.651  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 10:43:07.656  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:07.656  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:43:07.657  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:43:07.657  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:43:07.657  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:43:07.657  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:43:07.657  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:07.657  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 10:43:07.657  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 10:43:07.657  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9ae7fd removed from the list
09-16 10:43:07.657  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:07.657  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8520cf2 removed from the list
,09-16 10:43:07.660  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:43:07.662  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-16 10:43:07.662  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:43:07.662  5866  5882 D BtGatt.GattService: current time is 424606973427
09-16 10:43:07.662  5866  5882 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -92, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 10:43:07.663  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 10:43:07.663  5587  5633 D io.jxcore.node.ConnectivityMonitor: stop
09-16 10:43:07.663  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:43:07.664  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:07.664  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:07.664  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-16 10:43:07.665  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 10:43:07.665  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-16 10:43:07.665  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:43:07.665  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:43:07.665  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:07.665  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8520cf2 not in the list
09-16 10:43:07.665  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-16 10:43:07.665  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:07.666  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 10:43:07.666  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-16 10:43:07.667  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 10:43:07.667  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 10:43:07.667  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 10:43:07.667  5587  5633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8520cf2 not in the list
09-16 10:43:07.667  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 10:43:07.667  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:43:07.667  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 10:43:07.667  5587  5633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9ae7fd not in the list
,09-16 10:43:07.668  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-16 10:43:07.669  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 10:43:07.669  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-16 10:43:07.669  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:43:07.669  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 10:43:07.669  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:43:08.129  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 10:43:09.681  5587  5961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,09-16 10:43:11.680  5587  5633 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
09-16 10:43:11.680  5587  5633 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,09-16 10:43:11.685  5587  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
09-16 10:43:11.685  5587  5962 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
,09-16 10:43:11.685  5587  5962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-16 10:43:11.690  5587  5633 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 10:43:11.696  5587  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-16 10:43:11.697  5587  5963 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
,09-16 10:43:11.697  5587  5963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-16 10:43:11.703  5587  5633 I jxcore-log: Total number of executed tests:  82
09-16 10:43:11.703  5587  5633 I jxcore-log: 
,09-16 10:43:11.703  5587  5633 I jxcore-log: Number of passed tests:  82
09-16 10:43:11.703  5587  5633 I jxcore-log: 
,09-16 10:43:11.704  5587  5633 I jxcore-log: Number of failed tests:  0
09-16 10:43:11.704  5587  5633 I jxcore-log: 
,09-16 10:43:11.704  5587  5633 I jxcore-log: Number of ignored tests:  0
09-16 10:43:11.704  5587  5633 I jxcore-log: 
,09-16 10:43:11.704  5587  5633 I jxcore-log: Total duration:  100979
09-16 10:43:11.704  5587  5633 I jxcore-log: 
,09-16 10:43:11.709  5587  5633 I jxcore-log: Unit Test app is loaded
09-16 10:43:11.709  5587  5633 I jxcore-log: 
,09-16 10:43:11.721  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.721  5587  5633 I jxcore-log: 
,09-16 10:43:11.728  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.728  5587  5633 I jxcore-log: 
,09-16 10:43:11.729  5587  5587 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-16 10:43:11.730  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.730  5587  5633 I jxcore-log: 
,09-16 10:43:11.733  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.733  5587  5633 I jxcore-log: 
,09-16 10:43:11.735  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 10:43:11.735  5587  5633 I jxcore-log: 
,09-16 10:43:11.737  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 10:43:11.737  5587  5633 I jxcore-log: 
,09-16 10:43:11.740  5587  5961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-16 10:43:11.741  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.741  5587  5633 I jxcore-log: 
,09-16 10:43:11.743  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.743  5587  5633 I jxcore-log: 
,09-16 10:43:11.744  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 10:43:11.744  5587  5633 I jxcore-log: 
09-16 10:43:11.745  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 10:43:11.745  5587  5633 I jxcore-log: 
,09-16 10:43:11.746  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 10:43:11.746  5587  5633 I jxcore-log: 
,09-16 10:43:11.747  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.747  5587  5633 I jxcore-log: 
,09-16 10:43:11.748  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.748  5587  5633 I jxcore-log: 
,09-16 10:43:11.749  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.749  5587  5633 I jxcore-log: 
09-16 10:43:11.750  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.750  5587  5633 I jxcore-log: 
09-16 10:43:11.751  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.751  5587  5633 I jxcore-log: 
,09-16 10:43:11.752  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.752  5587  5633 I jxcore-log: 
,09-16 10:43:11.753  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.753  5587  5633 I jxcore-log: 
,09-16 10:43:11.754  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.754  5587  5633 I jxcore-log: 
09-16 10:43:11.755  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.755  5587  5633 I jxcore-log: 
,09-16 10:43:11.757  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.757  5587  5633 I jxcore-log: 
,09-16 10:43:11.758  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.758  5587  5633 I jxcore-log: 
09-16 10:43:11.758  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.758  5587  5633 I jxcore-log: 
,09-16 10:43:11.759  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.759  5587  5633 I jxcore-log: 
,09-16 10:43:11.760  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.760  5587  5633 I jxcore-log: 
09-16 10:43:11.761  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.761  5587  5633 I jxcore-log: 
09-16 10:43:11.762  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.762  5587  5633 I jxcore-log: 
,09-16 10:43:11.763  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.763  5587  5633 I jxcore-log: 
,09-16 10:43:11.764  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.764  5587  5633 I jxcore-log: 
,09-16 10:43:11.765  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.765  5587  5633 I jxcore-log: 
,09-16 10:43:11.766  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.766  5587  5633 I jxcore-log: 
,09-16 10:43:11.767  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.767  5587  5633 I jxcore-log: 
,09-16 10:43:11.768  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.768  5587  5633 I jxcore-log: 
,09-16 10:43:11.769  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.769  5587  5633 I jxcore-log: 
,09-16 10:43:11.770  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.770  5587  5633 I jxcore-log: 
,09-16 10:43:11.771  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.771  5587  5633 I jxcore-log: 
,09-16 10:43:11.772  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.772  5587  5633 I jxcore-log: 
,09-16 10:43:11.773  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.773  5587  5633 I jxcore-log: 
09-16 10:43:11.774  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.774  5587  5633 I jxcore-log: 
09-16 10:43:11.774  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.774  5587  5633 I jxcore-log: 
09-16 10:43:11.774  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 10:43:11.774  5587  5633 I jxcore-log: 
09-16 10:43:11.775  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.775  5587  5633 I jxcore-log: 
,09-16 10:43:11.776  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 10:43:11.776  5587  5633 I jxcore-log: 
,09-16 10:43:11.777  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.777  5587  5633 I jxcore-log: 
,09-16 10:43:11.778  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.778  5587  5633 I jxcore-log: 
,09-16 10:43:11.778  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.778  5587  5633 I jxcore-log: 
,09-16 10:43:11.779  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.779  5587  5633 I jxcore-log: 
,09-16 10:43:11.780  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.780  5587  5633 I jxcore-log: 
,09-16 10:43:11.781  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 10:43:11.781  5587  5633 I jxcore-log: 
,09-16 10:43:11.781  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.781  5587  5633 I jxcore-log: 
,09-16 10:43:11.782  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 10:43:11.782  5587  5633 I jxcore-log: 
,09-16 10:43:11.783  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.783  5587  5633 I jxcore-log: 
,09-16 10:43:11.783  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 10:43:11.783  5587  5633 I jxcore-log: 
,09-16 10:43:11.784  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 10:43:11.784  5587  5633 I jxcore-log: 
,09-16 10:43:11.785  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:11.785  5587  5633 I jxcore-log: 
,09-16 10:43:11.785  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 10:43:11.785  5587  5633 I jxcore-log: 
,09-16 10:43:11.791  5587  5633 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-16 10:43:11.791  5587  5633 I jxcore-log:   bluetooth: 'on',
09-16 10:43:11.791  5587  5633 I jxcore-log:   wifi: 'on',
09-16 10:43:11.791  5587  5633 I jxcore-log:   cellular: 'doNotCare',
09-16 10:43:11.791  5587  5633 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-16 10:43:11.791  5587  5633 I jxcore-log: 
,09-16 10:43:11.797  5587  5633 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-16 10:43:11.797  5587  5633 I jxcore-log:   bluetooth: 'on',
09-16 10:43:11.797  5587  5633 I jxcore-log:   wifi: 'on',
09-16 10:43:11.797  5587  5633 I jxcore-log:   cellular: 'doNotCare',
09-16 10:43:11.797  5587  5633 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-16 10:43:11.797  5587  5633 I jxcore-log: 
,09-16 10:43:11.798  5587  5633 I jxcore-log: My device name is: Huawei-Nexus 6P
09-16 10:43:11.798  5587  5633 I jxcore-log: 
,09-16 10:43:11.798  5587  5633 I jxcore-log: WARN testUtils: myNameCallback not set!
09-16 10:43:11.798  5587  5633 I jxcore-log: 
09-16 10:43:11.799  5587  5633 I jxcore-log: Running for WIFI network type
09-16 10:43:11.799  5587  5633 I jxcore-log: 
,09-16 10:43:13.546  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-16 10:43:13.546  5587  5633 I jxcore-log: 
,09-16 10:43:13.850  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-16 10:43:13.850  5587  5633 I jxcore-log: 
,09-16 10:43:13.874  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-16 10:43:13.874  5587  5633 I jxcore-log: 
,09-16 10:43:13.877  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-16 10:43:13.877  5587  5633 I jxcore-log: 
,09-16 10:43:13.881  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-16 10:43:13.881  5587  5633 I jxcore-log: 
,09-16 10:43:13.920  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-16 10:43:13.920  5587  5633 I jxcore-log: 
,09-16 10:43:13.931  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-16 10:43:13.931  5587  5633 I jxcore-log: 
,09-16 10:43:13.934  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-16 10:43:13.934  5587  5633 I jxcore-log: 
,09-16 10:43:14.448  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-16 10:43:14.448  5587  5633 I jxcore-log: 
,09-16 10:43:14.456  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-16 10:43:14.456  5587  5633 I jxcore-log: 
,09-16 10:43:14.462  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-16 10:43:14.462  5587  5633 I jxcore-log: 
,09-16 10:43:14.616  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-16 10:43:14.616  5587  5633 I jxcore-log: 
,09-16 10:43:15.678  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-16 10:43:15.678  5587  5633 I jxcore-log: 
,09-16 10:43:15.710  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-16 10:43:15.710  5587  5633 I jxcore-log: 
,09-16 10:43:15.715  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-16 10:43:15.715  5587  5633 I jxcore-log: 
,09-16 10:43:15.805  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-16 10:43:15.805  5587  5633 I jxcore-log: 
,09-16 10:43:15.819  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-16 10:43:15.819  5587  5633 I jxcore-log: 
,09-16 10:43:15.822  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-16 10:43:15.822  5587  5633 I jxcore-log: 
,09-16 10:43:15.827  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-16 10:43:15.827  5587  5633 I jxcore-log: 
,09-16 10:43:15.839  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-16 10:43:15.839  5587  5633 I jxcore-log: 
,09-16 10:43:15.900  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-16 10:43:15.900  5587  5633 I jxcore-log: 
,09-16 10:43:15.904  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-16 10:43:15.904  5587  5633 I jxcore-log: 
,09-16 10:43:15.922  5587  5633 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-16 10:43:15.922  5587  5633 I jxcore-log: 
,09-16 10:43:15.930  5587  5633 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-16 10:43:15.931  5587  5633 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-16 10:43:15.931  5587  5633 I jxcore-log: 
,09-16 10:43:15.933  5587  5633 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-16 10:43:15.933  5587  5633 I jxcore-log: 
,09-16 10:43:15.933  5587  5633 I jxcore-log: ThaliTape :: Started ThaliTape
09-16 10:43:15.933  5587  5633 I jxcore-log: 
,09-16 10:43:15.937  5587  5633 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-16 10:43:15.937  5587  5633 I jxcore-log: 
,09-16 10:43:16.028  5587  5633 I jxcore-log: ThaliTape :: Connected to the test server
09-16 10:43:16.028  5587  5633 I jxcore-log: 
,09-16 10:43:16.349  5587  5633 I jxcore-log: TAP version 13
09-16 10:43:16.349  5587  5633 I jxcore-log: 
,09-16 10:43:16.352  5587  5633 I jxcore-log: # setup
09-16 10:43:16.352  5587  5633 I jxcore-log: 
,09-16 10:43:17.205  5587  5633 I jxcore-log: # 1. calling createNativeListener directly rejects
09-16 10:43:17.205  5587  5633 I jxcore-log: 
,09-16 10:43:17.588  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:17.588  5587  5633 I jxcore-log: 
,09-16 10:43:17.594  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 37362
09-16 10:43:17.594  5587  5633 I jxcore-log: 
,09-16 10:43:17.607  5587  5633 I jxcore-log: ok 1 Should throw
09-16 10:43:17.607  5587  5633 I jxcore-log: 
,09-16 10:43:17.611  5587  5633 I jxcore-log: # teardown
09-16 10:43:17.611  5587  5633 I jxcore-log: 
,09-16 10:43:18.109  5587  5633 I jxcore-log: # setup
09-16 10:43:18.109  5587  5633 I jxcore-log: 
,09-16 10:43:18.814  5587  5633 I jxcore-log: # 2. emits incomingConnectionState
09-16 10:43:18.814  5587  5633 I jxcore-log: 
,09-16 10:43:19.334  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:19.334  5587  5633 I jxcore-log: 
,09-16 10:43:19.342  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 40823
09-16 10:43:19.342  5587  5633 I jxcore-log: 
,09-16 10:43:19.353  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:19.353  5587  5633 I jxcore-log: 
,09-16 10:43:19.357  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:19.357  5587  5633 I jxcore-log: 
,09-16 10:43:19.369  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:19.369  5587  5633 I jxcore-log: 
,09-16 10:43:19.376  5587  5633 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-16 10:43:19.376  5587  5633 I jxcore-log: 
,09-16 10:43:19.399  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:19.399  5587  5633 I jxcore-log: 
,09-16 10:43:19.410  5587  5633 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-16 10:43:19.410  5587  5633 I jxcore-log: 
,09-16 10:43:19.419  5587  5633 I jxcore-log: # teardown
09-16 10:43:19.419  5587  5633 I jxcore-log: 
,09-16 10:43:20.147  5587  5633 I jxcore-log: # setup
09-16 10:43:20.147  5587  5633 I jxcore-log: 
,09-16 10:43:20.657  5587  5633 I jxcore-log: # 3. emits routerPortConnectionFailed
09-16 10:43:20.657  5587  5633 I jxcore-log: 
,09-16 10:43:21.400  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:21.400  5587  5633 I jxcore-log: 
,09-16 10:43:21.404  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 46249
09-16 10:43:21.404  5587  5633 I jxcore-log: 
,09-16 10:43:21.413  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:21.413  5587  5633 I jxcore-log: 
,09-16 10:43:21.414  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:21.414  5587  5633 I jxcore-log: 
,09-16 10:43:21.417  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:21.417  5587  5633 I jxcore-log: 
,09-16 10:43:21.447  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:21.447  5587  5633 I jxcore-log: 
,09-16 10:43:21.450  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:21.450  5587  5633 I jxcore-log: 
,09-16 10:43:21.454  5587  5633 I jxcore-log: DEBUG createNativeListener: 
09-16 10:43:21.454  5587  5633 I jxcore-log: 
,09-16 10:43:21.455  5587  5633 I jxcore-log: ok 4 tried to connect to right port
09-16 10:43:21.455  5587  5633 I jxcore-log: 
09-16 10:43:21.456  5587  5633 I jxcore-log: ok 5 failed due to refused connection
09-16 10:43:21.456  5587  5633 I jxcore-log: 
,09-16 10:43:21.456  5587  5633 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-16 10:43:21.456  5587  5633 I jxcore-log: 
,09-16 10:43:21.459  5587  5633 I jxcore-log: # teardown
09-16 10:43:21.459  5587  5633 I jxcore-log: 
,09-16 10:43:21.460  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:21.460  5587  5633 I jxcore-log: 
,09-16 10:43:21.993  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:21.993  5587  5633 I jxcore-log: 
,09-16 10:43:22.001  5587  5633 I jxcore-log: # setup
09-16 10:43:22.001  5587  5633 I jxcore-log: 
,09-16 10:43:22.003  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:22.003  5587  5633 I jxcore-log: 
,09-16 10:43:22.706  5587  5633 I jxcore-log: # 4. native server connections all up
09-16 10:43:22.706  5587  5633 I jxcore-log: 
,09-16 10:43:23.305  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:23.305  5587  5633 I jxcore-log: 
,09-16 10:43:23.313  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 39065
09-16 10:43:23.313  5587  5633 I jxcore-log: 
,09-16 10:43:23.325  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:23.325  5587  5633 I jxcore-log: 
,09-16 10:43:23.328  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:23.328  5587  5633 I jxcore-log: 
,09-16 10:43:23.330  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:23.330  5587  5633 I jxcore-log: 
,09-16 10:43:23.372  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:23.372  5587  5633 I jxcore-log: 
,09-16 10:43:23.377  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:23.377  5587  5633 I jxcore-log: 
,09-16 10:43:23.381  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:23.381  5587  5633 I jxcore-log: 
,09-16 10:43:23.384  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:23.384  5587  5633 I jxcore-log: 
,09-16 10:43:23.407  5587  5633 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-16 10:43:23.407  5587  5633 I jxcore-log: 
,09-16 10:43:23.408  5587  5633 I jxcore-log: ok 8 Send/recvd #1 should be same
09-16 10:43:23.408  5587  5633 I jxcore-log: 
,09-16 10:43:23.410  5587  5633 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-16 10:43:23.410  5587  5633 I jxcore-log: 
,09-16 10:43:23.411  5587  5633 I jxcore-log: ok 10 Send/recvd #2 should be same
09-16 10:43:23.411  5587  5633 I jxcore-log: 
,09-16 10:43:23.414  5587  5633 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-16 10:43:23.414  5587  5633 I jxcore-log: 
,09-16 10:43:23.419  5587  5633 I jxcore-log: # teardown
09-16 10:43:23.419  5587  5633 I jxcore-log: 
,09-16 10:43:24.133  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:24.133  5587  5633 I jxcore-log: 
,09-16 10:43:24.139  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:24.139  5587  5633 I jxcore-log: 
,09-16 10:43:24.144  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:24.144  5587  5633 I jxcore-log: 
,09-16 10:43:24.150  5587  5633 I jxcore-log: # setup
09-16 10:43:24.150  5587  5633 I jxcore-log: 
,09-16 10:43:24.152  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:24.152  5587  5633 I jxcore-log: 
,09-16 10:43:25.164  5587  5633 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-16 10:43:25.164  5587  5633 I jxcore-log: 
,09-16 10:43:25.250  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:25.250  5587  5633 I jxcore-log: 
,09-16 10:43:25.257  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 41905
09-16 10:43:25.257  5587  5633 I jxcore-log: 
,09-16 10:43:25.269  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:25.269  5587  5633 I jxcore-log: 
,09-16 10:43:25.270  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:25.270  5587  5633 I jxcore-log: 
09-16 10:43:25.272  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:25.272  5587  5633 I jxcore-log: 
,09-16 10:43:25.289  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:25.289  5587  5633 I jxcore-log: 
,09-16 10:43:25.292  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:25.292  5587  5633 I jxcore-log: 
,09-16 10:43:25.307  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:25.307  5587  5633 I jxcore-log: 
,09-16 10:43:25.321  5587  5633 I jxcore-log: ok 12 socket shouldn't close until after stream
09-16 10:43:25.321  5587  5633 I jxcore-log: 
,09-16 10:43:25.322  5587  5633 I jxcore-log: ok 13 incoming remains open
09-16 10:43:25.322  5587  5633 I jxcore-log: 
09-16 10:43:25.325  5587  5633 I jxcore-log: # teardown
09-16 10:43:25.325  5587  5633 I jxcore-log: 
,09-16 10:43:26.079  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:26.079  5587  5633 I jxcore-log: 
,09-16 10:43:26.089  5587  5633 I jxcore-log: # setup
09-16 10:43:26.089  5587  5633 I jxcore-log: 
,09-16 10:43:26.091  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:26.091  5587  5633 I jxcore-log: 
,09-16 10:43:26.147   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:43:26.701  5587  5633 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-16 10:43:26.701  5587  5633 I jxcore-log: 
,09-16 10:43:26.854   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:43:26.854   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:43:28.131  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:28.131  5587  5633 I jxcore-log: 
,09-16 10:43:28.138  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 45398
09-16 10:43:28.138  5587  5633 I jxcore-log: 
,09-16 10:43:28.150  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:28.150  5587  5633 I jxcore-log: 
,09-16 10:43:28.154  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:28.154  5587  5633 I jxcore-log: 
,09-16 10:43:28.157  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:28.157  5587  5633 I jxcore-log: 
,09-16 10:43:28.181  5587  5633 I jxcore-log: ok 14 we should not have gotten an error
09-16 10:43:28.181  5587  5633 I jxcore-log: 
,09-16 10:43:28.191  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:28.191  5587  5633 I jxcore-log: 
,09-16 10:43:28.198  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:28.198  5587  5633 I jxcore-log: 
,09-16 10:43:28.209  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:28.209  5587  5633 I jxcore-log: 
,09-16 10:43:28.212  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:28.212  5587  5633 I jxcore-log: 
,09-16 10:43:28.220  5587  5633 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-16 10:43:28.220  5587  5633 I jxcore-log: 
,09-16 10:43:28.221  5587  5633 I jxcore-log: ok 16 incoming is cleaned up
09-16 10:43:28.221  5587  5633 I jxcore-log: 
,09-16 10:43:28.223  5587  5633 I jxcore-log: # teardown
09-16 10:43:28.223  5587  5633 I jxcore-log: 
,09-16 10:43:28.301  5587  5633 I jxcore-log: # setup
09-16 10:43:28.301  5587  5633 I jxcore-log: 
,09-16 10:43:29.382  5587  5633 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-16 10:43:29.382  5587  5633 I jxcore-log: 
,09-16 10:43:30.177  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:30.177  5587  5633 I jxcore-log: 
,09-16 10:43:30.183  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 45946
09-16 10:43:30.183  5587  5633 I jxcore-log: 
,09-16 10:43:30.196  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:30.196  5587  5633 I jxcore-log: 
,09-16 10:43:30.199  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:30.199  5587  5633 I jxcore-log: 
,09-16 10:43:30.206  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:30.206  5587  5633 I jxcore-log: 
,09-16 10:43:30.229  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:30.229  5587  5633 I jxcore-log: 
,09-16 10:43:30.232  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:30.232  5587  5633 I jxcore-log: 
,09-16 10:43:30.251  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:30.251  5587  5633 I jxcore-log: 
,09-16 10:43:30.269  5587  5633 I jxcore-log: ok 17 stream was closed
09-16 10:43:30.269  5587  5633 I jxcore-log: 
,09-16 10:43:30.269  5587  5633 I jxcore-log: ok 18 incoming should survive
09-16 10:43:30.269  5587  5633 I jxcore-log: 
09-16 10:43:30.270  5587  5633 I jxcore-log: ok 19 mux should have no streams
09-16 10:43:30.270  5587  5633 I jxcore-log: 
,09-16 10:43:30.275  5587  5633 I jxcore-log: # teardown
09-16 10:43:30.275  5587  5633 I jxcore-log: 
,09-16 10:43:31.226   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:43:31.302  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:31.302  5587  5633 I jxcore-log: 
,09-16 10:43:31.314  5587  5633 I jxcore-log: # setup
09-16 10:43:31.314  5587  5633 I jxcore-log: 
,09-16 10:43:31.315  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:31.315  5587  5633 I jxcore-log: 
,09-16 10:43:32.220  5587  5633 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-16 10:43:32.220  5587  5633 I jxcore-log: 
,09-16 10:43:32.739  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:32.739  5587  5633 I jxcore-log: 
,09-16 10:43:32.746  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 42109
09-16 10:43:32.746  5587  5633 I jxcore-log: 
,09-16 10:43:32.758  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:32.758  5587  5633 I jxcore-log: 
,09-16 10:43:32.761  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:32.761  5587  5633 I jxcore-log: 
,09-16 10:43:32.764  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:32.764  5587  5633 I jxcore-log: 
,09-16 10:43:32.778  5587  5633 I jxcore-log: ok 20 we should not have gotten an error
09-16 10:43:32.778  5587  5633 I jxcore-log: 
,09-16 10:43:32.796  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:32.796  5587  5633 I jxcore-log: 
,09-16 10:43:32.800  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:32.800  5587  5633 I jxcore-log: 
,09-16 10:43:32.811  5587  5633 I jxcore-log: ok 21 Buffers are identical
09-16 10:43:32.811  5587  5633 I jxcore-log: 
,09-16 10:43:32.814  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:32.814  5587  5633 I jxcore-log: 
,09-16 10:43:32.818  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:32.818  5587  5633 I jxcore-log: 
,09-16 10:43:32.821  5587  5633 I jxcore-log: ok 22 native server is nulled out
09-16 10:43:32.821  5587  5633 I jxcore-log: 
,09-16 10:43:32.821  5587  5633 I jxcore-log: ok 23 native server should be closed
09-16 10:43:32.821  5587  5633 I jxcore-log: 
09-16 10:43:32.822  5587  5633 I jxcore-log: ok 24 incoming has been removed
09-16 10:43:32.822  5587  5633 I jxcore-log: 
09-16 10:43:32.823  5587  5633 I jxcore-log: ok 25 Incoming should be done
09-16 10:43:32.823  5587  5633 I jxcore-log: 
,09-16 10:43:32.823  5587  5633 I jxcore-log: ok 26 The mux object should be closed
09-16 10:43:32.823  5587  5633 I jxcore-log: 
09-16 10:43:32.824  5587  5633 I jxcore-log: ok 27 The mux stream should be closed
09-16 10:43:32.824  5587  5633 I jxcore-log: 
,09-16 10:43:32.825  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:32.825  5587  5633 I jxcore-log: 
,09-16 10:43:32.837  5587  5633 I jxcore-log: # teardown
09-16 10:43:32.837  5587  5633 I jxcore-log: 
,09-16 10:43:33.667  5587  5633 I jxcore-log: # setup
09-16 10:43:33.667  5587  5633 I jxcore-log: 
,09-16 10:43:33.884  5587  5633 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-16 10:43:33.884  5587  5633 I jxcore-log: 
,09-16 10:43:34.251   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:43:35.188  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:35.188  5587  5633 I jxcore-log: 
,09-16 10:43:35.194  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 40227
09-16 10:43:35.194  5587  5633 I jxcore-log: 
,09-16 10:43:35.232  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.232  5587  5633 I jxcore-log: 
,09-16 10:43:35.233  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.233  5587  5633 I jxcore-log: 
09-16 10:43:35.234  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.234  5587  5633 I jxcore-log: 
,09-16 10:43:35.238  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.238  5587  5633 I jxcore-log: 
,09-16 10:43:35.239  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.239  5587  5633 I jxcore-log: 
,09-16 10:43:35.241  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.241  5587  5633 I jxcore-log: 
,09-16 10:43:35.244  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.244  5587  5633 I jxcore-log: 
09-16 10:43:35.245  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.245  5587  5633 I jxcore-log: 
,09-16 10:43:35.246  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.246  5587  5633 I jxcore-log: 
,09-16 10:43:35.250  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.250  5587  5633 I jxcore-log: 
,09-16 10:43:35.251  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.251  5587  5633 I jxcore-log: 
09-16 10:43:35.252  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.252  5587  5633 I jxcore-log: 
,09-16 10:43:35.255  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.255  5587  5633 I jxcore-log: 
09-16 10:43:35.256  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.256  5587  5633 I jxcore-log: 
09-16 10:43:35.257  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.257  5587  5633 I jxcore-log: 
,09-16 10:43:35.260  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.260  5587  5633 I jxcore-log: 
,09-16 10:43:35.260  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.260  5587  5633 I jxcore-log: 
,09-16 10:43:35.262  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.262  5587  5633 I jxcore-log: 
,09-16 10:43:35.271  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.271  5587  5633 I jxcore-log: 
,09-16 10:43:35.272  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.272  5587  5633 I jxcore-log: 
,09-16 10:43:35.274  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.274  5587  5633 I jxcore-log: 
,09-16 10:43:35.280  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.280  5587  5633 I jxcore-log: 
,09-16 10:43:35.280  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.280  5587  5633 I jxcore-log: 
,09-16 10:43:35.282  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.282  5587  5633 I jxcore-log: 
,09-16 10:43:35.284  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.284  5587  5633 I jxcore-log: 
,09-16 10:43:35.284  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.284  5587  5633 I jxcore-log: 
,09-16 10:43:35.286  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.286  5587  5633 I jxcore-log: 
,09-16 10:43:35.287  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:35.287  5587  5633 I jxcore-log: 
09-16 10:43:35.287  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:35.287  5587  5633 I jxcore-log: 
09-16 10:43:35.288  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:35.288  5587  5633 I jxcore-log: 
,09-16 10:43:35.349  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.349  5587  5633 I jxcore-log: 
,09-16 10:43:35.352  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.352  5587  5633 I jxcore-log: 
,09-16 10:43:35.354  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.354  5587  5633 I jxcore-log: 
,09-16 10:43:35.355  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.355  5587  5633 I jxcore-log: 
,09-16 10:43:35.356  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.356  5587  5633 I jxcore-log: 
,09-16 10:43:35.357  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.357  5587  5633 I jxcore-log: 
,09-16 10:43:35.358  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.358  5587  5633 I jxcore-log: 
,09-16 10:43:35.360  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.360  5587  5633 I jxcore-log: 
09-16 10:43:35.361  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.361  5587  5633 I jxcore-log: 
,09-16 10:43:35.362  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.362  5587  5633 I jxcore-log: 
09-16 10:43:35.363  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.363  5587  5633 I jxcore-log: 
,09-16 10:43:35.364  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.364  5587  5633 I jxcore-log: 
09-16 10:43:35.364  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.364  5587  5633 I jxcore-log: 
,09-16 10:43:35.365  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.365  5587  5633 I jxcore-log: 
09-16 10:43:35.366  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.366  5587  5633 I jxcore-log: 
,09-16 10:43:35.366  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.366  5587  5633 I jxcore-log: 
09-16 10:43:35.367  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.367  5587  5633 I jxcore-log: 
,09-16 10:43:35.368  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.368  5587  5633 I jxcore-log: 
09-16 10:43:35.369  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.369  5587  5633 I jxcore-log: 
09-16 10:43:35.370  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.370  5587  5633 I jxcore-log: 
,09-16 10:43:35.370  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.370  5587  5633 I jxcore-log: 
09-16 10:43:35.371  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.371  5587  5633 I jxcore-log: 
,09-16 10:43:35.372  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.372  5587  5633 I jxcore-log: 
09-16 10:43:35.372  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.372  5587  5633 I jxcore-log: 
,09-16 10:43:35.373  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.373  5587  5633 I jxcore-log: 
,09-16 10:43:35.374  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.374  5587  5633 I jxcore-log: 
09-16 10:43:35.375  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.375  5587  5633 I jxcore-log: 
09-16 10:43:35.376  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.376  5587  5633 I jxcore-log: 
,09-16 10:43:35.379  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.379  5587  5633 I jxcore-log: 
,09-16 10:43:35.380  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.380  5587  5633 I jxcore-log: 
09-16 10:43:35.381  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.381  5587  5633 I jxcore-log: 
,09-16 10:43:35.381  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.381  5587  5633 I jxcore-log: 
09-16 10:43:35.383  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.383  5587  5633 I jxcore-log: 
,09-16 10:43:35.383  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.383  5587  5633 I jxcore-log: 
09-16 10:43:35.384  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.384  5587  5633 I jxcore-log: 
,09-16 10:43:35.385  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.385  5587  5633 I jxcore-log: 
09-16 10:43:35.385  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.385  5587  5633 I jxcore-log: 
,09-16 10:43:35.386  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.386  5587  5633 I jxcore-log: 
,09-16 10:43:35.391  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.391  5587  5633 I jxcore-log: 
,09-16 10:43:35.392  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.392  5587  5633 I jxcore-log: 
,09-16 10:43:35.394  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.394  5587  5633 I jxcore-log: 
,09-16 10:43:35.395  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.395  5587  5633 I jxcore-log: 
09-16 10:43:35.395  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.395  5587  5633 I jxcore-log: 
09-16 10:43:35.396  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.396  5587  5633 I jxcore-log: 
,09-16 10:43:35.397  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.397  5587  5633 I jxcore-log: 
09-16 10:43:35.397  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.397  5587  5633 I jxcore-log: 
,09-16 10:43:35.398  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.398  5587  5633 I jxcore-log: 
09-16 10:43:35.399  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.399  5587  5633 I jxcore-log: 
,09-16 10:43:35.400  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.400  5587  5633 I jxcore-log: 
09-16 10:43:35.401  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.401  5587  5633 I jxcore-log: 
,09-16 10:43:35.401  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.401  5587  5633 I jxcore-log: 
,09-16 10:43:35.402  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.402  5587  5633 I jxcore-log: 
09-16 10:43:35.402  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.402  5587  5633 I jxcore-log: 
09-16 10:43:35.403  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.403  5587  5633 I jxcore-log: 
09-16 10:43:35.404  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.404  5587  5633 I jxcore-log: 
,09-16 10:43:35.404  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.404  5587  5633 I jxcore-log: 
09-16 10:43:35.405  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.405  5587  5633 I jxcore-log: 
,09-16 10:43:35.406  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.406  5587  5633 I jxcore-log: 
09-16 10:43:35.407  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.407  5587  5633 I jxcore-log: 
09-16 10:43:35.407  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.407  5587  5633 I jxcore-log: 
,09-16 10:43:35.408  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.408  5587  5633 I jxcore-log: 
09-16 10:43:35.409  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.409  5587  5633 I jxcore-log: 
,09-16 10:43:35.409  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.409  5587  5633 I jxcore-log: 
09-16 10:43:35.410  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.410  5587  5633 I jxcore-log: 
,09-16 10:43:35.411  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.411  5587  5633 I jxcore-log: 
09-16 10:43:35.411  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.411  5587  5633 I jxcore-log: 
,09-16 10:43:35.412  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.412  5587  5633 I jxcore-log: 
,09-16 10:43:35.413  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.413  5587  5633 I jxcore-log: 
09-16 10:43:35.413  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.413  5587  5633 I jxcore-log: 
09-16 10:43:35.414  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.414  5587  5633 I jxcore-log: 
,09-16 10:43:35.415  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.415  5587  5633 I jxcore-log: 
09-16 10:43:35.415  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.415  5587  5633 I jxcore-log: 
,09-16 10:43:35.416  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.416  5587  5633 I jxcore-log: 
09-16 10:43:35.417  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.417  5587  5633 I jxcore-log: 
,09-16 10:43:35.418  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.418  5587  5633 I jxcore-log: 
09-16 10:43:35.418  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.418  5587  5633 I jxcore-log: 
,09-16 10:43:35.419  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.419  5587  5633 I jxcore-log: 
09-16 10:43:35.420  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.420  5587  5633 I jxcore-log: 
,09-16 10:43:35.420  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:35.420  5587  5633 I jxcore-log: 
09-16 10:43:35.421  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:35.421  5587  5633 I jxcore-log: 
,09-16 10:43:35.465  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.465  5587  5633 I jxcore-log: 
,09-16 10:43:35.466  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.466  5587  5633 I jxcore-log: 
09-16 10:43:35.467  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.467  5587  5633 I jxcore-log: 
,09-16 10:43:35.468  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.468  5587  5633 I jxcore-log: 
09-16 10:43:35.468  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.468  5587  5633 I jxcore-log: 
,09-16 10:43:35.469  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.469  5587  5633 I jxcore-log: 
09-16 10:43:35.470  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.470  5587  5633 I jxcore-log: 
09-16 10:43:35.470  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.470  5587  5633 I jxcore-log: 
,09-16 10:43:35.471  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.471  5587  5633 I jxcore-log: 
09-16 10:43:35.471  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.471  5587  5633 I jxcore-log: 
,09-16 10:43:35.472  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.472  5587  5633 I jxcore-log: 
,09-16 10:43:35.473  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.473  5587  5633 I jxcore-log: 
09-16 10:43:35.474  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.474  5587  5633 I jxcore-log: 
09-16 10:43:35.474  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.474  5587  5633 I jxcore-log: 
,09-16 10:43:35.475  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.475  5587  5633 I jxcore-log: 
,09-16 10:43:35.479  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.479  5587  5633 I jxcore-log: 
,09-16 10:43:35.480  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.480  5587  5633 I jxcore-log: 
,09-16 10:43:35.481  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.481  5587  5633 I jxcore-log: 
09-16 10:43:35.482  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.482  5587  5633 I jxcore-log: 
09-16 10:43:35.482  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.482  5587  5633 I jxcore-log: 
,09-16 10:43:35.483  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.483  5587  5633 I jxcore-log: 
09-16 10:43:35.483  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.483  5587  5633 I jxcore-log: 
09-16 10:43:35.484  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.484  5587  5633 I jxcore-log: 
,09-16 10:43:35.484  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.484  5587  5633 I jxcore-log: 
09-16 10:43:35.485  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.485  5587  5633 I jxcore-log: 
09-16 10:43:35.485  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.485  5587  5633 I jxcore-log: 
09-16 10:43:35.486  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.486  5587  5633 I jxcore-log: 
09-16 10:43:35.486  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.486  5587  5633 I jxcore-log: 
,09-16 10:43:35.486  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.486  5587  5633 I jxcore-log: 
09-16 10:43:35.487  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.487  5587  5633 I jxcore-log: 
09-16 10:43:35.487  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.487  5587  5633 I jxcore-log: 
09-16 10:43:35.488  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.488  5587  5633 I jxcore-log: 
,09-16 10:43:35.488  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.488  5587  5633 I jxcore-log: 
09-16 10:43:35.489  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.489  5587  5633 I jxcore-log: 
09-16 10:43:35.489  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.489  5587  5633 I jxcore-log: 
09-16 10:43:35.489  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.489  5587  5633 I jxcore-log: 
,09-16 10:43:35.490  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.490  5587  5633 I jxcore-log: 
09-16 10:43:35.490  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.490  5587  5633 I jxcore-log: 
09-16 10:43:35.491  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.491  5587  5633 I jxcore-log: 
09-16 10:43:35.491  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.491  5587  5633 I jxcore-log: 
09-16 10:43:35.491  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.491  5587  5633 I jxcore-log: 
09-16 10:43:35.492  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.492  5587  5633 I jxcore-log: 
09-16 10:43:35.492  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.492  5587  5633 I jxcore-log: 
09-16 10:43:35.493  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.493  5587  5633 I jxcore-log: 
09-16 10:43:35.493  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.493  5587  5633 I jxcore-log: 
09-16 10:43:35.493  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.493  5587  5633 I jxcore-log: 
09-16 10:43:35.494  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.494  5587  5633 I jxcore-log: 
09-16 10:43:35.494  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.494  5587  5633 I jxcore-log: 
09-16 10:43:35.495  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:35.495  5587  5633 I jxcore-log: 
09-16 10:43:35.495  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:35.495  5587  5633 I jxcore-log: 
09-16 10:43:35.497  5587  5633 I jxcore-log: ok 28 native server is nulled out
09-16 10:43:35.497  5587  5633 I jxcore-log: 
09-16 10:43:35.497  5587  5633 I jxcore-log: ok 29 native server should be closed
09-16 10:43:35.497  5587  5633 I jxcore-log: 
09-16 10:43:35.497  5587  5633 I jxcore-log: ok 30 incoming has been removed
09-16 10:43:35.497  5587  5633 I jxcore-log: 
09-16 10:43:35.498  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.498  5587  5633 I jxcore-log: 
09-16 10:43:35.499  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.499  5587  5633 I jxcore-log: 
09-16 10:43:35.499  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.499  5587  5633 I jxcore-log: 
09-16 10:43:35.499  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.499  5587  5633 I jxcore-log: 
09-16 10:43:35.499  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.499  5587  5633 I jxcore-log: 
09-16 10:43:35.499  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.499  5587  5633 I jxcore-log: 
09-16 10:43:35.500  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.500  5587  5633 I jxcore-log: 
09-16 10:43:35.500  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.500  5587  5633 I jxcore-log: 
09-16 10:43:35.500  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.500  5587  5633 I jxcore-log: 
09-16 10:43:35.500  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:35.500  5587  5633 I jxcore-log: 
,09-16 10:43:35.575  5587  5633 I jxcore-log: # teardown
09-16 10:43:35.575  5587  5633 I jxcore-log: 
,09-16 10:43:35.595  5587  5633 I jxcore-log: # setup
09-16 10:43:35.595  5587  5633 I jxcore-log: 
,09-16 10:43:36.526  5587  5633 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-16 10:43:36.526  5587  5633 I jxcore-log: 
,09-16 10:43:37.138  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:37.138  5587  5633 I jxcore-log: 
,09-16 10:43:37.144  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 46240
09-16 10:43:37.144  5587  5633 I jxcore-log: 
,09-16 10:43:37.155  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:37.155  5587  5633 I jxcore-log: 
,09-16 10:43:37.157  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:37.157  5587  5633 I jxcore-log: 
,09-16 10:43:37.160  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:37.160  5587  5633 I jxcore-log: 
,09-16 10:43:37.171  5587  5633 I jxcore-log: ok 31 we should not have gotten an error
09-16 10:43:37.171  5587  5633 I jxcore-log: 
,09-16 10:43:37.185  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:37.185  5587  5633 I jxcore-log: 
,09-16 10:43:37.188  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:37.188  5587  5633 I jxcore-log: 
,09-16 10:43:37.197  5587  5633 I jxcore-log: ok 32 Buffers are identical
09-16 10:43:37.197  5587  5633 I jxcore-log: 
,09-16 10:43:37.198  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:37.198  5587  5633 I jxcore-log: 
,09-16 10:43:37.200  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:37.200  5587  5633 I jxcore-log: 
,09-16 10:43:37.213  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:37.213  5587  5633 I jxcore-log: 
,09-16 10:43:37.214  5587  5633 I jxcore-log: ok 33 server should be fine
09-16 10:43:37.214  5587  5633 I jxcore-log: 
09-16 10:43:37.214  5587  5633 I jxcore-log: ok 34 server should be open
09-16 10:43:37.214  5587  5633 I jxcore-log: 
09-16 10:43:37.214  5587  5633 I jxcore-log: ok 35 incoming has been removed
09-16 10:43:37.214  5587  5633 I jxcore-log: 
09-16 10:43:37.215  5587  5633 I jxcore-log: ok 36 The mux object should be closed
09-16 10:43:37.215  5587  5633 I jxcore-log: 
09-16 10:43:37.215  5587  5633 I jxcore-log: ok 37 The mux stream should be closed
09-16 10:43:37.215  5587  5633 I jxcore-log: 
,09-16 10:43:37.220  5587  5633 I jxcore-log: # teardown
09-16 10:43:37.220  5587  5633 I jxcore-log: 
,09-16 10:43:38.166  5587  5633 I jxcore-log: # setup
09-16 10:43:38.166  5587  5633 I jxcore-log: 
,09-16 10:43:38.381  5587  5633 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-16 10:43:38.381  5587  5633 I jxcore-log: 
,09-16 10:43:38.995  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:43:38.995  5587  5633 I jxcore-log: 
,09-16 10:43:39.001  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 48168
09-16 10:43:39.001  5587  5633 I jxcore-log: 
,09-16 10:43:39.014  5587  5633 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 10:43:39.014  5587  5633 I jxcore-log: 
,09-16 10:43:39.016  5587  5633 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 10:43:39.016  5587  5633 I jxcore-log: 
,09-16 10:43:39.018  5587  5633 I jxcore-log: DEBUG createNativeListener: new mux
09-16 10:43:39.018  5587  5633 I jxcore-log: 
,09-16 10:43:39.029  5587  5633 I jxcore-log: ok 38 we should not have gotten an error
09-16 10:43:39.029  5587  5633 I jxcore-log: 
,09-16 10:43:39.037  5587  5633 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 10:43:39.037  5587  5633 I jxcore-log: 
,09-16 10:43:39.041  5587  5633 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 10:43:39.041  5587  5633 I jxcore-log: 
,09-16 10:43:39.049  5587  5633 I jxcore-log: ok 39 Buffers are identical
09-16 10:43:39.049  5587  5633 I jxcore-log: 
,09-16 10:43:39.054  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-16 10:43:39.054  5587  5633 I jxcore-log: 
,09-16 10:43:39.056  5587  5633 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 10:43:39.056  5587  5633 I jxcore-log: 
,09-16 10:43:39.058  5587  5633 I jxcore-log: DEBUG createNativeListener: mux close
09-16 10:43:39.058  5587  5633 I jxcore-log: 
,09-16 10:43:39.063  5587  5633 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 10:43:39.063  5587  5633 I jxcore-log: 
,09-16 10:43:39.064  5587  5633 I jxcore-log: ok 40 server should be fine
09-16 10:43:39.064  5587  5633 I jxcore-log: 
09-16 10:43:39.064  5587  5633 I jxcore-log: ok 41 server should be open
09-16 10:43:39.064  5587  5633 I jxcore-log: 
09-16 10:43:39.064  5587  5633 I jxcore-log: ok 42 incoming has been removed
09-16 10:43:39.064  5587  5633 I jxcore-log: 
09-16 10:43:39.065  5587  5633 I jxcore-log: ok 43 The mux object should be closed
09-16 10:43:39.065  5587  5633 I jxcore-log: 
09-16 10:43:39.065  5587  5633 I jxcore-log: ok 44 The mux stream should be closed
09-16 10:43:39.065  5587  5633 I jxcore-log: 
,09-16 10:43:39.071  5587  5633 I jxcore-log: # teardown
09-16 10:43:39.071  5587  5633 I jxcore-log: 
,09-16 10:43:39.704  5587  5633 I jxcore-log: # setup
09-16 10:43:39.704  5587  5633 I jxcore-log: 
,09-16 10:43:40.289   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:43:40.408  5587  5633 I jxcore-log: # 12. closeAll can close even when connections open
09-16 10:43:40.408  5587  5633 I jxcore-log: 
,09-16 10:43:41.057  5587  5633 I jxcore-log: ok 45 not possible to connect to the server anymore
09-16 10:43:41.057  5587  5633 I jxcore-log: 
,09-16 10:43:41.062  5587  5633 I jxcore-log: # teardown
09-16 10:43:41.062  5587  5633 I jxcore-log: 
,09-16 10:43:41.643  5587  5633 I jxcore-log: # setup
09-16 10:43:41.643  5587  5633 I jxcore-log: 
,09-16 10:43:42.354  5587  5633 I jxcore-log: # 13. closeAll with promise
09-16 10:43:42.354  5587  5633 I jxcore-log: 
,09-16 10:43:43.308  5587  5633 I jxcore-log: ok 46 not possible to connect to the server anymore
09-16 10:43:43.308  5587  5633 I jxcore-log: 
09-16 10:43:43.309   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:43:43.314  5587  5633 I jxcore-log: # teardown
09-16 10:43:43.314  5587  5633 I jxcore-log: 
,09-16 10:43:43.791  5587  5633 I jxcore-log: # setup
09-16 10:43:43.791  5587  5633 I jxcore-log: 
,09-16 10:43:44.207  5587  5633 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
09-16 10:43:44.207  5587  5633 I jxcore-log: 
,09-16 10:43:45.016  5587  5633 I jxcore-log: ok 47 Got the right error
09-16 10:43:45.016  5587  5633 I jxcore-log: 
,09-16 10:43:45.025  5587  5633 I jxcore-log: # teardown
09-16 10:43:45.025  5587  5633 I jxcore-log: 
,09-16 10:43:45.525  5587  5633 I jxcore-log: # setup
09-16 10:43:45.525  5587  5633 I jxcore-log: 
,09-16 10:43:46.150   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:43:46.184  5587  5633 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-16 10:43:46.184  5587  5633 I jxcore-log: 
,09-16 10:43:46.765  5587  5633 I jxcore-log: # teardown
09-16 10:43:46.765  5587  5633 I jxcore-log: 
,09-16 10:43:46.855   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:47.166  5587  5633 I jxcore-log: # setup
09-16 10:43:47.166  5587  5633 I jxcore-log: 
,09-16 10:43:47.857   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:48.197  5587  5633 I jxcore-log: # 16. onPeerLost calls jxcore
09-16 10:43:48.197  5587  5633 I jxcore-log: 
,09-16 10:43:48.266  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 10:43:48.266  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e70f9c0 added. We now have 3 listener(s)
,09-16 10:43:48.270  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:43:48.270  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 10:43:48.271  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 10:43:48.271  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:43:48.271  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb306f9 added. We now have 4 listener(s)
09-16 10:43:48.271  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:43:48.273  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 10:43:48.280  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:43:48.287  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:43:48.287  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:43:48.287  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:43:48.287  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:43:48.287  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:43:48.287  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:48.287  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:43:48.287  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:43:48.289  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:48.290  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:43:48.290  5587  5633 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
,09-16 10:43:48.290  5587  5633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-16 10:43:48.295  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:43:48.300  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:43:48.858   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:49.340   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:43:49.860   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:50.293  5587  5633 I jxcore-log: onPeerLost
09-16 10:43:50.293  5587  5633 I jxcore-log: 
,09-16 10:43:50.296  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:50.296  5587  5633 I jxcore-log: 
,09-16 10:43:50.304  5587  5633 I jxcore-log: # teardown
09-16 10:43:50.304  5587  5633 I jxcore-log: 
,09-16 10:43:50.314  5587  5633 I jxcore-log: ok 48 check if callback was fired by onPeerLost
09-16 10:43:50.314  5587  5633 I jxcore-log: 
,09-16 10:43:50.315  5587  5633 I jxcore-log: ok 49 check if peerAvailable is false
09-16 10:43:50.315  5587  5633 I jxcore-log: 
,09-16 10:43:50.861   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:51.366  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 10:43:51.366  5587  5633 I jxcore-log: 
,09-16 10:43:51.371  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 10:43:51.371  5587  5633 I jxcore-log: 
,09-16 10:43:51.383  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:43:51.383  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:43:51.383  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:43:51.383  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:43:51.383  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:43:51.383  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:51.383  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:43:51.383  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:43:51.388  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:43:51.392  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 10:43:51.392  5587  5633 I jxcore-log: 
,09-16 10:43:51.394  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 10:43:51.394  5587  5633 I jxcore-log: 
,09-16 10:43:51.398  5587  5633 I jxcore-log: # setup
09-16 10:43:51.398  5587  5633 I jxcore-log: 
,09-16 10:43:51.401  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:51.401  5587  5633 I jxcore-log: 
,09-16 10:43:51.862   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:43:52.287  5587  5633 I jxcore-log: # 17. onPeerDiscovered calls jxcore
09-16 10:43:52.287  5587  5633 I jxcore-log: 
,09-16 10:43:52.354   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:43:52.503  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 10:43:52.504  5587  5633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70dbc9f added. We now have 4 listener(s)
,09-16 10:43:52.507  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 10:43:52.507  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 10:43:52.507  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 10:43:52.507  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 10:43:52.507  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bf1ec added. We now have 5 listener(s)
09-16 10:43:52.508  5587  5633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 10:43:52.509  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 10:43:52.518  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 10:43:52.525  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:43:52.525  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:43:52.525  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:43:52.525  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:43:52.525  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:43:52.525  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:52.525  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:43:52.525  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:43:52.528  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:43:52.528  5587  5633 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 10:43:52.529  5587  5633 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-16 10:43:52.534  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:43:52.539  5587  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 10:43:54.531  5587  5633 I jxcore-log: onPeerDiscovered
09-16 10:43:54.531  5587  5633 I jxcore-log: 
,09-16 10:43:54.534  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:54.534  5587  5633 I jxcore-log: 
,09-16 10:43:54.544  5587  5633 I jxcore-log: # teardown
09-16 10:43:54.544  5587  5633 I jxcore-log: 
,09-16 10:43:54.556  5587  5633 I jxcore-log: ok 50 check if callback was fired by onPeerDiscovered
09-16 10:43:54.556  5587  5633 I jxcore-log: 
,09-16 10:43:54.558  5587  5633 I jxcore-log: ok 51 check if peerAvailable is true
09-16 10:43:54.558  5587  5633 I jxcore-log: 
,09-16 10:43:55.274  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 10:43:55.274  5587  5633 I jxcore-log: 
,09-16 10:43:55.279  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 10:43:55.279  5587  5633 I jxcore-log: 
,09-16 10:43:55.288  5587  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 10:43:55.288  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 10:43:55.288  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 10:43:55.288  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 10:43:55.288  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 10:43:55.288  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 10:43:55.288  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 10:43:55.288  5587  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 10:43:55.292  5587  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 10:43:55.294  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 10:43:55.294  5587  5633 I jxcore-log: 
,09-16 10:43:55.297  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 10:43:55.297  5587  5633 I jxcore-log: 
09-16 10:43:55.299  5587  5633 I jxcore-log: # setup
09-16 10:43:55.299  5587  5633 I jxcore-log: 
09-16 10:43:55.301  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 10:43:55.301  5587  5633 I jxcore-log: 
,09-16 10:43:55.975  5587  5633 I jxcore-log: # 18. test defaultDirectory
09-16 10:43:55.975  5587  5633 I jxcore-log: 
,09-16 10:43:56.863   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:56.926  5587  5633 I jxcore-log: ok 52 should be equal
09-16 10:43:56.926  5587  5633 I jxcore-log: 
,09-16 10:43:56.930  5587  5633 I jxcore-log: ok 53 should be equal
09-16 10:43:56.930  5587  5633 I jxcore-log: 
,09-16 10:43:56.948  5587  5633 I jxcore-log: ok 54 should be equal
09-16 10:43:56.948  5587  5633 I jxcore-log: 
,09-16 10:43:56.950  5587  5633 I jxcore-log: # teardown
09-16 10:43:56.950  5587  5633 I jxcore-log: 
,09-16 10:43:57.183  5587  5633 I jxcore-log: # setup
09-16 10:43:57.183  5587  5633 I jxcore-log: 
,09-16 10:43:57.864   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:58.228  5587  5633 I jxcore-log: # 19. test defaultAdapter
09-16 10:43:58.228  5587  5633 I jxcore-log: 
,09-16 10:43:58.378   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:43:58.435  5587  5633 I jxcore-log: ok 55 should be equal
09-16 10:43:58.435  5587  5633 I jxcore-log: 
,09-16 10:43:58.436  5587  5633 I jxcore-log: ok 56 should be equal
09-16 10:43:58.436  5587  5633 I jxcore-log: 
,09-16 10:43:58.440  5587  5633 I jxcore-log: ok 57 should be equal
09-16 10:43:58.440  5587  5633 I jxcore-log: 
,09-16 10:43:58.441  5587  5633 I jxcore-log: ok 58 should be equal
09-16 10:43:58.441  5587  5633 I jxcore-log: 
,09-16 10:43:58.447  5587  5633 I jxcore-log: ok 59 should be equal
09-16 10:43:58.447  5587  5633 I jxcore-log: 
,09-16 10:43:58.448  5587  5633 I jxcore-log: ok 60 should be equal
09-16 10:43:58.448  5587  5633 I jxcore-log: 
,09-16 10:43:58.641  5587  5633 I jxcore-log: ok 61 should be equal
09-16 10:43:58.641  5587  5633 I jxcore-log: 
,09-16 10:43:58.642  5587  5633 I jxcore-log: ok 62 should be equal
09-16 10:43:58.642  5587  5633 I jxcore-log: 
,09-16 10:43:58.644  5587  5633 I jxcore-log: # teardown
09-16 10:43:58.644  5587  5633 I jxcore-log: 
,09-16 10:43:58.866   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:43:59.275  5587  5633 I jxcore-log: # setup
09-16 10:43:59.275  5587  5633 I jxcore-log: 
,09-16 10:43:59.772  5587  5633 I jxcore-log: # 20. enqueue and run in order
09-16 10:43:59.772  5587  5633 I jxcore-log: 
,09-16 10:43:59.867   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:00.063  5587  5633 I jxcore-log: ok 63 firstPromise setTimeout
09-16 10:44:00.063  5587  5633 I jxcore-log: 
,09-16 10:44:00.066  5587  5633 I jxcore-log: ok 64 firstPromise result
09-16 10:44:00.066  5587  5633 I jxcore-log: 
,09-16 10:44:00.066  5587  5633 I jxcore-log: ok 65 firstPromise testValue
09-16 10:44:00.066  5587  5633 I jxcore-log: 
,09-16 10:44:00.169  5587  5633 I jxcore-log: ok 66 secondPromise setTimeout
09-16 10:44:00.169  5587  5633 I jxcore-log: 
,09-16 10:44:00.170  5587  5633 I jxcore-log: ok 67 secondPromise result
09-16 10:44:00.170  5587  5633 I jxcore-log: 
09-16 10:44:00.170  5587  5633 I jxcore-log: ok 68 secondPromise testValue
09-16 10:44:00.170  5587  5633 I jxcore-log: 
09-16 10:44:00.170  5587  5633 I jxcore-log: ok 69 thirdPromise in promise
09-16 10:44:00.170  5587  5633 I jxcore-log: 
,09-16 10:44:00.171  5587  5633 I jxcore-log: ok 70 thirdPromise result
09-16 10:44:00.171  5587  5633 I jxcore-log: 
09-16 10:44:00.172  5587  5633 I jxcore-log: ok 71 thirdPromise testValue
09-16 10:44:00.172  5587  5633 I jxcore-log: 
09-16 10:44:00.176  5587  5633 I jxcore-log: # teardown
09-16 10:44:00.176  5587  5633 I jxcore-log: 
,09-16 10:44:00.868   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:01.095  5587  5633 I jxcore-log: # setup
09-16 10:44:01.095  5587  5633 I jxcore-log: 
,09-16 10:44:01.391   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:44:01.415  5587  5633 I jxcore-log: # 21. enqueueAtTop and run backwards
09-16 10:44:01.415  5587  5633 I jxcore-log: 
,09-16 10:44:01.534  5587  5633 I jxcore-log: ok 72 thirdPromise - first to run
09-16 10:44:01.534  5587  5633 I jxcore-log: 
,09-16 10:44:01.537  5587  5633 I jxcore-log: ok 73 thirdPromise - in resolve
09-16 10:44:01.537  5587  5633 I jxcore-log: 
09-16 10:44:01.538  5587  5633 I jxcore-log: ok 74 secondPromise - second to run
09-16 10:44:01.538  5587  5633 I jxcore-log: 
,09-16 10:44:01.540  5587  5633 I jxcore-log: ok 75 secondPromise - in catch
09-16 10:44:01.540  5587  5633 I jxcore-log: 
,09-16 10:44:01.543  5587  5633 I jxcore-log: ok 76 firstPromise - third to run
09-16 10:44:01.543  5587  5633 I jxcore-log: 
,09-16 10:44:01.546  5587  5633 I jxcore-log: ok 77 firstPromise - in then
09-16 10:44:01.546  5587  5633 I jxcore-log: 
,09-16 10:44:01.550  5587  5633 I jxcore-log: ok 78 testing promises
09-16 10:44:01.550  5587  5633 I jxcore-log: 
,09-16 10:44:01.554  5587  5633 I jxcore-log: # teardown
09-16 10:44:01.554  5587  5633 I jxcore-log: 
,09-16 10:44:01.614  5587  5633 I jxcore-log: # setup
09-16 10:44:01.614  5587  5633 I jxcore-log: 
,09-16 10:44:01.674  5587  5633 I jxcore-log: # 22. mix enqueue and enqueueAtTop
09-16 10:44:01.674  5587  5633 I jxcore-log: 
,09-16 10:44:01.746  5587  5633 I jxcore-log: ok 79 fourth
09-16 10:44:01.746  5587  5633 I jxcore-log: 
,09-16 10:44:01.748  5587  5633 I jxcore-log: ok 80 fourth
09-16 10:44:01.748  5587  5633 I jxcore-log: 
,09-16 10:44:01.750  5587  5633 I jxcore-log: ok 81 second
09-16 10:44:01.750  5587  5633 I jxcore-log: 
09-16 10:44:01.753  5587  5633 I jxcore-log: ok 82 secondPromise - in then
09-16 10:44:01.753  5587  5633 I jxcore-log: 
,09-16 10:44:01.858  5587  5633 I jxcore-log: ok 83 first
09-16 10:44:01.858  5587  5633 I jxcore-log: 
,09-16 10:44:01.863  5587  5633 I jxcore-log: ok 84 firstPromise - in catch
09-16 10:44:01.863  5587  5633 I jxcore-log: 
,09-16 10:44:01.866  5587  5633 I jxcore-log: ok 85 third
09-16 10:44:01.866  5587  5633 I jxcore-log: 
,09-16 10:44:01.869  5587  5633 I jxcore-log: ok 86 thirdPromise - in then
09-16 10:44:01.869  5587  5633 I jxcore-log: 
,09-16 10:44:01.869   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
09-16 10:44:01.871  5587  5633 I jxcore-log: ok 87 testingPromises
09-16 10:44:01.871  5587  5633 I jxcore-log: 
,09-16 10:44:01.880  5587  5633 I jxcore-log: # teardown
09-16 10:44:01.880  5587  5633 I jxcore-log: 
,09-16 10:44:01.934  5587  5633 I jxcore-log: # setup
09-16 10:44:01.934  5587  5633 I jxcore-log: 
,09-16 10:44:02.039  5587  5633 I jxcore-log: # 23. queues handled independently
09-16 10:44:02.039  5587  5633 I jxcore-log: 
,09-16 10:44:02.279  5587  5633 I jxcore-log: ok 88 all short operations completed before the long resolves
09-16 10:44:02.279  5587  5633 I jxcore-log: 
,09-16 10:44:02.301  5587  5633 I jxcore-log: # teardown
09-16 10:44:02.301  5587  5633 I jxcore-log: 
,09-16 10:44:02.350  5587  5633 I jxcore-log: # setup
09-16 10:44:02.350  5587  5633 I jxcore-log: 
,09-16 10:44:02.445  5587  5633 I jxcore-log: # 24. basic
09-16 10:44:02.445  5587  5633 I jxcore-log: 
,09-16 10:44:02.516  5587  5633 I jxcore-log: ok 89 sane
09-16 10:44:02.516  5587  5633 I jxcore-log: 
,09-16 10:44:02.521  5587  5633 I jxcore-log: # teardown
09-16 10:44:02.521  5587  5633 I jxcore-log: 
,09-16 10:44:02.569  5587  5633 I jxcore-log: # setup
09-16 10:44:02.569  5587  5633 I jxcore-log: 
,09-16 10:44:02.681  5587  5633 I jxcore-log: # 25. another
09-16 10:44:02.681  5587  5633 I jxcore-log: 
,09-16 10:44:02.737  5587  5633 I jxcore-log: ok 90 sane
09-16 10:44:02.737  5587  5633 I jxcore-log: 
,09-16 10:44:02.741  5587  5633 I jxcore-log: # teardown
09-16 10:44:02.741  5587  5633 I jxcore-log: 
,09-16 10:44:02.814  5587  5633 I jxcore-log: # setup
09-16 10:44:02.814  5587  5633 I jxcore-log: 
,09-16 10:44:02.878  5587  5633 I jxcore-log: # 26. can pass data in setup
09-16 10:44:02.878  5587  5633 I jxcore-log: 
,09-16 10:44:02.938  5587  5633 I jxcore-log: [{"uuid":"27b69e3c-c9aa-4e9a-b783-4e41421b27ce","data":"custom data"},{"uuid":"8c26536f-9509-43b0-96a0-05e9f5e08408","data":"custom data"},{"uuid":"20acf350-cc66-4dc6-be9b-ad9679c85c1a","data":"custom data"}]
09-16 10:44:02.938  5587  5633 I jxcore-log: 
,09-16 10:44:02.940  5587  5633 I jxcore-log: ok 91 test participant has uuid
09-16 10:44:02.940  5587  5633 I jxcore-log: 
,09-16 10:44:02.941  5587  5633 I jxcore-log: ok 92 participant data matches
09-16 10:44:02.941  5587  5633 I jxcore-log: 
,09-16 10:44:02.942  5587  5633 I jxcore-log: ok 93 test participant has uuid
09-16 10:44:02.942  5587  5633 I jxcore-log: 
09-16 10:44:02.943  5587  5633 I jxcore-log: ok 94 participant data matches
09-16 10:44:02.943  5587  5633 I jxcore-log: 
,09-16 10:44:02.944  5587  5633 I jxcore-log: ok 95 test participant has uuid
09-16 10:44:02.944  5587  5633 I jxcore-log: 
09-16 10:44:02.946  5587  5633 I jxcore-log: ok 96 participant data matches
09-16 10:44:02.946  5587  5633 I jxcore-log: 
,09-16 10:44:02.947  5587  5633 I jxcore-log: ok 97 own UUID is found from the participants list
09-16 10:44:02.947  5587  5633 I jxcore-log: 
,09-16 10:44:02.951  5587  5633 I jxcore-log: # teardown
09-16 10:44:02.951  5587  5633 I jxcore-log: 
,09-16 10:44:03.018  5587  5633 I jxcore-log: # setup
09-16 10:44:03.018  5587  5633 I jxcore-log: 
,09-16 10:44:03.128  5587  5633 I jxcore-log: # 27. #startListeningForAdvertisements should fail if start not called
09-16 10:44:03.128  5587  5633 I jxcore-log: 
,09-16 10:44:03.192  5587  5633 I jxcore-log: ok 98 specific error should be returned
09-16 10:44:03.192  5587  5633 I jxcore-log: 
,09-16 10:44:03.196  5587  5633 I jxcore-log: # teardown
09-16 10:44:03.196  5587  5633 I jxcore-log: 
,09-16 10:44:03.276  5587  5633 I jxcore-log: ok 99 error should be null
09-16 10:44:03.276  5587  5633 I jxcore-log: 
,09-16 10:44:03.278  5587  5633 I jxcore-log: ok 100 error should be null
09-16 10:44:03.278  5587  5633 I jxcore-log: 
,09-16 10:44:03.283  5587  5633 I jxcore-log: # setup
09-16 10:44:03.283  5587  5633 I jxcore-log: 
,09-16 10:44:03.334  5587  5633 I jxcore-log: # 28. #startUpdateAdvertisingAndListening should fail if start not called
09-16 10:44:03.334  5587  5633 I jxcore-log: 
,09-16 10:44:03.396  5587  5633 I jxcore-log: ok 101 specific error should be returned
09-16 10:44:03.396  5587  5633 I jxcore-log: 
,09-16 10:44:03.399  5587  5633 I jxcore-log: # teardown
09-16 10:44:03.399  5587  5633 I jxcore-log: 
,09-16 10:44:03.467  5587  5633 I jxcore-log: ok 102 error should be null
09-16 10:44:03.467  5587  5633 I jxcore-log: 
,09-16 10:44:03.469  5587  5633 I jxcore-log: ok 103 error should be null
09-16 10:44:03.469  5587  5633 I jxcore-log: 
,09-16 10:44:03.474  5587  5633 I jxcore-log: # setup
09-16 10:44:03.474  5587  5633 I jxcore-log: 
,09-16 10:44:03.576  5587  5633 I jxcore-log: # 29. should be able to call #stopListeningForAdvertisements many times
09-16 10:44:03.576  5587  5633 I jxcore-log: 
,09-16 10:44:03.797  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 41535
09-16 10:44:03.797  5587  5633 I jxcore-log: 
,09-16 10:44:03.798  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:44:03.798  5587  5633 I jxcore-log: 
,09-16 10:44:03.799  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 40578
09-16 10:44:03.799  5587  5633 I jxcore-log: 
,09-16 10:44:03.802  5587  5633 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 10:44:03.803  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 10:44:03.803  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 10:44:03.803  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:44:03.805  5587  5633 I jxcore-log: ok 104 error should be null
09-16 10:44:03.805  5587  5633 I jxcore-log: 
,09-16 10:44:03.806  5587  5633 I jxcore-log: ok 105 error should be null
09-16 10:44:03.806  5587  5633 I jxcore-log: 
,09-16 10:44:03.806  5587  5633 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 10:44:03.806  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 10:44:03.806  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 10:44:03.806  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:44:03.809  5587  5633 I jxcore-log: ok 106 error should be null
09-16 10:44:03.809  5587  5633 I jxcore-log: 
,09-16 10:44:03.809  5587  5633 I jxcore-log: ok 107 error should be null
09-16 10:44:03.809  5587  5633 I jxcore-log: 
,09-16 10:44:03.812  5587  5633 I jxcore-log: # teardown
09-16 10:44:03.812  5587  5633 I jxcore-log: 
,09-16 10:44:03.913  5587  5633 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 10:44:03.914  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:44:03.914  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:44:03.914  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:44:03.920  5587  5633 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 10:44:03.921  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-16 10:44:03.921  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 10:44:03.921  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:44:03.931  5587  5633 I jxcore-log: ok 108 error should be null
09-16 10:44:03.931  5587  5633 I jxcore-log: 
,09-16 10:44:03.932  5587  5633 I jxcore-log: ok 109 error should be null
09-16 10:44:03.932  5587  5633 I jxcore-log: 
,09-16 10:44:03.940  5587  5633 I jxcore-log: # setup
09-16 10:44:03.940  5587  5633 I jxcore-log: 
,09-16 10:44:04.025  5587  5633 I jxcore-log: # 30. should be able to call #startListeningForAdvertisements many times
09-16 10:44:04.025  5587  5633 I jxcore-log: 
,09-16 10:44:04.112  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 42036
09-16 10:44:04.112  5587  5633 I jxcore-log: 
,09-16 10:44:04.114  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:44:04.114  5587  5633 I jxcore-log: 
,09-16 10:44:04.119  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 38229
09-16 10:44:04.119  5587  5633 I jxcore-log: 
,09-16 10:44:04.127  5587  5633 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 10:44:04.132  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,09-16 10:44:04.132  5587  5633 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 10:44:04.132  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:44:04.132  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 10:44:04.132  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 10:44:04.132  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:44:04.132  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 10:44:04.137  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 10:44:04.138  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 10:44:04.143  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 10:44:04.143  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 10:44:04.143  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 10:44:04.146  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 10:44:04.146  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 10:44:04.146  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 10:44:04.147  5587  5633 D BluetoothAdapter: STATE_ON
09-16 10:44:04.149  5866  5895 D BtGatt.GattService: registerClient() - UUID=3f367ddc-8824-489e-8b47-818067965c35
09-16 10:44:04.150  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=3f367ddc-8824-489e-8b47-818067965c35, clientIf=5
09-16 10:44:04.150  5587  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 10:44:04.150  5866  5876 D BtGatt.GattService: start scan with filters
,09-16 10:44:04.153  5866  5885 D BtGatt.ScanManager: handling starting scan
,09-16 10:44:04.154  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 10:44:04.154  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 10:44:04.154  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 10:44:04.154  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 10:44:04.157  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:44:04.157  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 10:44:04.157  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 10:44:04.158  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 10:44:04.160  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
09-16 10:44:04.160  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 10:44:04.160  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:44:04.160  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 10:44:04.167  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 10:44:04.167  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:44:04.167  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
09-16 10:44:04.167  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 10:44:04.178  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 10:44:04.179  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:44:04.184  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 10:44:04.184  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:44:04.658  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 10:44:04.658  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:44:04.658  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:44:04.667  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 10:44:04.667  5587  5633 I jxcore-log: 
,09-16 10:44:04.670  5587  5633 I jxcore-log: ok 110 error should be null
09-16 10:44:04.670  5587  5633 I jxcore-log: 
09-16 10:44:04.671  5587  5633 I jxcore-log: ok 111 error should be null
09-16 10:44:04.671  5587  5633 I jxcore-log: 
,09-16 10:44:04.678  5587  5633 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-16 10:44:04.682  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,09-16 10:44:04.682  5587  5633 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 10:44:04.682  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 10:44:04.682  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:44:04.682  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 10:44:04.685  5587  5633 I jxcore-log: ok 112 error should be null
09-16 10:44:04.685  5587  5633 I jxcore-log: 
,09-16 10:44:04.686  5587  5633 I jxcore-log: ok 113 error should be null
09-16 10:44:04.686  5587  5633 I jxcore-log: 
,09-16 10:44:04.690  5587  5633 I jxcore-log: # teardown
09-16 10:44:04.690  5587  5633 I jxcore-log: 
,09-16 10:44:04.839  5587  5633 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 10:44:04.840  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:44:04.840  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 10:44:04.840  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 10:44:04.840  5587  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 10:44:04.841  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-16 10:44:04.841  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 10:44:04.841  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 10:44:04.841  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 10:44:04.841  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:44:04.841  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 10:44:04.841  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 10:44:04.846  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:44:04.848  5866  5876 D BtGatt.GattService: stopScan() - queue size =1
,09-16 10:44:04.850  5866  5896 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 10:44:04.851  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 10:44:04.851  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 10:44:04.851  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 10:44:04.851  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 10:44:04.851  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 10:44:04.857  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 10:44:04.857  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 10:44:04.857  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 10:44:04.858  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 10:44:04.858  5866  5866 D BtGatt.ScanManager: awakened up at time 481802
,09-16 10:44:04.863  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 10:44:04.865  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 10:44:04.865  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:44:04.865  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
09-16 10:44:04.865  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:44:04.865  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:44:04.866  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 10:44:04.868  5587  5633 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 10:44:04.868  5587  5633 I jxcore-log: 
,09-16 10:44:04.873  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 10:44:04.874  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 10:44:04.874  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 10:44:04.881  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 10:44:04.881  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 10:44:05.367  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-16 10:44:05.367  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 10:44:05.367  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:44:05.371  5587  5633 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-16 10:44:05.372  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 10:44:05.372  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 10:44:05.372  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:44:05.376  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 10:44:05.376  5587  5633 I jxcore-log: 
,09-16 10:44:05.384  5587  5633 I jxcore-log: ok 114 error should be null
09-16 10:44:05.384  5587  5633 I jxcore-log: 
,09-16 10:44:05.385  5587  5633 I jxcore-log: ok 115 error should be null
09-16 10:44:05.385  5587  5633 I jxcore-log: 
,09-16 10:44:05.391  5587  5633 I jxcore-log: # setup
09-16 10:44:05.391  5587  5633 I jxcore-log: 
,09-16 10:44:05.470  5587  5633 I jxcore-log: # 31. should be able to call #startUpdateAdvertisingAndListening many times
09-16 10:44:05.470  5587  5633 I jxcore-log: 
,09-16 10:44:05.559  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 48884
09-16 10:44:05.559  5587  5633 I jxcore-log: 
,09-16 10:44:05.561  5587  5633 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 10:44:05.561  5587  5633 I jxcore-log: 
,09-16 10:44:05.566  5587  5633 I jxcore-log: DEBUG createNativeListener: listening 44192
09-16 10:44:05.566  5587  5633 I jxcore-log: 
,09-16 10:44:05.583  5587  5633 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 10:44:05.587  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 44192, start advertisements: true
09-16 10:44:05.587  5587  5633 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 10:44:05.587  5587  5633 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-16 10:44:05.587  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-16 10:44:05.587  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 10:44:05.587  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 10:44:05.587  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 10:44:05.588  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:44:05.589  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 10:44:05.591  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 10:44:05.591  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 10:44:05.591  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-16 10:44:05.591  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 10:44:05.591  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 10:44:05.591  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 10:44:05.591  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 10:44:05.592  5587  5973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 10:44:05.589  5895  5895 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33512]" dev="sockfs" ino=33512 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 10:44:05.594  5587  5633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 10:44:05.589  5895  5895 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33512]" dev="sockfs" ino=33512 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 10:44:05.595  5587  5633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 10:44:05.595  5587  5973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-16 10:44:05.599  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 10:44:05.599  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 10:44:05.600  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 10:44:05.602  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-16 10:44:05.602  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:44:05.602  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-16 10:44:05.602  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 10:44:05.602  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 10:44:05.602  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-16 10:44:05.603  5587  5633 D BluetoothAdapter: STATE_ON
,09-16 10:44:05.607  5866  5877 D BtGatt.GattService: registerClient() - UUID=fd868cfe-4467-4fef-854a-e937c02dbc61
,09-16 10:44:05.607  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=fd868cfe-4467-4fef-854a-e937c02dbc61, clientIf=5
,09-16 10:44:05.607  5587  5598 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-16 10:44:05.609  5866  5884 D BtGatt.AdvertiseManager: message : 0
09-16 10:44:05.611  5866  5884 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 10:44:05.621  5866  5882 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 10:44:05.626  5866  5882 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 10:44:05.627  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-16 10:44:05.627  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 10:44:05.628  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 10:44:05.629  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
09-16 10:44:05.630  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 10:44:05.630  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-16 10:44:05.630  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 10:44:05.630  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 10:44:05.630  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 10:44:05.630  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-16 10:44:05.631  5587  5633 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 48468
09-16 10:44:05.631  5587  5633 I jxcore-log: 
09-16 10:44:05.633  5587  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 10:44:05.633  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 10:44:06.134  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 10:44:06.134  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 10:44:06.134  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 10:44:06.145  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 10:44:06.145  5587  5633 I jxcore-log: 
,09-16 10:44:06.148  5587  5633 I jxcore-log: ok 116 error should be null
09-16 10:44:06.148  5587  5633 I jxcore-log: 
,09-16 10:44:06.149  5587  5633 I jxcore-log: ok 117 error should be null
09-16 10:44:06.149  5587  5633 I jxcore-log: 
,09-16 10:44:06.160  5587  5633 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-16 10:44:06.165  5587  5633 I io.jxcore.node.ConnectionHelper: start: Port number: 44192, start advertisements: true
,09-16 10:44:06.165  5587  5633 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-16 10:44:06.165  5587  5633 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-16 10:44:06.165  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-16 10:44:06.166  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-16 10:44:06.167  5866  5884 D BtGatt.AdvertiseManager: message : 1
09-16 10:44:06.169  5866  5884 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 10:44:06.183  5866  5882 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 10:44:06.183  5866  5882 D BtGatt.GattService: Client app is not null!
,09-16 10:44:06.184  5866  5877 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 10:44:06.186  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 10:44:06.186  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 10:44:06.186  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 10:44:06.186  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-16 10:44:06.186  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 10:44:06.186  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,09-16 10:44:06.187  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 10:44:06.187  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 10:44:06.187  5587  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-16 10:44:06.189  5587  5633 D BluetoothAdapter: STATE_ON
09-16 10:44:06.192  5866  5877 D BtGatt.GattService: registerClient() - UUID=f3448b92-07a8-4bf6-86b6-3434325ed6c7
09-16 10:44:06.193  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=f3448b92-07a8-4bf6-86b6-3434325ed6c7, clientIf=5
09-16 10:44:06.193  5587  5597 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 10:44:06.194  5866  5884 D BtGatt.AdvertiseManager: message : 0
,09-16 10:44:06.200  5866  5884 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 10:44:06.213  5866  5882 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 10:44:06.221  5866  5882 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 10:44:06.222  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-16 10:44:06.222  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-16 10:44:06.222  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 10:44:06.222  5587  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 10:44:06.222  5587  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 10:44:06.222  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 10:44:06.222  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 10:44:06.223  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 10:44:06.223  5587  5633 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 10:44:06.230  5587  5633 I jxcore-log: ok 118 error should be null
09-16 10:44:06.230  5587  5633 I jxcore-log: 
,09-16 10:44:06.232  5587  5633 I jxcore-log: ok 119 error should be null
09-16 10:44:06.232  5587  5633 I jxcore-log: 
,09-16 10:44:06.236  5587  5633 I jxcore-log: # teardown
09-16 10:44:06.236  5587  5633 I jxcore-log: 
,09-16 10:44:06.547  5587  5633 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-16 10:44:06.548  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 10:44:06.548  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-16 10:44:06.548  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 10:44:06.548  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-16 10:44:06.549  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-16 10:44:06.549  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 10:44:06.549  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-16 10:44:06.549  5587  5973 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 10:44:06.549  5587  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 10:44:06.549  5587  5973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 10:44:06.550  5587  5633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 10:44:06.550  5587  5973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 10:44:06.550  5587  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 10:44:06.550  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 10:44:06.550  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 10:44:06.550  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 10:44:06.550  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 10:44:06.553  5587  5633 D BluetoothAdapter: STATE_ON
09-16 10:44:06.554  5587  5633 D BluetoothLeScanner: could not find callback wrapper
09-16 10:44:06.554  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 10:44:06.554  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-16 10:44:06.556  5866  5884 D BtGatt.AdvertiseManager: message : 1
09-16 10:44:06.558  5866  5884 D BtGatt.AdvertiseManager: stop advertise for client 5
09-16 10:44:06.573  5866  5882 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-16 10:44:06.573  5866  5882 D BtGatt.GattService: Client app is not null!
09-16 10:44:06.575  5866  5877 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 10:44:06.576  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 10:44:06.576  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-16 10:44:06.576  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-16 10:44:06.576  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-16 10:44:06.577  5587  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-16 10:44:06.580  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:44:06.580  5587  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 10:44:06.580  5587  5633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 10:44:06.581  5587  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 10:44:06.584  5587  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 10:44:06.584  5587  5587 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 10:44:06.584  5587  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-16 10:44:06.584  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:44:06.584  5587  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 10:44:06.584  5587  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 10:44:06.586  5587  5633 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-16 10:44:06.586  5587  5633 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-16 10:44:06.586  5587  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 10:44:06.586  5587  5633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 10:44:06.594  5587  5633 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-16 10:44:06.594  5587  5633 I jxcore-log: 
,09-16 10:44:06.599  5587  5633 I jxcore-log: ok 120 error should be null
09-16 10:44:06.599  5587  5633 I jxcore-log: 
,09-16 10:44:06.600  5587  5633 I jxcore-log: ok 121 error should be null
09-16 10:44:06.600  5587  5633 I jxcore-log: 
,09-16 10:44:06.605  5587  5633 I jxcore-log: # setup
09-16 10:44:06.605  5587  5633 I jxcore-log: 
,09-16 10:44:07.085  5587  5587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 10:44:07.088  5587  5633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 10:44:07.088  5587  5633 I jxcore-log: 
,09-16 10:44:11.871   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:12.872   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:13.873   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:14.874   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:15.876   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:16.877   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:44:31.878   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:32.880   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:33.881   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:34.883   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:35.884   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:36.884   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:44:46.156   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:44:49.779   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:44:52.806   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:44:56.886   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:57.887   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:58.889   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:44:59.890   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:45:00.892   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:45:01.892   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:45:04.925   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:06.157   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:45:07.955   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:20.068   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:26.116   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:26.893   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:45:26.894   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:45:38.215   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:41.248   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:46.160   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:45:47.322   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:50.352   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:51.979   535  1407 E QC-QMI  : qmi_client [535] 11: failed to locate client data
,09-16 10:45:51.981   518   518 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-16 10:45:51.982   518   518 E QC-QMI  : QMUX qmux_client_id=11 not found in qmux client list, unable to remove
,09-16 10:45:51.987   535   535 I Atfwd_Daemon: Stop the daemon....
,09-16 10:45:52.020  5977  5977 I libmdmdetect: ESOC framework not supported
,09-16 10:45:52.020  5977  5977 I libmdmdetect: Found internal modem: modem
09-16 10:45:52.015  5977  5977 W ATFWD-daemon: type=1400 audit(0.0:120): avc: denied { read write } for name="diag" dev="tmpfs" ino=12580 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
09-16 10:45:52.021  5977  5977 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-16 10:45:52.026  5977  5977 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-16 10:45:52.026  5977  5977 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 10:45:52.027  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:45:53.031  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:45:54.032  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:45:55.033  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:45:56.034  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:45:56.413   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:45:57.035  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:45:59.445   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:02.036  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:03.037  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:04.038  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:05.039  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:06.041  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:06.161   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:46:07.041  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:46:11.551   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:14.587   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:17.042  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:18.043  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:19.044  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:20.045  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:21.046  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:22.047  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:46:26.162   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:46:29.722   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:32.756   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:35.788   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:37.048  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:38.049  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:39.050  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:40.051  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:41.052  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:46:41.839   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:42.053  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:46:44.880   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:47.900   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:50.941   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:46:53.958   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:00.004   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:02.054  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:03.036   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:03.055  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:04.056  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:05.057  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:06.058  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:06.164   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:47:07.059  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:47:15.158   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:21.216   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:26.167   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:47:32.059  5977  5977 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:47:32.060  5977  5977 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:47:33.333   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:36.361   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:37.060  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:38.062  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:39.063  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:39.390   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:40.064  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:41.065  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:42.066  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:47:42.421   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:46.168   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:47:47.067  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:48.067  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:49.069  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:50.070  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:51.071  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:47:51.515   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:47:52.071  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:47:54.546   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:00.597   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:02.072  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:03.073  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:03.627   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:04.074  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:05.075  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:06.076  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:06.169   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:48:07.077  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:48:09.686   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:12.717   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:18.770   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:21.798   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:22.078  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:23.079  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:24.081  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:25.082  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:26.083  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:26.170   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:48:27.084  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:48:39.973   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:42.991   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:46.021   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:47.085  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:48.086  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:49.042   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:48:49.087  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:50.088  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:51.089  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:48:52.090  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:49:06.173   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:49:17.091  5977  5977 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:49:17.092  5977  5977 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:49:26.174   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:49:27.093  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:28.094  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:28.407   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:49:29.095  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:30.097  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:31.098  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:31.431   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:49:32.099  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:49:37.100  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:38.101  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:39.102  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:40.103  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:41.105  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:42.106  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:49:46.178   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:49:52.107  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:53.109  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:54.110  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:55.111  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:56.112  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:49:57.113  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:50:06.179   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:50:12.115  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:13.116  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:14.118  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:15.119  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:16.120  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:17.121  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:50:26.180   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:50:34.972   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:50:37.123  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:38.004   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:50:38.125  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:39.126  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:40.128  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:41.129  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:50:42.130  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:50:46.183   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:51:06.184   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:51:07.131  5977  5977 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:51:07.131  5977  5977 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:51:22.132  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:23.134  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:24.135  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:25.137  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:26.138  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:27.139  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:51:32.141  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:33.142  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:34.144  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:35.146  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:36.147  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:37.148  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:51:46.187   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:51:47.150  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:48.151  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:49.152  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:50.154  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:51.156  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:51:52.156  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:51:59.691   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:52:02.722   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:52:06.189   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:52:07.158  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:08.159  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:09.160  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:10.162  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:11.163  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:12.164  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:52:26.192   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:52:32.165  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:33.000   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:52:33.166  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:34.167  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:35.168  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:36.034   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:52:36.170  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:52:37.170  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:52:46.194   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:53:00.269   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:53:02.171  5977  5977 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:53:02.171  5977  5977 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:53:03.306   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:53:06.197   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:53:22.173  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:23.174  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:24.175  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:25.176  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:26.177  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:26.200   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:53:27.178  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:53:27.505   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:53:30.535   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:53:32.179  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:33.181  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:34.182  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:35.184  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:36.185  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:37.186  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:53:46.201   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:53:47.187  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:48.189  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:49.190  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:50.191  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:51.193  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:53:52.193  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:53:54.760   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:53:57.793   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:54:06.204   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:54:07.194  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:08.195  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:09.197  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:10.198  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:11.199  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:12.200  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:54:26.206   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:54:32.201  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:33.203  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:34.204  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:35.205  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:36.206  5977  5977 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:54:37.207  5977  5977 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:54:46.210   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:55:02.208  5977  5977 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:55:02.209  5977  5977 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:55:06.211   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:55:27.218  5977  5979 E QC-QMI  : qmi_client [5977] 1d: failed to locate client data
,09-16 10:55:27.221   518   518 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
09-16 10:55:27.221   518   518 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-16 10:55:27.226  5977  5977 I Atfwd_Daemon: Stop the daemon....
,09-16 10:55:27.260  5995  5995 I libmdmdetect: ESOC framework not supported
09-16 10:55:27.261  5995  5995 I libmdmdetect: Found internal modem: modem
,09-16 10:55:27.261  5995  5995 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-16 10:55:27.255  5995  5995 W ATFWD-daemon: type=1400 audit(0.0:121): avc: denied { read write } for name="diag" dev="tmpfs" ino=12580 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-16 10:55:27.266  5995  5995 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-16 10:55:27.266  5995  5995 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 10:55:27.267  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:28.270  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:29.271  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:30.273  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:31.274  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:32.274  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:55:37.276  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:38.277  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:39.279  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:40.280  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:41.282  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:42.253   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1179197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:55:42.283  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:55:46.215   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:55:52.284  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:53.285  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:54.000   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1190944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:55:54.286  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:55.287  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:56.289  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:55:57.290  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:55:58.854   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:56:04.913   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:56:06.216   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:56:07.266   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1204210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:56:12.291  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:13.293  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:14.003   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:56:14.294  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:15.295  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:16.297  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:17.027   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:56:17.298  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:56:19.040   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1215984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:56:22.282   927   939 I UsageStatsService: User[0] Flushing usage stats to disk
,09-16 10:56:26.217   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:56:32.386   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1229330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:56:35.199   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:56:37.299  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:38.235   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:56:38.300  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:39.301  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:40.302  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:41.304  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:56:42.305  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:56:44.120   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1241064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-16 10:56:46.219   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:57:02.413   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1259357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:57:06.221   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:57:07.306  5995  5995 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:57:07.306  5995  5995 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:57:09.159   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1266103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-16 10:57:12.307  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:13.308  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:14.309  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:15.311  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:16.312  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:17.313  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:57:22.314  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:23.316  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:24.317  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:25.319  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:26.225   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:57:26.320  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:26.632   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:57:27.321  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:57:27.483   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1284427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:57:29.666   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:57:32.694   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:57:34.199   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1291143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-16 10:57:35.737   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:57:37.322  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:38.324  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:38.771   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:57:39.325  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:40.326  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:41.328  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:41.808   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:57:42.329  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:57:46.227   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:57:52.493   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1309437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:57:57.330  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:58.332  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:57:59.240   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1316184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:57:59.333  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:58:00.335  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:58:01.336  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:58:02.337  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:58:03.007   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:58:06.046   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:58:06.227   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:58:12.212   927   936 I art     : Background sticky concurrent mark sweep GC freed 130674(9MB) AllocSpace objects, 127(3MB) LOS objects, 30% free, 30MB/43MB, paused 3.051ms total 102.446ms
,09-16 10:58:12.546   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1329490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:58:15.132   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:58:18.159   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:58:22.338  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:58:23.340  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:58:24.217   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:58:24.279   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1341223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:58:24.341  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:58:25.342  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:58:26.229   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:58:26.344  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:58:27.254   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:58:27.344  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 10:58:30.291   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:58:33.317   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:58:37.559   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1354503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:58:46.231   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:58:49.320   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1366264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:58:52.345  5995  5995 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 10:58:52.346  5995  5995 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 10:59:02.347  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:02.626   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1379570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:59:03.348  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:04.350  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:05.351  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:06.232   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:59:06.352  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:07.352  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 10:59:12.354  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:13.355  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:14.357  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:14.373   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1391317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:59:15.358  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:16.359  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:17.360  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 10:59:18.682   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:59:21.711   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:59:26.235   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:59:27.361  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:27.693   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1404637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 10:59:28.362  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:29.364  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:30.365  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:31.367  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:32.368  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 10:59:39.413   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1416357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 10:59:39.881   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:59:45.935   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 10:59:46.236   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 10:59:47.369  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:48.371  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:49.372  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:50.374  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:51.375  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 10:59:52.376  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 10:59:52.706   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1429650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:00:04.103   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:00:04.453   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1441397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:00:06.239   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:00:07.130   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:00:12.378  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:00:13.379  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:00:14.380  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:00:15.382  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:00:16.384  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:00:17.385  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 11:00:17.773   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1454717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:00:26.241   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:00:29.493   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1466437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:00:36.146   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1473090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:00:42.386  5995  5995 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:00:42.386  5995  5995 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 11:00:46.244   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:00:46.507   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:00:49.543   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:00:52.574   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:00:54.546   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1491490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:00:55.608   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:00:57.387  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:00:58.389  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:00:59.390  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:00.391  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:01.186   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1498130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:01:01.393  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:01.673   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:01:02.394  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 11:01:04.705   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:01:06.247   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:01:07.395  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:08.396  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:09.398  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:10.399  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:10.769   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:01:11.401  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:12.402  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 11:01:13.791   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:01:19.586   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1516530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:01:22.403  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:22.876   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:01:23.404  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:24.406  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:25.407  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:25.910   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:01:26.226   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1523170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:01:26.409  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:27.410  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 11:01:31.960   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:01:34.983   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:01:42.412  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:43.413  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:44.414  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:44.626   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1541570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:01:45.416  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:46.251   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:01:46.417  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:01:47.418  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 11:01:51.266   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1548210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:01:59.218   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:02:02.248   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:02:06.253   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:02:07.420  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:02:08.421  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:02:09.422  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:02:09.679   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1566623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:02:10.423  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:02:11.425  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:02:12.426  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 11:02:16.307   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1573251, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:02:26.257   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:02:34.719   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1591664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:02:37.426  5995  5995 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:02:37.427  5995  5995 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 11:02:41.347   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1598291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:02:41.605   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:02:44.638   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:02:46.260   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:02:57.428  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:02:58.429  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:02:59.430  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:02:59.760   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1616704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:03:00.432  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:01.433  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:02.433  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 11:03:05.827   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:06.261   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:03:06.399   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1623343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:03:07.435  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:08.437  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:08.870   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:09.438  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:10.440  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:11.441  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:11.904   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:12.442  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 11:03:14.935   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:22.444  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:23.445  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:24.031   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:24.446  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:24.800   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1641744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:03:25.448  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:26.262   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:03:26.449  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:27.071   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:27.450  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 11:03:31.453   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1648397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:03:36.169   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:42.219   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:42.452  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:43.454  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:44.455  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:45.457  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:46.264   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:03:46.458  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:03:47.459  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 11:03:48.289   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:49.853   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1666797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:03:51.328   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:03:56.493   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1673437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:03:57.385   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:04:00.416   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:04:06.267   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:04:06.463   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:04:07.460  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:04:08.462  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:04:09.463  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:04:09.497   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:04:10.465  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:04:11.466  5995  5995 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 11:04:12.467  5995  5995 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 11:04:14.893   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1691837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:04:21.532   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1698477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 11:04:24.626   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:04:26.270   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:04:27.662   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:04:33.715   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:04:36.738   927  3084 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 11:04:37.468  5995  5995 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 11:04:37.469  5995  5995 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 11:04:39.933   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1716877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 11:04:46.272   927  3082 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 11:04:46.573   927  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1723517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-16 11:04:48.825  6005  6005 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 11:04:48.830  6005  6005 D AndroidRuntime: CheckJNI is OFF
09-16 11:04:48.854  6005  6005 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 11:04:48.883  6005  6005 I Radio-JNI: register_android_hardware_Radio DONE
09-16 11:04:48.901  6005  6005 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-16 11:04:48.909   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-16 11:04:48.909   927   940 I ActivityManager: Killing 5587:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
09-16 11:04:48.947   927  3053 W InputDispatcher: channel '1893d07 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-16 11:04:48.947   927  3053 E InputDispatcher: channel '1893d07 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
09-16 11:04:48.954   927  3083 D WifiService: Client connection lost with reason: 4
09-16 11:04:48.954   927   937 I WindowState: WIN DEATH: Window{1893d07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-16 11:04:48.954   927  3519 D GraphicsStats: Buffer count: 2
09-16 11:04:48.954   927   937 W InputDispatcher: Attempted to unregister already unregistered input channel '1893d07 com.test.thalitest/com.test.thalitest.MainActivity (server)'
09-16 11:04:49.030   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-16 11:04:49.030   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-16 11:04:49.031   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-16 11:04:49.031   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-16 11:04:49.031   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.031   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.031   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:04:49.031   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 11:04:49.032   927   940 I ActivityManager:   Force finishing activity ActivityRecord{d971a1a u0 com.test.thalitest/.MainActivity t4}
09-16 11:04:49.034   927   950 I art     : Starting a blocking GC Explicit
09-16 11:04:49.039   927  3519 W ActivityManager: Spurious death for ProcessRecord{d7e0e66 0:com.test.thalitest/u0a77}, curProc for 5587: null
09-16 11:04:49.043   927   945 W WindowManager: Attempted to add application window with unknown token Token{d66394b ActivityRecord{d971a1a u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
09-16 11:04:49.043   927   945 W WindowManager: Token{d66394b ActivityRecord{d971a1a u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{d66394b ActivityRecord{d971a1a u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-16 11:04:49.044   927   945 W WindowManager: view not successfully added to wm, removing view
09-16 11:04:49.044   927   945 W WindowManager: Exception when adding starting window
09-16 11:04:49.044   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{decbcf9 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-16 11:04:49.044   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-16 11:04:49.044   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-16 11:04:49.044   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-16 11:04:49.044   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-16 11:04:49.044   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-16 11:04:49.044   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.044   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.044   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:04:49.044   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 11:04:49.137   927   950 I art     : Explicit concurrent mark sweep GC freed 135687(9MB) AllocSpace objects, 82(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.567ms total 103.539ms
09-16 11:04:49.158   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-16 11:04:49.161  6005  6005 I art     : System.exit called, status: 0
09-16 11:04:49.161  6005  6005 I AndroidRuntime: VM exiting with result code 0.
09-16 11:04:49.173   927   950 I ActivityManager: Start proc 6018:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-16 11:04:49.174   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-16 11:04:49.178   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-16 11:04:49.184  5866  5866 D BluetoothMapAppObserver: onReceive
09-16 11:04:49.184  5866  5866 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-16 11:04:49.188  3771  4064 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-16 11:04:49.194   927  3054 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-16 11:04:49.196  3525  3525 I Keyboard.Facilitator: resetDictionaries() : en_US
09-16 11:04:49.215  3525  6031 I Keyboard.Facilitator.DecoderInitializer: run()
09-16 11:04:49.221  3618  3618 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-16 11:04:49.232  3525  6031 I Decoder : createOrResetDecoder
09-16 11:04:49.248  3513  6033 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-16 11:04:49.265    27    27 W kworker/2:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 11:04:49.271   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-16 11:04:49.272    27    27 W kworker/2:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 11:04:49.278  3709  3709 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-16 11:04:49.278  3709  3709 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-16 11:04:49.282    27    27 W kworker/2:1: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 11:04:49.297   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-16 11:04:49.305   927   939 E PackageManager: Failed to write settings, restoring backup
09-16 11:04:49.305   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-16 11:04:49.305   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-16 11:04:49.305   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-16 11:04:49.305   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-16 11:04:49.305   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-16 11:04:49.305   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.305   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.305   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:04:49.308  4026  6038 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-16 11:04:49.308  4026  6038 D AccountUtils: Clearing selected account for com.test.thalitest
09-16 11:04:49.312   927   940 E DropBoxManagerService: Can't write: system_server_wtf
09-16 11:04:49.312   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 11:04:49.312   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 11:04:49.312   927   940 E DropBoxManagerService: 	... 13 more
09-16 11:04:49.315  3641  3835 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-16 11:04:49.326  3513  3547 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj0D5CE792C) - 
--------- beginning of crash
09-16 11:04:49.327  3513  3547 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-16 11:04:49.327  3513  3547 E AndroidRuntime: Process: android.process.acore, PID: 3513
09-16 11:04:49.327  3513  3547 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.327  3513  3547 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:04:49.328   927  3541 I ActivityManager: Start proc 6041:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-16 11:04:49.329  3641  3835 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-16 11:04:49.329  3641  3835 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3641
09-16 11:04:49.329  3641  3835 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.329  3641  3835 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:04:49.332  3709  3709 I ConfigService: onCreate
09-16 11:04:49.334   927  6049 E DropBoxManagerService: Can't write: system_app_crash
09-16 11:04:49.334   927  6049 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 11:04:49.334   927  6049 E DropBoxManagerService: 	... 5 more
09-16 11:04:49.334   927  3894 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-16 11:04:49.335  3709  6048 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-16 11:04:49.335  3709  6048 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-16 11:04:49.337  3709  6048 W SQLiteOpenHelper: Opened config.db in read-only mode
09-16 11:04:49.339  3641  3835 I Process : Sending signal. PID: 3641 SIG: 9
09-16 11:04:49.352  3525  6031 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-16 11:04:49.375  4026  6038 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.389  4026  6038 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.389  4026  6038 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 11:04:49.390  4026  6038 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
09-16 11:04:49.358  3513  6033 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-16 11:04:49.410  3513  6033 I Process : Sending signal. PID: 3513 SIG: 9
09-16 11:04:49.483   927  3895 D GraphicsStats: Buffer count: 1
09-16 11:04:49.483   927  3681 I WindowState: WIN DEATH: Window{7d291e6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-16 11:04:49.488   927  3259 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3641) has died
09-16 11:04:49.489   927  3259 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-16 11:04:49.490   927  3259 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-16 11:04:49.496  4026  6060 I GMPM-SVC: App measurement is starting up
09-16 11:04:49.504  4026  6060 E GMPM-SVC: AppMeasurementService not registered/enabled
09-16 11:04:49.505  4026  6060 E GMPM-SVC: Uploading is not possible. App measurement disabled
09-16 11:04:49.508   927   940 I ActivityManager: Start proc 6062:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:04:49.553  6062  6062 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:04:49.553  6062  6062 D AndroidRuntime: Shutting down VM
09-16 11:04:49.558  6062  6062 E AndroidRuntime: FATAL EXCEPTION: main
09-16 11:04:49.558  6062  6062 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6062
09-16 11:04:49.558  6062  6062 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 11:04:49.558  6062  6062 E AndroidRuntime: 	... 10 more
09-16 11:04:49.558   927  3509 I ActivityManager: Process android.process.acore (pid 3513) has died
09-16 11:04:49.559   927  3509 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-16 11:04:49.562   927  3894 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 11:04:49.562   927  6076 E DropBoxManagerService: Can't write: system_app_crash
09-16 11:04:49.562   927  6076 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 11:04:49.562   927  6076 E DropBoxManagerService: 	... 5 more
09-16 11:04:49.563  6062  6062 I Process : Sending signal. PID: 6062 SIG: 9
09-16 11:04:49.579   927  3519 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6062) has died
09-16 11:04:49.580   927  3519 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-16 11:04:49.593   927   940 I ActivityManager: Start proc 6077:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:04:49.640  6077  6077 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:04:49.640  6077  6077 D AndroidRuntime: Shutting down VM
09-16 11:04:49.647  6077  6077 E AndroidRuntime: FATAL EXCEPTION: main
09-16 11:04:49.647  6077  6077 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6077
09-16 11:04:49.647  6077  6077 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 11:04:49.647  6077  6077 E AndroidRuntime: 	... 10 more
09-16 11:04:49.650   927  3894 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 11:04:49.650   927  6089 E DropBoxManagerService: Can't write: system_app_crash
09-16 11:04:49.650   927  6089 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 11:04:49.650   927  6089 E DropBoxManagerService: 	... 5 more
09-16 11:04:49.652  6077  6077 I Process : Sending signal. PID: 6077 SIG: 9
09-16 11:04:49.665   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
