#### Test 8796643296748b2_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-07 10:49:10.406   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-07 10:49:10.407   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-07 10:49:10.932  5630  5630 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-07 10:49:10.937  5630  5630 D AndroidRuntime: CheckJNI is OFF
10-07 10:49:10.960  5630  5630 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-07 10:49:10.989  5630  5630 I Radio-JNI: register_android_hardware_Radio DONE
10-07 10:49:11.004  5630  5630 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-07 10:49:11.012   927   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-07 10:49:11.058   927   938 I ActivityManager: Start proc 5639:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-07 10:49:11.077  5630  5630 D AndroidRuntime: Shutting down VM
,10-07 10:49:11.399   927  3096 I WindowManager: Screenshot max retries 4 of Token{5cf2260 ActivityRecord{31e5663 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{1be2edb u0 Starting com.test.thalitest} drawState=2
,10-07 10:49:11.464  5639  5639 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-07 10:49:11.497  5639  5639 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-07 10:49:11.521  5639  5639 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 521-540)
,10-07 10:49:11.522  5639  5639 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-07 10:49:11.541  5639  5639 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5ddc774}
10-07 10:49:11.541  5639  5639 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-07 10:49:11.542  5639  5639 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
10-07 10:49:11.546  5639  5639 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-07 10:49:11.548  5639  5639 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-07 10:49:11.582  5639  5639 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-07 10:49:11.595  5639  5639 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-07 10:49:11.595  5639  5639 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-07 10:49:11.596  5639  5639 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-07 10:49:11.596  5639  5639 I Adreno  : Build Date                       : 12/06/15
10-07 10:49:11.596  5639  5639 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-07 10:49:11.596  5639  5639 I Adreno  : Local Branch                     : mybranch17112971
10-07 10:49:11.596  5639  5639 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-07 10:49:11.596  5639  5639 I Adreno  : Remote Branch                    : NONE
10-07 10:49:11.596  5639  5639 I Adreno  : Reconstruct Branch               : NOTHING
,10-07 10:49:11.668   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e750c8e:true
,10-07 10:49:11.701   927  2954 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 10:49:11.708   951   951 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25581]" dev="sockfs" ino=25581 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 10:49:11.708   951   951 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[25581]" dev="sockfs" ino=25581 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 10:49:11.728  5639  5639 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-07 10:49:11.739  5639  5639 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-07 10:49:11.769  5639  5676 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-07 10:49:11.765   950   950 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33860]" dev="sockfs" ino=33860 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-07 10:49:11.765   950   950 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33860]" dev="sockfs" ino=33860 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 10:49:11.772  3362  3362 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15054]" dev="sockfs" ino=15054 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-07 10:49:11.772  3362  3362 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15054]" dev="sockfs" ino=15054 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-07 10:49:11.777  5639  5663 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-07 10:49:11.809  5639  5676 I OpenGLRenderer: Initialized EGL, version 1.4
,10-07 10:49:11.892   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +492ms (total +860ms)
,10-07 10:49:11.917  5639  5639 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5639
,10-07 10:49:12.005  5639  5639 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-07 10:49:12.232  5639  5679 D jxcore_app_log: JniHelper::setJavaVM(0xf527c000), pthread_self() = -604243664
,10-07 10:49:12.242  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-07 10:49:12.242  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-07 10:49:12.242  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-07 10:49:12.242  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-07 10:49:12.242  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-07 10:49:12.242  5639  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1182415 added. We now have 1 listener(s)
,10-07 10:49:12.244  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
10-07 10:49:12.244  5639  5679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:49:12.245  5639  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-07 10:49:12.246  5639  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-07 10:49:12.251  5639  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d616b8 added. We now have 1 listener(s)
10-07 10:49:12.252  5639  5679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 10:49:12.265   927  2969 D WifiService: New client listening to asynchronous messages
,10-07 10:49:12.266  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-07 10:49:12.266  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-07 10:49:12.266  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-07 10:49:12.266  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-07 10:49:12.266  5639  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-07 10:49:12.269  5639  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:49:12.269  5639  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-07 10:49:12.277  5639  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-07 10:49:12.278  5639  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:49:12.278  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:12.278  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:12.278  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:12.278  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:49:12.278  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:12.278  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:12.278  5639  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:49:12.278  5639  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-07 10:49:12.278  5639  5679 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 10:49:12.278  5639  5679 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-07 10:49:12.284  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:12.288  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:12.298  5639  5639 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-07 10:49:12.922  5639  5648 I art     : Background sticky concurrent mark sweep GC freed 78251(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.509ms total 250.573ms
,10-07 10:49:12.985  5639  5685 W jxcore-log: Initializing JXcore engine
10-07 10:49:12.985  5639  5685 W jxcore-log: JXcore engine is ready
,10-07 10:49:13.015  5685  5685 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12259 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-07 10:49:13.015  5685  5685 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[10615]" dev="sockfs" ino=10615 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-07 10:49:13.015  5685  5685 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-07 10:49:13.015  5685  5685 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33019]" dev="sockfs" ino=33019 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-07 10:49:13.025  5639  5685 W jxcore-log: Starting JXcore engine
,10-07 10:49:13.077  5639  5685 W jxcore-log: Platform android
10-07 10:49:13.077  5639  5685 W jxcore-log: 
,10-07 10:49:13.077  5639  5685 W jxcore-log: Process ARCH arm
10-07 10:49:13.077  5639  5685 W jxcore-log: 
,10-07 10:49:13.175  5639  5685 I jxcore-log: JXcore Cordova bridge is ready!
10-07 10:49:13.175  5639  5685 I jxcore-log: 
,10-07 10:49:13.175  5639  5685 W jxcore-log: JXcore engine is started
,10-07 10:49:13.182  5639  5679 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-07 10:49:13.187  5639  5639 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-07 10:49:20.408   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:21.409   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:22.411   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:23.126  5639  5685 I jxcore-log: 2016-10-07 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-07 10:49:23.126  5639  5685 I jxcore-log: 
,10-07 10:49:23.128  5639  5685 I jxcore-log: 2016-10-07 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-07 10:49:23.128  5639  5685 I jxcore-log: 
,10-07 10:49:23.132  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:49:23.132  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:23.132  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:23.132  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:23.132  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:49:23.132  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:23.132  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:23.132  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:49:23.133  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:49:23.135  5639  5685 I jxcore-log: 2016-10-07 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-07 10:49:23.135  5639  5685 I jxcore-log: 
10-07 10:49:23.136  5639  5685 I jxcore-log: 2016-10-07 14:49:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-07 10:49:23.136  5639  5685 I jxcore-log: 
,10-07 10:49:23.393  5639  5685 I jxcore-log: 2016-10-07 14:49:23 - DEBUG UnitTest_app: 'Running unit tests'
10-07 10:49:23.393  5639  5685 I jxcore-log: 
10-07 10:49:23.393  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 10:49:23.394  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bcab3 added. We now have 2 listener(s)
,10-07 10:49:23.394  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-07 10:49:23.394  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:49:23.394  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:49:23.395  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:49:23.395  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cba0870 added. We now have 2 listener(s)
10-07 10:49:23.395  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:49:23.395  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-07 10:49:23.397  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:49:23.401  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:49:23.401  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:23.401  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:23.401  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:23.401  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:49:23.401  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:23.401  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:23.401  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:49:23.405  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:23.405  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 10:49:23.406  5639  5685 D executeNativeTests: Running unit tests
,10-07 10:49:23.412   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:23.412  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:23.418  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:23.442  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 10:49:23.442  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e added. We now have 3 listener(s)
10-07 10:49:23.443  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:49:23.443  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:49:23.443  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:49:23.443  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 10:49:23.443  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff added. We now have 3 listener(s)
10-07 10:49:23.443  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:49:23.443  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-07 10:49:23.445  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:49:23.447  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:49:23.447  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:23.447  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:23.447  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:23.447  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:49:23.447  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:23.447  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:23.447  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:49:23.448  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:49:23.448  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 10:49:23.449  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-07 10:49:23.450  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-07 10:49:23.450  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 10:49:23.450  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-07 10:49:23.450  5639  5685 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-07 10:49:23.450  5639  5685 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-07 10:49:23.450  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-07 10:49:23.451  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 10:49:23.451  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 10:49:23.451  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 10:49:23.451  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:23.451  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:23.451  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 10:49:23.451  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 10:49:23.451  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:23.451  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-07 10:49:23.452  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:23.452  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:49:23.452  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e removed from the list
,10-07 10:49:23.452  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:23.452  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff removed from the list
10-07 10:49:23.458  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:23.463  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:23.463  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 10:49:23.463  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:23.464  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:23.464  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:23.464  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
10-07 10:49:23.464  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:23.464  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:23.464  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:23.465  5639  5685 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-07 10:49:23.465  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:23.466  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:23.466  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:23.466  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:23.466  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:23.466  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:23.466  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:23.466  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
,10-07 10:49:23.466  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:23.466  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:23.466  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:23.466  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:23.466  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:23.466  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:23.466  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:23.466  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:23.466  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:23.467  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:23.467  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-0,7 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-07 10:49:23.469  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-07 10:49:23.470  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:23.470  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:23.470  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:23.470  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:23.470  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:23.470  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:23.470  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:23.470  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:23.470  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:23.470  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:23.470  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:23.470  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:23.470  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:23.470  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:23.470  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:23.471  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:23.471  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:23.471  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:23.471  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:23.471  5639  5685 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-07 10:49:23.472  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:49:23.474  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:49:23.474  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:23.474  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:23.474  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:23.474  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:49:23.474  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:23.474  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:23.474  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:49:23.475  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:23.475  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 10:49:23.475  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:49:23.475  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 10:49:23.475  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 10:49:23.475  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:49:23.476  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 10:49:23.478  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 10:49:23.478  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 10:49:23.478  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:23.480  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-07 10:49:23.481  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:23.482  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 10:49:23.482  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-07 10:49:23.483  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-07 10:49:23.485  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-07 10:49:23.485  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 10:49:23.485  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 10:49:23.485  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 10:49:23.485  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 10:49:23.485  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 10:49:23.485  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:49:23.488  4515  4714 D BtGatt.GattService: registerClient() - UUID=01b404a4-1db5-4d24-9293-6232cbfc258c
10-07 10:49:23.489  4515  4576 D BtGatt.GattService: onClientRegistered() - UUID=01b404a4-1db5-4d24-9293-6232cbfc258c, clientIf=5
10-07 10:49:23.490  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 10:49:23.491  4515  4713 D BtGatt.GattService: start scan with filters
10-07 10:49:23.498  4515  4579 D BtGatt.ScanManager: handling starting scan
10-07 10:49:23.498  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 10:49:23.499  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 10:49:23.499  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:49:23.499  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 10:49:23.499  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 10:49:23.499  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 10:49:23.499  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-07 10:49:23.500  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:49:23.500  4515  4579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:49:23.500  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 10:49:23.500  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:49:23.500  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 10:49:23.502  5639  5685 I io.jxcore.node.ConnectionHelper: start: OK
10-07 10:49:23.508  4515  4576 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 10:49:23.508  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:23.509  4515  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 10:49:23.517  4515  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 10:49:23.517  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:23.518  4515  4579 D BtGatt.ScanManager: Starting BLE batch scan
10-07 10:49:23.518  4515  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 10:49:23.530  4515  4576 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 10:49:23.530  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:23.537  4515  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 10:49:23.538  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:49:24.002  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-07 10:49:24.002  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:49:24.002  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 10:49:24.413   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:25.413   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-07 10:49:25.577   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 10:49:28.506  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 10:49:28.506  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:28.506  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 10:49:28.506  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:28.506  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 10:49:28.506  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:28.507  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 10:49:28.507  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 10:49:28.507  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 10:49:28.507  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 10:49:28.508  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 10:49:28.508  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 10:49:28.509  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:49:28.509  4515  4529 D BtGatt.GattService: stopScan() - queue size =1
10-07 10:49:28.510  4515  4734 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 10:49:28.511  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 10:49:28.511  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 10:49:28.511  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 10:49:28.511  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:49:28.511  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-07 10:49:28.512  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 10:49:28.512  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 10:49:28.512  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 10:49:28.513  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:49:28.514  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 10:49:28.514  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 10:49:28.514  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 10:49:28.514  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-07 10:49:28.515  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-07 10:49:28.516  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:28.516  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:49:28.517  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:49:28.516  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:49:28.517  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:28.517  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:28.517  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:28.517  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-07 10:49:28.517  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:28.517  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:28.517  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:49:28.517  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:28.520  4515  4515 D BtGatt.ScanManager: awakened up at time 237539
,10-07 10:49:28.530  4515  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-07 10:49:28.530  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:28.530  4515  4579 D BtGatt.ScanManager: stopping BLe Batch
,10-07 10:49:28.541  4515  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-07 10:49:28.541  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:49:28.541  4515  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 10:49:28.567  4515  4576 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
10-07 10:49:28.567  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:49:28.568  4515  4576 D BtGatt.GattService: current time is 237587055904
,10-07 10:49:28.568  4515  4576 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -81, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -82, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -82, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 67, -22, 62, -26, -102, 80, 1, -128, -98, 38, 0, 24, 2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0, 0]
10-07 10:49:28.570  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-07 10:49:28.571  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
10-07 10:49:28.572  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-07 10:49:28.572  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-07 10:49:28.572  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-07 10:49:28.573  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-07 10:49:28.573  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 26, 20, -1, 76, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 0, 0, 0, 0]
,10-07 10:49:28.603   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 10:49:29.018  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 10:49:30.414   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:31.416   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:31.626   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 10:49:31.702   927  2954 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 10:49:32.417   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:33.419   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:33.521  5639  5685 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-07 10:49:33.526  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:49:33.538  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:49:33.538  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:33.538  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:33.538  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:33.538  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:49:33.538  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:33.538  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:33.538  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:49:33.542  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:49:33.542  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 10:49:33.543  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:49:33.543  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 10:49:33.543  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 10:49:33.543  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:49:33.543  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 10:49:33.546  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:33.547  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 10:49:33.547  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 10:49:33.549  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:33.552  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-07 10:49:33.552  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-07 10:49:33.553  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-07 10:49:33.556  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 10:49:33.556  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 10:49:33.556  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 10:49:33.556  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 10:49:33.556  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 10:49:33.557  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:49:33.559  4515  4713 D BtGatt.GattService: registerClient() - UUID=813e9fbc-ea2e-4553-b9a1-2cba1aa01aef
10-07 10:49:33.560  4515  4576 D BtGatt.GattService: onClientRegistered() - UUID=813e9fbc-ea2e-4553-b9a1-2cba1aa01aef, clientIf=5
,10-07 10:49:33.560  5639  5649 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 10:49:33.561  4515  4527 D BtGatt.GattService: start scan with filters
,10-07 10:49:33.564  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-07 10:49:33.564  4515  4579 D BtGatt.ScanManager: handling starting scan
10-07 10:49:33.564  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 10:49:33.564  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-07 10:49:33.564  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 10:49:33.564  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 10:49:33.564  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 10:49:33.564  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 10:49:33.566  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:49:33.566  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 10:49:33.566  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-07 10:49:33.569  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-07 10:49:33.571  4515  4576 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 10:49:33.571  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:33.571  4515  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-07 10:49:33.571  5639  5685 I io.jxcore.node.ConnectionHelper: start: OK
,10-07 10:49:33.574  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:33.574  5639  5685 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-07 10:49:33.574  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:33.574  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 10:49:33.574  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:33.574  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 10:49:33.574  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:33.574  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 10:49:33.574  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 10:49:33.574  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 10:49:33.574  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 10:49:33.574  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 10:49:33.574  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 10:49:33.575  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:49:33.576  4515  4714 D BtGatt.GattService: stopScan() - queue size =1
,10-07 10:49:33.577  4515  4713 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 10:49:33.577  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 10:49:33.577  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 10:49:33.577  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 10:49:33.577  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-07 10:49:33.577  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 10:49:33.577  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 10:49:33.577  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-07 10:49:33.578  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 10:49:33.577  4515  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 10:49:33.578  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:33.578  4515  4579 D BtGatt.ScanManager: Starting BLE batch scan
10-07 10:49:33.578  4515  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 10:49:33.579  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:49:33.579  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 10:49:33.579  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 10:49:33.579  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 10:49:33.579  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 10:49:33.581  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:49:33.582  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:33.582  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:49:33.582  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:33.582  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:49:33.582  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:49:33.582  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:49:33.582  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:33.582  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:33.582  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:33.582  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:33.582  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:33.582  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:33.583  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:33.583  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:33.584  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:33.584  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:33.584  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:33.585  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:33.585  5639  5685 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-07 10:49:33.587  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:49:33.590  4515  4576 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 10:49:33.590  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:49:33.594  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:49:33.594  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:33.594  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:33.594  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:33.594  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:49:33.594  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:33.594  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:33.594  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:49:33.596  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:33.596  4515  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 10:49:33.596  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:33.596  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 10:49:33.597  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:49:33.597  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 10:49:33.597  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 10:49:33.597  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:49:33.597  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-07 10:49:33.599  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:33.601  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 10:49:33.601  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 10:49:33.602  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:33.603  4515  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 10:49:33.603  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:33.603  4515  4579 D BtGatt.ScanManager: stopping BLe Batch
,10-07 10:49:33.604  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-07 10:49:33.604  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 10:49:33.604  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 10:49:33.608  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 10:49:33.608  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 10:49:33.608  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 10:49:33.608  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 10:49:33.608  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 10:49:33.608  4515  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 10:49:33.608  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:33.608  4515  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-07 10:49:33.609  5639  5685 D BluetoothAdapter: STATE_ON
,10-07 10:49:33.611  4515  4527 D BtGatt.GattService: registerClient() - UUID=51717caf-308c-420f-bf1b-0297320d8a79
,10-07 10:49:33.611  4515  4576 D BtGatt.GattService: onClientRegistered() - UUID=51717caf-308c-420f-bf1b-0297320d8a79, clientIf=5
10-07 10:49:33.612  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-07 10:49:33.612  4515  4529 D BtGatt.GattService: start scan with filters
,10-07 10:49:33.613  4515  4576 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 10:49:33.613  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:49:33.615  4515  4579 D BtGatt.ScanManager: handling starting scan
,10-07 10:49:33.616  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 10:49:33.616  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 10:49:33.616  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:49:33.616  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 10:49:33.616  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 10:49:33.616  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 10:49:33.616  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 10:49:33.619  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:49:33.619  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 10:49:33.620  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:49:33.620  4515  4576 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 10:49:33.620  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:33.621  4515  4579 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 10:49:33.621  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-07 10:49:33.623  5639  5685 I io.jxcore.node.ConnectionHelper: start: OK
,10-07 10:49:33.625  4515  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 10:49:33.625  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:33.626  4515  4579 D BtGatt.ScanManager: Starting BLE batch scan
,10-07 10:49:33.626  4515  4579 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-07 10:49:33.634  4515  4576 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 10:49:33.634  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:49:33.639  4515  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 10:49:33.640  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:49:34.121  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-07 10:49:34.121  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-07 10:49:34.121  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 10:49:34.420   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:35.421   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-07 10:49:37.690   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 10:49:38.624  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 10:49:38.624  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:38.625  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-07 10:49:38.625  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:38.625  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 10:49:38.625  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:38.625  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-07 10:49:38.626  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 10:49:38.626  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 10:49:38.626  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-07 10:49:38.626  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-07 10:49:38.626  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-07 10:49:38.628  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:49:38.630  4515  4529 D BtGatt.GattService: stopScan() - queue size =1
,10-07 10:49:38.634  4515  4714 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-07 10:49:38.635  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 10:49:38.635  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 10:49:38.635  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 10:49:38.635  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:49:38.635  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 10:49:38.635  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-07 10:49:38.635  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 10:49:38.636  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 10:49:38.639  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:49:38.639  4515  4515 D BtGatt.ScanManager: awakened up at time 247658
10-07 10:49:38.640  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 10:49:38.640  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 10:49:38.641  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 10:49:38.641  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-07 10:49:38.642  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:49:38.643  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:49:38.644  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:49:38.644  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 10:49:38.647  4515  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 10:49:38.647  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:38.647  4515  4579 D BtGatt.ScanManager: stopping BLe Batch
,10-07 10:49:38.656  4515  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-07 10:49:38.656  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:38.656  4515  4579 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 10:49:38.673  4515  4576 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-07 10:49:38.673  4515  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:49:38.673  4515  4576 D BtGatt.GattService: current time is 247692740974
10-07 10:49:38.674  4515  4576 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -77, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -79, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -80, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-07 10:49:38.674  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-07 10:49:38.674  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-07 10:49:38.674  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-07 10:49:38.674  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,10-07 10:49:38.675  4515  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-07 10:49:39.145  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 10:49:39.145  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:39.145  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 10:49:40.725   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 10:49:43.645  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 10:49:43.645  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:43.645  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.645  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.646  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:49:43.646  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:49:43.646  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:43.646  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.646  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.646  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
,10-07 10:49:43.647  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.647  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:43.648  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:49:43.648  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.651  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.651  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-07 10:49:43.651  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.652  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.653  5639  5685 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-07 10:49:43.655  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 10:49:43.655  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:43.655  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.655  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.656  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.656  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.656  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 10:49:43.656  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.656  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.656  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.656  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.657  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.657  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.657  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.657  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:43.659  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.660  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:43.660  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.660  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.662  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-07 10:49:43.663  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:43.663  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 10:49:43.663  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.663  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.663  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.664  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.664  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:43.664  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.665  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 10:49:43.665  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.665  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.666  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.666  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.666  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.666  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.667  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.667  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:43.667  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.667  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
,10-07 10:49:43.668  5639  5685 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-07 10:49:43.668  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:43.668  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:43.668  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.668  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.669  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.669  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.669  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:43.669  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.669  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.669  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.669  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.669  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.669  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.669  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.669  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.670  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.671  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:43.671  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.671  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.672  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-07 10:49:43.672  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:43.672  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:43.672  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.672  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.672  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.672  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:43.672  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:43.672  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.672  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.672  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.672  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.672  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.673  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.673  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.673  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.674  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 10:49:43.674  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:43.674  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.675  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
,10-07 10:49:43.675  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-07 10:49:43.676  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 10:49:43.676  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 10:49:43.676  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-07 10:49:43.676  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 10:49:43.676  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 10:49:43.676  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-07 10:49:43.676  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 10:49:43.676  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 10:49:43.676  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:43.676  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 10:49:43.676  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.676  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.677  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.677  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.677  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:43.677  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.677  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.677  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.677  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.677  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.677  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.677  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.677  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.680  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.681  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-07 10:49:43.681  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.681  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.683  5639  5685 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 10:49:43.684  5639  5685 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-07 10:49:43.684  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-07 10:49:43.688  5639  5685 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 10:49:43.688  5639  5685 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-07 10:49:43.688  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-07 10:49:43.688  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-07 10:49:43.688  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-07 10:49:43.689  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-07 10:49:43.690  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-07 10:49:43.690  5639  5685 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-07 10:49:43.691  5639  5685 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-07 10:49:43.691  5639  5685 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-07 10:49:43.691  5639  5685 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 10:49:43.691  5639  5685 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-07 10:49:43.691  5639  5685 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-07 10:49:43.691  5639  5685 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 10:49:43.691  5639  5685 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-07 10:49:43.692  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-07 10:49:43.695  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-07 10:49:43.696  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,10-07 10:49:43.696  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-07 10:49:43.697  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-07 10:49:43.697  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-07 10:49:43.697  5639  5685 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,10-07 10:49:43.697  5639  5685 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 10:49:43.698  5639  5685 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-07 10:49:43.698  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-07 10:49:43.698  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-07 10:49:43.698  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-07 10:49:43.698  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-07 10:49:43.698  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 10:49:43.699  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:43.699  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.699  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.699  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.699  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.699  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 10:49:43.699  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,10-07 10:49:43.700  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.700  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.700  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.700  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.700  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.700  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.700  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.700  5639  5687 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-07 10:49:43.700  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.700  5639  5687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 10:49:43.701  5639  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-07 10:49:43.701  5639  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-07 10:49:43.702  5639  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-07 10:49:43.698  4529  4529 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32258]" dev="sockfs" ino=32258 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-07 10:49:43.698  4529  4529 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32258]" dev="sockfs" ino=32258 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-07 10:49:43.702  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.702  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:43.702  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.702  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.703  5639  5685 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-07 10:49:43.703  5639  5687 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-07 10:49:43.703  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-07 10:49:43.703  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-07 10:49:43.704  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:43.704  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:43.704  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.705  5639,  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.705  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.705  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.705  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:43.705  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.705  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.705  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.705  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.706  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.706  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.706  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.706  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.707  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.707  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:43.707  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.707  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.708  5639  5685 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-07 10:49:43.708  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:43.708  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:43.708  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.709  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.709  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.709  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.709  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 10:49:43.709  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.709  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.709  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.709  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.709  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.709  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.709  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.710  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:43.711  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.711  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:43.711  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.711  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
,10-07 10:49:43.712  5639  5685 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-07 10:49:43.712  5639  5685 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-07 10:49:43.712  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-07 10:49:43.712  5639  5685 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-07 10:49:43.712  5639  5685 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-07 10:49:43.712  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-07 10:49:43.712  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-07 10:49:43.712  5639  5685 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-07 10:49:43.712  5639  5685 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-07 10:49:43.713  5639  5685 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-07 10:49:43.713  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-07 10:49:43.713  5639  5685 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-07 10:49:43.713  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:43.713  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:43.713  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:43.713  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.713  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:49:43.713  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.713  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:43.714  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.714  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.714  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.714  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.714  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.714  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:43.714  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.714  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:43.715  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:43.715  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:43.716  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.716  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
,10-07 10:49:43.716  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:43.716  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:43.716  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:43.716  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:43.717  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:43.717  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:43.717  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:43.717  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:43.717  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:49:43.717  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:45.422   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:46.423   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:47.424   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:48.425   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:48.718  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.718  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.718  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:48.718  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.718  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.719  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:48.719  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:48.719  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:48.719  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:48.719  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:48.720  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:48.720  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.720  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.720  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:48.720  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:48.720  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.720  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.721  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:48.721  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.721  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.721  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.721  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.724  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:48.724  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:48.724  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.725  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.730  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-07 10:49:48.731  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:49:48.735  4714  4714 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32260]" dev="sockfs" ino=32260 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-07 10:49:48.735  4714  4714 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32260]" dev="sockfs" ino=32260 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-07 10:49:48.733  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-07 10:49:48.736  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-07 10:49:48.736  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-07 10:49:48.736  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-07 10:49:48.736  5639  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-07 10:49:48.736  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-07 10:49:48.736  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 10:49:48.736  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-07 10:49:48.737  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:48.737  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-07 10:49:48.737  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-07 10:49:48.737  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-07 10:49:48.737  5639  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 10:49:48.737  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.737  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-07 10:49:48.737  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-07 10:49:48.738  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:48.738  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-07 10:49:48.738  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.738  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 10:49:48.738  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 10:49:48.738  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 10:49:48.738  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.738  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.739  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:49:48.739  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.739  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:49:48.739  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:48.739  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:48.739  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:49:48.739  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:48.739  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:49:48.739  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:48.739  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:49:48.739  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.740  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-07 10:49:48.740  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:48.740  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.740  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.740  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:48.740  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.740  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.740  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.740  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.741  5639  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-07 10:49:48.741  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:48.741  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:48.741  5639  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-07 10:49:48.741  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.741  5639  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-07 10:49:48.741  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.742  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-07 10:49:48.742  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:48.742  5639  5685 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-07 10:49:48.743  5639  5685 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-07 10:49:48.743  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-07 10:49:48.743  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 10:49:48.743  5639  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 10:49:48.743  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:48.743  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:48.743  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:48.743  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:48.743  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.743  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.744  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:48.744  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
,10-07 10:49:48.744  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.744  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.744  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:48.745  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.745  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.745  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.745  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.747  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 10:49:48.747  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:49:48.747  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.747  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.754  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:48.754  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:48.754  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 10:49:48.754  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:48.754  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.754  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.755  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:48.755  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
10-07 10:49:48.755  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.755  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
,10-07 10:49:48.755  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:48.755  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.755  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.755  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.755  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.756  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:48.756  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-07 10:49:48.756  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.756  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.757  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:49:48.757  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:49:48.757  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:49:48.757  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:49:48.757  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.757  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.757  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:49:48.757  5639  5685 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c534d1e not in the list
,10-07 10:49:48.757  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.757  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
10-07 10:49:48.757  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:48.757  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.757  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.758  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:48.758  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:48.760  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:49:48.760  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-07 10:49:48.760  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:49:48.760  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42b29ff not in the list
,10-07 10:49:48.761  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-07 10:49:48.761  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-07 10:49:48.761  5639  5685 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-07 10:49:48.761  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-07 10:49:48.761  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-07 10:49:48.761  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-07 10:49:48.763  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-07 10:49:48.763  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-07 10:49:48.764  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-07 10:49:48.764  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-07 10:49:48.764  5639  5685 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-07 10:49:48.765  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-07 10:49:48.765  5639  5685 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-07 10:49:48.765  5639  5685 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-07 10:49:48.765  5639  5685 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-07 10:49:48.765  5639  5685 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-07 10:49:48.766  5639  5685 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-07 10:49:48.766  5639  5685 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-07 10:49:48.766  5639  5685 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-07 10:49:48.766  5639  5685 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-07 10:49:48.766  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:49:48.767  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5838ec9 added. We now have 3 listener(s)
10-07 10:49:48.767  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:49:48.769  5639  5685 D BluetoothAdapter: enable(): BT is already enabled..!
,10-07 10:49:48.769   927  3806 D WifiService: setWifiEnabled: true pid=5639, uid=10077
10-07 10:49:48.769   927  3806 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 10:49:48.829  4515  4706 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-07 10:49:48.830  4515  4711 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-07 10:49:49.240  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 10:49:49.426   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:49:50.427   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-07 10:49:53.774  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 10:49:53.774  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6fb39ce added. We now have 4 listener(s)
10-07 10:49:53.775  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 10:49:53.786  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 10:49:53.786  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6fb39ce removed from the list
,10-07 10:49:53.786  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 10:49:53.786  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:49:53.787  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:49:53.788  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 10:49:53.788  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e890ef added. We now have 4 listener(s)
,10-07 10:49:53.791  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 10:49:53.793  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 10:49:53.793  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e890ef removed from the list
,10-07 10:49:53.793  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:49:53.793  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:49:53.793  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:49:53.794  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:49:53.795  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@208b7fc added. We now have 4 listener(s)
10-07 10:49:53.795  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:49:53.799   927  3817 D WifiService: setWifiEnabled: false pid=5639, uid=10077
,10-07 10:49:53.799   927  3817 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 10:49:53.806   927  2954 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-07 10:49:53.806   927  2954 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-07 10:49:53.806   927  2954 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 10:49:53.806   927  2954 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 10:49:53.812  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:49:53.812  4515  4571 D BluetoothAdapterState: Current state: ON, message: 23
,10-07 10:49:53.812  4515  4571 D BluetoothAdapterProperties: Setting state to 13
,10-07 10:49:53.812  4515  4571 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-07 10:49:53.813  4515  4571 D BluetoothAdapterProperties: onBluetoothDisable()
10-07 10:49:53.815  4515  4571 I BluetoothAdapterState: Entering PendingCommandState
10-07 10:49:53.817  4515  4576 D BluetoothAdapterProperties: Scan Mode:20
10-07 10:49:53.818  4515  4571 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-07 10:49:53.819  4515  4515 D BluetoothMapService: onReceive
10-07 10:49:53.819  4515  4515 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 10:49:53.819  4515  4515 D BluetoothMapService: STATE_TURNING_OFF
10-07 10:49:53.820  4515  4515 D BluetoothMapService: MAP Service closeService in
10-07 10:49:53.820  4515  4515 D BluetoothMapMasInstance0: MAP Service shutdown
10-07 10:49:53.820  4515  4515 D ObexServerSockets0: shutdown(block = true)
,10-07 10:49:53.820  4515  4515 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 10:49:53.821  4515  4515 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 10:49:53.821  4515  4711 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-07 10:49:53.821   927  5381 D DhcpClient: Clearing IP address
10-07 10:49:53.821   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-07 10:49:53.822  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:49:53.822  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:49:53.822  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.822  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.822  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:53.822  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.822  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:53.822  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:53.822  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:49:53.824  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.824  4515  4737 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-07 10:49:53.824  4515  4736 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-07 10:49:53.825  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:49:53.826  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 10:49:53.826  4515  4515 I BtOppRfcommListener: stopping Accept Thread
,10-07 10:49:53.827  4515  5306 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-07 10:49:53.827  4515  5306 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-07 10:49:53.830  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.833   507   921 D CommandListener: Setting iface cfg
10-07 10:49:53.833  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.837  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.837  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.837  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.837  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.837  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:53.837  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.837  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:53.837  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:53.837  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:49:53.838  3529  5441 V NativeCrypto: Read error: ssl=0x7f8b644d80: I/O error during system call, Connection timed out
10-07 10:49:53.838  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.838  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:53.840   927  5382 D DhcpClient: Receive thread stopped
10-07 10:49:53.840  3529  5441 V NativeCrypto: SSL shutdown failed: ssl=0x7f8b644d80: I/O error during system call, Broken pipe
10-07 10:49:53.842   927  3545 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-07 10:49:53.843   927  5379 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-07 10:49:53.843  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.843  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.843  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.843  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.843  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:53.843  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.843  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:53.843  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:53.843  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:49:53.845   927  5379 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-07 10:49:53.845  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth,.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.845  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:49:53.845   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-07 10:49:53.845   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-07 10:49:53.847   927  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-07 10:49:53.848  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.851  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.854  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.855   927   940 I ActivityManager: Start proc 5693:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-07 10:49:53.858  4515  4515 D HeadsetService: Received stop request...Stopping profile...
10-07 10:49:53.860   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-07 10:49:53.861   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-07 10:49:53.861  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:49:53.861  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.861  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.861  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.861  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:53.861  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.861  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:53.861  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:49:53.861  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:49:53.862  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.862  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:49:53.863   533   533 E Parcel  : Reading a NULL string not supported here.
10-07 10:49:53.865  3085  3098 D BluetoothHeadset: Proxy object disconnected
10-07 10:49:53.865  3085  3085 D HeadsetProfile: Bluetooth service disconnected
,10-07 10:49:53.865   927   927 D BluetoothHeadset: Proxy object disconnected
10-07 10:49:53.866  3727  3760 D BluetoothHeadset: Proxy object disconnected
,10-07 10:49:53.866  4515  4515 D A2dpService: Received stop request...Stopping profile...
10-07 10:49:53.867   927   927 D BluetoothHeadset: Proxy object disconnected
,10-07 10:49:53.867   927   927 D BluetoothHeadset: Proxy object disconnected
10-07 10:49:53.867  4515  4717 D A2dpStateMachine: Exit Disconnected: -1
10-07 10:49:53.868   927   927 D RttService: SCAN_AVAILABLE : 1
10-07 10:49:53.869   927   927 D BluetoothA2dp: Proxy object disconnected
10-07 10:49:53.869  3085  3085 D BluetoothA2dp: Proxy object disconnected
10-07 10:49:53.869   927  3024 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-07 10:49:53.869  4515  4515 D HidService: Received stop request...Stopping profile...
10-07 10:49:53.869  4515  4515 D HidService: Stopping Bluetooth HidService
10-07 10:49:53.870  3085  3085 D BluetoothInputDevice: Proxy object disconnected
10-07 10:49:53.870  3085  3085 D HidProfile: Bluetooth service disconnected
10-07 10:49:53.871   927  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-07 10:49:53.870  4515  4515 V BluetoothAdapterState: isTurningOff()=true
10-07 10:49:53.871  4515  4515 V BluetoothAdapterState: isTurningOn()=false
,10-07 10:49:53.871  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:49:53.871  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 10:49:53.873  4515  4515 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-07 10:49:53.873  4515  4515 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-07 10:49:53.874  4515  4576 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-07 10:49:53.875  4515  4706 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:49:53.875  4515  4706 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:49:53.875  4515  4706 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:49:53.875  4515  4576 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-07 10:49:53.875  4515  4515 D HealthService: Received stop request...Stopping profile...
10-07 10:49:53.875  3686  3868 W QCNEJ   : |CORE| network lost: 100
,10-07 10:49:53.876  3686  3868 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-07 10:49:53.877  4515  4515 V BluetoothAdapterState: isTurningOff()=true
10-07 10:49:53.877  4515  4515 V BluetoothAdapterState: isTurningOn()=false
10-07 10:49:53.877  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:49:53.877  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:49:53.877  4515  4515 D PanService: Received stop request...Stopping profile...
10-07 10:49:53.878   927  2954 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-07 10:49:53.880  4515  4576 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-07 10:49:53.880  4515  4706 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:49:53.880  4515  4706 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-07 10:49:53.880  4515  4706 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-07 10:49:53.880  4515  4706 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 10:49:53.880  4515  4706 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 10:49:53.880  4515  4706 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 10:49:53.880  4515  4515 D BluetoothMapService: Received stop request...Stopping profile...
10-07 10:49:53.881  4515  4515 D BluetoothMapService: stop()
10-07 10:49:53.881  4515  4515 D BluetoothMapAppObserver: deinitObservers()
10-07 10:49:53.881  4515  4515 D BluetoothMapAppObserver: removeReceiver()
10-07 10:49:53.883  4515  4515 V BluetoothAdapterState: isTurningOff()=true
10-07 10:49:53.883  4515  4515 V BluetoothAdapterState: isTurningOn()=false
10-07 10:49:53.883  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:49:53.883  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:49:53.884  4515  4515 D SapService: Received stop request...Stopping profile...
10-07 10:49:53.884  4515  4515 V SapService: stop()
,10-07 10:49:53.886  4515  4515 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,10-07 10:49:53.886  4515  4515 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-07 10:49:53.887  4515  4576 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-07 10:49:53.887  4515  4515 V BluetoothAdapterState: isTurningOff()=true
10-07 10:49:53.887  4515  4515 V BluetoothAdapterState: isTurningOn()=false
10-07 10:49:53.887  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:49:53.887  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:49:53.887  4515  4515 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-07 10:49:53.887  4515  4515 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-07 10:49:53.887  4515  4576 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-07 10:49:53.888  4515  4515 V BluetoothAdapterState: isTurningOff()=true
10-07 10:49:53.888  4515  4515 V BluetoothAdapterState: isTurningOn()=false
10-07 10:49:53.888  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:49:53.888  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:49:53.888  4515  4515 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-07 10:49:53.888  4515  4515 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-07 10:49:53.889  4515  4515 D BluetoothMapService: MAP Service closeService in
10-07 10:49:53.889  4515  4515 V BluetoothAdapterState: isTurningOff()=true
10-07 10:49:53.889  4515  4515 V BluetoothAdapterState: isTurningOn()=false
10-07 10:49:53.889  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:49:53.889  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:49:53.889  4515  4515 D BluetoothMapService: cleanup()
10-07 10:49:53.889  4515  4515 D BluetoothMapService: MAP Service closeService in
10-07 10:49:53.890  4515  4515 V BluetoothAdapterState: isTurningOff()=true
10-07 10:49:53.890  4515  4515 V BluetoothAdapterState: isTurningOn()=false
10-07 10:49:53.890  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:49:53.890  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:49:53.890  4515  4571 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-07 10:49:53.890  4515  4571 D BluetoothAdapterProperties: Setting state to 15
10-07 10:49:53.890  4515  4571 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-07 10:49:53.891  4515  4571 I BluetoothAdapterState: Entering BleOnState
10-07 10:49:53.891  3085  3097 D BluetoothMap: onBluetoothStateChange: up=false
10-07 10:49:53.891  3085  3085 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-07 10:49:53.891   927  2954 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 10:49:53.891  3085  3085 D PanProfile: Bluetooth service disconnected
10-07 10:49:53.892   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 10:49:53.892   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:49:53.892  3085  3098 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-07 10:49:53.898  3085  3887 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-07 10:49:53.898   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-07 10:49:53.898  3727  3982 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:49:53.899   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:49:53.899  3085  3097 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-07 10:49:53.899  3085  3098 D BluetoothPbap: onBluetoothStateChange: up=false
,10-07 10:49:53.900  3085  3887 D BluetoothPan: onBluetoothStateChange on: false
,10-07 10:49:53.900  4515  4571 D BluetoothAdapterState: Current state: BLE ON, message: 20
,10-07 10:49:53.900  4515  4571 D BluetoothAdapterProperties: Setting state to 16
,10-07 10:49:53.900  4515  4571 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-07 10:49:53.902  4515  4571 D BluetoothAdapterProperties: onBleDisable
,10-07 10:49:53.902  4515  4571 I BluetoothAdapterState: Entering PendingCommandState
,10-07 10:49:53.902  4515  4573 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-07 10:49:53.903  4515  4576 D BluetoothAdapterProperties: Scan Mode:20
10-07 10:49:53.904  4515  4706 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-07 10:49:53.904  4515  4706 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:49:53.904  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:49:53.904  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.904  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.904  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.904  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:53.904  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.904  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:53.904  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:53.904  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 10:49:53.905  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:49:53.905  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:49:53.907  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.907  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.907  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.907  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.907  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:53.907  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.907  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:53.907  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:53.907  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:49:53.907   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-07 10:49:53.908  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.908  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:49:53.910  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.910  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.910  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.910  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.910  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:53.910  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.910  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:53.910  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:53.910  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:49:53.912  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:53.915  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.916  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.926   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-07 10:49:53.926  5693  5693 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-07 10:49:53.926   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-07 10:49:53.927   507   921 D TetherController: Setting IP forward enable = 0
10-07 10:49:53.928   927  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-07 10:49:53.928   927  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-07 10:49:53.932  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.932   927   944 D Tethering: MasterInitialState.processMessage what=3
10-07 10:49:53.932   927  2954 D DhcpClient: doQuit
,10-07 10:49:53.932   927  2954 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-07 10:49:53.933  3398  3398 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-07 10:49:53.933   927  5381 D DhcpClient: onQuitting
10-07 10:49:53.934  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.936  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.936  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.936  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.936  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.936  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:49:53.936  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.936  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:53.936  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:53.936  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 10:49:53.937  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:49:53.937  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:49:53.940  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.940  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.940  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.940  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.940  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:49:53.940  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.940  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:53.940  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:53.940  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:49:53.941  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.941  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:49:53.943  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.943  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:53.943  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:53.943  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:53.943  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:49:53.943  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:53.943  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:53.943  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:53.943  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:49:53.944  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:53.944  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 10:49:53.946  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:53.947  3917  3917 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-07 10:49:53.949  4947  4971 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-07 10:49:53.949  4947  4971 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 10:49:53.949  4947  4971 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-07 10:49:53.949  4947  4971 E SarControlService: no key has been found,reset the power
10-07 10:49:53.950  4947  4982 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 10:49:53.950  4947  4982 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 10:49:53.950  4947  4982 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 10:49:53.950  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 10:49:53.950  4972  4972 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-07 10:49:53.953  3398  3398 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-07 10:49:53.953  4947  4982 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 10:49:53.953  4947  4982 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 10:49:53.953  4947  4982 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 10:49:53.954  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 10:49:53.954  4972  4972 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 10:49:53.954  4972  4986 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f362e86 HexData = [00000000ea03000000000000ffffffff]
,10-07 10:49:53.954  4972  4986 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 10:49:53.954  4972  4986 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-07 10:49:53.955  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 10:49:53.955  4947  4958 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-07 10:49:53.959  4972  4986 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f362e86 HexData = [00000000eb03000000000000ffffffff]
10-07 10:49:53.959  3398  3398 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-07 10:49:53.959  4972  4986 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 10:49:53.959  4972  4986 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-07 10:49:53.960  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 10:49:53.960  4947  4957 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-07 10:49:53.968  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 10:49:53.973   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cf6f76:true
,10-07 10:49:53.974  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 10:49:53.979  3398  3398 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-07 10:49:53.986   927  3785 I ActivityManager: Start proc 5722:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-07 10:49:54.000  3398  3398 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-07 10:49:54.002  5693  5693 D LocalBluetoothProfileManager: Adding local MAP profile
,10-07 10:49:54.005  5693  5693 D BluetoothMap: Create BluetoothMap proxy object
,10-07 10:49:54.018  5693  5693 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-07 10:49:54.028  5722  5722 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-07 10:49:54.033  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,10-07 10:49:54.039   927   937 I ActivityManager: Killing 5428:com.android.chrome/u0a39 (adj 15): empty #17
,10-07 10:49:54.106  4894  4894 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-07 10:49:54.106   927  2954 D wifi    : In wifi stop Hal
10-07 10:49:54.106   927  2954 D wifi    : halHandle = 0x7f89f8de00, mVM = 0x7fa660d140, mCls = 0x100a02
10-07 10:49:54.108   927  3397 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-07 10:49:54.108   927  3397 D WifiHAL : Got a signal to exit!!!
10-07 10:49:54.108   927  3397 I WifiHAL : Exit wifi_event_loop
10-07 10:49:54.108   927  2954 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-07 10:49:54.108   927  2954 E WifiHAL : Event processing terminated
10-07 10:49:54.108   927  2954 D wifi    : In wifi cleaned up handler
10-07 10:49:54.109   927  2954 I WifiHAL : Internal cleanup completed
,10-07 10:49:54.110  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:49:54.111  4029  4176 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-07 10:49:54.112  4515  4576 I bt_hci  : shut_down
10-07 10:49:54.112  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:54.115  4515  4580 D bt_hwcfg: hw_epilog_process
10-07 10:49:54.115  4515  4580 I bt_vendor: low_power_mode_cb
,10-07 10:49:54.115  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:54.117  4515  4580 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-07 10:49:54.118  4515  4580 I bt_vendor: epilog_cb
10-07 10:49:54.118  4515  4580 I bt_hci  : epilog_finished_callback
,10-07 10:49:54.120  4515  4576 I bt_hci_h4: hal_close
10-07 10:49:54.121  4515  4576 I bt_userial_vendor: device fd = 54 close
,10-07 10:49:54.131   927  3397 D wifi    : set interface wlan0 flags (DOWN)
,10-07 10:49:54.131   927  2954 D WifiNative-HAL: HAL event thread stopped successfully
,10-07 10:49:54.230  4515  4573 D bt_stack_manager: event_shut_down_stack finished.
,10-07 10:49:54.230  4515  4571 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-07 10:49:54.232  4515  4571 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-07 10:49:54.232  4515  4515 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-07 10:49:54.232  4515  4515 D BtGatt.GattService: Received stop request...Stopping profile...
,10-07 10:49:54.232  4515  4515 D BtGatt.GattService: stop()
10-07 10:49:54.233  4515  4515 D BtGatt.AdvertiseManager: advertise clients cleared
10-07 10:49:54.234  4515  4515 V BluetoothAdapterState: isTurningOff()=false
10-07 10:49:54.234  4515  4515 V BluetoothAdapterState: isTurningOn()=false
10-07 10:49:54.234  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:49:54.234  4515  4515 V BluetoothAdapterState: isBleTurningOff()=true
10-07 10:49:54.234  4515  4571 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-07 10:49:54.235  4515  4571 D BluetoothAdapterProperties: Setting state to 10
10-07 10:49:54.235  4515  4571 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-07 10:49:54.235  4515  4571 I BluetoothAdapterState: Entering OffState
,10-07 10:49:54.236   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-07 10:49:54.242  4515  4515 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-07 10:49:54.242  4515  4515 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-07 10:49:54.242  4515  4515 I BluetoothServiceJni: cleanupNative: return from cleanup
10-07 10:49:54.243  4515  4573 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-07 10:49:54.250  5722  5722 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-07 10:49:54.250  5722  5722 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:49:54.250  5722  5722 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:49:54.250  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:49:54.251  5722  5722 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 10:49:54.251  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.r.e.b(PG:170)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:49:54.251  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:49:54.252  5722  5722 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 10:49:54.252  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.r.k.d(PG:583)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.r.e.b(PG:170)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:49:54.252  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:49:54.253  5722  5722 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:49:54.253  5722  5722 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:49:54.253  5722  5722 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:49:54.253  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:49:54.256  4515  4573 D bt_stack_manager: event_clean_up_stack finished.
10-07 10:49:54.259  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 10:49:54.262  4515  4515 I art     : System.exit called, status: 0
10-07 10:49:54.262  4515  4515 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-07 10:49:54.294  5693  5693 D DockEventReceiver: finishStartingService: stopping service
10-07 10:49:54.296   927  3803 I ActivityManager: Killing 4854:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-07 10:49:54.324   927  3817 I ActivityManager: Process com.android.bluetooth (pid 4515) has died
,10-07 10:49:54.328  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 10:49:54.340   927   937 I ActivityManager: Start proc 5755:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-07 10:49:54.341   927   944 D Tethering: InitialState.processMessage what=4
,10-07 10:49:54.344   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-07 10:49:54.408  5755  5755 D AdapterServiceConfig: Adding HeadsetService
,10-07 10:49:54.408  5755  5755 D AdapterServiceConfig: Adding A2dpService
10-07 10:49:54.408  5755  5755 D AdapterServiceConfig: Adding HidService
10-07 10:49:54.408  5755  5755 D AdapterServiceConfig: Adding HealthService
10-07 10:49:54.409  5755  5755 D AdapterServiceConfig: Adding PanService
10-07 10:49:54.409  5755  5755 D AdapterServiceConfig: Adding GattService
10-07 10:49:54.409  5755  5755 D AdapterServiceConfig: Adding BluetoothMapService
10-07 10:49:54.409  5755  5755 D AdapterServiceConfig: Adding SapService
10-07 10:49:54.412   927  3817 I ActivityManager: Killing 5054:com.google.android.deskclock/u0a66 (adj 15): empty #17
,10-07 10:49:54.432  3832  3832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-07 10:49:54.435  3832  3832 D SystemUpdateService: onCreate
,10-07 10:49:54.439  3832  3832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-07 10:49:54.447  3832  3832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-07 10:49:54.452  3832  5413 I iu.UploadsManager: num queued entries: 0
10-07 10:49:54.452  3832  5413 I iu.UploadsManager: num updated entries: 0
,10-07 10:49:54.453  3832  5413 I iu.SyncManager: NEXT; no task
,10-07 10:49:54.455  3832  5767 I SystemUpdateService: active receiver: enabled
,10-07 10:49:54.457  3832  3832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 10:49:54.459  3832  3832 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 10:49:54.466  3832  5767 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 10:49:54.470   927  3545 I ActivityManager: Start proc 5769:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-07 10:49:54.476  3832  5767 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-07 10:49:54.476  3832  5767 I SystemUpdateService: now status is 0 (complete)
10-07 10:49:54.476  3832  5767 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 10:49:54.476  3832  5767 I SystemUpdateService: file has been verified
10-07 10:49:54.476  3832  5767 I SystemUpdateService: OTA package size = 21989297
,10-07 10:49:54.492  3832  5767 I SystemUpdateService: showing system update notification
,10-07 10:49:54.510  5769  5769 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-07 10:49:54.512  5769  5769 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 10:49:54.526  5769  5769 D SprintDMHelper: simOperator: 
10-07 10:49:54.526  5769  5769 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 10:49:54.539   927  3362 I ActivityManager: Start proc 5781:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-07 10:49:54.547  3832  3832 D SystemUpdateService: onDestroy
,10-07 10:49:54.552   927  3362 I ActivityManager: Killing 5462:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-07 10:49:54.645  4894  5795 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-07 10:49:54.654   927  3362 I ActivityManager: Start proc 5796:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-07 10:49:54.656   927  3096 I ActivityManager: Killing 4586:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-07 10:49:54.706  5796  5796 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-07 10:49:54.710  5722  5748 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-07 10:49:54.722   927  3764 I ActivityManager: Killing 5504:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-07 10:49:54.741   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f77bc98:true
,10-07 10:49:55.017   507   921 E Netd    : netlink response contains error (No such file or directory)
,10-07 10:49:55.019   927  2973 E NetdConnector: NDC Command {113 network destroy 100} took too long (1090ms)
10-07 10:49:55.020   927  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-07 10:49:55.021   927  2942 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1086ms)
,10-07 10:49:55.022   507   921 D TetherController: Setting IP forward enable = 0
,10-07 10:49:55.022   927  2940 E NetdConnector: NDC Command {115 bandwidth gettetherstats} took too long (677ms)
,10-07 10:49:58.828   927  3364 D WifiService: setWifiEnabled: true pid=5639, uid=10077
,10-07 10:49:58.829   927  3364 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 10:49:58.837   507   921 D SoftapController: Softap fwReload - Ok
,10-07 10:49:58.843   507   921 D CommandListener: Setting iface cfg
,10-07 10:49:58.843   507   921 D CommandListener: Trying to bring down wlan0
,10-07 10:49:58.845   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-07 10:49:58.850   927  2954 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-07 10:49:59.414   927  2954 D wifi    : set interface wlan0 flags (UP)
10-07 10:49:59.419   927  2954 I WifiHAL : Initializing wifi
10-07 10:49:59.419   927  2954 I WifiHAL : Creating socket
10-07 10:49:59.421   927  2954 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-07 10:49:59.421   927  2954 D wifi    : Did set static halHandle = 0x7f89f8de00
10-07 10:49:59.422   927  2954 D wifi    : halHandle = 0x7f89f8de00, mVM = 0x7fa660d140, mCls = 0x1946
10-07 10:49:59.422   927  2954 D wifi    : array field set
10-07 10:49:59.422   927  2954 I WifiNative-HAL: interface[0] = wlan0
10-07 10:49:59.422   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-07 10:49:59.424   927  5817 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547775634944
10-07 10:49:59.424   927  5817 D wifi    : waitForHalEvents called, vm = 0x7fa660d140, obj = 0x1946, env = 0x7f87b4cbc0
,10-07 10:49:59.429   927  2954 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-07 10:49:59.435  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:59.439  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:59.440  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:49:59.496  5818  5818 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-07 10:49:59.510  5818  5818 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 10:49:59.527  5818  5818 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 10:49:59.527  5818  5818 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-07 10:49:59.543  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:49:59.544  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:59.544  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:59.544  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:59.544  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:59.544  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:59.544  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:59.544  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:59.544  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:49:59.544  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:59.544  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 10:49:59.545   927  2954 D WifiConfigStore: Loading config and enabling all networks 
,10-07 10:49:59.545  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:59.545  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:59.545  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:59.545  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:59.545  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:59.545  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:59.545  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:59.545  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:59.545  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:49:59.545  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:59.545  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:49:59.546  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:59.546  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:49:59.546  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:49:59.546  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:49:59.546  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:49:59.546  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:49:59.546  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:49:59.546  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:49:59.546  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 10:49:59.546  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:49:59.546  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 10:49:59.556   927  2954 D WifiConfigStore: loaded 0 passpoint configs
,10-07 10:49:59.557   927  2954 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-07 10:49:59.558   927  2954 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-07 10:49:59.559   927  2954 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-07 10:49:59.560   927  2954 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-07 10:49:59.560   927  2954 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-07 10:49:59.560   927  2954 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-07 10:49:59.560   927  2954 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-07 10:49:59.564   927  2954 D WifiNative-HAL: Setting external_sim to 1
,10-07 10:49:59.564  4894  4894 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 10:49:59.565   927  2954 D wifi    : setting dfs flag to true, 0x7f8c2ff9e0
10-07 10:49:59.565   927  2954 D WifiStateMachine: Setting OUI to DA-A1-19
10-07 10:49:59.565   927  2954 D wifi    : setting scan oui 0x7f8c2ff9e0
,10-07 10:49:59.565   927  2954 D WifiHAL : Sending mac address OUI
,10-07 10:49:59.569   927  2954 E native  : do suspend false
,10-07 10:49:59.576   927  2954 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-07 10:49:59.576   927   927 D RttService: SCAN_AVAILABLE : 3
10-07 10:49:59.576   927  3024 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-07 10:49:59.576   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-07 10:49:59.577   507   921 D CommandListener: Setting iface cfg
,10-07 10:49:59.581   927  2947 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
10-07 10:49:59.581   927  2947 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-07 10:49:59.589   927  2947 D WifiNative-HAL: p2pGetDeviceAddress
,10-07 10:49:59.593   927  2947 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-07 10:49:59.593   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268612 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-07 10:50:02.775  5818  5818 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:02.781  5818  5818 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:02.788  5818  5818 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:02.793  5818  5818 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:02.795  5818  5818 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:02.845   927  2954 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-07 10:50:02.846   927  2954 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-07 10:50:02.846   927  2954 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 10:50:02.857   927  2954 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-07 10:50:02.892   927  2954 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-07 10:50:02.893  5818  5818 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-07 10:50:03.316  5818  5818 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-07 10:50:03.346  5818  5818 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-07 10:50:03.346  5818  5818 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-07 10:50:03.357   927  2954 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 10:50:03.358   927  2954 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 10:50:03.358   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-07 10:50:03.375   927  2954 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 10:50:03.389   507   921 D CommandListener: Setting iface cfg
,10-07 10:50:03.395   927  2954 D WifiStateMachine: Start Dhcp Watchdog 2
,10-07 10:50:03.402   927  5826 D DhcpClient: Receive thread started
,10-07 10:50:03.407   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-07 10:50:03.407   927  2954 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-07 10:50:03.407   927  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-07 10:50:03.489   927  2954 E native  : do suspend false
,10-07 10:50:03.501   927  5825 D DhcpClient: Broadcasting DHCPDISCOVER
,10-07 10:50:03.515   927  5826 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,10-07 10:50:03.515   927  5825 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
,10-07 10:50:03.517   927  5825 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-07 10:50:03.530   927  5826 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-07 10:50:03.531   927  5825 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-07 10:50:03.533   507   921 D CommandListener: Setting iface cfg
,10-07 10:50:03.536   927  2954 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-07 10:50:03.543   927  5825 D DhcpClient: Scheduling renewal in 86399s
,10-07 10:50:03.554   927  2954 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-07 10:50:03.556   927  2954 D WifiConfigStore: No blacklist allowed without epno enabled
,10-07 10:50:03.557   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-07 10:50:03.558   927  2973 D ConnectivityService: Adding iface wlan0 to network 101
,10-07 10:50:03.577   927  2954 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-07 10:50:03.612   927  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-07 10:50:03.612   927  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-07 10:50:03.618   927  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-07 10:50:03.620   927  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-07 10:50:03.622   927  2973 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-07 10:50:03.632   927  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-07 10:50:03.636   927  2973 D ConnectivityService: scheduleUnvalidatedPrompt 101
10-07 10:50:03.636   927  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-07 10:50:03.637   927  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-07 10:50:03.637   927  2954 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-07 10:50:03.637   927  2973 D ConnectivityService:    accepting network in place of null
,10-07 10:50:03.637   927  2954 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 10:50:03.638   927  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 10:50:03.649   927  5824 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272668, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-07 10:50:03.662   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 10:50:03.684   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 10:50:03.687   927  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-07 10:50:03.687   927  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-07 10:50:03.687  3686  3868 W QCNEJ   : |CORE| network available: 101
10-07 10:50:03.688   927  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-07 10:50:03.690   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-07 10:50:03.693  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:50:03.694  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:03.694  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:03.694  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:03.694  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:03.694  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:03.694  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:03.694  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:03.694  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:50:03.694  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.694  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:03.694  3686  3868 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-07 10:50:03.695  3686  3868 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-07 10:50:03.696  3686  3868 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-07 10:50:03.697  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.697  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:03.697  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:03.697  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:03.697  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:03.697  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:03.697  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:03.697  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:03.697  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:50:03.697  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.697  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:03.699  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.699  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:03.699  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:03.699  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:03.699  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:03.699  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:03.699  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:03.699  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:03.699  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:50:03.699  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:50:03.699  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:50:03.702  4947  4971 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-07 10:50:03.702  4947  4971 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 10:50:03.702  4947  4971 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-07 10:50:03.702  4947  4971 E SarControlService: no key has been found,reset the power
10-07 10:50:03.702  4947  4982 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 10:50:03.702  4947  4982 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 10:50:03.703  4947  4982 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 10:50:03.703  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 10:50:03.703  4972  4972 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-07 10:50:03.704  3917  3917 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-07 10:50:03.706  4947  4982 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 10:50:03.706  4947  4982 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 10:50:03.706  4947  4982 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 10:50:03.706  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 10:50:03.706  4972  4972 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 10:50:03.708  3832  3832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-07 10:50:03.712  4972  4986 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f362e86 HexData = [00000000ec03000000000000ffffffff]
,10-07 10:50:03.712  4972  4986 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 10:50:03.712  4972  4986 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-07 10:50:03.712  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 10:50:03.712  4947  4958 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 10:50:03.713  3832  3832 D SystemUpdateService: onCreate
,10-07 10:50:03.718  4972  4986 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f362e86 HexData = [00000000ed03000000000000ffffffff]
,10-07 10:50:03.718  4972  4986 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 10:50:03.719  4972  4986 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-07 10:50:03.719  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-07 10:50:03.719  4947  4957 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-07 10:50:03.720  3832  3832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-07 10:50:03.723   927  5823 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-07 10:50:03.734  3832  3832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-07 10:50:03.738  3832  5413 I iu.UploadsManager: num queued entries: 0
,10-07 10:50:03.739  3832  5413 I iu.UploadsManager: num updated entries: 0
10-07 10:50:03.739  3832  5413 I iu.SyncManager: NEXT; no task
,10-07 10:50:03.743  3832  5836 I SystemUpdateService: active receiver: enabled
,10-07 10:50:03.744  3832  3832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 10:50:03.746  3832  3832 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 10:50:03.748  5769  5769 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-07 10:50:03.751  5769  5769 D SprintDMHelper: simOperator: 
10-07 10:50:03.751  5769  5769 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 10:50:03.767   927  5823 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 07 Oct 2016 14:50:03 GMT], X-Android-Received-Millis=[1475851803767], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475851803745]}
,10-07 10:50:03.768   927  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-07 10:50:03.768   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-07 10:50:03.768   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-07 10:50:03.769   927  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-07 10:50:03.777  3832  5836 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 10:50:03.790  3832  5836 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-07 10:50:03.790  3832  5836 I SystemUpdateService: now status is 0 (complete)
10-07 10:50:03.790  3832  5836 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 10:50:03.790  3832  5836 I SystemUpdateService: file has been verified
10-07 10:50:03.790  3832  5836 I SystemUpdateService: OTA package size = 21989297
,10-07 10:50:03.796  3832  5836 I SystemUpdateService: showing system update notification
,10-07 10:50:03.809  3832  3832 D SystemUpdateService: onDestroy
,10-07 10:50:03.834   927   938 D WifiService: setWifiEnabled: false pid=5639, uid=10077
,10-07 10:50:03.834   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 10:50:03.836   927  2954 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-07 10:50:03.836   927  2954 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-07 10:50:03.836   927  2954 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 10:50:03.836   927  2954 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 10:50:03.844   927  5825 D DhcpClient: Clearing IP address
,10-07 10:50:03.844   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-07 10:50:03.845   507   921 D CommandListener: Setting iface cfg
,10-07 10:50:03.852  3529  5837 V NativeCrypto: SSL handshake aborted: ssl=0x7f9c78c480: I/O error during system call, Connection timed out
,10-07 10:50:03.854  4894  5841 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
10-07 10:50:03.856   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-07 10:50:03.856   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-07 10:50:03.859   533   533 E Parcel  : Reading a NULL string not supported here.
10-07 10:50:03.861   927   927 D RttService: SCAN_AVAILABLE : 1
10-07 10:50:03.861   927  3024 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-07 10:50:03.865   927  2954 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-07 10:50:03.865   927  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-07 10:50:03.868  3686  3868 W QCNEJ   : |CORE| network lost: 101
10-07 10:50:03.868  3686  3868 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-07 10:50:03.870   927  2954 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-07 10:50:03.871  4894  5841 ,W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
10-07 10:50:03.871  4894  5841 W Babel_NetworkConnectionCheckingService: 	... 21 more
10-07 10:50:03.871  4894  5841 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-07 10:50:03.881   927  5826 D DhcpClient: Receive thread stopped
,10-07 10:50:03.892   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 10:50:03.911   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 10:50:03.911   507   921 D CommandListener: Clearing all IP addresses on wlan0
10-07 10:50:03.911   927  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-07 10:50:03.911   927  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-07 10:50:03.913   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-07 10:50:03.916   927  2954 D DhcpClient: doQuit
,10-07 10:50:03.916   927  2954 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-07 10:50:03.916   927  5825 D DhcpClient: onQuitting
,10-07 10:50:03.917  5818  5818 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-07 10:50:03.917  3917  3917 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-07 10:50:03.919  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.919  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:03.919  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:03.919  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:03.919  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:03.919  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:03.919  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:03.919  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:03.919  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:03.919  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.919  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:03.920  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.920  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:03.920  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:03.920  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:03.920  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:03.920  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:03.920  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:03.920  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:03.920  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:03.920  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:50:03.920  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:03.921  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.922  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:03.922  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:03.922  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:03.922  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:03.922  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:03.922  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:03.922  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:03.922  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:03.922  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:03.922  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:03.924  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:03.924  3832  3832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-07 10:50:03.925  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:03.925  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:03.926  4947  4971 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-07 10:50:03.926  4947  4971 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 10:50:03.926  4947  4971 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-07 10:50:03.926  4947  4971 E SarControlService: no key has been found,reset the power
10-07 10:50:03.926  4947  4982 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 10:50:03.926  4947  4982 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 10:50:03.927  4947  4982 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 10:50:03.927  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 10:50:03.927  4972  4972 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-07 10:50:03.928  4947  4982 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 10:50:03.928  4947  4982 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 10:50:03.929  4947  4982 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 10:50:03.929  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 10:50:03.929  4972  4972 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-07 10:50:03.932  3832  3832 D SystemUpdateService: onCreate
10-07 10:50:03.934  4972  4986 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f362e86 HexData = [00000000ee03000000000000ffffffff]
,10-07 10:50:03.934  4972  4986 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 10:50:03.934  4972  4986 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-07 10:50:03.934  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 10:50:03.934  4947  4957 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 10:50:03.935  4972  4986 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f362e86 HexData = [00000000ef03000000000000ffffffff]
10-07 10:50:03.935  4972  4986 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 10:50:03.935  4972  4986 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-07 10:50:03.935  5818  5818 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-07 10:50:03.936  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 10:50:03.936  4947  4958 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-07 10:50:03.939  3832  3832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-07 10:50:03.939  5818  5818 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-07 10:50:03.947  3832  5854 I SystemUpdateService: active receiver: enabled
,10-07 10:50:03.949  3832  3832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-07 10:50:03.953  3832  5413 I iu.UploadsManager: num queued entries: 0
,10-07 10:50:03.959  3832  3832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 10:50:03.962  3832  5854 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 10:50:03.963  3832  3832 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 10:50:03.965  5769  5769 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 10:50:03.968   507   921 E Netd    : netlink response contains error (No such file or directory)
,10-07 10:50:03.970  3832  5413 I iu.UploadsManager: num updated entries: 0
10-07 10:50:03.970  5769  5769 D SprintDMHelper: simOperator: 
10-07 10:50:03.970  5769  5769 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 10:50:03.971  5818  5818 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-07 10:50:03.978  3832  5854 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-07 10:50:03.978  3832  5854 I SystemUpdateService: now status is 0 (complete)
10-07 10:50:03.978  3832  5854 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 10:50:03.978  3832  5854 I SystemUpdateService: file has been verified
10-07 10:50:03.979  3832  5413 I iu.SyncManager: NEXT; no task
,10-07 10:50:03.980  3832  5854 I SystemUpdateService: OTA package size = 21989297
,10-07 10:50:03.982  4894  5858 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-07 10:50:03.984  5818  5818 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-07 10:50:04.000  3832  5854 I SystemUpdateService: showing system update notification
,10-07 10:50:04.007  3832  3832 D SystemUpdateService: onDestroy
,10-07 10:50:04.087   927  2954 D wifi    : In wifi stop Hal
10-07 10:50:04.087   927  2954 D wifi    : halHandle = 0x7f89f8de00, mVM = 0x7fa660d140, mCls = 0x1946
,10-07 10:50:04.087   927  5817 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-07 10:50:04.087   927  5817 D WifiHAL : Got a signal to exit!!!
10-07 10:50:04.087   927  5817 I WifiHAL : Exit wifi_event_loop
10-07 10:50:04.088   927  2954 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-07 10:50:04.088   927  2954 E WifiHAL : Event processing terminated
10-07 10:50:04.088   927  2954 D wifi    : In wifi cleaned up handler
10-07 10:50:04.088   927  2954 I WifiHAL : Internal cleanup completed
10-07 10:50:04.089  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:04.089  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:04.090  4029  4176 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-07 10:50:04.091  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:04.091  4894  4894 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-07 10:50:04.112   927  5817 D wifi    : set interface wlan0 flags (DOWN)
,10-07 10:50:04.113   927  2954 D WifiNative-HAL: HAL event thread stopped successfully
,10-07 10:50:04.320   927   944 D Tethering: InitialState.processMessage what=4
,10-07 10:50:04.328   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-07 10:50:04.688   927  2973 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-07 10:50:05.428   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:06.429   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:07.430   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:08.431   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:08.865   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f1469c:true
,10-07 10:50:08.865  5755  5755 D BluetoothAdapterState: make() - Creating AdapterState
,10-07 10:50:08.870  5755  5755 I bt_bluedroid: init
,10-07 10:50:08.870  5755  5860 I BluetoothAdapterState: Entering OffState
,10-07 10:50:08.873  5755  5861 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-07 10:50:08.874  5755  5861 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-07 10:50:08.874  5755  5861 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-07 10:50:08.874  5755  5861 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-07 10:50:08.875  5755  5755 I bt_bluedroid: get_profile_interface socket
,10-07 10:50:08.878  5755  5755 I bt_bluedroid: get_profile_interface sdp
10-07 10:50:08.878  5755  5864 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-07 10:50:08.882  5755  5864 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 10:50:08.886  5755  5766 I bt_bluedroid: config_hci_snoop_log
10-07 10:50:08.887   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-07 10:50:08.892  5755  5860 D BluetoothAdapterState: Current state: OFF, message: 0
,10-07 10:50:08.892  5755  5860 D BluetoothAdapterProperties: Setting state to 14
10-07 10:50:08.892  5755  5860 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-07 10:50:08.895  5755  5860 D BluetoothBondStateMachine: make
,10-07 10:50:08.897  5755  5865 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-07 10:50:08.901  5755  5860 I BluetoothAdapterState: Entering PendingCommandState
,10-07 10:50:08.902  5755  5755 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-07 10:50:08.905  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:08.906  5755  5755 D BtGatt.DebugUtils: handleDebugAction() action=null
10-07 10:50:08.906  5755  5755 D BtGatt.GattService: Received start request. Starting profile...
10-07 10:50:08.907  5755  5755 D BtGatt.GattService: start()
,10-07 10:50:08.907  5755  5755 I bt_bluedroid: get_profile_interface gatt
,10-07 10:50:08.908  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:08.908  5755  5755 D BtGatt.AdvertiseManager: advertise manager created
,10-07 10:50:08.914  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,10-07 10:50:08.914  5755  5755 V BluetoothAdapterState: isTurningOn()=false
10-07 10:50:08.914  5755  5755 V BluetoothAdapterState: isBleTurningOn()=true
10-07 10:50:08.915  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 10:50:08.915  5755  5860 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-07 10:50:08.916  5755  5860 I bt_bluedroid: bt_bluedroid
,10-07 10:50:08.917  5755  5861 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-07 10:50:08.917  5755  5861 I bt_hci  : start_up
,10-07 10:50:08.924  5755  5861 I bt_vendor: alloc value 0xf3ef8871
10-07 10:50:08.924  5755  5861 I bt_vendor: init
10-07 10:50:08.924  5755  5861 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-07 10:50:08.925  5755  5861 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-07 10:50:09.038  5755  5861 D bt_hci  : start_up starting async portion
,10-07 10:50:09.038  5755  5868 I bt_hci  : event_finish_startup
10-07 10:50:09.038  5755  5868 I bt_hci_h4: hal_open
,10-07 10:50:09.038  5755  5868 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-07 10:50:09.035  5869  5869 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-07 10:50:09.041  5755  5868 I bt_userial_vendor: device fd = 54 open
,10-07 10:50:09.055  5755  5868 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 10:50:09.058  5755  5868 D bt_hwcfg: Chipset BCM4358A3
,10-07 10:50:09.058  5755  5868 D bt_hwcfg: Target name = [BCM4358A3]
10-07 10:50:09.058  5755  5868 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-07 10:50:09.432   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:09.451  5755  5868 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-07 10:50:09.451  5755  5868 D bt_hwcfg: Settlement delay -- 100 ms
,10-07 10:50:09.452  5755  5868 I bt_hwcfg: Setting fw settlement delay to 100 
,10-07 10:50:09.586  5755  5868 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 10:50:09.586  5755  5868 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-07 10:50:09.588  5755  5868 I bt_hwcfg: vendor lib fwcfg completed
,10-07 10:50:09.588  5755  5868 I bt_vendor: firmware callback
10-07 10:50:09.588  5755  5868 I bt_hci  : firmware_config_callback
,10-07 10:50:09.597  5755  5871 I bt_btu  : btu_task pending for preload complete event
,10-07 10:50:09.597  5755  5871 I bt_btu_task: Bluetooth chip preload is complete
10-07 10:50:09.598  5755  5871 I bt_btu  : btu_task received preload complete event
,10-07 10:50:09.605  5755  5871 I         : BTE_InitTraceLevels -- TRC_HCI
,10-07 10:50:09.605  5755  5871 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-07 10:50:09.605  5755  5871 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-07 10:50:09.605  5755  5871 I         : BTE_InitTraceLevels -- TRC_AVDT
10-07 10:50:09.606  5755  5871 I         : BTE_InitTraceLevels -- TRC_AVRC
10-07 10:50:09.606  5755  5871 I         : BTE_InitTraceLevels -- TRC_A2D
,10-07 10:50:09.606  5755  5871 I         : BTE_InitTraceLevels -- TRC_BNEP
10-07 10:50:09.606  5755  5871 I         : BTE_InitTraceLevels -- TRC_BTM
10-07 10:50:09.606  5755  5871 I         : BTE_InitTraceLevels -- TRC_GAP
10-07 10:50:09.606  5755  5871 I         : BTE_InitTraceLevels -- TRC_PAN
,10-07 10:50:09.606  5755  5871 I         : BTE_InitTraceLevels -- TRC_SDP
10-07 10:50:09.606  5755  5871 I         : BTE_InitTraceLevels -- TRC_GATT
10-07 10:50:09.607  5755  5871 I         : BTE_InitTraceLevels -- TRC_SMP
10-07 10:50:09.607  5755  5871 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-07 10:50:09.607  5755  5871 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-07 10:50:09.689  5755  5871 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e76549
10-07 10:50:09.689  5755  5871 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e76549 
,10-07 10:50:09.717  5755  5864 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-07 10:50:09.718  5755  5864 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-07 10:50:09.719  5755  5864 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-07 10:50:09.720  5755  5864 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 10:50:09.723  5755  5864 D BluetoothAdapterProperties: Scan Mode:20
10-07 10:50:09.723  5755  5864 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 10:50:09.723  5755  5864 D bt_hci  : do_postload posting postload work item
10-07 10:50:09.724  5755  5868 I bt_hci  : event_postload
10-07 10:50:09.724  5755  5868 I bt_vendor: sco_config_cb
10-07 10:50:09.724  5755  5868 I bt_hci  : sco_config_callback postload finished.
10-07 10:50:09.726  5755  5864 D bt_bte_conf: Device ID record 1 : primary
10-07 10:50:09.726  5755  5864 D bt_bte_conf:   vendorId            = 000f
10-07 10:50:09.726  5755  5864 D bt_bte_conf:   vendorIdSource      = 0001
10-07 10:50:09.726  5755  5864 D bt_bte_conf:   product             = 1200
10-07 10:50:09.726  5755  5864 D bt_bte_conf:   version             = 1436
10-07 10:50:09.726  5755  5864 D bt_bte_conf:   clientExecutableURL = 
10-07 10:50:09.727  5755  5864 D bt_bte_conf:   serviceDescription  = 
,10-07 10:50:09.727  5755  5864 D bt_bte_conf:   documentationURL    = 
10-07 10:50:09.727  5755  5864 D bt_bte_conf: bte_load_did_conf no section named DID2.
,10-07 10:50:09.727  5755  5861 D bt_stack_manager: event_start_up_stack finished
,10-07 10:50:09.727  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:09.727  5755  5860 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-07 10:50:09.728  5755  5860 D BluetoothAdapterProperties: Setting state to 15
10-07 10:50:09.728  5755  5860 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-07 10:50:09.728  5755  5860 I BluetoothAdapterState: Entering BleOnState
10-07 10:50:09.729  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:09.732  5755  5860 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-07 10:50:09.732  5755  5860 D BluetoothAdapterProperties: Setting state to 11
10-07 10:50:09.732  5755  5860 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-07 10:50:09.733  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:09.735  5755  5868 I bt_vendor: low_power_mode_cb
10-07 10:50:09.737  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:09.738  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:09.740  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:09.744  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:09.744  5755  5755 D HeadsetService: Received start request. Starting profile...
,10-07 10:50:09.747  5755  5755 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-07 10:50:09.747  5755  5755 D HeadsetStateMachine: make
,10-07 10:50:09.756  5755  5860 I BluetoothAdapterState: Entering PendingCommandState
10-07 10:50:09.756  5755  5755 D HeadsetStateMachine: max_hf_connections = 1
10-07 10:50:09.756  5755  5755 I bt_bluedroid: get_profile_interface handsfree
10-07 10:50:09.756  5755  5864 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,10-07 10:50:09.757  5755  5864 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-07 10:50:09.759  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:09.765  5755  5755 D A2dpService: Received start request. Starting profile...
10-07 10:50:09.765  5755  5755 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-07 10:50:09.766  5755  5755 I bt_bluedroid: get_profile_interface avrcp
,10-07 10:50:09.771  5755  5755 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-07 10:50:09.771  5755  5755 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-07 10:50:09.771  5755  5755 D A2dpStateMachine: make
10-07 10:50:09.772  5755  5755 I bt_bluedroid: get_profile_interface a2dp
10-07 10:50:09.773  5755  5864 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-07 10:50:09.774  5755  5880 D A2dpStateMachine: Enter Disconnected: -2
,10-07 10:50:09.775  5755  5755 I BluetoothHidServiceJni: classInitNative: succeeds
,10-07 10:50:09.776  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:09.777  5755  5755 D HidService: Received start request. Starting profile...
10-07 10:50:09.777  5693  5693 D BluetoothInputDevice: Proxy object connected
10-07 10:50:09.777  5755  5755 I bt_bluedroid: get_profile_interface hidhost
10-07 10:50:09.777  5755  5755 D HidService: setHidService(): set to: null
10-07 10:50:09.777  5755  5864 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e5756d
10-07 10:50:09.777  5755  5864 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-07 10:50:09.778  5693  5693 D HidProfile: Bluetooth service connected
10-07 10:50:09.778  5755  5755 I BluetoothHealthServiceJni: classInitNative: succeeds
10-07 10:50:09.779  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:09.779  5755  5755 D HealthService: Received start request. Starting profile...
,10-07 10:50:09.781  5755  5755 I bt_bluedroid: get_profile_interface health
10-07 10:50:09.782  5755  5755 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-07 10:50:09.783  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:09.783  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 10:50:09.785  5693  5693 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 10:50:09.785  5755  5755 D PanService: Received start request. Starting profile...
10-07 10:50:09.785  5755  5755 D BluetoothPanServiceJni: initializeNative(L110): pan
10-07 10:50:09.785  5755  5755 I bt_bluedroid: get_profile_interface pan
10-07 10:50:09.785  5693  5693 D PanProfile: Bluetooth service connected
,10-07 10:50:09.786  5755  5864 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-07 10:50:09.788  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:09.790  5693  5693 D BluetoothMap: Proxy object connected
,10-07 10:50:09.790  5693  5693 D MapProfile: Bluetooth service connected
10-07 10:50:09.790  5693  5693 D BluetoothMap: getConnectedDevices()
10-07 10:50:09.791  5755  5755 D BluetoothMapService: Received start request. Starting profile...
10-07 10:50:09.791  5755  5755 D BluetoothMapService: start()
10-07 10:50:09.791  5693  5693 D BluetoothMap: Bluetooth is Not enabled
,10-07 10:50:09.793  5755  5755 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-07 10:50:09.794  5755  5755 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-07 10:50:09.794  5755  5755 D BluetoothMapAppObserver: createReceiver()
10-07 10:50:09.795  5755  5755 D BluetoothMapAppObserver: initObservers()
10-07 10:50:09.796  5755  5755 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-07 10:50:09.803  5755  5755 V SapService: SapBinder()
,10-07 10:50:09.803  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:09.803  5755  5755 D SapService: Received start request. Starting profile...
10-07 10:50:09.803  5755  5755 V SapService: start()
,10-07 10:50:09.805  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,10-07 10:50:09.805  5755  5755 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:09.805  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:09.805  5755  5878 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-07 10:50:09.805  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isTurningOn()=true
,10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:09.806  5755  5755 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:09.807  5755  5755 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:09.807  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:09.807  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 10:50:09.807  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,10-07 10:50:09.807  5755  5755 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:09.807  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:09.807  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 10:50:09.808  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,10-07 10:50:09.808  5755  5755 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:09.808  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:09.808  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:09.809  5755  5755 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:09.809  5755  5755 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:09.809  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:09.809  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:09.809  5755  5860 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-07 10:50:09.809  5755  5860 D BluetoothAdapterProperties: ScanMode =  20
10-07 10:50:09.809  5755  5860 D BluetoothAdapterProperties: State =  11
10-07 10:50:09.810  5755  5864 D BluetoothAdapterProperties: Scan Mode:21
10-07 10:50:09.811  5755  5864 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 10:50:09.811  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 10:50:09.811  5755  5860 D BluetoothAdapterProperties: Setting state to 12
10-07 10:50:09.811  5755  5860 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-07 10:50:09.811  3085  3887 D BluetoothMap: onBluetoothStateChange: up=true
10-07 10:50:09.812  5755  5860 I BluetoothAdapterState: Entering OnState
10-07 10:50:09.814  3085  3085 D BluetoothMap: Proxy object connected
10-07 10:50:09.814  3085  3085 D MapProfile: Bluetooth service connected
,10-07 10:50:09.814  3085  3085 D BluetoothMap: getConnectedDevices()
10-07 10:50:09.814  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:09.814  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:09.814  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:09.814  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:09.814  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:09.814  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:09.814  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:09.814  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 10:50:09.814  5693  5707 D BluetoothMap: onBluetoothStateChange: up=true
10-07 10:50:09.815   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 10:50:09.815   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 10:50:09.815  3085  3098 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 10:50:09.816   927   927 D BluetoothA2dp: Proxy object connected
10-07 10:50:09.816  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:09.817  3085  3887 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 10:50:09.817  3085  3085 D BluetoothInputDevice: Proxy object connected
10-07 10:50:09.817  3085  3085 D HidProfile: Bluetooth service connected
10-07 10:50:09.820   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-07 10:50:09.820  5693  5704 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 10:50:09.820  3085  3085 D BluetoothA2dp: Proxy object connected
10-07 10:50:09.821  5755  5755 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 10:50:09.821  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:09.821  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:09.821  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:09.821  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:09.821  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:09.821  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:09.821  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:09.821  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:09.821  3727  4184 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 10:50:09.822  5755  5755 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-07 10:50:09.822   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-07 10:50:09.822  3085  3097 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 10:50:09.822  3085  3887 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 10:50:09.823  5755  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 10:50:09.823  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:09.824  5693  5707 D BluetoothPan: onBluetoothStateChange on: true
10-07 10:50:09.824  5693  5704 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 10:50:09.824  5755  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 10:50:09.825  3085  3097 D BluetoothPan: onBluetoothStateChange on: true
10-07 10:50:09.826  3085  3085 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 10:50:09.826  3085  3085 D PanProfile: Bluetooth service connected
10-07 10:50:09.827  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:09.827  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:09.827  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:09.827  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:09.827  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:09.827  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:09.827  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:09.827  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:09.827   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,10-07 10:50:09.829  5755  5755 D ObexServerSockets: Succeed to create listening sockets 
,10-07 10:50:09.829  5755  5755 D ObexServerSockets0: startAccept()
10-07 10:50:09.829  5755  5755 D ObexServerSockets0: prepareForNewConnect()
10-07 10:50:09.830  5693  5693 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-07 10:50:09.831  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 10:50:09.832  5755  5755 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-07 10:50:09.832  5755  5755 D BluetoothSdpJni: SDP Create record success - handle: 0
10-07 10:50:09.832  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 10:50:09.832  5755  5886 D ObexServerSockets0: Accepting socket connection...
10-07 10:50:09.832  5755  5755 D BluetoothMapService: onReceive
10-07 10:50:09.832  5755  5755 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 10:50:09.832  5755  5755 D BluetoothMapService: STATE_ON
10-07 10:50:09.833  5755  5887 D ObexServerSockets0: Accepting socket connection...
10-07 10:50:09.834  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:09.836  5755  5888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 10:50:09.836  5693  5693 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-07 10:50:09.836  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:09.837  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:09.838  5755  5888 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-07 10:50:09.838  5755  5888 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-07 10:50:09.844  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 10:50:09.846  5693  5693 D BluetoothA2dp: Proxy object connected
,10-07 10:50:09.850  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 10:50:09.854  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,10-07 10:50:09.858  5693  5693 D BluetoothPbap: Proxy object connected
10-07 10:50:09.858  5693  5693 D PbapServerProfile: Bluetooth service connected
10-07 10:50:09.859  5755  5755 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 10:50:09.859  5755  5755 D ObexServerSockets0: prepareForNewConnect()
10-07 10:50:09.860  3085  3085 D BluetoothPbap: Proxy object connected
10-07 10:50:09.861  3085  3085 D PbapServerProfile: Bluetooth service connected
,10-07 10:50:09.867  5755  5892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 10:50:09.882  5755  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 10:50:09.884  5755  5896 I BtOppRfcommListener: Accept thread started.
,10-07 10:50:09.917  3085  3097 D BluetoothHeadset: Proxy object connected
10-07 10:50:09.917  3085  3085 D HeadsetProfile: Bluetooth service connected
,10-07 10:50:09.917   927   927 D BluetoothHeadset: Proxy object connected
10-07 10:50:09.918  3727  3755 D BluetoothHeadset: Proxy object connected
10-07 10:50:09.918   927   927 D BluetoothHeadset: Proxy object connected
10-07 10:50:09.918   927   927 D BluetoothHeadset: Proxy object connected
,10-07 10:50:09.920   927   944 D BluetoothHeadset: Proxy object connected
,10-07 10:50:09.922  3727  3982 D BluetoothHeadset: Proxy object connected
10-07 10:50:09.922   927   944 D BluetoothHeadset: Proxy object connected
,10-07 10:50:09.922  3085  3098 D BluetoothHeadset: Proxy object connected
10-07 10:50:09.922  3085  3085 D HeadsetProfile: Bluetooth service connected
,10-07 10:50:09.938  5693  5707 D BluetoothHeadset: Proxy object connected
,10-07 10:50:09.939  5693  5693 D HeadsetProfile: Bluetooth service connected
,10-07 10:50:10.433   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-07 10:50:11.644   927  2973 D ConnectivityService: handlePromptUnvalidated 101
,10-07 10:50:13.851  5755  5860 D BluetoothAdapterState: Current state: ON, message: 23
10-07 10:50:13.851  5755  5860 D BluetoothAdapterProperties: Setting state to 13
,10-07 10:50:13.851  5755  5860 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-07 10:50:13.852  5755  5860 D BluetoothAdapterProperties: onBluetoothDisable()
10-07 10:50:13.854  5755  5860 I BluetoothAdapterState: Entering PendingCommandState
,10-07 10:50:13.861  5755  5755 D BluetoothMapService: onReceive
,10-07 10:50:13.861  5755  5755 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 10:50:13.861  5755  5755 D BluetoothMapService: STATE_TURNING_OFF
10-07 10:50:13.862  5755  5755 D BluetoothMapService: MAP Service closeService in
10-07 10:50:13.862  5755  5755 D BluetoothMapMasInstance0: MAP Service shutdown
10-07 10:50:13.862  5755  5755 D ObexServerSockets0: shutdown(block = true)
,10-07 10:50:13.863  5755  5755 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-07 10:50:13.864  5755  5873 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-07 10:50:13.864  5755  5886 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-07 10:50:13.864  5755  5887 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-07 10:50:13.864  5755  5755 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 10:50:13.867  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:13.868  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:13.868  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:13.868  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:13.868  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:13.868  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:13.868  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:13.868  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:13.868  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:13.869  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:13.869  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:13.869  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 10:50:13.869  5755  5755 I BtOppRfcommListener: stopping Accept Thread
10-07 10:50:13.869  5755  5896 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-07 10:50:13.870  5755  5896 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-07 10:50:13.871  5755  5864 D BluetoothAdapterProperties: Scan Mode:20
10-07 10:50:13.872  5755  5860 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-07 10:50:13.873  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:13.873  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:13.873  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:13.873  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:13.873  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:13.873  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:13.873  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:13.873  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:13.873  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:13.874  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 10:50:13.875  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:13.878  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:13.878  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:13.878  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:13.878  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:13.878  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:13.878  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 10:50:13.878  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:13.878  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:13.878  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:13.879  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,10-07 10:50:13.879  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 10:50:13.879  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:13.881  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:13.883  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:13.885  5755  5755 D HeadsetService: Received stop request...Stopping profile...
10-07 10:50:13.885  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:13.892  5693  5704 D BluetoothHeadset: Proxy object disconnected
,10-07 10:50:13.893  3085  3098 D BluetoothHeadset: Proxy object disconnected
,10-07 10:50:13.893  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 10:50:13.893  3085  3085 D HeadsetProfile: Bluetooth service disconnected
10-07 10:50:13.893   927   927 D BluetoothHeadset: Proxy object disconnected
10-07 10:50:13.893  3727  3760 D BluetoothHeadset: Proxy object disconnected
10-07 10:50:13.894   927   927 D BluetoothHeadset: Proxy object disconnected
,10-07 10:50:13.894   927   927 D BluetoothHeadset: Proxy object disconnected
10-07 10:50:13.895  5755  5755 D A2dpService: Received stop request...Stopping profile...
10-07 10:50:13.896  5755  5880 D A2dpStateMachine: Exit Disconnected: -1
10-07 10:50:13.897   927   927 D BluetoothA2dp: Proxy object disconnected
10-07 10:50:13.898  3085  3085 D BluetoothA2dp: Proxy object disconnected
10-07 10:50:13.898  5755  5755 D HidService: Received stop request...Stopping profile...
10-07 10:50:13.898  5755  5755 D HidService: Stopping Bluetooth HidService
10-07 10:50:13.899  5693  5693 D HeadsetProfile: Bluetooth service disconnected
10-07 10:50:13.899  5693  5693 D BluetoothA2dp: Proxy object disconnected
10-07 10:50:13.899  3085  3085 D BluetoothInputDevice: Proxy object disconnected
10-07 10:50:13.900  3085  3085 D HidProfile: Bluetooth service disconnected
,10-07 10:50:13.900  5693  5693 D BluetoothInputDevice: Proxy object disconnected
10-07 10:50:13.900  5693  5693 D HidProfile: Bluetooth service disconnected
10-07 10:50:13.900  5755  5755 D HealthService: Received stop request...Stopping profile...
,10-07 10:50:13.901  5755  5755 D PanService: Received stop request...Stopping profile...
,10-07 10:50:13.902  3085  3085 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-07 10:50:13.902  3085  3085 D PanProfile: Bluetooth service disconnected
10-07 10:50:13.902  5693  5693 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-07 10:50:13.902  5693  5693 D PanProfile: Bluetooth service disconnected
10-07 10:50:13.903  5755  5755 V BluetoothAdapterState: isTurningOff()=true
10-07 10:50:13.903  5755  5755 V BluetoothAdapterState: isTurningOn()=false
,10-07 10:50:13.903  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:13.903  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:13.903  5755  5755 D BluetoothMapService: Received stop request...Stopping profile...
10-07 10:50:13.904  5755  5755 D BluetoothMapService: stop()
10-07 10:50:13.904  5755  5755 D BluetoothMapAppObserver: deinitObservers()
,10-07 10:50:13.905  5755  5755 D BluetoothMapAppObserver: removeReceiver()
10-07 10:50:13.906  3085  3085 D BluetoothMap: Proxy object disconnected
10-07 10:50:13.906  5693  5693 D BluetoothMap: Proxy object disconnected
10-07 10:50:13.906  5693  5693 D MapProfile: Bluetooth service disconnected
10-07 10:50:13.906  3085  3085 D MapProfile: Bluetooth service disconnected
,10-07 10:50:13.908  5755  5755 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-07 10:50:13.908  5755  5755 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-07 10:50:13.909  5755  5871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:50:13.909  5755  5871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:50:13.909  5755  5871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:50:13.909  5755  5864 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-07 10:50:13.909  5755  5864 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-07 10:50:13.910  3085  3085 D BluetoothPbap: Proxy object disconnected
10-07 10:50:13.910  3085  3085 D PbapServerProfile: Bluetooth service disconnected
10-07 10:50:13.910  5693  5693 D BluetoothPbap: Proxy object disconnected
10-07 10:50:13.910  5693  5693 D PbapServerProfile: Bluetooth service disconnected
10-07 10:50:13.911  5755  5755 D SapService: Received stop request...Stopping profile...
10-07 10:50:13.911  5755  5755 V SapService: stop()
,10-07 10:50:13.913  5755  5755 V BluetoothAdapterState: isTurningOff()=true
10-07 10:50:13.913  5755  5755 V BluetoothAdapterState: isTurningOn()=false
,10-07 10:50:13.913  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:13.913  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 10:50:13.914  5755  5864 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-07 10:50:13.914  5755  5871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:50:13.915  5755  5871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:50:13.915  5755  5755 V BluetoothAdapterState: isTurningOff()=true
10-07 10:50:13.915  5755  5871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 10:50:13.915  5755  5755 V BluetoothAdapterState: isTurningOn()=false
,10-07 10:50:13.915  5755  5871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 10:50:13.915  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:13.915  5755  5871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 10:50:13.915  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:13.915  5755  5871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 10:50:13.915  5755  5755 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-07 10:50:13.915  5755  5755 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-07 10:50:13.916  5755  5755 V BluetoothAdapterState: isTurningOff()=true
10-07 10:50:13.916  5755  5755 V BluetoothAdapterState: isTurningOn()=false
10-07 10:50:13.916  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:13.916  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:13.916  5755  5755 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-07 10:50:13.916  5755  5755 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-07 10:50:13.917  5755  5755 V BluetoothAdapterState: isTurningOff()=true
10-07 10:50:13.917  5755  5755 V BluetoothAdapterState: isTurningOn()=false
10-07 10:50:13.917  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:13.917  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 10:50:13.917  5755  5755 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-07 10:50:13.917  5755  5755 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-07 10:50:13.918  5755  5755 D BluetoothMapService: MAP Service closeService in
10-07 10:50:13.918  5755  5755 V BluetoothAdapterState: isTurningOff()=true
10-07 10:50:13.918  5755  5755 V BluetoothAdapterState: isTurningOn()=false
10-07 10:50:13.918  5755  5864 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-07 10:50:13.918  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:13.918  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:13.918  5755  5864 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-07 10:50:13.918  5755  5755 D BluetoothMapService: cleanup()
10-07 10:50:13.918  5755  5755 D BluetoothMapService: MAP Service closeService in
10-07 10:50:13.919  5755  5755 V BluetoothAdapterState: isTurningOff()=true
10-07 10:50:13.919  5755  5755 V BluetoothAdapterState: isTurningOn()=false
10-07 10:50:13.919  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:13.919  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:13.919  5755  5860 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-07 10:50:13.919  5755  5860 D BluetoothAdapterProperties: Setting state to 15
10-07 10:50:13.919  5755  5860 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-07 10:50:13.920  5755  5860 I BluetoothAdapterState: Entering BleOnState
10-07 10:50:13.920  3085  3098 D BluetoothMap: onBluetoothStateChange: up=false
,10-07 10:50:13.922  5693  5707 D BluetoothMap: onBluetoothStateChange: up=false
,10-07 10:50:13.924   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 10:50:13.924   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:50:13.925  3085  3097 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-07 10:50:13.925  3085  3887 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 10:50:13.925   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:50:13.926  5693  5704 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 10:50:13.926  5693  5707 D BluetoothPbap: onBluetoothStateChange: up=false
,10-07 10:50:13.927  3727  4184 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:50:13.927   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:50:13.927  3085  3098 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:50:13.927  3085  3097 D BluetoothPbap: onBluetoothStateChange: up=false
10-07 10:50:13.928  5693  5704 D BluetoothPan: onBluetoothStateChange on: false
10-07 10:50:13.928  5693  5707 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-07 10:50:13.929  3085  3887 D BluetoothPan: onBluetoothStateChange on: false
10-07 10:50:13.929  5693  5704 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 10:50:13.930  5755  5860 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-07 10:50:13.930  5755  5860 D BluetoothAdapterProperties: Setting state to 16
10-07 10:50:13.930  5755  5860 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-07 10:50:13.931  5755  5860 D BluetoothAdapterProperties: onBleDisable
,10-07 10:50:13.931  5755  5860 I BluetoothAdapterState: Entering PendingCommandState
10-07 10:50:13.931  5755  5861 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-07 10:50:13.932  5755  5871 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-07 10:50:13.932  5755  5871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 10:50:13.932  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:13.933  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 10:50:13.934  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:13.935  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:13.938  5755  5864 D BluetoothAdapterProperties: Scan Mode:20
10-07 10:50:13.940  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:13.941  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 10:50:13.942  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,10-07 10:50:13.942  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:13.945  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:14.151  5755  5864 I bt_hci  : shut_down
,10-07 10:50:14.162  5755  5868 D bt_hwcfg: hw_epilog_process
,10-07 10:50:14.163  5755  5868 I bt_vendor: low_power_mode_cb
,10-07 10:50:14.165  5755  5868 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-07 10:50:14.165  5755  5868 I bt_vendor: epilog_cb
10-07 10:50:14.165  5755  5868 I bt_hci  : epilog_finished_callback
,10-07 10:50:14.168  5755  5864 I bt_hci_h4: hal_close
,10-07 10:50:14.169  5755  5864 I bt_userial_vendor: device fd = 54 close
,10-07 10:50:14.283  5755  5861 D bt_stack_manager: event_shut_down_stack finished.
,10-07 10:50:14.284  5755  5860 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-07 10:50:14.288  5755  5755 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-07 10:50:14.289  5755  5860 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-07 10:50:14.289  5755  5755 D BtGatt.GattService: Received stop request...Stopping profile...
,10-07 10:50:14.289  5755  5755 D BtGatt.GattService: stop()
10-07 10:50:14.290  5755  5755 D BtGatt.AdvertiseManager: advertise clients cleared
10-07 10:50:14.293  5755  5755 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:14.293  5755  5755 V BluetoothAdapterState: isTurningOn()=false
10-07 10:50:14.293  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:14.293  5755  5755 V BluetoothAdapterState: isBleTurningOff()=true
10-07 10:50:14.294  5755  5860 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-07 10:50:14.294  5755  5860 D BluetoothAdapterProperties: Setting state to 10
10-07 10:50:14.294  5755  5860 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-07 10:50:14.295  5755  5860 I BluetoothAdapterState: Entering OffState
10-07 10:50:14.296   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-07 10:50:14.309  5755  5755 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-07 10:50:14.309  5755  5755 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,10-07 10:50:14.309  5755  5755 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-07 10:50:14.312  5755  5861 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-07 10:50:14.318  5755  5755 I art     : System.exit called, status: 0
,10-07 10:50:14.319  5755  5755 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-07 10:50:14.350   927   937 I ActivityManager: Process com.android.bluetooth (pid 5755) has died
,10-07 10:50:18.849  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 10:50:18.849  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:50:18.854  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 10:50:18.854  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@208b7fc removed from the list
10-07 10:50:18.854  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:50:18.855  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:18.855  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:50:18.857  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:18.857  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d9524da added. We now have 4 listener(s)
,10-07 10:50:18.858  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 10:50:18.859  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:18.860  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d9524da removed from the list
10-07 10:50:18.860  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 10:50:18.860  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:18.860  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:18.862  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:18.862  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4574d0b added. We now have 4 listener(s)
10-07 10:50:18.862  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 10:50:23.873  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:23.905   927   944 I ActivityManager: Start proc 5904:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-07 10:50:24.009  5904  5904 D AdapterServiceConfig: Adding HeadsetService
,10-07 10:50:24.010  5904  5904 D AdapterServiceConfig: Adding A2dpService
10-07 10:50:24.010  5904  5904 D AdapterServiceConfig: Adding HidService
10-07 10:50:24.010  5904  5904 D AdapterServiceConfig: Adding HealthService
10-07 10:50:24.010  5904  5904 D AdapterServiceConfig: Adding PanService
10-07 10:50:24.010  5904  5904 D AdapterServiceConfig: Adding GattService
10-07 10:50:24.010  5904  5904 D AdapterServiceConfig: Adding BluetoothMapService
10-07 10:50:24.011  5904  5904 D AdapterServiceConfig: Adding SapService
,10-07 10:50:24.023   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7ef9b3a:true
,10-07 10:50:24.023  5904  5904 D BluetoothAdapterState: make() - Creating AdapterState
,10-07 10:50:24.027  5904  5904 I bt_bluedroid: init
,10-07 10:50:24.027  5904  5916 I BluetoothAdapterState: Entering OffState
,10-07 10:50:24.030  5904  5917 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-07 10:50:24.030  5904  5917 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-07 10:50:24.030  5904  5917 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-07 10:50:24.030  5904  5917 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-07 10:50:24.031  5904  5904 I bt_bluedroid: get_profile_interface socket
,10-07 10:50:24.033  5904  5904 I bt_bluedroid: get_profile_interface sdp
,10-07 10:50:24.033  5904  5920 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-07 10:50:24.034  5904  5920 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 10:50:24.037  5904  5915 I bt_bluedroid: config_hci_snoop_log
10-07 10:50:24.039   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-07 10:50:24.042  5904  5916 D BluetoothAdapterState: Current state: OFF, message: 0
10-07 10:50:24.043  5904  5916 D BluetoothAdapterProperties: Setting state to 14
10-07 10:50:24.043  5904  5916 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-07 10:50:24.044  5904  5916 D BluetoothBondStateMachine: make
,10-07 10:50:24.046  5904  5921 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-07 10:50:24.049  5904  5916 I BluetoothAdapterState: Entering PendingCommandState
,10-07 10:50:24.051  5904  5904 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-07 10:50:24.053  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:24.054  5904  5904 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-07 10:50:24.054  5904  5904 D BtGatt.GattService: Received start request. Starting profile...
10-07 10:50:24.055  5904  5904 D BtGatt.GattService: start()
10-07 10:50:24.055  5904  5904 I bt_bluedroid: get_profile_interface gatt
10-07 10:50:24.056  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:24.056  5904  5904 D BtGatt.AdvertiseManager: advertise manager created
,10-07 10:50:24.061  5904  5904 V BluetoothAdapterState: isTurningOff()=false
,10-07 10:50:24.062  5904  5904 V BluetoothAdapterState: isTurningOn()=false
10-07 10:50:24.062  5904  5904 V BluetoothAdapterState: isBleTurningOn()=true
10-07 10:50:24.062  5904  5904 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:24.062  5904  5916 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-07 10:50:24.063  5904  5916 I bt_bluedroid: bt_bluedroid
10-07 10:50:24.063  5904  5917 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-07 10:50:24.063  5904  5917 I bt_hci  : start_up
,10-07 10:50:24.069  5904  5917 I bt_vendor: alloc value 0xf3f55871
,10-07 10:50:24.069  5904  5917 I bt_vendor: init
10-07 10:50:24.069  5904  5917 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-07 10:50:24.069  5904  5917 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-07 10:50:24.178  5904  5917 D bt_hci  : start_up starting async portion
10-07 10:50:24.179  5904  5924 I bt_hci  : event_finish_startup
10-07 10:50:24.179  5904  5924 I bt_hci_h4: hal_open
10-07 10:50:24.179  5904  5924 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-07 10:50:24.175  5925  5925 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-07 10:50:24.182  5904  5924 I bt_userial_vendor: device fd = 54 open
,10-07 10:50:24.196  5904  5924 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 10:50:24.199  5904  5924 D bt_hwcfg: Chipset BCM4358A3
,10-07 10:50:24.199  5904  5924 D bt_hwcfg: Target name = [BCM4358A3]
10-07 10:50:24.200  5904  5924 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-07 10:50:24.602  5904  5924 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-07 10:50:24.603  5904  5924 D bt_hwcfg: Settlement delay -- 100 ms
10-07 10:50:24.603  5904  5924 I bt_hwcfg: Setting fw settlement delay to 100 
,10-07 10:50:24.738  5904  5924 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-07 10:50:24.738  5904  5924 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-07 10:50:24.740  5904  5924 I bt_hwcfg: vendor lib fwcfg completed
10-07 10:50:24.740  5904  5924 I bt_vendor: firmware callback
10-07 10:50:24.740  5904  5924 I bt_hci  : firmware_config_callback
,10-07 10:50:24.750  5904  5927 I bt_btu  : btu_task pending for preload complete event
,10-07 10:50:24.750  5904  5927 I bt_btu_task: Bluetooth chip preload is complete
10-07 10:50:24.750  5904  5927 I bt_btu  : btu_task received preload complete event
,10-07 10:50:24.756  5904  5927 I         : BTE_InitTraceLevels -- TRC_HCI
,10-07 10:50:24.757  5904  5927 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-07 10:50:24.757  5904  5927 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-07 10:50:24.757  5904  5927 I         : BTE_InitTraceLevels -- TRC_AVDT
10-07 10:50:24.757  5904  5927 I         : BTE_InitTraceLevels -- TRC_AVRC
10-07 10:50:24.757  5904  5927 I         : BTE_InitTraceLevels -- TRC_A2D
,10-07 10:50:24.757  5904  5927 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-07 10:50:24.758  5904  5927 I         : BTE_InitTraceLevels -- TRC_BTM
10-07 10:50:24.758  5904  5927 I         : BTE_InitTraceLevels -- TRC_GAP
,10-07 10:50:24.758  5904  5927 I         : BTE_InitTraceLevels -- TRC_PAN
10-07 10:50:24.758  5904  5927 I         : BTE_InitTraceLevels -- TRC_SDP
,10-07 10:50:24.758  5904  5927 I         : BTE_InitTraceLevels -- TRC_GATT
10-07 10:50:24.758  5904  5927 I         : BTE_InitTraceLevels -- TRC_SMP
10-07 10:50:24.758  5904  5927 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-07 10:50:24.758  5904  5927 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-07 10:50:24.840  5904  5927 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ed3549
,10-07 10:50:24.840  5904  5927 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ed3549 
,10-07 10:50:24.852  5904  5920 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-07 10:50:24.854  5904  5920 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-07 10:50:24.854  5904  5920 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-07 10:50:24.856  5904  5920 D BluetoothAdapterProperties: Name is: Nexus 6P
10-07 10:50:24.860  5904  5920 D BluetoothAdapterProperties: Scan Mode:20
10-07 10:50:24.862  5904  5920 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 10:50:24.862  5904  5920 D bt_hci  : do_postload posting postload work item
10-07 10:50:24.862  5904  5924 I bt_hci  : event_postload
,10-07 10:50:24.862  5904  5924 I bt_vendor: sco_config_cb
10-07 10:50:24.862  5904  5924 I bt_hci  : sco_config_callback postload finished.
10-07 10:50:24.863  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:24.867  5904  5920 D bt_bte_conf: Device ID record 1 : primary
10-07 10:50:24.867  5904  5920 D bt_bte_conf:   vendorId            = 000f
10-07 10:50:24.867  5904  5920 D bt_bte_conf:   vendorIdSource      = 0001
10-07 10:50:24.867  5904  5920 D bt_bte_conf:   product             = 1200
10-07 10:50:24.867  5904  5920 D bt_bte_conf:   version             = 1436
10-07 10:50:24.867  5904  5920 D bt_bte_conf:   clientExecutableURL = 
10-07 10:50:24.867  5904  5920 D bt_bte_conf:   serviceDescription  = 
10-07 10:50:24.867  5904  5920 D bt_bte_conf:   documentationURL    = 
10-07 10:50:24.868  5904  5920 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-07 10:50:24.868  5904  5917 D bt_stack_manager: event_start_up_stack finished
10-07 10:50:24.869  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:24.869  5904  5916 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-07 10:50:24.870  5904  5916 D BluetoothAdapterProperties: Setting state to 15
10-07 10:50:24.870  5904  5916 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-07 10:50:24.870  5904  5924 I bt_vendor: low_power_mode_cb
10-07 10:50:24.872  5904  5916 I BluetoothAdapterState: Entering BleOnState
10-07 10:50:24.881  5904  5916 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-07 10:50:24.881  5904  5916 D BluetoothAdapterProperties: Setting state to 11
10-07 10:50:24.881  5904  5916 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-07 10:50:24.888  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:24.889  5904  5904 D HeadsetService: Received start request. Starting profile...
,10-07 10:50:24.891  5904  5904 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-07 10:50:24.892  5904  5904 D HeadsetStateMachine: make
10-07 10:50:24.893  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:24.896  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:24.906  5904  5916 I BluetoothAdapterState: Entering PendingCommandState
,10-07 10:50:24.908  5904  5904 D HeadsetStateMachine: max_hf_connections = 1
,10-07 10:50:24.908  5904  5904 I bt_bluedroid: get_profile_interface handsfree
10-07 10:50:24.908  5904  5920 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-07 10:50:24.908  5904  5920 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-07 10:50:24.912  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:24.912  5904  5904 D A2dpService: Received start request. Starting profile...
10-07 10:50:24.913  5904  5904 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-07 10:50:24.913  5904  5904 I bt_bluedroid: get_profile_interface avrcp
,10-07 10:50:24.922  5904  5904 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-07 10:50:24.923  5904  5904 I BluetoothA2dpServiceJni: classInitNative: succeeds
,10-07 10:50:24.923  5904  5904 D A2dpStateMachine: make
10-07 10:50:24.924  5904  5904 I bt_bluedroid: get_profile_interface a2dp
,10-07 10:50:24.924  5904  5920 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-07 10:50:24.925  5904  5935 D A2dpStateMachine: Enter Disconnected: -2
,10-07 10:50:24.926  5904  5904 I BluetoothHidServiceJni: classInitNative: succeeds
,10-07 10:50:24.926  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:24.927  5904  5904 D HidService: Received start request. Starting profile...
10-07 10:50:24.927  5904  5904 I bt_bluedroid: get_profile_interface hidhost
10-07 10:50:24.927  5904  5904 D HidService: setHidService(): set to: null
10-07 10:50:24.928  5904  5904 I BluetoothHealthServiceJni: classInitNative: succeeds
10-07 10:50:24.929  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:24.929  5904  5920 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3eb456d
10-07 10:50:24.929  5904  5920 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-07 10:50:24.930  5904  5904 D HealthService: Received start request. Starting profile...
10-07 10:50:24.931  5904  5904 I bt_bluedroid: get_profile_interface health
,10-07 10:50:24.932  5904  5904 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-07 10:50:24.933  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:24.933  5904  5904 D PanService: Received start request. Starting profile...
,10-07 10:50:24.933  5904  5904 D BluetoothPanServiceJni: initializeNative(L110): pan
10-07 10:50:24.933  5904  5904 I bt_bluedroid: get_profile_interface pan
10-07 10:50:24.933  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 10:50:24.935  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:24.936  5904  5904 D BluetoothMapService: Received start request. Starting profile...
10-07 10:50:24.936  5904  5904 D BluetoothMapService: start()
,10-07 10:50:24.937  5904  5920 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-07 10:50:24.938  5904  5904 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-07 10:50:24.941  5904  5904 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-07 10:50:24.941  5904  5904 D BluetoothMapAppObserver: createReceiver()
10-07 10:50:24.945  5904  5904 D BluetoothMapAppObserver: initObservers()
10-07 10:50:24.945  5904  5904 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-07 10:50:24.950  5904  5904 V SapService: SapBinder()
,10-07 10:50:24.950  5904  5904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
10-07 10:50:24.950  5904  5904 D SapService: Received start request. Starting profile...
10-07 10:50:24.950  5904  5904 V SapService: start()
,10-07 10:50:24.951  5904  5904 V BluetoothAdapterState: isTurningOff()=false
,10-07 10:50:24.951  5904  5904 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:24.951  5904  5904 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:24.951  5904  5904 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:24.951  5904  5932 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,10-07 10:50:24.951  5904  5904 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:24.951  5904  5904 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:24.951  5904  5904 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:24.951  5904  5904 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isTurningOn()=true
,10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 10:50:24.952  5904  5904 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:24.953  5904  5904 V BluetoothAdapterState: isTurningOff()=false
10-07 10:50:24.953  5904  5904 V BluetoothAdapterState: isTurningOn()=true
10-07 10:50:24.953  5904  5904 V BluetoothAdapterState: isBleTurningOn()=false
10-07 10:50:24.953  5904  5904 V BluetoothAdapterState: isBleTurningOff()=false
10-07 10:50:24.953  5904  5916 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-07 10:50:24.953  5904  5916 D BluetoothAdapterProperties: ScanMode =  20
10-07 10:50:24.953  5904  5916 D BluetoothAdapterProperties: State =  11
,10-07 10:50:24.958  5904  5920 D BluetoothAdapterProperties: Scan Mode:21
,10-07 10:50:24.958  5904  5920 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 10:50:24.958  5904  5916 D BluetoothAdapterProperties: Setting state to 12
10-07 10:50:24.958  5904  5916 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-07 10:50:24.958  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 10:50:24.959  3085  3887 D BluetoothMap: onBluetoothStateChange: up=true
10-07 10:50:24.960  5693  5707 D BluetoothMap: onBluetoothStateChange: up=true
10-07 10:50:24.961  3085  3085 D BluetoothMap: Proxy object connected
10-07 10:50:24.961  3085  3085 D MapProfile: Bluetooth service connected
10-07 10:50:24.961  3085  3085 D BluetoothMap: getConnectedDevices()
10-07 10:50:24.961  5904  5916 I BluetoothAdapterState: Entering OnState
,10-07 10:50:24.962  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:24.962  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:24.962  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:24.962  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:24.962  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:24.962  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:24.962  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:24.962  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:24.962   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 10:50:24.962  5693  5693 D BluetoothMap: Proxy object connected
10-07 10:50:24.962  5693  5693 D MapProfile: Bluetooth service connected
10-07 10:50:24.962  5693  5693 D BluetoothMap: getConnectedDevices()
10-07 10:50:24.963   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-07 10:50:24.963  3085  3097 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-07 10:50:24.963  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:24.963   927   927 D BluetoothA2dp: Proxy object connected
10-07 10:50:24.965  3085  3887 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 10:50:24.966  3085  3085 D BluetoothInputDevice: Proxy object connected
10-07 10:50:24.966  3085  3085 D HidProfile: Bluetooth service connected
10-07 10:50:24.966  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:24.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:24.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:24.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:24.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:24.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:24.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:24.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 10:50:24.966   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 10:50:24.967  5693  5704 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 10:50:24.967  3085  3085 D BluetoothA2dp: Proxy object connected
,10-07 10:50:24.968  5693  5707 D BluetoothPbap: onBluetoothStateChange: up=true
,10-07 10:50:24.969  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 10:50:24.970  5904  5904 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 10:50:24.970  3727  4184 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 10:50:24.970  5904  5904 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-07 10:50:24.970   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 10:50:24.970  3085  3098 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 10:50:24.971  5693  5693 D BluetoothA2dp: Proxy object connected
10-07 10:50:24.971  3085  3887 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 10:50:24.971  5904  5904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 10:50:24.972  5904  5904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 10:50:24.973  5693  5940 D BluetoothPan: onBluetoothStateChange on: true
,10-07 10:50:24.973  5904  5904 D ObexServerSockets: Succeed to create listening sockets 
10-07 10:50:24.973  5904  5904 D ObexServerSockets0: startAccept()
10-07 10:50:24.973  5904  5904 D ObexServerSockets0: prepareForNewConnect()
,10-07 10:50:24.974  5693  5704 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-07 10:50:24.976  5904  5904 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-07 10:50:24.976  5904  5904 D BluetoothSdpJni: SDP Create record success - handle: 0
10-07 10:50:24.976  3085  3097 D BluetoothPan: onBluetoothStateChange on: true
10-07 10:50:24.976  5904  5943 D ObexServerSockets0: Accepting socket connection...
10-07 10:50:24.976  5904  5944 D ObexServerSockets0: Accepting socket connection...
10-07 10:50:24.978  3085  3085 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 10:50:24.978  3085  3085 D PanProfile: Bluetooth service connected
,10-07 10:50:24.978  5693  5707 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 10:50:24.979  5693  5693 D BluetoothInputDevice: Proxy object connected
10-07 10:50:24.979  5693  5693 D HidProfile: Bluetooth service connected
10-07 10:50:24.979   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-07 10:50:24.979  5904  5904 D BluetoothMapService: onReceive
10-07 10:50:24.979  5904  5904 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 10:50:24.979  5904  5904 D BluetoothMapService: STATE_ON
10-07 10:50:24.980  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 10:50:24.981  5693  5693 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 10:50:24.981  5693  5693 D PanProfile: Bluetooth service connected
,10-07 10:50:24.981  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:24.981  5904  5945 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 10:50:24.982  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:24.982  5904  5945 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-07 10:50:24.982  5904  5945 D BluetoothSdpJni: SDP Create record success - handle: 1
10-07 10:50:24.984  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 10:50:24.991  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 10:50:24.992  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,10-07 10:50:24.994  5693  5693 D BluetoothPbap: Proxy object connected
10-07 10:50:24.995  5693  5693 D PbapServerProfile: Bluetooth service connected
,10-07 10:50:24.997  5904  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 10:50:24.997  3085  3085 D BluetoothPbap: Proxy object connected
10-07 10:50:24.997  3085  3085 D PbapServerProfile: Bluetooth service connected
,10-07 10:50:25.008  5904  5904 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-07 10:50:25.008  5904  5904 D ObexServerSockets0: prepareForNewConnect()
,10-07 10:50:25.012  5904  5953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 10:50:25.014  5904  5953 I BtOppRfcommListener: Accept thread started.
,10-07 10:50:25.065  5693  5940 D BluetoothHeadset: Proxy object connected
,10-07 10:50:25.065  3085  3097 D BluetoothHeadset: Proxy object connected
10-07 10:50:25.065  3085  3085 D HeadsetProfile: Bluetooth service connected
10-07 10:50:25.065   927   927 D BluetoothHeadset: Proxy object connected
10-07 10:50:25.066  3727  3755 D BluetoothHeadset: Proxy object connected
10-07 10:50:25.066   927   927 D BluetoothHeadset: Proxy object connected
10-07 10:50:25.066   927   927 D BluetoothHeadset: Proxy object connected
10-07 10:50:25.066   927   944 D BluetoothHeadset: Proxy object connected
10-07 10:50:25.068  5693  5693 D HeadsetProfile: Bluetooth service connected
,10-07 10:50:25.070  3727  3982 D BluetoothHeadset: Proxy object connected
,10-07 10:50:25.070   927   944 D BluetoothHeadset: Proxy object connected
10-07 10:50:25.071  3085  3098 D BluetoothHeadset: Proxy object connected
,10-07 10:50:25.071  3085  3085 D HeadsetProfile: Bluetooth service connected
,10-07 10:50:25.078  5693  5707 D BluetoothHeadset: Proxy object connected
,10-07 10:50:25.079  5693  5693 D HeadsetProfile: Bluetooth service connected
,10-07 10:50:28.888  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:28.888  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:28.888  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:28.888  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 10:50:28.888  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:28.888  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:28.888  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:28.888  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 10:50:28.896  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 10:50:28.897  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:28.897  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4574d0b removed from the list
10-07 10:50:28.897  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:50:28.898  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:50:28.898  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:28.900  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:28.900  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42757e8 added. We now have 4 listener(s)
,10-07 10:50:28.900  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:28.905   927  3545 D WifiService: setWifiEnabled: false pid=5639, uid=10077
10-07 10:50:28.905   927  3545 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 10:50:30.434   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:31.435   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:32.436   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:33.437   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:33.915  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:33.919   927  3364 D WifiService: setWifiEnabled: true pid=5639, uid=10077
,10-07 10:50:33.919   927  3364 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 10:50:33.928   507   921 D SoftapController: Softap fwReload - Ok
,10-07 10:50:33.933   507   921 D CommandListener: Setting iface cfg
10-07 10:50:33.933   507   921 D CommandListener: Trying to bring down wlan0
,10-07 10:50:33.935   507   921 D CommandListener: Clearing all IP addresses on wlan0
,10-07 10:50:33.939   927  2954 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-07 10:50:34.438   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:50:34.614   927  2954 D wifi    : set interface wlan0 flags (UP)
,10-07 10:50:34.614   927  2954 I WifiHAL : Initializing wifi
10-07 10:50:34.614   927  2954 I WifiHAL : Creating socket
,10-07 10:50:34.620   927  2954 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-07 10:50:34.620   927  2954 D wifi    : Did set static halHandle = 0x7f89f8de00
10-07 10:50:34.621   927  2954 D wifi    : halHandle = 0x7f89f8de00, mVM = 0x7fa660d140, mCls = 0x2015be
10-07 10:50:34.621   927  2954 D wifi    : array field set
10-07 10:50:34.621   927  2954 I WifiNative-HAL: interface[0] = wlan0
,10-07 10:50:34.623   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-07 10:50:34.624   927  5958 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547775634944
10-07 10:50:34.625   927  5958 D wifi    : waitForHalEvents called, vm = 0x7fa660d140, obj = 0x2015be, env = 0x7f8bd366c0
,10-07 10:50:34.672  5959  5959 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-07 10:50:34.694  5959  5959 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 10:50:34.703  5959  5959 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 10:50:34.703  5959  5959 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-07 10:50:34.726   927  2954 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-07 10:50:34.742   927  2954 D WifiConfigStore: Loading config and enabling all networks 
,10-07 10:50:34.743  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:34.743  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:34.743  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:34.743  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:34.743  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:34.743  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:34.743  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:34.743  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 10:50:34.745  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 10:50:34.749  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:34.749  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:34.749  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:34.749  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:34.749  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:34.749  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 10:50:34.749  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 10:50:34.749  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 10:50:34.750  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 10:50:34.752  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:34.753   927  2954 D WifiConfigStore: loaded 0 passpoint configs
,10-07 10:50:34.753   927  2954 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-07 10:50:34.753  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:34.754   927  2954 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-07 10:50:34.755   927  2954 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-07 10:50:34.757   927  2954 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-07 10:50:34.757   927  2954 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-07 10:50:34.757   927  2954 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-07 10:50:34.757   927  2954 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-07 10:50:34.762   927  2954 D WifiNative-HAL: Setting external_sim to 1
10-07 10:50:34.763   927  2954 D wifi    : setting dfs flag to true, 0x7f8c2ff660
10-07 10:50:34.764   927  2954 D WifiStateMachine: Setting OUI to DA-A1-19
10-07 10:50:34.764   927  2954 D wifi    : setting scan oui 0x7f8c2ff660
10-07 10:50:34.764   927  2954 D WifiHAL : Sending mac address OUI
10-07 10:50:34.765  4894  4894 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-07 10:50:34.769   927  2954 E native  : do suspend false
,10-07 10:50:34.779   927  2954 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-07 10:50:34.779   927   927 D RttService: SCAN_AVAILABLE : 3
10-07 10:50:34.779   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-07 10:50:34.779   927  3024 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-07 10:50:34.780   507   921 D CommandListener: Setting iface cfg
,10-07 10:50:34.784   927  2947 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-07 10:50:34.784   927  2947 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-07 10:50:34.794   927  2947 D WifiNative-HAL: p2pGetDeviceAddress
,10-07 10:50:34.800   927  2947 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-07 10:50:34.800   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303819 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-07 10:50:35.441   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-07 10:50:37.975  5959  5959 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:37.980  5959  5959 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:37.985  5959  5959 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:37.989  5959  5959 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:37.994  5959  5959 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 10:50:38.097   927  2954 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-07 10:50:38.099   927  2954 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-07 10:50:38.099   927  2954 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 10:50:38.110   927  2954 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-07 10:50:38.144   927  2954 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-07 10:50:38.146  5959  5959 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-07 10:50:38.568  5959  5959 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-07 10:50:38.609  5959  5959 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-07 10:50:38.611  5959  5959 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-07 10:50:38.624   927  2954 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 10:50:38.624   927  2954 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-07 10:50:38.624   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-07 10:50:38.640   927  2954 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 10:50:38.655   507   921 D CommandListener: Setting iface cfg
,10-07 10:50:38.660   927  2954 D WifiStateMachine: Start Dhcp Watchdog 3
,10-07 10:50:38.672   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 10:50:38.672   927  2954 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-07 10:50:38.672   927  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-07 10:50:38.676   927  5964 D DhcpClient: Receive thread started
,10-07 10:50:38.756   927  2954 E native  : do suspend false
,10-07 10:50:38.766   927  5963 D DhcpClient: Broadcasting DHCPDISCOVER
,10-07 10:50:38.779   927  5964 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-07 10:50:38.779   927  5963 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-07 10:50:38.781   927  5963 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-07 10:50:38.800   927  5964 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-07 10:50:38.801   927  5963 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-07 10:50:38.803   507   921 D CommandListener: Setting iface cfg
,10-07 10:50:38.807   927  2954 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-07 10:50:38.812   927  5963 D DhcpClient: Scheduling renewal in 86399s
,10-07 10:50:38.823   927  2954 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-07 10:50:38.824   927  2954 D WifiConfigStore: No blacklist allowed without epno enabled
10-07 10:50:38.825   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-07 10:50:38.828   927  2973 D ConnectivityService: Adding iface wlan0 to network 102
10-07 10:50:38.834   927  2954 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-07 10:50:38.882   927  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-07 10:50:38.882   927  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-07 10:50:38.885   927  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-07 10:50:38.887   927  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-07 10:50:38.889   927  2973 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-07 10:50:38.896   927  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 10:50:38.900   927  2973 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-07 10:50:38.900   927  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-07 10:50:38.901   927  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-07 10:50:38.901   927  2973 D ConnectivityService:    accepting network in place of null
10-07 10:50:38.901   927  2954 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-07 10:50:38.901   927  2954 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-07 10:50:38.901   927  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 10:50:38.913   927  5962 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307932, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-07 10:50:38.927   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 10:50:38.932  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:38.932  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:38.932  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:38.932  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:38.932  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:38.932  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:38.932  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:38.932  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:50:38.934  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:38.934  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:38.934  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42757e8 removed from the list
10-07 10:50:38.934  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:50:38.934  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:38.934  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:50:38.938  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-07 10:50:38.939  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-07 10:50:38.941  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@76cc6a Bundle[{}]
,10-07 10:50:38.941  5639  5685 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-07 10:50:38.941  5639  5685 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-07 10:50:38.942  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-07 10:50:38.943  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-07 10:50:38.943  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-07 10:50:38.944  5639  5685 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-07 10:50:38.950  5639  5685 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
10-07 10:50:38.950  5639  5685 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-07 10:50:38.950  5639  5685 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,10-07 10:50:38.951   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 10:50:38.953  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:38.953  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f94e01 added. We now have 3 listener(s)
,10-07 10:50:38.954  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:38.954  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:38.954  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:38.954  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:38.955  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b0b4a6 added. We now have 4 listener(s)
,10-07 10:50:38.955  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:38.955   927  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-07 10:50:38.955  3686  3868 W QCNEJ   : |CORE| network available: 102
10-07 10:50:38.955   927  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-07 10:50:38.955  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-07 10:50:38.956   927  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-07 10:50:38.959   927   944 D Tethering: MasterInitialState.processMessage what=3
10-07 10:50:38.959  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:50:38.963  3686  3868 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-07 10:50:38.965  3686  3868 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-07 10:50:38.965  3686  3868 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-07 10:50:38.966  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:38.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:38.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:38.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:38.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:38.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:38.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:38.966  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:50:38.969  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:50:38.972  4947  4971 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-07 10:50:38.972  4947  4971 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 10:50:38.973  4947  4971 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-07 10:50:38.973  4947  4971 E SarControlService: no key has been found,reset the power
10-07 10:50:38.973  4947  4982 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 10:50:38.973  4947  4982 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 10:50:38.973  4947  4982 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 10:50:38.973  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 10:50:38.973  4972  4972 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-07 10:50:38.974  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 10:50:38.974  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:38.974  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:38.974  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:38.974  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:38.974  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:38.974  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:38.974  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 10:50:38.974  4947  4982 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 10:50:38.974  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:50:38.974  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:38.974  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:38.974  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:38.974  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:38.974  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:38.974  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:38.974  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:50:38.974  4947  4982 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 10:50:38.974  4947  4982 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 10:50:38.975  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 10:50:38.975  4972  4972 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 10:50:38.975  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:50:38.977  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:38.978  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 10:50:38.978  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:38.978  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e0a94 added. We now have 4 listener(s)
10-07 10:50:38.978   927  5961 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-07 10:50:38.979  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:38.979  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:38.979  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:38.979  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:38.980  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cabc93d added. We now have 5 listener(s)
10-07 10:50:38.980  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:38.980  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:50:38.980  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:50:38.980  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:38.980  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:50:38.980  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 10:50:38.980  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:38.980  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:50:38.980  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:38.980  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:38.980  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f94e01 removed from the list
10-07 10:50:38.980  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:38.980  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b0b4a6 removed from the list
,10-07 10:50:38.981  4972  4986 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f362e86 HexData = [00000000f003000000000000ffffffff]
,10-07 10:50:38.981  4972  4986 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 10:50:38.981  4972  4986 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-07 10:50:38.982  3917  3917 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-07 10:50:38.982  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:38.982  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:50:38.983  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:38.983  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:38.983  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:38.983  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 10:50:38.984  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:38.984  3832  3832 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-07 10:50:38.984  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:38.984  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 10:50:38.984  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b0b4a6 not in the list
,10-07 10:50:38.984  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:38.985  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:38.985  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:38.985  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 10:50:38.985  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:38.986  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cabc93d removed from the list
10-07 10:50:38.986  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:38.986  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:38.986  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:38.986  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:38.986  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:38.986  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e0a94 removed from the list
10-07 10:50:38.987  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:38.987  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea37532 added. We now have 3 listener(s)
10-07 10:50:38.987  3832  3832 D SystemUpdateService: onCreate
,10-07 10:50:38.988  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:38.988  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:38.988  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:38.988  4947  4957 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 10:50:38.988  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:38.988  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffa5283 added. We now have 4 listener(s)
10-07 10:50:38.988  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:38.988  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 10:50:38.990  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:50:38.992  3832  3832 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-07 10:50:38.993  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:50:38.993  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:38.993  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:38.993  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:38.993  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:38.993  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:38.993  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:38.993  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:50:38.995  4972  4986 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f362e86 HexData = [00000000f103000000000000ffffffff]
10-07 10:50:38.995  4972  4986 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 10:50:38.995  4972  4986 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-07 10:50:38.995  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:38.995  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 10:50:38.995  4972  4972 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 10:50:38.995  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:38.996  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410bc39 added. We now have 4 listener(s)
10-07 10:50:38.996  4947  4958 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-07 10:50:38.997  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:38.997  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:38.997  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:38.997  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 10:50:38.997  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18fb27e added. We now have 5 listener(s)
10-07 10:50:38.997  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:38.998  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:50:38.998  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 10:50:38.998  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 10:50:38.998  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:50:38.998  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 10:50:38.999  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:39.002  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:39.004  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 10:50:39.004  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-07 10:50:39.006  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 10:50:39.007  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 10:50:39.007  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 10:50:39.009  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-07 10:50:39.009  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 10:50:39.009  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 10:50:39.010  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 10:50:39.010  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-07 10:50:39.010  3832  3832 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
10-07 10:50:39.010  5639  5685 D BluetoothAdapter: STATE_ON
,10-07 10:50:39.012  5904  5915 D BtGatt.GattService: registerClient() - UUID=2a27a44d-4970-44d0-951f-3ed8ce8b2f9f
,10-07 10:50:39.014  5904  5920 D BtGatt.GattService: onClientRegistered() - UUID=2a27a44d-4970-44d0-951f-3ed8ce8b2f9f, clientIf=5
,10-07 10:50:39.014  5639  5737 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 10:50:39.015  5904  5914 D BtGatt.GattService: start scan with filters
,10-07 10:50:39.018  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 10:50:39.018  5904  5923 D BtGatt.ScanManager: handling starting scan
10-07 10:50:39.018  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 10:50:39.018  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:50:39.018  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 10:50:39.018  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 10:50:39.018  3832  5413 I iu.UploadsManager: num queued entries: 0
10-07 10:50:39.018  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 10:50:39.018  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 10:50:39.019  3832  5413 I iu.UploadsManager: num updated entries: 0
10-07 10:50:39.020  3832  5413 I iu.SyncManager: NEXT; no task
,10-07 10:50:39.020  5904  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ab0e43f
,10-07 10:50:39.021  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:50:39.021  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-07 10:50:39.021  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-07 10:50:39.023  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-07 10:50:39.025  3832  3832 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 10:50:39.026  5639  5685 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-07 10:50:39.026  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 10:50:39.026  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 10:50:39.026  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.026  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 10:50:39.026  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:39.026  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 10:50:39.026  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 10:50:39.026  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 10:50:39.026  5904  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 10:50:39.026  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 10:50:39.027  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.027  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 10:50:39.027  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 10:50:39.027  5904  5923 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 10:50:39.027  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:50:39.028   927  5961 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 07 Oct 2016 14:50:39 GMT], X-Android-Received-Millis=[1475851839027], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475851839001]}
,10-07 10:50:39.028  5904  5915 D BtGatt.GattService: stopScan() - queue size =1
10-07 10:50:39.028   927  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-07 10:50:39.029  3832  3832 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-07 10:50:39.029   927  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-07 10:50:39.029   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-07 10:50:39.029  5904  5914 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 10:50:39.029  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 10:50:39.030  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 10:50:39.030  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 10:50:39.030  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:50:39.030   927  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-07 10:50:39.030  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 10:50:39.030  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 10:50:39.030  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 10:50:39.030  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 10:50:39.030  5769  5769 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-07 10:50:39.031  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 10:50:39.032  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 10:50:39.032  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 10:50:39.032  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 10:50:39.032  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 10:50:39.032  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:50:39.034  5904  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 10:50:39.034  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.034  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-07 10:50:39.034  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:50:39.034  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 10:50:39.035  5904  5923 D BtGatt.ScanManager: Starting BLE batch scan
10-07 10:50:39.035  5904  5923 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 10:50:39.038  5769  5769 D SprintDMHelper: simOperator: 
10-07 10:50:39.038  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:50:39.038  5769  5769 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-07 10:50:39.038  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:50:39.038  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:50:39.038  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:39.038  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.038  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:50:39.038  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:39.038  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:39.039  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea37532 removed from the list
10-07 10:50:39.039  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 10:50:39.039  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffa5283 removed from the list
,10-07 10:50:39.039  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:50:39.039  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.043  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:50:39.044  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.045  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:39.045  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:39.045  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.045  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffa5283 not in the list
10-07 10:50:39.045  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:50:39.045  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.046  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:39.046  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:39.046  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.046  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18fb27e removed from the list
10-07 10:50:39.046  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:39.046  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.046  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.046  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:39.046  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:39.047  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@410bc39 removed from the list
,10-07 10:50:39.047  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:39.047  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d70788a added. We now have 3 listener(s)
10-07 10:50:39.048  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:39.048  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:39.048  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:39.049  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:39.049  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2598efb added. We now have 4 listener(s)
10-07 10:50:39.049  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:39.049  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 10:50:39.050  5904  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 10:50:39.050  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.051  3832  5974 I SystemUpdateService: active receiver: enabled
10-07 10:50:39.052  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:50:39.057  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:50:39.057  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:39.057  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:39.057  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:39.057  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:39.057  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:39.057  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:39.057  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:50:39.059  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:39.059  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 10:50:39.060  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:39.060  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b70b971 added. We now have 4 listener(s)
10-07 10:50:39.061  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:39.061  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:39.061  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:39.061  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:39.061  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e59356 added. We now have 5 listener(s)
10-07 10:50:39.061  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:39.061  5904  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 10:50:39.061  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-07 10:50:39.061  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.062  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:50:39.062  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 10:50:39.062  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 10:50:39.062  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:50:39.062  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 10:50:39.063  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:39.064  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 10:50:39.065  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 10:50:39.066  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:39.068  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 10:50:39.068  5904  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 10:50:39.068  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.068  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 10:50:39.068  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-07 10:50:39.068  5904  5923 D BtGatt.ScanManager: stopping BLe Batch
,10-07 10:50:39.073  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 10:50:39.073  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 10:50:39.073  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 10:50:39.073  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 10:50:39.073  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 10:50:39.074  5904  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 10:50:39.074  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.075  5904  5923 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-07 10:50:39.075  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:50:39.077  5904  5941 D BtGatt.GattService: registerClient() - UUID=659a4ea2-611f-4191-8d05-2c6376aac130
10-07 10:50:39.078  5904  5920 D BtGatt.GattService: onClientRegistered() - UUID=659a4ea2-611f-4191-8d05-2c6376aac130, clientIf=5
10-07 10:50:39.078  5639  5649 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 10:50:39.078  5904  5914 D BtGatt.GattService: start scan with filters
,10-07 10:50:39.081  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-07 10:50:39.081  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 10:50:39.081  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:50:39.081  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 10:50:39.081  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 10:50:39.081  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 10:50:39.081  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-07 10:50:39.082  5904  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 10:50:39.082  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.083  5904  5923 D BtGatt.ScanManager: handling starting scan
10-07 10:50:39.083  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:50:39.084  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 10:50:39.084  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:50:39.085  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 10:50:39.088  5904  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 10:50:39.088  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.088  5904  5923 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 10:50:39.089  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-07 10:50:39.089  5639  5685 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-07 10:50:39.089  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:50:39.089  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:50:39.089  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:50:39.089  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:39.089  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.089  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 10:50:39.089  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 10:50:39.089  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:39.089  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d70788a removed from the list
10-07 10:50:39.089  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.090  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2598efb removed from the list
10-07 10:50:39.090  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:50:39.090  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:50:39.090  3832  5974 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-07 10:50:39.092  5904  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 10:50:39.092  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.092  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.092  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-07 10:50:39.092  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:50:39.092  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:50:39.092  5904  5923 D BtGatt.ScanManager: Starting BLE batch scan
10-07 10:50:39.092  5904  5923 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 10:50:39.093  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:39.093  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:39.093  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.093  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2598efb not in the list
10-07 10:50:39.093  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 10:50:39.093  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 10:50:39.093  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 10:50:39.093  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 10:50:39.093  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 10:50:39.094  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:50:39.095  5904  5914 D BtGatt.GattService: stopScan() - queue size =1
,10-07 10:50:39.095  5904  5915 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-07 10:50:39.095  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 10:50:39.095  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 10:50:39.096  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 10:50:39.096  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:50:39.096  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 10:50:39.096  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 10:50:39.096  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 10:50:39.096  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 10:50:39.097  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:50:39.097  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 10:50:39.097  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 10:50:39.097  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 10:50:39.097  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 10:50:39.097  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.099  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:39.099  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:39.099  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.099  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:50:39.099  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e59356 removed from the list
10-07 10:50:39.099  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:39.099  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:50:39.099  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.099  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:50:39.099  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.099  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:39.099  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:39.099  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b70b971 removed from the list
10-07 10:50:39.100  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:39.100  5639  5685 V org.thaliproject.p2,p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bf8ee2 added. We now have 3 listener(s)
10-07 10:50:39.100  5904  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 10:50:39.100  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.101  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:39.101  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:39.102  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:39.102  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:39.102  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e4e273 added. We now have 4 listener(s)
10-07 10:50:39.102  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:39.102  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 10:50:39.102  3832  5974 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-07 10:50:39.103  3832  5974 I SystemUpdateService: now status is 0 (complete)
10-07 10:50:39.103  3832  5974 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 10:50:39.103  3832  5974 I SystemUpdateService: file has been verified
10-07 10:50:39.103  3832  5974 I SystemUpdateService: OTA package size = 21989297
10-07 10:50:39.105  5904  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 10:50:39.105  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.106  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:50:39.110  3832  5974 I SystemUpdateService: showing system update notification
,10-07 10:50:39.110  5904  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 10:50:39.111  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.111  5904  5923 D BtGatt.ScanManager: stopping BLe Batch
10-07 10:50:39.111  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:50:39.111  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:39.111  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:39.111  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:39.111  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:39.111  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:39.111  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:39.111  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:50:39.115  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:50:39.115  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 10:50:39.115  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:39.115  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbc25a9 added. We now have 4 listener(s)
10-07 10:50:39.116  5904  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 10:50:39.116  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.116  5904  5923 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-07 10:50:39.116  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:39.116  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:39.116  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:39.116  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:39.116  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64bb72e added. We now have 5 listener(s)
10-07 10:50:39.116  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:39.116  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:50:39.117  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-07 10:50:39.117  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 10:50:39.117  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 10:50:39.117  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:39.117  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 10:50:39.119  5639  5685 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 10:50:39.119  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 10:50:39.120  3832  3832 D SystemUpdateService: onDestroy
10-07 10:50:39.121  5904  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 10:50:39.121  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.122  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 10:50:39.123  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 10:50:39.124  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 10:50:39.124  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 10:50:39.128  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-07 10:50:39.128  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 10:50:39.128  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 10:50:39.128  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 10:50:39.128  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-07 10:50:39.129  5639  5685 D BluetoothAdapter: STATE_ON
,10-07 10:50:39.131  5904  5915 D BtGatt.GattService: registerClient() - UUID=54621861-bf5d-42a0-89f7-7c3400c21c38
,10-07 10:50:39.132  5904  5920 D BtGatt.GattService: onClientRegistered() - UUID=54621861-bf5d-42a0-89f7-7c3400c21c38, clientIf=5
,10-07 10:50:39.132  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 10:50:39.132  5904  5933 D BtGatt.GattService: start scan with filters
,10-07 10:50:39.134  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 10:50:39.134  5904  5923 D BtGatt.ScanManager: handling starting scan
10-07 10:50:39.134  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 10:50:39.134  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:50:39.134  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 10:50:39.134  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 10:50:39.135  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 10:50:39.135  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-07 10:50:39.136  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:50:39.136  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 10:50:39.136  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 10:50:39.138  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 10:50:39.139  5904  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 10:50:39.139  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.139  5904  5923 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 10:50:39.141  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:50:39.141  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:50:39.141  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:50:39.142  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:39.142  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.142  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 10:50:39.142  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 10:50:39.142  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:39.142  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bf8ee2 removed from the list
,10-07 10:50:39.142  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 10:50:39.142  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e4e273 removed from the list
10-07 10:50:39.142  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:50:39.142  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-07 10:50:39.143  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.143  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-07 10:50:39.143  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.143  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:50:39.144  5904  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 10:50:39.144  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:39.144  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.144  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:39.144  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.144  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e4e273 not in the list
10-07 10:50:39.144  5904  5923 D BtGatt.ScanManager: Starting BLE batch scan
10-07 10:50:39.144  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 10:50:39.144  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-07 10:50:39.144  5904  5923 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 10:50:39.144  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 10:50:39.145  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 10:50:39.145  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 10:50:39.145  5639  5685 D BluetoothAdapter: STATE_ON
10-07 10:50:39.146  5904  5941 D BtGatt.GattService: stopScan() - queue size =1
10-07 10:50:39.146  5904  5933 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 10:50:39.147  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 10:50:39.147  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 10:50:39.147  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 10:50:39.147  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 10:50:39.147  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 10:50:39.147  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-07 10:50:39.147  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 10:50:39.147  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 10:50:39.148  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:50:39.148  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 10:50:39.148  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 10:50:39.148  5639  5685 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 10:50:39.148  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 10:50:39.149  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.150  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:39.150  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:39.150  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.150  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:50:39.150  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64bb72e removed from the list
10-07 10:50:39.150  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:39.150  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 10:50:39.150  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.150  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 10:50:39.150  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.150  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:39.150  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:39.150  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbc25a9 removed from the list
10-07 10:50:39.151  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 10:50:39.151  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60183a added. We now have 3 listener(s)
10-07 10:50:39.152  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:39.153  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:39.153  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 10:50:39.153  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:39.153  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7282ceb added. We now have 4 listener(s)
10-07 10:50:39.153  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:39.154  5904  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 10:50:39.154  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 10:50:39.154  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.156  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 10:50:39.160  5904  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-07 10:50:39.160  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.162  5639  5685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 10:50:39.162  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 10:50:39.162  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 10:50:39.162  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 10:50:39.162  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 10:50:39.162  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 10:50:39.162  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 10:50:39.162  5639  5685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 10:50:39.164  5639  5685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 10:50:39.164  5639  5685 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 10:50:39.164  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 10:50:39.164  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@111e0e1 added. We now have 4 listener(s)
10-07 10:50:39.165  5904  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 10:50:39.165  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.165  5904  5923 D BtGatt.ScanManager: stopping BLe Batch
10-07 10:50:39.165  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 10:50:39.166  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 10:50:39.166  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 10:50:39.166  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 10:50:39.166  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6277e06 added. We now have 5 listener(s)
10-07 10:50:39.166  5639  5685 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 10:50:39.166  5639  5685 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 10:50:39.166  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:50:39.166  5639  5685 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 10:50:39.166  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:39.166  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:39.166  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 10:50:39.166  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 10:50:39.166  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:39.166  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:39.166  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60183a removed from the list
10-07 10:50:39.166  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.166  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7282ceb removed from the list
10-07 10:50:39.168  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 10:50:39.168  5639  5685 D io.jxcore.node.ConnectivityMonitor: stop
10-07 10:50:39.168  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 10:50:39.169  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.169  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.170  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:39.170  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:39.170  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.170  5904  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 10:50:39.170  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 10:50:39.170  5639  5685 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7282ceb not in the list
10-07 10:50:39.170  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.170  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.170  5904  5923 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 10:50:39.172  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 10:50:39.172  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 10:50:39.173  5639  5685 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 10:50:39.173  5639  5685 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6277e06 removed from the list
,10-07 10:50:39.173  5639  5685 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 10:50:39.173  5639  5685 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 10:50:39.173  5639  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 10:50:39.173  5639  5685 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 10:50:39.173  5639  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 10:50:39.173  5639  5685 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@111e0e1 removed from the list
10-07 10:50:39.174  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,10-07 10:50:39.174  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-07 10:50:39.174  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-07 10:50:39.174  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:50:39.174  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-07 10:50:39.174  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 10:50:39.174  5904  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 10:50:39.174  5904  5920 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 10:50:39.210  4894  5980 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-07 10:50:39.535  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 10:50:39.599  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 10:50:39.651  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 10:50:41.325  5639  5986 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-07 10:50:41.325  5639  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 10:50:41.698   927  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 10:50:42.134  5639  5986 W !!      : call onHalfStreamCopied
,10-07 10:50:42.134  5639  5986 I testCopyDataAndClose: closing input stream
,10-07 10:50:42.913  5639  5986 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-07 10:50:42.913  5639  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-07 10:50:42.914  5639  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-07 10:50:46.681  5639  5987 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-07 10:50:46.681  5639  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 10:50:46.906   927  2973 D ConnectivityService: handlePromptUnvalidated 102
,10-07 10:50:48.681  5639  5685 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-07 10:50:48.681  5639  5685 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 10:50:48.682  5639  5685 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-07 10:50:48.813  5639  5988 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 10:50:48.813  5639  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 10:50:48.878  5639  5987 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-07 10:50:48.878  5639  5987 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-07 10:50:48.878  5639  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,10-07 10:50:49.795   927  2954 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-07 10:50:50.436  5639  5988 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 10:50:50.436  5639  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 10:50:50.437  5639  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-07 10:50:54.171  5639  5989 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-07 10:50:54.171  5639  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 10:50:54.171  5639  5989 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-07 10:50:54.171  5639  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 10:50:54.172  5639  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 10:50:54.172  5639  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 10:50:54.172  5639  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-07 10:50:54.172  5639  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-07 10:50:54.172  5639  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-07 10:50:54.172  5639  5989 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-07 10:50:54.172  5639  5989 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-07 10:50:54.173  5639  5989 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-07 10:50:54.173  5639  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-07 10:50:54.184  5639  5685 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-07 10:50:54.187  5639  5990 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 10:50:54.187  5639  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 10:50:54.188  5639  5990 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
10-07 10:50:54.188  5639  5990 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 10:50:54.188  5639  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-07 10:50:54.188  5639  5990 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-07 10:50:54.188  5639  5990 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 10:50:54.188  5639  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-07 10:50:54.194  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-07 10:50:54.194  5639  5685 I jxcore-log: 
,10-07 10:50:54.195  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-07 10:50:54.195  5639  5685 I jxcore-log: 
10-07 10:50:54.195  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-07 10:50:54.195  5639  5685 I jxcore-log: 
10-07 10:50:54.195  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-07 10:50:54.195  5639  5685 I jxcore-log: 
10-07 10:50:54.196  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG UnitTest_app: 'Total duration:  90751'
10-07 10:50:54.196  5639  5685 I jxcore-log: 
,10-07 10:50:54.198  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-07 10:50:54.198  5639  5685 I jxcore-log: 
,10-07 10:50:54.202  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.202  5639  5685 I jxcore-log: 
,10-07 10:50:54.206  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.206  5639  5685 I jxcore-log: 
10-07 10:50:54.207  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.207  5639  5685 I jxcore-log: 
10-07 10:50:54.207  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.207  5639  5685 I jxcore-log: 
10-07 10:50:54.207  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-07 10:50:54.207  5639  5685 I jxcore-log: 
,10-07 10:50:54.234  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 10:50:54.234  5639  5685 I jxcore-log: 
,10-07 10:50:54.234  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.234  5639  5685 I jxcore-log: 
10-07 10:50:54.234  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.234  5639  5685 I jxcore-log: 
10-07 10:50:54.235  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-07 10:50:54.235  5639  5685 I jxcore-log: 
10-07 10:50:54.235  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 10:50:54.235  5639  5685 I jxcore-log: 
10-07 10:50:54.235  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 10:50:54.235  5639  5685 I jxcore-log: 
,10-07 10:50:54.235  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.235  5639  5685 I jxcore-log: 
10-07 10:50:54.236  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.236  5639  5685 I jxcore-log: 
10-07 10:50:54.236  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 10:50:54.236  5639  5685 I jxcore-log: 
10-07 10:50:54.236  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.236  5639  5685 I jxcore-log: 
10-07 10:50:54.236  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 10:50:54.236  5639  5685 I jxcore-log: 
,10-07 10:50:54.237  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 10:50:54.237  5639  5685 I jxcore-log: 
,10-07 10:50:54.237  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.237  5639  5685 I jxcore-log: 
10-07 10:50:54.237  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.237  5639  5685 I jxcore-log: 
10-07 10:50:54.237  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.237  5639  5685 I jxcore-log: 
10-07 10:50:54.238  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 10:50:54.238  5639  5685 I jxcore-log: 
10-07 10:50:54.238  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 10:50:54.238  5639  5685 I jxcore-log: 
,10-07 10:50:54.238  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 10:50:54.238  5639  5685 I jxcore-log: 
10-07 10:50:54.240  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.240  5639  5685 I jxcore-log: 
10-07 10:50:54.240  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.240  5639  5685 I jxcore-log: 
10-07 10:50:54.240  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.240  5639  5685 I jxcore-log: 
,10-07 10:50:54.240  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.240  5639  5685 I jxcore-log: 
10-07 10:50:54.241  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.241  5639  5685 I jxcore-log: 
,10-07 10:50:54.241  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.241  5639  5685 I jxcore-log: 
10-07 10:50:54.241  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.241  5639  5685 I jxcore-log: 
10-07 10:50:54.241  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.241  5639  5685 I jxcore-log: 
10-07 10:50:54.242  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.242  5639  5685 I jxcore-log: 
10-07 10:50:54.242  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.242  5639  5685 I jxcore-log: 
,10-07 10:50:54.242  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.242  5639  5685 I jxcore-log: 
10-07 10:50:54.242  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.242  5639  5685 I jxcore-log: 
10-07 10:50:54.242  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.242  5639  5685 I jxcore-log: 
10-07 10:50:54.243  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.243  5639  5685 I jxcore-log: 
10-07 10:50:54.243  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 10:50:54.243  5639  5685 I jxcore-log: 
10-07 10:50:54.243  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 10:50:54.243  5639  5685 I jxcore-log: 
10-07 10:50:54.243  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 10:50:54.243  5639  5685 I jxcore-log: 
10-07 10:50:54.244  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.244  5639  5685 I jxcore-log: 
10-07 10:50:54.244  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.244  5639  5685 I jxcore-log: 
,10-07 10:50:54.244  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.244  5639  5685 I jxcore-log: 
10-07 10:50:54.244  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.244  5639  5685 I jxcore-log: 
10-07 10:50:54.245  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.245  5639  5685 I jxcore-log: 
,10-07 10:50:54.245  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 10:50:54.245  5639  5685 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-07 10:50:54.245  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.245  5639  5685 I jxcore-log: 
,10-07 10:50:54.246  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.246  5639  5685 I jxcore-log: 
10-07 10:50:54.246  5639  5685 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 10:50:54.246  5639  5685 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-07 10:50:54.246  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 10:50:54.246  5639  5685 I jxcore-log: 
,10-07 10:50:54.247  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 10:50:54.247  5639  5685 I jxcore-log: 
10-07 10:50:54.247  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 10:50:54.247  5639  5685 I jxcore-log: 
10-07 10:50:54.247  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 10:50:54.247  5639  5685 I jxcore-log: 
10-07 10:50:54.248  5639  5639 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-07 10:50:54.254  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-07 10:50:54.254  5639  5685 I jxcore-log: 
10-07 10:50:54.255  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - WARN testUtils: 'myNameCallback not set!'
10-07 10:50:54.255  5639  5685 I jxcore-log: 
,10-07 10:50:54.256  5639  5685 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-07 10:50:54.257  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-07 10:50:54.257  5639  5685 I jxcore-log: 
,10-07 10:50:54.737  5639  5685 I jxcore-log: 2016-10-07 14:50:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-07 10:50:54.737  5639  5685 I jxcore-log: 
,10-07 10:50:55.129  5639  5685 I jxcore-log: 2016-10-07 14:50:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-07 10:50:55.129  5639  5685 I jxcore-log: 
,10-07 10:50:55.144  5639  5685 I jxcore-log: 2016-10-07 14:50:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-07 10:50:55.144  5639  5685 I jxcore-log: 
,10-07 10:50:56.290  5639  5685 I jxcore-log: 2016-10-07 14:50:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-07 10:50:56.290  5639  5685 I jxcore-log: 
,10-07 10:50:56.458  5639  5685 I jxcore-log: 2016-10-07 14:50:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-07 10:50:56.458  5639  5685 I jxcore-log: 
,10-07 10:50:56.463  5639  5685 I jxcore-log: 2016-10-07 14:50:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-07 10:50:56.463  5639  5685 I jxcore-log: 
,10-07 10:50:56.468  5639  5685 I jxcore-log: 2016-10-07 14:50:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-07 10:50:56.468  5639  5685 I jxcore-log: 
,10-07 10:50:57.025  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-07 10:50:57.025  5639  5685 I jxcore-log: 
,10-07 10:50:57.078  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-07 10:50:57.078  5639  5685 I jxcore-log: 
,10-07 10:50:57.091  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-07 10:50:57.091  5639  5685 I jxcore-log: 
,10-07 10:50:57.096  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-07 10:50:57.096  5639  5685 I jxcore-log: 
,10-07 10:50:57.524  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-07 10:50:57.524  5639  5685 I jxcore-log: 
,10-07 10:50:57.651  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-07 10:50:57.651  5639  5685 I jxcore-log: 
,10-07 10:50:57.880  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-07 10:50:57.880  5639  5685 I jxcore-log: 
,10-07 10:50:57.891  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-07 10:50:57.891  5639  5685 I jxcore-log: 
,10-07 10:50:57.895  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-07 10:50:57.895  5639  5685 I jxcore-log: 
,10-07 10:50:57.901  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-07 10:50:57.901  5639  5685 I jxcore-log: 
,10-07 10:50:57.907  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-07 10:50:57.907  5639  5685 I jxcore-log: 
,10-07 10:50:57.935  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-07 10:50:57.935  5639  5685 I jxcore-log: 
,10-07 10:50:57.970  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-07 10:50:57.970  5639  5685 I jxcore-log: 
,10-07 10:50:57.976  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-07 10:50:57.976  5639  5685 I jxcore-log: 
,10-07 10:50:57.982  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-07 10:50:57.982  5639  5685 I jxcore-log: 
,10-07 10:50:57.997  5639  5685 I jxcore-log: 2016-10-07 14:50:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-07 10:50:57.997  5639  5685 I jxcore-log: 
,10-07 10:50:58.002  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-07 10:50:58.002  5639  5685 I jxcore-log: 
,10-07 10:50:58.008  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-07 10:50:58.008  5639  5685 I jxcore-log: 
,10-07 10:50:58.013  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-07 10:50:58.013  5639  5685 I jxcore-log: 
,10-07 10:50:58.027  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-07 10:50:58.027  5639  5685 I jxcore-log: 
,10-07 10:50:58.048  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-07 10:50:58.048  5639  5685 I jxcore-log: 
,10-07 10:50:58.057  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-07 10:50:58.057  5639  5685 I jxcore-log: 
,10-07 10:50:58.068  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-07 10:50:58.068  5639  5685 I jxcore-log: 
,10-07 10:50:58.078  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-07 10:50:58.078  5639  5685 I jxcore-log: 
,10-07 10:50:58.090  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-07 10:50:58.090  5639  5685 I jxcore-log: 
,10-07 10:50:58.100  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-07 10:50:58.100  5639  5685 I jxcore-log: 
,10-07 10:50:58.105  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-07 10:50:58.105  5639  5685 I jxcore-log: 
,10-07 10:50:58.126  5639  5685 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-07 10:50:58.128  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - INFO testUtils: 'BLE multiple advertisement supported'
10-07 10:50:58.128  5639  5685 I jxcore-log: 
,10-07 10:50:58.167  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - DEBUG ServerClient: 'connecting to '85.14.110.168:3000''
10-07 10:50:58.167  5639  5685 I jxcore-log: 
,10-07 10:50:58.869  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - DEBUG ServerClient: 'connected to '85.14.110.168:3000''
10-07 10:50:58.869  5639  5685 I jxcore-log: 
,10-07 10:50:58.871  5639  5685 I jxcore-log: 2016-10-07 14:50:58 - DEBUG CoordinatedClient: 'connected to the test server'
10-07 10:50:58.871  5639  5685 I jxcore-log: 
,10-07 10:50:59.344  5639  5685 I jxcore-log: TAP version 13
10-07 10:50:59.344  5639  5685 I jxcore-log: 
,10-07 10:50:59.346  5639  5685 I jxcore-log: # setup
10-07 10:50:59.346  5639  5685 I jxcore-log: 
,10-07 10:50:59.347  5639  5685 I jxcore-log: 2016-10-07 14:50:59 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_calling createNativeListener directly rejects''
10-07 10:50:59.347  5639  5685 I jxcore-log: 
,10-07 10:51:00.204  5639  5685 I jxcore-log: 2016-10-07 14:51:00 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects_confirmed', data: '{"uuid":"c022fd79-7714-4510-8a80-9e6f73d63d4a"}''
10-07 10:51:00.204  5639  5685 I jxcore-log: 
,10-07 10:51:00.241  5639  5685 I jxcore-log: 2016-10-07 14:51:00 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects_finished', data: '{"success":true}''
10-07 10:51:00.241  5639  5685 I jxcore-log: 
,10-07 10:51:00.247  5639  5685 I jxcore-log: # calling createNativeListener directly rejects
10-07 10:51:00.247  5639  5685 I jxcore-log: 
,10-07 10:51:00.255  5639  5685 I jxcore-log: 2016-10-07 14:51:00 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_calling createNativeListener directly rejects''
10-07 10:51:00.255  5639  5685 I jxcore-log: 
,10-07 10:51:00.441   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-07 10:51:00.442   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-07 10:51:01.342  5639  5685 I jxcore-log: 2016-10-07 14:51:01 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_calling createNativeListener directly rejects_confirmed', data: '{"uuid":"87a9c2e9-9e78-47b6-80f4-995f4126a58e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:01.342  5639  5685 I jxcore-log: 
,10-07 10:51:01.353  5639  5685 I jxcore-log: 2016-10-07 14:51:01 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:01.353  5639  5685 I jxcore-log: 
,10-07 10:51:01.359  5639  5685 I jxcore-log: 2016-10-07 14:51:01 - DEBUG createNativeListener: 'listening 37651'
10-07 10:51:01.359  5639  5685 I jxcore-log: 
,10-07 10:51:01.367  5639  5685 I jxcore-log: ok 1 Should throw
10-07 10:51:01.367  5639  5685 I jxcore-log: 
,10-07 10:51:01.369  5639  5685 I jxcore-log: 2016-10-07 14:51:01 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_calling createNativeListener directly rejects_finished', data: '{"success":true}''
10-07 10:51:01.369  5639  5685 I jxcore-log: 
,10-07 10:51:01.375  5639  5685 I jxcore-log: # teardown
10-07 10:51:01.375  5639  5685 I jxcore-log: 
,10-07 10:51:01.376  5639  5685 I jxcore-log: 2016-10-07 14:51:01 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects''
10-07 10:51:01.376  5639  5685 I jxcore-log: 
,10-07 10:51:01.814  5639  5685 I jxcore-log: 2016-10-07 14:51:01 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects_confirmed', data: '{"uuid":"7f6ce294-5433-494b-b55f-67dc9b5cc6ca"}''
10-07 10:51:01.814  5639  5685 I jxcore-log: 
,10-07 10:51:01.827  5639  5685 I jxcore-log: server is closing
10-07 10:51:01.827  5639  5685 I jxcore-log: 
,10-07 10:51:01.829  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:01.829  5639  5685 I jxcore-log: 
10-07 10:51:01.830  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:01.830  5639  5685 I jxcore-log: 
,10-07 10:51:01.830  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:01.830  5639  5685 I jxcore-log: 
,10-07 10:51:01.836  5639  5685 I jxcore-log: server is closing
10-07 10:51:01.836  5639  5685 I jxcore-log: 
10-07 10:51:01.837  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:01.837  5639  5685 I jxcore-log: 
,10-07 10:51:01.837  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:01.837  5639  5685 I jxcore-log: 
10-07 10:51:01.837  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:01.837  5639  5685 I jxcore-log: 
,10-07 10:51:01.842  5639  5685 I jxcore-log: 2016-10-07 14:51:01 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects_finished', data: '{"success":true}''
10-07 10:51:01.842  5639  5685 I jxcore-log: 
,10-07 10:51:01.849  5639  5685 I jxcore-log: # setup
10-07 10:51:01.849  5639  5685 I jxcore-log: 
,10-07 10:51:01.850  5639  5685 I jxcore-log: 2016-10-07 14:51:01 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_emits incomingConnectionState''
10-07 10:51:01.850  5639  5685 I jxcore-log: 
,10-07 10:51:02.565  5639  5685 I jxcore-log: 2016-10-07 14:51:02 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_emits incomingConnectionState_confirmed', data: '{"uuid":"97acd2b2-0bd3-49ca-ac60-5e0479b3968b"}''
10-07 10:51:02.565  5639  5685 I jxcore-log: 
,10-07 10:51:02.577  5639  5685 I jxcore-log: 2016-10-07 14:51:02 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_emits incomingConnectionState_finished', data: '{"success":true}''
10-07 10:51:02.577  5639  5685 I jxcore-log: 
,10-07 10:51:02.585  5639  5685 I jxcore-log: # emits incomingConnectionState
10-07 10:51:02.585  5639  5685 I jxcore-log: 
,10-07 10:51:02.590  5639  5685 I jxcore-log: 2016-10-07 14:51:02 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_emits incomingConnectionState''
10-07 10:51:02.590  5639  5685 I jxcore-log: 
,10-07 10:51:03.073  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_emits incomingConnectionState_confirmed', data: '{"uuid":"072b6df4-0a43-46b9-993c-9c789e0c1792","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:03.073  5639  5685 I jxcore-log: 
,10-07 10:51:03.091  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:03.091  5639  5685 I jxcore-log: 
,10-07 10:51:03.096  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG createNativeListener: 'listening 49116'
10-07 10:51:03.096  5639  5685 I jxcore-log: 
,10-07 10:51:03.106  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:03.106  5639  5685 I jxcore-log: 
,10-07 10:51:03.110  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:03.110  5639  5685 I jxcore-log: 
,10-07 10:51:03.119  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG createNativeListener: 'new mux'
10-07 10:51:03.119  5639  5685 I jxcore-log: 
,10-07 10:51:03.125  5639  5685 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-07 10:51:03.125  5639  5685 I jxcore-log: 
,10-07 10:51:03.143  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:03.143  5639  5685 I jxcore-log: 
,10-07 10:51:03.144  5639  5685 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-07 10:51:03.144  5639  5685 I jxcore-log: 
,10-07 10:51:03.146  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_emits incomingConnectionState_finished', data: '{"success":true}''
10-07 10:51:03.146  5639  5685 I jxcore-log: 
,10-07 10:51:03.150  5639  5685 I jxcore-log: # teardown
10-07 10:51:03.150  5639  5685 I jxcore-log: 
,10-07 10:51:03.153  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_emits incomingConnectionState''
10-07 10:51:03.153  5639  5685 I jxcore-log: 
,10-07 10:51:03.891  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_emits incomingConnectionState_confirmed', data: '{"uuid":"0a3dd3c2-221a-46f1-a960-5058641f1fa5"}''
10-07 10:51:03.891  5639  5685 I jxcore-log: 
,10-07 10:51:03.897  5639  5685 I jxcore-log: server is closing
10-07 10:51:03.897  5639  5685 I jxcore-log: 
,10-07 10:51:03.898  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:03.898  5639  5685 I jxcore-log: 
10-07 10:51:03.899  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:03.899  5639  5685 I jxcore-log: 
10-07 10:51:03.899  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:03.899  5639  5685 I jxcore-log: 
,10-07 10:51:03.902  5639  5685 I jxcore-log: server is closing
10-07 10:51:03.902  5639  5685 I jxcore-log: 
,10-07 10:51:03.903  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:03.903  5639  5685 I jxcore-log: 
10-07 10:51:03.903  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:03.903  5639  5685 I jxcore-log: 
10-07 10:51:03.904  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:03.904  5639  5685 I jxcore-log: 
,10-07 10:51:03.907  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_emits incomingConnectionState_finished', data: '{"success":true}''
10-07 10:51:03.907  5639  5685 I jxcore-log: 
,10-07 10:51:03.913  5639  5685 I jxcore-log: # setup
10-07 10:51:03.913  5639  5685 I jxcore-log: 
,10-07 10:51:03.915  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_emits routerPortConnectionFailed''
10-07 10:51:03.915  5639  5685 I jxcore-log: 
,10-07 10:51:03.972  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed_confirmed', data: '{"uuid":"57be73bd-8fdf-45ed-ad14-4140dc879b5d"}''
10-07 10:51:03.972  5639  5685 I jxcore-log: 
,10-07 10:51:03.986  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed_finished', data: '{"success":true}''
10-07 10:51:03.986  5639  5685 I jxcore-log: 
,10-07 10:51:03.992  5639  5685 I jxcore-log: # emits routerPortConnectionFailed
10-07 10:51:03.992  5639  5685 I jxcore-log: 
,10-07 10:51:03.996  5639  5685 I jxcore-log: 2016-10-07 14:51:03 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_emits routerPortConnectionFailed''
10-07 10:51:03.996  5639  5685 I jxcore-log: 
,10-07 10:51:04.069  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_emits routerPortConnectionFailed_confirmed', data: '{"uuid":"642f3388-2c4e-4124-a695-b3ce2fb0c31e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:04.069  5639  5685 I jxcore-log: 
,10-07 10:51:04.075  5639  5685 I jxcore-log: server is closing
10-07 10:51:04.075  5639  5685 I jxcore-log: 
,10-07 10:51:04.075  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:04.075  5639  5685 I jxcore-log: 
10-07 10:51:04.075  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:04.075  5639  5685 I jxcore-log: 
10-07 10:51:04.075  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:04.075  5639  5685 I jxcore-log: 
10-07 10:51:04.078  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:04.078  5639  5685 I jxcore-log: 
,10-07 10:51:04.082  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'listening 44832'
10-07 10:51:04.082  5639  5685 I jxcore-log: 
,10-07 10:51:04.089  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:04.089  5639  5685 I jxcore-log: 
,10-07 10:51:04.090  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:04.090  5639  5685 I jxcore-log: 
,10-07 10:51:04.092  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new mux'
10-07 10:51:04.092  5639  5685 I jxcore-log: 
,10-07 10:51:04.115  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:04.115  5639  5685 I jxcore-log: 
,10-07 10:51:04.118  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:04.118  5639  5685 I jxcore-log: 
,10-07 10:51:04.122  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: ' $c@net.js:837:7
10-07 10:51:04.122  5639  5685 I jxcore-log: $09@net.js:829:13
10-07 10:51:04.122  5639  5685 I jxcore-log: '
10-07 10:51:04.122  5639  5685 I jxcore-log: 
,10-07 10:51:04.123  5639  5685 I jxcore-log: ok 4 tried to connect to right port
10-07 10:51:04.123  5639  5685 I jxcore-log: 
10-07 10:51:04.123  5639  5685 I jxcore-log: ok 5 failed due to refused connection
10-07 10:51:04.123  5639  5685 I jxcore-log: 
10-07 10:51:04.124  5639  5685 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-07 10:51:04.124  5639  5685 I jxcore-log: 
10-07 10:51:04.125  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_emits routerPortConnectionFailed_finished', data: '{"success":true}''
10-07 10:51:04.125  5639  5685 I jxcore-log: 
,10-07 10:51:04.127  5639  5685 I jxcore-log: # teardown
10-07 10:51:04.127  5639  5685 I jxcore-log: 
,10-07 10:51:04.127  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed''
10-07 10:51:04.127  5639  5685 I jxcore-log: 
,10-07 10:51:04.129  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:04.129  5639  5685 I jxcore-log: 
,10-07 10:51:04.176  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed_confirmed', data: '{"uuid":"df1cebed-4a09-4aa6-8858-c0827cb200e9"}''
10-07 10:51:04.176  5639  5685 I jxcore-log: 
,10-07 10:51:04.179  5639  5685 I jxcore-log: server is closing
10-07 10:51:04.179  5639  5685 I jxcore-log: 
,10-07 10:51:04.179  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:04.179  5639  5685 I jxcore-log: 
10-07 10:51:04.179  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:04.179  5639  5685 I jxcore-log: 
10-07 10:51:04.180  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:04.180  5639  5685 I jxcore-log: 
10-07 10:51:04.182  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'mux close'
10-07 10:51:04.182  5639  5685 I jxcore-log: 
,10-07 10:51:04.187  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed_finished', data: '{"success":true}''
10-07 10:51:04.187  5639  5685 I jxcore-log: 
,10-07 10:51:04.191  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:04.191  5639  5685 I jxcore-log: 
,10-07 10:51:04.200  5639  5685 I jxcore-log: # setup
10-07 10:51:04.200  5639  5685 I jxcore-log: 
,10-07 10:51:04.201  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_native server connections all up''
10-07 10:51:04.201  5639  5685 I jxcore-log: 
,10-07 10:51:04.247  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server connections all up_confirmed', data: '{"uuid":"4fd9e3f5-9278-475d-a28e-d6969c9fa58e"}''
10-07 10:51:04.247  5639  5685 I jxcore-log: 
,10-07 10:51:04.256  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server connections all up_finished', data: '{"success":true}''
10-07 10:51:04.256  5639  5685 I jxcore-log: 
,10-07 10:51:04.263  5639  5685 I jxcore-log: # native server connections all up
10-07 10:51:04.263  5639  5685 I jxcore-log: 
,10-07 10:51:04.268  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_native server connections all up''
10-07 10:51:04.268  5639  5685 I jxcore-log: 
,10-07 10:51:04.359  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server connections all up_confirmed', data: '{"uuid":"d0913edd-8d0f-4e08-85dc-a170ecc7f1f5","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:04.359  5639  5685 I jxcore-log: 
,10-07 10:51:04.368  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:04.368  5639  5685 I jxcore-log: 
,10-07 10:51:04.376  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'listening 40194'
10-07 10:51:04.376  5639  5685 I jxcore-log: 
,10-07 10:51:04.385  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:04.385  5639  5685 I jxcore-log: 
,10-07 10:51:04.386  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:04.386  5639  5685 I jxcore-log: 
10-07 10:51:04.388  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new mux'
10-07 10:51:04.388  5639  5685 I jxcore-log: 
,10-07 10:51:04.419  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:04.419  5639  5685 I jxcore-log: 
,10-07 10:51:04.422  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:04.422  5639  5685 I jxcore-log: 
,10-07 10:51:04.425  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:04.425  5639  5685 I jxcore-log: 
,10-07 10:51:04.428  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:04.428  5639  5685 I jxcore-log: 
,10-07 10:51:04.454  5639  5685 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-07 10:51:04.454  5639  5685 I jxcore-log: 
,10-07 10:51:04.454  5639  5685 I jxcore-log: ok 8 Send/recvd #1 should be same
10-07 10:51:04.454  5639  5685 I jxcore-log: 
,10-07 10:51:04.457  5639  5685 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-07 10:51:04.457  5639  5685 I jxcore-log: 
10-07 10:51:04.458  5639  5685 I jxcore-log: ok 10 Send/recvd #2 should be same
10-07 10:51:04.458  5639  5685 I jxcore-log: 
,10-07 10:51:04.460  5639  5685 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-07 10:51:04.460  5639  5685 I jxcore-log: 
,10-07 10:51:04.463  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server connections all up_finished', data: '{"success":true}''
10-07 10:51:04.463  5639  5685 I jxcore-log: 
,10-07 10:51:04.468  5639  5685 I jxcore-log: # teardown
10-07 10:51:04.468  5639  5685 I jxcore-log: 
,10-07 10:51:04.468  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_native server connections all up''
10-07 10:51:04.468  5639  5685 I jxcore-log: 
,10-07 10:51:04.496  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server connections all up_confirmed', data: '{"uuid":"2f3adc23-35f1-415e-8a32-84f40b271ff3"}''
10-07 10:51:04.496  5639  5685 I jxcore-log: 
,10-07 10:51:04.498  5639  5685 I jxcore-log: server is closing
10-07 10:51:04.498  5639  5685 I jxcore-log: 
,10-07 10:51:04.498  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:04.498  5639  5685 I jxcore-log: 
10-07 10:51:04.498  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:04.498  5639  5685 I jxcore-log: 
10-07 10:51:04.499  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:04.499  5639  5685 I jxcore-log: 
,10-07 10:51:04.500  5639  5685 I jxcore-log: server is closing
10-07 10:51:04.500  5639  5685 I jxcore-log: 
10-07 10:51:04.500  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:04.500  5639  5685 I jxcore-log: 
10-07 10:51:04.501  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:04.501  5639  5685 I jxcore-log: 
10-07 10:51:04.501  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:04.501  5639  5685 I jxcore-log: 
10-07 10:51:04.504  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:04.504  5639  5685 I jxcore-log: 
10-07 10:51:04.506  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:04.506  5639  5685 I jxcore-log: 
,10-07 10:51:04.507  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'mux close'
10-07 10:51:04.507  5639  5685 I jxcore-log: 
,10-07 10:51:04.509  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server connections all up_finished', data: '{"success":true}''
10-07 10:51:04.509  5639  5685 I jxcore-log: 
,10-07 10:51:04.516  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:04.516  5639  5685 I jxcore-log: 
,10-07 10:51:04.525  5639  5685 I jxcore-log: # setup
10-07 10:51:04.525  5639  5685 I jxcore-log: 
,10-07 10:51:04.526  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket''
10-07 10:51:04.526  5639  5685 I jxcore-log: 
,10-07 10:51:04.570  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed', data: '{"uuid":"2072a262-810c-474a-8f59-0de40403dffe"}''
10-07 10:51:04.570  5639  5685 I jxcore-log: 
,10-07 10:51:04.576  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished', data: '{"success":true}''
10-07 10:51:04.576  5639  5685 I jxcore-log: 
,10-07 10:51:04.580  5639  5685 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-07 10:51:04.580  5639  5685 I jxcore-log: 
,10-07 10:51:04.583  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket''
10-07 10:51:04.583  5639  5685 I jxcore-log: 
,10-07 10:51:04.703  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed', data: '{"uuid":"2d38b625-c624-4927-8592-c400d547d9c1","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:04.703  5639  5685 I jxcore-log: 
,10-07 10:51:04.711  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:04.711  5639  5685 I jxcore-log: 
,10-07 10:51:04.717  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'listening 49734'
10-07 10:51:04.717  5639  5685 I jxcore-log: 
,10-07 10:51:04.728  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:04.728  5639  5685 I jxcore-log: 
,10-07 10:51:04.730  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:04.730  5639  5685 I jxcore-log: 
,10-07 10:51:04.732  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new mux'
10-07 10:51:04.732  5639  5685 I jxcore-log: 
,10-07 10:51:04.752  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:04.752  5639  5685 I jxcore-log: 
,10-07 10:51:04.756  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:04.756  5639  5685 I jxcore-log: 
,10-07 10:51:04.773  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:04.773  5639  5685 I jxcore-log: 
,10-07 10:51:04.790  5639  5685 I jxcore-log: ok 12 socket shouldn't close until after stream
10-07 10:51:04.790  5639  5685 I jxcore-log: 
,10-07 10:51:04.790  5639  5685 I jxcore-log: ok 13 incoming remains open
10-07 10:51:04.790  5639  5685 I jxcore-log: 
10-07 10:51:04.792  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket_finished', data: '{"success":true}''
10-07 10:51:04.792  5639  5685 I jxcore-log: 
,10-07 10:51:04.794  5639  5685 I jxcore-log: # teardown
10-07 10:51:04.794  5639  5685 I jxcore-log: 
,10-07 10:51:04.795  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket''
10-07 10:51:04.795  5639  5685 I jxcore-log: 
,10-07 10:51:04.835  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed', data: '{"uuid":"045d5701-8d99-47e4-b4c4-b4a96f96938b"}''
10-07 10:51:04.835  5639  5685 I jxcore-log: 
,10-07 10:51:04.841  5639  5685 I jxcore-log: server is closing
10-07 10:51:04.841  5639  5685 I jxcore-log: 
,10-07 10:51:04.841  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:04.841  5639  5685 I jxcore-log: 
10-07 10:51:04.842  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:04.842  5639  5685 I jxcore-log: 
10-07 10:51:04.842  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:04.842  5639  5685 I jxcore-log: 
,10-07 10:51:04.843  5639  5685 I jxcore-log: server is closing
10-07 10:51:04.843  5639  5685 I jxcore-log: 
10-07 10:51:04.844  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:04.844  5639  5685 I jxcore-log: 
10-07 10:51:04.844  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:04.844  5639  5685 I jxcore-log: 
,10-07 10:51:04.845  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:04.845  5639  5685 I jxcore-log: 
,10-07 10:51:04.848  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'mux close'
10-07 10:51:04.848  5639  5685 I jxcore-log: 
,10-07 10:51:04.855  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished', data: '{"success":true}''
10-07 10:51:04.855  5639  5685 I jxcore-log: 
,10-07 10:51:04.859  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:04.859  5639  5685 I jxcore-log: 
,10-07 10:51:04.864  5639  5685 I jxcore-log: # setup
10-07 10:51:04.864  5639  5685 I jxcore-log: 
,10-07 10:51:04.865  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket''
10-07 10:51:04.865  5639  5685 I jxcore-log: 
,10-07 10:51:04.928  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed', data: '{"uuid":"3b020264-c921-4f80-97a6-e52c5d468e51"}''
10-07 10:51:04.928  5639  5685 I jxcore-log: 
,10-07 10:51:04.947  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished', data: '{"success":true}''
10-07 10:51:04.947  5639  5685 I jxcore-log: 
,10-07 10:51:04.952  5639  5685 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-07 10:51:04.952  5639  5685 I jxcore-log: 
,10-07 10:51:04.957  5639  5685 I jxcore-log: 2016-10-07 14:51:04 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket''
10-07 10:51:04.957  5639  5685 I jxcore-log: 
,10-07 10:51:05.021  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed', data: '{"uuid":"025cb58a-6d30-4cf2-9fd5-3cb0d5db4c27","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:05.021  5639  5685 I jxcore-log: 
,10-07 10:51:05.028  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:05.028  5639  5685 I jxcore-log: 
,10-07 10:51:05.034  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'listening 49195'
10-07 10:51:05.034  5639  5685 I jxcore-log: 
,10-07 10:51:05.041  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:05.041  5639  5685 I jxcore-log: 
,10-07 10:51:05.043  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:05.043  5639  5685 I jxcore-log: 
10-07 10:51:05.044  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new mux'
10-07 10:51:05.044  5639  5685 I jxcore-log: 
,10-07 10:51:05.055  5639  5685 I jxcore-log: ok 14 we should not have gotten an error
10-07 10:51:05.055  5639  5685 I jxcore-log: 
,10-07 10:51:05.060  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:05.060  5639  5685 I jxcore-log: 
,10-07 10:51:05.064  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:05.064  5639  5685 I jxcore-log: 
,10-07 10:51:05.075  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:05.075  5639  5685 I jxcore-log: 
,10-07 10:51:05.077  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:05.077  5639  5685 I jxcore-log: 
,10-07 10:51:05.085  5639  5685 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-07 10:51:05.085  5639  5685 I jxcore-log: 
,10-07 10:51:05.085  5639  5685 I jxcore-log: ok 16 incoming is cleaned up
10-07 10:51:05.085  5639  5685 I jxcore-log: 
10-07 10:51:05.086  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket_finished', data: '{"success":true}''
10-07 10:51:05.086  5639  5685 I jxcore-log: 
,10-07 10:51:05.088  5639  5685 I jxcore-log: # teardown
10-07 10:51:05.088  5639  5685 I jxcore-log: 
,10-07 10:51:05.089  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket''
10-07 10:51:05.089  5639  5685 I jxcore-log: 
,10-07 10:51:05.235  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed', data: '{"uuid":"f7938288-1d59-4d17-9836-bb828475ffcf"}''
10-07 10:51:05.235  5639  5685 I jxcore-log: 
,10-07 10:51:05.243  5639  5685 I jxcore-log: server is closing
10-07 10:51:05.243  5639  5685 I jxcore-log: 
,10-07 10:51:05.245  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:05.245  5639  5685 I jxcore-log: 
,10-07 10:51:05.246  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:05.246  5639  5685 I jxcore-log: 
10-07 10:51:05.246  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:05.246  5639  5685 I jxcore-log: 
,10-07 10:51:05.250  5639  5685 I jxcore-log: server is closing
10-07 10:51:05.250  5639  5685 I jxcore-log: 
,10-07 10:51:05.251  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:05.251  5639  5685 I jxcore-log: 
10-07 10:51:05.251  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:05.251  5639  5685 I jxcore-log: 
10-07 10:51:05.251  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:05.251  5639  5685 I jxcore-log: 
10-07 10:51:05.254  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished', data: '{"success":true}''
10-07 10:51:05.254  5639  5685 I jxcore-log: 
,10-07 10:51:05.258  5639  5685 I jxcore-log: # setup
10-07 10:51:05.258  5639  5685 I jxcore-log: 
,10-07 10:51:05.259  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream''
10-07 10:51:05.259  5639  5685 I jxcore-log: 
,10-07 10:51:05.341  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed', data: '{"uuid":"b7df00f8-3229-4f74-b33c-7b6b9219b947"}''
10-07 10:51:05.341  5639  5685 I jxcore-log: 
,10-07 10:51:05.352  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished', data: '{"success":true}''
10-07 10:51:05.352  5639  5685 I jxcore-log: 
,10-07 10:51:05.359  5639  5685 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-07 10:51:05.359  5639  5685 I jxcore-log: 
,10-07 10:51:05.365  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream''
10-07 10:51:05.365  5639  5685 I jxcore-log: 
,10-07 10:51:05.395  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed', data: '{"uuid":"1347ce77-baa0-479b-8a9c-b6a2f04b9d4f","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:05.395  5639  5685 I jxcore-log: 
,10-07 10:51:05.405  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:05.405  5639  5685 I jxcore-log: 
,10-07 10:51:05.410  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'listening 48634'
10-07 10:51:05.410  5639  5685 I jxcore-log: 
,10-07 10:51:05.418  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:05.418  5639  5685 I jxcore-log: 
,10-07 10:51:05.419  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:05.419  5639  5685 I jxcore-log: 
,10-07 10:51:05.423  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new mux'
10-07 10:51:05.423  5639  5685 I jxcore-log: 
,10-07 10:51:05.434  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:05.434  5639  5685 I jxcore-log: 
,10-07 10:51:05.436  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:05.436  5639  5685 I jxcore-log: 
,10-07 10:51:05.449  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:05.449  5639  5685 I jxcore-log: 
,10-07 10:51:05.457  5639  5685 I jxcore-log: ok 17 stream was closed
10-07 10:51:05.457  5639  5685 I jxcore-log: 
,10-07 10:51:05.458  5639  5685 I jxcore-log: ok 18 incoming should survive
10-07 10:51:05.458  5639  5685 I jxcore-log: 
10-07 10:51:05.458  5639  5685 I jxcore-log: ok 19 mux should have no streams
10-07 10:51:05.458  5639  5685 I jxcore-log: 
10-07 10:51:05.459  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished', data: '{"success":true}''
10-07 10:51:05.459  5639  5685 I jxcore-log: 
,10-07 10:51:05.462  5639  5685 I jxcore-log: # teardown
10-07 10:51:05.462  5639  5685 I jxcore-log: 
,10-07 10:51:05.463  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream''
10-07 10:51:05.463  5639  5685 I jxcore-log: 
,10-07 10:51:05.502  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed', data: '{"uuid":"4b8bd82b-49c8-47fc-9dac-0b832d519e73"}''
10-07 10:51:05.502  5639  5685 I jxcore-log: 
,10-07 10:51:05.504  5639  5685 I jxcore-log: server is closing
10-07 10:51:05.504  5639  5685 I jxcore-log: 
,10-07 10:51:05.505  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:05.505  5639  5685 I jxcore-log: 
10-07 10:51:05.505  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:05.505  5639  5685 I jxcore-log: 
10-07 10:51:05.505  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:05.505  5639  5685 I jxcore-log: 
10-07 10:51:05.506  5639  5685 I jxcore-log: server is closing
10-07 10:51:05.506  5639  5685 I jxcore-log: 
10-07 10:51:05.506  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:05.506  5639  5685 I jxcore-log: 
10-07 10:51:05.506  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:05.506  5639  5685 I jxcore-log: 
10-07 10:51:05.507  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:05.507  5639  5685 I jxcore-log: 
10-07 10:51:05.508  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'mux close'
10-07 10:51:05.508  5639  5685 I jxcore-log: 
,10-07 10:51:05.519  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished', data: '{"success":true}''
10-07 10:51:05.519  5639  5685 I jxcore-log: 
,10-07 10:51:05.522  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:05.522  5639  5685 I jxcore-log: 
,10-07 10:51:05.529  5639  5685 I jxcore-log: # setup
10-07 10:51:05.529  5639  5685 I jxcore-log: 
10-07 10:51:05.530  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up''
10-07 10:51:05.530  5639  5685 I jxcore-log: 
,10-07 10:51:05.633  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up_confirmed', data: '{"uuid":"de561ba1-bb40-4523-8a4f-bc9b2955c7de"}''
10-07 10:51:05.633  5639  5685 I jxcore-log: 
,10-07 10:51:05.645  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up_finished', data: '{"success":true}''
10-07 10:51:05.645  5639  5685 I jxcore-log: 
,10-07 10:51:05.651  5639  5685 I jxcore-log: # native server - closing the whole server cleans everything up
10-07 10:51:05.651  5639  5685 I jxcore-log: 
,10-07 10:51:05.654  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up''
10-07 10:51:05.654  5639  5685 I jxcore-log: 
,10-07 10:51:05.700  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up_confirmed', data: '{"uuid":"bf556015-1bad-45f5-b275-e2e059dd6d93","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:05.700  5639  5685 I jxcore-log: 
,10-07 10:51:05.704  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:05.704  5639  5685 I jxcore-log: 
,10-07 10:51:05.709  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'listening 37209'
10-07 10:51:05.709  5639  5685 I jxcore-log: 
,10-07 10:51:05.716  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:05.716  5639  5685 I jxcore-log: 
,10-07 10:51:05.719  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:05.719  5639  5685 I jxcore-log: 
,10-07 10:51:05.720  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new mux'
10-07 10:51:05.720  5639  5685 I jxcore-log: 
,10-07 10:51:05.728  5639  5685 I jxcore-log: ok 20 we should not have gotten an error
10-07 10:51:05.728  5639  5685 I jxcore-log: 
,10-07 10:51:05.733  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:05.733  5639  5685 I jxcore-log: 
,10-07 10:51:05.736  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:05.736  5639  5685 I jxcore-log: 
,10-07 10:51:05.743  5639  5685 I jxcore-log: ok 21 Buffers are identical
10-07 10:51:05.743  5639  5685 I jxcore-log: 
,10-07 10:51:05.743  5639  5685 I jxcore-log: server is closing
10-07 10:51:05.743  5639  5685 I jxcore-log: 
10-07 10:51:05.744  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:05.744  5639  5685 I jxcore-log: 
10-07 10:51:05.744  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:05.744  5639  5685 I jxcore-log: 
,10-07 10:51:05.744  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:05.744  5639  5685 I jxcore-log: 
,10-07 10:51:05.746  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:05.746  5639  5685 I jxcore-log: 
,10-07 10:51:05.748  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'mux close'
10-07 10:51:05.748  5639  5685 I jxcore-log: 
,10-07 10:51:05.750  5639  5685 I jxcore-log: ok 22 native server is nulled out
10-07 10:51:05.750  5639  5685 I jxcore-log: 
,10-07 10:51:05.751  5639  5685 I jxcore-log: ok 23 native server should be closed
10-07 10:51:05.751  5639  5685 I jxcore-log: 
10-07 10:51:05.751  5639  5685 I jxcore-log: ok 24 incoming has been removed
10-07 10:51:05.751  5639  5685 I jxcore-log: 
10-07 10:51:05.752  5639  5685 I jxcore-log: ok 25 Incoming should be done
10-07 10:51:05.752  5639  5685 I jxcore-log: 
10-07 10:51:05.752  5639  5685 I jxcore-log: ok 26 The mux object should be closed
10-07 10:51:05.752  5639  5685 I jxcore-log: 
10-07 10:51:05.752  5639  5685 I jxcore-log: ok 27 The mux stream should be closed
10-07 10:51:05.752  5639  5685 I jxcore-log: 
,10-07 10:51:05.753  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:05.753  5639  5685 I jxcore-log: 
,10-07 10:51:05.762  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up_finished', data: '{"success":true}''
10-07 10:51:05.762  5639  5685 I jxcore-log: 
,10-07 10:51:05.765  5639  5685 I jxcore-log: # teardown
10-07 10:51:05.765  5639  5685 I jxcore-log: 
,10-07 10:51:05.766  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up''
10-07 10:51:05.766  5639  5685 I jxcore-log: 
,10-07 10:51:05.832  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up_confirmed', data: '{"uuid":"45209c09-3850-463b-a4a9-2a7ad75e8bf7"}''
10-07 10:51:05.832  5639  5685 I jxcore-log: 
,10-07 10:51:05.838  5639  5685 I jxcore-log: server is closing
10-07 10:51:05.838  5639  5685 I jxcore-log: 
,10-07 10:51:05.839  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:05.839  5639  5685 I jxcore-log: 
,10-07 10:51:05.839  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:05.839  5639  5685 I jxcore-log: 
,10-07 10:51:05.839  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:05.839  5639  5685 I jxcore-log: 
,10-07 10:51:05.844  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up_finished', data: '{"success":true}''
10-07 10:51:05.844  5639  5685 I jxcore-log: 
,10-07 10:51:05.849  5639  5685 I jxcore-log: # setup
10-07 10:51:05.849  5639  5685 I jxcore-log: 
,10-07 10:51:05.851  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely''
10-07 10:51:05.851  5639  5685 I jxcore-log: 
,10-07 10:51:05.915  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed', data: '{"uuid":"889a20b6-d939-4082-8597-e167257358bb"}''
10-07 10:51:05.915  5639  5685 I jxcore-log: 
,10-07 10:51:05.925  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished', data: '{"success":true}''
10-07 10:51:05.925  5639  5685 I jxcore-log: 
,10-07 10:51:05.931  5639  5685 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-07 10:51:05.931  5639  5685 I jxcore-log: 
,10-07 10:51:05.935  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely''
10-07 10:51:05.935  5639  5685 I jxcore-log: 
,10-07 10:51:05.995  5639  5685 I jxcore-log: 2016-10-07 14:51:05 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed', data: '{"uuid":"326b3757-3bfd-4333-91c3-362747e1c8bd","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:05.995  5639  5685 I jxcore-log: 
,10-07 10:51:06.000  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:06.000  5639  5685 I jxcore-log: 
,10-07 10:51:06.005  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'listening 44668'
10-07 10:51:06.005  5639  5685 I jxcore-log: 
,10-07 10:51:06.039  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.039  5639  5685 I jxcore-log: 
,10-07 10:51:06.039  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.039  5639  5685 I jxcore-log: 
10-07 10:51:06.041  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.041  5639  5685 I jxcore-log: 
,10-07 10:51:06.044  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.044  5639  5685 I jxcore-log: 
,10-07 10:51:06.045  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.045  5639  5685 I jxcore-log: 
10-07 10:51:06.046  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.046  5639  5685 I jxcore-log: 
,10-07 10:51:06.050  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.050  5639  5685 I jxcore-log: 
,10-07 10:51:06.051  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.051  5639  5685 I jxcore-log: 
,10-07 10:51:06.052  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.052  5639  5685 I jxcore-log: 
,10-07 10:51:06.055  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.055  5639  5685 I jxcore-log: 
,10-07 10:51:06.056  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.056  5639  5685 I jxcore-log: 
10-07 10:51:06.057  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.057  5639  5685 I jxcore-log: 
,10-07 10:51:06.060  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.060  5639  5685 I jxcore-log: 
,10-07 10:51:06.060  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.060  5639  5685 I jxcore-log: 
,10-07 10:51:06.062  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.062  5639  5685 I jxcore-log: 
,10-07 10:51:06.063  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.063  5639  5685 I jxcore-log: 
10-07 10:51:06.064  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.064  5639  5685 I jxcore-log: 
,10-07 10:51:06.065  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.065  5639  5685 I jxcore-log: 
,10-07 10:51:06.067  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.067  5639  5685 I jxcore-log: 
,10-07 10:51:06.068  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.068  5639  5685 I jxcore-log: 
,10-07 10:51:06.069  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.069  5639  5685 I jxcore-log: 
,10-07 10:51:06.071  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.071  5639  5685 I jxcore-log: 
10-07 10:51:06.072  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.072  5639  5685 I jxcore-log: 
,10-07 10:51:06.073  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.073  5639  5685 I jxcore-log: 
,10-07 10:51:06.076  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.076  5639  5685 I jxcore-log: 
,10-07 10:51:06.076  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.076  5639  5685 I jxcore-log: 
,10-07 10:51:06.077  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.077  5639  5685 I jxcore-log: 
,10-07 10:51:06.086  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.086  5639  5685 I jxcore-log: 
,10-07 10:51:06.088  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.088  5639  5685 I jxcore-log: 
,10-07 10:51:06.090  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.090  5639  5685 I jxcore-log: 
,10-07 10:51:06.147  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.147  5639  5685 I jxcore-log: 
,10-07 10:51:06.149  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.149  5639  5685 I jxcore-log: 
,10-07 10:51:06.151  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.151  5639  5685 I jxcore-log: 
,10-07 10:51:06.152  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.152  5639  5685 I jxcore-log: 
,10-07 10:51:06.153  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.153  5639  5685 I jxcore-log: 
,10-07 10:51:06.154  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.154  5639  5685 I jxcore-log: 
,10-07 10:51:06.155  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.155  5639  5685 I jxcore-log: 
,10-07 10:51:06.156  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.156  5639  5685 I jxcore-log: 
,10-07 10:51:06.158  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.158  5639  5685 I jxcore-log: 
,10-07 10:51:06.159  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.159  5639  5685 I jxcore-log: 
,10-07 10:51:06.160  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.160  5639  5685 I jxcore-log: 
10-07 10:51:06.160  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.160  5639  5685 I jxcore-log: 
,10-07 10:51:06.161  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.161  5639  5685 I jxcore-log: 
10-07 10:51:06.162  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.162  5639  5685 I jxcore-log: 
,10-07 10:51:06.163  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.163  5639  5685 I jxcore-log: 
10-07 10:51:06.164  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.164  5639  5685 I jxcore-log: 
,10-07 10:51:06.165  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.165  5639  5685 I jxcore-log: 
10-07 10:51:06.166  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.166  5639  5685 I jxcore-log: 
10-07 10:51:06.166  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.166  5639  5685 I jxcore-log: 
,10-07 10:51:06.167  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.167  5639  5685 I jxcore-log: 
10-07 10:51:06.168  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.168  5639  5685 I jxcore-log: 
,10-07 10:51:06.169  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.169  5639  5685 I jxcore-log: 
10-07 10:51:06.169  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.169  5639  5685 I jxcore-log: 
,10-07 10:51:06.170  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.170  5639  5685 I jxcore-log: 
,10-07 10:51:06.171  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.171  5639  5685 I jxcore-log: 
,10-07 10:51:06.172  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.172  5639  5685 I jxcore-log: 
10-07 10:51:06.173  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.173  5639  5685 I jxcore-log: 
,10-07 10:51:06.174  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.174  5639  5685 I jxcore-log: 
10-07 10:51:06.174  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.174  5639  5685 I jxcore-log: 
,10-07 10:51:06.175  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.175  5639  5685 I jxcore-log: 
10-07 10:51:06.176  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.176  5639  5685 I jxcore-log: 
10-07 10:51:06.177  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.177  5639  5685 I jxcore-log: 
,10-07 10:51:06.178  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.178  5639  5685 I jxcore-log: 
10-07 10:51:06.179  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.179  5639  5685 I jxcore-log: 
,10-07 10:51:06.179  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.179  5639  5685 I jxcore-log: 
10-07 10:51:06.180  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.180  5639  5685 I jxcore-log: 
,10-07 10:51:06.186  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.186  5639  5685 I jxcore-log: 
,10-07 10:51:06.187  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.187  5639  5685 I jxcore-log: 
,10-07 10:51:06.188  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.188  5639  5685 I jxcore-log: 
,10-07 10:51:06.189  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.189  5639  5685 I jxcore-log: 
,10-07 10:51:06.191  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.191  5639  5685 I jxcore-log: 
,10-07 10:51:06.192  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.192  5639  5685 I jxcore-log: 
,10-07 10:51:06.192  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.192  5639  5685 I jxcore-log: 
10-07 10:51:06.193  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.193  5639  5685 I jxcore-log: 
,10-07 10:51:06.194  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.194  5639  5685 I jxcore-log: 
10-07 10:51:06.195  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.195  5639  5685 I jxcore-log: 
,10-07 10:51:06.195  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.195  5639  5685 I jxcore-log: 
10-07 10:51:06.196  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.196  5639  5685 I jxcore-log: 
,10-07 10:51:06.197  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.197  5639  5685 I jxcore-log: 
,10-07 10:51:06.198  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.198  5639  5685 I jxcore-log: 
,10-07 10:51:06.201  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.201  5639  5685 I jxcore-log: 
,10-07 10:51:06.203  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.203  5639  5685 I jxcore-log: 
,10-07 10:51:06.204  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.204  5639  5685 I jxcore-log: 
,10-07 10:51:06.205  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.205  5639  5685 I jxcore-log: 
,10-07 10:51:06.205  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.205  5639  5685 I jxcore-log: 
,10-07 10:51:06.206  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.206  5639  5685 I jxcore-log: 
,10-07 10:51:06.207  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.207  5639  5685 I jxcore-log: 
,10-07 10:51:06.208  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.208  5639  5685 I jxcore-log: 
,10-07 10:51:06.209  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.209  5639  5685 I jxcore-log: 
,10-07 10:51:06.210  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.210  5639  5685 I jxcore-log: 
,10-07 10:51:06.210  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.210  5639  5685 I jxcore-log: 
10-07 10:51:06.211  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.211  5639  5685 I jxcore-log: 
,10-07 10:51:06.212  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.212  5639  5685 I jxcore-log: 
10-07 10:51:06.213  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.213  5639  5685 I jxcore-log: 
,10-07 10:51:06.214  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.214  5639  5685 I jxcore-log: 
,10-07 10:51:06.215  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.215  5639  5685 I jxcore-log: 
10-07 10:51:06.215  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.215  5639  5685 I jxcore-log: 
10-07 10:51:06.216  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.216  5639  5685 I jxcore-log: 
,10-07 10:51:06.216  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.216  5639  5685 I jxcore-log: 
10-07 10:51:06.217  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.217  5639  5685 I jxcore-log: 
10-07 10:51:06.218  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.218  5639  5685 I jxcore-log: 
,10-07 10:51:06.218  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.218  5639  5685 I jxcore-log: 
,10-07 10:51:06.219  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.219  5639  5685 I jxcore-log: 
10-07 10:51:06.220  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.220  5639  5685 I jxcore-log: 
,10-07 10:51:06.220  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.220  5639  5685 I jxcore-log: 
10-07 10:51:06.221  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.221  5639  5685 I jxcore-log: 
10-07 10:51:06.222  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.222  5639  5685 I jxcore-log: 
,10-07 10:51:06.222  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.222  5639  5685 I jxcore-log: 
10-07 10:51:06.223  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.223  5639  5685 I jxcore-log: 
,10-07 10:51:06.223  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.223  5639  5685 I jxcore-log: 
,10-07 10:51:06.265  5639  5685 I jxcore-log: server is closing
10-07 10:51:06.265  5639  5685 I jxcore-log: 
,10-07 10:51:06.266  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:06.266  5639  5685 I jxcore-log: 
10-07 10:51:06.266  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:06.266  5639  5685 I jxcore-log: 
,10-07 10:51:06.267  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:06.267  5639  5685 I jxcore-log: 
,10-07 10:51:06.268  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.268  5639  5685 I jxcore-log: 
,10-07 10:51:06.269  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.269  5639  5685 I jxcore-log: 
,10-07 10:51:06.270  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.270  5639  5685 I jxcore-log: 
,10-07 10:51:06.271  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.271  5639  5685 I jxcore-log: 
10-07 10:51:06.271  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.271  5639  5685 I jxcore-log: 
,10-07 10:51:06.272  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.272  5639  5685 I jxcore-log: 
,10-07 10:51:06.274  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.274  5639  5685 I jxcore-log: 
10-07 10:51:06.274  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.274  5639  5685 I jxcore-log: 
,10-07 10:51:06.275  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.275  5639  5685 I jxcore-log: 
10-07 10:51:06.275  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.275  5639  5685 I jxcore-log: 
,10-07 10:51:06.276  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.276  5639  5685 I jxcore-log: 
10-07 10:51:06.276  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.276  5639  5685 I jxcore-log: 
10-07 10:51:06.277  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.277  5639  5685 I jxcore-log: 
,10-07 10:51:06.277  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.277  5639  5685 I jxcore-log: 
10-07 10:51:06.278  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.278  5639  5685 I jxcore-log: 
,10-07 10:51:06.278  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.278  5639  5685 I jxcore-log: 
10-07 10:51:06.279  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.279  5639  5685 I jxcore-log: 
10-07 10:51:06.279  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.279  5639  5685 I jxcore-log: 
,10-07 10:51:06.280  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.280  5639  5685 I jxcore-log: 
10-07 10:51:06.280  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.280  5639  5685 I jxcore-log: 
10-07 10:51:06.280  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.280  5639  5685 I jxcore-log: 
,10-07 10:51:06.281  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.281  5639  5685 I jxcore-log: 
10-07 10:51:06.281  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.281  5639  5685 I jxcore-log: 
10-07 10:51:06.282  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.282  5639  5685 I jxcore-log: 
,10-07 10:51:06.282  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.282  5639  5685 I jxcore-log: 
10-07 10:51:06.283  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.283  5639  5685 I jxcore-log: 
,10-07 10:51:06.283  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.283  5639  5685 I jxcore-log: 
10-07 10:51:06.284  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.284  5639  5685 I jxcore-log: 
,10-07 10:51:06.284  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.284  5639  5685 I jxcore-log: 
10-07 10:51:06.284  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.284  5639  5685 I jxcore-log: 
10-07 10:51:06.285  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.285  5639  5685 I jxcore-log: 
10-07 10:51:06.285  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.285  5639  5685 I jxcore-log: 
,10-07 10:51:06.286  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.286  5639  5685 I jxcore-log: 
10-07 10:51:06.286  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.286  5639  5685 I jxcore-log: 
10-07 10:51:06.286  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.286  5639  5685 I jxcore-log: 
10-07 10:51:06.287  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.287  5639  5685 I jxcore-log: 
,10-07 10:51:06.287  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.287  5639  5685 I jxcore-log: 
10-07 10:51:06.288  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.288  5639  5685 I jxcore-log: 
10-07 10:51:06.288  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.288  5639  5685 I jxcore-log: 
10-07 10:51:06.289  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.289  5639  5685 I jxcore-log: 
10-07 10:51:06.289  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.289  5639  5685 I jxcore-log: 
10-07 10:51:06.289  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.289  5639  5685 I jxcore-log: 
10-07 10:51:06.290  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.290  5639  5685 I jxcore-log: 
10-07 10:51:06.290  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.290  5639  5685 I jxcore-log: 
10-07 10:51:06.290  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.290  5639  5685 I jxcore-log: 
10-07 10:51:06.291  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.291  5639  5685 I jxcore-log: 
10-07 10:51:06.291  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.291  5639  5685 I jxcore-log: 
10-07 10:51:06.292  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.292  5639  5685 I jxcore-log: 
10-07 10:51:06.292  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.292  5639  5685 I jxcore-log: 
10-07 10:51:06.292  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.292  5639  5685 I jxcore-log: 
10-07 10:51:06.294  5639  5685 I jxcore-log: ok 28 native server is nulled out
10-07 10:51:06.294  5639  5685 I jxcore-log: 
10-07 10:51:06.294  5639  5685 I jxcore-log: ok 29 native server should be closed
10-07 10:51:06.294  5639  5685 I jxcore-log: 
10-07 10:51:06.295  5639  5685 I jxcore-log: ok 30 incoming has been removed
10-07 10:51:06.295  5639  5685 I jxcore-log: 
10-07 10:51:06.295  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.295  5639  5685 I jxcore-log: 
10-07 10:51:06.296  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.296  5639  5685 I jxcore-log: 
10-07 10:51:06.296  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.296  5639  5685 I jxcore-log: 
10-07 10:51:06.296  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.296  5639  5685 I jxcore-log: 
10-07 10:51:06.297  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.297  5639  5685 I jxcore-log: 
10-07 10:51:06.297  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.297  5639  5685 I jxcore-log: 
10-07 10:51:06.297  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.297  5639  5685 I jxcore-log: 
10-07 10:51:06.297  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.297  5639  5685 I jxcore-log: 
10-07 10:51:06.298  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.298  5639  5685 I jxcore-log: 
10-07 10:51:06.298  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.298  5639  5685 I jxcore-log: 
,10-07 10:51:06.327  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished', data: '{"success":true}''
10-07 10:51:06.327  5639  5685 I jxcore-log: 
,10-07 10:51:06.368  5639  5685 I jxcore-log: # teardown
10-07 10:51:06.368  5639  5685 I jxcore-log: 
,10-07 10:51:06.369  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely''
10-07 10:51:06.369  5639  5685 I jxcore-log: 
,10-07 10:51:06.445  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed', data: '{"uuid":"177a2fa5-e022-4c3c-be85-f8e4b37785d2"}''
10-07 10:51:06.445  5639  5685 I jxcore-log: 
,10-07 10:51:06.452  5639  5685 I jxcore-log: server is closing
10-07 10:51:06.452  5639  5685 I jxcore-log: 
,10-07 10:51:06.453  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:06.453  5639  5685 I jxcore-log: 
10-07 10:51:06.453  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:06.453  5639  5685 I jxcore-log: 
,10-07 10:51:06.455  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:06.455  5639  5685 I jxcore-log: 
,10-07 10:51:06.459  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished', data: '{"success":true}''
10-07 10:51:06.459  5639  5685 I jxcore-log: 
,10-07 10:51:06.466  5639  5685 I jxcore-log: # setup
10-07 10:51:06.466  5639  5685 I jxcore-log: 
,10-07 10:51:06.467  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up''
10-07 10:51:06.467  5639  5685 I jxcore-log: 
,10-07 10:51:06.499  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed', data: '{"uuid":"b544ae8d-70c1-4365-872d-db17a5649bd6"}''
10-07 10:51:06.499  5639  5685 I jxcore-log: 
,10-07 10:51:06.506  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished', data: '{"success":true}''
10-07 10:51:06.506  5639  5685 I jxcore-log: 
,10-07 10:51:06.510  5639  5685 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-07 10:51:06.510  5639  5685 I jxcore-log: 
,10-07 10:51:06.513  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up''
10-07 10:51:06.513  5639  5685 I jxcore-log: 
,10-07 10:51:06.578  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed', data: '{"uuid":"d7f26703-8fa7-4989-91d4-b20201217cb0","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:06.578  5639  5685 I jxcore-log: 
,10-07 10:51:06.584  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:06.584  5639  5685 I jxcore-log: 
,10-07 10:51:06.591  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'listening 48604'
10-07 10:51:06.591  5639  5685 I jxcore-log: 
,10-07 10:51:06.599  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.599  5639  5685 I jxcore-log: 
,10-07 10:51:06.600  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.600  5639  5685 I jxcore-log: 
10-07 10:51:06.602  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.602  5639  5685 I jxcore-log: 
,10-07 10:51:06.609  5639  5685 I jxcore-log: ok 31 we should not have gotten an error
10-07 10:51:06.609  5639  5685 I jxcore-log: 
,10-07 10:51:06.612  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.612  5639  5685 I jxcore-log: 
,10-07 10:51:06.615  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.615  5639  5685 I jxcore-log: 
,10-07 10:51:06.623  5639  5685 I jxcore-log: ok 32 Buffers are identical
10-07 10:51:06.623  5639  5685 I jxcore-log: 
,10-07 10:51:06.624  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.624  5639  5685 I jxcore-log: 
,10-07 10:51:06.626  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.626  5639  5685 I jxcore-log: 
,10-07 10:51:06.637  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.637  5639  5685 I jxcore-log: 
,10-07 10:51:06.638  5639  5685 I jxcore-log: ok 33 server should be fine
10-07 10:51:06.638  5639  5685 I jxcore-log: 
10-07 10:51:06.638  5639  5685 I jxcore-log: ok 34 server should be open
10-07 10:51:06.638  5639  5685 I jxcore-log: 
10-07 10:51:06.639  5639  5685 I jxcore-log: ok 35 incoming has been removed
10-07 10:51:06.639  5639  5685 I jxcore-log: 
10-07 10:51:06.639  5639  5685 I jxcore-log: ok 36 The mux object should be closed
10-07 10:51:06.639  5639  5685 I jxcore-log: 
10-07 10:51:06.639  5639  5685 I jxcore-log: ok 37 The mux stream should be closed
10-07 10:51:06.639  5639  5685 I jxcore-log: 
10-07 10:51:06.640  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished', data: '{"success":true}''
10-07 10:51:06.640  5639  5685 I jxcore-log: 
,10-07 10:51:06.643  5639  5685 I jxcore-log: # teardown
10-07 10:51:06.643  5639  5685 I jxcore-log: 
,10-07 10:51:06.643  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up''
10-07 10:51:06.643  5639  5685 I jxcore-log: 
,10-07 10:51:06.693  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed', data: '{"uuid":"95a50a18-a820-490b-8e3e-8b1c51183306"}''
10-07 10:51:06.693  5639  5685 I jxcore-log: 
,10-07 10:51:06.696  5639  5685 I jxcore-log: server is closing
10-07 10:51:06.696  5639  5685 I jxcore-log: 
,10-07 10:51:06.697  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:06.697  5639  5685 I jxcore-log: 
10-07 10:51:06.697  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:06.697  5639  5685 I jxcore-log: 
10-07 10:51:06.697  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:06.697  5639  5685 I jxcore-log: 
,10-07 10:51:06.699  5639  5685 I jxcore-log: server is closing
10-07 10:51:06.699  5639  5685 I jxcore-log: 
,10-07 10:51:06.699  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:06.699  5639  5685 I jxcore-log: 
10-07 10:51:06.699  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:06.699  5639  5685 I jxcore-log: 
10-07 10:51:06.699  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:06.699  5639  5685 I jxcore-log: 
,10-07 10:51:06.702  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished', data: '{"success":true}''
10-07 10:51:06.702  5639  5685 I jxcore-log: 
,10-07 10:51:06.706  5639  5685 I jxcore-log: # setup
10-07 10:51:06.706  5639  5685 I jxcore-log: 
,10-07 10:51:06.707  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up''
10-07 10:51:06.707  5639  5685 I jxcore-log: 
,10-07 10:51:06.789  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed', data: '{"uuid":"563107dc-9431-4656-b2d4-e32e2b2cf0ea"}''
10-07 10:51:06.789  5639  5685 I jxcore-log: 
,10-07 10:51:06.799  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up_finished', data: '{"success":true}''
10-07 10:51:06.799  5639  5685 I jxcore-log: 
,10-07 10:51:06.805  5639  5685 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-07 10:51:06.805  5639  5685 I jxcore-log: 
,10-07 10:51:06.813  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up''
10-07 10:51:06.813  5639  5685 I jxcore-log: 
,10-07 10:51:06.889  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed', data: '{"uuid":"e55a55d1-8934-44f1-8892-a90623752512","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:06.889  5639  5685 I jxcore-log: 
,10-07 10:51:06.898  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating native server'
10-07 10:51:06.898  5639  5685 I jxcore-log: 
,10-07 10:51:06.904  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'listening 37511'
10-07 10:51:06.904  5639  5685 I jxcore-log: 
,10-07 10:51:06.912  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new incoming socket'
10-07 10:51:06.912  5639  5685 I jxcore-log: 
,10-07 10:51:06.916  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'creating incoming mux'
10-07 10:51:06.916  5639  5685 I jxcore-log: 
,10-07 10:51:06.919  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new mux'
10-07 10:51:06.919  5639  5685 I jxcore-log: 
,10-07 10:51:06.929  5639  5685 I jxcore-log: ok 38 we should not have gotten an error
10-07 10:51:06.929  5639  5685 I jxcore-log: 
,10-07 10:51:06.934  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new stream: '
10-07 10:51:06.934  5639  5685 I jxcore-log: 
,10-07 10:51:06.937  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'new outgoing socket'
10-07 10:51:06.937  5639  5685 I jxcore-log: 
,10-07 10:51:06.947  5639  5685 I jxcore-log: ok 39 Buffers are identical
10-07 10:51:06.947  5639  5685 I jxcore-log: 
,10-07 10:51:06.955  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket timeout'
10-07 10:51:06.955  5639  5685 I jxcore-log: 
,10-07 10:51:06.956  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'stream close:'
10-07 10:51:06.956  5639  5685 I jxcore-log: 
10-07 10:51:06.958  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'mux close'
10-07 10:51:06.958  5639  5685 I jxcore-log: 
,10-07 10:51:06.965  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG createNativeListener: 'incoming socket close'
10-07 10:51:06.965  5639  5685 I jxcore-log: 
,10-07 10:51:06.966  5639  5685 I jxcore-log: ok 40 server should be fine
10-07 10:51:06.966  5639  5685 I jxcore-log: 
10-07 10:51:06.966  5639  5685 I jxcore-log: ok 41 server should be open
10-07 10:51:06.966  5639  5685 I jxcore-log: 
,10-07 10:51:06.967  5639  5685 I jxcore-log: ok 42 incoming has been removed
10-07 10:51:06.967  5639  5685 I jxcore-log: 
,10-07 10:51:06.968  5639  5685 I jxcore-log: ok 43 The mux object should be closed
10-07 10:51:06.968  5639  5685 I jxcore-log: 
,10-07 10:51:06.968  5639  5685 I jxcore-log: ok 44 The mux stream should be closed
10-07 10:51:06.968  5639  5685 I jxcore-log: 
,10-07 10:51:06.969  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up_finished', data: '{"success":true}''
10-07 10:51:06.969  5639  5685 I jxcore-log: 
,10-07 10:51:06.974  5639  5685 I jxcore-log: # teardown
10-07 10:51:06.974  5639  5685 I jxcore-log: 
,10-07 10:51:06.975  5639  5685 I jxcore-log: 2016-10-07 14:51:06 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up''
10-07 10:51:06.975  5639  5685 I jxcore-log: 
,10-07 10:51:07.022  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed', data: '{"uuid":"26c176b7-6c7f-492e-b462-8ace0f2a627c"}''
10-07 10:51:07.022  5639  5685 I jxcore-log: 
,10-07 10:51:07.027  5639  5685 I jxcore-log: server is closing
10-07 10:51:07.027  5639  5685 I jxcore-log: 
,10-07 10:51:07.029  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:07.029  5639  5685 I jxcore-log: 
,10-07 10:51:07.029  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:07.029  5639  5685 I jxcore-log: 
,10-07 10:51:07.029  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:07.029  5639  5685 I jxcore-log: 
,10-07 10:51:07.031  5639  5685 I jxcore-log: server is closing
10-07 10:51:07.031  5639  5685 I jxcore-log: 
,10-07 10:51:07.032  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:07.032  5639  5685 I jxcore-log: 
10-07 10:51:07.033  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:07.033  5639  5685 I jxcore-log: 
10-07 10:51:07.033  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:07.033  5639  5685 I jxcore-log: 
,10-07 10:51:07.038  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished', data: '{"success":true}''
10-07 10:51:07.038  5639  5685 I jxcore-log: 
,10-07 10:51:07.043  5639  5685 I jxcore-log: # setup
10-07 10:51:07.043  5639  5685 I jxcore-log: 
,10-07 10:51:07.044  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there''
10-07 10:51:07.044  5639  5685 I jxcore-log: 
,10-07 10:51:07.101  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed', data: '{"uuid":"a42a12b1-6774-46be-8b6e-204262bd62b9"}''
10-07 10:51:07.101  5639  5685 I jxcore-log: 
,10-07 10:51:07.106  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished', data: '{"success":true}''
10-07 10:51:07.106  5639  5685 I jxcore-log: 
,10-07 10:51:07.112  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-07 10:51:07.112  5639  5685 I jxcore-log: 
,10-07 10:51:07.115  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there''
10-07 10:51:07.115  5639  5685 I jxcore-log: 
,10-07 10:51:07.178  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed', data: '{"uuid":"f3f1939a-1fc4-4f46-90aa-f644c8f0adb1","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:07.178  5639  5685 I jxcore-log: 
,10-07 10:51:07.187  5639  5685 I jxcore-log: server is closing
10-07 10:51:07.187  5639  5685 I jxcore-log: 
,10-07 10:51:07.188  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:07.188  5639  5685 I jxcore-log: 
10-07 10:51:07.188  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:07.188  5639  5685 I jxcore-log: 
10-07 10:51:07.189  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:07.189  5639  5685 I jxcore-log: 
,10-07 10:51:07.320  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-07 10:51:07.320  5639  5685 I jxcore-log: 
,10-07 10:51:07.321  5639  5685 I jxcore-log: ok 45 Got right error
10-07 10:51:07.321  5639  5685 I jxcore-log: 
10-07 10:51:07.322  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there_finished', data: '{"success":true}''
10-07 10:51:07.322  5639  5685 I jxcore-log: 
,10-07 10:51:07.326  5639  5685 I jxcore-log: # teardown
10-07 10:51:07.326  5639  5685 I jxcore-log: 
,10-07 10:51:07.327  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there''
10-07 10:51:07.327  5639  5685 I jxcore-log: 
,10-07 10:51:07.372  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed', data: '{"uuid":"480dc61f-d0b4-4c03-a711-164b983474b2"}''
10-07 10:51:07.372  5639  5685 I jxcore-log: 
,10-07 10:51:07.377  5639  5685 I jxcore-log: server is closing
10-07 10:51:07.377  5639  5685 I jxcore-log: 
,10-07 10:51:07.380  5639  5685 I jxcore-log: server was closed with error: 'Error: Not running'
10-07 10:51:07.380  5639  5685 I jxcore-log: 
,10-07 10:51:07.381  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:07.381  5639  5685 I jxcore-log: 
10-07 10:51:07.381  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:07.381  5639  5685 I jxcore-log: 
,10-07 10:51:07.384  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished', data: '{"success":true}''
10-07 10:51:07.384  5639  5685 I jxcore-log: 
,10-07 10:51:07.389  5639  5685 I jxcore-log: # setup
10-07 10:51:07.389  5639  5685 I jxcore-log: 
,10-07 10:51:07.392  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection''
10-07 10:51:07.392  5639  5685 I jxcore-log: 
,10-07 10:51:07.466  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed', data: '{"uuid":"2ff44975-2496-4d04-b849-e4e068388886"}''
10-07 10:51:07.466  5639  5685 I jxcore-log: 
,10-07 10:51:07.476  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished', data: '{"success":true}''
10-07 10:51:07.476  5639  5685 I jxcore-log: 
,10-07 10:51:07.485  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-07 10:51:07.485  5639  5685 I jxcore-log: 
,10-07 10:51:07.488  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection''
10-07 10:51:07.488  5639  5685 I jxcore-log: 
,10-07 10:51:07.539  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed', data: '{"uuid":"aec63c25-a468-43a4-8d51-2ac408c21f96","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:07.539  5639  5685 I jxcore-log: 
,10-07 10:51:07.593  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-07 10:51:07.593  5639  5685 I jxcore-log: 
,10-07 10:51:07.595  5639  5685 I jxcore-log: ok 46 Got socket hang up
10-07 10:51:07.595  5639  5685 I jxcore-log: 
,10-07 10:51:07.596  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished', data: '{"success":true}''
10-07 10:51:07.596  5639  5685 I jxcore-log: 
,10-07 10:51:07.599  5639  5685 I jxcore-log: # teardown
10-07 10:51:07.599  5639  5685 I jxcore-log: 
,10-07 10:51:07.600  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection''
10-07 10:51:07.600  5639  5685 I jxcore-log: 
,10-07 10:51:07.654  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed', data: '{"uuid":"84c2835b-c215-46bc-bdfd-8a50353b2b7e"}''
10-07 10:51:07.654  5639  5685 I jxcore-log: 
,10-07 10:51:07.658  5639  5685 I jxcore-log: server is closing
10-07 10:51:07.658  5639  5685 I jxcore-log: 
,10-07 10:51:07.659  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:07.659  5639  5685 I jxcore-log: 
10-07 10:51:07.659  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:07.659  5639  5685 I jxcore-log: 
10-07 10:51:07.659  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:07.659  5639  5685 I jxcore-log: 
10-07 10:51:07.660  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished', data: '{"success":true}''
10-07 10:51:07.660  5639  5685 I jxcore-log: 
,10-07 10:51:07.665  5639  5685 I jxcore-log: # setup
10-07 10:51:07.665  5639  5685 I jxcore-log: 
,10-07 10:51:07.667  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500''
10-07 10:51:07.667  5639  5685 I jxcore-log: 
,10-07 10:51:07.722  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed', data: '{"uuid":"42606609-0f78-4a15-a755-0289e144380e"}''
10-07 10:51:07.722  5639  5685 I jxcore-log: 
,10-07 10:51:07.725  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished', data: '{"success":true}''
10-07 10:51:07.725  5639  5685 I jxcore-log: 
,10-07 10:51:07.729  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-07 10:51:07.729  5639  5685 I jxcore-log: 
,10-07 10:51:07.731  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500''
10-07 10:51:07.731  5639  5685 I jxcore-log: 
,10-07 10:51:07.813  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed', data: '{"uuid":"d48458f2-6814-4657-9423-7459a31d2d76","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:07.813  5639  5685 I jxcore-log: 
,10-07 10:51:07.943  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-07 10:51:07.943  5639  5685 I jxcore-log: 
,10-07 10:51:07.945  5639  5685 I jxcore-log: ok 47 Got 500 as expected
10-07 10:51:07.945  5639  5685 I jxcore-log: 
,10-07 10:51:07.946  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished', data: '{"success":true}''
10-07 10:51:07.946  5639  5685 I jxcore-log: 
,10-07 10:51:07.948  5639  5685 I jxcore-log: # teardown
10-07 10:51:07.948  5639  5685 I jxcore-log: 
,10-07 10:51:07.948  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500''
10-07 10:51:07.948  5639  5685 I jxcore-log: 
,10-07 10:51:07.982  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed', data: '{"uuid":"52bf10bc-985d-4a5f-807d-7cb3749e452b"}''
10-07 10:51:07.982  5639  5685 I jxcore-log: 
,10-07 10:51:07.985  5639  5685 I jxcore-log: server is closing
10-07 10:51:07.985  5639  5685 I jxcore-log: 
,10-07 10:51:07.985  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:07.985  5639  5685 I jxcore-log: 
10-07 10:51:07.986  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:07.986  5639  5685 I jxcore-log: 
,10-07 10:51:07.986  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:07.986  5639  5685 I jxcore-log: 
,10-07 10:51:07.988  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished', data: '{"success":true}''
10-07 10:51:07.988  5639  5685 I jxcore-log: 
,10-07 10:51:07.996  5639  5685 I jxcore-log: # setup
10-07 10:51:07.996  5639  5685 I jxcore-log: 
10-07 10:51:07.996  5639  5685 I jxcore-log: 2016-10-07 14:51:07 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc''
10-07 10:51:07.996  5639  5685 I jxcore-log: 
,10-07 10:51:08.075  5639  5685 I jxcore-log: 2016-10-07 14:51:08 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed', data: '{"uuid":"10afce5c-87b0-4705-aefa-2405db5b9c4a"}''
10-07 10:51:08.075  5639  5685 I jxcore-log: 
,10-07 10:51:08.081  5639  5685 I jxcore-log: 2016-10-07 14:51:08 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished', data: '{"success":true}''
10-07 10:51:08.081  5639  5685 I jxcore-log: 
,10-07 10:51:08.087  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-07 10:51:08.087  5639  5685 I jxcore-log: 
,10-07 10:51:08.099  5639  5685 I jxcore-log: 2016-10-07 14:51:08 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc''
10-07 10:51:08.099  5639  5685 I jxcore-log: 
,10-07 10:51:08.133  5639  5685 I jxcore-log: 2016-10-07 14:51:08 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed', data: '{"uuid":"ee33db2b-58c2-4c2e-b88d-5dfa606bbd62","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:08.133  5639  5685 I jxcore-log: 
,10-07 10:51:09.929  5639  5685 I jxcore-log: ok 48 should be equal
10-07 10:51:09.929  5639  5685 I jxcore-log: 
,10-07 10:51:09.930  5639  5685 I jxcore-log: ok 49 revs are equal
10-07 10:51:09.930  5639  5685 I jxcore-log: 
,10-07 10:51:09.932  5639  5685 I jxcore-log: 2016-10-07 14:51:09 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished', data: '{"success":true}''
10-07 10:51:09.932  5639  5685 I jxcore-log: 
,10-07 10:51:09.935  5639  5685 I jxcore-log: # teardown
10-07 10:51:09.935  5639  5685 I jxcore-log: 
,10-07 10:51:09.936  5639  5685 I jxcore-log: 2016-10-07 14:51:09 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc''
10-07 10:51:09.936  5639  5685 I jxcore-log: 
,10-07 10:51:09.977  5639  5685 I jxcore-log: 2016-10-07 14:51:09 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed', data: '{"uuid":"a4e057ef-529d-4190-b78a-5c714c5cadb6"}''
10-07 10:51:09.977  5639  5685 I jxcore-log: 
,10-07 10:51:09.984  5639  5685 I jxcore-log: server is closing
10-07 10:51:09.984  5639  5685 I jxcore-log: 
,10-07 10:51:09.985  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:09.985  5639  5685 I jxcore-log: 
10-07 10:51:09.985  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:09.985  5639  5685 I jxcore-log: 
,10-07 10:51:09.987  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:09.987  5639  5685 I jxcore-log: 
,10-07 10:51:09.991  5639  5685 I jxcore-log: 2016-10-07 14:51:09 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished', data: '{"success":true}''
10-07 10:51:09.991  5639  5685 I jxcore-log: 
,10-07 10:51:10.017  5639  5685 I jxcore-log: # setup
10-07 10:51:10.017  5639  5685 I jxcore-log: 
,10-07 10:51:10.018  5639  5685 I jxcore-log: 2016-10-07 14:51:10 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update''
10-07 10:51:10.018  5639  5685 I jxcore-log: 
,10-07 10:51:10.197  5639  5685 I jxcore-log: 2016-10-07 14:51:10 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed', data: '{"uuid":"4d3f181e-cc3d-4835-b795-9914f6651486"}''
10-07 10:51:10.197  5639  5685 I jxcore-log: 
,10-07 10:51:10.213  5639  5685 I jxcore-log: 2016-10-07 14:51:10 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished', data: '{"success":true}''
10-07 10:51:10.213  5639  5685 I jxcore-log: 
,10-07 10:51:10.222  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-07 10:51:10.222  5639  5685 I jxcore-log: 
,10-07 10:51:10.225  5639  5685 I jxcore-log: 2016-10-07 14:51:10 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update''
10-07 10:51:10.225  5639  5685 I jxcore-log: 
,10-07 10:51:10.287  5639  5685 I jxcore-log: 2016-10-07 14:51:10 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed', data: '{"uuid":"fcf20a18-2228-420c-90e3-4e8ed2ba24ae","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:10.287  5639  5685 I jxcore-log: 
,10-07 10:51:10.991  5639  5685 I jxcore-log: ok 50 should be equal
10-07 10:51:10.991  5639  5685 I jxcore-log: 
,10-07 10:51:10.991  5639  5685 I jxcore-log: ok 51 revs are equal
10-07 10:51:10.991  5639  5685 I jxcore-log: 
10-07 10:51:10.992  5639  5685 I jxcore-log: 2016-10-07 14:51:10 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished', data: '{"success":true}''
10-07 10:51:10.992  5639  5685 I jxcore-log: 
,10-07 10:51:10.996  5639  5685 I jxcore-log: # teardown
10-07 10:51:10.996  5639  5685 I jxcore-log: 
,10-07 10:51:10.996  5639  5685 I jxcore-log: 2016-10-07 14:51:10 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update''
10-07 10:51:10.996  5639  5685 I jxcore-log: 
,10-07 10:51:11.043  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed', data: '{"uuid":"5f0d56e7-9290-4c4b-88a2-76890d592cb7"}''
10-07 10:51:11.043  5639  5685 I jxcore-log: 
,10-07 10:51:11.051  5639  5685 I jxcore-log: server is closing
10-07 10:51:11.051  5639  5685 I jxcore-log: 
,10-07 10:51:11.052  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:11.052  5639  5685 I jxcore-log: 
,10-07 10:51:11.052  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:11.052  5639  5685 I jxcore-log: 
10-07 10:51:11.055  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:11.055  5639  5685 I jxcore-log: 
,10-07 10:51:11.060  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished', data: '{"success":true}''
10-07 10:51:11.060  5639  5685 I jxcore-log: 
,10-07 10:51:11.091  5639  5685 I jxcore-log: # setup
10-07 10:51:11.091  5639  5685 I jxcore-log: 
,10-07 10:51:11.092  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times''
10-07 10:51:11.092  5639  5685 I jxcore-log: 
,10-07 10:51:11.116  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed', data: '{"uuid":"6f225b5d-ffbe-4114-8bea-13c3c6cb7c5a"}''
10-07 10:51:11.116  5639  5685 I jxcore-log: 
,10-07 10:51:11.119  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished', data: '{"success":true}''
10-07 10:51:11.119  5639  5685 I jxcore-log: 
,10-07 10:51:11.123  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-07 10:51:11.123  5639  5685 I jxcore-log: 
,10-07 10:51:11.125  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times''
10-07 10:51:11.125  5639  5685 I jxcore-log: 
,10-07 10:51:11.203  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed', data: '{"uuid":"f5954afc-d181-4302-b063-0e46f04f0ce7","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:11.203  5639  5685 I jxcore-log: 
,10-07 10:51:11.710  5639  5685 I jxcore-log: ok 52 should be equal
10-07 10:51:11.710  5639  5685 I jxcore-log: 
,10-07 10:51:11.710  5639  5685 I jxcore-log: ok 53 revs are equal
10-07 10:51:11.710  5639  5685 I jxcore-log: 
,10-07 10:51:11.842  5639  5685 I jxcore-log: ok 54 should be equal
10-07 10:51:11.842  5639  5685 I jxcore-log: 
,10-07 10:51:11.842  5639  5685 I jxcore-log: ok 55 revs are equal
10-07 10:51:11.842  5639  5685 I jxcore-log: 
,10-07 10:51:11.954  5639  5685 I jxcore-log: ok 56 should be equal
10-07 10:51:11.954  5639  5685 I jxcore-log: 
,10-07 10:51:11.954  5639  5685 I jxcore-log: ok 57 revs are equal
10-07 10:51:11.954  5639  5685 I jxcore-log: 
10-07 10:51:11.955  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished', data: '{"success":true}''
10-07 10:51:11.955  5639  5685 I jxcore-log: 
,10-07 10:51:11.958  5639  5685 I jxcore-log: # teardown
10-07 10:51:11.958  5639  5685 I jxcore-log: 
,10-07 10:51:11.959  5639  5685 I jxcore-log: 2016-10-07 14:51:11 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times''
10-07 10:51:11.959  5639  5685 I jxcore-log: 
,10-07 10:51:12.007  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed', data: '{"uuid":"59da2341-40a8-474b-b371-f2a06d9b99be"}''
10-07 10:51:12.007  5639  5685 I jxcore-log: 
,10-07 10:51:12.013  5639  5685 I jxcore-log: server is closing
10-07 10:51:12.013  5639  5685 I jxcore-log: 
,10-07 10:51:12.015  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:12.015  5639  5685 I jxcore-log: 
,10-07 10:51:12.015  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:12.015  5639  5685 I jxcore-log: 
,10-07 10:51:12.018  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:12.018  5639  5685 I jxcore-log: 
,10-07 10:51:12.022  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished', data: '{"success":true}''
10-07 10:51:12.022  5639  5685 I jxcore-log: 
,10-07 10:51:12.049  5639  5685 I jxcore-log: # setup
10-07 10:51:12.049  5639  5685 I jxcore-log: 
,10-07 10:51:12.050  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us''
10-07 10:51:12.050  5639  5685 I jxcore-log: 
,10-07 10:51:12.056  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed', data: '{"uuid":"c3815f6a-1cb4-48a5-b8f8-c9b84fa3b30a"}''
10-07 10:51:12.056  5639  5685 I jxcore-log: 
,10-07 10:51:12.059  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished', data: '{"success":true}''
10-07 10:51:12.059  5639  5685 I jxcore-log: 
,10-07 10:51:12.063  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-07 10:51:12.063  5639  5685 I jxcore-log: 
,10-07 10:51:12.066  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us''
10-07 10:51:12.066  5639  5685 I jxcore-log: 
,10-07 10:51:12.193  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed', data: '{"uuid":"1430f97b-967b-491b-9ed0-417ca93cfb24","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:12.193  5639  5685 I jxcore-log: 
,10-07 10:51:12.767  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-07 10:51:12.767  5639  5685 I jxcore-log: 
,10-07 10:51:12.768  5639  5685 I jxcore-log: ok 58 Our rev is old so we should fail
10-07 10:51:12.768  5639  5685 I jxcore-log: 
10-07 10:51:12.769  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished', data: '{"success":true}''
10-07 10:51:12.769  5639  5685 I jxcore-log: 
,10-07 10:51:12.770  5639  5685 I jxcore-log: # teardown
10-07 10:51:12.770  5639  5685 I jxcore-log: 
,10-07 10:51:12.771  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us''
10-07 10:51:12.771  5639  5685 I jxcore-log: 
,10-07 10:51:12.826  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed', data: '{"uuid":"20016da6-1f42-489c-99b8-f235b3225c94"}''
10-07 10:51:12.826  5639  5685 I jxcore-log: 
,10-07 10:51:12.833  5639  5685 I jxcore-log: server is closing
10-07 10:51:12.833  5639  5685 I jxcore-log: 
10-07 10:51:12.834  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:12.834  5639  5685 I jxcore-log: 
10-07 10:51:12.834  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:12.834  5639  5685 I jxcore-log: 
,10-07 10:51:12.839  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:12.839  5639  5685 I jxcore-log: 
,10-07 10:51:12.842  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished', data: '{"success":true}''
10-07 10:51:12.842  5639  5685 I jxcore-log: 
,10-07 10:51:12.867  5639  5685 I jxcore-log: # setup
10-07 10:51:12.867  5639  5685 I jxcore-log: 
,10-07 10:51:12.868  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called''
10-07 10:51:12.868  5639  5685 I jxcore-log: 
,10-07 10:51:12.880  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed', data: '{"uuid":"0fa47931-04a0-4278-8963-93da3fb11f8e"}''
10-07 10:51:12.880  5639  5685 I jxcore-log: 
,10-07 10:51:12.884  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished', data: '{"success":true}''
10-07 10:51:12.884  5639  5685 I jxcore-log: 
,10-07 10:51:12.888  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-07 10:51:12.888  5639  5685 I jxcore-log: 
,10-07 10:51:12.891  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called''
10-07 10:51:12.891  5639  5685 I jxcore-log: 
,10-07 10:51:12.983  5639  5685 I jxcore-log: 2016-10-07 14:51:12 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed', data: '{"uuid":"15103899-af29-428d-b1fb-c7c6d7a9f632","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:12.983  5639  5685 I jxcore-log: 
,10-07 10:51:13.059  5639  5685 I jxcore-log: ok 59 confirm stop caused failure
10-07 10:51:13.059  5639  5685 I jxcore-log: 
,10-07 10:51:13.061  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished', data: '{"success":true}''
10-07 10:51:13.061  5639  5685 I jxcore-log: 
,10-07 10:51:13.068  5639  5685 I jxcore-log: # teardown
10-07 10:51:13.068  5639  5685 I jxcore-log: 
,10-07 10:51:13.069  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called''
10-07 10:51:13.069  5639  5685 I jxcore-log: 
,10-07 10:51:13.092  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed', data: '{"uuid":"79b39bd8-d3a5-4085-ba21-d0366ea9d422"}''
10-07 10:51:13.092  5639  5685 I jxcore-log: 
,10-07 10:51:13.097  5639  5685 I jxcore-log: server is closing
10-07 10:51:13.097  5639  5685 I jxcore-log: 
,10-07 10:51:13.097  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:13.097  5639  5685 I jxcore-log: 
10-07 10:51:13.097  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:13.097  5639  5685 I jxcore-log: 
10-07 10:51:13.097  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:13.097  5639  5685 I jxcore-log: 
,10-07 10:51:13.099  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished', data: '{"success":true}''
10-07 10:51:13.099  5639  5685 I jxcore-log: 
,10-07 10:51:13.103  5639  5685 I jxcore-log: # setup
10-07 10:51:13.103  5639  5685 I jxcore-log: 
,10-07 10:51:13.104  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right''
10-07 10:51:13.104  5639  5685 I jxcore-log: 
,10-07 10:51:13.164  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed', data: '{"uuid":"d7a0a247-302f-49d6-9c44-a25dcf2e5dce"}''
10-07 10:51:13.164  5639  5685 I jxcore-log: 
,10-07 10:51:13.169  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished', data: '{"success":true}''
10-07 10:51:13.169  5639  5685 I jxcore-log: 
,10-07 10:51:13.175  5639  5685 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-07 10:51:13.175  5639  5685 I jxcore-log: 
,10-07 10:51:13.179  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right''
10-07 10:51:13.179  5639  5685 I jxcore-log: 
,10-07 10:51:13.251  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed', data: '{"uuid":"378bf283-3605-4f0e-96ec-5530af13a9d1","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:13.251  5639  5685 I jxcore-log: 
,10-07 10:51:13.540  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-07 10:51:13.540  5639  5685 I jxcore-log: 
,10-07 10:51:13.542  5639  5685 I jxcore-log: ok 60 stop caused us to fail
10-07 10:51:13.542  5639  5685 I jxcore-log: 
,10-07 10:51:13.543  5639  5685 I jxcore-log: ok 61 We specifically failed on a stop before put
10-07 10:51:13.543  5639  5685 I jxcore-log: 
,10-07 10:51:13.544  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished', data: '{"success":true}''
10-07 10:51:13.544  5639  5685 I jxcore-log: 
,10-07 10:51:13.546  5639  5685 I jxcore-log: # teardown
10-07 10:51:13.546  5639  5685 I jxcore-log: 
,10-07 10:51:13.547  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right''
10-07 10:51:13.547  5639  5685 I jxcore-log: 
,10-07 10:51:13.596  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed', data: '{"uuid":"450e30ca-2f49-488d-b68a-4a23b9b108a8"}''
10-07 10:51:13.596  5639  5685 I jxcore-log: 
,10-07 10:51:13.599  5639  5685 I jxcore-log: server is closing
10-07 10:51:13.599  5639  5685 I jxcore-log: 
10-07 10:51:13.600  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:13.600  5639  5685 I jxcore-log: 
10-07 10:51:13.600  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:13.600  5639  5685 I jxcore-log: 
10-07 10:51:13.601  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:13.601  5639  5685 I jxcore-log: 
,10-07 10:51:13.605  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished', data: '{"success":true}''
10-07 10:51:13.605  5639  5685 I jxcore-log: 
,10-07 10:51:13.616  5639  5685 I jxcore-log: # setup
10-07 10:51:13.616  5639  5685 I jxcore-log: 
,10-07 10:51:13.617  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#update - fail if stop is called''
10-07 10:51:13.617  5639  5685 I jxcore-log: 
,10-07 10:51:13.647  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - fail if stop is called_confirmed', data: '{"uuid":"fda5567e-3e76-4bf5-95d8-e855333336ee"}''
10-07 10:51:13.647  5639  5685 I jxcore-log: 
,10-07 10:51:13.650  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - fail if stop is called_finished', data: '{"success":true}''
10-07 10:51:13.650  5639  5685 I jxcore-log: 
,10-07 10:51:13.653  5639  5685 I jxcore-log: # #update - fail if stop is called
10-07 10:51:13.653  5639  5685 I jxcore-log: 
,10-07 10:51:13.655  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#update - fail if stop is called''
10-07 10:51:13.655  5639  5685 I jxcore-log: 
,10-07 10:51:13.746  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - fail if stop is called_confirmed', data: '{"uuid":"d3b33575-e739-4c89-b4f3-642060c8add0","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:13.746  5639  5685 I jxcore-log: 
,10-07 10:51:13.793  5639  5685 I jxcore-log: ok 62 failed due to stop
10-07 10:51:13.793  5639  5685 I jxcore-log: 
,10-07 10:51:13.796  5639  5685 I jxcore-log: ok 63 failed due to stop
10-07 10:51:13.796  5639  5685 I jxcore-log: 
,10-07 10:51:13.797  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - fail if stop is called_finished', data: '{"success":true}''
10-07 10:51:13.797  5639  5685 I jxcore-log: 
,10-07 10:51:13.805  5639  5685 I jxcore-log: # teardown
10-07 10:51:13.805  5639  5685 I jxcore-log: 
,10-07 10:51:13.805  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#update - fail if stop is called''
10-07 10:51:13.805  5639  5685 I jxcore-log: 
,10-07 10:51:13.865  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - fail if stop is called_confirmed', data: '{"uuid":"07dd975c-33a8-4b2a-8b03-e58ca7210bfa"}''
10-07 10:51:13.865  5639  5685 I jxcore-log: 
,10-07 10:51:13.880  5639  5685 I jxcore-log: server is closing
10-07 10:51:13.880  5639  5685 I jxcore-log: 
,10-07 10:51:13.881  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:13.881  5639  5685 I jxcore-log: 
,10-07 10:51:13.882  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:13.882  5639  5685 I jxcore-log: 
10-07 10:51:13.882  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:13.882  5639  5685 I jxcore-log: 
,10-07 10:51:13.887  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - fail if stop is called_finished', data: '{"success":true}''
10-07 10:51:13.887  5639  5685 I jxcore-log: 
,10-07 10:51:13.893  5639  5685 I jxcore-log: # setup
10-07 10:51:13.893  5639  5685 I jxcore-log: 
,10-07 10:51:13.894  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#update - set seq for first time''
10-07 10:51:13.894  5639  5685 I jxcore-log: 
,10-07 10:51:13.928  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - set seq for first time_confirmed', data: '{"uuid":"6a66b08c-d1a3-4eed-9993-cb5cc0766f74"}''
10-07 10:51:13.928  5639  5685 I jxcore-log: 
,10-07 10:51:13.932  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - set seq for first time_finished', data: '{"success":true}''
10-07 10:51:13.932  5639  5685 I jxcore-log: 
,10-07 10:51:13.934  5639  5685 I jxcore-log: # #update - set seq for first time
10-07 10:51:13.934  5639  5685 I jxcore-log: 
,10-07 10:51:13.937  5639  5685 I jxcore-log: 2016-10-07 14:51:13 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#update - set seq for first time''
10-07 10:51:13.937  5639  5685 I jxcore-log: 
,10-07 10:51:14.016  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - set seq for first time_confirmed', data: '{"uuid":"6489f644-bbaf-4ea6-b22c-5669b1ce0fbe","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:14.016  5639  5685 I jxcore-log: 
,10-07 10:51:14.415  5639  5685 I jxcore-log: ok 64 should be equal
10-07 10:51:14.415  5639  5685 I jxcore-log: 
,10-07 10:51:14.417  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - set seq for first time_finished', data: '{"success":true}''
10-07 10:51:14.417  5639  5685 I jxcore-log: 
,10-07 10:51:14.420  5639  5685 I jxcore-log: # teardown
10-07 10:51:14.420  5639  5685 I jxcore-log: 
,10-07 10:51:14.421  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#update - set seq for first time''
10-07 10:51:14.421  5639  5685 I jxcore-log: 
,10-07 10:51:14.528  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - set seq for first time_confirmed', data: '{"uuid":"52b4efe2-848b-483b-bc62-c9380803d180"}''
10-07 10:51:14.528  5639  5685 I jxcore-log: 
,10-07 10:51:14.541  5639  5685 I jxcore-log: server is closing
10-07 10:51:14.541  5639  5685 I jxcore-log: 
,10-07 10:51:14.542  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:14.542  5639  5685 I jxcore-log: 
10-07 10:51:14.542  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:14.542  5639  5685 I jxcore-log: 
,10-07 10:51:14.544  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:14.544  5639  5685 I jxcore-log: 
10-07 10:51:14.549  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - set seq for first time_finished', data: '{"success":true}''
10-07 10:51:14.549  5639  5685 I jxcore-log: 
,10-07 10:51:14.570  5639  5685 I jxcore-log: # setup
10-07 10:51:14.570  5639  5685 I jxcore-log: 
,10-07 10:51:14.572  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#update - Fail on bad seq value''
10-07 10:51:14.572  5639  5685 I jxcore-log: 
,10-07 10:51:14.596  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - Fail on bad seq value_confirmed', data: '{"uuid":"d50233e3-6bed-4d5b-9819-2d3df10e1f87"}''
10-07 10:51:14.596  5639  5685 I jxcore-log: 
,10-07 10:51:14.601  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - Fail on bad seq value_finished', data: '{"success":true}''
10-07 10:51:14.601  5639  5685 I jxcore-log: 
,10-07 10:51:14.605  5639  5685 I jxcore-log: # #update - Fail on bad seq value
10-07 10:51:14.605  5639  5685 I jxcore-log: 
,10-07 10:51:14.606  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#update - Fail on bad seq value''
10-07 10:51:14.606  5639  5685 I jxcore-log: 
,10-07 10:51:14.670  5639  5685 I jxcore-log: 2016-10-07 14:51:14 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - Fail on bad seq value_confirmed', data: '{"uuid":"9be58701-14a9-40b1-a1dd-4f9991d62ae2","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:14.670  5639  5685 I jxcore-log: 
,10-07 10:51:15.004  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-07 10:51:15.004  5639  5685 I jxcore-log: 
,10-07 10:51:15.006  5639  5685 I jxcore-log: ok 65 Expected bad seq error
10-07 10:51:15.006  5639  5685 I jxcore-log: 
10-07 10:51:15.007  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - Fail on bad seq value_finished', data: '{"success":true}''
10-07 10:51:15.007  5639  5685 I jxcore-log: 
10-07 10:51:15.009  5639  5685 I jxcore-log: # teardown
10-07 10:51:15.009  5639  5685 I jxcore-log: 
10-07 10:51:15.010  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#update - Fail on bad seq value''
10-07 10:51:15.010  5639  5685 I jxcore-log: 
,10-07 10:51:15.083  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value_confirmed', data: '{"uuid":"6d4fc8bd-245d-47de-a5fd-7652c104853d"}''
10-07 10:51:15.083  5639  5685 I jxcore-log: 
,10-07 10:51:15.088  5639  5685 I jxcore-log: server is closing
10-07 10:51:15.088  5639  5685 I jxcore-log: 
10-07 10:51:15.088  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:15.088  5639  5685 I jxcore-log: 
10-07 10:51:15.089  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:15.089  5639  5685 I jxcore-log: 
10-07 10:51:15.090  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:15.090  5639  5685 I jxcore-log: 
10-07 10:51:15.092  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value_finished', data: '{"success":true}''
10-07 10:51:15.092  5639  5685 I jxcore-log: 
,10-07 10:51:15.104  5639  5685 I jxcore-log: # setup
10-07 10:51:15.104  5639  5685 I jxcore-log: 
,10-07 10:51:15.105  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?''
10-07 10:51:15.105  5639  5685 I jxcore-log: 
,10-07 10:51:15.168  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed', data: '{"uuid":"864ac994-6b22-4b1b-b8cb-cbc09c26741b"}''
10-07 10:51:15.168  5639  5685 I jxcore-log: 
,10-07 10:51:15.176  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?_finished', data: '{"success":true}''
10-07 10:51:15.176  5639  5685 I jxcore-log: 
,10-07 10:51:15.182  5639  5685 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-07 10:51:15.182  5639  5685 I jxcore-log: 
,10-07 10:51:15.187  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?''
10-07 10:51:15.187  5639  5685 I jxcore-log: 
,10-07 10:51:15.242  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed', data: '{"uuid":"b178a191-2401-4a46-a1d0-1580edfad014","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:15.242  5639  5685 I jxcore-log: 
,10-07 10:51:15.443   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:15.639  5639  5685 I jxcore-log: ok 66 Different promises
10-07 10:51:15.639  5639  5685 I jxcore-log: 
,10-07 10:51:15.642  5639  5685 I jxcore-log: ok 67 Timer was cancelled
10-07 10:51:15.642  5639  5685 I jxcore-log: 
,10-07 10:51:15.787  5639  5685 I jxcore-log: ok 68 should be equal
10-07 10:51:15.787  5639  5685 I jxcore-log: 
,10-07 10:51:15.788  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?_finished', data: '{"success":true}''
10-07 10:51:15.788  5639  5685 I jxcore-log: 
,10-07 10:51:15.792  5639  5685 I jxcore-log: # teardown
10-07 10:51:15.792  5639  5685 I jxcore-log: 
,10-07 10:51:15.793  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?''
10-07 10:51:15.793  5639  5685 I jxcore-log: 
,10-07 10:51:15.829  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed', data: '{"uuid":"056476fc-7404-48fa-93ff-74fb44b8948f"}''
10-07 10:51:15.829  5639  5685 I jxcore-log: 
,10-07 10:51:15.836  5639  5685 I jxcore-log: server is closing
10-07 10:51:15.836  5639  5685 I jxcore-log: 
,10-07 10:51:15.836  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:15.836  5639  5685 I jxcore-log: 
10-07 10:51:15.837  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:15.837  5639  5685 I jxcore-log: 
,10-07 10:51:15.840  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:15.840  5639  5685 I jxcore-log: 
,10-07 10:51:15.843  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished', data: '{"success":true}''
10-07 10:51:15.843  5639  5685 I jxcore-log: 
,10-07 10:51:15.865  5639  5685 I jxcore-log: # setup
10-07 10:51:15.865  5639  5685 I jxcore-log: 
,10-07 10:51:15.866  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#update - do we wait for blocked update''
10-07 10:51:15.866  5639  5685 I jxcore-log: 
,10-07 10:51:15.910  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - do we wait for blocked update_confirmed', data: '{"uuid":"64187c51-f766-44a7-89d7-1b0fc02d2a3b"}''
10-07 10:51:15.910  5639  5685 I jxcore-log: 
,10-07 10:51:15.917  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - do we wait for blocked update_finished', data: '{"success":true}''
10-07 10:51:15.917  5639  5685 I jxcore-log: 
,10-07 10:51:15.925  5639  5685 I jxcore-log: # #update - do we wait for blocked update
10-07 10:51:15.925  5639  5685 I jxcore-log: 
,10-07 10:51:15.929  5639  5685 I jxcore-log: 2016-10-07 14:51:15 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#update - do we wait for blocked update''
10-07 10:51:15.929  5639  5685 I jxcore-log: 
,10-07 10:51:16.014  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - do we wait for blocked update_confirmed', data: '{"uuid":"edc2de0d-07e9-4e79-bde9-854823855a1e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:16.014  5639  5685 I jxcore-log: 
,10-07 10:51:16.096  5639  5685 I jxcore-log: ok 69 One go and one blocked
10-07 10:51:16.096  5639  5685 I jxcore-log: 
10-07 10:51:16.096  5639  5685 I jxcore-log: ok 70 All blocked
10-07 10:51:16.096  5639  5685 I jxcore-log: 
10-07 10:51:16.097  5639  5685 I jxcore-log: ok 71 Still blocked
10-07 10:51:16.097  5639  5685 I jxcore-log: 
,10-07 10:51:16.443   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:16.520  5639  5685 I jxcore-log: ok 72 should be equal
10-07 10:51:16.520  5639  5685 I jxcore-log: 
,10-07 10:51:16.523  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - do we wait for blocked update_finished', data: '{"success":true}''
10-07 10:51:16.523  5639  5685 I jxcore-log: 
,10-07 10:51:16.527  5639  5685 I jxcore-log: # teardown
10-07 10:51:16.527  5639  5685 I jxcore-log: 
,10-07 10:51:16.528  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#update - do we wait for blocked update''
10-07 10:51:16.528  5639  5685 I jxcore-log: 
,10-07 10:51:16.560  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update_confirmed', data: '{"uuid":"04c41e68-7bdf-4e87-98e0-60a57c36359c"}''
10-07 10:51:16.560  5639  5685 I jxcore-log: 
,10-07 10:51:16.573  5639  5685 I jxcore-log: server is closing
10-07 10:51:16.573  5639  5685 I jxcore-log: 
10-07 10:51:16.573  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:16.573  5639  5685 I jxcore-log: 
,10-07 10:51:16.573  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:16.573  5639  5685 I jxcore-log: 
,10-07 10:51:16.575  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:16.575  5639  5685 I jxcore-log: 
,10-07 10:51:16.577  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update_finished', data: '{"success":true}''
10-07 10:51:16.577  5639  5685 I jxcore-log: 
,10-07 10:51:16.605  5639  5685 I jxcore-log: # setup
10-07 10:51:16.605  5639  5685 I jxcore-log: 
,10-07 10:51:16.605  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#update - test that we wait long enough''
10-07 10:51:16.605  5639  5685 I jxcore-log: 
,10-07 10:51:16.634  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - test that we wait long enough_confirmed', data: '{"uuid":"c6b8b7fe-0467-4068-937d-5d090dad849e"}''
10-07 10:51:16.634  5639  5685 I jxcore-log: 
,10-07 10:51:16.639  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - test that we wait long enough_finished', data: '{"success":true}''
10-07 10:51:16.639  5639  5685 I jxcore-log: 
,10-07 10:51:16.652  5639  5685 I jxcore-log: # #update - test that we wait long enough
10-07 10:51:16.652  5639  5685 I jxcore-log: 
,10-07 10:51:16.680  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#update - test that we wait long enough''
10-07 10:51:16.680  5639  5685 I jxcore-log: 
,10-07 10:51:16.723  5639  5685 I jxcore-log: 2016-10-07 14:51:16 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - test that we wait long enough_confirmed', data: '{"uuid":"281f77cf-8e6f-4e99-ba70-9503a8938b99","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:16.723  5639  5685 I jxcore-log: 
,10-07 10:51:17.444   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:17.888  5639  5685 I jxcore-log: ok 73 We waited long enough
10-07 10:51:17.888  5639  5685 I jxcore-log: 
,10-07 10:51:18.014  5639  5685 I jxcore-log: ok 74 should be equal
10-07 10:51:18.014  5639  5685 I jxcore-log: 
,10-07 10:51:18.015  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - test that we wait long enough_finished', data: '{"success":true}''
10-07 10:51:18.015  5639  5685 I jxcore-log: 
,10-07 10:51:18.017  5639  5685 I jxcore-log: # teardown
10-07 10:51:18.017  5639  5685 I jxcore-log: 
,10-07 10:51:18.018  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#update - test that we wait long enough''
10-07 10:51:18.018  5639  5685 I jxcore-log: 
,10-07 10:51:18.121  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - test that we wait long enough_confirmed', data: '{"uuid":"8e249cfc-6576-41a6-8013-70b776610ec5"}''
10-07 10:51:18.121  5639  5685 I jxcore-log: 
,10-07 10:51:18.128  5639  5685 I jxcore-log: server is closing
10-07 10:51:18.128  5639  5685 I jxcore-log: 
,10-07 10:51:18.129  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:18.129  5639  5685 I jxcore-log: 
10-07 10:51:18.129  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:18.129  5639  5685 I jxcore-log: 
,10-07 10:51:18.132  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:18.132  5639  5685 I jxcore-log: 
,10-07 10:51:18.136  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - test that we wait long enough_finished', data: '{"success":true}''
10-07 10:51:18.136  5639  5685 I jxcore-log: 
,10-07 10:51:18.159  5639  5685 I jxcore-log: # setup
10-07 10:51:18.159  5639  5685 I jxcore-log: 
,10-07 10:51:18.160  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait''
10-07 10:51:18.160  5639  5685 I jxcore-log: 
,10-07 10:51:18.192  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed', data: '{"uuid":"1aa8c18a-1c96-4c79-8247-4fe98f245ceb"}''
10-07 10:51:18.192  5639  5685 I jxcore-log: 
,10-07 10:51:18.199  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait_finished', data: '{"success":true}''
10-07 10:51:18.199  5639  5685 I jxcore-log: 
,10-07 10:51:18.206  5639  5685 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-07 10:51:18.206  5639  5685 I jxcore-log: 
,10-07 10:51:18.209  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait''
10-07 10:51:18.209  5639  5685 I jxcore-log: 
,10-07 10:51:18.265  5639  5685 I jxcore-log: 2016-10-07 14:51:18 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait_confirmed', data: '{"uuid":"2386d749-585a-47f2-926d-a2159ca2c410","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
10-07 10:51:18.265  5639  5685 I jxcore-log: 
,10-07 10:51:18.445   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:18.642  5639  5685 I jxcore-log: ok 75 Should have gotten same timer promise
10-07 10:51:18.642  5639  5685 I jxcore-log: 
,10-07 10:51:18.642  5639  5685 I jxcore-log: ok 76 Still same timer promise
10-07 10:51:18.642  5639  5685 I jxcore-log: 
,10-07 10:51:18.882   927  2954 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 10:51:19.425  5639  5685 I jxcore-log: ok 77 We waited long enough
10-07 10:51:19.425  5639  5685 I jxcore-log: 
,10-07 10:51:19.446   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:19.499  5639  5685 I jxcore-log: ok 78 should be equal
10-07 10:51:19.499  5639  5685 I jxcore-log: 
,10-07 10:51:19.500  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait_finished', data: '{"success":true}''
10-07 10:51:19.500  5639  5685 I jxcore-log: 
10-07 10:51:19.503  5639  5685 I jxcore-log: # teardown
10-07 10:51:19.503  5639  5685 I jxcore-log: 
10-07 10:51:19.503  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait''
10-07 10:51:19.503  5639  5685 I jxcore-log: 
,10-07 10:51:19.589  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed', data: '{"uuid":"ca59a6ab-b1ee-4563-8d21-8333e4c71047"}''
10-07 10:51:19.589  5639  5685 I jxcore-log: 
,10-07 10:51:19.594  5639  5685 I jxcore-log: server is closing
10-07 10:51:19.594  5639  5685 I jxcore-log: 
10-07 10:51:19.594  5639  5685 I jxcore-log: server was closed without error
10-07 10:51:19.594  5639  5685 I jxcore-log: 
10-07 10:51:19.594  5639  5685 I jxcore-log: server is closing connections
10-07 10:51:19.594  5639  5685 I jxcore-log: 
10-07 10:51:19.596  5639  5685 I jxcore-log: server was closed connections without error
10-07 10:51:19.596  5639  5685 I jxcore-log: 
,10-07 10:51:19.598  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait_finished', data: '{"success":true}''
10-07 10:51:19.598  5639  5685 I jxcore-log: 
,10-07 10:51:19.618  5639  5685 I jxcore-log: # setup
10-07 10:51:19.618  5639  5685 I jxcore-log: 
,10-07 10:51:19.619  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are waiting for event: 'setup_Coordinated seq test''
10-07 10:51:19.619  5639  5685 I jxcore-log: 
,10-07 10:51:19.673  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_Coordinated seq test_confirmed', data: '{"uuid":"8f104aa9-4592-4069-958d-3057982360ed"}''
10-07 10:51:19.673  5639  5685 I jxcore-log: 
,10-07 10:51:19.709  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are emitting data for event: 'setup_Coordinated seq test_finished', data: '{"success":true,"data":[4,161,207,4,87,39,129,101,238,62,80,166,85,125,90,180,9,57,150,171,139,11,241,22,247,66,174,165,112,54,36,21,113,203,255,80,70,17,72,219,196,163,61,145,20,4,70,73,30,41,130,228,53,57,91,27,200,230,120,171,223,128,163,158,241]}''
10-07 10:51:19.709  5639  5685 I jxcore-log: 
,10-07 10:51:19.716  5639  5685 I jxcore-log: # Coordinated seq test
10-07 10:51:19.716  5639  5685 I jxcore-log: 
,10-07 10:51:19.718  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are waiting for event: 'run_Coordinated seq test''
10-07 10:51:19.718  5639  5685 I jxcore-log: 
,10-07 10:51:19.820  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_Coordinated seq test_confirmed', data: '{"uuid":"48a1ec86-97d5-4789-a7e7-af826e10dad3","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31","data":[4,13,2,237,65,107,95,43,25,150,7,81,216,172,217,146,13,25,143,47,92,228,230,207,74,101,202,139,180,102,88,214,109,106,199,86,243,1,201,221,213,232,91,169,96,149,233,196,50,233,166,165,125,176,11,109,33,244,144,10,240,108,44,62,158]},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89","data":[4,138,110,77,59,243,2,252,183,176,15,78,90,206,73,47,234,153,195,144,153,249,192,31,121,73,93,151,43,147,141,30,247,251,230,44,11,228,28,127,158,82,84,3,249,113,221,73,228,193,244,85,21,79,221,249,33,19,113,98,114,70,218,47,38]},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5","data":[4,161,207,4,87,39,129,101,238,62,80,166,85,125,90,180,9,57,150,171,139,11,241,22,247,66,174,165,112,54,36,21,113,203,255,80,70,17,72,219,196,163,61,145,20,4,70,73,30,41,130,228,53,57,91,27,200,230,120,171,223,128,
,10-07 10:51:19.967  5639  5685 I jxcore-log: 2016-10-07 14:51:19 - DEBUG thaliWifiInfrastructure: 'listening 44516'
10-07 10:51:19.967  5639  5685 I jxcore-log: 
,10-07 10:51:20.446   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-07 10:51:22.358  5639  5685 I jxcore-log: ok 79 should be equal
10-07 10:51:22.358  5639  5685 I jxcore-log: 
,10-07 10:51:22.375  5639  5685 I jxcore-log: ok 80 should be equal
10-07 10:51:22.375  5639  5685 I jxcore-log: 
,10-07 10:51:22.384  5639  5685 I jxcore-log: 2016-10-07 14:51:22 - DEBUG CoordinatedClient: 'we are emitting data for event: 'run_Coordinated seq test_finished', data: '{"success":true}''
10-07 10:51:22.384  5639  5685 I jxcore-log: 
,10-07 10:51:22.388  5639  5685 I jxcore-log: # teardown
10-07 10:51:22.388  5639  5685 I jxcore-log: 
,10-07 10:51:22.389  5639  5685 I jxcore-log: 2016-10-07 14:51:22 - DEBUG CoordinatedClient: 'we are waiting for event: 'teardown_Coordinated seq test''
10-07 10:51:22.389  5639  5685 I jxcore-log: 
,10-07 10:51:25.447   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:26.449   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:27.450   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:28.451   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:29.453   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:30.453   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-07 10:51:38.886   927  2954 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 10:51:39.535   927  5962 D NetlinkSocketObserver: NeighborEvent{elapsedMs=368554, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-07 10:51:40.455   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:41.456   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:42.458   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:43.459   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:44.460   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:51:45.461   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-07 10:52:00.462   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:52:01.464   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:52:02.465   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:52:03.466   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:52:04.468   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 10:52:05.468   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-07 10:52:12.992   927  5962 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,10-07 10:52:18.889   927  2954 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 10:52:22.407  5639  5685 I jxcore-log: 2016-10-07 14:52:22 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-07 10:52:22.407  5639  5685 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-07 10:52:22.407  5639  5685 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-07 10:52:22.407  5639  5685 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-07 10:52:22.407  5639  5685 I jxcore-log:     at $9@timers.js:120:1
10-07 10:52:22.407  5639  5685 I jxcore-log: ''
10-07 10:52:22.407  5639  5685 I jxcore-log: 
,10-07 10:52:22.410  5639  5685 I jxcore-log: 2016-10-07 14:52:22 - DEBUG CoordinatedClient: 'test client failed'
10-07 10:52:22.410  5639  5685 I jxcore-log: 
,10-07 10:52:22.422  5639  5685 I jxcore-log: 2016-10-07 14:52:22 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-07 10:52:22.422  5639  5685 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-07 10:52:22.422  5639  5685 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-07 10:52:22.422  5639  5685 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-07 10:52:22.422  5639  5685 I jxcore-log:     at $9@timers.js:120:1
10-07 10:52:22.422  5639  5685 I jxcore-log: ''
10-07 10:52:22.422  5639  5685 I jxcore-log: 
,10-07 10:52:22.424  5639  5685 I jxcore-log: 2016-10-07 14:52:22 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-07 10:52:22.424  5639  5685 I jxcore-log: 
,10-07 10:52:22.495   927  2887 W InputDispatcher: channel '383b53e com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-07 10:52:22.495   927  2887 E InputDispatcher: channel '383b53e com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-07 10:52:22.505   927  3806 I WindowState: WIN DEATH: Window{383b53e u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-07 10:52:22.505   927  3806 W InputDispatcher: Attempted to unregister already unregistered input channel '383b53e com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-07 10:52:22.506   927  2969 D WifiService: Client connection lost with reason: 4
10-07 10:52:22.508   527   527 I Zygote  : Process 5639 exited cleanly (139)
,10-07 10:52:22.508   927  3096 D GraphicsStats: Buffer count: 2
,10-07 10:52:22.511   927  3803 I ActivityManager: Process com.test.thalitest (pid 5639) has died
,10-07 10:52:22.540   927  3803 I ActivityManager: Start proc 6002:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-07 10:52:22.873   927   937 I WindowManager: Screenshot max retries 4 of Token{5cf2260 ActivityRecord{31e5663 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{8323da4 u0 Starting com.test.thalitest} drawState=4
,10-07 10:52:22.945  6000  6000 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-07 10:52:22.951  6000  6000 D AndroidRuntime: CheckJNI is OFF
,10-07 10:52:22.959  6002  6002 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-07 10:52:22.977  6002  6002 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-07 10:52:22.981  6000  6000 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-07 10:52:22.982  6002  6002 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1999-2001)
,10-07 10:52:22.982  6002  6002 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-07 10:52:22.991  6002  6002 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {de2d347}
10-07 10:52:22.992  6002  6002 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-07 10:52:22.992  6002  6002 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-07 10:52:22.995  6002  6002 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-07 10:52:22.996  6002  6002 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-07 10:52:23.004  6000  6000 I Radio-JNI: register_android_hardware_Radio DONE
,10-07 10:52:23.006  6002  6002 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-07 10:52:23.013  6002  6002 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-07 10:52:23.014  6002  6002 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-07 10:52:23.014  6002  6002 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-07 10:52:23.014  6002  6002 I Adreno  : Build Date                       : 12/06/15
10-07 10:52:23.014  6002  6002 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-07 10:52:23.014  6002  6002 I Adreno  : Local Branch                     : mybranch17112971
10-07 10:52:23.014  6002  6002 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-07 10:52:23.014  6002  6002 I Adreno  : Remote Branch                    : NONE
10-07 10:52:23.014  6002  6002 I Adreno  : Reconstruct Branch               : NOTHING
,10-07 10:52:23.019  6000  6000 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-07 10:52:23.025   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-07 10:52:23.025   927   940 I ActivityManager: Killing 6002:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-07 10:52:23.145   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-07 10:52:23.146   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-07 10:52:23.148   927   952 I art     : Starting a blocking GC Explicit
,10-07 10:52:23.148   927   940 E ActivityManager: Failure starting process com.test.thalitest
10-07 10:52:23.148   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-07 10:52:23.148   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.148   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.148   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 10:52:23.148   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-07 10:52:23.152   927   940 I ActivityManager:   Force finishing activity ActivityRecord{31e5663 u0 com.test.thalitest/.MainActivity t2}
,10-07 10:52:23.165   927   945 W WindowManager: Failed looking up window
10-07 10:52:23.165   927   945 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@a638437 does not exist
10-07 10:52:23.165   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-07 10:52:23.165   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-07 10:52:23.165   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-07 10:52:23.165   927   945 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-07 10:52:23.165   927   945 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-07 10:52:23.165   927   945 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-07 10:52:23.165   927   945 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-07 10:52:23.165   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.165   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.165   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 10:52:23.165   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-07 10:52:23.167   927  3785 W ActivityManager: Spurious death for ProcessRecord{8279010 0:com.test.thalitest/u0a77}, curProc for 6002: null
,10-07 10:52:23.245   927   952 I art     : Explicit concurrent mark sweep GC freed 83941(6MB) AllocSpace objects, 41(1628KB) LOS objects, 33% free, 29MB/43MB, paused 1.581ms total 96.818ms
,10-07 10:52:23.266   927   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-07 10:52:23.269  6000  6000 I art     : System.exit called, status: 0
10-07 10:52:23.270  6000  6000 I AndroidRuntime: VM exiting with result code 0.
,10-07 10:52:23.284   927   952 I ActivityManager: Start proc 6028:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
10-07 10:52:23.284   927   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-07 10:52:23.292   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-07 10:52:23.296  5904  5904 D BluetoothMapAppObserver: onReceive
10-07 10:52:23.296  5904  5904 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-07 10:52:23.298  4029  4146 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-07 10:52:23.298  3612  3612 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-07 10:52:23.301   927  2888 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-07 10:52:23.326  3612  6039 I Keyboard.Facilitator.DecoderInitializer: run()
,10-07 10:52:23.332  3349  6041 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-07 10:52:23.345  3612  6039 I Decoder : createOrResetDecoder
,10-07 10:52:23.360  3727  3727 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-07 10:52:23.374  3529  3529 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-07 10:52:23.374  3529  3529 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
10-07 10:52:23.375    17    17 W kworker/2:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 10:52:23.380   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-07 10:52:23.378    17    17 W kworker/2:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 10:52:23.385    17    17 W kworker/2:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 10:52:23.391  3832  6048 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-07 10:52:23.391  3832  6048 D AccountUtils: Clearing selected account for com.test.thalitest
,10-07 10:52:23.394  3769  3879 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-07 10:52:23.395   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,10-07 10:52:23.396   927   939 E PackageManager: Failed to write settings, restoring backup
10-07 10:52:23.396   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-07 10:52:23.396   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-07 10:52:23.396   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-07 10:52:23.396   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-07 10:52:23.396   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-07 10:52:23.396   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.396   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.396   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-07 10:52:23.398   927   940 E DropBoxManagerService: Can't write: system_server_wtf
10-07 10:52:23.398   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-07 10:52:23.398   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 10:52:23.398   927   940 E DropBoxManagerService: 	... 13 more
,10-07 10:52:23.405  3349  3372 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj6CE1B0974) - 
,--------- beginning of crash
10-07 10:52:23.406  3349  3372 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-07 10:52:23.406  3349  3372 E AndroidRuntime: Process: android.process.acore, PID: 3349
10-07 10:52:23.406  3349  3372 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.406  3349  3372 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-07 10:52:23.408   927  3364 I ActivityManager: Start proc 6051:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
10-07 10:52:23.408  3769  3879 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-07 10:52:23.408  3769  3879 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3769
10-07 10:52:23.408  3769  3879 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.408  3769  3879 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-07 10:52:23.414   927  3096 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-07 10:52:23.416   927  6056 E DropBoxManagerService: Can't write: system_app_crash
10-07 10:52:23.416   927  6056 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 10:52:23.416   927  6056 E DropBoxManagerService: 	... 5 more
10-07 10:52:23.417   927  6060 E DropBoxManagerService: Can't write: system_app_crash
10-07 10:52:23.417   927  6060 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 10:52:23.417   927  6060 E DropBoxManagerService: 	... 5 more
,10-07 10:52:23.418  3769  3879 I Process : Sending signal. PID: 3769 SIG: 9
,10-07 10:52:23.431  3529  3529 I ConfigService: onCreate
,10-07 10:52:23.434  3529  6066 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-07 10:52:23.434  3529  6066 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-07 10:52:23.434  3529  6066 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-07 10:52:23.436  3529  6066 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-07 10:52:23.449  3349  6041 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
10-07 10:52:23.449  3349  6041 I Process : Sending signal. PID: 3349 SIG: 9
,10-07 10:52:23.466  3612  6039 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-07 10:52:23.488  3832  6048 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-07 10:52:23.506  3832  6048 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.506  3832  6048 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 10:52:23.507  3832  6048 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.507  3832  6048 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 10:52:23.508  3832  6048 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-07 10:52:23.545   927  2887 W InputDispatcher: channel 'c4d35f9 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-07 10:52:23.545   927  2887 E InputDispatcher: channel 'c4d35f9 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
10-07 10:52:23.546   927  3096 D GraphicsStats: Buffer count: 1
10-07 10:52:23.546   927  3096 I WindowState: WIN DEATH: Window{c4d35f9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
10-07 10:52:23.546   927  3096 W InputDispatcher: Attempted to unregister already unregistered input channel 'c4d35f9 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-07 10:52:23.562   927  3806 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3769) has died
,10-07 10:52:23.563   927  3806 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
10-07 10:52:23.564   927  3806 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-07 10:52:23.579   927   940 I ActivityManager: Start proc 6071:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-07 10:52:23.580   927  3545 I ActivityManager: Process android.process.acore (pid 3349) has died
,10-07 10:52:23.580   927  3545 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-07 10:52:23.597  3832  6083 I GMPM-SVC: App measurement is starting up
,10-07 10:52:23.607  3832  6083 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-07 10:52:23.608  3832  6083 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-07 10:52:23.623  6071  6071 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:52:23.623  6071  6071 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-07 10:52:23.623  6071  6071 D AndroidRuntime: Shutting down VM
,10-07 10:52:23.629  6071  6071 E AndroidRuntime: FATAL EXCEPTION: main
10-07 10:52:23.629  6071  6071 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6071
10-07 10:52:23.629  6071  6071 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-07 10:52:23.629  6071  6071 E AndroidRuntime: 	... 10 more
10-07 10:52:23.631   927  3096 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-07 10:52:23.632   927  6087 E DropBoxManagerService: Can't write: system_app_crash
10-07 10:52:23.632   927  6087 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 10:52:23.632   927  6087 E DropBoxManagerService: 	... 5 more
10-07 10:52:23.632  6071  6071 I Process : Sending signal. PID: 6071 SIG: 9
,10-07 10:52:23.677   927  3362 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6071) has died
,10-07 10:52:23.679   927  3362 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-07 10:52:23.694   927   940 I ActivityManager: Start proc 6088:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-07 10:52:23.742  6088  6088 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:52:23.742  6088  6088 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-07 10:52:23.742  6088  6088 D AndroidRuntime: Shutting down VM
,10-07 10:52:23.749  6088  6088 E AndroidRuntime: FATAL EXCEPTION: main
10-07 10:52:23.749  6088  6088 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6088
10-07 10:52:23.749  6088  6088 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-07 10:52:23.749  6088  6088 E AndroidRuntime: 	... 10 more
10-07 10:52:23.751   927   937 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-07 10:52:23.752   927  6100 E DropBoxManagerService: Can't write: system_app_crash
10-07 10:52:23.752   927  6100 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 10:52:23.752   927  6100 E DropBoxManagerService: 	... 5 more
10-07 10:52:23.752  6088  6088 I Process : Sending signal. PID: 6088 SIG: 9
,10-07 10:52:23.770   927  3764 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6088) has died

```
