#### Test 884969632a6a9b7_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-10 20:33:30.993   924  5233 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-10 20:33:31.471  5557  5557 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-10 20:33:31.476  5557  5557 D AndroidRuntime: CheckJNI is OFF
10-10 20:33:31.505  5557  5557 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-10 20:33:31.542  5557  5557 I Radio-JNI: register_android_hardware_Radio DONE
10-10 20:33:31.559  5557  5557 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-10 20:33:31.565   924  3719 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-10 20:33:31.613   924  3719 I ActivityManager: Start proc 5566:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-10 20:33:31.633  5557  5557 D AndroidRuntime: Shutting down VM
,10-10 20:33:31.961   924  3751 I WindowManager: Screenshot max retries 4 of Token{84b45df ActivityRecord{b74ec7e u0 com.test.thalitest/.MainActivity t2}} appWin=Window{bf80d56 u0 Starting com.test.thalitest} drawState=2
,10-10 20:33:32.028  5566  5566 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-10 20:33:32.061  5566  5566 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-10 20:33:32.127  5566  5566 I LibraryLoader: Time to load native libraries: 62 ms (timestamps 2283-2345)
,10-10 20:33:32.128  5566  5566 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-10 20:33:32.163  5566  5566 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5eb5031}
,10-10 20:33:32.163  5566  5566 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-10 20:33:32.164  5566  5566 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-10 20:33:32.170  5566  5566 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-10 20:33:32.172  5566  5566 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-10 20:33:32.244  5566  5566 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-10 20:33:32.261  5566  5566 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-10 20:33:32.261  5566  5566 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-10 20:33:32.261  5566  5566 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-10 20:33:32.261  5566  5566 I Adreno  : Build Date                       : 12/06/15
10-10 20:33:32.261  5566  5566 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-10 20:33:32.261  5566  5566 I Adreno  : Local Branch                     : mybranch17112971
10-10 20:33:32.261  5566  5566 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-10 20:33:32.261  5566  5566 I Adreno  : Remote Branch                    : NONE
10-10 20:33:32.261  5566  5566 I Adreno  : Reconstruct Branch               : NOTHING
,10-10 20:33:32.306   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce72e5c:true
,10-10 20:33:32.330   401   401 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[15010]" dev="sockfs" ino=15010 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-10 20:33:32.330   401   401 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[15010]" dev="sockfs" ino=15010 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-10 20:33:32.342  5566  5566 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-10 20:33:32.351  5566  5566 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-10 20:33:32.370   401   401 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32651]" dev="sockfs" ino=32651 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-10 20:33:32.375  5566  5603 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-10 20:33:32.370   401   401 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32651]" dev="sockfs" ino=32651 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-10 20:33:32.374  3775  3775 W Binder_B: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[20091]" dev="sockfs" ino=20091 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-10 20:33:32.374  3775  3775 W Binder_B: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[20091]" dev="sockfs" ino=20091 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-10 20:33:32.381  5566  5590 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-10 20:33:32.408  5566  5603 I OpenGLRenderer: Initialized EGL, version 1.4
,10-10 20:33:32.471   924   942 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +509ms (total +885ms)
,10-10 20:33:32.496  5566  5566 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5566
,10-10 20:33:32.577  5566  5566 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-10 20:33:32.694  5566  5606 D jxcore_app_log: JniHelper::setJavaVM(0xf54bc000), pthread_self() = -563607248
,10-10 20:33:32.698  5566  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-10 20:33:32.698  5566  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-10 20:33:32.698  5566  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-10 20:33:32.698  5566  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-10 20:33:32.698  5566  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-10 20:33:32.698  5566  5606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3fe9ae added. We now have 1 listener(s)
,10-10 20:33:32.700  5566  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-10 20:33:32.700  5566  5606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-10 20:33:32.701  5566  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-10 20:33:32.701  5566  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-10 20:33:32.703  5566  5606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec627e5 added. We now have 1 listener(s)
10-10 20:33:32.704  5566  5606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-10 20:33:32.709   924  2923 D WifiService: New client listening to asynchronous messages
,10-10 20:33:32.710  5566  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-10 20:33:32.710  5566  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-10 20:33:32.710  5566  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-10 20:33:32.710  5566  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-10 20:33:32.710  5566  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-10 20:33:32.712  5566  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:33:32.712  5566  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-10 20:33:32.717  5566  5606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-10 20:33:32.717  5566  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-10 20:33:32.717  5566  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:33:32.717  5566  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:33:32.717  5566  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:33:32.717  5566  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:33:32.717  5566  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:33:32.717  5566  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:33:32.717  5566  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-10 20:33:32.718  5566  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-10 20:33:32.718  5566  5606 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-10 20:33:32.718  5566  5606 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-10 20:33:32.721  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:33:32.723  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:33:32.735  5566  5566 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-10 20:33:33.011  5566  5612 W jxcore-log: Initializing JXcore engine
,10-10 20:33:33.011  5566  5612 W jxcore-log: JXcore engine is ready
,10-10 20:33:33.034  5612  5612 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11683 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-10 20:33:33.034  5612  5612 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[15549]" dev="sockfs" ino=15549 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-10 20:33:33.034  5612  5612 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-10 20:33:33.034  5612  5612 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32631]" dev="sockfs" ino=32631 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-10 20:33:33.042  5566  5612 W jxcore-log: Starting JXcore engine
,10-10 20:33:33.052  5566  5575 I art     : Background sticky concurrent mark sweep GC freed 86345(8MB) AllocSpace objects, 19(2MB) LOS objects, 24% free, 24MB/32MB, paused 1.438ms total 105.546ms
,10-10 20:33:33.096  5566  5612 W jxcore-log: Platform android
10-10 20:33:33.096  5566  5612 W jxcore-log: 
,10-10 20:33:33.096  5566  5612 W jxcore-log: Process ARCH arm
10-10 20:33:33.096  5566  5612 W jxcore-log: 
,10-10 20:33:33.199  5566  5612 I jxcore-log: JXcore Cordova bridge is ready!
10-10 20:33:33.199  5566  5612 I jxcore-log: 
,10-10 20:33:33.199  5566  5612 W jxcore-log: JXcore engine is started
,10-10 20:33:33.211  5566  5606 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-10 20:33:33.217  5566  5566 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-10 20:33:39.010   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-10 20:33:39.010   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-10 20:33:41.773   924  2922 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-10 20:33:43.187  5566  5612 I jxcore-log: 2016-10-11 00:33:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-10 20:33:43.187  5566  5612 I jxcore-log: 
,10-10 20:33:43.188  5566  5612 I jxcore-log: 2016-10-11 00:33:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-10 20:33:43.188  5566  5612 I jxcore-log: 
,10-10 20:33:43.192  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-10 20:33:43.192  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:33:43.192  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:33:43.192  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:33:43.192  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:33:43.192  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:33:43.192  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:33:43.192  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:33:43.194  5566  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-10 20:33:43.195  5566  5612 I jxcore-log: 2016-10-11 00:33:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-10 20:33:43.195  5566  5612 I jxcore-log: 
,10-10 20:33:43.197  5566  5612 I jxcore-log: 2016-10-11 00:33:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-10 20:33:43.197  5566  5612 I jxcore-log: 
,10-10 20:33:43.459  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-10 20:33:43.459  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7041aa added. We now have 2 listener(s)
10-10 20:33:43.460  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-10 20:33:43.460  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-10 20:33:43.460  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-10 20:33:43.461  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-10 20:33:43.461  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a49f19b added. We now have 2 listener(s)
,10-10 20:33:43.461  5566  5612 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-10 20:33:43.461  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-10 20:33:43.463  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-10 20:33:43.466  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-10 20:33:43.466  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:33:43.466  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:33:43.466  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:33:43.466  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:33:43.466  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:33:43.466  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:33:43.466  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:33:43.467  5566  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-10 20:33:43.467  5566  5612 D io.jxcore.node.ConnectivityMonitor: start: OK
10-10 20:33:43.468  5566  5612 D ExecuteNativeTests: Running unit tests
10-10 20:33:43.469  5566  5612 D BluetoothAdapter: enable(): BT is already enabled..!
10-10 20:33:43.469   924  3787 D WifiService: setWifiEnabled: true pid=5566, uid=10077
,10-10 20:33:43.469   924  3787 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:33:43.476  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:33:43.482  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:33:49.012   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:33:50.013   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:33:51.014   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:33:52.015   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:33:53.017   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:33:53.474  5566  5612 I com.test.thalitest.ThaliTestRunner: Running UT
,10-10 20:33:53.540  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-10 20:33:53.541  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e0975 added. We now have 3 listener(s)
10-10 20:33:53.542  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-10 20:33:53.542  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-10 20:33:53.542  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-10 20:33:53.542  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-10 20:33:53.542  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b69dd0a added. We now have 3 listener(s)
10-10 20:33:53.542  5566  5612 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-10 20:33:53.543  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-10 20:33:53.546  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-10 20:33:53.551  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-10 20:33:53.551  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:33:53.551  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:33:53.551  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:33:53.551  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:33:53.551  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:33:53.551  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:33:53.551  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:33:53.554  5566  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:33:53.554  5566  5612 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-10 20:33:53.561  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:33:53.564  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
10-10 20:33:53.564  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-10 20:33:53.564  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-10 20:33:53.564  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-10 20:33:53.564  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-10 20:33:53.565  5566  5612 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-10 20:33:53.565  5566  5612 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-10 20:33:53.565  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-10 20:33:53.565  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-10 20:33:53.565  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-10 20:33:53.565  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-10 20:33:53.566  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
10-10 20:33:53.566  5566  5612 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-10 20:33:53.567  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
10-10 20:33:53.569  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
10-10 20:33:53.569  5566  5612 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-10 20:33:53.570  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:33:53.571  5566  5612 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-10 20:33:53.571  5566  5612 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
10-10 20:33:53.571  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
10-10 20:33:53.571  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-10 20:33:53.571  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-10 20:33:53.571  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-10 20:33:53.572  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:33:53.572  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-10 20:33:53.573  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-10 20:33:53.573  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-10 20:33:53.573  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-10 20:33:53.573  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-10 20:33:53.573  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-10 20:33:53.573  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:33:53.573  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-10 20:33:53.573  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-10 20:33:53.574  5566  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-10 20:33:53.581  5566  5612 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-10 20:33:53.581  5566  5614 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-10 20:33:53.581  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-10 20:33:53.586  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-10 20:33:53.588  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-10 20:33:53.588  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-10 20:33:53.584  4326  4326 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31718]" dev="sockfs" ino=31718 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-10 20:33:53.584  4326  4326 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31718]" dev="sockfs" ino=31718 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-10 20:33:53.589  5566  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-10 20:33:53.589  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-10 20:33:53.590  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-10 20:33:53.590  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
10-10 20:33:53.590  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:33:53.590  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-10 20:33:53.590  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-10 20:33:53.591  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:33:53.591  5566  5612 D BluetoothAdapter: STATE_ON
,10-10 20:33:53.595  4176  4188 D BtGatt.GattService: registerClient() - UUID=01f5451d-2a74-4f33-962e-e2f2f325661c
10-10 20:33:53.595  4176  4199 D BtGatt.GattService: onClientRegistered() - UUID=01f5451d-2a74-4f33-962e-e2f2f325661c, clientIf=5
10-10 20:33:53.596  5566  5576 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-10 20:33:53.598  4176  4205 D BtGatt.AdvertiseManager: message : 0
10-10 20:33:53.601  4176  4205 D BtGatt.AdvertiseManager: starting multi advertising
10-10 20:33:53.617  4176  4199 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
10-10 20:33:53.623  4176  4199 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-10 20:33:53.625  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-10 20:33:53.625  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-10 20:33:53.625  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-10 20:33:53.625  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-10 20:33:53.625  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-10 20:33:53.626  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-10 20:33:53.627  5566  5612 I io.jxcore.node.ConnectionHelper: start: OK
10-10 20:33:53.627  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-10 20:33:53.628  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-10 20:33:53.628  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-10 20:33:53.628  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-10 20:33:53.628  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,10-10 20:33:53.628  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:33:53.628  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-10 20:33:53.628  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-10 20:33:53.628  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-10 20:33:53.628  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-10 20:33:53.631  5566  5566 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-10 20:33:53.631  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-10 20:33:53.677   924   933 I art     : Background partial concurrent mark sweep GC freed 61931(4MB) AllocSpace objects, 32(916KB) LOS objects, 33% free, 29MB/43MB, paused 1.783ms total 102.142ms
,10-10 20:33:54.017   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-10 20:33:54.132  5566  5612 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-10 20:33:54.132  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-10 20:33:54.132  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-10 20:33:54.132  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-10 20:33:54.132  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-10 20:33:54.132  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-10 20:33:54.133  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-10 20:33:54.133  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,10-10 20:33:54.133  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-10 20:33:54.133  5566  5566 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-10 20:33:54.134  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-10 20:33:54.135  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-10 20:33:54.135  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-10 20:33:54.135  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-10 20:33:54.135  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-10 20:33:54.135  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,10-10 20:33:54.135  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-10 20:33:54.136  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-10 20:33:54.136  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-10 20:33:54.136  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-10 20:33:54.136  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-10 20:33:54.136  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-10 20:33:54.137  5566  5614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-10 20:33:54.137  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-10 20:33:54.137  5566  5614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-10 20:33:54.137  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-10 20:33:54.137  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-10 20:33:54.137  5566  5614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-10 20:33:54.138  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-10 20:33:54.138  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-10 20:33:54.138  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-10 20:33:54.138  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-10 20:33:54.138  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-10 20:33:54.139  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-10 20:33:54.142  5566  5612 D BluetoothAdapter: STATE_ON
,10-10 20:33:54.143  5566  5612 D BluetoothLeScanner: could not find callback wrapper
10-10 20:33:54.143  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-10 20:33:54.144  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-10 20:33:54.147  4176  4205 D BtGatt.AdvertiseManager: message : 1
10-10 20:33:54.148  4176  4205 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-10 20:33:54.160  4176  4199 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-10 20:33:54.160  4176  4199 D BtGatt.GattService: Client app is not null!
,10-10 20:33:54.162  4176  4188 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-10 20:33:54.163  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-10 20:33:54.163  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-10 20:33:54.163  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-10 20:33:54.164  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,10-10 20:33:54.164  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:33:54.164  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-10 20:33:54.164  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-10 20:33:54.164  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-10 20:33:54.164  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-10 20:33:54.167  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-10 20:33:54.167  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-10 20:33:54.167  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-10 20:33:54.169  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-10 20:33:54.172  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-10 20:33:54.172  5566  5566 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-10 20:33:54.172  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-10 20:33:54.172  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-10 20:33:54.172  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-10 20:33:54.173  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-10 20:33:54.173  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-10 20:33:54.174  5566  5612 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-10 20:33:54.174  5566  5612 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-10 20:33:54.174  5566  5612 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
10-10 20:33:54.175  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-10 20:33:54.175  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-10 20:33:54.175  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-10 20:33:54.175  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-10 20:33:54.175  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:33:54.180  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-10 20:33:54.180  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-10 20:33:54.181  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-10 20:33:54.181  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-10 20:33:54.181  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-10 20:33:54.181  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-10 20:33:54.181  5566  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-10 20:33:54.181  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:33:54.181  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-10 20:33:54.181  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-10 20:33:54.182  5566  5617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-10 20:33:54.186  5566  5612 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-10 20:33:54.186  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-10 20:33:54.184  4326  4326 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32669]" dev="sockfs" ino=32669 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-10 20:33:54.187  4326  4326 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32669]" dev="sockfs" ino=32669 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-10 20:33:54.190  5566  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-10 20:33:54.192  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-10 20:33:54.193  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-10 20:33:54.193  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-10 20:33:54.196  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-10 20:33:54.196  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-10 20:33:54.196  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
10-10 20:33:54.196  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:33:54.196  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-10 20:33:54.196  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-10 20:33:54.196  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:33:54.198  5566  5612 D BluetoothAdapter: STATE_ON
10-10 20:33:54.201  4176  4346 D BtGatt.GattService: registerClient() - UUID=caed5721-246e-4770-bf44-5af45475a4fb
10-10 20:33:54.202  4176  4199 D BtGatt.GattService: onClientRegistered() - UUID=caed5721-246e-4770-bf44-5af45475a4fb, clientIf=5
10-10 20:33:54.203  5566  5576 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-10 20:33:54.204  4176  4205 D BtGatt.AdvertiseManager: message : 0
10-10 20:33:54.207  4176  4205 D BtGatt.AdvertiseManager: starting multi advertising
,10-10 20:33:54.220  4176  4199 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
10-10 20:33:54.229  4176  4199 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-10 20:33:54.230  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-10 20:33:54.230  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-10 20:33:54.230  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-10 20:33:54.230  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-10 20:33:54.230  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-10 20:33:54.232  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-10 20:33:54.234  5566  5612 I io.jxcore.node.ConnectionHelper: start: OK
10-10 20:33:54.234  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-10 20:33:54.234  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-10 20:33:54.235  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-10 20:33:54.235  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-10 20:33:54.235  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-10 20:33:54.235  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:33:54.235  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-10 20:33:54.235  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-10 20:33:54.235  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-10 20:33:54.235  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-10 20:33:54.239  5566  5566 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-10 20:33:54.239  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-10 20:33:54.740  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-10 20:33:54.741  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-10 20:33:54.741  5566  5566 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-10 20:33:54.742  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,10-10 20:33:54.742  5566  5612 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-10 20:33:54.742  5566  5612 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-10 20:33:54.742  5566  5612 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-10 20:33:54.743  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-10 20:33:54.746  4176  4205 D BtGatt.AdvertiseManager: message : 1
,10-10 20:33:54.747  4176  4205 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-10 20:33:54.762  4176  4199 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-10 20:33:54.762  4176  4199 D BtGatt.GattService: Client app is not null!
10-10 20:33:54.764  4176  4188 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-10 20:33:54.765  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-10 20:33:54.765  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-10 20:33:54.765  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-10 20:33:54.765  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-10 20:33:54.765  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-10 20:33:54.765  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-10 20:33:54.765  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
10-10 20:33:54.766  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-10 20:33:54.766  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-10 20:33:54.766  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,10-10 20:33:54.766  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:33:54.768  5566  5612 D BluetoothAdapter: STATE_ON
,10-10 20:33:54.773  4176  4188 D BtGatt.GattService: registerClient() - UUID=69eacebb-cb5e-4d16-b76c-2089d6b7dddf
,10-10 20:33:54.774  4176  4199 D BtGatt.GattService: onClientRegistered() - UUID=69eacebb-cb5e-4d16-b76c-2089d6b7dddf, clientIf=5
10-10 20:33:54.775  5566  5577 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-10 20:33:54.777  4176  4205 D BtGatt.AdvertiseManager: message : 0
,10-10 20:33:54.781  4176  4205 D BtGatt.AdvertiseManager: starting multi advertising
,10-10 20:33:54.796  4176  4199 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-10 20:33:54.805  4176  4199 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-10 20:33:54.805  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,10-10 20:33:54.806  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-10 20:33:54.806  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-10 20:33:54.806  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-10 20:33:54.806  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-10 20:33:54.806  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-10 20:33:54.806  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-10 20:33:54.806  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-10 20:33:54.806  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-10 20:33:54.806  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-10 20:33:54.806  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-10 20:33:54.806  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:33:54.806  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-10 20:33:54.806  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-10 20:33:54.806  5566  5612 I io.jxcore.node.ConnectionHelper: start: OK
10-10 20:33:54.806  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-10 20:33:54.808  5566  5612 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-10 20:33:54.808  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-10 20:33:54.808  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-10 20:33:54.808  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-10 20:33:54.808  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-10 20:33:54.808  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-10 20:33:54.809  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-10 20:33:54.809  5566  5617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-10 20:33:54.809  5566  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-10 20:33:54.809  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-10 20:33:54.809  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-10 20:33:54.809  5566  5617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-10 20:33:54.809  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-10 20:33:54.809  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-10 20:33:54.809  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-10 20:33:54.809  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-10 20:33:54.809  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-10 20:33:54.809  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-10 20:33:54.810  5566  5612 D BluetoothAdapter: STATE_ON
10-10 20:33:54.810  5566  5612 D BluetoothLeScanner: could not find callback wrapper
10-10 20:33:54.810  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-10 20:33:54.810  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-10 20:33:54.811  4176  4205 D BtGatt.AdvertiseManager: message : 1
10-10 20:33:54.812  4176  4205 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-10 20:33:54.821  4176  4199 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-10 20:33:54.821  4176  4199 D BtGatt.GattService: Client app is not null!
10-10 20:33:54.822  4176  4188 D BtGatt.GattService: unregisterClient() - clientIf=5
10-10 20:33:54.822  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-10 20:33:54.822  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-10 20:33:54.822  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-10 20:33:54.822  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-10 20:33:54.823  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:33:54.823  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-10 20:33:54.823  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-10 20:33:54.823  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,10-10 20:33:54.823  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-10 20:33:54.824  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-10 20:33:54.824  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-10 20:33:54.824  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-10 20:33:54.825  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-10 20:33:54.827  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-10 20:33:54.827  5566  5566 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-10 20:33:54.827  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-10 20:33:54.827  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-10 20:33:54.827  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-10 20:33:54.827  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-10 20:33:54.827  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-10 20:33:54.828  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
10-10 20:33:54.829  5566  5612 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-10 20:33:54.830  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
10-10 20:33:54.831  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-10 20:33:54.832  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
10-10 20:33:54.832  5566  5612 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-10 20:33:54.833  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,10-10 20:33:54.833  5566  5612 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-10 20:33:54.834  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
10-10 20:33:54.834  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-10 20:33:54.834  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-10 20:33:54.834  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-10 20:33:54.834  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-10 20:33:54.835  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-10 20:33:54.835  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-10 20:33:54.835  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-10 20:33:54.835  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-10 20:33:54.835  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-10 20:33:54.835  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-10 20:33:54.835  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-10 20:33:54.835  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-10 20:33:54.836  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
10-10 20:33:54.836  5566  5612 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-10 20:33:54.836  5566  5612 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-10 20:33:54.839  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,10-10 20:33:54.840  5566  5612 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-10 20:33:54.841  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
10-10 20:33:54.841  5566  5612 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-10 20:33:54.843  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
10-10 20:33:54.843  5566  5612 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
10-10 20:33:54.843  5566  5612 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-10 20:33:54.843  5566  5612 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-10 20:33:54.843  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-10 20:33:54.843  5566  5612 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-10 20:33:54.843  5566  5612 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-10 20:33:54.843  5566  5612 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-10 20:33:54.844  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-10 20:33:54.844  5566  5612 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-10 20:33:54.844  5566  5612 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-10 20:33:54.844  5566  5612 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-10 20:33:54.844  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-10 20:33:54.844  5566  5612 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-10 20:33:54.845  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-10 20:33:54.845  5566  5612 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-10 20:33:54.845  5566  5612 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-10 20:33:54.845  5566  5612 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
10-10 20:33:54.845  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
10-10 20:33:54.845  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-10 20:33:54.845  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-10 20:33:54.845  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-10 20:33:54.845  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:33:54.847  4188  4188 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33847]" dev="sockfs" ino=33847 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-10 20:33:54.847  4188  4188 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33847]" dev="sockfs" ino=33847 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-10 20:33:54.846  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-10 20:33:54.847  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-10 20:33:54.847  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-10 20:33:54.847  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-10 20:33:54.847  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-10 20:33:54.847  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-10 20:33:54.847  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:33:54.847  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-10 20:33:54.847  5566  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-10 20:33:54.847  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-10 20:33:54.848  5566  5621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-10 20:33:54.850  5566  5612 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-10 20:33:54.850  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-10 20:33:54.852  5566  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-10 20:33:54.854  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-10 20:33:54.855  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-10 20:33:54.855  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-10 20:33:54.857  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-10 20:33:54.857  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-10 20:33:54.857  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
,10-10 20:33:54.857  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:33:54.857  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-10 20:33:54.857  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-10 20:33:54.858  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:33:54.858  5566  5612 D BluetoothAdapter: STATE_ON
,10-10 20:33:54.862  4176  4186 D BtGatt.GattService: registerClient() - UUID=d02d9b4f-1cd0-41d3-b9ec-d5ada78d32b6
,10-10 20:33:54.862  4176  4199 D BtGatt.GattService: onClientRegistered() - UUID=d02d9b4f-1cd0-41d3-b9ec-d5ada78d32b6, clientIf=5
,10-10 20:33:54.862  5566  5577 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-10 20:33:54.863  4176  4205 D BtGatt.AdvertiseManager: message : 0
,10-10 20:33:54.867  4176  4205 D BtGatt.AdvertiseManager: starting multi advertising
,10-10 20:33:54.878  4176  4199 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-10 20:33:54.885  4176  4199 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-10 20:33:54.885  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-10 20:33:54.885  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-10 20:33:54.885  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-10 20:33:54.885  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-10 20:33:54.885  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-10 20:33:54.887  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-10 20:33:54.888  5566  5612 I io.jxcore.node.ConnectionHelper: start: OK
10-10 20:33:54.888  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-10 20:33:54.888  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,10-10 20:33:54.888  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-10 20:33:54.888  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-10 20:33:54.888  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,10-10 20:33:54.888  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:33:54.888  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-10 20:33:54.888  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-10 20:33:54.888  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-10 20:33:54.888  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-10 20:33:54.891  5566  5566 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-10 20:33:54.891  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-10 20:33:55.389  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-10 20:33:55.390  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-10 20:33:55.390  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-10 20:33:55.390  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-10 20:33:55.391  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-10 20:33:55.391  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-10 20:33:55.391  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-10 20:33:55.391  5566  5621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-10 20:33:55.391  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-10 20:33:55.391  5566  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-10 20:33:55.391  5566  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-10 20:33:55.391  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e0975 removed from the list
10-10 20:33:55.392  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-10 20:33:55.392  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-10 20:33:55.392  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-10 20:33:55.392  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-10 20:33:55.392  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-10 20:33:55.392  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-10 20:33:55.393  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-10 20:33:55.393  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-10 20:33:55.393  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-10 20:33:55.395  5566  5612 D BluetoothAdapter: STATE_ON
10-10 20:33:55.396  5566  5612 D BluetoothLeScanner: could not find callback wrapper
10-10 20:33:55.396  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-10 20:33:55.396  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-10 20:33:55.398  4176  4205 D BtGatt.AdvertiseManager: message : 1
10-10 20:33:55.399  4176  4205 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-10 20:33:55.413  4176  4199 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-10 20:33:55.413  4176  4199 D BtGatt.GattService: Client app is not null!
,10-10 20:33:55.415  4176  4346 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-10 20:33:55.416  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-10 20:33:55.416  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-10 20:33:55.416  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-10 20:33:55.416  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-10 20:33:55.417  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-10 20:33:55.417  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-10 20:33:55.417  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-10 20:33:55.417  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-10 20:33:55.417  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-10 20:33:55.419  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-10 20:33:55.420  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-10 20:33:55.420  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-10 20:33:55.421  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-10 20:33:55.423  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b69dd0a removed from the list
10-10 20:33:55.423  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-10 20:33:55.423  5566  5612 D io.jxcore.node.ConnectivityMonitor: stop
10-10 20:33:55.423  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-10 20:33:55.423  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-10 20:33:55.423  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-10 20:33:55.924  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-10 20:33:59.018   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:00.019   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:00.427  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-10 20:34:00.430  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-10 20:34:00.430  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-10 20:34:00.433  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-10 20:34:00.434  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-10 20:34:00.434  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-10 20:34:00.434  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-10 20:34:00.434  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-10 20:34:00.434  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-10 20:34:00.435  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-10 20:34:00.435  5566  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-10 20:34:00.437  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
10-10 20:34:00.437  5566  5622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-10 20:34:00.438  5566  5612 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-10 20:34:00.439  5566  5612 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-10 20:34:00.439  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-10 20:34:00.439  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-10 20:34:00.439  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-10 20:34:00.441  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
10-10 20:34:00.437  4346  4346 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31741]" dev="sockfs" ino=31741 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-10 20:34:00.437  4346  4346 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31741]" dev="sockfs" ino=31741 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-10 20:34:00.443  5566  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-10 20:34:00.449  5566  5612 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-10 20:34:00.450  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-10 20:34:00.450  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-10 20:34:00.451  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-10 20:34:00.451  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-10 20:34:00.451  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-10 20:34:00.451  5566  5622 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-10 20:34:00.451  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-10 20:34:00.451  5566  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-10 20:34:00.451  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-10 20:34:00.451  5566  5622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-10 20:34:00.451  5566  5612 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e0975 not in the list
10-10 20:34:00.451  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-10 20:34:00.451  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-10 20:34:00.451  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-10 20:34:00.451  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-10 20:34:00.451  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-10 20:34:00.451  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-10 20:34:00.451  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-10 20:34:00.452  5566  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-10 20:34:00.452  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-10 20:34:00.453  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-10 20:34:00.454  5566  5612 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b69dd0a not in the list
10-10 20:34:00.454  5566  5612 D io.jxcore.node.ConnectivityMonitor: stop
10-10 20:34:00.454  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-10 20:34:00.454  5566  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-10 20:34:00.454  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-10 20:34:00.454  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-10 20:34:00.454  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-10 20:34:00.455  5566  5612 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,10-10 20:34:00.456  5566  5612 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-10 20:34:00.456  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-10 20:34:00.456  5566  5612 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-10 20:34:00.456  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-10 20:34:00.456  5566  5612 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-10 20:34:00.456  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-10 20:34:00.457  5566  5612 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,10-10 20:34:00.458  5566  5612 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
10-10 20:34:00.459  5566  5612 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
10-10 20:34:00.460  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-10 20:34:00.460  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-10 20:34:00.461  5566  5612 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,10-10 20:34:00.461  5566  5612 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-10 20:34:00.461  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-10 20:34:00.461  5566  5612 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-10 20:34:00.461  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-10 20:34:00.461  5566  5612 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-10 20:34:00.462  5566  5612 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,10-10 20:34:00.462  5566  5612 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
10-10 20:34:00.463  5566  5612 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-10 20:34:00.463  5566  5612 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-10 20:34:00.464  5566  5612 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
10-10 20:34:00.464  5566  5612 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-10 20:34:00.464  5566  5612 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-10 20:34:00.464  5566  5612 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-10 20:34:00.464  5566  5612 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-10 20:34:00.465  5566  5612 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,10-10 20:34:00.467  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-10 20:34:00.467  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbb9cba added. We now have 3 listener(s)
,10-10 20:34:00.469  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-10 20:34:00.470  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-10 20:34:00.470  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-10 20:34:00.470  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-10 20:34:00.470  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7e976b added. We now have 3 listener(s)
10-10 20:34:00.470  5566  5612 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-10 20:34:00.471  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-10 20:34:00.473  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-10 20:34:00.478  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-10 20:34:00.478  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:00.478  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:00.478  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:00.478  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:00.478  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:00.478  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:00.478  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:00.480  5566  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:00.481  5566  5612 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-10 20:34:00.483  5566  5612 D BluetoothAdapter: enable(): BT is already enabled..!
10-10 20:34:00.484   924   935 D WifiService: setWifiEnabled: true pid=5566, uid=10077
10-10 20:34:00.484   924   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:00.484  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:00.486  5566  5612 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,10-10 20:34:00.488  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:00.489  5566  5612 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,10-10 20:34:00.490  5566  5612 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,10-10 20:34:00.494   924   935 D WifiService: setWifiEnabled: false pid=5566, uid=10077
,10-10 20:34:00.494   924   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:00.496   924  2922 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-10 20:34:00.497   924  2922 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-10 20:34:00.497   924  2922 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-10 20:34:00.497   924  2922 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-10 20:34:00.505   924  5234 D DhcpClient: Clearing IP address
10-10 20:34:00.505   506   915 D CommandListener: Clearing all IP addresses on wlan0
,10-10 20:34:00.512   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:00.516  3524  5291 V NativeCrypto: Read error: ssl=0x7f843ba180: I/O error during system call, Connection timed out
10-10 20:34:00.518  3524  5291 V NativeCrypto: SSL shutdown failed: ssl=0x7f843ba180: I/O error during system call, Broken pipe
10-10 20:34:00.520   924  3687 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-10 20:34:00.520   924  5232 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-10 20:34:00.522   924  5232 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-10 20:34:00.523   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-10 20:34:00.523   924  2924 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-10 20:34:00.524   924  5235 D DhcpClient: Receive thread stopped
10-10 20:34:00.525   924  2924 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-10 20:34:00.531   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-10 20:34:00.532   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,10-10 20:34:00.535   532   532 E Parcel  : Reading a NULL string not supported here.
,10-10 20:34:00.539   924  2924 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-10 20:34:00.540   924   924 D RttService: SCAN_AVAILABLE : 1
10-10 20:34:00.540   924  3031 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-10 20:34:00.542  3670  3842 W QCNEJ   : |CORE| network lost: 100
10-10 20:34:00.543  3670  3842 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-10 20:34:00.561   924  2922 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-10 20:34:00.566   506   915 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-10 20:34:00.572   924  2922 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-10 20:34:00.585   506   915 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-10 20:34:00.586   506   915 D CommandListener: Clearing all IP addresses on wlan0
10-10 20:34:00.586   924  2924 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-10 20:34:00.586   924  2924 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-10 20:34:00.587   506   915 D TetherController: Setting IP forward enable = 0
,10-10 20:34:00.588   924   941 D Tethering: MasterInitialState.processMessage what=3
10-10 20:34:00.591   924  2922 D DhcpClient: doQuit
10-10 20:34:00.592  5103  5103 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@744202d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-10 20:34:00.592   924  5234 D DhcpClient: onQuitting
10-10 20:34:00.592   924  2922 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-10 20:34:00.593  3398  3398 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-10 20:34:00.595  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:00.595  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:00.595  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:00.595  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:00.595  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:00.595  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:00.595  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:00.595  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-10 20:34:00.599  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:00.601  4790  4814 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-10 20:34:00.601  4790  4814 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-10 20:34:00.602  3990  3990 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-10 20:34:00.603  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:00.603  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:00.603  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:00.603  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-10 20:34:00.603  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:00.603  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:00.603  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:00.603  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-10 20:34:00.606  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-10 20:34:00.606  4790  4814 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-10 20:34:00.606  4790  4814 E SarControlService: no key has been found,reset the power
10-10 20:34:00.606  4790  4827 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-10 20:34:00.606  4790  4827 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-10 20:34:00.606  4790  4827 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-10 20:34:00.607  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-10 20:34:00.607  4815  4815 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-10 20:34:00.608  4790  4827 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-10 20:34:00.609  4790  4827 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-10 20:34:00.609  4790  4827 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-10 20:34:00.609  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-10 20:34:00.609  4815  4815 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-10 20:34:00.610  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:00.610  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:00.610  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:00.610  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-10 20:34:00.610  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:00.610  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:00.610  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:00.610  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:00.613  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:00.617  4815  4829 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@70117bb HexData = [00000000ea03000000000000ffffffff]
,10-10 20:34:00.617  4815  4829 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-10 20:34:00.617  4815  4829 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-10 20:34:00.618  3398  3398 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-10 20:34:00.618  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-10 20:34:00.618  4790  4800 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-10 20:34:00.618  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:00.618  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:00.618  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:00.618  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-10 20:34:00.618  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:00.618  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:00.618  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:00.618  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:00.619  3990  3990 D SystemUpdateService: onCreate
10-10 20:34:00.622  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-10 20:34:00.623  4815  4829 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@70117bb HexData = [00000000eb03000000000000ffffffff]
10-10 20:34:00.623  4815  4829 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-10 20:34:00.623  4815  4829 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-10 20:34:00.624  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:00.624  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-10 20:34:00.624  4790  4801 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-10 20:34:00.625  3990  3990 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-10 20:34:00.625  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:00.627  3398  3398 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-10 20:34:00.629   506   908 W SocketClient: write error (Broken pipe)
10-10 20:34:00.629   506   908 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-10 20:34:00.629   506   908 W SocketListener: Error sending broadcast (Broken pipe)
,10-10 20:34:00.635  3990  3990 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-10 20:34:00.641  3990  5641 I SystemUpdateService: active receiver: enabled
,10-10 20:34:00.642  3990  5260 I iu.UploadsManager: num queued entries: 0
,10-10 20:34:00.643  3990  5260 I iu.UploadsManager: num updated entries: 0
10-10 20:34:00.644  3990  5260 I iu.SyncManager: NEXT; no task
,10-10 20:34:00.645  3990  3990 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-10 20:34:00.646  3990  3990 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-10 20:34:00.648  5264  5264 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-10 20:34:00.652  5264  5264 D SprintDMHelper: simOperator: 
10-10 20:34:00.652  5264  5264 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-10 20:34:00.656   506   915 E Netd    : netlink response contains error (No such file or directory)
,10-10 20:34:00.656   506   915 D TetherController: Setting IP forward enable = 0
10-10 20:34:00.657   924  2924 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-10 20:34:00.657   924  2924 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-10 20:34:00.661  3398  3398 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-10 20:34:00.666  4738  5646 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-10 20:34:00.667  3990  5641 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-10 20:34:00.669  3990  5641 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-10 20:34:00.670  3990  5641 I SystemUpdateService: now status is 0 (complete)
10-10 20:34:00.670  3990  5641 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-10 20:34:00.670  3990  5641 I SystemUpdateService: file has been verified
10-10 20:34:00.670  3990  5641 I SystemUpdateService: OTA package size = 21989297
,10-10 20:34:00.672  3398  3398 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-10 20:34:00.675  3990  5641 I SystemUpdateService: showing system update notification
,10-10 20:34:00.677   924  3751 I ActivityManager: Start proc 5648:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-10 20:34:00.692  3990  3990 D SystemUpdateService: onDestroy
,10-10 20:34:00.711  5648  5648 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-10 20:34:00.718   924  3719 I ActivityManager: Killing 5103:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-10 20:34:00.777   924  2922 D wifi    : In wifi stop Hal
,10-10 20:34:00.777   924  2922 D wifi    : halHandle = 0x7f6ff035a0, mVM = 0x7f8a50d140, mCls = 0x100a12
10-10 20:34:00.777   924  3397 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-10 20:34:00.777   924  3397 D WifiHAL : Got a signal to exit!!!
10-10 20:34:00.777   924  3397 I WifiHAL : Exit wifi_event_loop
10-10 20:34:00.778   924  2922 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-10 20:34:00.778   924  2922 E WifiHAL : Event processing terminated
10-10 20:34:00.778   924  2922 D wifi    : In wifi cleaned up handler
10-10 20:34:00.778   924  2922 I WifiHAL : Internal cleanup completed
,10-10 20:34:00.780  3848  4165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-10 20:34:00.781  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:00.783  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:00.777  4738  4738 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-10 20:34:00.785  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:00.801   924  3397 D wifi    : set interface wlan0 flags (DOWN)
,10-10 20:34:00.801   924  2922 D WifiNative-HAL: HAL event thread stopped successfully
,10-10 20:34:00.955  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-10 20:34:01.001  5566  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:01.006   924  3554 D WifiService: setWifiEnabled: true pid=5566, uid=10077
,10-10 20:34:01.006   924  3554 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:01.009   924   941 D Tethering: InitialState.processMessage what=4
,10-10 20:34:01.013   506   915 D SoftapController: Softap fwReload - Ok
10-10 20:34:01.015   924   941 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
10-10 20:34:01.017   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:01.018   506   915 D CommandListener: Trying to bring down wlan0
,10-10 20:34:01.020   506   915 D CommandListener: Clearing all IP addresses on wlan0
,10-10 20:34:01.021   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:01.025   924  2922 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-10 20:34:01.511   924  3356 D WifiService: setWifiEnabled: true pid=5566, uid=10077
,10-10 20:34:01.514   924  3356 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:01.630   924  2922 D wifi    : set interface wlan0 flags (UP)
,10-10 20:34:01.630   924  2922 I WifiHAL : Initializing wifi
,10-10 20:34:01.631   924  2922 I WifiHAL : Creating socket
,10-10 20:34:01.637   924   941 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-10 20:34:01.641   924  2922 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-10 20:34:01.642   924  2922 D wifi    : Did set static halHandle = 0x7f6ff035a0
10-10 20:34:01.642   924  2922 D wifi    : halHandle = 0x7f6ff035a0, mVM = 0x7f8a50d140, mCls = 0x201886
,10-10 20:34:01.642   924  2922 D wifi    : array field set
10-10 20:34:01.642   924  2922 I WifiNative-HAL: interface[0] = wlan0
,10-10 20:34:01.644   924  5663 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547338859936
10-10 20:34:01.644   924  5663 D wifi    : waitForHalEvents called, vm = 0x7f8a50d140, obj = 0x201886, env = 0x7f6a45ea00
,10-10 20:34:01.731  5664  5664 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-10 20:34:01.748   924  2922 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-10 20:34:01.756  5664  5664 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-10 20:34:01.758  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:01.762  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:01.763  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:01.782  5664  5664 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-10 20:34:01.783  5664  5664 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-10 20:34:01.798   924  2922 D WifiConfigStore: Loading config and enabling all networks 
,10-10 20:34:01.803  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:01.803  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:01.803  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:01.803  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:01.803  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:01.803  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:01.803  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:01.803  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:01.806  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:01.809  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:01.809  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:01.809  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:01.809  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:01.809  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:01.809  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:01.809  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:01.809  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:01.809   924  2922 D WifiConfigStore: loaded 0 passpoint configs
10-10 20:34:01.810   924  2922 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-10 20:34:01.810   924  2922 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-10 20:34:01.811   924  2922 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-10 20:34:01.811  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-10 20:34:01.812   924  2922 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-10 20:34:01.812   924  2922 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-10 20:34:01.813   924  2922 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,10-10 20:34:01.813   924  2922 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-10 20:34:01.816  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:01.816  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:01.816  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:01.816  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:01.816  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:01.816  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:01.816  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:01.816  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:01.816   924  2922 D WifiNative-HAL: Setting external_sim to 1
10-10 20:34:01.817   924  2922 D wifi    : setting dfs flag to true, 0x7f706adc60
10-10 20:34:01.817   924  2922 D WifiStateMachine: Setting OUI to DA-A1-19
10-10 20:34:01.818   924  2922 D wifi    : setting scan oui 0x7f706adc60
10-10 20:34:01.818   924  2922 D WifiHAL : Sending mac address OUI
10-10 20:34:01.818  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:01.820  4738  4738 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-10 20:34:01.823   924  2922 E native  : do suspend false
,10-10 20:34:01.830   924  2922 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-10 20:34:01.830   506   915 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-10 20:34:01.831   924   924 D RttService: SCAN_AVAILABLE : 3
10-10 20:34:01.831   924  3031 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-10 20:34:01.832   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:01.835   924  2918 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-10 20:34:01.835   924  2918 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-10 20:34:01.845   924  2918 D WifiNative-HAL: p2pGetDeviceAddress
,10-10 20:34:01.850   924  2918 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
10-10 20:34:01.850   924   939 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=242067 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-10 20:34:02.019  5566  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:02.023   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:02.034  4176  4195 D BluetoothAdapterState: Current state: ON, message: 23
10-10 20:34:02.034  4176  4195 D BluetoothAdapterProperties: Setting state to 13
10-10 20:34:02.034  4176  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-10 20:34:02.036  4176  4195 D BluetoothAdapterProperties: onBluetoothDisable()
,10-10 20:34:02.041  4176  4176 D BluetoothMapService: onReceive
,10-10 20:34:02.041  4176  4176 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-10 20:34:02.041  4176  4176 D BluetoothMapService: STATE_TURNING_OFF
,10-10 20:34:02.042  4176  4176 D BluetoothMapService: MAP Service closeService in
10-10 20:34:02.042  4176  4176 D BluetoothMapMasInstance0: MAP Service shutdown
10-10 20:34:02.042  4176  4176 D ObexServerSockets0: shutdown(block = true)
10-10 20:34:02.038  4176  4195 I BluetoothAdapterState: Entering PendingCommandState
10-10 20:34:02.043  4176  4176 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-10 20:34:02.043  4176  4176 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-10 20:34:02.044  4176  4359 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-10 20:34:02.046  4176  4324 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-10 20:34:02.046  4176  4358 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-10 20:34:02.052  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:02.052  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:02.052  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:02.052  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:02.052  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:02.052  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:02.052  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:02.052  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:02.052  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-10 20:34:02.053  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-10 20:34:02.054  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-10 20:34:02.055  4176  4176 I BtOppRfcommListener: stopping Accept Thread
,10-10 20:34:02.056  4176  5149 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,10-10 20:34:02.056  4176  5149 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-10 20:34:02.059  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:02.059  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:02.059  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:02.059  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:02.059  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:02.059  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:02.059  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:02.059  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:02.059  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-10 20:34:02.061  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:02.061  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:02.066  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:02.066  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:02.066  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:02.066  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:02.066  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:02.066  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:02.066  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:02.066  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:02.066  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-10 20:34:02.068  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:02.068  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:02.084   924   937 I ActivityManager: Start proc 5669:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-10 20:34:02.085  4176  4199 D BluetoothAdapterProperties: Scan Mode:20
,10-10 20:34:02.086  4176  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-10 20:34:02.089  4176  4176 D HeadsetService: Received stop request...Stopping profile...
10-10 20:34:02.090  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:02.092   924   924 D BluetoothHeadset: Proxy object disconnected
10-10 20:34:02.092   924   924 D BluetoothHeadset: Proxy object disconnected
10-10 20:34:02.092   924   924 D BluetoothHeadset: Proxy object disconnected
10-10 20:34:02.093  3077  3922 D BluetoothHeadset: Proxy object disconnected
10-10 20:34:02.093  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:02.093  3077  3077 D HeadsetProfile: Bluetooth service disconnected
10-10 20:34:02.093  3721  3946 D BluetoothHeadset: Proxy object disconnected
10-10 20:34:02.096  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:02.096  4176  4176 D A2dpService: Received stop request...Stopping profile...
10-10 20:34:02.097  4176  4329 D A2dpStateMachine: Exit Disconnected: -1
10-10 20:34:02.099   924   924 D BluetoothA2dp: Proxy object disconnected
10-10 20:34:02.099  3077  3077 D BluetoothA2dp: Proxy object disconnected
10-10 20:34:02.101  4176  4176 D HidService: Received stop request...Stopping profile...
10-10 20:34:02.101  4176  4176 D HidService: Stopping Bluetooth HidService
,10-10 20:34:02.102  3077  3077 D BluetoothInputDevice: Proxy object disconnected
10-10 20:34:02.102  3077  3077 D HidProfile: Bluetooth service disconnected
10-10 20:34:02.102  4176  4176 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:02.102  4176  4176 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:02.102  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
,10-10 20:34:02.102  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:02.103  4176  4176 D HealthService: Received stop request...Stopping profile...
10-10 20:34:02.106  4176  4176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-10 20:34:02.106  4176  4176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-10 20:34:02.106  4176  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-10 20:34:02.106  4176  4304 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:02.106  4176  4304 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:02.106  4176  4304 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:02.106  4176  4176 D PanService: Received stop request...Stopping profile...
10-10 20:34:02.107  3077  3077 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-10 20:34:02.107  3077  3077 D PanProfile: Bluetooth service disconnected
10-10 20:34:02.107  4176  4199 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-10 20:34:02.108  4176  4176 D BluetoothMapService: Received stop request...Stopping profile...
10-10 20:34:02.108  4176  4176 D BluetoothMapService: stop()
10-10 20:34:02.108  4176  4176 D BluetoothMapAppObserver: deinitObservers()
10-10 20:34:02.109  4176  4176 D BluetoothMapAppObserver: removeReceiver()
10-10 20:34:02.110  3077  3077 D BluetoothMap: Proxy object disconnected
10-10 20:34:02.110  3077  3077 D MapProfile: Bluetooth service disconnected
,10-10 20:34:02.112  4176  4176 D SapService: Received stop request...Stopping profile...
,10-10 20:34:02.112  4176  4176 V SapService: stop()
10-10 20:34:02.113  4176  4176 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:02.113  4176  4176 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:02.114  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:02.114  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:02.115  4176  4304 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:02.115  4176  4304 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:02.115  4176  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-10 20:34:02.115  4176  4304 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-10 20:34:02.115  4176  4304 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-10 20:34:02.115  4176  4304 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-10 20:34:02.115  4176  4304 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-10 20:34:02.117  4176  4176 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:02.117  4176  4176 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:02.117  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:02.117  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:02.117  4176  4176 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-10 20:34:02.117  4176  4176 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-10 20:34:02.118  4176  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-10 20:34:02.118  4176  4176 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:02.118  4176  4176 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:02.118  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:02.118  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:02.118  4176  4176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-10 20:34:02.118  4176  4199 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-10 20:34:02.118  4176  4176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-10 20:34:02.119  4176  4176 V BluetoothAdapterState: isTurningOff()=true
,10-10 20:34:02.119  4176  4176 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:02.119  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:02.119  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:02.119  4176  4176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-10 20:34:02.119  4176  4176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-10 20:34:02.120  4176  4176 D BluetoothMapService: MAP Service closeService in
10-10 20:34:02.121  4176  4176 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:02.121  4176  4176 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:02.121  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
,10-10 20:34:02.121  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
,10-10 20:34:02.121  4176  4176 D BluetoothMapService: cleanup()
10-10 20:34:02.121  4176  4176 D BluetoothMapService: MAP Service closeService in
10-10 20:34:02.122  4176  4176 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:02.123  4176  4176 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:02.123  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:02.123  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:02.123  4176  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-10 20:34:02.123  4176  4195 D BluetoothAdapterProperties: Setting state to 15
10-10 20:34:02.123  4176  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-10 20:34:02.123  4176  4195 I BluetoothAdapterState: Entering BleOnState
,10-10 20:34:02.124  3077  3090 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:02.125  3077  3091 D BluetoothMap: onBluetoothStateChange: up=false
10-10 20:34:02.126  3077  3922 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-10 20:34:02.126  3721  3749 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:02.126  3077  3090 D BluetoothPbap: onBluetoothStateChange: up=false
10-10 20:34:02.127   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:02.127   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:02.127   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:02.127   924   941 D BluetoothA2dp: onBluetoothStateChange: up=false
10-10 20:34:02.127  3077  3091 D BluetoothPan: onBluetoothStateChange on: false
10-10 20:34:02.128  3077  3922 D BluetoothA2dp: onBluetoothStateChange: up=false
10-10 20:34:02.129  4176  4195 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-10 20:34:02.129  4176  4195 D BluetoothAdapterProperties: Setting state to 16
,10-10 20:34:02.129  4176  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-10 20:34:02.130  4176  4195 D BluetoothAdapterProperties: onBleDisable
,10-10 20:34:02.130  4176  4195 I BluetoothAdapterState: Entering PendingCommandState
10-10 20:34:02.130  4176  4196 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-10 20:34:02.131  4176  4199 D BluetoothAdapterProperties: Scan Mode:20
10-10 20:34:02.132  4176  4304 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-10 20:34:02.132  4176  4304 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-10 20:34:02.133  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:02.134  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:02.136  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:02.138  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:02.141  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:02.143  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:02.149  5669  5669 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-10 20:34:02.159  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-10 20:34:02.165   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8808569:true
,10-10 20:34:02.166  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-10 20:34:02.179   924  3054 I ActivityManager: Start proc 5681:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-10 20:34:02.191  5669  5669 D LocalBluetoothProfileManager: Adding local MAP profile
,10-10 20:34:02.194  5669  5669 D BluetoothMap: Create BluetoothMap proxy object
,10-10 20:34:02.212  5681  5681 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-10 20:34:02.215  5669  5669 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-10 20:34:02.227  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,10-10 20:34:02.234   924  3787 I ActivityManager: Killing 4453:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-10 20:34:02.337  4176  4199 I bt_hci  : shut_down
,10-10 20:34:02.339  4176  4207 D bt_hwcfg: hw_epilog_process
10-10 20:34:02.339  4176  4207 I bt_vendor: low_power_mode_cb
,10-10 20:34:02.342  4176  4207 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-10 20:34:02.342  4176  4207 I bt_vendor: epilog_cb
10-10 20:34:02.342  4176  4207 I bt_hci  : epilog_finished_callback
,10-10 20:34:02.344  4176  4199 I bt_hci_h4: hal_close
,10-10 20:34:02.345  4176  4199 I bt_userial_vendor: device fd = 54 close
,10-10 20:34:02.446  5681  5681 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.io.File.exists(File.java:361)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-10 20:34:02.446  5681  5681 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-10 20:34:02.446  5681  5681 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-10 20:34:02.446  5681  5681 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.r.e.b(PG:170)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-10 20:34:02.446  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-10 20:34:02.447  5681  5681 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-10 20:34:02.447  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.r.k.d(PG:583)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.r.e.b(PG:170)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-10 20:34:02.447  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-10 20:34:02.449  5681  5681 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at java.io.File.exists(File.java:361)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-10 20:34:02.449  5681  5681 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at java.io.File.exists(File.java:361)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-10 20:34:02.449  5681  5681 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-10 20:34:02.449  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-10 20:34:02.453  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-10 20:34:02.456  4176  4196 D bt_stack_manager: event_shut_down_stack finished.
10-10 20:34:02.456  4176  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-10 20:34:02.457  4176  4195 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-10 20:34:02.457  4176  4176 D BtGatt.DebugUtils: handleDebugAction() action=null
10-10 20:34:02.458  4176  4176 D BtGatt.GattService: Received stop request...Stopping profile...
10-10 20:34:02.458  4176  4176 D BtGatt.GattService: stop()
10-10 20:34:02.458  4176  4176 D BtGatt.AdvertiseManager: advertise clients cleared
10-10 20:34:02.459  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-10 20:34:02.461  4176  4176 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:02.461  4176  4176 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:02.461  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:02.461  4176  4176 V BluetoothAdapterState: isBleTurningOff()=true
10-10 20:34:02.461  4176  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-10 20:34:02.461  4176  4195 D BluetoothAdapterProperties: Setting state to 10
10-10 20:34:02.461  4176  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-10 20:34:02.463   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-10 20:34:02.463  4176  4195 I BluetoothAdapterState: Entering OffState
10-10 20:34:02.470  4176  4176 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-10 20:34:02.470  4176  4176 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-10 20:34:02.470  4176  4176 I BluetoothServiceJni: cleanupNative: return from cleanup
10-10 20:34:02.471  4176  4196 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-10 20:34:02.477  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,10-10 20:34:02.479   924  3739 I ActivityManager: Killing 5346:com.android.defcontainer/u0a7 (adj 15): empty #17
10-10 20:34:02.486  4176  4196 D bt_stack_manager: event_clean_up_stack finished.
10-10 20:34:02.491  4176  4176 I art     : System.exit called, status: 0
10-10 20:34:02.492  4176  4176 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-10 20:34:02.532  5566  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:02.534   379   379 E lowmemorykiller: Error writing /proc/4176/oom_score_adj; errno=22
10-10 20:34:02.534   924   941 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
10-10 20:34:02.535   924   941 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
10-10 20:34:02.535   924   941 W ActivityManager: Application dead when creating service ServiceRecord{6f9c438 u0 com.android.bluetooth/.btservice.AdapterService}
,10-10 20:34:02.541   924   941 I ActivityManager: Process com.android.bluetooth (pid 4176) has died
,10-10 20:34:02.541   924   941 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,10-10 20:34:02.542   924   941 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
10-10 20:34:02.543   924   941 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
10-10 20:34:02.543   924   941 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-10 20:34:02.543   924   941 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
10-10 20:34:02.543   924   941 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
10-10 20:34:02.543   924   941 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
10-10 20:34:02.543   924   941 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
10-10 20:34:02.543   924   941 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
10-10 20:34:02.543   924   941 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:02.543   924   941 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:02.543   924   941 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-10 20:34:02.543   924   941 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-10 20:34:02.543   924  3739 W ActivityManager: Spurious death for ProcessRecord{eae11c7 0:com.android.bluetooth/1002}, curProc for 4176: null
,10-10 20:34:02.648  5681  5699 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-10 20:34:02.659   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bc74176:true
,10-10 20:34:03.024   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:04.025   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-10 20:34:04.997  5664  5664 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-10 20:34:05.001  5664  5664 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-10 20:34:05.007  5664  5664 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-10 20:34:05.084   924  2922 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-10 20:34:05.086   924  2922 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-10 20:34:05.086   924  2922 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-10 20:34:05.099   924  2922 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-10 20:34:05.137   924  2922 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-10 20:34:05.140  5664  5664 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-10 20:34:05.534   924   941 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,10-10 20:34:05.566  5664  5664 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-10 20:34:05.578   924   941 I ActivityManager: Start proc 5715:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-10 20:34:05.594  5664  5664 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-10 20:34:05.594  5664  5664 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-10 20:34:05.602   924  2922 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-10 20:34:05.602   924  2922 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-10 20:34:05.602   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-10 20:34:05.615   924  2922 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-10 20:34:05.626   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:05.633   924  2922 D WifiStateMachine: Start Dhcp Watchdog 2
,10-10 20:34:05.638   924  5730 D DhcpClient: Receive thread started
,10-10 20:34:05.642   924  2924 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-10 20:34:05.642   924  2922 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-10 20:34:05.642   924  2924 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-10 20:34:05.678  5715  5715 D AdapterServiceConfig: Adding HeadsetService
,10-10 20:34:05.678  5715  5715 D AdapterServiceConfig: Adding A2dpService
10-10 20:34:05.678  5715  5715 D AdapterServiceConfig: Adding HidService
10-10 20:34:05.678  5715  5715 D AdapterServiceConfig: Adding HealthService
10-10 20:34:05.679  5715  5715 D AdapterServiceConfig: Adding PanService
10-10 20:34:05.679  5715  5715 D AdapterServiceConfig: Adding GattService
10-10 20:34:05.679  5715  5715 D AdapterServiceConfig: Adding BluetoothMapService
10-10 20:34:05.679  5715  5715 D AdapterServiceConfig: Adding SapService
,10-10 20:34:05.688   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6017647:true
,10-10 20:34:05.689  5715  5715 D BluetoothAdapterState: make() - Creating AdapterState
,10-10 20:34:05.691  5715  5715 I bt_bluedroid: init
10-10 20:34:05.691  5715  5731 I BluetoothAdapterState: Entering OffState
,10-10 20:34:05.693  5715  5732 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-10 20:34:05.693  5715  5732 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-10 20:34:05.693  5715  5732 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-10 20:34:05.693  5715  5732 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-10 20:34:05.694  5715  5715 I bt_bluedroid: get_profile_interface socket
,10-10 20:34:05.695  5715  5715 I bt_bluedroid: get_profile_interface sdp
10-10 20:34:05.695  5715  5735 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-10 20:34:05.697  5715  5735 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-10 20:34:05.701  5715  5725 I bt_bluedroid: config_hci_snoop_log
,10-10 20:34:05.702   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-10 20:34:05.706  5715  5731 D BluetoothAdapterState: Current state: OFF, message: 0
,10-10 20:34:05.706  5715  5731 D BluetoothAdapterProperties: Setting state to 14
10-10 20:34:05.706  5715  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-10 20:34:05.708  5715  5731 D BluetoothBondStateMachine: make
,10-10 20:34:05.710  5715  5736 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-10 20:34:05.714  5715  5731 I BluetoothAdapterState: Entering PendingCommandState
,10-10 20:34:05.714  5715  5715 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-10 20:34:05.717  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:05.718  5715  5715 D BtGatt.DebugUtils: handleDebugAction() action=null
10-10 20:34:05.719  5715  5715 D BtGatt.GattService: Received start request. Starting profile...
10-10 20:34:05.719  5715  5715 D BtGatt.GattService: start()
10-10 20:34:05.720  5715  5715 I bt_bluedroid: get_profile_interface gatt
10-10 20:34:05.720  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:05.721  5715  5715 D BtGatt.AdvertiseManager: advertise manager created
10-10 20:34:05.722   924  2922 E native  : do suspend false
,10-10 20:34:05.726  5715  5715 V BluetoothAdapterState: isTurningOff()=false
,10-10 20:34:05.726  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:05.726  5715  5715 V BluetoothAdapterState: isBleTurningOn()=true
10-10 20:34:05.726  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
,10-10 20:34:05.727  5715  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-10 20:34:05.728  5715  5731 I bt_bluedroid: bt_bluedroid
10-10 20:34:05.728  5715  5732 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-10 20:34:05.729  5715  5732 I bt_hci  : start_up
,10-10 20:34:05.730   924  5729 D DhcpClient: Broadcasting DHCPDISCOVER
,10-10 20:34:05.735  5715  5732 I bt_vendor: alloc value 0xf417f871
,10-10 20:34:05.735  5715  5732 I bt_vendor: init
10-10 20:34:05.735  5715  5732 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-10 20:34:05.735  5715  5732 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-10 20:34:05.743   924  5730 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172595, domain null
,10-10 20:34:05.743   924  5729 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172595 seconds
10-10 20:34:05.744   924  5729 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-10 20:34:05.758   924  5730 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-10 20:34:05.759   924  5729 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-10 20:34:05.760   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:05.761   924  2922 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-10 20:34:05.763   924  5729 D DhcpClient: Scheduling renewal in 86399s
,10-10 20:34:05.769   924  2922 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-10 20:34:05.769   924  2922 D WifiConfigStore: No blacklist allowed without epno enabled
10-10 20:34:05.769   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-10 20:34:05.770   924  2924 D ConnectivityService: Adding iface wlan0 to network 101
,10-10 20:34:05.772   924  2922 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-10 20:34:05.800   924  2924 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-10 20:34:05.800   924  2924 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-10 20:34:05.802   924  2924 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-10 20:34:05.803   924  2924 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-10 20:34:05.804   924  2924 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-10 20:34:05.810   924  2924 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-10 20:34:05.814   924  2924 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-10 20:34:05.814   924  2924 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-10 20:34:05.814   924  2924 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-10 20:34:05.814   924  2922 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-10 20:34:05.814   924  2924 D ConnectivityService:    accepting network in place of null
10-10 20:34:05.814   924  2922 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-10 20:34:05.815   924  2924 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-10 20:34:05.830   924  5728 D NetlinkSocketObserver: NeighborEvent{elapsedMs=246047, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-10 20:34:05.834   506   915 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-10 20:34:05.842  5715  5732 D bt_hci  : start_up starting async portion
10-10 20:34:05.842  5715  5739 I bt_hci  : event_finish_startup
10-10 20:34:05.842  5715  5739 I bt_hci_h4: hal_open
10-10 20:34:05.842  5715  5739 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-10 20:34:05.840  5746  5746 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-10 20:34:05.843  5715  5739 I bt_userial_vendor: device fd = 54 open
,10-10 20:34:05.855   506   915 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-10 20:34:05.855  5715  5739 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-10 20:34:05.857  5715  5739 D bt_hwcfg: Chipset BCM4358A3
10-10 20:34:05.857  5715  5739 D bt_hwcfg: Target name = [BCM4358A3]
10-10 20:34:05.858  5715  5739 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
10-10 20:34:05.858   924  2924 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-10 20:34:05.858  3670  3842 W QCNEJ   : |CORE| network available: 101
10-10 20:34:05.858   924  2924 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-10 20:34:05.860   924  2924 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-10 20:34:05.861   924   941 D Tethering: MasterInitialState.processMessage what=3
10-10 20:34:05.865  3670  3842 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-10 20:34:05.867  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:05.867  3670  3842 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-10 20:34:05.867  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:05.867  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:05.867  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:05.867  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:05.867  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:05.867  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:05.867  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:05.867  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-10 20:34:05.868  3670  3842 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-10 20:34:05.868  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:05.868  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-10 20:34:05.871  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:05.872  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:05.872  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:05.872  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:05.872  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:05.872  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:05.872  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:05.872  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:05.872  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:05.872  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-10 20:34:05.873  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:05.875  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:05.876  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:05.876  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:05.876  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:05.876  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:05.876  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:05.876  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:05.876  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:05.876  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-10 20:34:05.876  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:05.877  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-10 20:34:05.880  4790  4814 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-10 20:34:05.880  4790  4814 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-10 20:34:05.880  4790  4814 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-10 20:34:05.880  4790  4814 E SarControlService: no key has been found,reset the power
10-10 20:34:05.880  4790  4827 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-10 20:34:05.880  4790  4827 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-10 20:34:05.880  4790  4827 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-10 20:34:05.881  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-10 20:34:05.881  4815  4815 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-10 20:34:05.882  4790  4827 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-10 20:34:05.882  4790  4827 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-10 20:34:05.882  4790  4827 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-10 20:34:05.883  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-10 20:34:05.883  4815  4815 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-10 20:34:05.888  3990  3990 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-10 20:34:05.889  4815  4829 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@70117bb HexData = [00000000ec03000000000000ffffffff]
10-10 20:34:05.889  4815  4829 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-10 20:34:05.889  4815  4829 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-10 20:34:05.891  4815  4829 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@70117bb HexData = [00000000ed03000000000000ffffffff]
,10-10 20:34:05.891  4815  4829 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-10 20:34:05.891  4815  4829 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-10 20:34:05.892  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-10 20:34:05.892  4790  4800 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-10 20:34:05.892  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-10 20:34:05.892  4790  4801 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-10 20:34:05.893  3990  3990 D SystemUpdateService: onCreate
10-10 20:34:05.896   924  5726 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
10-10 20:34:05.897  3990  3990 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-10 20:34:05.909  3990  3990 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-10 20:34:05.914  3990  5260 I iu.UploadsManager: num queued entries: 0
,10-10 20:34:05.914  3990  5260 I iu.UploadsManager: num updated entries: 0
10-10 20:34:05.915  3990  5260 I iu.SyncManager: NEXT; no task
,10-10 20:34:05.919  3990  5751 I SystemUpdateService: active receiver: enabled
,10-10 20:34:05.921  3990  3990 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-10 20:34:05.922  3990  3990 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-10 20:34:05.924  5264  5264 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-10 20:34:05.928  5264  5264 D SprintDMHelper: simOperator: 
,10-10 20:34:05.928  5264  5264 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-10 20:34:05.941   924  5726 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 11 Oct 2016 00:34:05 GMT], X-Android-Received-Millis=[1476146045940], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476146045919]}
,10-10 20:34:05.941   924  2924 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-10 20:34:05.942   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-10 20:34:05.942   924  2924 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-10 20:34:05.943   924  2924 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-10 20:34:05.950  3990  5751 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-10 20:34:05.967  3990  5751 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-10 20:34:05.967  3990  5751 I SystemUpdateService: now status is 0 (complete)
10-10 20:34:05.967  3990  5751 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-10 20:34:05.967  3990  5751 I SystemUpdateService: file has been verified
,10-10 20:34:05.968  3990  5751 I SystemUpdateService: OTA package size = 21989297
,10-10 20:34:05.977  3990  5751 I SystemUpdateService: showing system update notification
,10-10 20:34:05.986  3990  3990 D SystemUpdateService: onDestroy
,10-10 20:34:06.030  4738  5756 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-10 20:34:06.045  5715  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-10 20:34:06.160  5715  5739 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-10 20:34:06.161  5715  5739 D bt_hwcfg: Settlement delay -- 100 ms
,10-10 20:34:06.161  5715  5739 I bt_hwcfg: Setting fw settlement delay to 100 
,10-10 20:34:06.285  5715  5739 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-10 20:34:06.285  5715  5739 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-10 20:34:06.287  5715  5739 I bt_hwcfg: vendor lib fwcfg completed
,10-10 20:34:06.287  5715  5739 I bt_vendor: firmware callback
,10-10 20:34:06.287  5715  5739 I bt_hci  : firmware_config_callback
,10-10 20:34:06.296  5715  5763 I bt_btu  : btu_task pending for preload complete event,
10-10 20:34:06.297  5715  5763 I bt_btu_task: Bluetooth chip preload is complete
,10-10 20:34:06.297  5715  5763 I bt_btu  : btu_task received preload complete event
,10-10 20:34:06.303  5715  5763 I         : BTE_InitTraceLevels -- TRC_HCI
,10-10 20:34:06.303  5715  5763 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_AVDT
10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_AVRC
10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_A2D
10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_BNEP
10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_BTM
,10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_GAP
10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_PAN
10-10 20:34:06.304  5715  5763 I         : BTE_InitTraceLevels -- TRC_SDP
10-10 20:34:06.305  5715  5763 I         : BTE_InitTraceLevels -- TRC_GATT
10-10 20:34:06.305  5715  5763 I         : BTE_InitTraceLevels -- TRC_SMP
,10-10 20:34:06.305  5715  5763 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-10 20:34:06.305  5715  5763 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-10 20:34:06.390  5715  5763 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40fd549
,10-10 20:34:06.390  5715  5763 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40fd549 
,10-10 20:34:06.412  5715  5735 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-10 20:34:06.413  5715  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-10 20:34:06.414  5715  5735 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-10 20:34:06.416  5715  5735 D BluetoothAdapterProperties: Name is: Nexus 6P
10-10 20:34:06.419  5715  5735 D BluetoothAdapterProperties: Scan Mode:20
10-10 20:34:06.420  5715  5735 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-10 20:34:06.420  5715  5735 D bt_hci  : do_postload posting postload work item
,10-10 20:34:06.420  5715  5739 I bt_hci  : event_postload
,10-10 20:34:06.420  5715  5739 I bt_vendor: sco_config_cb
,10-10 20:34:06.420  5715  5739 I bt_hci  : sco_config_callback postload finished.
10-10 20:34:06.427  5715  5739 I bt_vendor: low_power_mode_cb
10-10 20:34:06.427  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.428  5715  5735 D bt_bte_conf: Device ID record 1 : primary
10-10 20:34:06.428  5715  5735 D bt_bte_conf:   vendorId            = 000f
10-10 20:34:06.428  5715  5735 D bt_bte_conf:   vendorIdSource      = 0001
10-10 20:34:06.428  5715  5735 D bt_bte_conf:   product             = 1200
10-10 20:34:06.428  5715  5735 D bt_bte_conf:   version             = 1436
10-10 20:34:06.428  5715  5735 D bt_bte_conf:   clientExecutableURL = 
10-10 20:34:06.429  5715  5735 D bt_bte_conf:   serviceDescription  = 
,10-10 20:34:06.429  5715  5735 D bt_bte_conf:   documentationURL    = 
10-10 20:34:06.429  5715  5735 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-10 20:34:06.429  5715  5732 D bt_stack_manager: event_start_up_stack finished
,10-10 20:34:06.432  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:06.436  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.436  5715  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-10 20:34:06.436  5715  5731 D BluetoothAdapterProperties: Setting state to 15
,10-10 20:34:06.436  5715  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-10 20:34:06.437  5715  5731 I BluetoothAdapterState: Entering BleOnState
,10-10 20:34:06.440  5715  5731 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-10 20:34:06.440  5715  5731 D BluetoothAdapterProperties: Setting state to 11
10-10 20:34:06.440  5715  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-10 20:34:06.446  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:06.447  5715  5715 D HeadsetService: Received start request. Starting profile...
,10-10 20:34:06.450  5715  5715 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-10 20:34:06.450  5715  5715 D HeadsetStateMachine: make
10-10 20:34:06.450  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:06.454  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.458  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:06.460  5715  5731 I BluetoothAdapterState: Entering PendingCommandState
,10-10 20:34:06.461  5715  5715 D HeadsetStateMachine: max_hf_connections = 1
10-10 20:34:06.461  5715  5715 I bt_bluedroid: get_profile_interface handsfree
10-10 20:34:06.461  5715  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-10 20:34:06.461  5715  5735 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-10 20:34:06.464  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
,10-10 20:34:06.464  5715  5715 D A2dpService: Received start request. Starting profile...
,10-10 20:34:06.465  5715  5715 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-10 20:34:06.465  5715  5715 I bt_bluedroid: get_profile_interface avrcp
,10-10 20:34:06.470  5715  5715 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-10 20:34:06.470  5715  5715 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-10 20:34:06.470  5715  5715 D A2dpStateMachine: make
10-10 20:34:06.471  5715  5715 I bt_bluedroid: get_profile_interface a2dp
,10-10 20:34:06.472  5715  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-10 20:34:06.473  5715  5772 D A2dpStateMachine: Enter Disconnected: -2
,10-10 20:34:06.474  5715  5715 I BluetoothHidServiceJni: classInitNative: succeeds
,10-10 20:34:06.474  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
,10-10 20:34:06.476  5669  5669 D BluetoothInputDevice: Proxy object connected
,10-10 20:34:06.476  5715  5715 D HidService: Received start request. Starting profile...
10-10 20:34:06.476  5715  5715 I bt_bluedroid: get_profile_interface hidhost
10-10 20:34:06.476  5715  5715 D HidService: setHidService(): set to: null
10-10 20:34:06.476  5669  5669 D HidProfile: Bluetooth service connected
10-10 20:34:06.476  5715  5735 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40de56d
10-10 20:34:06.477  5715  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-10 20:34:06.477  5715  5715 I BluetoothHealthServiceJni: classInitNative: succeeds
10-10 20:34:06.478  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
,10-10 20:34:06.478  5715  5715 D HealthService: Received start request. Starting profile...
,10-10 20:34:06.480  5715  5715 I bt_bluedroid: get_profile_interface health
,10-10 20:34:06.480  5715  5715 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-10 20:34:06.481  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
,10-10 20:34:06.482  5715  5715 D PanService: Received start request. Starting profile...
10-10 20:34:06.482  5669  5669 D BluetoothPan: BluetoothPAN Proxy object connected
10-10 20:34:06.482  5715  5715 D BluetoothPanServiceJni: initializeNative(L110): pan
10-10 20:34:06.482  5715  5715 I bt_bluedroid: get_profile_interface pan
,10-10 20:34:06.483  5669  5669 D PanProfile: Bluetooth service connected
10-10 20:34:06.483  5715  5735 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-10 20:34:06.485  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:06.486  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-10 20:34:06.488  5715  5715 D BluetoothMapService: Received start request. Starting profile...
,10-10 20:34:06.488  5715  5715 D BluetoothMapService: start()
10-10 20:34:06.488  5669  5669 D BluetoothMap: Proxy object connected
,10-10 20:34:06.489  5669  5669 D MapProfile: Bluetooth service connected
,10-10 20:34:06.490  5669  5669 D BluetoothMap: getConnectedDevices()
10-10 20:34:06.490  5669  5669 D BluetoothMap: Bluetooth is Not enabled
10-10 20:34:06.491  5715  5715 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-10 20:34:06.492  5715  5715 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-10 20:34:06.492  5715  5715 D BluetoothMapAppObserver: createReceiver()
,10-10 20:34:06.493  5715  5715 D BluetoothMapAppObserver: initObservers()
,10-10 20:34:06.493  5715  5715 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-10 20:34:06.498  5715  5715 V SapService: SapBinder()
,10-10 20:34:06.498  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:06.499  5715  5715 D SapService: Received start request. Starting profile...
10-10 20:34:06.499  5715  5715 V SapService: start()
,10-10 20:34:06.500  5715  5715 V BluetoothAdapterState: isTurningOff()=false
,10-10 20:34:06.500  5715  5715 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:06.500  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.501  5715  5770 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.501  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.502  5715  5715 V BluetoothAdapterState: isTurningOff()=false
,10-10 20:34:06.502  5715  5715 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:06.502  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.502  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.503  5715  5715 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:06.503  5715  5715 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:06.503  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.503  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
,10-10 20:34:06.503  5715  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-10 20:34:06.503  5715  5731 D BluetoothAdapterProperties: ScanMode =  20
10-10 20:34:06.503  5715  5731 D BluetoothAdapterProperties: State =  11
10-10 20:34:06.503  5715  5731 D BluetoothAdapterProperties: Setting state to 12
10-10 20:34:06.504  5715  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-10 20:34:06.504  5715  5731 I BluetoothAdapterState: Entering OnState
10-10 20:34:06.504  3077  3090 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-10 20:34:06.505  3077  3922 D BluetoothMap: onBluetoothStateChange: up=true
,10-10 20:34:06.506  5715  5735 D BluetoothAdapterProperties: Scan Mode:21
10-10 20:34:06.506  5715  5735 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-10 20:34:06.507  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-10 20:34:06.508  3077  3077 D BluetoothMap: Proxy object connected
10-10 20:34:06.508  3077  3077 D MapProfile: Bluetooth service connected
10-10 20:34:06.508  3077  3077 D BluetoothMap: getConnectedDevices()
10-10 20:34:06.508  5669  5680 D BluetoothPbap: onBluetoothStateChange: up=true
,10-10 20:34:06.509  5566  5566 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,10-10 20:34:06.510  3077  3090 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-10 20:34:06.511  5566  5566 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-10 20:34:06.512  3077  3077 D BluetoothInputDevice: Proxy object connected
10-10 20:34:06.512  3077  3077 D HidProfile: Bluetooth service connected
,10-10 20:34:06.513  3721  3749 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-10 20:34:06.514  3077  3091 D BluetoothPbap: onBluetoothStateChange: up=true
10-10 20:34:06.516  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:06.516  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:06.516  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:06.516  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:06.516  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:06.516  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:06.516  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:06.516  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-10 20:34:06.517   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
10-10 20:34:06.517  5669  5679 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-10 20:34:06.517   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
10-10 20:34:06.517   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
10-10 20:34:06.517   924   941 D BluetoothA2dp: onBluetoothStateChange: up=true
10-10 20:34:06.518  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:06.519  5715  5715 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-10 20:34:06.519  5669  5680 D BluetoothMap: onBluetoothStateChange: up=true
10-10 20:34:06.519  5715  5715 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-10 20:34:06.520  5669  5679 D BluetoothPan: onBluetoothStateChange on: true
10-10 20:34:06.521  3077  3922 D BluetoothPan: onBluetoothStateChange on: true
10-10 20:34:06.522  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:06.522  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:06.522  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:06.522  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:06.522  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:06.522  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:06.522  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:06.522  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:06.524  3077  3077 D BluetoothPan: BluetoothPAN Proxy object connected
10-10 20:34:06.524  3077  3077 D PanProfile: Bluetooth service connected
10-10 20:34:06.524  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:06.524  3077  3091 D BluetoothA2dp: onBluetoothStateChange: up=true
10-10 20:34:06.526  5715  5715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-10 20:34:06.527   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
,10-10 20:34:06.530  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:06.530  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:06.530  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:06.530  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:06.530  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:06.530  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:06.530  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:06.530  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:06.531  5669  5669 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-10 20:34:06.531  5715  5715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-10 20:34:06.533  5715  5715 D ObexServerSockets: Succeed to create listening sockets 
10-10 20:34:06.533  5715  5715 D ObexServerSockets0: startAccept()
10-10 20:34:06.533  5715  5715 D ObexServerSockets0: prepareForNewConnect()
10-10 20:34:06.534  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:06.534  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-10 20:34:06.535  5669  5669 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-10 20:34:06.536  5715  5715 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-10 20:34:06.536  5715  5715 D BluetoothSdpJni: SDP Create record success - handle: 0
10-10 20:34:06.536  5715  5780 D ObexServerSockets0: Accepting socket connection...
,10-10 20:34:06.536  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.537  3077  3077 D BluetoothA2dp: Proxy object connected
10-10 20:34:06.537  5715  5715 D BluetoothMapService: onReceive
10-10 20:34:06.537  5715  5781 D ObexServerSockets0: Accepting socket connection...
10-10 20:34:06.537   924   924 D BluetoothA2dp: Proxy object connected
10-10 20:34:06.537  5715  5715 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-10 20:34:06.538  5715  5715 D BluetoothMapService: STATE_ON
10-10 20:34:06.539  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.539  5715  5782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-10 20:34:06.540  5715  5782 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-10 20:34:06.540  5715  5782 D BluetoothSdpJni: SDP Create record success - handle: 1
10-10 20:34:06.543  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.547  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-10 20:34:06.547  5566  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:06.548  5566  5612 D io.jxcore.node.ConnectivityMonitor: stop
10-10 20:34:06.548  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-10 20:34:06.549  5669  5669 D BluetoothA2dp: Proxy object connected
,10-10 20:34:06.550  5566  5612 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,10-10 20:34:06.551  5566  5612 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,10-10 20:34:06.553  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-10 20:34:06.554  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.557  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,10-10 20:34:06.561  5669  5669 D BluetoothPbap: Proxy object connected
,10-10 20:34:06.561  3077  3077 D BluetoothPbap: Proxy object connected
10-10 20:34:06.561  3077  3077 D PbapServerProfile: Bluetooth service connected
10-10 20:34:06.561  5669  5669 D PbapServerProfile: Bluetooth service connected
10-10 20:34:06.562  5715  5731 D BluetoothAdapterState: Current state: ON, message: 23
10-10 20:34:06.562  5715  5731 D BluetoothAdapterProperties: Setting state to 13
10-10 20:34:06.562  5715  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-10 20:34:06.563  5715  5731 D BluetoothAdapterProperties: onBluetoothDisable()
,10-10 20:34:06.563  5715  5731 I BluetoothAdapterState: Entering PendingCommandState
10-10 20:34:06.564  5715  5735 D BluetoothAdapterProperties: Scan Mode:20
10-10 20:34:06.564  5715  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-10 20:34:06.567  3077  3077 D BluetoothPbap: Proxy object disconnected
10-10 20:34:06.567  3077  3077 D PbapServerProfile: Bluetooth service disconnected
,10-10 20:34:06.569  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:06.569  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:06.569  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:06.569  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:06.569  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:06.569  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:06.569  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:06.569  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:06.569  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:06.571  5669  5669 D BluetoothPbap: Proxy object disconnected
10-10 20:34:06.571  5669  5669 D PbapServerProfile: Bluetooth service disconnected
10-10 20:34:06.572  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:06.572  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-10 20:34:06.575  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:06.575  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:06.575  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:06.575  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:06.575  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:06.575  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:06.575  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:06.575  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:06.575  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:06.576  5566  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:06.576  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-10 20:34:06.580  5715  5715 D HeadsetService: Received stop request...Stopping profile...
,10-10 20:34:06.582  5715  5715 D A2dpService: Received stop request...Stopping profile...
,10-10 20:34:06.582  5715  5772 D A2dpStateMachine: Exit Disconnected: -1
,10-10 20:34:06.583  3077  3077 D BluetoothA2dp: Proxy object disconnected
10-10 20:34:06.583   924   924 D BluetoothA2dp: Proxy object disconnected
10-10 20:34:06.584  5715  5715 D HidService: Received stop request...Stopping profile...
10-10 20:34:06.584  5715  5715 D HidService: Stopping Bluetooth HidService
10-10 20:34:06.584  3077  3077 D BluetoothInputDevice: Proxy object disconnected
10-10 20:34:06.584  3077  3077 D HidProfile: Bluetooth service disconnected
10-10 20:34:06.585  5715  5715 D HealthService: Received stop request...Stopping profile...
10-10 20:34:06.586  5715  5715 D PanService: Received stop request...Stopping profile...
10-10 20:34:06.587  3077  3077 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-10 20:34:06.588  3077  3077 D PanProfile: Bluetooth service disconnected
10-10 20:34:06.589  5715  5715 D BluetoothMapService: Received stop request...Stopping profile...
10-10 20:34:06.589  5715  5715 D BluetoothMapService: stop()
10-10 20:34:06.590  5715  5715 D BluetoothMapAppObserver: deinitObservers()
10-10 20:34:06.590  5715  5715 D BluetoothMapAppObserver: removeReceiver()
10-10 20:34:06.591  3077  3077 D BluetoothMap: Proxy object disconnected
10-10 20:34:06.591  3077  3077 D MapProfile: Bluetooth service disconnected
10-10 20:34:06.591  5715  5715 D SapService: Received stop request...Stopping profile...
10-10 20:34:06.591  5715  5715 V SapService: stop()
10-10 20:34:06.592  5669  5669 D BluetoothA2dp: Proxy object disconnected
10-10 20:34:06.593  5715  5715 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:06.593  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:06.593  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.593  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.593  5669  5669 D BluetoothInputDevice: Proxy object disconnected
10-10 20:34:06.593  5669  5669 D HidProfile: Bluetooth service disconnected
10-10 20:34:06.593  5669  5669 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-10 20:34:06.593  5669  5669 D PanProfile: Bluetooth service disconnected
10-10 20:34:06.593  5669  5669 D BluetoothMap: Proxy object disconnected
10-10 20:34:06.593  5669  5669 D MapProfile: Bluetooth service disconnected
10-10 20:34:06.594  5715  5715 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-10 20:34:06.594  5715  5715 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-10 20:34:06.594  5715  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-10 20:34:06.594  5715  5763 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:06.594  5715  5715 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:06.594  5715  5763 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:06.594  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:06.594  5715  5763 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:06.594  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
,10-10 20:34:06.594  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.594  5715  5735 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
10-10 20:34:06.595  5715  5763 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:06.595  5715  5715 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:06.595  5715  5763 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:06.595  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:06.595  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.596  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.596  5715  5715 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-10 20:34:06.596  5715  5715 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-10 20:34:06.596  5715  5715 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:06.596  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:06.596  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.596  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.596  5715  5715 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-10 20:34:06.597  5715  5715 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-10 20:34:06.597  5715  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-10 20:34:06.597  5715  5735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-10 20:34:06.597  5715  5763 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-10 20:34:06.597  5715  5735 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-10 20:34:06.597  5715  5763 W bt_l2cap: btif_in_execute_service_request: Unknown service
10-10 20:34:06.597  5715  5763 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-10 20:34:06.597  5715  5763 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-10 20:34:06.598  5715  5715 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:06.598  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:06.598  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.598  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.598  5715  5715 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-10 20:34:06.598  5715  5715 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-10 20:34:06.600  5715  5715 D BluetoothMapService: MAP Service closeService in
10-10 20:34:06.600  5715  5715 D BluetoothMapMasInstance0: MAP Service shutdown
10-10 20:34:06.600  5715  5715 D ObexServerSockets0: shutdown(block = true)
10-10 20:34:06.600  5715  5780 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-10 20:34:06.601  5715  5715 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-10 20:34:06.601  5715  5715 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-10 20:34:06.601  5715  5781 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-10 20:34:06.601  5715  5715 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:06.601  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:06.601  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.601  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.602  5715  5715 D BluetoothMapService: cleanup()
,10-10 20:34:06.602  5715  5715 D BluetoothMapService: MAP Service closeService in
10-10 20:34:06.602  5715  5765 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-10 20:34:06.602  5715  5715 V BluetoothAdapterState: isTurningOff()=true
10-10 20:34:06.602  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:06.603  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:06.603  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:06.603  5715  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-10 20:34:06.603  5715  5731 D BluetoothAdapterProperties: Setting state to 15
10-10 20:34:06.603  5715  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-10 20:34:06.603  5715  5731 I BluetoothAdapterState: Entering BleOnState
,10-10 20:34:06.615  3077  3091 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-10 20:34:06.615  3077  3090 D BluetoothMap: onBluetoothStateChange: up=false
10-10 20:34:06.616  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:06.616  5669  5680 D BluetoothPbap: onBluetoothStateChange: up=false
10-10 20:34:06.617  3077  3922 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-10 20:34:06.617  3721  3946 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-10 20:34:06.618  3077  3091 D BluetoothPbap: onBluetoothStateChange: up=false
,10-10 20:34:06.618  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.618   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:06.619  5669  5679 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-10 20:34:06.619   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:06.619   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:06.619   924   941 D BluetoothA2dp: onBluetoothStateChange: up=false
10-10 20:34:06.619  5669  5680 D BluetoothMap: onBluetoothStateChange: up=false
10-10 20:34:06.620  5669  5679 D BluetoothPan: onBluetoothStateChange on: false
10-10 20:34:06.620  5669  5680 D BluetoothHeadset: onBluetoothStateChange: up=false
10-10 20:34:06.621  3077  3090 D BluetoothPan: onBluetoothStateChange on: false
10-10 20:34:06.621  5669  5679 D BluetoothA2dp: onBluetoothStateChange: up=false
10-10 20:34:06.621  3077  3922 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-10 20:34:06.622  5715  5731 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-10 20:34:06.622  5715  5731 D BluetoothAdapterProperties: Setting state to 16
10-10 20:34:06.622  5715  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-10 20:34:06.622  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-10 20:34:06.623  5715  5731 D BluetoothAdapterProperties: onBleDisable
10-10 20:34:06.624  5715  5731 I BluetoothAdapterState: Entering PendingCommandState
10-10 20:34:06.624  5715  5732 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-10 20:34:06.625  5715  5763 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-10 20:34:06.625  5715  5763 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-10 20:34:06.627  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:06.629  5715  5735 D BluetoothAdapterProperties: Scan Mode:20
10-10 20:34:06.630  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:06.633  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:06.635  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:06.639  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-10 20:34:06.646  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,10-10 20:34:06.649  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-10 20:34:06.654  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-10 20:34:06.656  5669  5669 D DockEventReceiver: finishStartingService: stopping service
,10-10 20:34:06.825  5715  5735 I bt_hci  : shut_down
,10-10 20:34:06.825  5715  5739 D bt_hwcfg: hw_epilog_process
10-10 20:34:06.826  5715  5739 I bt_vendor: low_power_mode_cb
,10-10 20:34:06.828  5715  5739 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-10 20:34:06.828  5715  5739 I bt_vendor: epilog_cb
10-10 20:34:06.829  5715  5739 I bt_hci  : epilog_finished_callback
,10-10 20:34:06.829  5715  5735 I bt_hci_h4: hal_close
,10-10 20:34:06.843  5715  5735 I bt_userial_vendor: device fd = 54 close
,10-10 20:34:06.858   924  2924 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-10 20:34:06.965  5715  5732 D bt_stack_manager: event_shut_down_stack finished.
,10-10 20:34:06.966  5715  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-10 20:34:06.970  5715  5731 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-10 20:34:06.970  5715  5715 D BtGatt.DebugUtils: handleDebugAction() action=null
10-10 20:34:06.972  5715  5715 D BtGatt.GattService: Received stop request...Stopping profile...
10-10 20:34:06.972  5715  5715 D BtGatt.GattService: stop()
10-10 20:34:06.972  5715  5715 D BtGatt.AdvertiseManager: advertise clients cleared
10-10 20:34:06.976  5715  5715 V BluetoothAdapterState: isTurningOff()=false
,10-10 20:34:06.976  5715  5715 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:06.976  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
,10-10 20:34:06.976  5715  5715 V BluetoothAdapterState: isBleTurningOff()=true
10-10 20:34:06.977  5715  5731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-10 20:34:06.977  5715  5731 D BluetoothAdapterProperties: Setting state to 10
10-10 20:34:06.977  5715  5731 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-10 20:34:06.978  5715  5731 I BluetoothAdapterState: Entering OffState
10-10 20:34:06.980   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-10 20:34:06.994  5715  5715 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-10 20:34:06.994  5715  5715 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-10 20:34:06.994  5715  5715 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-10 20:34:06.998  5715  5732 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-10 20:34:07.004  5715  5715 I art     : System.exit called, status: 0
,10-10 20:34:07.005  5715  5715 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-10 20:34:07.033   924  3356 I ActivityManager: Process com.android.bluetooth (pid 5715) has died
,10-10 20:34:07.062  5566  5623 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-10 20:34:07.062  5566  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:07.062  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:07.062  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:07.062  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:07.062  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-10 20:34:07.062  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:07.062  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:07.062  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:07.062  5566  5623 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-10 20:34:07.062  5566  5623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:07.065  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:07.082   924   941 I ActivityManager: Start proc 5794:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-10 20:34:07.142  5794  5794 D AdapterServiceConfig: Adding HeadsetService
,10-10 20:34:07.143  5794  5794 D AdapterServiceConfig: Adding A2dpService
10-10 20:34:07.143  5794  5794 D AdapterServiceConfig: Adding HidService
10-10 20:34:07.143  5794  5794 D AdapterServiceConfig: Adding HealthService
10-10 20:34:07.143  5794  5794 D AdapterServiceConfig: Adding PanService
10-10 20:34:07.143  5794  5794 D AdapterServiceConfig: Adding GattService
10-10 20:34:07.143  5794  5794 D AdapterServiceConfig: Adding BluetoothMapService
10-10 20:34:07.144  5794  5794 D AdapterServiceConfig: Adding SapService
,10-10 20:34:07.155   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fedcdb8:true
,10-10 20:34:07.155  5794  5794 D BluetoothAdapterState: make() - Creating AdapterState
,10-10 20:34:07.158  5794  5794 I bt_bluedroid: init
,10-10 20:34:07.158  5794  5806 I BluetoothAdapterState: Entering OffState
,10-10 20:34:07.160  5794  5807 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-10 20:34:07.160  5794  5807 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-10 20:34:07.160  5794  5807 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-10 20:34:07.160  5794  5807 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-10 20:34:07.161  5794  5794 I bt_bluedroid: get_profile_interface socket
,10-10 20:34:07.162  5794  5810 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-10 20:34:07.163  5794  5794 I bt_bluedroid: get_profile_interface sdp
10-10 20:34:07.164  5794  5810 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-10 20:34:07.167  5794  5805 I bt_bluedroid: config_hci_snoop_log
10-10 20:34:07.168   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-10 20:34:07.172  5794  5806 D BluetoothAdapterState: Current state: OFF, message: 0
10-10 20:34:07.172  5794  5806 D BluetoothAdapterProperties: Setting state to 14
,10-10 20:34:07.172  5794  5806 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-10 20:34:07.175  5794  5806 D BluetoothBondStateMachine: make
,10-10 20:34:07.176  5794  5811 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-10 20:34:07.178  5794  5806 I BluetoothAdapterState: Entering PendingCommandState
,10-10 20:34:07.179  5794  5794 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-10 20:34:07.181  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:07.181  5794  5794 D BtGatt.DebugUtils: handleDebugAction() action=null
10-10 20:34:07.182  5794  5794 D BtGatt.GattService: Received start request. Starting profile...
10-10 20:34:07.182  5794  5794 D BtGatt.GattService: start()
10-10 20:34:07.182  5794  5794 I bt_bluedroid: get_profile_interface gatt
,10-10 20:34:07.183  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
,10-10 20:34:07.183  5794  5794 D BtGatt.AdvertiseManager: advertise manager created
,10-10 20:34:07.189  5794  5794 V BluetoothAdapterState: isTurningOff()=false
,10-10 20:34:07.189  5794  5794 V BluetoothAdapterState: isTurningOn()=false
10-10 20:34:07.189  5794  5794 V BluetoothAdapterState: isBleTurningOn()=true
10-10 20:34:07.189  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
,10-10 20:34:07.190  5794  5806 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-10 20:34:07.191  5794  5806 I bt_bluedroid: bt_bluedroid
10-10 20:34:07.191  5794  5807 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-10 20:34:07.191  5794  5807 I bt_hci  : start_up
,10-10 20:34:07.196  5794  5807 I bt_vendor: alloc value 0xf417f871
,10-10 20:34:07.196  5794  5807 I bt_vendor: init
10-10 20:34:07.196  5794  5807 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-10 20:34:07.196  5794  5807 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-10 20:34:07.303  5794  5807 D bt_hci  : start_up starting async portion
10-10 20:34:07.304  5794  5814 I bt_hci  : event_finish_startup
,10-10 20:34:07.304  5794  5814 I bt_hci_h4: hal_open
10-10 20:34:07.304  5794  5814 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-10 20:34:07.300  5815  5815 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-10 20:34:07.304  5794  5814 I bt_userial_vendor: device fd = 54 open
,10-10 20:34:07.316  5794  5814 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-10 20:34:07.318  5794  5814 D bt_hwcfg: Chipset BCM4358A3
,10-10 20:34:07.318  5794  5814 D bt_hwcfg: Target name = [BCM4358A3]
10-10 20:34:07.318  5794  5814 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-10 20:34:07.574  5794  5806 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-10 20:34:07.710  5794  5814 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-10 20:34:07.711  5794  5814 D bt_hwcfg: Settlement delay -- 100 ms
10-10 20:34:07.711  5794  5814 I bt_hwcfg: Setting fw settlement delay to 100 
,10-10 20:34:07.835  5794  5814 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-10 20:34:07.835  5794  5814 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-10 20:34:07.837  5794  5814 I bt_hwcfg: vendor lib fwcfg completed
10-10 20:34:07.838  5794  5814 I bt_vendor: firmware callback
10-10 20:34:07.838  5794  5814 I bt_hci  : firmware_config_callback
,10-10 20:34:07.849  5794  5817 I bt_btu  : btu_task pending for preload complete event
,10-10 20:34:07.849  5794  5817 I bt_btu_task: Bluetooth chip preload is complete
,10-10 20:34:07.849  5794  5817 I bt_btu  : btu_task received preload complete event
,10-10 20:34:07.855  5794  5817 I         : BTE_InitTraceLevels -- TRC_HCI
,10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_AVRC
10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_A2D
10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_BNEP
10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_BTM
,10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_GAP
10-10 20:34:07.856  5794  5817 I         : BTE_InitTraceLevels -- TRC_PAN
10-10 20:34:07.857  5794  5817 I         : BTE_InitTraceLevels -- TRC_SDP
,10-10 20:34:07.857  5794  5817 I         : BTE_InitTraceLevels -- TRC_GATT
10-10 20:34:07.857  5794  5817 I         : BTE_InitTraceLevels -- TRC_SMP
,10-10 20:34:07.857  5794  5817 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-10 20:34:07.857  5794  5817 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-10 20:34:07.942  5794  5817 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40fd549
,10-10 20:34:07.942  5794  5817 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40fd549 
,10-10 20:34:07.966  5794  5810 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-10 20:34:07.967  5794  5810 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-10 20:34:07.968  5794  5810 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-10 20:34:07.970  5794  5810 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-10 20:34:07.974  5794  5810 D BluetoothAdapterProperties: Scan Mode:20
10-10 20:34:07.974  5794  5810 D BluetoothAdapterProperties: Discoverable Timeout:120
10-10 20:34:07.974  5794  5810 D bt_hci  : do_postload posting postload work item
10-10 20:34:07.974  5794  5814 I bt_hci  : event_postload
10-10 20:34:07.974  5794  5814 I bt_vendor: sco_config_cb
10-10 20:34:07.974  5794  5814 I bt_hci  : sco_config_callback postload finished.
,10-10 20:34:07.980  5794  5814 I bt_vendor: low_power_mode_cb
,10-10 20:34:07.982  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:07.984  5794  5810 D bt_bte_conf: Device ID record 1 : primary
10-10 20:34:07.985  5794  5810 D bt_bte_conf:   vendorId            = 000f
10-10 20:34:07.985  5794  5810 D bt_bte_conf:   vendorIdSource      = 0001
10-10 20:34:07.985  5794  5810 D bt_bte_conf:   product             = 1200
10-10 20:34:07.985  5794  5810 D bt_bte_conf:   version             = 1436
10-10 20:34:07.985  5794  5810 D bt_bte_conf:   clientExecutableURL = 
10-10 20:34:07.985  5794  5810 D bt_bte_conf:   serviceDescription  = 
10-10 20:34:07.985  5794  5810 D bt_bte_conf:   documentationURL    = 
10-10 20:34:07.985  5794  5810 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-10 20:34:07.985  5794  5807 D bt_stack_manager: event_start_up_stack finished
,10-10 20:34:07.986  5794  5806 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-10 20:34:07.986  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:07.986  5794  5806 D BluetoothAdapterProperties: Setting state to 15
,10-10 20:34:07.987  5794  5806 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-10 20:34:07.988  5794  5806 I BluetoothAdapterState: Entering BleOnState
,10-10 20:34:07.990  5794  5806 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-10 20:34:07.990  5794  5806 D BluetoothAdapterProperties: Setting state to 11
10-10 20:34:07.990  5794  5806 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-10 20:34:07.998  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:08.002  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:08.004  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:08.005   924   924 D BluetoothHeadset: Proxy object connected
10-10 20:34:08.006   924   924 D BluetoothHeadset: Proxy object connected
10-10 20:34:08.006   924   924 D BluetoothHeadset: Proxy object connected
10-10 20:34:08.006  5794  5794 D HeadsetService: Received start request. Starting profile...
10-10 20:34:08.006  3077  3922 D BluetoothHeadset: Proxy object connected
10-10 20:34:08.006  3077  3077 D HeadsetProfile: Bluetooth service connected
,10-10 20:34:08.007  5669  5679 D BluetoothHeadset: Proxy object connected
,10-10 20:34:08.010  3721  3749 D BluetoothHeadset: Proxy object connected
10-10 20:34:08.010  5794  5794 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-10 20:34:08.010  5794  5794 D HeadsetStateMachine: make
,10-10 20:34:08.017  5794  5806 I BluetoothAdapterState: Entering PendingCommandState
,10-10 20:34:08.017  5669  5669 D HeadsetProfile: Bluetooth service connected
,10-10 20:34:08.018  5794  5794 D HeadsetStateMachine: max_hf_connections = 1
10-10 20:34:08.018  5794  5794 I bt_bluedroid: get_profile_interface handsfree
,10-10 20:34:08.018  5794  5810 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-10 20:34:08.018  5794  5810 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-10 20:34:08.022  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
,10-10 20:34:08.023  5794  5794 D A2dpService: Received start request. Starting profile...
,10-10 20:34:08.023  5794  5794 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-10 20:34:08.023  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-10 20:34:08.024  5794  5794 I bt_bluedroid: get_profile_interface avrcp
,10-10 20:34:08.028  5794  5794 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-10 20:34:08.029  5794  5794 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-10 20:34:08.029  5794  5794 D A2dpStateMachine: make
,10-10 20:34:08.030  5794  5794 I bt_bluedroid: get_profile_interface a2dp
,10-10 20:34:08.030  5794  5810 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-10 20:34:08.033  5794  5825 D A2dpStateMachine: Enter Disconnected: -2
,10-10 20:34:08.034  5794  5794 I BluetoothHidServiceJni: classInitNative: succeeds
,10-10 20:34:08.035  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
,10-10 20:34:08.035  5794  5794 D HidService: Received start request. Starting profile...
10-10 20:34:08.035  5794  5794 I bt_bluedroid: get_profile_interface hidhost
10-10 20:34:08.036  5794  5794 D HidService: setHidService(): set to: null
10-10 20:34:08.036  5794  5810 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40de56d
10-10 20:34:08.036  5794  5794 I BluetoothHealthServiceJni: classInitNative: succeeds
10-10 20:34:08.036  5794  5810 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-10 20:34:08.037  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:08.037  5794  5794 D HealthService: Received start request. Starting profile...
,10-10 20:34:08.039  5794  5794 I bt_bluedroid: get_profile_interface health
,10-10 20:34:08.040  5794  5794 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-10 20:34:08.040  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:08.041  5794  5794 D PanService: Received start request. Starting profile...
10-10 20:34:08.041  5794  5794 D BluetoothPanServiceJni: initializeNative(L110): pan
10-10 20:34:08.041  5794  5794 I bt_bluedroid: get_profile_interface pan
10-10 20:34:08.041  5794  5810 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-10 20:34:08.045  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:08.045  5794  5794 D BluetoothMapService: Received start request. Starting profile...
,10-10 20:34:08.045  5794  5794 D BluetoothMapService: start()
,10-10 20:34:08.048  5794  5794 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-10 20:34:08.048  5794  5794 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-10 20:34:08.049  5794  5794 D BluetoothMapAppObserver: createReceiver()
10-10 20:34:08.050  5794  5794 D BluetoothMapAppObserver: initObservers()
10-10 20:34:08.050  5794  5794 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-10 20:34:08.055  5794  5794 V SapService: SapBinder()
,10-10 20:34:08.055  5794  5794 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
10-10 20:34:08.056  5794  5794 D SapService: Received start request. Starting profile...
10-10 20:34:08.056  5794  5794 V SapService: start()
10-10 20:34:08.057  5794  5794 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:08.057  5794  5794 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:08.058  5794  5823 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isTurningOff()=false
,10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:08.058  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:08.059  5794  5794 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:08.059  5794  5794 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:08.059  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:08.059  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:08.059  5794  5794 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:08.059  5794  5794 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:08.059  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:08.059  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
,10-10 20:34:08.060  5794  5794 V BluetoothAdapterState: isTurningOff()=false
10-10 20:34:08.060  5794  5794 V BluetoothAdapterState: isTurningOn()=true
10-10 20:34:08.060  5794  5794 V BluetoothAdapterState: isBleTurningOn()=false
10-10 20:34:08.060  5794  5794 V BluetoothAdapterState: isBleTurningOff()=false
10-10 20:34:08.060  5794  5806 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-10 20:34:08.060  5794  5806 D BluetoothAdapterProperties: ScanMode =  20
10-10 20:34:08.060  5794  5806 D BluetoothAdapterProperties: State =  11
10-10 20:34:08.060  5794  5806 D BluetoothAdapterProperties: Setting state to 12
10-10 20:34:08.060  5794  5806 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-10 20:34:08.061  3077  3091 D BluetoothHeadset: onBluetoothStateChange: up=true
10-10 20:34:08.062  3077  3090 D BluetoothMap: onBluetoothStateChange: up=true
10-10 20:34:08.063  5794  5810 D BluetoothAdapterProperties: Scan Mode:21
10-10 20:34:08.063  5794  5810 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-10 20:34:08.063  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-10 20:34:08.063  5794  5806 I BluetoothAdapterState: Entering OnState
10-10 20:34:08.064  3077  3077 D BluetoothMap: Proxy object connected
10-10 20:34:08.064  3077  3077 D MapProfile: Bluetooth service connected
10-10 20:34:08.064  3077  3077 D BluetoothMap: getConnectedDevices()
10-10 20:34:08.065  5669  5680 D BluetoothPbap: onBluetoothStateChange: up=true
,10-10 20:34:08.068  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:08.068  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:08.068  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:08.068  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:08.068  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:08.068  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:08.068  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:08.068  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-10 20:34:08.068  3077  3091 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-10 20:34:08.070  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:08.070  3721  3747 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-10 20:34:08.070  3077  3091 D BluetoothPbap: onBluetoothStateChange: up=true
,10-10 20:34:08.071  3077  3077 D BluetoothInputDevice: Proxy object connected
10-10 20:34:08.071  3077  3077 D HidProfile: Bluetooth service connected
,10-10 20:34:08.073   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-10 20:34:08.074  5669  5679 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-10 20:34:08.074  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:08.074  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:08.074  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:08.074  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:08.074  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:08.074  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:08.074  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:08.074  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-10 20:34:08.075  5794  5794 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-10 20:34:08.076  5794  5794 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-10 20:34:08.076  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:08.077  5794  5794 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-10 20:34:08.077   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
10-10 20:34:08.077   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
10-10 20:34:08.077   924   941 D BluetoothA2dp: onBluetoothStateChange: up=true
10-10 20:34:08.078  5669  5680 D BluetoothMap: onBluetoothStateChange: up=true
,10-10 20:34:08.078  5794  5794 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-10 20:34:08.080  5669  5679 D BluetoothPan: onBluetoothStateChange on: true
,10-10 20:34:08.080  5794  5794 D ObexServerSockets: Succeed to create listening sockets 
10-10 20:34:08.080  5794  5794 D ObexServerSockets0: startAccept()
10-10 20:34:08.080  5794  5794 D ObexServerSockets0: prepareForNewConnect()
10-10 20:34:08.080  5566  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:08.080  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:08.080  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:08.080  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:08.080  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:08.080  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:08.080  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:08.080  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-10 20:34:08.081  5669  5680 D BluetoothHeadset: onBluetoothStateChange: up=true
10-10 20:34:08.082  3077  3090 D BluetoothPan: onBluetoothStateChange on: true
10-10 20:34:08.082  5794  5794 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-10 20:34:08.082  5794  5794 D BluetoothSdpJni: SDP Create record success - handle: 0
10-10 20:34:08.082  5566  5623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:08.083  5566  5612 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
10-10 20:34:08.084  5669  5679 D BluetoothA2dp: onBluetoothStateChange: up=true
10-10 20:34:08.084   924   935 D WifiService: setWifiEnabled: false pid=5566, uid=10077
10-10 20:34:08.084   924   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-10 20:34:08.085   924   924 D BluetoothA2dp: Proxy object connected
10-10 20:34:08.086  5669  5669 D BluetoothInputDevice: Proxy object connected
10-10 20:34:08.086  5669  5669 D HidProfile: Bluetooth service connected
10-10 20:34:08.086  3077  3077 D BluetoothPan: BluetoothPAN Proxy object connected
10-10 20:34:08.086  3077  3077 D PanProfile: Bluetooth service connected
10-10 20:34:08.086  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:08.086  5794  5832 D ObexServerSockets0: Accepting socket connection...
10-10 20:34:08.087   924  2922 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-10 20:34:08.087  3077  3091 D BluetoothA2dp: onBluetoothStateChange: up=true
10-10 20:34:08.087   924  2922 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-10 20:34:08.088   924  2922 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-10 20:34:08.088  5794  5831 D ObexServerSockets0: Accepting socket connection...
10-10 20:34:08.088   924  2922 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-10 20:34:08.089  3077  3077 D BluetoothA2dp: Proxy object connected
10-10 20:34:08.091   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
10-10 20:34:08.091   924   924 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
10-10 20:34:08.092  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-10 20:34:08.096  5794  5794 D BluetoothMapService: onReceive
10-10 20:34:08.096  5794  5794 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-10 20:34:08.096  5794  5794 D BluetoothMapService: STATE_ON
,10-10 20:34:08.096  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:08.098  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:08.099   924  5729 D DhcpClient: Clearing IP address
,10-10 20:34:08.099   506   915 D CommandListener: Clearing all IP addresses on wlan0
,10-10 20:34:08.101  5669  5669 D BluetoothMap: Proxy object connected
,10-10 20:34:08.101  5669  5669 D MapProfile: Bluetooth service connected
10-10 20:34:08.101  5669  5669 D BluetoothMap: getConnectedDevices()
10-10 20:34:08.101  5794  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-10 20:34:08.103  5669  5669 D BluetoothPan: BluetoothPAN Proxy object connected
10-10 20:34:08.103  5669  5669 D PanProfile: Bluetooth service connected
10-10 20:34:08.103  5669  5669 D BluetoothA2dp: Proxy object connected
10-10 20:34:08.104  5794  5837 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-10 20:34:08.104  5794  5837 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-10 20:34:08.106   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:08.109  5669  5669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-10 20:34:08.109   924  5730 D DhcpClient: Receive thread stopped
10-10 20:34:08.111  3524  5762 V NativeCrypto: Read error: ssl=0x7f6fbdd400: I/O error during system call, Connection timed out
10-10 20:34:08.113  3524  5762 V NativeCrypto: SSL shutdown failed: ssl=0x7f6fbdd400: I/O error during system call, Broken pipe
10-10 20:34:08.115   924  3739 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
10-10 20:34:08.116   924  5726 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-10 20:34:08.116  5669  5669 D DockEventReceiver: finishStartingService: stopping service
10-10 20:34:08.116  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-10 20:34:08.117   924  5726 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-10 20:34:08.118   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
10-10 20:34:08.118   924  2924 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-10 20:34:08.119   924  2924 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-10 20:34:08.124   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-10 20:34:08.124  5669  5669 D BluetoothPbap: Proxy object connected
10-10 20:34:08.124   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-10 20:34:08.124  5669  5669 D PbapServerProfile: Bluetooth service connected
,10-10 20:34:08.125  5794  5794 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-10 20:34:08.125  5794  5794 D ObexServerSockets0: prepareForNewConnect()
10-10 20:34:08.126   532   532 E Parcel  : Reading a NULL string not supported here.
,10-10 20:34:08.130   924   924 D RttService: SCAN_AVAILABLE : 1
10-10 20:34:08.131   924  3031 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-10 20:34:08.131   924  2924 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-10 20:34:08.132  3670  3842 W QCNEJ   : |CORE| network lost: 101
10-10 20:34:08.133  3670  3842 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-10 20:34:08.135  3077  3077 D BluetoothPbap: Proxy object connected
10-10 20:34:08.135  3077  3077 D PbapServerProfile: Bluetooth service connected
10-10 20:34:08.135  5794  5844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-10 20:34:08.149   924  2922 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-10 20:34:08.153  5794  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-10 20:34:08.155  5794  5849 I BtOppRfcommListener: Accept thread started.
,10-10 20:34:08.156   924  2922 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-10 20:34:08.160   506   915 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-10 20:34:08.179   506   915 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-10 20:34:08.179   506   915 D CommandListener: Clearing all IP addresses on wlan0
,10-10 20:34:08.180   924  2924 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-10 20:34:08.180   924  2924 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-10 20:34:08.182   924   941 D Tethering: MasterInitialState.processMessage what=3
,10-10 20:34:08.185   924  2922 D DhcpClient: doQuit
,10-10 20:34:08.185   924  2922 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-10 20:34:08.185   924  5729 D DhcpClient: onQuitting
10-10 20:34:08.186  5664  5664 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-10 20:34:08.187  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:08.187  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:08.187  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:08.187  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:08.187  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:08.187  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:08.187  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:08.187  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:08.188  4790  4814 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-10 20:34:08.188  4790  4814 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-10 20:34:08.188  4790  4814 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-10 20:34:08.189  4790  4814 E SarControlService: no key has been found,reset the power
10-10 20:34:08.189  4790  4827 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-10 20:34:08.189  4790  4827 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-10 20:34:08.189  4790  4827 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-10 20:34:08.190  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-10 20:34:08.190  4815  4815 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-10 20:34:08.190  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-10 20:34:08.192  4790  4827 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-10 20:34:08.193  4790  4827 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-10 20:34:08.193  4790  4827 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-10 20:34:08.194  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-10 20:34:08.195  4815  4815 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-10 20:34:08.196  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:08.196  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:08.196  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:08.196  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-10 20:34:08.196  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:08.196  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:08.196  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:08.196  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:08.197  3990  3990 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-10 20:34:08.199  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-10 20:34:08.199  4815  4829 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@70117bb HexData = [00000000ee03000000000000ffffffff]
10-10 20:34:08.199  4815  4829 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-10 20:34:08.199  4815  4829 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-10 20:34:08.200  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-10 20:34:08.200  4790  4801 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-10 20:34:08.201  3990  3990 D SystemUpdateService: onCreate
10-10 20:34:08.204  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:08.204  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:08.204  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:08.204  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-10 20:34:08.204  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:08.204  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:08.204  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:08.204  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:08.208  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:08.210  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-10 20:34:08.210  4815  4829 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@70117bb HexData = [00000000ef03000000000000ffffffff]
10-10 20:34:08.210  4815  4829 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-10 20:34:08.210  5664  5664 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-10 20:34:08.210  4815  4829 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-10 20:34:08.211  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-10 20:34:08.211  4790  4800 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-10 20:34:08.212  3990  3990 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-10 20:34:08.215  5664  5664 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-10 20:34:08.216  3990  5855 I SystemUpdateService: active receiver: enabled
,10-10 20:34:08.219  3990  3990 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-10 20:34:08.225  3990  5260 I iu.UploadsManager: num queued entries: 0
,10-10 20:34:08.227  3990  3990 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-10 20:34:08.229  3990  3990 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-10 20:34:08.231  5264  5264 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-10 20:34:08.234   506   915 E Netd    : netlink response contains error (No such file or directory)
10-10 20:34:08.235  5264  5264 D SprintDMHelper: simOperator: 
10-10 20:34:08.235  5264  5264 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-10 20:34:08.235   924  2924 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-10 20:34:08.235   924  2924 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-10 20:34:08.236  3990  5855 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-10 20:34:08.242  3990  5260 I iu.UploadsManager: num updated entries: 0
,10-10 20:34:08.245  5664  5664 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-10 20:34:08.246  3990  5260 I iu.SyncManager: NEXT; no task
,10-10 20:34:08.249  4738  5858 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-10 20:34:08.249  3990  5855 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-10 20:34:08.249  3990  5855 I SystemUpdateService: now status is 0 (complete)
,10-10 20:34:08.249  3990  5855 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-10 20:34:08.251  3990  5855 I SystemUpdateService: file has been verified
10-10 20:34:08.252  3990  5855 I SystemUpdateService: OTA package size = 21989297
,10-10 20:34:08.263  5664  5664 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-10 20:34:08.267  3990  5855 I SystemUpdateService: showing system update notification
,10-10 20:34:08.275  3990  3990 D SystemUpdateService: onDestroy
,10-10 20:34:08.365  4738  4738 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-10 20:34:08.365   924  2922 D wifi    : In wifi stop Hal
,10-10 20:34:08.365   924  2922 D wifi    : halHandle = 0x7f6ff035a0, mVM = 0x7f8a50d140, mCls = 0x201886
10-10 20:34:08.365   924  5663 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-10 20:34:08.365   924  5663 D WifiHAL : Got a signal to exit!!!
10-10 20:34:08.365   924  5663 I WifiHAL : Exit wifi_event_loop
10-10 20:34:08.366   924  2922 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-10 20:34:08.366   924  2922 E WifiHAL : Event processing terminated
10-10 20:34:08.367   924  2922 D wifi    : In wifi cleaned up handler
10-10 20:34:08.367   924  2922 I WifiHAL : Internal cleanup completed
10-10 20:34:08.370  3848  4165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-10 20:34:08.372  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:08.376  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:08.393   924  5663 D wifi    : set interface wlan0 flags (DOWN)
,10-10 20:34:08.393   924  2922 D WifiNative-HAL: HAL event thread stopped successfully
,10-10 20:34:08.597  5566  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:08.597  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:08.597  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:08.597  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-10 20:34:08.597  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:08.597  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:08.597  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:08.597  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:08.601   924   941 D Tethering: InitialState.processMessage what=4
,10-10 20:34:08.604  5566  5623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-10 20:34:08.607   924   941 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
10-10 20:34:08.607   924  3786 D WifiService: setWifiEnabled: true pid=5566, uid=10077
10-10 20:34:08.607   924  3786 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:08.608  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:08.611   506   915 D SoftapController: Softap fwReload - Ok
,10-10 20:34:08.615   506   915 D CommandListener: Setting iface cfg
10-10 20:34:08.616   506   915 D CommandListener: Trying to bring down wlan0
,10-10 20:34:08.617   506   915 D CommandListener: Clearing all IP addresses on wlan0
,10-10 20:34:08.621   924  2922 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-10 20:34:09.111   924  3054 D WifiService: setWifiEnabled: true pid=5566, uid=10077
10-10 20:34:09.113   924  3054 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:09.230   924  2922 D wifi    : set interface wlan0 flags (UP)
,10-10 20:34:09.231   924  2922 I WifiHAL : Initializing wifi
,10-10 20:34:09.231   924  2922 I WifiHAL : Creating socket
,10-10 20:34:09.234   924   941 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-10 20:34:09.240   924  2922 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-10 20:34:09.240   924  2922 D wifi    : Did set static halHandle = 0x7f6ff035a0
10-10 20:34:09.240   924  2922 D wifi    : halHandle = 0x7f6ff035a0, mVM = 0x7f8a50d140, mCls = 0x14b2
10-10 20:34:09.240   924  2922 D wifi    : array field set
10-10 20:34:09.241   924  2922 I WifiNative-HAL: interface[0] = wlan0
,10-10 20:34:09.242   924  5862 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547338859936
10-10 20:34:09.242   924  5862 D wifi    : waitForHalEvents called, vm = 0x7f8a50d140, obj = 0x14b2, env = 0x7f843926c0
,10-10 20:34:09.245   924  2922 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
10-10 20:34:09.247   924  2922 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,10-10 20:34:09.249  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:09.251  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:09.292  5863  5863 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-10 20:34:09.313  5863  5863 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-10 20:34:09.321  5863  5863 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-10 20:34:09.321  5863  5863 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-10 20:34:09.618   924  3687 D WifiService: setWifiEnabled: true pid=5566, uid=10077
,10-10 20:34:09.618   924  3687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:10.121   924  3554 D WifiService: setWifiEnabled: true pid=5566, uid=10077
,10-10 20:34:10.121   924  3554 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:10.258   924  2922 D WifiConfigStore: Loading config and enabling all networks 
,10-10 20:34:10.268  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:10.268  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:10.268  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:10.268  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:10.268  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:10.268  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:10.268  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:10.268  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:10.271  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:10.278   924  2922 D WifiConfigStore: loaded 0 passpoint configs
10-10 20:34:10.278  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:10.278  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:10.278  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:10.278  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:10.278  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:10.278  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:10.278  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:10.278  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-10 20:34:10.278   924  2922 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-10 20:34:10.279   924  2922 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-10 20:34:10.280   924  2922 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-10 20:34:10.281  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-10 20:34:10.282   924  2922 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-10 20:34:10.282   924  2922 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-10 20:34:10.282   924  2922 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-10 20:34:10.282   924  2922 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-10 20:34:10.287  4738  4738 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-10 20:34:10.287   924  2922 D WifiNative-HAL: Setting external_sim to 1
10-10 20:34:10.287   924  2922 D wifi    : setting dfs flag to true, 0x7f70bf0060
,10-10 20:34:10.288   924  2922 D WifiStateMachine: Setting OUI to DA-A1-19
,10-10 20:34:10.288   924  2922 D wifi    : setting scan oui 0x7f70bf0060
10-10 20:34:10.288   924  2922 D WifiHAL : Sending mac address OUI
,10-10 20:34:10.293   924  2922 E native  : do suspend false
,10-10 20:34:10.302   924  2922 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-10 20:34:10.302   506   915 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-10 20:34:10.303   924   924 D RttService: SCAN_AVAILABLE : 3
,10-10 20:34:10.303   924  3031 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-10 20:34:10.303   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:10.307   924  2918 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-10 20:34:10.307   924  2918 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-10 20:34:10.317   924  2918 D WifiNative-HAL: p2pGetDeviceAddress
,10-10 20:34:10.322   924   939 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=250540 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-10 20:34:10.322   924  2918 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-10 20:34:10.632  5566  5623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:10.632  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:10.632  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:10.632  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:10.632  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:10.632  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:10.632  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:10.632  5566  5623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:10.638  5566  5623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:10.641  5566  5612 D BluetoothAdapter: enable(): BT is already enabled..!
,10-10 20:34:10.643   924  3687 D WifiService: setWifiEnabled: true pid=5566, uid=10077
,10-10 20:34:10.643   924  3687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-10 20:34:10.644  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-10 20:34:10.644  5566  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-10 20:34:10.644  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-10 20:34:10.645  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-10 20:34:10.645  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-10 20:34:10.645  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbb9cba removed from the list
,10-10 20:34:10.645  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-10 20:34:10.646  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7e976b removed from the list
10-10 20:34:10.646  5566  5612 D io.jxcore.node.ConnectivityMonitor: stop
10-10 20:34:10.646  5566  5612 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-10 20:34:10.646  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-10 20:34:10.649  5566  5612 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
10-10 20:34:10.652  5566  5612 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
10-10 20:34:10.654  5566  5612 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,10-10 20:34:10.657  5566  5612 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,10-10 20:34:10.660  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,10-10 20:34:10.661  5566  5612 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-10 20:34:10.663  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,10-10 20:34:10.663  5566  5612 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-10 20:34:10.665  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,10-10 20:34:10.669  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,10-10 20:34:10.670  5566  5612 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7965f8f Bundle[{}]
10-10 20:34:10.670  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
10-10 20:34:10.670  5566  5612 I io.jxcore.node.LifeCycleMonitor: start: OK
10-10 20:34:10.671  5566  5612 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-10 20:34:10.671  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,10-10 20:34:10.671  5566  5612 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-10 20:34:10.672  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
10-10 20:34:10.672  5566  5612 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-10 20:34:10.673  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
10-10 20:34:10.673  5566  5612 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-10 20:34:10.674  5566  5612 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,10-10 20:34:10.674  5566  5612 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-10 20:34:10.677  5566  5612 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,10-10 20:34:10.678  5566  5612 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,10-10 20:34:10.680  5566  5612 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
10-10 20:34:10.681  5566  5612 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,10-10 20:34:10.682  5566  5612 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,10-10 20:34:10.683  5566  5612 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,10-10 20:34:10.685  5566  5612 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,10-10 20:34:10.686  5566  5612 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,10-10 20:34:10.687  5566  5612 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
10-10 20:34:10.689  5566  5612 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,10-10 20:34:10.690  5566  5612 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,10-10 20:34:10.691  5566  5612 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
10-10 20:34:10.691  5566  5612 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 137)
10-10 20:34:10.692  5566  5612 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
10-10 20:34:10.692  5566  5612 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-10 20:34:10.693  5566  5612 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 138)
,10-10 20:34:10.693  5566  5612 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,10-10 20:34:10.695  5566  5612 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,10-10 20:34:10.696  5566  5612 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
10-10 20:34:10.696  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-10 20:34:10.696  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f6ca86 added. We now have 3 listener(s)
10-10 20:34:10.698  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-10 20:34:10.698  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-10 20:34:10.698  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-10 20:34:10.698  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-10 20:34:10.698  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6d3f47 added. We now have 3 listener(s)
10-10 20:34:10.698  5566  5612 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-10 20:34:10.699  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-10 20:34:10.703  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-10 20:34:10.707  5566  5612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-10 20:34:10.707  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:10.707  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:10.707  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:10.707  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:10.707  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-10 20:34:10.707  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-10 20:34:10.707  5566  5612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-10 20:34:10.708  5566  5612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-10 20:34:10.708  5566  5612 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-10 20:34:10.711  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:10.712  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-10 20:34:10.713  5566  5612 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,10-10 20:34:10.714  5566  5612 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
10-10 20:34:10.717  5836  5836 W Binder_6: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33204]" dev="sockfs" ino=33204 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-10 20:34:10.714  5566  5612 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
10-10 20:34:10.714  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
10-10 20:34:10.715  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-10 20:34:10.715  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-10 20:34:10.715  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-10 20:34:10.715  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:34:10.716  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-10 20:34:10.716  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-10 20:34:10.716  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-10 20:34:10.716  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-10 20:34:10.716  5566  5865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-10 20:34:10.717  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-10 20:34:10.717  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-10 20:34:10.717  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-10 20:34:10.717  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:34:10.717  5566  5865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-10 20:34:10.717  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-10 20:34:10.720  5566  5865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-10 20:34:10.724  5566  5612 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-10 20:34:10.724  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-10 20:34:10.717  5836  5836 W Binder_6: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33204]" dev="sockfs" ino=33204 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-10 20:34:10.728  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-10 20:34:10.728  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-10 20:34:10.728  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-10 20:34:10.730  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-10 20:34:10.731  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-10 20:34:10.731  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
10-10 20:34:10.731  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:34:10.731  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-10 20:34:10.731  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-10 20:34:10.731  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:34:10.732  5566  5612 D BluetoothAdapter: STATE_ON
,10-10 20:34:10.735  5794  5836 D BtGatt.GattService: registerClient() - UUID=701f4d6a-bfa1-4cde-bda4-5040a358ba8f
10-10 20:34:10.736  5794  5810 D BtGatt.GattService: onClientRegistered() - UUID=701f4d6a-bfa1-4cde-bda4-5040a358ba8f, clientIf=5
,10-10 20:34:10.737  5566  5576 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-10 20:34:10.739  5794  5812 D BtGatt.AdvertiseManager: message : 0
,10-10 20:34:10.741  5794  5812 D BtGatt.AdvertiseManager: starting multi advertising
,10-10 20:34:10.751  5794  5810 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-10 20:34:10.757  5794  5810 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-10 20:34:10.757  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
,10-10 20:34:10.757  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-10 20:34:10.757  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-10 20:34:10.757  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-10 20:34:10.757  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-10 20:34:10.758  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-10 20:34:10.760  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-10 20:34:10.760  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-10 20:34:10.760  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-10 20:34:10.760  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-10 20:34:10.760  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-10 20:34:10.760  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:34:10.760  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-10 20:34:10.760  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-10 20:34:10.760  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-10 20:34:10.760  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-10 20:34:10.763  5566  5566 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-10 20:34:10.763  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-10 20:34:11.264  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-10 20:34:11.264  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,10-10 20:34:11.264  5566  5566 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-10 20:34:13.480  5863  5863 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-10 20:34:13.488  5863  5863 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-10 20:34:13.493  5863  5863 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-10 20:34:13.526   924  2922 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-10 20:34:13.527   924  2922 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-10 20:34:13.527   924  2922 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-10 20:34:13.538   924  2922 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-10 20:34:13.574   924  2922 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-10 20:34:13.576  5863  5863 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-10 20:34:13.819   924  2924 D ConnectivityService: handlePromptUnvalidated 101
,10-10 20:34:13.999  5863  5863 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-10 20:34:14.026   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:14.036  5863  5863 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-10 20:34:14.037  5863  5863 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-10 20:34:14.050   924  2922 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-10 20:34:14.051   924  2922 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-10 20:34:14.051   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-10 20:34:14.068   924  2922 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-10 20:34:14.081   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:14.086   924  2922 D WifiStateMachine: Start Dhcp Watchdog 3
,10-10 20:34:14.091   924  5872 D DhcpClient: Receive thread started
,10-10 20:34:14.095   924  2922 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-10 20:34:14.095   924  2924 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-10 20:34:14.095   924  2924 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-10 20:34:14.176   924  2922 E native  : do suspend false
,10-10 20:34:14.186   924  5871 D DhcpClient: Broadcasting DHCPDISCOVER
,10-10 20:34:14.200   924  5872 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
,10-10 20:34:14.201   924  5871 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,10-10 20:34:14.203   924  5871 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-10 20:34:14.216   924  5872 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-10 20:34:14.217   924  5871 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-10 20:34:14.220   506   915 D CommandListener: Setting iface cfg
,10-10 20:34:14.225   924  2922 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-10 20:34:14.228   924  5871 D DhcpClient: Scheduling renewal in 86399s
,10-10 20:34:14.242   924  2922 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-10 20:34:14.244   924  2922 D WifiConfigStore: No blacklist allowed without epno enabled
,10-10 20:34:14.246   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-10 20:34:14.248   924  2924 D ConnectivityService: Adding iface wlan0 to network 102
,10-10 20:34:14.256   924  2922 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-10 20:34:14.262  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-10 20:34:14.262  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-10 20:34:14.262  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-10 20:34:14.262  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-10 20:34:14.262  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-10 20:34:14.263  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-10 20:34:14.263  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-10 20:34:14.263  5566  5865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-10 20:34:14.263  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-10 20:34:14.263  5566  5865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-10 20:34:14.263  5566  5865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-10 20:34:14.263  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-10 20:34:14.263  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-10 20:34:14.263  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-10 20:34:14.263  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-10 20:34:14.263  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-10 20:34:14.263  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-10 20:34:14.265  5566  5612 D BluetoothAdapter: STATE_ON
,10-10 20:34:14.265  5566  5612 D BluetoothLeScanner: could not find callback wrapper
10-10 20:34:14.265  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-10 20:34:14.265  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-10 20:34:14.268  5794  5812 D BtGatt.AdvertiseManager: message : 1
,10-10 20:34:14.269  5794  5812 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-10 20:34:14.280  5794  5810 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-10 20:34:14.280  5794  5810 D BtGatt.GattService: Client app is not null!
10-10 20:34:14.282  5794  5836 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-10 20:34:14.283  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-10 20:34:14.283  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-10 20:34:14.283  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-10 20:34:14.283  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-10 20:34:14.283  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:34:14.283  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-10 20:34:14.284  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-10 20:34:14.284  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-10 20:34:14.284  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-10 20:34:14.285  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-10 20:34:14.286  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-10 20:34:14.286  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-10 20:34:14.286  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-10 20:34:14.288  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-10 20:34:14.288  5566  5566 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-10 20:34:14.288  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-10 20:34:14.288  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-10 20:34:14.288  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-10 20:34:14.288  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-10 20:34:14.289  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-10 20:34:14.290  5566  5612 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
10-10 20:34:14.291  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-10 20:34:14.291  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-10 20:34:14.292  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-10 20:34:14.292  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-10 20:34:14.292  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-10 20:34:14.292  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-10 20:34:14.296  5566  5612 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-10 20:34:14.296  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-10 20:34:14.301  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-10 20:34:14.302  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-10 20:34:14.302  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-10 20:34:14.307   924  2924 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-10 20:34:14.307   924  2924 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
10-10 20:34:14.308  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-10 20:34:14.308   924  2924 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
10-10 20:34:14.308  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-10 20:34:14.308  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-10 20:34:14.309  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-10 20:34:14.309  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-10 20:34:14.310   924  2924 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
10-10 20:34:14.310  5566  5612 D BluetoothAdapter: STATE_ON
10-10 20:34:14.312   924  2924 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-10 20:34:14.314  5794  5836 D BtGatt.GattService: registerClient() - UUID=01e46dac-54f0-4b36-95c7-3a455f09a9d6
10-10 20:34:14.314  5794  5810 D BtGatt.GattService: onClientRegistered() - UUID=01e46dac-54f0-4b36-95c7-3a455f09a9d6, clientIf=5
,10-10 20:34:14.315  5566  5577 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-10 20:34:14.319  5794  5805 D BtGatt.GattService: start scan with filters
10-10 20:34:14.320   924  2924 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-10 20:34:14.323  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-10 20:34:14.323  5794  5813 D BtGatt.ScanManager: handling starting scan
10-10 20:34:14.323  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-10 20:34:14.323  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:34:14.323  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-10 20:34:14.323  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-10 20:34:14.323  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-10 20:34:14.323  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-10 20:34:14.323   924  2924 D ConnectivityService: scheduleUnvalidatedPrompt 102
10-10 20:34:14.324   924  2924 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-10 20:34:14.324   924  2924 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-10 20:34:14.324   924  2924 D ConnectivityService:    accepting network in place of null
10-10 20:34:14.324   924  2922 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-10 20:34:14.324   924  2922 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-10 20:34:14.324   924  2924 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-10 20:34:14.325  5794  5813 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ad6f0
,10-10 20:34:14.327  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-10 20:34:14.327  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-10 20:34:14.327  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-10 20:34:14.328  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-10 20:34:14.332  5794  5810 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-10 20:34:14.332  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:14.332  5794  5813 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-10 20:34:14.335   924  5870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=254552, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-10 20:34:14.338  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-10 20:34:14.338  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:14.338  5794  5813 D BtGatt.ScanManager: Starting BLE batch scan
10-10 20:34:14.338  5794  5813 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-10 20:34:14.347  5794  5810 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-10 20:34:14.347  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:14.349   506   915 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-10 20:34:14.351  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-10 20:34:14.351  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-10 20:34:14.368   506   915 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-10 20:34:14.372   924  2924 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-10 20:34:14.372   924  2924 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-10 20:34:14.372  3670  3842 W QCNEJ   : |CORE| network available: 102
,10-10 20:34:14.373   924  2924 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-10 20:34:14.375   924   941 D Tethering: MasterInitialState.processMessage what=3
10-10 20:34:14.375  3670  3842 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-10 20:34:14.378  3670  3842 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-10 20:34:14.378  3670  3842 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-10 20:34:14.382  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:14.382  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:14.382  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:14.382  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:14.382  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:14.382  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:14.382  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:14.382  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:14.385  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-10 20:34:14.389  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:14.389  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:14.389  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:14.389  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:14.389  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:14.389  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:14.389  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:14.389  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:14.390  4790  4814 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-10 20:34:14.390  4790  4814 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-10 20:34:14.390  4790  4814 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-10 20:34:14.390  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:14.391  4790  4814 E SarControlService: no key has been found,reset the power
10-10 20:34:14.391  4790  4827 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-10 20:34:14.391  4790  4827 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-10 20:34:14.391  4790  4827 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-10 20:34:14.391  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-10 20:34:14.391  4815  4815 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-10 20:34:14.393  4790  4827 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-10 20:34:14.393  4790  4827 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-10 20:34:14.393  4790  4827 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-10 20:34:14.394  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-10 20:34:14.394  4815  4815 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-10 20:34:14.394  5566  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-10 20:34:14.394  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-10 20:34:14.394  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-10 20:34:14.394  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-10 20:34:14.394  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-10 20:34:14.394  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-10 20:34:14.394  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-10 20:34:14.394  5566  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-10 20:34:14.396  3990  3990 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-10 20:34:14.396  5566  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-10 20:34:14.400  4815  4829 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@70117bb HexData = [00000000f003000000000000ffffffff]
,10-10 20:34:14.400  4815  4829 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-10 20:34:14.400  4815  4829 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-10 20:34:14.400  4815  4829 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@70117bb HexData = [00000000f103000000000000ffffffff]
10-10 20:34:14.400  4815  4829 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-10 20:34:14.400  4815  4829 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-10 20:34:14.401  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-10 20:34:14.401  4790  4801 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-10 20:34:14.402  3990  3990 D SystemUpdateService: onCreate
10-10 20:34:14.403  4815  4815 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-10 20:34:14.403  4790  4800 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-10 20:34:14.406  3990  3990 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-10 20:34:14.414  3990  3990 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-10 20:34:14.422  3990  5883 I SystemUpdateService: active receiver: enabled
,10-10 20:34:14.425  3990  5260 I iu.UploadsManager: num queued entries: 0
,10-10 20:34:14.425  3990  5260 I iu.UploadsManager: num updated entries: 0
,10-10 20:34:14.430  3990  3990 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-10 20:34:14.431  3990  3990 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-10 20:34:14.433  5264  5264 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-10 20:34:14.436  5264  5264 D SprintDMHelper: simOperator: 
10-10 20:34:14.436  5264  5264 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-10 20:34:14.448  3990  5883 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-10 20:34:14.457  3990  5260 I iu.SyncManager: NEXT; no task
,10-10 20:34:14.464  3990  5883 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-10 20:34:14.464  3990  5883 I SystemUpdateService: now status is 0 (complete)
10-10 20:34:14.464  3990  5883 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-10 20:34:14.464  3990  5883 I SystemUpdateService: file has been verified
10-10 20:34:14.465  3990  5883 I SystemUpdateService: OTA package size = 21989297
,10-10 20:34:14.476  3990  5883 I SystemUpdateService: showing system update notification
,10-10 20:34:14.485  3990  3990 D SystemUpdateService: onDestroy
,10-10 20:34:14.707   924  5869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,10-10 20:34:14.827  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-10 20:34:14.828  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-10 20:34:14.828  5566  5566 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-10 20:34:14.855  5794  5794 D BtGatt.ScanManager: awakened up at time 255073
,10-10 20:34:14.858  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-10 20:34:14.887  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
10-10 20:34:14.887  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:14.887  5794  5810 D BtGatt.GattService: current time is 255104928008
10-10 20:34:14.887  5794  5810 D BtGatt.GattService: Batch record : [-29, 114, 4, 110, -32, 73, 1, -128, -53, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0, 105, -103, 8, -127, -113, 115, 1, -128, -47, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -78, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -77, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-10 20:34:14.889  5794  5810 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
10-10 20:34:14.891  5794  5810 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-10 20:34:14.891  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-10 20:34:14.891  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-10 20:34:14.891  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-10 20:34:14.891  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-10 20:34:14.894  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults
10-10 20:34:14.894  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-10 20:34:14.895  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=254755577071}
,10-10 20:34:14.895  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-10 20:34:14.896  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-77, mTimestampNanos=255055577071}
,10-10 20:34:14.896  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-10 20:34:14.896  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-78, mTimestampNanos=255055577071}
,10-10 20:34:14.896  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-10 20:34:14.897  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=73:8F:81:08:99:69, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-47, mTimestampNanos=255105577071}
10-10 20:34:14.897  5566  5566 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null]
,10-10 20:34:14.898  5566  5566 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
10-10 20:34:14.898  5566  5566 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
10-10 20:34:14.898  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-10 20:34:14.899  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=49:E0:6E:04:72:E3, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=254805577071}
,10-10 20:34:14.899  5566  5566 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null]
10-10 20:34:14.899  5566  5566 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 6]
10-10 20:34:14.899  5566  5566 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
10-10 20:34:14.899  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-10 20:34:14.900  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=255005577071}
10-10 20:34:14.900  5566  5566 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
10-10 20:34:14.901  5566  5566 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 6], Bluetooth address: 44:78:3E:94:4A:3E, device name: '', device address: ''
,10-10 20:34:14.925   924  5869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 11 Oct 2016 00:34:14 GMT], X-Android-Received-Millis=[1476146054922], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476146054736]}
,10-10 20:34:14.926   924  2924 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-10 20:34:14.927   924  2924 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-10 20:34:14.927   924  2924 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-10 20:34:14.930   924  2924 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-10 20:34:14.948  4738  5888 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-10 20:34:15.026   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:15.372   924  2924 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,10-10 20:34:15.390  5794  5794 D BtGatt.ScanManager: awakened up at time 255608
,10-10 20:34:15.392  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-10 20:34:15.420  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
10-10 20:34:15.420  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-10 20:34:15.421  5794  5810 D BtGatt.GattService: current time is 255638730248
10-10 20:34:15.421  5794  5810 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 105, -103, 8, -127, -113, 115, 1, -128, -50, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0]
10-10 20:34:15.422  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
10-10 20:34:15.422  5794  5810 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-10 20:34:15.424  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults
,10-10 20:34:15.424  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-10 20:34:15.424  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=255289217853}
,10-10 20:34:15.425  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-10 20:34:15.425  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=73:8F:81:08:99:69, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-50, mTimestampNanos=255589217853}
10-10 20:34:15.426  5566  5566 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null]
10-10 20:34:15.426  5566  5566 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
10-10 20:34:15.427  5566  5566 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> A8:81:95:E9:5F:6F 6], device name: '', device address: ''
,10-10 20:34:16.027   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:16.843   924  2922 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 17 -> obsolete
,10-10 20:34:17.028   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:17.333  5566  5612 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,10-10 20:34:17.333  5566  5612 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,10-10 20:34:17.333  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-10 20:34:17.334  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-10 20:34:17.334  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-10 20:34:17.337  5566  5612 D BluetoothAdapter: STATE_ON
10-10 20:34:17.339  5794  5835 D BtGatt.GattService: stopScan() - queue size =1
,10-10 20:34:17.341  5794  5822 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-10 20:34:17.341  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-10 20:34:17.342  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-10 20:34:17.342  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-10 20:34:17.342  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-10 20:34:17.342  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-10 20:34:17.342  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-10 20:34:17.343  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-10 20:34:17.343  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-10 20:34:17.344  5566  5612 D BluetoothAdapter: STATE_ON
10-10 20:34:17.351  5794  5836 D BtGatt.GattService: registerClient() - UUID=2c4dda1d-23ec-4041-b4b1-b23eca03eb3a
10-10 20:34:17.353  5794  5794 D BtGatt.ScanManager: awakened up at time 257570
10-10 20:34:17.353  5794  5810 D BtGatt.GattService: onClientRegistered() - UUID=2c4dda1d-23ec-4041-b4b1-b23eca03eb3a, clientIf=5
,10-10 20:34:17.355  5566  5577 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-10 20:34:17.356  5794  5805 D BtGatt.GattService: start scan with filters
,10-10 20:34:17.357  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-10 20:34:17.357  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:17.358  5794  5813 D BtGatt.ScanManager: stopping BLe Batch
,10-10 20:34:17.363  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-10 20:34:17.363  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-10 20:34:17.363  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:34:17.364  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-10 20:34:17.364  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-10 20:34:17.364  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-10 20:34:17.364  5566  5612 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-10 20:34:17.364  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-10 20:34:17.364  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-10 20:34:17.366  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-10 20:34:17.367  5835  5835 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33252]" dev="sockfs" ino=33252 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-10 20:34:17.367  5835  5835 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33252]" dev="sockfs" ino=33252 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-10 20:34:17.366  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-10 20:34:17.366  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-10 20:34:17.366  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-10 20:34:17.367  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-10 20:34:17.367  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-10 20:34:17.367  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-10 20:34:17.368  5566  5895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-10 20:34:17.368  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-10 20:34:17.368  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-10 20:34:17.368  5566  5612 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-10 20:34:17.368  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-10 20:34:17.369  5566  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-10 20:34:17.372  5566  5895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-10 20:34:17.379  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,10-10 20:34:17.379  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-10 20:34:17.380  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-10 20:34:17.380  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
10-10 20:34:17.380  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:34:17.380  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-10 20:34:17.380  5566  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-10 20:34:17.380  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-10 20:34:17.381  5566  5612 D BluetoothAdapter: STATE_ON
,10-10 20:34:17.385  5794  5822 D BtGatt.GattService: registerClient() - UUID=d1816b21-7b1e-40fc-828e-a6a468a31e54
,10-10 20:34:17.385  5794  5810 D BtGatt.GattService: onClientRegistered() - UUID=d1816b21-7b1e-40fc-828e-a6a468a31e54, clientIf=6
,10-10 20:34:17.386  5566  5576 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
10-10 20:34:17.387  5794  5812 D BtGatt.AdvertiseManager: message : 0
,10-10 20:34:17.392  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-10 20:34:17.392  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:17.393  5794  5810 D BtGatt.GattService: current time is 257610624039
10-10 20:34:17.393  5794  5810 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -86, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 105, -103, 8, -127, -113, 115, 1, -128, -47, 31, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 37, -47, 14, -113, 116, -46, 1, -128, -80, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -78, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -77, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-10 20:34:17.393  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
10-10 20:34:17.393  5794  5810 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-10 20:34:17.394  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-10 20:34:17.394  5794  5813 D BtGatt.ScanManager: handling starting scan
10-10 20:34:17.394  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-10 20:34:17.394  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-10 20:34:17.395  5794  5812 D BtGatt.AdvertiseManager: starting multi advertising
,10-10 20:34:17.401  5794  5810 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-10 20:34:17.401  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:17.401  5794  5813 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-10 20:34:17.411  5794  5810 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,10-10 20:34:17.416  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-10 20:34:17.416  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-10 20:34:17.416  5794  5813 D BtGatt.ScanManager: Starting BLE batch scan
10-10 20:34:17.416  5794  5813 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-10 20:34:17.421  5794  5810 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,10-10 20:34:17.422  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
,10-10 20:34:17.422  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-10 20:34:17.422  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-10 20:34:17.422  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-10 20:34:17.422  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-10 20:34:17.422  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-10 20:34:17.422  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser, adv = true, disc = true
10-10 20:34:17.422  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-10 20:34:17.423  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-10 20:34:17.426  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-10 20:34:17.426  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-10 20:34:17.426  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-10 20:34:17.426  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-10 20:34:17.426  5566  5566 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-10 20:34:17.427  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:34:17.427  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
10-10 20:34:17.427  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-10 20:34:17.427  5566  5566 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
10-10 20:34:17.427  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
10-10 20:34:17.429  5566  5566 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
10-10 20:34:17.430  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
10-10 20:34:17.431  5794  5810 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-10 20:34:17.431  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-10 20:34:17.436  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-10 20:34:17.436  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-10 20:34:17.930  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,10-10 20:34:17.931  5566  5566 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-10 20:34:17.931  5566  5566 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-10 20:34:18.029   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:19.030   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-10 20:34:20.429  5566  5612 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,10-10 20:34:20.430  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-10 20:34:20.430  5566  5612 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-10 20:34:20.430  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-10 20:34:20.431  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-10 20:34:20.431  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-10 20:34:20.431  5566  5895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-10 20:34:20.431  5566  5895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-10 20:34:20.431  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-10 20:34:20.431  5566  5895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-10 20:34:20.431  5566  5612 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-10 20:34:20.432  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-10 20:34:20.432  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-10 20:34:20.432  5566  5566 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-10 20:34:20.432  5566  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f6ca86 removed from the list
10-10 20:34:20.432  5566  5566 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-10 20:34:20.433  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-10 20:34:20.433  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-10 20:34:20.433  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-10 20:34:20.433  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-10 20:34:20.433  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-10 20:34:20.433  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-10 20:34:20.436  5566  5612 D BluetoothAdapter: STATE_ON
,10-10 20:34:20.437  5794  5833 D BtGatt.GattService: stopScan() - queue size =1
10-10 20:34:20.439  5794  5805 D BtGatt.GattService: unregisterClient() - clientIf=5
10-10 20:34:20.440  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-10 20:34:20.440  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-10 20:34:20.440  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-10 20:34:20.440  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:34:20.441  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-10 20:34:20.441  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
10-10 20:34:20.441  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
10-10 20:34:20.441  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,10-10 20:34:20.448  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-10 20:34:20.448  5794  5794 D BtGatt.ScanManager: awakened up at time 260665
10-10 20:34:20.448  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-10 20:34:20.450  5794  5812 D BtGatt.AdvertiseManager: message : 1
10-10 20:34:20.451  5794  5812 D BtGatt.AdvertiseManager: stop advertise for client 6
10-10 20:34:20.453  5794  5810 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-10 20:34:20.453  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:20.454  5794  5813 D BtGatt.ScanManager: stopping BLe Batch
,10-10 20:34:20.463  5794  5810 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
10-10 20:34:20.463  5794  5810 D BtGatt.GattService: Client app is not null!
,10-10 20:34:20.465  5794  5833 D BtGatt.GattService: unregisterClient() - clientIf=6
10-10 20:34:20.465  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-10 20:34:20.466  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-10 20:34:20.466  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-10 20:34:20.466  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-10 20:34:20.466  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-10 20:34:20.466  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-10 20:34:20.466  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-10 20:34:20.466  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-10 20:34:20.466  5566  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-10 20:34:20.469  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-10 20:34:20.469  5566  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-10 20:34:20.469  5566  5612 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-10 20:34:20.470  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-10 20:34:20.470  5566  5612 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
10-10 20:34:20.471  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-10 20:34:20.471  5566  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6d3f47 removed from the list
10-10 20:34:20.472  5566  5612 D io.jxcore.node.ConnectivityMonitor: stop
10-10 20:34:20.472  5566  5566 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-10 20:34:20.472  5566  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-10 20:34:20.472  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
10-10 20:34:20.472  5566  5566 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-10 20:34:20.474  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
10-10 20:34:20.474  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-10 20:34:20.474  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-10 20:34:20.474  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-10 20:34:20.474  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-10 20:34:20.474  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-10 20:34:20.474  5566  5612 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-10 20:34:20.475  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,10-10 20:34:20.476  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
10-10 20:34:20.477  5794  5810 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-10 20:34:20.477  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:20.477  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
10-10 20:34:20.477  5794  5813 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-10 20:34:20.478  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,10-10 20:34:20.480  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
10-10 20:34:20.481  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
10-10 20:34:20.482  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
10-10 20:34:20.482  5566  5612 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-10 20:34:20.499  5794  5810 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-10 20:34:20.499  5794  5810 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-10 20:34:20.499  5794  5810 D BtGatt.GattService: current time is 260717123187
10-10 20:34:20.499  5794  5810 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -89, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -79, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -82, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-10 20:34:20.500  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-10 20:34:20.500  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-10 20:34:20.500  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-10 20:34:20.500  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-10 20:34:20.500  5794  5810 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-10 20:34:20.972  5566  5566 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-10 20:34:22.329   924  2924 D ConnectivityService: handlePromptUnvalidated 102
,10-10 20:34:22.487  5566  5612 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-10 20:34:22.644  5566  5897 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 151, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-10 20:34:22.644  5566  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-10 20:34:23.459  5566  5897 W !!      : call onHalfStreamCopied
,10-10 20:34:23.459  5566  5897 I testCopyDataAndClose: closing input stream
,10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 151, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 151, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-10 20:34:24.233  5566  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-10 20:34:25.318   924  2922 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,10-10 20:34:25.799   924  2922 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 17 -> obsolete
,10-10 20:34:27.967  5566  5612 I StreamCopyingThreadTest: Starting test: testRun
,10-10 20:34:27.972  5566  5898 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: My test thread name). Connection data: Peer properties: [null null].
10-10 20:34:27.972  5566  5898 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-10 20:34:32.980  5566  5899 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,10-10 20:34:32.983  5566  5612 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-10 20:34:33.095  5566  5900 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-10 20:34:33.095  5566  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-10 20:34:34.031   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-10 20:34:34.810  5566  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-10 20:34:35.032   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:36.033   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:37.034   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:38.027  5863  5863 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-10 20:34:38.036   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-10 20:34:38.646  5566  5612 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-10 20:34:38.649  5566  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
10-10 20:34:38.649  5566  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-10 20:34:38.649  5566  5901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: My test thread name). Connection data: Peer properties: [null null].
10-10 20:34:38.649  5566  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
10-10 20:34:38.650  5566  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-10 20:34:38.652  5566  5612 I StreamCopyingThreadTest: Starting test: testSetBufferSize
10-10 20:34:38.653  5566  5612 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-10 20:34:38.653  5566  5612 I StreamCopyingThreadTest: Starting test: testRunWithException
,10-10 20:34:38.655  5566  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-10 20:34:38.655  5566  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-10 20:34:38.656  5566  5902 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 163, thread name: My test thread name): Test exception.
10-10 20:34:38.656  5566  5902 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-10 20:34:38.656  5566  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-10 20:34:38.656  5566  5902 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-10 20:34:38.657  5566  5902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-10 20:34:38.657  5566  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-10 20:34:38.658  5566  5612 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
10-10 20:34:38.658  5566  5612 E com.test.thalitest.ThaliTestRunner: 
10-10 20:34:38.658  5566  5612 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-10 20:34:38.658  5566  5612 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.,junit.runners.ParentRunner.run(ParentRunner.java:363)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
10-10 2,0:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-10 20:34:38.659  5566  5612 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runne,rs.ParentRunner.runChildren(ParentRunner.java:288)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:38.660  5566  5612 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-10 20:34:38.662  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG UnitTest_app: 'Running unit tests'
10-10 20:34:38.662  5566  5612 I jxcore-log: 
10-10 20:34:38.662  5566  5612 I jxcore-log: *Native tests were executed*
10-10 20:34:38.662  5566  5612 I jxcore-log: 
10-10 20:34:38.662  5566  5612 I jxcore-log: Total number of executed tests:  82
10-10 20:34:38.662  5566  5612 I jxcore-log: 
10-10 20:34:38.662  5566  5612 I jxcore-log: Number of passed tests:  80
10-10 20:34:38.662  5566  5612 I jxcore-log: 
10-10 20:34:38.662  5566  5612 I jxcore-log: Number of failed tests:  2
10-10 20:34:38.662  5566  5612 I jxcore-log: 
10-10 20:34:38.663  5566  5612 I jxcore-log: Number of ignored tests:  0
10-10 20:34:38.663  5566  5612 I jxcore-log: 
10-10 20:34:38.6,63  5566  5612 I jxcore-log: Total duration:  45119
10-10 20:34:38.663  5566  5612 I jxcore-log: 
10-10 20:34:38.663  5566  5612 I jxcore-log: Failed to execute UT.
10-10 20:34:38.663  5566  5612 I jxcore-log: 
10-10 20:34:38.664  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-10 20:34:38.664  5566  5612 I jxcore-log: 
10-10 20:34:38.665  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-10 20:34:38.665  5566  5612 I jxcore-log: 
10-10 20:34:38.669  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.669  5566  5612 I jxcore-log: 
10-10 20:34:38.670  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.670  5566  5612 I jxcore-log: 
10-10 20:34:38.670  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.670  5566  5612 I jxcore-log: 
10-10 20:34:38.671  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-10 20:34:38.671  5566  5612 I jxcore-log: 
10-10 20:34:38.672  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-10 20:34:38.672  5566  5612 I jxcore-log: 
10-10 20:34:38.673  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-10 20:34:38.673  5566  5612 I jxcore-log: 
10-10 20:34:38.673  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-10 20:34:38.673  5566  5612 I jxcore-log: 
10-10 20:34:38.673  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.673  5566  5612 I jxcore-log: 
10-10 20:34:38.674  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.674  5566  5612 I jxcore-log: 
10-10 20:34:38.674  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-10 20:34:38.674  5566  5612 I jxcore-log: 
10-10 20:34:38.674  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-10 20:34:38.674  5566  5612 I jxcore-log: 
10-10 20:34:38.674  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-10 20:34:38.674  5566  5612 I jxcore-log: 
10-10 20:34:38.675  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-10 20:34:38.675  5566  5612 I jxcore-log: 
10-10 20:34:38.675  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.675  5566  5612 I jxcore-log: 
10-10 20:34:38.675  5566  56,12 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.675  5566  5612 I jxcore-log: 
10-10 20:34:38.676  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.676  5566  5612 I jxcore-log: 
10-10 20:34:38.676  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.676  5566  5612 I jxcore-log: 
10-10 20:34:38.676  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.676  5566  5612 I jxcore-log: 
10-10 20:34:38.677  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.677  5566  5612 I jxcore-log: 
10-10 20:34:38.677  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.677  5566  5612 I jxcore-log: 
10-10 20:34:38.677  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.677  5566  5612 I jxcore-log: 
10-10 20:34:38.677  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.677  5566  5612 I jxcore-log: 
10-10 20:34:38.678  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.678  5566  5612 I jxcore-log: 
10-10 20:34:38.678  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.678  5566  5612 I jxcore-log: 
10-10 20:34:38.678  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.678  5566  5612 I jxcore-log: 
10-10 20:34:38.678  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.678  5566  5612 I jxcore-log: 
10-10 20:34:38.680  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.680  5566  5612 I jxcore-log: 
10-10 20:34:38.680  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.680  5566  5612 I jxcore-log: 
,10-10 20:34:38.680  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.680  5566  5612 I jxcore-log: 
10-10 20:34:38.680  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.680  5566  5612 I jxcore-log: 
10-10 20:34:38.681  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.681  5566  5612 I jxcore-log: 
10-10 20:34:38.681  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.681  5566  5612 I jxcore-log: 
10-10 20:34:38.681  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-10 20:34:38.681  5566  5612 I jxcore-log: 
10-10 20:34:38.681  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-10 20:34:38.681  5566  5612 I jxcore-log: 
10-10 20:34:38.682  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-10 20:34:38.682  5566  5612 I jxcore-log: 
10-10 20:34:38.682  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.682  5566  5612 I jxcore-log: 
10-10 20:34:38.682  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.682  5566  5612 I jxcore-log: 
10-10 20:34:38.682  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.682  5566  5612 I jxcore-log: 
10-10 20:34:38.682  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-10 20:34:38.682  5566  5612 I jxcore-log: 
10-10 20:34:38.683  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-10 20:34:38.683  5566  5612 I jxcore-log: 
,10-10 20:34:38.683  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.683  5566  5612 I jxcore-log: 
10-10 20:34:38.683  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.683  5566  5612 I jxcore-log: 
,10-10 20:34:38.683  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-10 20:34:38.683  5566  5612 I jxcore-log: 
10-10 20:34:38.684  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-10 20:34:38.684  5566  5612 I jxcore-log: 
10-10 20:34:38.684  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-10 20:34:38.684  5566  5612 I jxcore-log: 
10-10 20:34:38.684  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-10 20:34:38.684  5566  5612 I jxcore-log: 
10-10 20:34:38.684  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-10 20:34:38.684  5566  5612 I jxcore-log: 
10-10 20:34:38.685  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
10-10 20:34:38.685  5566  5612 I jxcore-log: 
10-10 20:34:38.685  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-10 20:34:38.685  5566  5612 I jxcore-log: 
10-10 20:34:38.686  5566  5566 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-10 20:34:38.690  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-10 20:34:38.690  5566  5612 I jxcore-log: 
10-10 20:34:38.690  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - WARN testUtils: 'myNameCallback not set!'
10-10 20:34:38.690  5566  5612 I jxcore-log: 
,10-10 20:34:38.691  5566  5612 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-10 20:34:38.692  5566  5612 I jxcore-log: 2016-10-11 00:34:38 - DEBUG UnitTest_app: 'Running for NATIVE network type'
10-10 20:34:38.692  5566  5612 I jxcore-log: 
,10-10 20:34:39.036   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-10 20:34:40.745  5566  5612 I jxcore-log: 2016-10-11 00:34:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-10 20:34:40.745  5566  5612 I jxcore-log: 
,10-10 20:34:41.093  5566  5612 I jxcore-log: 2016-10-11 00:34:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-10 20:34:41.093  5566  5612 I jxcore-log: 
,10-10 20:34:41.107  5566  5612 I jxcore-log: 2016-10-11 00:34:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-10 20:34:41.107  5566  5612 I jxcore-log: 
,10-10 20:34:42.223  5566  5612 I jxcore-log: 2016-10-11 00:34:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-10 20:34:42.223  5566  5612 I jxcore-log: 
,10-10 20:34:42.371  5566  5612 I jxcore-log: 2016-10-11 00:34:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-10 20:34:42.371  5566  5612 I jxcore-log: 
,10-10 20:34:42.376  5566  5612 I jxcore-log: 2016-10-11 00:34:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-10 20:34:42.376  5566  5612 I jxcore-log: 
,10-10 20:34:42.381  5566  5612 I jxcore-log: 2016-10-11 00:34:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-10 20:34:42.381  5566  5612 I jxcore-log: 
,10-10 20:34:42.941  5566  5612 I jxcore-log: 2016-10-11 00:34:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-10 20:34:42.941  5566  5612 I jxcore-log: 
,10-10 20:34:42.994  5566  5612 I jxcore-log: 2016-10-11 00:34:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-10 20:34:42.994  5566  5612 I jxcore-log: 
,10-10 20:34:43.007  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-10 20:34:43.007  5566  5612 I jxcore-log: 
,10-10 20:34:43.011  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-10 20:34:43.011  5566  5612 I jxcore-log: 
,10-10 20:34:43.295  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-10 20:34:43.295  5566  5612 I jxcore-log: 
,10-10 20:34:43.421  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-10 20:34:43.421  5566  5612 I jxcore-log: 
,10-10 20:34:43.657  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-10 20:34:43.657  5566  5612 I jxcore-log: 
,10-10 20:34:43.820  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
10-10 20:34:43.820  5566  5612 I jxcore-log: 
,10-10 20:34:43.828  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-10 20:34:43.828  5566  5612 I jxcore-log: 
,10-10 20:34:43.833  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-10 20:34:43.833  5566  5612 I jxcore-log: 
,10-10 20:34:43.840  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
10-10 20:34:43.840  5566  5612 I jxcore-log: 
,10-10 20:34:43.854  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-10 20:34:43.854  5566  5612 I jxcore-log: 
,10-10 20:34:43.859  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-10 20:34:43.859  5566  5612 I jxcore-log: 
,10-10 20:34:43.886  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-10 20:34:43.886  5566  5612 I jxcore-log: 
,10-10 20:34:43.920  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-10 20:34:43.920  5566  5612 I jxcore-log: 
,10-10 20:34:43.927  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-10 20:34:43.927  5566  5612 I jxcore-log: 
,10-10 20:34:43.933  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-10 20:34:43.933  5566  5612 I jxcore-log: 
,10-10 20:34:43.949  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-10 20:34:43.949  5566  5612 I jxcore-log: 
,10-10 20:34:43.953  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-10 20:34:43.953  5566  5612 I jxcore-log: 
,10-10 20:34:43.959  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-10 20:34:43.959  5566  5612 I jxcore-log: 
,10-10 20:34:43.964  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-10 20:34:43.964  5566  5612 I jxcore-log: 
,10-10 20:34:43.978  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-10 20:34:43.978  5566  5612 I jxcore-log: 
,10-10 20:34:43.999  5566  5612 I jxcore-log: 2016-10-11 00:34:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-10 20:34:43.999  5566  5612 I jxcore-log: 
,10-10 20:34:44.008  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-10 20:34:44.008  5566  5612 I jxcore-log: 
,10-10 20:34:44.020  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-10 20:34:44.020  5566  5612 I jxcore-log: 
,10-10 20:34:44.029  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-10 20:34:44.029  5566  5612 I jxcore-log: 
,10-10 20:34:44.041  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-10 20:34:44.041  5566  5612 I jxcore-log: 
,10-10 20:34:44.051  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-10 20:34:44.051  5566  5612 I jxcore-log: 
,10-10 20:34:44.056  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-10 20:34:44.056  5566  5612 I jxcore-log: 
,10-10 20:34:44.062  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-10 20:34:44.062  5566  5612 I jxcore-log: 
,10-10 20:34:44.067  5566  5612 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-10 20:34:44.068  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - INFO testUtils: 'BLE multiple advertisement supported'
10-10 20:34:44.068  5566  5612 I jxcore-log: 
,10-10 20:34:44.174  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - DEBUG CoordinatedClient: 'connected to the test server'
10-10 20:34:44.174  5566  5612 I jxcore-log: 
,10-10 20:34:44.276  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-10 20:34:44.276  5566  5612 I jxcore-log: 
,10-10 20:34:44.278  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - DEBUG CoordinatedClient: 'test client failed'
10-10 20:34:44.278  5566  5612 I jxcore-log: 
,10-10 20:34:44.281  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-10 20:34:44.281  5566  5612 I jxcore-log: 
,10-10 20:34:44.284  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-10 20:34:44.284  5566  5612 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-10 20:34:44.284  5566  5612 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-10 20:34:44.284  5566  5612 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-10 20:34:44.284  5566  5612 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-10 20:34:44.284  5566  5612 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-10 20:34:44.284  5566  5612 I jxcore-log: 
,10-10 20:34:44.286  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-10 20:34:44.286  5566  5612 I jxcore-log: 
,10-10 20:34:44.288  5566  5612 I jxcore-log: 2016-10-11 00:34:44 - ERROR runTests: 'Test client failed: Native unit tests failed
10-10 20:34:44.288  5566  5612 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-10 20:34:44.288  5566  5612 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-10 20:34:44.288  5566  5612 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-10 20:34:44.288  5566  5612 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-10 20:34:44.288  5566  5612 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-10 20:34:44.288  5566  5612 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
10-10 20:34:44.288  5566  5612 I jxcore-log: 
,10-10 20:34:44.822  5911  5911 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-10 20:34:44.827  5911  5911 D AndroidRuntime: CheckJNI is OFF
,10-10 20:34:44.855  5911  5911 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-10 20:34:44.885  5911  5911 I Radio-JNI: register_android_hardware_Radio DONE
,10-10 20:34:44.900  5911  5911 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-10 20:34:44.911   924   937 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-10 20:34:44.912   924   937 I ActivityManager: Killing 5566:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-10 20:34:45.013   924   934 I WindowState: WIN DEATH: Window{700e68c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-10 20:34:45.013   924  3687 D GraphicsStats: Buffer count: 2
,10-10 20:34:45.014   924  2923 D WifiService: Client connection lost with reason: 4
,10-10 20:34:45.054   924   948 I art     : Starting a blocking GC Explicit
10-10 20:34:45.053   924   937 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-10 20:34:45.055   924   937 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-10 20:34:45.056   924   937 E ActivityManager: Failure starting process com.test.thalitest
10-10 20:34:45.056   924   937 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-10 20:34:45.056   924   937 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:45.056   924   937 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:45.056   924   937 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-10 20:34:45.056   924   937 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-10 20:34:45.056   924   937 I ActivityManager:   Force finishing activity ActivityRecord{b74ec7e u0 com.test.thalitest/.MainActivity t2}
,10-10 20:34:45.064   924  3719 W ActivityManager: Spurious death for ProcessRecord{1ecbf13 0:com.test.thalitest/u0a77}, curProc for 5566: null
,10-10 20:34:45.068   924   942 W WindowManager: Attempted to add application window with unknown token Token{84b45df ActivityRecord{b74ec7e u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,10-10 20:34:45.068   924   942 W WindowManager: Token{84b45df ActivityRecord{b74ec7e u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{84b45df ActivityRecord{b74ec7e u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-10 20:34:45.068   924   942 W WindowManager: view not successfully added to wm, removing view
10-10 20:34:45.069   924   942 W WindowManager: Exception when adding starting window
10-10 20:34:45.069   924   942 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a2f475a V.E...... R.....ID 0,0-0,0} not attached to window manager
10-10 20:34:45.069   924   942 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-10 20:34:45.069   924   942 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-10 20:34:45.069   924   942 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-10 20:34:45.069   924   942 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-10 20:34:45.069   924   942 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-10 20:34:45.069   924   942 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:45.069   924   942 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:45.069   924   942 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-10 20:34:45.069   924   942 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-10 20:34:45.139   924   948 I art     : Explicit concurrent mark sweep GC freed 64516(4MB) AllocSpace objects, 17(680KB) LOS objects, 33% free, 29MB/43MB, paused 1.620ms total 85.032ms
,10-10 20:34:45.159   924   948 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-10 20:34:45.162  5911  5911 I art     : System.exit called, status: 0
,10-10 20:34:45.162  5911  5911 I AndroidRuntime: VM exiting with result code 0.
,10-10 20:34:45.178   924   948 I ActivityManager: Start proc 5921:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-10 20:34:45.178   924   948 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-10 20:34:45.183   924   937 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-10 20:34:45.188  5794  5794 D BluetoothMapAppObserver: onReceive
,10-10 20:34:45.189  5794  5794 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-10 20:34:45.194   924  2883 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-10 20:34:45.196  3604  3604 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-10 20:34:45.199  3848  4055 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-10 20:34:45.212  3604  5932 I Keyboard.Facilitator.DecoderInitializer: run()
,10-10 20:34:45.227  3342  5935 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-10 20:34:45.228  3604  5932 I Decoder : createOrResetDecoder
,10-10 20:34:45.249   924   924 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-10 20:34:45.251  3721  3721 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-10 20:34:45.260    13    13 W kworker/1:0: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-10 20:34:45.274    13    13 W kworker/1:0: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-10 20:34:45.281  3524  3524 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-10 20:34:45.281  3524  3524 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-10 20:34:45.294    13    13 W kworker/1:0: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-10 20:34:45.303  3524  3524 I ConfigService: onCreate
,10-10 20:34:45.308  3524  5941 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-10 20:34:45.308  3524  5941 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-10 20:34:45.308  3524  5941 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,10-10 20:34:45.311  3524  5941 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-10 20:34:45.312  3990  5940 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-10 20:34:45.325  3990  5940 D AccountUtils: Clearing selected account for com.test.thalitest
,10-10 20:34:45.329  3604  5932 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-10 20:34:45.334  3762  3893 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
10-10 20:34:45.334   924   936 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
10-10 20:34:45.335   924   936 E PackageManager: Failed to write settings, restoring backup
10-10 20:34:45.335   924   936 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-10 20:34:45.335   924   936 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-10 20:34:45.335   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-10 20:34:45.335   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-10 20:34:45.335   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-10 20:34:45.335   924   936 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:45.335   924   936 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:45.335   924   936 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-10 20:34:45.340   924   937 E DropBoxManagerService: Can't write: system_server_wtf
10-10 20:34:45.340   924   937 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-10 20:34:45.340   924   937 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-10 20:34:45.340   924   937 E DropBoxManagerService: 	... 13 more
,10-10 20:34:45.347   924  3786 I ActivityManager: Start proc 5944:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-10 20:34:45.347  3762  3893 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-10 20:34:45.347  3762  3893 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3762
10-10 20:34:45.347  3762  3893 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:45.347  3762  3893 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: Can't write: system_app_crash
10-10 20:34:45.350   924  5950 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-10 20:34:45.350   924  5950 E DropBoxManagerService: 	... 5 more
,10-10 20:34:45.351   924  3554 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-10 20:34:45.356  3762  3893 I Process : Sending signal. PID: 3762 SIG: 9
10-10 20:34:45.361  3342  5935 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
10-10 20:34:45.362  3342  5935 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-10 20:34:45.362  3342  5935 E AndroidRuntime: Process: android.process.acore, PID: 3342
10-10 20:34:45.362  3342  5935 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-10 20:34:45.362  3342  5935 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-10 20:34:45.366   924  5958 E DropBoxManagerService: Can't write: system_app_crash
10-10 20:34:45.366   924  5958 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-10 20:34:45.366   924  5958 E DropBoxManagerService: 	... 5 more
,10-10 20:34:45.374  3342  5935 I Process : Sending signal. PID: 3342 SIG: 9
,10-10 20:34:45.408   924  3554 D GraphicsStats: Buffer count: 1
10-10 20:34:45.408   924  3054 I WindowState: WIN DEATH: Window{de98848 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-10 20:34:45.414   924  3751 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3762) has died
,10-10 20:34:45.414   924  3751 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
10-10 20:34:45.415   924  3751 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-10 20:34:45.420   924  3775 I ActivityManager: Process android.process.acore (pid 3342) has died
,10-10 20:34:45.420   924  3775 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-10 20:34:45.432   924   937 I ActivityManager: Start proc 5959:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-10 20:34:45.671   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
