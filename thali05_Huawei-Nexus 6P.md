#### Test 879664320d5b49a_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of system
10-05 13:50:52.006   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
10-05 13:50:52.469  5580  5580 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-05 13:50:52.474  5580  5580 D AndroidRuntime: CheckJNI is OFF
10-05 13:50:52.502  5580  5580 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-05 13:50:52.538  5580  5580 I Radio-JNI: register_android_hardware_Radio DONE
10-05 13:50:52.552  5580  5580 D AndroidRuntime: Calling main entry com.android.commands.am.Am
10-05 13:50:52.565   931  3154 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-05 13:50:52.610   931  3154 I ActivityManager: Start proc 5589:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-05 13:50:52.629  5580  5580 D AndroidRuntime: Shutting down VM
,10-05 13:50:52.957   931  3819 I WindowManager: Screenshot max retries 4 of Token{e76f2e5 ActivityRecord{fdab1dc u0 com.test.thalitest/.MainActivity t2}} appWin=Window{8296074 u0 Starting com.test.thalitest} drawState=2
,10-05 13:50:53.024  5589  5589 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-05 13:50:53.059  5589  5589 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-05 13:50:53.087  5589  5589 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 2916-2938)
,10-05 13:50:53.087  5589  5589 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-05 13:50:53.108  5589  5589 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c327e92}
,10-05 13:50:53.108  5589  5589 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-05 13:50:53.108  5589  5589 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-05 13:50:53.114  5589  5589 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-05 13:50:53.115  5589  5589 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-05 13:50:53.159  5589  5589 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-05 13:50:53.172  5589  5589 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-05 13:50:53.172  5589  5589 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-05 13:50:53.173  5589  5589 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-05 13:50:53.173  5589  5589 I Adreno  : Build Date                       : 12/06/15
10-05 13:50:53.173  5589  5589 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-05 13:50:53.173  5589  5589 I Adreno  : Local Branch                     : mybranch17112971
10-05 13:50:53.173  5589  5589 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-05 13:50:53.173  5589  5589 I Adreno  : Remote Branch                    : NONE
10-05 13:50:53.173  5589  5589 I Adreno  : Reconstruct Branch               : NOTHING
,10-05 13:50:53.235   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc1525b:true
,10-05 13:50:53.271   407   407 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24527]" dev="sockfs" ino=24527 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 13:50:53.271   407   407 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[24527]" dev="sockfs" ino=24527 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 13:50:53.286  5589  5589 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-05 13:50:53.295  5589  5589 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-05 13:50:53.318   740   740 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30641]" dev="sockfs" ino=30641 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 13:50:53.318   740   740 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30641]" dev="sockfs" ino=30641 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-05 13:50:53.321  5350  5350 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[24538]" dev="sockfs" ino=24538 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-05 13:50:53.321  5350  5350 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[24538]" dev="sockfs" ino=24538 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-05 13:50:53.326  5589  5613 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-05 13:50:53.360  5589  5626 I OpenGLRenderer: Initialized EGL, version 1.4
,10-05 13:50:53.448   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +488ms (total +867ms)
,10-05 13:50:53.475  5589  5589 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5589
,10-05 13:50:53.561  5589  5589 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-05 13:50:53.669  5589  5629 D jxcore_app_log: JniHelper::setJavaVM(0xf54bc000), pthread_self() = -564127440
,10-05 13:50:53.673  5589  5629 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-05 13:50:53.673  5589  5629 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-05 13:50:53.673  5589  5629 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-05 13:50:53.673  5589  5629 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-05 13:50:53.673  5589  5629 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-05 13:50:53.673  5589  5629 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d61289b added. We now have 1 listener(s)
,10-05 13:50:53.675  5589  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-05 13:50:53.675  5589  5629 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:50:53.676  5589  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:50:53.676  5589  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-05 13:50:53.678  5589  5629 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a36b176 added. We now have 1 listener(s)
10-05 13:50:53.678  5589  5629 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:50:53.683   931  2927 D WifiService: New client listening to asynchronous messages
,10-05 13:50:53.684  5589  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:50:53.684  5589  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-05 13:50:53.684  5589  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-05 13:50:53.684  5589  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-05 13:50:53.684  5589  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-05 13:50:53.685  5589  5629 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:50:53.685  5589  5629 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-05 13:50:53.689  5589  5629 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-05 13:50:53.689  5589  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:50:53.689  5589  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:50:53.689  5589  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:50:53.689  5589  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:50:53.689  5589  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:50:53.689  5589  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:50:53.689  5589  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:50:53.689  5589  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:50:53.689  5589  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,10-05 13:50:53.689  5589  5629 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 13:50:53.690  5589  5629 I io.jxcore.node.LifeCycleMonitor: start: OK
10-05 13:50:53.693  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:50:53.697  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:50:53.706  5589  5589 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-05 13:50:54.010  5589  5635 W jxcore-log: Initializing JXcore engine
10-05 13:50:54.010  5589  5635 W jxcore-log: JXcore engine is ready
,10-05 13:50:54.034  5635  5635 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12580 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-05 13:50:54.034  5635  5635 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16473]" dev="sockfs" ino=16473 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-05 13:50:54.034  5635  5635 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-05 13:50:54.034  5635  5635 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30620]" dev="sockfs" ino=30620 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-05 13:50:54.042  5589  5635 W jxcore-log: Starting JXcore engine
,10-05 13:50:54.091  5589  5635 W jxcore-log: Platform android
10-05 13:50:54.091  5589  5635 W jxcore-log: 
,10-05 13:50:54.091  5589  5635 W jxcore-log: Process ARCH arm
10-05 13:50:54.091  5589  5635 W jxcore-log: 
,10-05 13:50:54.193  5589  5635 I jxcore-log: JXcore Cordova bridge is ready!
10-05 13:50:54.193  5589  5635 I jxcore-log: 
,10-05 13:50:54.193  5589  5635 W jxcore-log: JXcore engine is started
,10-05 13:50:54.201  5589  5629 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-05 13:50:54.207  5589  5589 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-05 13:50:59.634   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-05 13:50:59.634   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-05 13:51:02.483   931  2925 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-05 13:51:03.765  5589  5635 I jxcore-log: 2016-10-05 17:51:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-05 13:51:03.765  5589  5635 I jxcore-log: 
,10-05 13:51:03.767  5589  5635 I jxcore-log: 2016-10-05 17:51:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-05 13:51:03.767  5589  5635 I jxcore-log: 
,10-05 13:51:03.771  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:51:03.771  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:03.771  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:03.771  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:03.771  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:03.771  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:03.771  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:03.771  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:51:03.772  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:51:03.774  5589  5635 I jxcore-log: 2016-10-05 17:51:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-05 13:51:03.774  5589  5635 I jxcore-log: 
,10-05 13:51:03.775  5589  5635 I jxcore-log: 2016-10-05 17:51:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-05 13:51:03.775  5589  5635 I jxcore-log: 
,10-05 13:51:04.022  5589  5635 I jxcore-log: 2016-10-05 17:51:04 - DEBUG UnitTest_app: 'Running unit tests'
10-05 13:51:04.022  5589  5635 I jxcore-log: 
,10-05 13:51:04.023  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:51:04.023  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64915f0 added. We now have 2 listener(s)
,10-05 13:51:04.024  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:51:04.024  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:51:04.024  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:51:04.024  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 13:51:04.024  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96da769 added. We now have 2 listener(s)
10-05 13:51:04.024  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:51:04.025  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:51:04.027  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:51:04.030  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:51:04.030  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:04.030  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:04.030  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:04.030  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:04.030  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:04.030  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:04.030  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:51:04.030  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:51:04.031  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 13:51:04.031  5589  5635 D executeNativeTests: Running unit tests
,10-05 13:51:04.036  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:04.043  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:04.067  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:51:04.067  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f added. We now have 3 listener(s)
10-05 13:51:04.068  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:51:04.068  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:51:04.068  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 13:51:04.068  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:51:04.068  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c added. We now have 3 listener(s)
,10-05 13:51:04.068  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:51:04.068  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:51:04.070  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:51:04.072  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:51:04.072  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:04.072  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:04.072  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:04.072  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:04.072  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:04.072  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:04.072  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:04.073  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:51:04.073  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 13:51:04.074  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-05 13:51:04.074  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:51:04.074  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:51:04.074  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:51:04.075  5589  5635 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-05 13:51:04.075  5589  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-05 13:51:04.075  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 13:51:04.075  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:51:04.075  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:51:04.075  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:51:04.076  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:04.076  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:04.076  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:04.076  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:04.077  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:04.077  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:51:04.077  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:04.077  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:51:04.077  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f removed from the list
,10-05 13:51:04.077  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:04.077  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c removed from the list
,10-05 13:51:04.084  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:04.090  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:04.090  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:04.090  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:04.091  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:04.091  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:04.091  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:04.091  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:04.091  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:04.091  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:04.092  5589  5635 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-05 13:51:04.093  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:04.093  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:04.093  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:04.093  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:51:04.093  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:04.093  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:04.093  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:04.093  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:04.093  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:04.093  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:04.093  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:04.093  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:04.093  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:04.093  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:51:04.093  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:04.093  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:04.094  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:04.094  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:04.094  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:04.098  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-05 13:51:04.098  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-05 13:51:04.098  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-05 13:51:04.099  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-05 13:51:04.099  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:04.099  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:04.099  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:04.099  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:04.099  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:04.100  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:04.100  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:04.100  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:04.100  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:04.100  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:04.100  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:51:04.100  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:04.100  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:04.100  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:04.100  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:04.100  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:04.100  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:04.100  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:04.100  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:04.101  5589  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-05 13:51:04.102  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:51:04.104  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:51:04.104  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:04.104  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:04.104  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:04.104  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:04.104  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:04.104  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:04.104  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:04.105  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:04.105  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:51:04.105  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:51:04.105  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:51:04.105  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:51:04.105  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:51:04.105  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 13:51:04.109  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:04.110  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 13:51:04.110  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 13:51:04.114  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:04.114  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-05 13:51:04.116  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 13:51:04.116  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-05 13:51:04.117  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-05 13:51:04.118  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-05 13:51:04.118  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 13:51:04.118  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:51:04.118  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:51:04.119  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:51:04.119  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 13:51:04.120  5589  5635 D BluetoothAdapter: STATE_ON
10-05 13:51:04.122  4554  4570 D BtGatt.GattService: registerClient() - UUID=f2bee9d6-2b8e-4bf4-a3b4-10c8d24793b6
10-05 13:51:04.122  4554  4629 D BtGatt.GattService: onClientRegistered() - UUID=f2bee9d6-2b8e-4bf4-a3b4-10c8d24793b6, clientIf=5
10-05 13:51:04.123  5589  5599 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 13:51:04.124  4554  4786 D BtGatt.GattService: start scan with filters
10-05 13:51:04.127  4554  4632 D BtGatt.ScanManager: handling starting scan
10-05 13:51:04.128  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:51:04.128  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:51:04.128  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:51:04.128  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:51:04.128  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:51:04.128  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:51:04.128  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-05 13:51:04.130  4554  4632 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:51:04.131  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:51:04.131  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:51:04.132  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:51:04.132  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 13:51:04.133  5589  5635 I io.jxcore.node.ConnectionHelper: start: OK
10-05 13:51:04.137  4554  4629 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:51:04.137  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:04.138  4554  4632 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 13:51:04.144  4554  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:51:04.144  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:04.145  4554  4632 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:51:04.145  4554  4632 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-05 13:51:04.155  4554  4629 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 13:51:04.155  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:04.161  4554  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 13:51:04.161  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:51:04.633  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-05 13:51:04.634  5589  5589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:51:04.634  5589  5589 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 13:51:07.125   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:51:09.137  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:51:09.137  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:09.138  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-05 13:51:09.138  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:09.138  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 13:51:09.138  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:51:09.138  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 13:51:09.138  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:51:09.138  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:51:09.138  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:51:09.139  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-05 13:51:09.139  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:51:09.140  5589  5635 D BluetoothAdapter: STATE_ON
10-05 13:51:09.141  4554  4570 D BtGatt.GattService: stopScan() - queue size =1
,10-05 13:51:09.142  4554  4786 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 13:51:09.143  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:51:09.143  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-05 13:51:09.143  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:51:09.143  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:51:09.144  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:51:09.144  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:51:09.144  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:51:09.144  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:51:09.145  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:51:09.146  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:51:09.146  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:51:09.146  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:51:09.146  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-05 13:51:09.147  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:51:09.148  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:51:09.149  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:09.149  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:51:09.149  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:51:09.149  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:09.149  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:09.149  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:09.149  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:09.149  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:09.149  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:51:09.150  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:51:09.150  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:51:09.150  4554  4554 D BtGatt.ScanManager: awakened up at time 229001
,10-05 13:51:09.156  4554  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:51:09.156  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:09.157  4554  4632 D BtGatt.ScanManager: stopping BLe Batch
,10-05 13:51:09.164  4554  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 13:51:09.164  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:09.164  4554  4632 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 13:51:09.183  4554  4629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-05 13:51:09.183  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:09.183  4554  4629 D BtGatt.GattService: current time is 229035347307
10-05 13:51:09.184  4554  4629 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -87, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -86, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -87, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-05 13:51:09.185  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-05 13:51:09.186  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-05 13:51:09.186  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-05 13:51:09.186  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-05 13:51:09.187  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-05 13:51:09.187  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-05 13:51:09.635   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:09.650  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:51:10.159   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:51:10.636   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:11.638   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:12.639   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:13.641   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:14.151  5589  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-05 13:51:14.157  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:51:14.168  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:51:14.168  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:14.168  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:14.168  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:14.168  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:14.168  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:14.168  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:14.168  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:14.172  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:14.173  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:51:14.173  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:51:14.173  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-05 13:51:14.173  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-05 13:51:14.173  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:51:14.173  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-05 13:51:14.179  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:14.182  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 13:51:14.182  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 13:51:14.185  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:14.191  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 13:51:14.193  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-05 13:51:14.193  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 13:51:14.200  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 13:51:14.200  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-05 13:51:14.200  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:51:14.200  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-05 13:51:14.200  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 13:51:14.202  5589  5635 D BluetoothAdapter: STATE_ON
10-05 13:51:14.205  4554  4570 D BtGatt.GattService: registerClient() - UUID=afe06e30-b0b2-413d-a35b-8f6982d4fc65
,10-05 13:51:14.206  4554  4629 D BtGatt.GattService: onClientRegistered() - UUID=afe06e30-b0b2-413d-a35b-8f6982d4fc65, clientIf=5
,10-05 13:51:14.206  5589  5599 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 13:51:14.207  4554  4786 D BtGatt.GattService: start scan with filters
,10-05 13:51:14.212  4554  4632 D BtGatt.ScanManager: handling starting scan
10-05 13:51:14.212  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:51:14.212  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-05 13:51:14.212  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:51:14.212  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:51:14.212  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:51:14.213  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:51:14.213  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:51:14.217  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:51:14.217  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-05 13:51:14.218  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:51:14.220  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-05 13:51:14.224  4554  4629 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-05 13:51:14.224  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:51:14.224  5589  5635 I io.jxcore.node.ConnectionHelper: start: OK
,10-05 13:51:14.224  4554  4632 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 13:51:14.228  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:51:14.228  5589  5635 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-05 13:51:14.228  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:51:14.228  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 13:51:14.228  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:14.229  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 13:51:14.229  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:14.229  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-05 13:51:14.229  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:51:14.229  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:51:14.229  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:51:14.229  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-05 13:51:14.229  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:51:14.230  5589  5635 D BluetoothAdapter: STATE_ON
10-05 13:51:14.231  4554  4570 D BtGatt.GattService: stopScan() - queue size =1
10-05 13:51:14.232  4554  4786 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 13:51:14.233  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:51:14.233  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-05 13:51:14.233  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:51:14.233  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-05 13:51:14.233  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:51:14.233  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:51:14.233  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:51:14.233  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-05 13:51:14.235  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-05 13:51:14.235  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:51:14.235  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:51:14.235  4554  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-05 13:51:14.236  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:51:14.236  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:14.236  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:51:14.236  4554  4632 D BtGatt.ScanManager: Starting BLE batch scan
,10-05 13:51:14.236  4554  4632 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 13:51:14.236  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:51:14.238  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:51:14.238  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-05 13:51:14.238  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:14.238  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:14.238  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:51:14.238  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 13:51:14.239  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:14.239  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:14.239  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:14.239  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:14.239  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:14.240  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:14.240  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:14.240  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:14.241  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:14.241  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:14.241  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:14.241  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:14.242  5589  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-05 13:51:14.245  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:51:14.250  4554  4629 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-05 13:51:14.250  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:14.251  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:51:14.251  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:14.251  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:14.251  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:14.251  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:14.251  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:14.251  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:14.251  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:51:14.253  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:14.254  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:51:14.254  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:51:14.254  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:51:14.254  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:51:14.254  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:51:14.254  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-05 13:51:14.257  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:14.258  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 13:51:14.258  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 13:51:14.259  4554  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-05 13:51:14.259  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:51:14.262  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-05 13:51:14.262  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:14.263  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 13:51:14.263  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 13:51:14.266  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 13:51:14.266  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:51:14.266  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:51:14.266  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:51:14.266  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 13:51:14.267  5589  5635 D BluetoothAdapter: STATE_ON
,10-05 13:51:14.268  4554  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:51:14.268  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:14.268  4554  4632 D BtGatt.ScanManager: stopping BLe Batch
,10-05 13:51:14.270  4554  4567 D BtGatt.GattService: registerClient() - UUID=d196664c-08bd-4266-a6e8-3d4c036e1c12
10-05 13:51:14.270  4554  4629 D BtGatt.GattService: onClientRegistered() - UUID=d196664c-08bd-4266-a6e8-3d4c036e1c12, clientIf=5
,10-05 13:51:14.271  5589  5599 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 13:51:14.271  4554  4570 D BtGatt.GattService: start scan with filters
,10-05 13:51:14.273  4554  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 13:51:14.273  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:14.273  4554  4632 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-05 13:51:14.274  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:51:14.274  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:51:14.274  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:51:14.274  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:51:14.274  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:51:14.274  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,10-05 13:51:14.274  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:51:14.276  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:51:14.276  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-05 13:51:14.276  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:51:14.278  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 13:51:14.278  4554  4629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 13:51:14.278  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:51:14.279  4554  4632 D BtGatt.ScanManager: handling starting scan
10-05 13:51:14.280  5589  5635 I io.jxcore.node.ConnectionHelper: start: OK
,10-05 13:51:14.284  4554  4629 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-05 13:51:14.284  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:14.284  4554  4632 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 13:51:14.289  4554  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-05 13:51:14.289  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:14.289  4554  4632 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:51:14.289  4554  4632 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-05 13:51:14.297  4554  4629 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-05 13:51:14.297  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:51:14.301  4554  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-05 13:51:14.301  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:51:14.641   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-05 13:51:14.777  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-05 13:51:14.778  5589  5589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:51:14.778  5589  5589 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 13:51:16.209   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:51:16.214   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-05 13:51:19.238   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-05 13:51:19.280  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:19.281  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:51:19.281  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-05 13:51:19.281  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:19.281  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-05 13:51:19.281  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:19.282  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 13:51:19.282  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-05 13:51:19.282  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:51:19.282  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-05 13:51:19.282  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 13:51:19.282  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:51:19.285  5589  5635 D BluetoothAdapter: STATE_ON
,10-05 13:51:19.286  4554  4786 D BtGatt.GattService: stopScan() - queue size =1
10-05 13:51:19.289  4554  4775 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 13:51:19.289  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-05 13:51:19.290  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 13:51:19.290  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-05 13:51:19.290  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:51:19.290  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:51:19.290  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-05 13:51:19.290  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:51:19.291  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-05 13:51:19.294  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:51:19.294  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:51:19.294  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:51:19.294  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:51:19.295  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:51:19.298  4554  4554 D BtGatt.ScanManager: awakened up at time 239149
10-05 13:51:19.299  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:51:19.302  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:51:19.303  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-05 13:51:19.303  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-05 13:51:19.307  4554  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-05 13:51:19.308  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:19.308  4554  4632 D BtGatt.ScanManager: stopping BLe Batch
,10-05 13:51:19.317  4554  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 13:51:19.317  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:19.318  4554  4632 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 13:51:19.337  4554  4629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-05 13:51:19.337  4554  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:51:19.337  4554  4629 D BtGatt.GattService: current time is 239189148406
10-05 13:51:19.338  4554  4629 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -88, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -90, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-05 13:51:19.338  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-05 13:51:19.340  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-05 13:51:19.340  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-05 13:51:19.340  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-05 13:51:19.340  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-05 13:51:19.340  4554  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-05 13:51:19.642   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:19.804  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:51:19.804  5589  5589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:19.804  5589  5589 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 13:51:20.643   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:21.644   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:22.263   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:51:22.271   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-05 13:51:22.645   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:23.646   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:24.303  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:51:24.304  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:24.304  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.304  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.304  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.304  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 13:51:24.305  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.305  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.305  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.305  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.305  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:51:24.306  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.307  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.307  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.312  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:24.312  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.312  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:24.312  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:24.313  5589  5635 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-05 13:51:24.315  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:24.315  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:24.316  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.316  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.316  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:51:24.316  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.316  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.316  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.317  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.317  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.317  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.317  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:51:24.317  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.317  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.317  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.320  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:24.320  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.321  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:24.321  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.325  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-05 13:51:24.325  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:24.325  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:51:24.326  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.326  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.326  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.326  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.326  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.326  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
,10-05 13:51:24.326  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.327  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.327  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.327  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.327  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.327  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.327  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.329  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:51:24.329  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.329  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.330  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.331  5589  5635 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-05 13:51:24.331  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:24.331  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:51:24.331  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.331  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.332  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.332  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.332  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.332  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
,10-05 13:51:24.332  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.332  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.332  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.332  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:51:24.332  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.332  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.333  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.334  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:24.335  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.335  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:24.335  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.336  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-05 13:51:24.336  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:51:24.336  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:24.337  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.337  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.337  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:51:24.337  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.337  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.337  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.337  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:24.337  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.337  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.337  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.338  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.338  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.338  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.340  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:24.340  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.340  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.340  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.341  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-05 13:51:24.341  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-05 13:51:24.342  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:51:24.343  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-05 13:51:24.343  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:51:24.343  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-05 13:51:24.343  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-05 13:51:24.343  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:51:24.343  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-05 13:51:24.343  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:51:24.344  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:24.344  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.345  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.345  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.345  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:24.346  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:51:24.346  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.346  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.347  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.348  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.348  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.348  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.348  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.349  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.353  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:51:24.353  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.353  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.353  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.354  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:51:24.354  5589  5635 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-05 13:51:24.354  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-05 13:51:24.365  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:51:24.366  5589  5635 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,10-05 13:51:24.366  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-05 13:51:24.366  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-05 13:51:24.366  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-05 13:51:24.366  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-05 13:51:24.366  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-05 13:51:24.366  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-05 13:51:24.366  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-05 13:51:24.366  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-05 13:51:24.367  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-05 13:51:24.367  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-05 13:51:24.367  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,10-05 13:51:24.368  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-05 13:51:24.368  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-05 13:51:24.368  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-05 13:51:24.368  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-05 13:51:24.369  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-05 13:51:24.369  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-05 13:51:24.369  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-05 13:51:24.369  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-05 13:51:24.370  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,10-05 13:51:24.370  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-05 13:51:24.371  5589  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 13:51:24.371  5589  5635 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-05 13:51:24.371  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:51:24.371  5589  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 13:51:24.371  5589  5635 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-05 13:51:24.371  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:51:24.371  5589  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-05 13:51:24.371  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-05 13:51:24.375  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-05 13:51:24.376  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-05 13:51:24.376  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-05 13:51:24.377  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-05 13:51:24.377  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,10-05 13:51:24.377  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-05 13:51:24.377  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-05 13:51:24.377  5589  5635 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-05 13:51:24.377  5589  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-05 13:51:24.377  5589  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-05 13:51:24.378  5589  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-05 13:51:24.378  5589  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-05 13:51:24.378  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:24.378  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:24.379  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.379  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.379  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.379  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.379  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.379  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-05 13:51:24.380  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.380  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.380  5589  5637 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-05 13:51:24.381  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.381  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.381  5589  5637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:51:24.381  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:51:24.381  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.381  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.381  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.381  4775  4775 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33115]" dev="sockfs" ino=33115 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 13:51:24.381  4775  4775 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33115]" dev="sockfs" ino=33115 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-05 13:51:24.383  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:24.383  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.383  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:24.383  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.384  5589  5635 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-05 13:51:24.384  5589  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-05 13:51:24.384  5589  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-05 13:51:24.384  5589  5637 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-05 13:51:24.384  5589  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-05 13:51:24.384  5589  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,10-05 13:51:24.384  5589  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-05 13:51:24.384  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:24.384  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:24.384  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.384  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.384  4554  4772 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
,10-05 13:51:24.385  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.385  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.385  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.385  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.385  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.385  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.385  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.385  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.385  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:24.385  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.385  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.386  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:24.386  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.386  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.387  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.387  5589  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-05 13:51:24.388  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:24.388  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:24.388  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.388  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.388  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.388  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.388  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.388  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.388  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:24.388  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.388  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.388  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.389  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.389  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.389  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.390  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:24.390  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.390  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.390  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.391  5589  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,10-05 13:51:24.391  5589  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-05 13:51:24.391  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 13:51:24.391  5589  5635 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-05 13:51:24.391  5589  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-05 13:51:24.391  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-05 13:51:24.391  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-05 13:51:24.391  5589  5635 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-05 13:51:24.391  5589  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-05 13:51:24.391  5589  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-05 13:51:24.391  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 13:51:24.391  5589  5635 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-05 13:51:24.392  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:24.392  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:51:24.392  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:24.392  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.392  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.392  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.392  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:24.392  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.393  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:24.393  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.393  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.393  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.393  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.393  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.393  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.395  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:51:24.395  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:24.395  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.395  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.396  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:24.396  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.396  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:24.396  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:51:24.396  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:24.396  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:24.396  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:24.396  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:24.396  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:24.396  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:24.647   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-05 13:51:28.321   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:51:29.397  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:29.397  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:29.397  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:29.398  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.398  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.398  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:51:29.398  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:29.399  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:29.399  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:29.399  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:29.399  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:51:29.399  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.400  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.400  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:29.400  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
,10-05 13:51:29.400  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.400  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:29.400  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:29.401  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:51:29.401  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.401  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.401  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:29.404  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:29.404  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:29.404  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.405  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:29.408  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-05 13:51:29.408  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:51:29.410  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-05 13:51:29.412  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-05 13:51:29.412  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-05 13:51:29.413  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-05 13:51:29.413  5589  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-05 13:51:29.413  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-05 13:51:29.413  5589  5589 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-05 13:51:29.413  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-05 13:51:29.414  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:29.415  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-05 13:51:29.415  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-05 13:51:29.415  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-05 13:51:29.415  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.415  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-05 13:51:29.415  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-05 13:51:29.416  5589  5639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:51:29.416  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
,10-05 13:51:29.416  5589  5589 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-05 13:51:29.416  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.416  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:51:29.416  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:51:29.416  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:51:29.416  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.416  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.419  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:51:29.419  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:29.419  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:51:29.419  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:29.419  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:51:29.419  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:29.419  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-05 13:51:29.419  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:51:29.419  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:29.419  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.420  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.420  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-05 13:51:29.420  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
,10-05 13:51:29.420  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.420  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:29.420  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:29.420  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.420  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.420  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.420  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:29.421  5589  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-05 13:51:29.422  5589  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-05 13:51:29.422  5589  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-05 13:51:29.418  4567  4567 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31624]" dev="sockfs" ino=31624 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 13:51:29.418  4567  4567 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31624]" dev="sockfs" ino=31624 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-05 13:51:29.422  5589  5589 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-05 13:51:29.422  5589  5589 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:29.423  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:29.423  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:29.424  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.424  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:29.426  5589  5635 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,10-05 13:51:29.427  5589  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-05 13:51:29.427  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
10-05 13:51:29.427  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:51:29.427  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-05 13:51:29.428  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:29.428  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:29.428  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:29.428  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:29.428  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.428  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.428  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:29.429  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:29.429  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.429  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
,10-05 13:51:29.429  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:29.429  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.429  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.429  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.429  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:29.432  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:51:29.432  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:29.432  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.433  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:29.439  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:29.439  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:29.439  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:29.439  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:29.439  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.439  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:29.439  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:29.439  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
10-05 13:51:29.439  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.440  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:29.440  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:29.440  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.440  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.440  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.440  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.441  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:51:29.441  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:51:29.441  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.441  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:29.442  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:51:29.442  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:51:29.443  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:51:29.443  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:51:29.443  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.443  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.443  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:51:29.443  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@833957f not in the list
,10-05 13:51:29.443  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.443  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:29.443  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:29.443  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.443  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:29.443  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:29.443  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:29.445  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:51:29.445  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:51:29.445  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:29.446  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4bd894c not in the list
10-05 13:51:29.447  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-05 13:51:29.447  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 13:51:29.447  5589  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-05 13:51:29.447  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-05 13:51:29.447  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-05 13:51:29.447  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-05 13:51:29.450  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-05 13:51:29.450  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-05 13:51:29.452  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-05 13:51:29.452  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-05 13:51:29.452  5589  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,10-05 13:51:29.452  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-05 13:51:29.452  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-05 13:51:29.452  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-05 13:51:29.453  5589  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-05 13:51:29.453  5589  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-05 13:51:29.454  5589  5635 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-05 13:51:29.454  5589  5635 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-05 13:51:29.454  5589  5635 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-05 13:51:29.454  5589  5635 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-05 13:51:29.456  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:51:29.456  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d49834e added. We now have 3 listener(s)
10-05 13:51:29.456  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:51:29.458  5589  5635 D BluetoothAdapter: enable(): BT is already enabled..!
10-05 13:51:29.458   931  3105 D WifiService: setWifiEnabled: true pid=5589, uid=10077
10-05 13:51:29.459   931  3105 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:51:29.511  4554  4731 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-05 13:51:29.511  4554  4731 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-05 13:51:29.920  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:51:34.377   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-05 13:51:34.464  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-05 13:51:34.464  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa2dc6f added. We now have 4 listener(s)
10-05 13:51:34.464  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:51:34.477  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:34.478  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa2dc6f removed from the list
10-05 13:51:34.478  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:34.478  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:34.478  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:34.480  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:51:34.480  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35bdd7c added. We now have 4 listener(s)
10-05 13:51:34.480  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:51:34.482  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:34.482  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35bdd7c removed from the list
,10-05 13:51:34.482  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:34.482  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:34.482  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:34.484  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:51:34.484  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5814605 added. We now have 4 listener(s)
,10-05 13:51:34.484  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:51:34.487   931   942 D WifiService: setWifiEnabled: false pid=5589, uid=10077
10-05 13:51:34.487   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:51:34.495   931  2925 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-05 13:51:34.495   931  2925 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-05 13:51:34.496   931  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:51:34.496   931  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-05 13:51:34.498  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:51:34.500  4554  4624 D BluetoothAdapterState: Current state: ON, message: 23
,10-05 13:51:34.500  4554  4624 D BluetoothAdapterProperties: Setting state to 13
10-05 13:51:34.500  4554  4624 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-05 13:51:34.502  4554  4624 D BluetoothAdapterProperties: onBluetoothDisable()
10-05 13:51:34.503  4554  4624 I BluetoothAdapterState: Entering PendingCommandState
10-05 13:51:34.505  4554  4629 D BluetoothAdapterProperties: Scan Mode:20
10-05 13:51:34.505  4554  4624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-05 13:51:34.505  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.505  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:51:34.505  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.505  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.505  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.505  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.505  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:34.505  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:34.505  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:51:34.506  4554  4554 D BluetoothMapService: onReceive
10-05 13:51:34.506  4554  4554 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 13:51:34.507  4554  4554 D BluetoothMapService: STATE_TURNING_OFF
10-05 13:51:34.507  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.507  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:34.507  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:51:34.509  4554  4554 D BluetoothMapService: MAP Service closeService in
10-05 13:51:34.509  4554  4554 D BluetoothMapMasInstance0: MAP Service shutdown
10-05 13:51:34.509  4554  4554 D ObexServerSockets0: shutdown(block = true)
10-05 13:51:34.510  4554  4554 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-05 13:51:34.510  4554  4788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-05 13:51:34.510  4554  4554 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 13:51:34.510  4554  4789 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-05 13:51:34.510  4554  4772 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-05 13:51:34.513  4554  4554 I BtOppRfcommListener: stopping Accept Thread
10-05 13:51:34.514  4554  5264 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-05 13:51:34.514  4554  5264 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-05 13:51:34.515  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:34.515   931  5340 D DhcpClient: Clearing IP address
10-05 13:51:34.515   509   924 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:51:34.519  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.520   509   924 D CommandListener: Setting iface cfg
10-05 13:51:34.522   931  5341 D DhcpClient: Receive thread stopped
10-05 13:51:34.524  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.524  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.524  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.524  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.524  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.524  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.524  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:34.524  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:34.524  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:51:34.525  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.525  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:34.528  3522  5395 V NativeCrypto: Read error: ssl=0x7f936bde80: I/O error during system call, Connection timed out
,10-05 13:51:34.530  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.530  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.530  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.530  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.530  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.530  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.530  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:34.530  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:34.530  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:34.531  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.531  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:51:34.532  3522  5395 V NativeCrypto: SSL shutdown failed: ssl=0x7f936bde80: I/O error during system call, Broken pipe
,10-05 13:51:34.535   931  3105 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,10-05 13:51:34.536   931  5338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-05 13:51:34.537  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:34.538   931  5338 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-05 13:51:34.538   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-05 13:51:34.539   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-05 13:51:34.540  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.540   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-05 13:51:34.541  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.541  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.541  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.541  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.541  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.541  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.541  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:34.541  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:51:34.542  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.543  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:34.545   931   944 I ActivityManager: Start proc 5643:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-05 13:51:34.546  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.546  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.546  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.546  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.546  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.546  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.546  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.546  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:34.546  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:34.546  4554  4554 D HeadsetService: Received stop request...Stopping profile...
10-05 13:51:34.547  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.547  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:51:34.549   535   535 E Parcel  : Reading a NULL string not supported here.
10-05 13:51:34.551   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-05 13:51:34.551  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.551   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-05 13:51:34.551  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.551  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.551  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.551  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.551  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.551  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.551  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:34.551  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:34.552  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.552  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:51:34.556   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:51:34.556  3725  3981 D BluetoothHeadset: Proxy object disconnected
,10-05 13:51:34.556   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:51:34.556   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:51:34.556  3092  3106 D BluetoothHeadset: Proxy object disconnected
,10-05 13:51:34.557   931  2928 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-05 13:51:34.559  3680  3844 W QCNEJ   : |CORE| network lost: 100
10-05 13:51:34.559  3680  3844 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-05 13:51:34.561  4554  4554 D A2dpService: Received stop request...Stopping profile...
,10-05 13:51:34.561  4554  4778 D A2dpStateMachine: Exit Disconnected: -1
10-05 13:51:34.562   931   931 D RttService: SCAN_AVAILABLE : 1
10-05 13:51:34.562   931  3034 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-05 13:51:34.562   931   931 D BluetoothA2dp: Proxy object disconnected
10-05 13:51:34.563  4554  4554 D HidService: Received stop request...Stopping profile...
10-05 13:51:34.563  4554  4554 D HidService: Stopping Bluetooth HidService
10-05 13:51:34.565  4554  4554 D HealthService: Received stop request...Stopping profile...
,10-05 13:51:34.566  4554  4554 D PanService: Received stop request...Stopping profile...
,10-05 13:51:34.568  4554  4554 D BluetoothMapService: Received stop request...Stopping profile...
10-05 13:51:34.568  4554  4554 D BluetoothMapService: stop()
10-05 13:51:34.570  4554  4554 D BluetoothMapAppObserver: deinitObservers()
10-05 13:51:34.570  4554  4554 D BluetoothMapAppObserver: removeReceiver()
10-05 13:51:34.572  4554  4554 V BluetoothAdapterState: isTurningOff()=true
,10-05 13:51:34.572  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:34.572  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:34.572  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:34.572  3092  3092 D HeadsetProfile: Bluetooth service disconnected
,10-05 13:51:34.573  4554  4554 D SapService: Received stop request...Stopping profile...
10-05 13:51:34.573  4554  4554 V SapService: stop()
10-05 13:51:34.573   931  2925 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-05 13:51:34.573  3092  3092 D BluetoothA2dp: Proxy object disconnected
10-05 13:51:34.574  3092  3092 D BluetoothInputDevice: Proxy object disconnected
10-05 13:51:34.574  3092  3092 D HidProfile: Bluetooth service disconnected
10-05 13:51:34.574  3092  3092 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 13:51:34.574  3092  3092 D PanProfile: Bluetooth service disconnected
,10-05 13:51:34.574  3092  3092 D BluetoothMap: Proxy object disconnected
10-05 13:51:34.574  3092  3092 D MapProfile: Bluetooth service disconnected
10-05 13:51:34.579  5643  5643 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-05 13:51:34.580  4554  4554 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-05 13:51:34.580  4554  4554 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-05 13:51:34.580  4554  4629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-05 13:51:34.580  4554  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:34.580  4554  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:34.580  4554  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:34.580  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:34.580  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:34.580  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:34.580  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:51:34.581   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:51:34.581   931  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:51:34.582  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:34.582  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:34.582  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:34.582  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:34.582  4554  4629 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-05 13:51:34.582  4554  4629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-05 13:51:34.582  4554  4554 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,10-05 13:51:34.582  4554  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-05 13:51:34.582  4554  4554 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-05 13:51:34.582  4554  4629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 13:51:34.582  4554  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:34.582  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:34.583  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:34.583  4554  4731 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 13:51:34.583  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:34.583  4554  4731 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 13:51:34.583  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:34.583  4554  4731 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 13:51:34.583  4554  4731 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 13:51:34.583  4554  4554 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-05 13:51:34.583  4554  4629 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-05 13:51:34.584  4554  4554 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-05 13:51:34.584  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:34.584  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:34.584  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:34.584  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:34.585  4554  4554 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-05 13:51:34.585  4554  4554 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-05 13:51:34.585  4554  4554 D BluetoothMapService: MAP Service closeService in
10-05 13:51:34.586  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:34.586  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:34.586  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:34.586  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:34.586  4554  4554 D BluetoothMapService: cleanup()
10-05 13:51:34.586  4554  4554 D BluetoothMapService: MAP Service closeService in
10-05 13:51:34.586  4554  4554 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:34.586  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:34.586  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:34.586  4554  4554 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:34.586  4554  4624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-05 13:51:34.587  4554  4624 D BluetoothAdapterProperties: Setting state to 15
10-05 13:51:34.587  4554  4624 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-05 13:51:34.587  4554  4624 I BluetoothAdapterState: Entering BleOnState
,10-05 13:51:34.588  3092  3106 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-05 13:51:34.588   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:51:34.588   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:34.588   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:34.589  3092  3104 D BluetoothMap: onBluetoothStateChange: up=false
10-05 13:51:34.589  3092  3931 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-05 13:51:34.590  3092  3106 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:34.590  3725  3740 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:34.591  3092  3104 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 13:51:34.591   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:34.592  3092  3931 D BluetoothPan: onBluetoothStateChange on: false
,10-05 13:51:34.593  4554  4624 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-05 13:51:34.593  4554  4624 D BluetoothAdapterProperties: Setting state to 16
10-05 13:51:34.593  4554  4624 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-05 13:51:34.594  4554  4624 D BluetoothAdapterProperties: onBleDisable
10-05 13:51:34.594  4554  4624 I BluetoothAdapterState: Entering PendingCommandState
10-05 13:51:34.595  4554  4626 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-05 13:51:34.595  4554  4629 D BluetoothAdapterProperties: Scan Mode:20
10-05 13:51:34.596  4554  4731 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-05 13:51:34.596  4554  4731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:34.597  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.597  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.597  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.597  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.597  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.597  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.597  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.597  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:34.597  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:51:34.599  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.599  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.599  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.599  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.599  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.599  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.599  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.599  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:34.599  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:34.601  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.601  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.601  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.601  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.601  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:34.601  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.601  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.601  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:34.601  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:34.602   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-05 13:51:34.602   509   924 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:51:34.602   509   924 D TetherController: Setting IP forward enable = 0
,10-05 13:51:34.603   931  2928 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-05 13:51:34.603   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 13:51:34.605  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.605   931  2925 D DhcpClient: doQuit
10-05 13:51:34.605  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 13:51:34.605   931  2925 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-05 13:51:34.606  3404  3404 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-05 13:51:34.607   931   948 D Tethering: MasterInitialState.processMessage what=3
,10-05 13:51:34.609   931  5340 D DhcpClient: onQuitting
,10-05 13:51:34.608  5250  5250 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@35fac9e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-05 13:51:34.612  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.613  5003  5025 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 13:51:34.614  5003  5025 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 13:51:34.614  5003  5025 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-05 13:51:34.614  5003  5025 E SarControlService: no key has been found,reset the power
10-05 13:51:34.614  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:51:34.614  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.614  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.614  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.614  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:34.614  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.614  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.614  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:34.614  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:34.614  5003  5040 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 13:51:34.615  5003  5040 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 13:51:34.615  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.615  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:34.616  5003  5040 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 13:51:34.616  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 13:51:34.617  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:51:34.617  5028  5028 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-05 13:51:34.617  5003  5040 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-05 13:51:34.618  5003  5040 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 13:51:34.618  5003  5040 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 13:51:34.619  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:51:34.619  5028  5028 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 13:51:34.620  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.620  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.620  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.620  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.620  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:34.620  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.620  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.620  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:34.620  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:51:34.620  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.621  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:34.622  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.622  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:34.622  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:34.622  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:34.622  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:34.622  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:34.622  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:34.622  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:34.622  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:34.623  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:34.623  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:51:34.623  3404  3404 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-05 13:51:34.624  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.624  5028  5042 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@441dcf4 HexData = [00000000ea03000000000000ffffffff]
10-05 13:51:34.625  5028  5042 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:51:34.625  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.625  5028  5042 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,10-05 13:51:34.625  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:51:34.625  5003  5013 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 13:51:34.625  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.626  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.627  3404  3404 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-05 13:51:34.629  5028  5042 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@441dcf4 HexData = [00000000eb03000000000000ffffffff]
10-05 13:51:34.629  5028  5042 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-05 13:51:34.629  5028  5042 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-05 13:51:34.629   509   917 W SocketClient: write error (Broken pipe)
10-05 13:51:34.629   509   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-05 13:51:34.629   509   917 W SocketListener: Error sending broadcast (Broken pipe)
10-05 13:51:34.630  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:51:34.630  5003  5014 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-05 13:51:34.631   931  3809 I ActivityManager: Start proc 5668:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-05 13:51:34.638   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@98251a3:true
,10-05 13:51:34.648   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:34.658  5643  5643 D LocalBluetoothProfileManager: Adding local MAP profile
,10-05 13:51:34.661  5643  5643 D BluetoothMap: Create BluetoothMap proxy object
,10-05 13:51:34.663   509   924 E Netd    : netlink response contains error (No such file or directory)
10-05 13:51:34.663   931  2928 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-05 13:51:34.664   509   924 D TetherController: Setting IP forward enable = 0
,10-05 13:51:34.667  3404  3404 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-05 13:51:34.672  5643  5643 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-05 13:51:34.675  3404  3404 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-05 13:51:34.686  5668  5668 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-05 13:51:34.690  5643  5643 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:51:34.694   931  5350 I ActivityManager: Killing 4943:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-05 13:51:34.780  4978  4978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 13:51:34.780   931  2925 D wifi    : In wifi stop Hal
10-05 13:51:34.780   931  2925 D wifi    : halHandle = 0x7f81be2680, mVM = 0x7f9e20d140, mCls = 0x100a02
10-05 13:51:34.780   931  3402 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-05 13:51:34.780   931  3402 D WifiHAL : Got a signal to exit!!!
10-05 13:51:34.780   931  3402 I WifiHAL : Exit wifi_event_loop
10-05 13:51:34.781   931  2925 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-05 13:51:34.781   931  2925 E WifiHAL : Event processing terminated
10-05 13:51:34.781   931  2925 D wifi    : In wifi cleaned up handler
10-05 13:51:34.782   931  2925 I WifiHAL : Internal cleanup completed
10-05 13:51:34.783  4068  4175 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:51:34.783  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.784  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:34.785  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:34.803   931  3402 D wifi    : set interface wlan0 flags (DOWN)
,10-05 13:51:34.804   931  2925 D WifiNative-HAL: HAL event thread stopped successfully
,10-05 13:51:34.806  4554  4629 I bt_hci  : shut_down
,10-05 13:51:34.811  4554  4633 D bt_hwcfg: hw_epilog_process
,10-05 13:51:34.811  4554  4633 I bt_vendor: low_power_mode_cb
,10-05 13:51:34.814  4554  4633 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-05 13:51:34.814  4554  4633 I bt_vendor: epilog_cb
,10-05 13:51:34.814  4554  4633 I bt_hci  : epilog_finished_callback
10-05 13:51:34.816  4554  4629 I bt_hci_h4: hal_close
10-05 13:51:34.816  4554  4629 I bt_userial_vendor: device fd = 54 close
,10-05 13:51:34.883  5668  5668 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-05 13:51:34.883  5668  5668 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:51:34.883  5668  5668 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:51:34.883  5668  5668 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.e.b(PG:170)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:51:34.883  5668  5668 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.k.d(PG:583)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.e.b(PG:170)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:51:34.883  5668  5668 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:51:34.883  5668  5668 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.io.File.exists(File.java:361)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:51:34.883  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:51:34.884  5668  5668 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-05 13:51:34.884  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-05 13:51:34.884  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-05 13:51:34.888  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 13:51:34.892  5643  5643 D DockEventReceiver: finishStartingService: stopping service
10-05 13:51:34.894  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 13:51:34.895   931  3154 I ActivityManager: Killing 5369:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-05 13:51:34.920  4554  4626 D bt_stack_manager: event_shut_down_stack finished.
10-05 13:51:34.920  4554  4624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-05 13:51:34.924  4554  4624 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-05 13:51:34.924  4554  4554 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 13:51:34.925  4554  4554 D BtGatt.GattService: Received stop request...Stopping profile...
10-05 13:51:34.925  4554  4554 D BtGatt.GattService: stop()
10-05 13:51:34.925  4554  4554 D BtGatt.AdvertiseManager: advertise clients cleared
10-05 13:51:34.927  4554  4554 V BluetoothAdapterState: isTurningOff()=false
10-05 13:51:34.927  4554  4554 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:34.927  4554  4554 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:34.927  4554  4554 V BluetoothAdapterState: isBleTurningOff()=true
10-05 13:51:34.927  4554  4624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-05 13:51:34.927  4554  4624 D BluetoothAdapterProperties: Setting state to 10
10-05 13:51:34.927  4554  4624 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-05 13:51:34.928  4554  4624 I BluetoothAdapterState: Entering OffState
10-05 13:51:34.928   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-05 13:51:34.934  4554  4554 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-05 13:51:34.934  4554  4554 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-05 13:51:34.934  4554  4554 I BluetoothServiceJni: cleanupNative: return from cleanup
10-05 13:51:34.935  4554  4626 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-05 13:51:34.941  4554  4554 I art     : System.exit called, status: 0
10-05 13:51:34.941  4554  4554 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-05 13:51:34.982  3900  3900 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 13:51:34.984  3900  3900 D SystemUpdateService: onCreate
,10-05 13:51:34.987  3900  3900 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 13:51:34.990   931   942 I ActivityManager: Process com.android.bluetooth (pid 4554) has died
,10-05 13:51:34.997  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-05 13:51:35.001  3900  5366 I iu.UploadsManager: num queued entries: 0
,10-05 13:51:35.003  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-05 13:51:35.004  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 13:51:35.005  3900  5366 I iu.UploadsManager: num updated entries: 0
10-05 13:51:35.006   931   948 D Tethering: InitialState.processMessage what=4
10-05 13:51:35.006  3900  5366 I iu.SyncManager: NEXT; no task
,10-05 13:51:35.007  3900  5708 I SystemUpdateService: active receiver: enabled
,10-05 13:51:35.014  3900  5708 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 13:51:35.018   931   942 I ActivityManager: Start proc 5710:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-05 13:51:35.019   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-05 13:51:35.023  3900  5708 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-05 13:51:35.023  3900  5708 I SystemUpdateService: now status is 0 (complete)
10-05 13:51:35.023  3900  5708 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 13:51:35.023  3900  5708 I SystemUpdateService: file has been verified
10-05 13:51:35.023  3900  5708 I SystemUpdateService: OTA package size = 21989297
,10-05 13:51:35.054  3900  5708 I SystemUpdateService: showing system update notification
,10-05 13:51:35.059  5710  5710 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-05 13:51:35.061  5710  5710 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 13:51:35.079  5710  5710 D SprintDMHelper: simOperator: 
10-05 13:51:35.079  5710  5710 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 13:51:35.095  4978  5722 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-05 13:51:35.102   931  3105 I ActivityManager: Start proc 5723:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-05 13:51:35.113  3900  3900 D SystemUpdateService: onDestroy
,10-05 13:51:35.115   931   941 I ActivityManager: Killing 5250:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-05 13:51:35.166  5723  5723 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-05 13:51:35.179   931   942 I ActivityManager: Killing 4639:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-05 13:51:35.265  5668  5696 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-05 13:51:35.277   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@55ac994:true
,10-05 13:51:35.649   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:36.650   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:37.651   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:38.652   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:39.511   931  3154 D WifiService: setWifiEnabled: true pid=5589, uid=10077
,10-05 13:51:39.511   931  3154 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:51:39.519   509   924 D SoftapController: Softap fwReload - Ok
,10-05 13:51:39.525   509   924 D CommandListener: Setting iface cfg
,10-05 13:51:39.525   509   924 D CommandListener: Trying to bring down wlan0
,10-05 13:51:39.527   509   924 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:51:39.535   931  2925 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 13:51:39.653   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-05 13:51:40.108   931  2925 D wifi    : set interface wlan0 flags (UP)
,10-05 13:51:40.111   931  2925 I WifiHAL : Initializing wifi
10-05 13:51:40.111   931  2925 I WifiHAL : Creating socket
10-05 13:51:40.112   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-05 13:51:40.116   931  2925 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-05 13:51:40.116   931  2925 D wifi    : Did set static halHandle = 0x7f81be2680
10-05 13:51:40.116   931  2925 D wifi    : halHandle = 0x7f81be2680, mVM = 0x7f9e20d140, mCls = 0x18c2
10-05 13:51:40.116   931  2925 D wifi    : array field set
10-05 13:51:40.116   931  2925 I WifiNative-HAL: interface[0] = wlan0
10-05 13:51:40.117   931  5742 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547637569152
10-05 13:51:40.117   931  5742 D wifi    : waitForHalEvents called, vm = 0x7f9e20d140, obj = 0x18c2, env = 0x7f86a42780
,10-05 13:51:40.189  5743  5743 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-05 13:51:40.202  5743  5743 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 13:51:40.208  5743  5743 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 13:51:40.208  5743  5743 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-05 13:51:40.220   931  2925 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-05 13:51:40.222  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:40.222  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:40.222  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:40.222  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:40.222  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:40.222  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:40.222  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:40.222  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:40.222  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:51:40.222  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:40.222  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:40.223  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:40.224  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:40.224  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:40.224  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:40.224  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:40.224  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:40.224  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:51:40.228   931  2925 D WifiConfigStore: Loading config and enabling all networks 
,10-05 13:51:40.229  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:40.230  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:40.231  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:40.239   931  2925 D WifiConfigStore: loaded 0 passpoint configs
,10-05 13:51:40.239   931  2925 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-05 13:51:40.240   931  2925 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-05 13:51:40.241   931  2925 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-05 13:51:40.242   931  2925 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-05 13:51:40.242   931  2925 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-05 13:51:40.242   931  2925 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-05 13:51:40.242   931  2925 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-05 13:51:40.246   931  2925 D WifiNative-HAL: Setting external_sim to 1
,10-05 13:51:40.246  4978  4978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:51:40.246   931  2925 D wifi    : setting dfs flag to true, 0x7f858ff020
10-05 13:51:40.247   931  2925 D WifiStateMachine: Setting OUI to DA-A1-19
10-05 13:51:40.247   931  2925 D wifi    : setting scan oui 0x7f858ff020
10-05 13:51:40.247   931  2925 D WifiHAL : Sending mac address OUI
,10-05 13:51:40.252   931  2925 E native  : do suspend false
,10-05 13:51:40.258   931  2925 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-05 13:51:40.258   931   931 D RttService: SCAN_AVAILABLE : 3
10-05 13:51:40.258   509   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-05 13:51:40.259   931  3034 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-05 13:51:40.259   509   924 D CommandListener: Setting iface cfg
,10-05 13:51:40.263   931  2909 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-05 13:51:40.263   931  2909 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-05 13:51:40.271   931  2909 D WifiNative-HAL: p2pGetDeviceAddress
,10-05 13:51:40.276   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=260127 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-05 13:51:40.276   931  2909 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-05 13:51:42.486   931  2925 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 14, 15 -> obsolete
,10-05 13:51:43.444  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:51:43.452  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:51:43.458  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:51:43.463  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:51:43.487   931  2925 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-05 13:51:43.488   931  2925 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-05 13:51:43.488   931  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:51:43.500   931  2925 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-05 13:51:43.530   931  2925 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-05 13:51:43.533  5743  5743 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-05 13:51:43.955  5743  5743 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-05 13:51:43.988  5743  5743 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-05 13:51:43.990  5743  5743 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-05 13:51:44.000   931  2925 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 13:51:44.000   931  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-05 13:51:44.000   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-05 13:51:44.018   931  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:51:44.031   509   924 D CommandListener: Setting iface cfg
,10-05 13:51:44.038   931  2925 D WifiStateMachine: Start Dhcp Watchdog 2
,10-05 13:51:44.045   931  5749 D DhcpClient: Receive thread started
,10-05 13:51:44.050   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-05 13:51:44.050   931  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-05 13:51:44.050   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-05 13:51:44.131   931  2925 E native  : do suspend false
,10-05 13:51:44.149   931  5748 D DhcpClient: Broadcasting DHCPDISCOVER
,10-05 13:51:44.162   931  5749 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172578, domain null
,10-05 13:51:44.162   931  5748 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172578 seconds
,10-05 13:51:44.165   931  5748 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-05 13:51:44.183   931  5749 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-05 13:51:44.183   931  5748 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-05 13:51:44.187   509   924 D CommandListener: Setting iface cfg
,10-05 13:51:44.194   931  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-05 13:51:44.199   931  5748 D DhcpClient: Scheduling renewal in 86399s
,10-05 13:51:44.208   931  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-05 13:51:44.209   931  2925 D WifiConfigStore: No blacklist allowed without epno enabled
,10-05 13:51:44.210   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-05 13:51:44.212   931  2928 D ConnectivityService: Adding iface wlan0 to network 101
,10-05 13:51:44.221   931  2925 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-05 13:51:44.255   931  2928 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-05 13:51:44.256   931  2928 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-05 13:51:44.259   931  2928 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-05 13:51:44.261   931  2928 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-05 13:51:44.267   931  2928 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-05 13:51:44.273   931  2928 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-05 13:51:44.276   931  2928 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-05 13:51:44.276   931  2928 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-05 13:51:44.276   931  2928 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-05 13:51:44.277   931  2925 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-05 13:51:44.277   931  2928 D ConnectivityService:    accepting network in place of null
10-05 13:51:44.277   931  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:51:44.277   931  2928 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 13:51:44.289   931  5747 D NetlinkSocketObserver: NeighborEvent{elapsedMs=264141, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-05 13:51:44.298   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:51:44.318   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:51:44.321   931  2928 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-05 13:51:44.321  3680  3844 W QCNEJ   : |CORE| network available: 101
,10-05 13:51:44.321   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 13:51:44.322   931  2928 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-05 13:51:44.324   931   948 D Tethering: MasterInitialState.processMessage what=3
10-05 13:51:44.325  3680  3844 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-05 13:51:44.327  3680  3844 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-05 13:51:44.327  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.327  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:44.327  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:44.327  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:44.327  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:44.327  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:44.327  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:44.327  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:44.327  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:44.327  3680  3844 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-05 13:51:44.327  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.327  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:51:44.330  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:51:44.330  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:44.330  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:44.330  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:44.330  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:44.330  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:44.330  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:44.330  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:44.330  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:44.330  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.330  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:51:44.334  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:51:44.334  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:44.334  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:44.334  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:44.334  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:51:44.334  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:44.334  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:51:44.334  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:51:44.334  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:51:44.335  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.335  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:51:44.336  5003  5025 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 13:51:44.336  5003  5025 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 13:51:44.336  5003  5025 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,10-05 13:51:44.337  5003  5025 E SarControlService: no key has been found,reset the power
10-05 13:51:44.337  5003  5040 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 13:51:44.337  5003  5040 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 13:51:44.337  5003  5040 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 13:51:44.337  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:51:44.337  5028  5028 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 13:51:44.339  5003  5040 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 13:51:44.339  5003  5040 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-05 13:51:44.339  5003  5040 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 13:51:44.340  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:51:44.340  5028  5028 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 13:51:44.342  3900  3900 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-05 13:51:44.345  5028  5042 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@441dcf4 HexData = [00000000ec03000000000000ffffffff]
10-05 13:51:44.345  5028  5042 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:51:44.345  5028  5042 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-05 13:51:44.345  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:51:44.345  5003  5013 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-05 13:51:44.345  5028  5042 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@441dcf4 HexData = [00000000ed03000000000000ffffffff]
10-05 13:51:44.345  5028  5042 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:51:44.346  5028  5042 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-05 13:51:44.346  3900  3900 D SystemUpdateService: onCreate
10-05 13:51:44.347  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:51:44.347  5003  5014 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-05 13:51:44.351  3900  3900 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 13:51:44.359  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-05 13:51:44.363   931  5746 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:816::200e
,10-05 13:51:44.367  3900  5366 I iu.UploadsManager: num queued entries: 0
10-05 13:51:44.368  3900  5366 I iu.UploadsManager: num updated entries: 0
,10-05 13:51:44.369  3900  5759 I SystemUpdateService: active receiver: enabled
,10-05 13:51:44.371  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 13:51:44.372  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 13:51:44.374  5710  5710 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 13:51:44.379  5710  5710 D SprintDMHelper: simOperator: 
10-05 13:51:44.379  5710  5710 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 13:51:44.391  3900  5366 I iu.SyncManager: NEXT; no task
,10-05 13:51:44.397  3900  5759 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 13:51:44.414  3900  5759 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-05 13:51:44.414  3900  5759 I SystemUpdateService: now status is 0 (complete)
10-05 13:51:44.414  3900  5759 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 13:51:44.414  3900  5759 I SystemUpdateService: file has been verified
10-05 13:51:44.414  3900  5759 I SystemUpdateService: OTA package size = 21989297
,10-05 13:51:44.420  3900  5759 I SystemUpdateService: showing system update notification
,10-05 13:51:44.428  3900  3900 D SystemUpdateService: onDestroy
,10-05 13:51:44.436   931  5746 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 05 Oct 2016 17:51:44 GMT], X-Android-Received-Millis=[1475689904435], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475689904394]}
,10-05 13:51:44.436   931  2928 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-05 13:51:44.437   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-05 13:51:44.437   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-05 13:51:44.438   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-05 13:51:44.503  4978  5763 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-05 13:51:44.515   931   942 D WifiService: setWifiEnabled: false pid=5589, uid=10077
10-05 13:51:44.515   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:51:44.517   931  2925 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-05 13:51:44.517   931  2925 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-05 13:51:44.517   931  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:51:44.517   931  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:51:44.524   931  5748 D DhcpClient: Clearing IP address
,10-05 13:51:44.524   509   924 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:51:44.533  3522  5769 V NativeCrypto: Read error: ssl=0x7f9ca18e00: I/O error during system call, Connection timed out
,10-05 13:51:44.534  3522  5769 V NativeCrypto: SSL shutdown failed: ssl=0x7f9ca18e00: I/O error during system call, Broken pipe
,10-05 13:51:44.534   509   924 D CommandListener: Setting iface cfg
10-05 13:51:44.536   931  5749 D DhcpClient: Receive thread stopped
,10-05 13:51:44.540   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-05 13:51:44.540   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-05 13:51:44.544   535   535 E Parcel  : Reading a NULL string not supported here.
,10-05 13:51:44.546   931  2928 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-05 13:51:44.549  3680  3844 W QCNEJ   : |CORE| network lost: 101
,10-05 13:51:44.550  3680  3844 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-05 13:51:44.550   931   931 D RttService: SCAN_AVAILABLE : 1
10-05 13:51:44.551   931  3034 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-05 13:51:44.554   931  2925 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-05 13:51:44.557   931  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-05 13:51:44.571   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:51:44.593   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:51:44.594   931  2928 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-05 13:51:44.594   509   924 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:51:44.594   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-05 13:51:44.596   931  2925 D DhcpClient: doQuit
,10-05 13:51:44.596   931  2925 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-05 13:51:44.596   931  5748 D DhcpClient: onQuitting
,10-05 13:51:44.596  5743  5743 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-05 13:51:44.597   931   948 D Tethering: MasterInitialState.processMessage what=3
,10-05 13:51:44.606  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.606  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:44.606  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:44.606  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:44.606  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:44.606  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:44.606  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:44.606  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:44.606  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:44.607  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.607  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:44.607  3900  3900 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-05 13:51:44.608  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.608  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:44.608  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:44.608  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:44.608  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:44.608  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:44.608  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:44.608  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:44.608  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:44.608  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.608  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:44.609  5003  5025 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 13:51:44.609  5003  5025 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 13:51:44.609  5003  5025 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-05 13:51:44.609  5003  5025 E SarControlService: no key has been found,reset the power
10-05 13:51:44.610  5003  5040 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 13:51:44.610  5003  5040 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 13:51:44.610  5003  5040 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 13:51:44.610  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.610  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:51:44.610  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:44.610  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:44.610  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:44.610  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:44.610  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:44.610  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:44.610  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:44.610  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:44.610  5028  5028 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 13:51:44.610  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:44.610  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:44.611  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state chang,es
10-05 13:51:44.612  5003  5040 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 13:51:44.612  5003  5040 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 13:51:44.612  5003  5040 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-05 13:51:44.612  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:44.612  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:51:44.612  5028  5028 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 13:51:44.613  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:44.616  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-05 13:51:44.617  3900  3900 D SystemUpdateService: onCreate
10-05 13:51:44.619  5028  5042 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@441dcf4 HexData = [00000000ee03000000000000ffffffff]
10-05 13:51:44.619  5028  5042 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:51:44.619  5028  5042 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-05 13:51:44.619  5028  5042 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@441dcf4 HexData = [00000000ef03000000000000ffffffff]
10-05 13:51:44.619  5028  5042 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:51:44.619  5028  5042 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-05 13:51:44.620  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:51:44.620  5003  5014 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-05 13:51:44.620  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:51:44.620  5003  5013 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-05 13:51:44.621  5743  5743 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-05 13:51:44.623  3900  3900 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-05 13:51:44.630  3900  5779 I SystemUpdateService: active receiver: enabled
,10-05 13:51:44.632  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-05 13:51:44.638  3900  5779 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 13:51:44.640  3900  5366 I iu.UploadsManager: num queued entries: 0
10-05 13:51:44.640  3900  5366 I iu.UploadsManager: num updated entries: 0
,10-05 13:51:44.641  3900  5366 I iu.SyncManager: NEXT; no task
,10-05 13:51:44.643  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 13:51:44.644  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 13:51:44.646  5710  5710 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 13:51:44.650  5710  5710 D SprintDMHelper: simOperator: 
10-05 13:51:44.650  5710  5710 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 13:51:44.651  3900  5779 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-05 13:51:44.653  3900  5779 I SystemUpdateService: now status is 0 (complete)
,10-05 13:51:44.653  3900  5779 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-05 13:51:44.656   509   924 E Netd    : netlink response contains error (No such file or directory)
10-05 13:51:44.656  3900  5779 I SystemUpdateService: file has been verified
10-05 13:51:44.657   931  2928 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-05 13:51:44.657  3900  5779 I SystemUpdateService: OTA package size = 21989297
,10-05 13:51:44.660  4978  5783 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-05 13:51:44.661  5743  5743 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-05 13:51:44.677  3900  5779 I SystemUpdateService: showing system update notification
,10-05 13:51:44.678  5743  5743 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-05 13:51:44.686  3900  3900 D SystemUpdateService: onDestroy
,10-05 13:51:44.780   931  2925 D wifi    : In wifi stop Hal
,10-05 13:51:44.780   931  2925 D wifi    : halHandle = 0x7f81be2680, mVM = 0x7f9e20d140, mCls = 0x18c2
10-05 13:51:44.780   931  5742 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-05 13:51:44.780   931  5742 D WifiHAL : Got a signal to exit!!!
10-05 13:51:44.780   931  5742 I WifiHAL : Exit wifi_event_loop
,10-05 13:51:44.781   931  2925 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-05 13:51:44.781   931  2925 E WifiHAL : Event processing terminated
10-05 13:51:44.782   931  2925 D wifi    : In wifi cleaned up handler
,10-05 13:51:44.782   931  2925 I WifiHAL : Internal cleanup completed
10-05 13:51:44.782  4978  4978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-05 13:51:44.783  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:44.784  4068  4175 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:51:44.784  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:44.785  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:44.805   931  5742 D wifi    : set interface wlan0 flags (DOWN)
,10-05 13:51:44.805   931  2925 D WifiNative-HAL: HAL event thread stopped successfully
,10-05 13:51:45.012   931   948 D Tethering: InitialState.processMessage what=4
,10-05 13:51:45.021   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-05 13:51:45.323   931  2928 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-05 13:51:49.557   931   948 I ActivityManager: Start proc 5785:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-05 13:51:49.640  5785  5785 D AdapterServiceConfig: Adding HeadsetService
,10-05 13:51:49.641  5785  5785 D AdapterServiceConfig: Adding A2dpService
10-05 13:51:49.641  5785  5785 D AdapterServiceConfig: Adding HidService
10-05 13:51:49.641  5785  5785 D AdapterServiceConfig: Adding HealthService
10-05 13:51:49.641  5785  5785 D AdapterServiceConfig: Adding PanService
10-05 13:51:49.641  5785  5785 D AdapterServiceConfig: Adding GattService
10-05 13:51:49.641  5785  5785 D AdapterServiceConfig: Adding BluetoothMapService
,10-05 13:51:49.642  5785  5785 D AdapterServiceConfig: Adding SapService
,10-05 13:51:49.652   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@61499bb:true
,10-05 13:51:49.652  5785  5785 D BluetoothAdapterState: make() - Creating AdapterState
,10-05 13:51:49.655  5785  5785 I bt_bluedroid: init
,10-05 13:51:49.655  5785  5797 I BluetoothAdapterState: Entering OffState
,10-05 13:51:49.658  5785  5798 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-05 13:51:49.658  5785  5798 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-05 13:51:49.658  5785  5798 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-05 13:51:49.658  5785  5798 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-05 13:51:49.659  5785  5785 I bt_bluedroid: get_profile_interface socket
,10-05 13:51:49.660  5785  5801 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 13:51:49.661  5785  5785 I bt_bluedroid: get_profile_interface sdp
10-05 13:51:49.662  5785  5801 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 13:51:49.665  5785  5796 I bt_bluedroid: config_hci_snoop_log
,10-05 13:51:49.666   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-05 13:51:49.669  5785  5797 D BluetoothAdapterState: Current state: OFF, message: 0
10-05 13:51:49.669  5785  5797 D BluetoothAdapterProperties: Setting state to 14
10-05 13:51:49.669  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-05 13:51:49.671  5785  5797 D BluetoothBondStateMachine: make
,10-05 13:51:49.672  5785  5802 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-05 13:51:49.675  5785  5797 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:51:49.676  5785  5785 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-05 13:51:49.678  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
,10-05 13:51:49.678  5785  5785 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-05 13:51:49.679  5785  5785 D BtGatt.GattService: Received start request. Starting profile...
,10-05 13:51:49.679  5785  5785 D BtGatt.GattService: start()
10-05 13:51:49.679  5785  5785 I bt_bluedroid: get_profile_interface gatt
10-05 13:51:49.680  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:51:49.680  5785  5785 D BtGatt.AdvertiseManager: advertise manager created
,10-05 13:51:49.684  5785  5785 V BluetoothAdapterState: isTurningOff()=false
10-05 13:51:49.684  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:49.684  5785  5785 V BluetoothAdapterState: isBleTurningOn()=true
10-05 13:51:49.684  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:51:49.684  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-05 13:51:49.686  5785  5797 I bt_bluedroid: bt_bluedroid
10-05 13:51:49.686  5785  5798 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-05 13:51:49.686  5785  5798 I bt_hci  : start_up
,10-05 13:51:49.692  5785  5798 I bt_vendor: alloc value 0xf416d871
10-05 13:51:49.692  5785  5798 I bt_vendor: init
10-05 13:51:49.692  5785  5798 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-05 13:51:49.692  5785  5798 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-05 13:51:49.802  5785  5798 D bt_hci  : start_up starting async portion
,10-05 13:51:49.802  5785  5805 I bt_hci  : event_finish_startup
10-05 13:51:49.802  5785  5805 I bt_hci_h4: hal_open
10-05 13:51:49.803  5785  5805 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-05 13:51:49.805  5785  5805 I bt_userial_vendor: device fd = 54 open
,10-05 13:51:49.801  5806  5806 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 13:51:49.819  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 13:51:49.822  5785  5805 D bt_hwcfg: Chipset BCM4358A3
,10-05 13:51:49.822  5785  5805 D bt_hwcfg: Target name = [BCM4358A3]
,10-05 13:51:49.823  5785  5805 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-05 13:51:50.209  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-05 13:51:50.210  5785  5805 D bt_hwcfg: Settlement delay -- 100 ms
10-05 13:51:50.210  5785  5805 I bt_hwcfg: Setting fw settlement delay to 100 
,10-05 13:51:50.346  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-05 13:51:50.346  5785  5805 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-05 13:51:50.348  5785  5805 I bt_hwcfg: vendor lib fwcfg completed
10-05 13:51:50.348  5785  5805 I bt_vendor: firmware callback
10-05 13:51:50.348  5785  5805 I bt_hci  : firmware_config_callback
,10-05 13:51:50.358  5785  5808 I bt_btu  : btu_task pending for preload complete event
,10-05 13:51:50.358  5785  5808 I bt_btu_task: Bluetooth chip preload is complete
10-05 13:51:50.358  5785  5808 I bt_btu  : btu_task received preload complete event
,10-05 13:51:50.366  5785  5808 I         : BTE_InitTraceLevels -- TRC_HCI
,10-05 13:51:50.366  5785  5808 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-05 13:51:50.366  5785  5808 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-05 13:51:50.366  5785  5808 I         : BTE_InitTraceLevels -- TRC_AVDT
10-05 13:51:50.366  5785  5808 I         : BTE_InitTraceLevels -- TRC_AVRC
10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_A2D
10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTM
10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_GAP
10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_PAN
10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_SDP
10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_GATT
,10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_SMP
10-05 13:51:50.367  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-05 13:51:50.368  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-05 13:51:50.449  5785  5808 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40eb549
10-05 13:51:50.449  5785  5808 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40eb549 
,10-05 13:51:50.466  5785  5801 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-05 13:51:50.467  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 13:51:50.468  5785  5801 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 13:51:50.472  5785  5801 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 13:51:50.474  5785  5801 D BluetoothAdapterProperties: Scan Mode:20
,10-05 13:51:50.474  5785  5801 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-05 13:51:50.475  5785  5801 D bt_hci  : do_postload posting postload work item
10-05 13:51:50.475  5785  5805 I bt_hci  : event_postload
,10-05 13:51:50.475  5785  5805 I bt_vendor: sco_config_cb
,10-05 13:51:50.475  5785  5805 I bt_hci  : sco_config_callback postload finished.
10-05 13:51:50.478  5785  5801 D bt_bte_conf: Device ID record 1 : primary
10-05 13:51:50.478  5785  5801 D bt_bte_conf:   vendorId            = 000f
10-05 13:51:50.478  5785  5801 D bt_bte_conf:   vendorIdSource      = 0001
10-05 13:51:50.478  5785  5801 D bt_bte_conf:   product             = 1200
10-05 13:51:50.478  5785  5801 D bt_bte_conf:   version             = 1436
10-05 13:51:50.478  5785  5801 D bt_bte_conf:   clientExecutableURL = 
10-05 13:51:50.478  5785  5801 D bt_bte_conf:   serviceDescription  = 
10-05 13:51:50.479  5785  5801 D bt_bte_conf:   documentationURL    = 
10-05 13:51:50.479  5785  5801 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-05 13:51:50.479  5785  5798 D bt_stack_manager: event_start_up_stack finished
10-05 13:51:50.480  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-05 13:51:50.480  5785  5797 D BluetoothAdapterProperties: Setting state to 15
,10-05 13:51:50.480  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-05 13:51:50.482  5785  5797 I BluetoothAdapterState: Entering BleOnState
10-05 13:51:50.482  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:50.488  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:50.489  5785  5805 I bt_vendor: low_power_mode_cb
10-05 13:51:50.489  5785  5797 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-05 13:51:50.490  5785  5797 D BluetoothAdapterProperties: Setting state to 11
,10-05 13:51:50.490  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-05 13:51:50.491  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:50.499  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:51:50.500  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:50.501  5785  5785 D HeadsetService: Received start request. Starting profile...
10-05 13:51:50.502  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:50.504  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:50.504  5785  5785 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-05 13:51:50.504  5785  5785 D HeadsetStateMachine: make
,10-05 13:51:50.512  5785  5797 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:51:50.514  5785  5785 D HeadsetStateMachine: max_hf_connections = 1
10-05 13:51:50.514  5785  5785 I bt_bluedroid: get_profile_interface handsfree
10-05 13:51:50.514  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,10-05 13:51:50.515  5785  5801 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-05 13:51:50.519  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
,10-05 13:51:50.519  5785  5785 D A2dpService: Received start request. Starting profile...
,10-05 13:51:50.520  5785  5785 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-05 13:51:50.520  5785  5785 I bt_bluedroid: get_profile_interface avrcp
,10-05 13:51:50.525  5785  5785 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-05 13:51:50.526  5785  5785 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-05 13:51:50.526  5785  5785 D A2dpStateMachine: make
10-05 13:51:50.527  5785  5785 I bt_bluedroid: get_profile_interface a2dp
,10-05 13:51:50.528  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-05 13:51:50.529  5785  5817 D A2dpStateMachine: Enter Disconnected: -2
,10-05 13:51:50.529  5785  5785 I BluetoothHidServiceJni: classInitNative: succeeds
,10-05 13:51:50.530  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:51:50.531  5643  5643 D BluetoothInputDevice: Proxy object connected
,10-05 13:51:50.531  5785  5785 D HidService: Received start request. Starting profile...
10-05 13:51:50.531  5785  5785 I bt_bluedroid: get_profile_interface hidhost
10-05 13:51:50.532  5785  5785 D HidService: setHidService(): set to: null
10-05 13:51:50.532  5785  5801 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40cc56d
10-05 13:51:50.532  5643  5643 D HidProfile: Bluetooth service connected
10-05 13:51:50.532  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-05 13:51:50.533  5785  5785 I BluetoothHealthServiceJni: classInitNative: succeeds
10-05 13:51:50.534  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:51:50.535  5785  5785 D HealthService: Received start request. Starting profile...
,10-05 13:51:50.535  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 13:51:50.536  5785  5785 I bt_bluedroid: get_profile_interface health
,10-05 13:51:50.537  5785  5785 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-05 13:51:50.537  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
,10-05 13:51:50.538  5643  5643 D BluetoothPan: BluetoothPAN Proxy object connected
,10-05 13:51:50.539  5785  5785 D PanService: Received start request. Starting profile...
10-05 13:51:50.539  5785  5785 D BluetoothPanServiceJni: initializeNative(L110): pan
10-05 13:51:50.539  5785  5785 I bt_bluedroid: get_profile_interface pan
10-05 13:51:50.539  5643  5643 D PanProfile: Bluetooth service connected
10-05 13:51:50.539  5785  5801 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-05 13:51:50.542  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
,10-05 13:51:50.543  5643  5643 D BluetoothMap: Proxy object connected
,10-05 13:51:50.543  5785  5785 D BluetoothMapService: Received start request. Starting profile...
10-05 13:51:50.543  5785  5785 D BluetoothMapService: start()
10-05 13:51:50.543  5643  5643 D MapProfile: Bluetooth service connected
10-05 13:51:50.543  5643  5643 D BluetoothMap: getConnectedDevices()
10-05 13:51:50.544  5643  5643 D BluetoothMap: Bluetooth is Not enabled
,10-05 13:51:50.545  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-05 13:51:50.546  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-05 13:51:50.546  5785  5785 D BluetoothMapAppObserver: createReceiver()
,10-05 13:51:50.548  5785  5785 D BluetoothMapAppObserver: initObservers()
10-05 13:51:50.548  5785  5785 D BluetoothMapAppObserver: getEnabledAccountItems()
10-05 13:51:50.555  5785  5785 V SapService: SapBinder()
10-05 13:51:50.555  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:51:50.556  5785  5785 D SapService: Received start request. Starting profile...
10-05 13:51:50.556  5785  5785 V SapService: start()
,10-05 13:51:50.557  5785  5785 V BluetoothAdapterState: isTurningOff()=false
10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isTurningOn()=true
,10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isTurningOff()=false
10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isTurningOn()=true
10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:50.558  5785  5815 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isTurningOff()=false
10-05 13:51:50.558  5785  5785 V BluetoothAdapterState: isTurningOn()=true
10-05 13:51:50.559  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:50.559  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:51:50.559  5785  5785 V BluetoothAdapterState: isTurningOff()=false
10-05 13:51:50.559  5785  5785 V BluetoothAdapterState: isTurningOn()=true
10-05 13:51:50.559  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:50.559  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:50.560  5785  5785 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:51:50.560  5785  5785 V BluetoothAdapterState: isTurningOn()=true
10-05 13:51:50.560  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:50.560  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:50.560  5785  5785 V BluetoothAdapterState: isTurningOff()=false
10-05 13:51:50.560  5785  5785 V BluetoothAdapterState: isTurningOn()=true
10-05 13:51:50.560  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:50.560  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:51:50.561  5785  5785 V BluetoothAdapterState: isTurningOff()=false
10-05 13:51:50.561  5785  5785 V BluetoothAdapterState: isTurningOn()=true
10-05 13:51:50.561  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:50.561  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:51:50.561  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-05 13:51:50.562  5785  5797 D BluetoothAdapterProperties: ScanMode =  20
,10-05 13:51:50.562  5785  5797 D BluetoothAdapterProperties: State =  11
10-05 13:51:50.563  5785  5801 D BluetoothAdapterProperties: Scan Mode:21
10-05 13:51:50.563  5785  5797 D BluetoothAdapterProperties: Setting state to 12
,10-05 13:51:50.563  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-05 13:51:50.563  5785  5801 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 13:51:50.564  5589  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-05 13:51:50.564  5785  5797 I BluetoothAdapterState: Entering OnState
10-05 13:51:50.564  3092  3931 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-05 13:51:50.567  3092  3092 D BluetoothA2dp: Proxy object connected
,10-05 13:51:50.568  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:50.568  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:50.568  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:50.568  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:50.568  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:50.568  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:50.568  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:50.568  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:51:50.569  5643  5653 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-05 13:51:50.569  5643  5655 D BluetoothPan: onBluetoothStateChange on: true
,10-05 13:51:50.569  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:50.570  5643  5653 D BluetoothMap: onBluetoothStateChange: up=true
10-05 13:51:50.570   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:51:50.570   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:51:50.570   931   931 D BluetoothA2dp: Proxy object connected
10-05 13:51:50.570   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:51:50.570  3092  3106 D BluetoothMap: onBluetoothStateChange: up=true
10-05 13:51:50.572  3092  3106 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 13:51:50.573  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-05 13:51:50.573  3092  3092 D BluetoothMap: Proxy object connected
,10-05 13:51:50.573  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:50.573  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:50.573  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:50.573  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:50.573  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:50.573  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:50.573  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:50.573  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:50.573  3092  3092 D MapProfile: Bluetooth service connected
10-05 13:51:50.573  3092  3092 D BluetoothMap: getConnectedDevices()
,10-05 13:51:50.573  5785  5785 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-05 13:51:50.574  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:51:50.575  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:50.576  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:51:50.577  5643  5655 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 13:51:50.578  3092  3092 D BluetoothInputDevice: Proxy object connected
10-05 13:51:50.578  3092  3092 D HidProfile: Bluetooth service connected
10-05 13:51:50.578  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:50.578  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:50.578  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:50.578  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:50.578  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:51:50.578  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:50.578  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:50.578  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:51:50.578  5785  5785 D ObexServerSockets: Succeed to create listening sockets 
10-05 13:51:50.579  5785  5785 D ObexServerSockets0: startAccept()
,10-05 13:51:50.579  5785  5785 D ObexServerSockets0: prepareForNewConnect()
,10-05 13:51:50.579  3092  3104 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:51:50.580  3725  3983 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:51:50.580  3092  3106 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 13:51:50.581  5785  5785 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-05 13:51:50.581  5785  5785 D BluetoothSdpJni: SDP Create record success - handle: 0
10-05 13:51:50.581  5785  5822 D ObexServerSockets0: Accepting socket connection...
10-05 13:51:50.581  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:50.581   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:51:50.582  5785  5823 D ObexServerSockets0: Accepting socket connection...
10-05 13:51:50.582  3092  3931 D BluetoothPan: onBluetoothStateChange on: true
10-05 13:51:50.583  3092  3092 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 13:51:50.584  3092  3092 D PanProfile: Bluetooth service connected
10-05 13:51:50.584   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
10-05 13:51:50.585  5589  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-05 13:51:50.585  5785  5785 D BluetoothMapService: onReceive
10-05 13:51:50.585  5785  5785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 13:51:50.585  5785  5785 D BluetoothMapService: STATE_ON
10-05 13:51:50.587  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:50.588  5643  5643 D LocalBluetoothProfileManager: Adding local A2DP profile
10-05 13:51:50.588  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:50.590  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:50.591  5785  5826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:51:50.592  5785  5826 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-05 13:51:50.592  5785  5826 D BluetoothSdpJni: SDP Create record success - handle: 1
10-05 13:51:50.592  5643  5643 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-05 13:51:50.598  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 13:51:50.600  5643  5643 D BluetoothA2dp: Proxy object connected
,10-05 13:51:50.605  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 13:51:50.606  5643  5643 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:51:50.613  3092  3092 D BluetoothPbap: Proxy object connected
,10-05 13:51:50.613  3092  3092 D PbapServerProfile: Bluetooth service connected
,10-05 13:51:50.613  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-05 13:51:50.613  5785  5785 D ObexServerSockets0: prepareForNewConnect()
10-05 13:51:50.614  5643  5643 D BluetoothPbap: Proxy object connected
10-05 13:51:50.615  5643  5643 D PbapServerProfile: Bluetooth service connected
,10-05 13:51:50.621  5785  5830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:51:50.633  5785  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:51:50.636  5785  5834 I BtOppRfcommListener: Accept thread started.
,10-05 13:51:50.673   931   931 D BluetoothHeadset: Proxy object connected
,10-05 13:51:50.673  3725  3981 D BluetoothHeadset: Proxy object connected
10-05 13:51:50.673   931   931 D BluetoothHeadset: Proxy object connected
10-05 13:51:50.673   931   931 D BluetoothHeadset: Proxy object connected
10-05 13:51:50.674  3092  3931 D BluetoothHeadset: Proxy object connected
,10-05 13:51:50.675  3092  3092 D HeadsetProfile: Bluetooth service connected
,10-05 13:51:50.680  3092  3106 D BluetoothHeadset: Proxy object connected
10-05 13:51:50.680  3092  3092 D HeadsetProfile: Bluetooth service connected
,10-05 13:51:50.680  3725  3740 D BluetoothHeadset: Proxy object connected
,10-05 13:51:50.681   931   948 D BluetoothHeadset: Proxy object connected
,10-05 13:51:50.695  5643  5655 D BluetoothHeadset: Proxy object connected
,10-05 13:51:50.697  5643  5643 D HeadsetProfile: Bluetooth service connected
,10-05 13:51:52.284   931  2928 D ConnectivityService: handlePromptUnvalidated 101
,10-05 13:51:54.532  5785  5797 D BluetoothAdapterState: Current state: ON, message: 23
,10-05 13:51:54.532  5785  5797 D BluetoothAdapterProperties: Setting state to 13
10-05 13:51:54.532  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-05 13:51:54.534  5785  5797 D BluetoothAdapterProperties: onBluetoothDisable()
,10-05 13:51:54.535  5785  5797 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:51:54.539  5785  5785 D BluetoothMapService: onReceive
10-05 13:51:54.541  5785  5785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-05 13:51:54.542  5785  5785 D BluetoothMapService: STATE_TURNING_OFF
10-05 13:51:54.542  5785  5785 D BluetoothMapService: MAP Service closeService in
10-05 13:51:54.542  5785  5785 D BluetoothMapMasInstance0: MAP Service shutdown
10-05 13:51:54.542  5785  5785 D ObexServerSockets0: shutdown(block = true)
10-05 13:51:54.544  5785  5785 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 13:51:54.544  5785  5785 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-05 13:51:54.545  5785  5822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-05 13:51:54.546  5785  5801 D BluetoothAdapterProperties: Scan Mode:20
,10-05 13:51:54.546  5785  5823 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-05 13:51:54.547  5785  5810 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-05 13:51:54.547  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-05 13:51:54.549  5785  5785 I BtOppRfcommListener: stopping Accept Thread
10-05 13:51:54.549  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:54.549  5785  5834 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-05 13:51:54.550  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:54.550  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:54.550  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:54.550  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:54.550  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:54.550  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:54.550  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:54.550  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:54.551  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 13:51:54.551  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:54.551  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:54.553  5785  5834 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-05 13:51:54.557  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:54.557  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:54.557  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:54.557  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:54.557  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:54.557  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:54.557  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:54.557  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:54.557  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:54.559  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:54.559  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:51:54.562  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-05 13:51:54.562  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:51:54.562  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:51:54.562  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:51:54.562  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:51:54.562  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-05 13:51:54.562  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:51:54.562  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:51:54.562  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:51:54.563  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-05 13:51:54.563  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:51:54.566  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:54.566  5785  5785 D HeadsetService: Received stop request...Stopping profile...
10-05 13:51:54.567  5643  5643 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:51:54.568  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:54.571   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:51:54.572  3725  3737 D BluetoothHeadset: Proxy object disconnected
10-05 13:51:54.572  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:54.572   931   931 D BluetoothHeadset: Proxy object disconnected
10-05 13:51:54.572   931   931 D BluetoothHeadset: Proxy object disconnected
,10-05 13:51:54.573  5643  5655 D BluetoothHeadset: Proxy object disconnected
10-05 13:51:54.573  5785  5785 D A2dpService: Received stop request...Stopping profile...
10-05 13:51:54.573  5785  5817 D A2dpStateMachine: Exit Disconnected: -1
10-05 13:51:54.573  3092  3104 D BluetoothHeadset: Proxy object disconnected
10-05 13:51:54.574   931   931 D BluetoothA2dp: Proxy object disconnected
10-05 13:51:54.574  5643  5643 D HeadsetProfile: Bluetooth service disconnected
10-05 13:51:54.574  5643  5643 D BluetoothA2dp: Proxy object disconnected
10-05 13:51:54.575  3092  3092 D HeadsetProfile: Bluetooth service disconnected
10-05 13:51:54.575  3092  3092 D BluetoothA2dp: Proxy object disconnected
,10-05 13:51:54.577  5785  5785 D HidService: Received stop request...Stopping profile...
10-05 13:51:54.577  5785  5785 D HidService: Stopping Bluetooth HidService
,10-05 13:51:54.578  3092  3092 D BluetoothInputDevice: Proxy object disconnected
,10-05 13:51:54.578  3092  3092 D HidProfile: Bluetooth service disconnected
,10-05 13:51:54.580  5785  5785 D HealthService: Received stop request...Stopping profile...
,10-05 13:51:54.581  5785  5785 D PanService: Received stop request...Stopping profile...
10-05 13:51:54.582  3092  3092 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 13:51:54.582  3092  3092 D PanProfile: Bluetooth service disconnected
10-05 13:51:54.582  5643  5643 D BluetoothInputDevice: Proxy object disconnected
10-05 13:51:54.582  5643  5643 D HidProfile: Bluetooth service disconnected
10-05 13:51:54.582  5643  5643 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-05 13:51:54.582  5643  5643 D PanProfile: Bluetooth service disconnected
,10-05 13:51:54.583  5785  5785 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:54.583  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:54.583  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:54.583  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:54.584  5785  5785 D BluetoothMapService: Received stop request...Stopping profile...
10-05 13:51:54.584  5785  5785 D BluetoothMapService: stop()
,10-05 13:51:54.585  5785  5785 D BluetoothMapAppObserver: deinitObservers()
10-05 13:51:54.585  5785  5785 D BluetoothMapAppObserver: removeReceiver()
10-05 13:51:54.585  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 13:51:54.588  3092  3092 D BluetoothMap: Proxy object disconnected
10-05 13:51:54.588  3092  3092 D MapProfile: Bluetooth service disconnected
,10-05 13:51:54.589  5643  5643 D BluetoothMap: Proxy object disconnected
10-05 13:51:54.589  5643  5643 D MapProfile: Bluetooth service disconnected
,10-05 13:51:54.590  5785  5785 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-05 13:51:54.590  5785  5785 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-05 13:51:54.590  5785  5808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:54.590  5785  5808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:54.590  5785  5808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:54.590  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-05 13:51:54.591  5785  5801 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-05 13:51:54.591  5785  5785 D SapService: Received stop request...Stopping profile...
10-05 13:51:54.591  5785  5785 V SapService: stop()
10-05 13:51:54.592  5785  5785 V BluetoothAdapterState: isTurningOff()=true
,10-05 13:51:54.592  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:54.592  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:54.592  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:54.593  5785  5808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:54.593  5785  5808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:54.593  5785  5785 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:54.593  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:54.593  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:54.593  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:54.594  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-05 13:51:54.594  5785  5808 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 13:51:54.594  5785  5808 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 13:51:54.594  5785  5808 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-05 13:51:54.594  5785  5808 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-05 13:51:54.594  5785  5785 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-05 13:51:54.594  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 13:51:54.594  5785  5785 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-05 13:51:54.595  5785  5785 V BluetoothAdapterState: isTurningOff()=true
,10-05 13:51:54.595  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:54.595  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:54.595  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:54.595  5785  5785 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-05 13:51:54.595  5785  5801 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-05 13:51:54.598  5785  5785 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-05 13:51:54.598  5785  5785 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:54.598  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:54.599  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:54.599  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:54.599  5785  5785 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-05 13:51:54.599  5785  5785 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-05 13:51:54.601  3092  3092 D BluetoothPbap: Proxy object disconnected
10-05 13:51:54.601  3092  3092 D PbapServerProfile: Bluetooth service disconnected
10-05 13:51:54.601  5785  5785 D BluetoothMapService: MAP Service closeService in
10-05 13:51:54.601  5785  5785 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:54.601  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:54.601  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:54.601  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:51:54.601  5785  5785 D BluetoothMapService: cleanup()
10-05 13:51:54.601  5785  5785 D BluetoothMapService: MAP Service closeService in
,10-05 13:51:54.602  5785  5785 V BluetoothAdapterState: isTurningOff()=true
10-05 13:51:54.602  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:54.602  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 13:51:54.602  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:51:54.602  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-05 13:51:54.602  5785  5797 D BluetoothAdapterProperties: Setting state to 15
,10-05 13:51:54.602  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-05 13:51:54.603  5785  5797 I BluetoothAdapterState: Entering BleOnState
10-05 13:51:54.603  3092  3104 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:51:54.604  5643  5643 D BluetoothPbap: Proxy object disconnected
10-05 13:51:54.604  5643  5643 D PbapServerProfile: Bluetooth service disconnected
10-05 13:51:54.604  5643  5653 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-05 13:51:54.604  5643  5655 D BluetoothPan: onBluetoothStateChange on: false
10-05 13:51:54.605  5643  5653 D BluetoothMap: onBluetoothStateChange: up=false
10-05 13:51:54.605   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:51:54.605   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:54.605   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:54.606  5643  5655 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:54.606  3092  3931 D BluetoothMap: onBluetoothStateChange: up=false
10-05 13:51:54.606  3092  3106 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-05 13:51:54.607  5643  5653 D BluetoothPbap: onBluetoothStateChange: up=false
,10-05 13:51:54.608  3092  3104 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:54.608  3725  3983 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:54.609  5643  5655 D BluetoothA2dp: onBluetoothStateChange: up=false
10-05 13:51:54.609  3092  3931 D BluetoothPbap: onBluetoothStateChange: up=false
10-05 13:51:54.610   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-05 13:51:54.610  3092  3106 D BluetoothPan: onBluetoothStateChange on: false
10-05 13:51:54.610  5785  5797 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-05 13:51:54.610  5785  5797 D BluetoothAdapterProperties: Setting state to 16
10-05 13:51:54.610  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-05 13:51:54.611  5785  5797 D BluetoothAdapterProperties: onBleDisable
10-05 13:51:54.611  5785  5797 I BluetoothAdapterState: Entering PendingCommandState
10-05 13:51:54.611  5785  5798 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-05 13:51:54.613  5785  5801 D BluetoothAdapterProperties: Scan Mode:20
10-05 13:51:54.613  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:54.614  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-05 13:51:54.614  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:54.615  5785  5808 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-05 13:51:54.615  5785  5808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-05 13:51:54.616  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:54.619  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:54.620  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 13:51:54.621  5643  5643 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:51:54.623  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:51:54.624  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:51:54.653   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:54.821  5785  5801 I bt_hci  : shut_down
,10-05 13:51:54.825  5785  5805 D bt_hwcfg: hw_epilog_process
,10-05 13:51:54.825  5785  5805 I bt_vendor: low_power_mode_cb
,10-05 13:51:54.828  5785  5805 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-05 13:51:54.828  5785  5805 I bt_vendor: epilog_cb
10-05 13:51:54.828  5785  5805 I bt_hci  : epilog_finished_callback
,10-05 13:51:54.830  5785  5801 I bt_hci_h4: hal_close
,10-05 13:51:54.830  5785  5801 I bt_userial_vendor: device fd = 54 close
,10-05 13:51:54.935  5785  5798 D bt_stack_manager: event_shut_down_stack finished.
,10-05 13:51:54.936  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-05 13:51:54.941  5785  5797 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-05 13:51:54.942  5785  5785 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 13:51:54.943  5785  5785 D BtGatt.GattService: Received stop request...Stopping profile...
10-05 13:51:54.943  5785  5785 D BtGatt.GattService: stop()
10-05 13:51:54.943  5785  5785 D BtGatt.AdvertiseManager: advertise clients cleared
,10-05 13:51:54.948  5785  5785 V BluetoothAdapterState: isTurningOff()=false
,10-05 13:51:54.948  5785  5785 V BluetoothAdapterState: isTurningOn()=false
10-05 13:51:54.948  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:51:54.948  5785  5785 V BluetoothAdapterState: isBleTurningOff()=true
,10-05 13:51:54.949  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-05 13:51:54.949  5785  5797 D BluetoothAdapterProperties: Setting state to 10
10-05 13:51:54.949  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-05 13:51:54.950  5785  5797 I BluetoothAdapterState: Entering OffState
,10-05 13:51:54.952   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-05 13:51:54.973  5785  5785 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-05 13:51:54.973  5785  5785 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-05 13:51:54.973  5785  5798 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-05 13:51:54.976  5785  5785 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-05 13:51:54.983  5785  5785 I art     : System.exit called, status: 0
10-05 13:51:54.983  5785  5785 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-05 13:51:55.014   931  3808 I ActivityManager: Process com.android.bluetooth (pid 5785) has died
,10-05 13:51:55.654   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:56.655   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:57.656   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:58.657   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:51:59.532  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:59.533  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:51:59.537  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:51:59.538  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5814605 removed from the list
10-05 13:51:59.538  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:59.538  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:51:59.538  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:59.541  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:51:59.541  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32ad08b added. We now have 4 listener(s)
10-05 13:51:59.541  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:51:59.543  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:51:59.543  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32ad08b removed from the list
10-05 13:51:59.543  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:51:59.543  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:51:59.544  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:51:59.545  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:51:59.546  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b475568 added. We now have 4 listener(s)
10-05 13:51:59.546  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:51:59.658   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-05 13:52:04.556  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:04.590   931   948 I ActivityManager: Start proc 5842:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-05 13:52:04.676  5842  5842 D AdapterServiceConfig: Adding HeadsetService
,10-05 13:52:04.676  5842  5842 D AdapterServiceConfig: Adding A2dpService
10-05 13:52:04.676  5842  5842 D AdapterServiceConfig: Adding HidService
10-05 13:52:04.677  5842  5842 D AdapterServiceConfig: Adding HealthService
10-05 13:52:04.677  5842  5842 D AdapterServiceConfig: Adding PanService
10-05 13:52:04.677  5842  5842 D AdapterServiceConfig: Adding GattService
10-05 13:52:04.677  5842  5842 D AdapterServiceConfig: Adding BluetoothMapService
10-05 13:52:04.677  5842  5842 D AdapterServiceConfig: Adding SapService
,10-05 13:52:04.688   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79ae398:true
,10-05 13:52:04.689  5842  5842 D BluetoothAdapterState: make() - Creating AdapterState
,10-05 13:52:04.692  5842  5842 I bt_bluedroid: init
,10-05 13:52:04.693  5842  5854 I BluetoothAdapterState: Entering OffState
,10-05 13:52:04.696  5842  5855 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-05 13:52:04.696  5842  5855 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-05 13:52:04.696  5842  5855 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-05 13:52:04.696  5842  5855 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-05 13:52:04.697  5842  5842 I bt_bluedroid: get_profile_interface socket
,10-05 13:52:04.699  5842  5858 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-05 13:52:04.699  5842  5842 I bt_bluedroid: get_profile_interface sdp
,10-05 13:52:04.704  5842  5858 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 13:52:04.705  5842  5853 I bt_bluedroid: config_hci_snoop_log
,10-05 13:52:04.706   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-05 13:52:04.711  5842  5854 D BluetoothAdapterState: Current state: OFF, message: 0
10-05 13:52:04.711  5842  5854 D BluetoothAdapterProperties: Setting state to 14
10-05 13:52:04.711  5842  5854 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-05 13:52:04.712  5842  5854 D BluetoothBondStateMachine: make
,10-05 13:52:04.714  5842  5859 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-05 13:52:04.717  5842  5854 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:52:04.718  5842  5842 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-05 13:52:04.720  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:52:04.721  5842  5842 D BtGatt.DebugUtils: handleDebugAction() action=null
10-05 13:52:04.721  5842  5842 D BtGatt.GattService: Received start request. Starting profile...
10-05 13:52:04.721  5842  5842 D BtGatt.GattService: start()
10-05 13:52:04.722  5842  5842 I bt_bluedroid: get_profile_interface gatt
,10-05 13:52:04.723  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:52:04.723  5842  5842 D BtGatt.AdvertiseManager: advertise manager created
,10-05 13:52:04.729  5842  5842 V BluetoothAdapterState: isTurningOff()=false
10-05 13:52:04.729  5842  5842 V BluetoothAdapterState: isTurningOn()=false
,10-05 13:52:04.729  5842  5842 V BluetoothAdapterState: isBleTurningOn()=true
10-05 13:52:04.729  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
,10-05 13:52:04.730  5842  5854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-05 13:52:04.731  5842  5854 I bt_bluedroid: bt_bluedroid
10-05 13:52:04.731  5842  5855 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-05 13:52:04.731  5842  5855 I bt_hci  : start_up
,10-05 13:52:04.736  5842  5855 I bt_vendor: alloc value 0xf416d871
,10-05 13:52:04.736  5842  5855 I bt_vendor: init
10-05 13:52:04.736  5842  5855 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-05 13:52:04.736  5842  5855 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-05 13:52:04.846  5842  5855 D bt_hci  : start_up starting async portion
,10-05 13:52:04.846  5842  5862 I bt_hci  : event_finish_startup
10-05 13:52:04.847  5842  5862 I bt_hci_h4: hal_open
10-05 13:52:04.847  5842  5862 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-05 13:52:04.850  5842  5862 I bt_userial_vendor: device fd = 54 open
,10-05 13:52:04.844  5863  5863 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 13:52:04.866  5842  5862 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 13:52:04.869  5842  5862 D bt_hwcfg: Chipset BCM4358A3
,10-05 13:52:04.869  5842  5862 D bt_hwcfg: Target name = [BCM4358A3]
10-05 13:52:04.870  5842  5862 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-05 13:52:05.379  5842  5862 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-05 13:52:05.379  5842  5862 D bt_hwcfg: Settlement delay -- 100 ms
10-05 13:52:05.379  5842  5862 I bt_hwcfg: Setting fw settlement delay to 100 
,10-05 13:52:05.516  5842  5862 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-05 13:52:05.517  5842  5862 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-05 13:52:05.518  5842  5862 I bt_hwcfg: vendor lib fwcfg completed
,10-05 13:52:05.518  5842  5862 I bt_vendor: firmware callback
10-05 13:52:05.519  5842  5862 I bt_hci  : firmware_config_callback
,10-05 13:52:05.526  5842  5865 I bt_btu  : btu_task pending for preload complete event
,10-05 13:52:05.527  5842  5865 I bt_btu_task: Bluetooth chip preload is complete
10-05 13:52:05.527  5842  5865 I bt_btu  : btu_task received preload complete event
,10-05 13:52:05.533  5842  5865 I         : BTE_InitTraceLevels -- TRC_HCI
,10-05 13:52:05.534  5842  5865 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-05 13:52:05.534  5842  5865 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-05 13:52:05.534  5842  5865 I         : BTE_InitTraceLevels -- TRC_AVDT
10-05 13:52:05.534  5842  5865 I         : BTE_InitTraceLevels -- TRC_AVRC
10-05 13:52:05.534  5842  5865 I         : BTE_InitTraceLevels -- TRC_A2D
10-05 13:52:05.534  5842  5865 I         : BTE_InitTraceLevels -- TRC_BNEP
10-05 13:52:05.534  5842  5865 I         : BTE_InitTraceLevels -- TRC_BTM
10-05 13:52:05.534  5842  5865 I         : BTE_InitTraceLevels -- TRC_GAP
10-05 13:52:05.535  5842  5865 I         : BTE_InitTraceLevels -- TRC_PAN
10-05 13:52:05.535  5842  5865 I         : BTE_InitTraceLevels -- TRC_SDP
10-05 13:52:05.535  5842  5865 I         : BTE_InitTraceLevels -- TRC_GATT
10-05 13:52:05.535  5842  5865 I         : BTE_InitTraceLevels -- TRC_SMP
10-05 13:52:05.535  5842  5865 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-05 13:52:05.535  5842  5865 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-05 13:52:05.622  5842  5865 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40eb549
,10-05 13:52:05.622  5842  5865 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40eb549 
,10-05 13:52:05.635  5842  5858 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-05 13:52:05.637  5842  5858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-05 13:52:05.637  5842  5858 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-05 13:52:05.640  5842  5858 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-05 13:52:05.644  5842  5858 D BluetoothAdapterProperties: Scan Mode:20
,10-05 13:52:05.644  5842  5858 D BluetoothAdapterProperties: Discoverable Timeout:120
10-05 13:52:05.644  5842  5858 D bt_hci  : do_postload posting postload work item
10-05 13:52:05.644  5842  5862 I bt_hci  : event_postload
,10-05 13:52:05.645  5842  5862 I bt_vendor: sco_config_cb
10-05 13:52:05.645  5842  5862 I bt_hci  : sco_config_callback postload finished.
10-05 13:52:05.649  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:05.654  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:05.647  5842  5858 D bt_bte_conf: Device ID record 1 : primary
10-05 13:52:05.668  5842  5858 D bt_bte_conf:   vendorId            = 000f
10-05 13:52:05.668  5842  5858 D bt_bte_conf:   vendorIdSource      = 0001
10-05 13:52:05.668  5842  5858 D bt_bte_conf:   product             = 1200
10-05 13:52:05.668  5842  5858 D bt_bte_conf:   version             = 1436
10-05 13:52:05.668  5842  5858 D bt_bte_conf:   clientExecutableURL = 
10-05 13:52:05.668  5842  5858 D bt_bte_conf:   serviceDescription  = 
10-05 13:52:05.668  5842  5858 D bt_bte_conf:   documentationURL    = 
10-05 13:52:05.669  5842  5858 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-05 13:52:05.669  5842  5855 D bt_stack_manager: event_start_up_stack finished
,10-05 13:52:05.669  5842  5854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-05 13:52:05.670  5842  5854 D BluetoothAdapterProperties: Setting state to 15
10-05 13:52:05.670  5842  5854 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-05 13:52:05.671  5842  5854 I BluetoothAdapterState: Entering BleOnState
,10-05 13:52:05.654  5842  5862 I bt_vendor: low_power_mode_cb
10-05 13:52:05.675  5842  5854 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-05 13:52:05.675  5842  5854 D BluetoothAdapterProperties: Setting state to 11
,10-05 13:52:05.675  5842  5854 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-05 13:52:05.680  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:05.683  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:05.684  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
,10-05 13:52:05.684  5842  5842 D HeadsetService: Received start request. Starting profile...
,10-05 13:52:05.687  5842  5842 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-05 13:52:05.687  5842  5842 D HeadsetStateMachine: make
,10-05 13:52:05.699  5842  5854 I BluetoothAdapterState: Entering PendingCommandState
,10-05 13:52:05.702  5842  5842 D HeadsetStateMachine: max_hf_connections = 1
,10-05 13:52:05.703  5842  5842 I bt_bluedroid: get_profile_interface handsfree
10-05 13:52:05.703  5842  5858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-05 13:52:05.703  5842  5858 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
10-05 13:52:05.706  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:52:05.707  5842  5842 D A2dpService: Received start request. Starting profile...
,10-05 13:52:05.707  5842  5842 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-05 13:52:05.707  5842  5842 I bt_bluedroid: get_profile_interface avrcp
,10-05 13:52:05.714  5842  5842 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-05 13:52:05.714  5842  5842 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-05 13:52:05.714  5842  5842 D A2dpStateMachine: make
,10-05 13:52:05.715  5842  5842 I bt_bluedroid: get_profile_interface a2dp
10-05 13:52:05.716  5842  5858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-05 13:52:05.717  5842  5873 D A2dpStateMachine: Enter Disconnected: -2
,10-05 13:52:05.719  5842  5842 I BluetoothHidServiceJni: classInitNative: succeeds
,10-05 13:52:05.719  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:52:05.720  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-05 13:52:05.720  5842  5842 D HidService: Received start request. Starting profile...
10-05 13:52:05.720  5842  5842 I bt_bluedroid: get_profile_interface hidhost
10-05 13:52:05.720  5842  5842 D HidService: setHidService(): set to: null
10-05 13:52:05.720  5842  5842 I BluetoothHealthServiceJni: classInitNative: succeeds
10-05 13:52:05.721  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:52:05.721  5842  5842 D HealthService: Received start request. Starting profile...
,10-05 13:52:05.722  5842  5842 I bt_bluedroid: get_profile_interface health
,10-05 13:52:05.723  5842  5858 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40cc56d
10-05 13:52:05.723  5842  5858 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-05 13:52:05.723  5842  5842 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-05 13:52:05.724  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
,10-05 13:52:05.724  5842  5842 D PanService: Received start request. Starting profile...
10-05 13:52:05.724  5842  5842 D BluetoothPanServiceJni: initializeNative(L110): pan
10-05 13:52:05.724  5842  5842 I bt_bluedroid: get_profile_interface pan
10-05 13:52:05.725  5842  5858 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-05 13:52:05.727  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:52:05.728  5842  5842 D BluetoothMapService: Received start request. Starting profile...
10-05 13:52:05.728  5842  5842 D BluetoothMapService: start()
,10-05 13:52:05.730  5842  5842 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-05 13:52:05.730  5842  5842 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-05 13:52:05.731  5842  5842 D BluetoothMapAppObserver: createReceiver()
,10-05 13:52:05.731  5842  5842 D BluetoothMapAppObserver: initObservers()
10-05 13:52:05.731  5842  5842 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-05 13:52:05.736  5842  5842 V SapService: SapBinder()
,10-05 13:52:05.736  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:52:05.736  5842  5842 D SapService: Received start request. Starting profile...
10-05 13:52:05.736  5842  5842 V SapService: start()
,10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isTurningOff()=false
10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isTurningOn()=true
10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isTurningOff()=false
10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isTurningOn()=true
10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
,10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:52:05.737  5842  5842 V BluetoothAdapterState: isTurningOff()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isTurningOn()=true
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:52:05.738  5842  5871 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isTurningOff()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isTurningOn()=true
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isTurningOff()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isTurningOn()=true
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isTurningOff()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isTurningOn()=true
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:52:05.738  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:52:05.739  5842  5842 V BluetoothAdapterState: isTurningOff()=false
10-05 13:52:05.739  5842  5842 V BluetoothAdapterState: isTurningOn()=true
10-05 13:52:05.739  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
10-05 13:52:05.739  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
10-05 13:52:05.739  5842  5854 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-05 13:52:05.739  5842  5854 D BluetoothAdapterProperties: ScanMode =  20
10-05 13:52:05.739  5842  5854 D BluetoothAdapterProperties: State =  11
,10-05 13:52:05.741  5842  5858 D BluetoothAdapterProperties: Scan Mode:21
10-05 13:52:05.741  5589  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-05 13:52:05.741  5842  5854 D BluetoothAdapterProperties: Setting state to 12
10-05 13:52:05.741  5842  5854 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-05 13:52:05.741  5842  5858 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-05 13:52:05.741  3092  3104 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:52:05.743  5842  5854 I BluetoothAdapterState: Entering OnState
,10-05 13:52:05.744  5643  5653 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-05 13:52:05.744  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:52:05.744  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:05.744  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:05.744  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:52:05.744  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:05.744  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:52:05.744  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:52:05.744  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-05 13:52:05.745  3092  3092 D BluetoothA2dp: Proxy object connected
10-05 13:52:05.747  5643  5655 D BluetoothPan: onBluetoothStateChange on: true
10-05 13:52:05.748  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:52:05.749  5643  5643 D BluetoothInputDevice: Proxy object connected
10-05 13:52:05.749  5643  5643 D HidProfile: Bluetooth service connected
10-05 13:52:05.751  5643  5653 D BluetoothMap: onBluetoothStateChange: up=true
10-05 13:52:05.752  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:52:05.752  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:05.752  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:05.752  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:52:05.752  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:05.752  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:52:05.752  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:52:05.752  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:52:05.753   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:52:05.754   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:52:05.754   931   931 D BluetoothA2dp: Proxy object connected
10-05 13:52:05.754   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:52:05.754  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:52:05.754  5643  5655 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:52:05.754  5842  5842 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-05 13:52:05.755  5842  5842 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-05 13:52:05.755  3092  3106 D BluetoothMap: onBluetoothStateChange: up=true
10-05 13:52:05.757  5842  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:52:05.757  3092  3931 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-05 13:52:05.757  3092  3092 D BluetoothMap: Proxy object connected
10-05 13:52:05.757  3092  3092 D MapProfile: Bluetooth service connected
10-05 13:52:05.757  5643  5643 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 13:52:05.757  3092  3092 D BluetoothMap: getConnectedDevices()
10-05 13:52:05.757  5643  5643 D PanProfile: Bluetooth service connected
10-05 13:52:05.757  5643  5643 D BluetoothMap: Proxy object connected
10-05 13:52:05.757  5643  5643 D MapProfile: Bluetooth service connected
10-05 13:52:05.757  5643  5643 D BluetoothMap: getConnectedDevices()
10-05 13:52:05.758  5842  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:52:05.759  5643  5653 D BluetoothPbap: onBluetoothStateChange: up=true
,10-05 13:52:05.759  3092  3092 D BluetoothInputDevice: Proxy object connected
10-05 13:52:05.759  3092  3092 D HidProfile: Bluetooth service connected
10-05 13:52:05.760  3092  3104 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-05 13:52:05.761  3725  3983 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:52:05.761  5643  5655 D BluetoothA2dp: onBluetoothStateChange: up=true
10-05 13:52:05.761  5842  5842 D ObexServerSockets: Succeed to create listening sockets 
10-05 13:52:05.762  5842  5842 D ObexServerSockets0: startAccept()
10-05 13:52:05.762  5842  5842 D ObexServerSockets0: prepareForNewConnect()
10-05 13:52:05.763  3092  3931 D BluetoothPbap: onBluetoothStateChange: up=true
10-05 13:52:05.764  5842  5842 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-05 13:52:05.764  5842  5842 D BluetoothSdpJni: SDP Create record success - handle: 0
10-05 13:52:05.764  5842  5880 D ObexServerSockets0: Accepting socket connection...
10-05 13:52:05.764  5643  5643 D BluetoothA2dp: Proxy object connected
10-05 13:52:05.764  5842  5881 D ObexServerSockets0: Accepting socket connection...
,10-05 13:52:05.765   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-05 13:52:05.765  3092  3104 D BluetoothPan: onBluetoothStateChange on: true
10-05 13:52:05.766  3092  3092 D BluetoothPan: BluetoothPAN Proxy object connected
10-05 13:52:05.766  3092  3092 D PanProfile: Bluetooth service connected
,10-05 13:52:05.766   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
10-05 13:52:05.767  5842  5842 D BluetoothMapService: onReceive
10-05 13:52:05.767  5842  5842 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-05 13:52:05.767  5842  5842 D BluetoothMapService: STATE_ON
10-05 13:52:05.768  5589  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-05 13:52:05.769  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:05.770  5842  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-05 13:52:05.770  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:05.771  5842  5882 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-05 13:52:05.771  5842  5882 D BluetoothSdpJni: SDP Create record success - handle: 1
10-05 13:52:05.772  5643  5643 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-05 13:52:05.777  3522  3522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-05 13:52:05.779  5643  5643 D DockEventReceiver: finishStartingService: stopping service
,10-05 13:52:05.780  5643  5643 D BluetoothPbap: Proxy object connected
10-05 13:52:05.780  5643  5643 D PbapServerProfile: Bluetooth service connected
,10-05 13:52:05.783  5842  5885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:52:05.784  3092  3092 D BluetoothPbap: Proxy object connected
,10-05 13:52:05.784  3092  3092 D PbapServerProfile: Bluetooth service connected
,10-05 13:52:05.793  5842  5842 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-05 13:52:05.793  5842  5842 D ObexServerSockets0: prepareForNewConnect()
,10-05 13:52:05.795  5842  5891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-05 13:52:05.796  5842  5891 I BtOppRfcommListener: Accept thread started.
,10-05 13:52:05.854   931   931 D BluetoothHeadset: Proxy object connected
,10-05 13:52:05.854  3725  3981 D BluetoothHeadset: Proxy object connected
,10-05 13:52:05.855   931   931 D BluetoothHeadset: Proxy object connected
10-05 13:52:05.855  5643  5879 D BluetoothHeadset: Proxy object connected
10-05 13:52:05.855   931   931 D BluetoothHeadset: Proxy object connected
10-05 13:52:05.855  5643  5655 D BluetoothHeadset: Proxy object connected
,10-05 13:52:05.856  3092  3104 D BluetoothHeadset: Proxy object connected
,10-05 13:52:05.856  3092  3092 D HeadsetProfile: Bluetooth service connected
10-05 13:52:05.857  5643  5643 D HeadsetProfile: Bluetooth service connected
,10-05 13:52:05.858  5643  5643 D HeadsetProfile: Bluetooth service connected
,10-05 13:52:05.860  3092  3931 D BluetoothHeadset: Proxy object connected
,10-05 13:52:05.861  3092  3092 D HeadsetProfile: Bluetooth service connected
10-05 13:52:05.861  3725  3740 D BluetoothHeadset: Proxy object connected
,10-05 13:52:05.865   931   948 D BluetoothHeadset: Proxy object connected
,10-05 13:52:09.572  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:52:09.572  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:09.572  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:09.572  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-05 13:52:09.572  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:09.572  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:52:09.572  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:52:09.572  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:52:09.577  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:52:09.578  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:09.578  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b475568 removed from the list
,10-05 13:52:09.578  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:52:09.578  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:09.579  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:52:09.580  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:09.580  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd53d81 added. We now have 4 listener(s)
10-05 13:52:09.581  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:52:09.584   931  3809 D WifiService: setWifiEnabled: false pid=5589, uid=10077
10-05 13:52:09.584   931  3809 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:52:14.594  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:14.595   931  3516 D WifiService: setWifiEnabled: true pid=5589, uid=10077
10-05 13:52:14.595   931  3516 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-05 13:52:14.604   509   924 D SoftapController: Softap fwReload - Ok
,10-05 13:52:14.609   509   924 D CommandListener: Setting iface cfg
10-05 13:52:14.610   509   924 D CommandListener: Trying to bring down wlan0
,10-05 13:52:14.612   509   924 D CommandListener: Clearing all IP addresses on wlan0
,10-05 13:52:14.617   931  2925 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-05 13:52:15.229   931  2925 D wifi    : set interface wlan0 flags (UP)
,10-05 13:52:15.230   931  2925 I WifiHAL : Initializing wifi
,10-05 13:52:15.231   931  2925 I WifiHAL : Creating socket
10-05 13:52:15.236   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-05 13:52:15.238   931  2925 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-05 13:52:15.239   931  2925 D wifi    : Did set static halHandle = 0x7f81be2680
10-05 13:52:15.239   931  2925 D wifi    : halHandle = 0x7f81be2680, mVM = 0x7f9e20d140, mCls = 0x17be
10-05 13:52:15.239   931  2925 D wifi    : array field set
10-05 13:52:15.239   931  2925 I WifiNative-HAL: interface[0] = wlan0
10-05 13:52:15.241   931  5896 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547637569152
,10-05 13:52:15.241   931  5896 D wifi    : waitForHalEvents called, vm = 0x7f9e20d140, obj = 0x17be, env = 0x7f86a44580
,10-05 13:52:15.301  5897  5897 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-05 13:52:15.322  5897  5897 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 13:52:15.331  5897  5897 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-05 13:52:15.331  5897  5897 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-05 13:52:15.342   931  2925 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-05 13:52:15.354  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:15.357   931  2925 D WifiConfigStore: Loading config and enabling all networks 
,10-05 13:52:15.359  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:52:15.359  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:15.359  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:15.359  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:15.359  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:15.359  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:52:15.359  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:52:15.359  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:52:15.361  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-05 13:52:15.364  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:52:15.364  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:15.364  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:15.364  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:15.364  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:15.364  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-05 13:52:15.364  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-05 13:52:15.364  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-05 13:52:15.366  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-05 13:52:15.367  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:15.372   931  2925 D WifiConfigStore: loaded 0 passpoint configs
10-05 13:52:15.372   931  2925 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-05 13:52:15.373   931  2925 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-05 13:52:15.374   931  2925 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-05 13:52:15.375   931  2925 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-05 13:52:15.375   931  2925 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-05 13:52:15.376   931  2925 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-05 13:52:15.376   931  2925 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-05 13:52:15.380  4978  4978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-05 13:52:15.380   931  2925 D WifiNative-HAL: Setting external_sim to 1
10-05 13:52:15.381   931  2925 D wifi    : setting dfs flag to true, 0x7f858fcca0
,10-05 13:52:15.381   931  2925 D WifiStateMachine: Setting OUI to DA-A1-19
10-05 13:52:15.381   931  2925 D wifi    : setting scan oui 0x7f858fcca0
10-05 13:52:15.382   931  2925 D WifiHAL : Sending mac address OUI
,10-05 13:52:15.386   931  2925 E native  : do suspend false
,10-05 13:52:15.398   931  2925 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-05 13:52:15.398   509   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-05 13:52:15.398   931   931 D RttService: SCAN_AVAILABLE : 3
,10-05 13:52:15.399   931  3034 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-05 13:52:15.399   509   924 D CommandListener: Setting iface cfg
,10-05 13:52:15.404   931  2909 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
10-05 13:52:15.404   931  2909 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-05 13:52:15.413   931  2909 D WifiNative-HAL: p2pGetDeviceAddress
,10-05 13:52:15.418   931  2909 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-05 13:52:15.418   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=295270 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-05 13:52:18.596  5897  5897 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:52:18.607  5897  5897 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:52:18.613  5897  5897 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:52:18.618  5897  5897 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-05 13:52:18.646   931  2925 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-05 13:52:18.647   931  2925 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-05 13:52:18.647   931  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:52:18.661   931  2925 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-05 13:52:18.698   931  2925 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-05 13:52:18.700  5897  5897 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-05 13:52:19.133  5897  5897 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-05 13:52:19.172  5897  5897 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-05 13:52:19.173  5897  5897 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-05 13:52:19.186   931  2925 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-05 13:52:19.187   931  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:52:19.187   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-05 13:52:19.208   931  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-05 13:52:19.221   509   924 D CommandListener: Setting iface cfg
,10-05 13:52:19.227   931  2925 D WifiStateMachine: Start Dhcp Watchdog 3
,10-05 13:52:19.235   931  5902 D DhcpClient: Receive thread started
,10-05 13:52:19.240   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-05 13:52:19.240   931  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-05 13:52:19.240   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-05 13:52:19.331   931  2925 E native  : do suspend false
,10-05 13:52:19.353   931  5901 D DhcpClient: Broadcasting DHCPDISCOVER
,10-05 13:52:19.366   931  5902 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-05 13:52:19.367   931  5901 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-05 13:52:19.369   931  5901 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-05 13:52:19.382   931  5902 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-05 13:52:19.383   931  5901 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-05 13:52:19.386   509   924 D CommandListener: Setting iface cfg
,10-05 13:52:19.392   931  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-05 13:52:19.397   931  5901 D DhcpClient: Scheduling renewal in 86399s
,10-05 13:52:19.410   931  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-05 13:52:19.412   931  2925 D WifiConfigStore: No blacklist allowed without epno enabled
10-05 13:52:19.413   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-05 13:52:19.419   931  2928 D ConnectivityService: Adding iface wlan0 to network 102
10-05 13:52:19.423   931  2925 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-05 13:52:19.460   931  2928 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-05 13:52:19.461   931  2928 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-05 13:52:19.463   931  2928 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-05 13:52:19.466   931  2928 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-05 13:52:19.467   931  2928 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-05 13:52:19.472   931  5900 D NetlinkSocketObserver: NeighborEvent{elapsedMs=299323, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-05 13:52:19.477   931  2928 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:52:19.480   931  2928 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-05 13:52:19.481   931  2928 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-05 13:52:19.481   931  2928 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-05 13:52:19.481   931  2928 D ConnectivityService:    accepting network in place of null
10-05 13:52:19.481   931  2925 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-05 13:52:19.481   931  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-05 13:52:19.481   931  2928 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-05 13:52:19.501   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:52:19.523   509   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-05 13:52:19.526   931  2928 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-05 13:52:19.527   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-05 13:52:19.527  3680  3844 W QCNEJ   : |CORE| network available: 102
10-05 13:52:19.528   931  2928 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,10-05 13:52:19.529   931   948 D Tethering: MasterInitialState.processMessage what=3
,10-05 13:52:19.529  3680  3844 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-05 13:52:19.530  3680  3844 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-05 13:52:19.531  3680  3844 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-05 13:52:19.537  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:52:19.537  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:19.537  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:19.537  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:19.537  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:19.537  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:19.537  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:52:19.537  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:52:19.539  5003  5025 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-05 13:52:19.539  5003  5025 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-05 13:52:19.540  5003  5025 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,10-05 13:52:19.540  5003  5025 E SarControlService: no key has been found,reset the power
10-05 13:52:19.540  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:19.540  5003  5040 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-05 13:52:19.540  5003  5040 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-05 13:52:19.540  5003  5040 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-05 13:52:19.540  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:52:19.541  5028  5028 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-05 13:52:19.544  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:52:19.544  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:19.544  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:19.544  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:19.544  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:19.544  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:19.544  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:52:19.544  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:52:19.545  5003  5040 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-05 13:52:19.545  5003  5040 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-05 13:52:19.545  5003  5040 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-05 13:52:19.546  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-05 13:52:19.546  5028  5028 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-05 13:52:19.546  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:19.549  3900  3900 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-05 13:52:19.549   931  5899 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:816::200e
10-05 13:52:19.550  5028  5042 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@441dcf4 HexData = [00000000f003000000000000ffffffff]
10-05 13:52:19.550  5028  5042 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:52:19.550  5028  5042 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-05 13:52:19.550  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:52:19.551  5003  5014 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-05 13:52:19.554  5028  5042 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@441dcf4 HexData = [00000000f103000000000000ffffffff]
,10-05 13:52:19.554  5028  5042 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-05 13:52:19.554  5028  5042 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-05 13:52:19.555  5028  5028 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-05 13:52:19.555  5003  5013 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-05 13:52:19.556  3900  3900 D SystemUpdateService: onCreate
10-05 13:52:19.560  3900  3900 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-05 13:52:19.571  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-05 13:52:19.578  3900  5366 I iu.UploadsManager: num queued entries: 0
,10-05 13:52:19.578  3900  5366 I iu.UploadsManager: num updated entries: 0
10-05 13:52:19.579  3900  5366 I iu.SyncManager: NEXT; no task
10-05 13:52:19.579  3900  5912 I SystemUpdateService: active receiver: enabled
,10-05 13:52:19.583  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-05 13:52:19.585  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-05 13:52:19.587  5710  5710 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-05 13:52:19.591  5710  5710 D SprintDMHelper: simOperator: 
10-05 13:52:19.591  5710  5710 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-05 13:52:19.603  3900  5912 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-05 13:52:19.608  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-05 13:52:19.608  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:19.608  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:19.608  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:19.608  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:19.608  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:19.608  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:52:19.608  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:52:19.609  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:19.610  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:19.610  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd53d81 removed from the list
10-05 13:52:19.610  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-05 13:52:19.610  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:19.610  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:19.614  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-05 13:52:19.614  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-05 13:52:19.617  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@851cf78 Bundle[{}]
10-05 13:52:19.618  5589  5635 I io.jxcore.node.LifeCycleMonitor: start: OK
10-05 13:52:19.618  5589  5635 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-05 13:52:19.618  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-05 13:52:19.619  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-05 13:52:19.619  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-05 13:52:19.620  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
10-05 13:52:19.623  3900  5912 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-05 13:52:19.623  3900  5912 I SystemUpdateService: now status is 0 (complete)
10-05 13:52:19.623  3900  5912 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-05 13:52:19.623  3900  5912 I SystemUpdateService: file has been verified
10-05 13:52:19.623  3900  5912 I SystemUpdateService: OTA package size = 21989297
10-05 13:52:19.624   931  5899 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 05 Oct 2016 17:52:19 GMT], X-Android-Received-Millis=[1475689939623], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475689939584]}
10-05 13:52:19.625   931  2928 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-05 13:52:19.625   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-05 13:52:19.625   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-05 13:52:19.625  5589  5635 I System.out: Running OutgoingSocketThread
10-05 13:52:19.626   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-05 13:52:19.627  5589  5922 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
10-05 13:52:19.627  5589  5922 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-05 13:52:19.629  3900  5912 I SystemUpdateService: showing system update notification
,10-05 13:52:19.639  3900  3900 D SystemUpdateService: onDestroy
,10-05 13:52:19.658   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:52:19.711  4978  5917 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-05 13:52:20.659   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:52:21.660   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:52:22.261   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:52:22.652  5589  5925 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,10-05 13:52:22.652  5589  5922 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,10-05 13:52:22.653  5589  5925 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-05 13:52:22.653  5589  5922 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-05 13:52:22.653  5589  5925 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 13:52:22.654  5589  5925 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 13:52:22.654  5589  5922 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 13:52:22.657  5589  5927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:52:22.657  5589  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 13:52:22.657  5589  5925 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,10-05 13:52:22.657  5589  5922 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-05 13:52:22.661  5589  5922 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-05 13:52:22.661   537   537 I ServiceManager: Waiting for service AtCmdFwd...
10-05 13:52:22.662  5589  5928 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:52:22.662  5589  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-05 13:52:22.664  5589  5928 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:52:22.664  5589  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 13:52:22.664  5589  5929 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:52:22.664  5589  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:22.664  5589  5928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:52:22.664  5589  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-05 13:52:22.665  5589  5928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:52:22.665  5589  5928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 13:52:22.666  5589  5928 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-05 13:52:22.666  5589  5927 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 163, thread name: IncomingSocketThread/Sender): Socket closed
10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:52:22.666  5589  5928 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:52:22.666  5589  5927 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 163, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:52:22.666  5589  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 13:52:22.666  5589  5928 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-05 13:52:22.666  5589  5930 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:52:22.666  5589  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:52:22.666  5589  5928 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,10-05 13:52:22.666  5589  5929 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:52:22.666  5589  5927 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,10-05 13:52:22.666  5589  5927 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-05 13:52:22.666  5589  5929 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
10-05 13:52:22.666  5589  5928 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:52:22.666  5589  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,10-05 13:52:22.666  5589  5927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:52:22.666  5589  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-05 13:52:22.667  5589  5929 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-05 13:52:22.667  5589  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-05 13:52:22.667  5589  5930 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:52:22.667  5589  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:22.667  5589  5930 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:52:22.667  5589  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:52:22.667  5589  5930 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:52:22.667  5589  5930 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 13:52:22.668  5589  5930 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 13:52:22.668  5589  5930 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 13:52:22.668  5589  5930 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:52:22.668  5589  5930 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,10-05 13:52:22.668  5589  5930 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
10-05 13:52:22.668  5589  5930 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-05 13:52:22.668  5589  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-05 13:52:23.662   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-05 13:52:24.492   931  5900 D NetlinkSocketObserver: NeighborEvent{elapsedMs=304343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-05 13:52:24.662   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-05 13:52:25.288   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:52:25.640  5589  5635 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 175)
,10-05 13:52:25.641  5589  5635 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-05 13:52:25.641  5589  5635 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,10-05 13:52:25.646  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:52:25.647  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94eae26 added. We now have 3 listener(s)
10-05 13:52:25.649  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 13:52:25.649  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:52:25.649  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.649  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.649  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f3ea67 added. We now have 4 listener(s)
,10-05 13:52:25.650  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:52:25.651  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 13:52:25.656  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:52:25.662  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:52:25.662  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:25.662  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:25.662  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:25.662  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:25.662  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.662  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:52:25.662  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:52:25.666  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-05 13:52:25.666  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:52:25.666  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:52:25.666  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1730bd added. We now have 4 listener(s)
10-05 13:52:25.668  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:52:25.668  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:52:25.668  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-05 13:52:25.668  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.668  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e786b2 added. We now have 5 listener(s)
10-05 13:52:25.668  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:52:25.669  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:52:25.669  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:52:25.669  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:52:25.669  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-05 13:52:25.669  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.669  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:52:25.669  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.669  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:25.669  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:52:25.669  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94eae26 removed from the list
10-05 13:52:25.669  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:52:25.669  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f3ea67 removed from the list
10-05 13:52:25.673  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:25.674  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:52:25.674  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:52:25.674  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.675  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:52:25.676  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:52:25.676  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.676  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.676  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f3ea67 not in the list
10-05 13:52:25.676  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.676  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.678  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.678  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:52:25.678  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:52:25.678  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e786b2 removed from the list
10-05 13:52:25.678  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.678  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.678  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.678  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.678  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:52:25.679  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1730bd removed from the list
,10-05 13:52:25.680  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:52:25.680  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4ac603 added. We now have 3 listener(s)
,10-05 13:52:25.681  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 13:52:25.681  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:52:25.681  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.682  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.682  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77d6980 added. We now have 4 listener(s)
10-05 13:52:25.682  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:52:25.683  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 13:52:25.686  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:52:25.691  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:52:25.691  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:25.691  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:25.691  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:25.691  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:25.691  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.691  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:52:25.691  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-05 13:52:25.692  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.693  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:52:25.693  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:52:25.693  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac35bfe added. We now have 4 listener(s)
10-05 13:52:25.694  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 13:52:25.695  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:52:25.695  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.695  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.695  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa9bf5f added. We now have 5 listener(s)
10-05 13:52:25.695  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:52:25.695  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:52:25.696  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:52:25.696  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:52:25.696  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:52:25.696  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 13:52:25.696  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:25.699  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:25.700  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-05 13:52:25.700  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 13:52:25.704  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 13:52:25.704  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 13:52:25.704  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 13:52:25.707  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 13:52:25.707  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:52:25.708  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:52:25.708  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:52:25.708  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-05 13:52:25.708  5589  5635 D BluetoothAdapter: STATE_ON
,10-05 13:52:25.711  5842  5853 D BtGatt.GattService: registerClient() - UUID=33c32954-3c6d-4b33-9af2-2f56f032566b
,10-05 13:52:25.712  5842  5858 D BtGatt.GattService: onClientRegistered() - UUID=33c32954-3c6d-4b33-9af2-2f56f032566b, clientIf=5
10-05 13:52:25.713  5589  5599 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 13:52:25.713  5842  5870 D BtGatt.GattService: start scan with filters
,10-05 13:52:25.717  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-05 13:52:25.717  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:52:25.717  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:52:25.717  5842  5861 D BtGatt.ScanManager: handling starting scan
10-05 13:52:25.717  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:52:25.717  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:52:25.717  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,10-05 13:52:25.717  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:52:25.719  5842  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed31d5
10-05 13:52:25.720  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:52:25.720  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:52:25.720  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:52:25.721  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-05 13:52:25.724  5589  5635 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-05 13:52:25.724  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-05 13:52:25.724  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-05 13:52:25.724  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.724  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 13:52:25.724  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.724  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-05 13:52:25.724  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:52:25.724  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:52:25.724  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:52:25.724  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 13:52:25.724  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:52:25.725  5589  5635 D BluetoothAdapter: STATE_ON
,10-05 13:52:25.726  5842  5858 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:52:25.726  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.727  5842  5853 D BtGatt.GattService: stopScan() - queue size =1
10-05 13:52:25.727  5842  5861 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 13:52:25.728  5842  5870 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 13:52:25.728  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:52:25.728  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-05 13:52:25.728  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:52:25.728  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:52:25.728  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:52:25.728  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:52:25.728  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:52:25.728  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:52:25.732  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:52:25.732  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:52:25.732  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:52:25.732  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:52:25.732  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:52:25.732  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:52:25.733  5842  5858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:52:25.733  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:52:25.734  5842  5861 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:52:25.734  5842  5861 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 13:52:25.735  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:52:25.735  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:52:25.735  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-05 13:52:25.737  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:52:25.737  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:52:25.737  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:52:25.737  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.737  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.737  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:52:25.737  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.737  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-05 13:52:25.737  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4ac603 removed from the list
10-05 13:52:25.737  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.737  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77d6980 removed from the list
10-05 13:52:25.737  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:52:25.738  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.738  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.738  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:52:25.741  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-05 13:52:25.741  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.741  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.741  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77d6980 not in the list
10-05 13:52:25.741  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.741  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.742  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.742  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:52:25.742  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-05 13:52:25.742  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa9bf5f removed from the list
10-05 13:52:25.742  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.742  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.742  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.742  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.742  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:52:25.743  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac35bfe removed from the list
10-05 13:52:25.743  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-05 13:52:25.743  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d4f27b added. We now have 3 listener(s)
10-05 13:52:25.745  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:52:25.745  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:52:25.745  5842  5858 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 13:52:25.745  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.745  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.745  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.745  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6aee898 added. We now have 4 listener(s)
,10-05 13:52:25.745  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:52:25.746  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-05 13:52:25.750  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:52:25.751  5842  5858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-05 13:52:25.751  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:52:25.754  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:52:25.754  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:25.754  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:25.754  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:25.754  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:25.754  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.754  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:52:25.754  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:52:25.756  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.756  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:52:25.756  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:52:25.756  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b4ecd6 added. We now have 4 listener(s)
10-05 13:52:25.757  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:52:25.757  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 13:52:25.757  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.758  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.758  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b63b57 added. We now have 5 listener(s)
10-05 13:52:25.758  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:52:25.758  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:52:25.758  5842  5858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:52:25.758  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.758  5842  5861 D BtGatt.ScanManager: stopping BLe Batch
10-05 13:52:25.758  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:25.759  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:52:25.759  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:52:25.759  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:52:25.759  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:52:25.759  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 13:52:25.761  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-05 13:52:25.762  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-05 13:52:25.762  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-05 13:52:25.764  5842  5858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 13:52:25.764  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.764  5842  5861 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 13:52:25.767  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 13:52:25.768  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 13:52:25.768  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 13:52:25.769  5842  5858 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-05 13:52:25.769  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.772  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-05 13:52:25.772  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:52:25.772  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:52:25.772  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:52:25.772  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-05 13:52:25.772  5589  5635 D BluetoothAdapter: STATE_ON
10-05 13:52:25.774  5842  5853 D BtGatt.GattService: registerClient() - UUID=a2dcaec9-d7c2-4591-8b7f-6b6e20a2d284
10-05 13:52:25.774  5842  5858 D BtGatt.GattService: onClientRegistered() - UUID=a2dcaec9-d7c2-4591-8b7f-6b6e20a2d284, clientIf=5
10-05 13:52:25.774  5589  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-05 13:52:25.774  5842  5883 D BtGatt.GattService: start scan with filters
,10-05 13:52:25.776  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-05 13:52:25.777  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:52:25.777  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:52:25.777  5842  5861 D BtGatt.ScanManager: handling starting scan
10-05 13:52:25.777  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:52:25.777  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:52:25.777  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:52:25.777  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:52:25.779  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 13:52:25.779  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:52:25.779  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:52:25.780  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-05 13:52:25.782  5842  5858 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:52:25.782  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:52:25.782  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.782  5589  5635 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-05 13:52:25.782  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:52:25.782  5842  5861 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-05 13:52:25.782  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:52:25.782  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:52:25.782  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.782  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.782  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-05 13:52:25.782  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-05 13:52:25.782  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:52:25.782  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d4f27b removed from the list
10-05 13:52:25.782  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.782  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6aee898 removed from the list
10-05 13:52:25.782  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:52:25.782  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:52:25.783  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.783  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-05 13:52:25.783  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.783  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-05 13:52:25.784  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:52:25.784  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.784  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.784  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6aee898 not in the list
10-05 13:52:25.784  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:52:25.784  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:52:25.784  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:52:25.784  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 13:52:25.784  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:52:25.785  5589  5635 D BluetoothAdapter: STATE_ON
,10-05 13:52:25.786  5842  5852 D BtGatt.GattService: stopScan() - queue size =1
,10-05 13:52:25.787  5842  5878 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-05 13:52:25.787  5842  5858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:52:25.787  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.787  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:52:25.787  5842  5861 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:52:25.787  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 13:52:25.787  5842  5861 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 13:52:25.787  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:52:25.787  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:52:25.787  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:52:25.787  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:52:25.787  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:52:25.788  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:52:25.789  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-05 13:52:25.789  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-05 13:52:25.789  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:52:25.789  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:52:25.789  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-05 13:52:25.789  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.790  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.790  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:52:25.790  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.790  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:52:25.790  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b63b57 removed from the list
,10-05 13:52:25.790  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.790  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:52:25.790  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.791  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.791  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:52:25.791  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.791  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:52:25.791  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b4ecd6 removed from the list
10-05 13:52:25.791  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:52:25.791  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f935f3 added. We now have 3 listener(s)
10-05 13:52:25.792  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:52:25.793  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:52:25.793  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.793  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.793  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97e32b0 added. We now have 4 listener(s)
10-05 13:52:25.793  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:52:25.793  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:52:25.796  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-05 13:52:25.796  5842  5858 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 13:52:25.796  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:52:25.800  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:52:25.800  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:25.800  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:25.800  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:25.800  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:25.800  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.800  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:52:25.800  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:52:25.800  5842  5858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-05 13:52:25.800  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:52:25.802  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.802  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-05 13:52:25.802  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:52:25.802  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67cc0ae added. We now have 4 listener(s)
10-05 13:52:25.803  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:52:25.803  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:52:25.803  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.803  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.803  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a673e4f added. We now have 5 listener(s)
10-05 13:52:25.803  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:52:25.804  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:52:25.804  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-05 13:52:25.804  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-05 13:52:25.804  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:52:25.804  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-05 13:52:25.804  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:25.806  5842  5858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:52:25.806  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.806  5842  5861 D BtGatt.ScanManager: stopping BLe Batch
10-05 13:52:25.806  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:25.807  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-05 13:52:25.808  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-05 13:52:25.811  5842  5858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-05 13:52:25.811  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.811  5842  5861 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-05 13:52:25.812  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-05 13:52:25.813  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-05 13:52:25.813  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-05 13:52:25.815  5842  5858 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-05 13:52:25.815  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.816  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-05 13:52:25.816  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-05 13:52:25.816  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-05 13:52:25.816  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-05 13:52:25.816  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-05 13:52:25.816  5589  5635 D BluetoothAdapter: STATE_ON
,10-05 13:52:25.818  5842  5883 D BtGatt.GattService: registerClient() - UUID=b4f336c2-b1b2-4ab5-8560-0bba20515feb
10-05 13:52:25.818  5842  5858 D BtGatt.GattService: onClientRegistered() - UUID=b4f336c2-b1b2-4ab5-8560-0bba20515feb, clientIf=5
,10-05 13:52:25.819  5589  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-05 13:52:25.819  5842  5870 D BtGatt.GattService: start scan with filters
10-05 13:52:25.821  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-05 13:52:25.821  5842  5861 D BtGatt.ScanManager: handling starting scan
10-05 13:52:25.821  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-05 13:52:25.821  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-05 13:52:25.821  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-05 13:52:25.821  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-05 13:52:25.821  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-05 13:52:25.821  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-05 13:52:25.823  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-05 13:52:25.823  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-05 13:52:25.823  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-05 13:52:25.824  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-05 13:52:25.825  5842  5858 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-05 13:52:25.825  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.826  5842  5861 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-05 13:52:25.827  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-05 13:52:25.827  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:52:25.827  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:52:25.828  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.828  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.828  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-05 13:52:25.828  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.828  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-05 13:52:25.828  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f935f3 removed from the list
10-05 13:52:25.828  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.828  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97e32b0 removed from the list
10-05 13:52:25.828  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:52:25.828  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:52:25.828  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.828  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-05 13:52:25.828  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.829  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:52:25.829  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:52:25.829  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.829  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.829  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97e32b0 not in the list
10-05 13:52:25.829  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-05 13:52:25.829  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-05 13:52:25.829  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-05 13:52:25.830  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-05 13:52:25.830  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-05 13:52:25.830  5842  5858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-05 13:52:25.830  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.830  5842  5861 D BtGatt.ScanManager: Starting BLE batch scan
10-05 13:52:25.830  5842  5861 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-05 13:52:25.830  5589  5635 D BluetoothAdapter: STATE_ON
10-05 13:52:25.831  5842  5883 D BtGatt.GattService: stopScan() - queue size =1
10-05 13:52:25.831  5842  5870 D BtGatt.GattService: unregisterClient() - clientIf=5
10-05 13:52:25.831  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-05 13:52:25.831  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-05 13:52:25.832  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-05 13:52:25.832  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-05 13:52:25.832  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-05 13:52:25.832  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-05 13:52:25.832  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateSta,te: State changed from [SCANNING] to [NOT_STARTED]
10-05 13:52:25.832  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-05 13:52:25.832  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:52:25.833  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-05 13:52:25.833  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-05 13:52:25.833  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-05 13:52:25.833  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-05 13:52:25.833  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.834  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-05 13:52:25.834  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:52:25.834  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.834  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:52:25.834  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a673e4f removed from the list
10-05 13:52:25.834  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.834  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-05 13:52:25.834  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.834  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.834  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-05 13:52:25.834  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.834  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:52:25.835  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67cc0ae removed from the list
10-05 13:52:25.835  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:52:25.835  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@703706b added. We now have 3 listener(s)
10-05 13:52:25.836  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-05 13:52:25.836  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-05 13:52:25.837  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.837  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.837  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@679a7c8 added. We now have 4 listener(s)
10-05 13:52:25.837  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-05 13:52:25.837  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-05 13:52:25.838  5842  5858 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-05 13:52:25.838  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.839  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-05 13:52:25.843  5842  5858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-05 13:52:25.843  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-05 13:52:25.848  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-05 13:52:25.848  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-05 13:52:25.848  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-05 13:52:25.848  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-05 13:52:25.848  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-05 13:52:25.848  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.848  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-05 13:52:25.848  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-05 13:52:25.849  5842  5858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-05 13:52:25.849  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.849  5842  5861 D BtGatt.ScanManager: stopping BLe Batch
,10-05 13:52:25.851  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-05 13:52:25.851  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-05 13:52:25.851  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-05 13:52:25.851  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7403786 added. We now have 4 listener(s)
,10-05 13:52:25.853  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-05 13:52:25.853  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-05 13:52:25.853  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:25.853  5842  5858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-05 13:52:25.853  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.853  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-05 13:52:25.853  5842  5861 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-05 13:52:25.853  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-05 13:52:25.853  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee6a847 added. We now have 5 listener(s)
10-05 13:52:25.854  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-05 13:52:25.854  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-05 13:52:25.854  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:52:25.854  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-05 13:52:25.854  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.854  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.854  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-05 13:52:25.854  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.854  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:52:25.854  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@703706b removed from the list
10-05 13:52:25.855  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.855  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@679a7c8 removed from the list
10-05 13:52:25.856  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-05 13:52:25.856  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-05 13:52:25.856  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.857  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-05 13:52:25.857  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:52:25.858  5842  5858 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-05 13:52:25.858  5842  5858 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-05 13:52:25.858  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:52:25.858  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.858  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.858  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@679a7c8 not in the list
10-05 13:52:25.858  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:52:25.858  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-05 13:52:25.859  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-05 13:52:25.859  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-05 13:52:25.860  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-05 13:52:25.860  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee6a847 removed from the list
10-05 13:52:25.860  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-05 13:52:25.860  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-05 13:52:25.860  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-05 13:52:25.860  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-05 13:52:25.860  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-05 13:52:25.860  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7403786 removed from the list
,10-05 13:52:25.861  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-05 13:52:25.861  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-05 13:52:25.861  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-05 13:52:25.861  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-05 13:52:25.862  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-05 13:52:25.862  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-05 13:52:26.235  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:52:26.291  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:52:26.335  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-05 13:52:27.483   931  2928 D ConnectivityService: handlePromptUnvalidated 102
,10-05 13:52:28.000  5589  5931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 13:52:28.000  5589  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:28.807  5589  5931 W !!      : call onHalfStreamCopied
,10-05 13:52:28.807  5589  5931 I testCopyDataAndClose: closing input stream
,10-05 13:52:29.584  5589  5931 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 13:52:29.584  5589  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-05 13:52:29.585  5589  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-05 13:52:30.415   931  2925 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,10-05 13:52:33.336  5589  5932 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:52:33.336  5589  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:35.335  5589  5635 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 187. Connection data: Peer properties: [null null].
10-05 13:52:35.335  5589  5635 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:35.336  5589  5635 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 187, name: My test thread name)
,10-05 13:52:35.405  5589  5932 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-05 13:52:35.405  5589  5932 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:52:35.405  5589  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,10-05 13:52:35.456  5589  5933 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 13:52:35.456  5589  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-05 13:52:37.124  5589  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-05 13:52:40.894  5589  5934 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:52:40.894  5589  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-05 13:52:40.895  5589  5934 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:52:40.895  5589  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:52:40.895  5589  5934 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-05 13:52:40.895  5589  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:52:40.895  5589  5934 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-05 13:52:40.895  5589  5934 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-05 13:52:40.896  5589  5934 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-05 13:52:40.896  5589  5934 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-05 13:52:40.896  5589  5934 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-05 13:52:40.896  5589  5934 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:52:40.896  5589  5934 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-05 13:52:40.898  5589  5635 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-05 13:52:40.901  5589  5935 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:52:40.901  5589  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-05 13:52:40.901  5589  5935 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 195, thread name: My test thread name): Test exception.
,10-05 13:52:40.902  5589  5935 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:52:40.902  5589  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-05 13:52:40.902  5589  5935 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-05 13:52:40.903  5589  5935 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
10-05 13:52:40.903  5589  5935 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-05 13:52:40.906  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Total number of executed tests:  83'
10-05 13:52:40.906  5589  5635 I jxcore-log: 
,10-05 13:52:40.906  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-05 13:52:40.906  5589  5635 I jxcore-log: 
10-05 13:52:40.907  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Number of failed tests:  1'
10-05 13:52:40.907  5589  5635 I jxcore-log: 
10-05 13:52:40.907  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-05 13:52:40.907  5589  5635 I jxcore-log: 
10-05 13:52:40.907  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Total duration:  96838'
10-05 13:52:40.907  5589  5635 I jxcore-log: 
10-05 13:52:40.908  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Failures: 
10-05 13:52:40.908  5589  5635 I jxcore-log:  IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
10-05 13:52:40.908  5589  5635 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
10-05 13:52:40.908  5589  5635 I jxcore-log:      but: was ""
10-05 13:52:40.908  5589  5635 I jxcore-log: '
10-05 13:52:40.908  5589  5635 I jxcore-log: 
,10-05 13:52:40.909  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-05 13:52:40.909  5589  5635 I jxcore-log: 
10-05 13:52:40.910  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-05 13:52:40.910  5589  5635 I jxcore-log: 
,10-05 13:52:40.913  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.913  5589  5635 I jxcore-log: 
10-05 13:52:40.914  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.914  5589  5635 I jxcore-log: 
,10-05 13:52:40.914  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.914  5589  5635 I jxcore-log: 
10-05 13:52:40.914  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.914  5589  5635 I jxcore-log: 
10-05 13:52:40.915  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-05 13:52:40.915  5589  5635 I jxcore-log: 
10-05 13:52:40.915  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:52:40.915  5589  5635 I jxcore-log: 
10-05 13:52:40.915  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.915  5589  5635 I jxcore-log: 
10-05 13:52:40.916  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.916  5589  5635 I jxcore-log: 
10-05 13:52:40.916  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-05 13:52:40.916  5589  5635 I jxcore-log: 
10-05 13:52:40.916  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:52:40.916  5589  5635 I jxcore-log: 
,10-05 13:52:40.916  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:52:40.916  5589  5635 I jxcore-log: 
10-05 13:52:40.917  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.917  5589  5635 I jxcore-log: 
10-05 13:52:40.917  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.917  5589  5635 I jxcore-log: 
10-05 13:52:40.917  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.917  5589  5635 I jxcore-log: 
10-05 13:52:40.917  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:52:40.917  5589  5635 I jxcore-log: 
10-05 13:52:40.918  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:52:40.918  5589  5635 I jxcore-log: 
10-05 13:52:40.918  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:52:40.918  5589  5635 I jxcore-log: 
10-05 13:52:40.918  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.918  5589  5635 I jxcore-log: 
10-05 13:52:40.918  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.918  5589  5635 I jxcore-log: 
10-05 13:52:40.919  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.919  5589  5635 I jxcore-log: 
10-05 13:52:40.919  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:52:40.919  5589  5635 I jxcore-log: 
,10-05 13:52:40.919  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:52:40.919  5589  5635 I jxcore-log: 
10-05 13:52:40.921  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-05 13:52:40.921  5589  5635 I jxcore-log: 
10-05 13:52:40.921  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.921  5589  5635 I jxcore-log: 
10-05 13:52:40.921  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.921  5589  5635 I jxcore-log: 
10-05 13:52:40.922  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.922  5589  5635 I jxcore-log: 
10-05 13:52:40.922  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.922  5589  5635 I jxcore-log: 
,10-05 13:52:40.922  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.922  5589  5635 I jxcore-log: 
10-05 13:52:40.922  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.922  5589  5635 I jxcore-log: 
10-05 13:52:40.923  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.923  5589  5635 I jxcore-log: 
10-05 13:52:40.923  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.923  5589  5635 I jxcore-log: 
10-05 13:52:40.923  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.923  5589  5635 I jxcore-log: 
10-05 13:52:40.923  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.923  5589  5635 I jxcore-log: 
,10-05 13:52:40.924  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.924  5589  5635 I jxcore-log: 
10-05 13:52:40.924  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.924  5589  5635 I jxcore-log: 
10-05 13:52:40.924  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.924  5589  5635 I jxcore-log: 
10-05 13:52:40.924  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.924  5589  5635 I jxcore-log: 
10-05 13:52:40.924  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-05 13:52:40.924  5589  5635 I jxcore-log: 
10-05 13:52:40.925  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-05 13:52:40.925  5589  5635 I jxcore-log: 
,10-05 13:52:40.925  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-05 13:52:40.925  5589  5635 I jxcore-log: 
10-05 13:52:40.925  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.925  5589  5635 I jxcore-log: 
10-05 13:52:40.925  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.925  5589  5635 I jxcore-log: 
10-05 13:52:40.926  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.926  5589  5635 I jxcore-log: 
10-05 13:52:40.926  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.926  5589  5635 I jxcore-log: 
10-05 13:52:40.926  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.926  5589  5635 I jxcore-log: 
10-05 13:52:40.926  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-05 13:52:40.926  5589  5635 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-05 13:52:40.926  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.926  5589  5635 I jxcore-log: 
10-05 13:52:40.927  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.927  5589  5635 I jxcore-log: 
10-05 13:52:40.927  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-05 13:52:40.927  5589  5635 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-05 13:52:40.927  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-05 13:52:40.927  5589  5635 I jxcore-log: 
10-05 13:52:40.927  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:52:40.927  5589  5635 I jxcore-log: 
10-05 13:52:40.927  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:52:40.927  5589  5635 I jxcore-log: 
,10-05 13:52:40.928  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-05 13:52:40.928  5589  5635 I jxcore-log: 
,10-05 13:52:40.933  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-05 13:52:40.933  5589  5635 I jxcore-log: 
10-05 13:52:40.934  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - WARN testUtils: 'myNameCallback not set!'
10-05 13:52:40.934  5589  5635 I jxcore-log: 
10-05 13:52:40.934  5589  5635 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-05 13:52:40.935  5589  5635 I jxcore-log: 2016-10-05 17:52:40 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-05 13:52:40.935  5589  5635 I jxcore-log: 
10-05 13:52:40.936  5589  5589 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-05 13:52:41.385  5589  5635 I jxcore-log: 2016-10-05 17:52:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-05 13:52:41.385  5589  5635 I jxcore-log: 
,10-05 13:52:41.759  5589  5635 I jxcore-log: 2016-10-05 17:52:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-05 13:52:41.759  5589  5635 I jxcore-log: 
,10-05 13:52:41.775  5589  5635 I jxcore-log: 2016-10-05 17:52:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-05 13:52:41.775  5589  5635 I jxcore-log: 
,10-05 13:52:42.877  5589  5635 I jxcore-log: 2016-10-05 17:52:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-05 13:52:42.877  5589  5635 I jxcore-log: 
,10-05 13:52:43.041  5589  5635 I jxcore-log: 2016-10-05 17:52:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-05 13:52:43.041  5589  5635 I jxcore-log: 
,10-05 13:52:43.045  5589  5635 I jxcore-log: 2016-10-05 17:52:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-05 13:52:43.045  5589  5635 I jxcore-log: 
,10-05 13:52:43.050  5589  5635 I jxcore-log: 2016-10-05 17:52:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-05 13:52:43.050  5589  5635 I jxcore-log: 
,10-05 13:52:43.423   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-05 13:52:43.583  5589  5635 I jxcore-log: 2016-10-05 17:52:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-05 13:52:43.583  5589  5635 I jxcore-log: 
,10-05 13:52:43.634  5589  5635 I jxcore-log: 2016-10-05 17:52:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-05 13:52:43.634  5589  5635 I jxcore-log: 
,10-05 13:52:43.647  5589  5635 I jxcore-log: 2016-10-05 17:52:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-05 13:52:43.647  5589  5635 I jxcore-log: 
,10-05 13:52:43.651  5589  5635 I jxcore-log: 2016-10-05 17:52:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-05 13:52:43.651  5589  5635 I jxcore-log: 
,10-05 13:52:44.065  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-05 13:52:44.065  5589  5635 I jxcore-log: 
,10-05 13:52:44.188  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-05 13:52:44.188  5589  5635 I jxcore-log: 
,10-05 13:52:44.413  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-05 13:52:44.413  5589  5635 I jxcore-log: 
,10-05 13:52:44.423  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-05 13:52:44.423  5589  5635 I jxcore-log: 
,10-05 13:52:44.427  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-05 13:52:44.427  5589  5635 I jxcore-log: 
,10-05 13:52:44.432  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-05 13:52:44.432  5589  5635 I jxcore-log: 
,10-05 13:52:44.438  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-05 13:52:44.438  5589  5635 I jxcore-log: 
,10-05 13:52:44.465  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-05 13:52:44.465  5589  5635 I jxcore-log: 
,10-05 13:52:44.499  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-05 13:52:44.499  5589  5635 I jxcore-log: 
,10-05 13:52:44.506  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-05 13:52:44.506  5589  5635 I jxcore-log: 
,10-05 13:52:44.513  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-05 13:52:44.513  5589  5635 I jxcore-log: 
,10-05 13:52:44.528  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-05 13:52:44.528  5589  5635 I jxcore-log: 
,10-05 13:52:44.533  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-05 13:52:44.533  5589  5635 I jxcore-log: 
,10-05 13:52:44.538  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-05 13:52:44.538  5589  5635 I jxcore-log: 
,10-05 13:52:44.543  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-05 13:52:44.543  5589  5635 I jxcore-log: 
,10-05 13:52:44.554  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-05 13:52:44.554  5589  5635 I jxcore-log: 
,10-05 13:52:44.573  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-05 13:52:44.573  5589  5635 I jxcore-log: 
,10-05 13:52:44.582  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-05 13:52:44.582  5589  5635 I jxcore-log: 
,10-05 13:52:44.593  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-05 13:52:44.593  5589  5635 I jxcore-log: 
,10-05 13:52:44.602  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-05 13:52:44.602  5589  5635 I jxcore-log: 
,10-05 13:52:44.613  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-05 13:52:44.613  5589  5635 I jxcore-log: 
,10-05 13:52:44.623  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-05 13:52:44.623  5589  5635 I jxcore-log: 
,10-05 13:52:44.629  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-05 13:52:44.629  5589  5635 I jxcore-log: 
,10-05 13:52:44.650  5589  5635 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-05 13:52:44.651  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - INFO testUtils: 'BLE multiple advertisement supported'
10-05 13:52:44.651  5589  5635 I jxcore-log: 
,10-05 13:52:44.691  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - DEBUG ServerClient: 'connecting to '85.14.110.168:3000''
10-05 13:52:44.691  5589  5635 I jxcore-log: 
,10-05 13:52:44.710  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - DEBUG ServerClient: 'connected to '85.14.110.168:3000''
10-05 13:52:44.710  5589  5635 I jxcore-log: 
,10-05 13:52:44.710  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - DEBUG CoordinatedClient: 'connected to the test server'
10-05 13:52:44.710  5589  5635 I jxcore-log: 
,10-05 13:52:44.785  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-05 13:52:44.785  5589  5635 I jxcore-log: 
,10-05 13:52:44.786  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - DEBUG CoordinatedClient: 'test client failed'
10-05 13:52:44.786  5589  5635 I jxcore-log: 
,10-05 13:52:44.792  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:152:20
10-05 13:52:44.792  5589  5635 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-05 13:52:44.792  5589  5635 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-05 13:52:44.792  5589  5635 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-05 13:52:44.792  5589  5635 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-05 13:52:44.792  5589  5635 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-05 13:52:44.792  5589  5635 I jxcore-log: 
,10-05 13:52:44.792  5589  5635 I jxcore-log: 2016-10-05 17:52:44 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-05 13:52:44.792  5589  5635 I jxcore-log: 
,10-05 13:52:45.329  5936  5936 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-05 13:52:45.335  5936  5936 D AndroidRuntime: CheckJNI is OFF
,10-05 13:52:45.370  5936  5936 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-05 13:52:45.404  5936  5936 I Radio-JNI: register_android_hardware_Radio DONE
,10-05 13:52:45.422  5936  5936 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-05 13:52:45.430   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-05 13:52:45.431   931   944 I ActivityManager: Killing 5589:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-05 13:52:45.531   931  3808 I WindowState: WIN DEATH: Window{437884b u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-05 13:52:45.531   931  3536 D GraphicsStats: Buffer count: 2
,10-05 13:52:45.533   931  2927 D WifiService: Client connection lost with reason: 4
,10-05 13:52:45.567   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-05 13:52:45.568   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-05 13:52:45.569   931   944 E ActivityManager: Failure starting process com.test.thalitest
10-05 13:52:45.569   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-05 13:52:45.569   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:52:45.569   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:52:45.569   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-05 13:52:45.569   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-05 13:52:45.569   931   944 I ActivityManager:   Force finishing activity ActivityRecord{fdab1dc u0 com.test.thalitest/.MainActivity t2}
10-05 13:52:45.570   931   954 I art     : Starting a blocking GC Explicit
,10-05 13:52:45.576   931  3516 W ActivityManager: Spurious death for ProcessRecord{6708c48 0:com.test.thalitest/u0a77}, curProc for 5589: null
,10-05 13:52:45.581   931   949 W WindowManager: Attempted to add application window with unknown token Token{e76f2e5 ActivityRecord{fdab1dc u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,10-05 13:52:45.581   931   949 W WindowManager: Token{e76f2e5 ActivityRecord{fdab1dc u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{e76f2e5 ActivityRecord{fdab1dc u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-05 13:52:45.581   931   949 W WindowManager: view not successfully added to wm, removing view
10-05 13:52:45.582   931   949 W WindowManager: Exception when adding starting window
10-05 13:52:45.582   931   949 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{f437863 V.E...... R.....ID 0,0-0,0} not attached to window manager
10-05 13:52:45.582   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-05 13:52:45.582   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-05 13:52:45.582   931   949 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-05 13:52:45.582   931   949 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-05 13:52:45.582   931   949 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-05 13:52:45.582   931   949 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:52:45.582   931   949 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:52:45.582   931   949 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-05 13:52:45.582   931   949 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-05 13:52:45.653   931   954 I art     : Explicit concurrent mark sweep GC freed 53842(3MB) AllocSpace objects, 16(556KB) LOS objects, 33% free, 29MB/43MB, paused 1.501ms total 82.258ms
,10-05 13:52:45.677   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-05 13:52:45.680  5936  5936 I art     : System.exit called, status: 0
10-05 13:52:45.680  5936  5936 I AndroidRuntime: VM exiting with result code 0.
,10-05 13:52:45.690   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-05 13:52:45.698   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-05 13:52:45.702  5842  5842 D BluetoothMapAppObserver: onReceive
10-05 13:52:45.702  5842  5842 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-05 13:52:45.704  4068  4144 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-05 13:52:45.707  3606  3606 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-05 13:52:45.717   931  2892 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-05 13:52:45.730  3348  5948 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-05 13:52:45.733  3606  5947 I Keyboard.Facilitator.DecoderInitializer: run()
,10-05 13:52:45.758  3606  5947 I Decoder : createOrResetDecoder
,10-05 13:52:45.761  3725  3725 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-05 13:52:45.776  3522  3522 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-05 13:52:45.776  3522  3522 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-05 13:52:45.784   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-05 13:52:45.797  3900  5953 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-05 13:52:45.797  3900  5953 D AccountUtils: Clearing selected account for com.test.thalitest
,10-05 13:52:45.799  3522  3522 I ConfigService: onCreate
10-05 13:52:45.801    27    27 W kworker/1:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 13:52:45.804    27    27 W kworker/1:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 13:52:45.814    27    27 W kworker/1:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-05 13:52:45.822  3900  5953 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-05 13:52:45.838  3348  3370 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjB12C1890D) - 
,10-05 13:52:45.850  3606  5947 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-05 13:52:45.855  3900  5953 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:52:45.855  3900  5953 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:52:45.855  3900  5953 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-05 13:52:45.856  3900  5953 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-05 13:52:45.899  3348  5948 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
10-05 13:52:45.900  3348  5948 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-05 13:52:45.900  3348  5948 E AndroidRuntime: Process: android.process.acore, PID: 3348
10-05 13:52:45.900  3348  5948 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-05 13:52:45.900  3348  5948 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-05 13:52:45.905  3348  3370 I Process : Sending signal. PID: 3348 SIG: 9
,10-05 13:52:45.962  3900  5960 I GMPM-SVC: App measurement is starting up
,10-05 13:52:45.966  3900  5960 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-05 13:52:45.967  3900  5960 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-05 13:52:45.969   931  3819 I ActivityManager: Process android.process.acore (pid 3348) has died
10-05 13:52:45.969   931  3819 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-05 13:52:46.206   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
