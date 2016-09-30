#### Test 87463757544e7bf_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-30 07:25:02.380   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-30 07:25:02.380   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 07:25:02.859  5576  5576 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-30 07:25:02.865  5576  5576 D AndroidRuntime: CheckJNI is OFF
09-30 07:25:02.893  5576  5576 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-30 07:25:02.929  5576  5576 I Radio-JNI: register_android_hardware_Radio DONE
09-30 07:25:02.946  5576  5576 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-30 07:25:02.952   929  3551 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-30 07:25:03.000   929  3551 I ActivityManager: Start proc 5585:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-30 07:25:03.018  5576  5576 D AndroidRuntime: Shutting down VM
,09-30 07:25:03.345   929  3115 I WindowManager: Screenshot max retries 4 of Token{75c0ba1 ActivityRecord{7ce0808 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{e93d020 u0 Starting com.test.thalitest} drawState=2
,09-30 07:25:03.423  5585  5585 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-30 07:25:03.459  5585  5585 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-30 07:25:03.482  5585  5585 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 9697-9715)
,09-30 07:25:03.482  5585  5585 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 07:25:03.502  5585  5585 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {648435d}
,09-30 07:25:03.503  5585  5585 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 07:25:03.503  5585  5585 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-30 07:25:03.508  5585  5585 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-30 07:25:03.510  5585  5585 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-30 07:25:03.544  5585  5585 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-30 07:25:03.558  5585  5585 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-30 07:25:03.558  5585  5585 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-30 07:25:03.558  5585  5585 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-30 07:25:03.558  5585  5585 I Adreno  : Build Date                       : 12/06/15
09-30 07:25:03.558  5585  5585 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-30 07:25:03.558  5585  5585 I Adreno  : Local Branch                     : mybranch17112971
09-30 07:25:03.558  5585  5585 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-30 07:25:03.558  5585  5585 I Adreno  : Remote Branch                    : NONE
09-30 07:25:03.558  5585  5585 I Adreno  : Reconstruct Branch               : NOTHING
,09-30 07:25:03.607   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a590e77:true
,09-30 07:25:03.639  2901  2901 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22492]" dev="sockfs" ino=22492 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 07:25:03.639  2901  2901 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22492]" dev="sockfs" ino=22492 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 07:25:03.652  5585  5585 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-30 07:25:03.661  5585  5585 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-30 07:25:03.685   404   404 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33005]" dev="sockfs" ino=33005 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 07:25:03.685   404   404 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33005]" dev="sockfs" ino=33005 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 07:25:03.689  3772  3772 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31824]" dev="sockfs" ino=31824 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-30 07:25:03.689  3772  3772 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31824]" dev="sockfs" ino=31824 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 07:25:03.693  5585  5609 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-30 07:25:03.717  5585  5622 I OpenGLRenderer: Initialized EGL, version 1.4
,09-30 07:25:03.795   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +447ms (total +825ms)
,09-30 07:25:03.841  5585  5585 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5585
,09-30 07:25:03.927  5585  5585 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-30 07:25:04.087  5585  5624 D jxcore_app_log: JniHelper::setJavaVM(0xf4ebc000), pthread_self() = -566494928
,09-30 07:25:04.091  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-30 07:25:04.091  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-30 07:25:04.091  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-30 07:25:04.091  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-30 07:25:04.091  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-30 07:25:04.091  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d72ea added. We now have 1 listener(s)
,09-30 07:25:04.094  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-30 07:25:04.095  5585  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 07:25:04.095  5585  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 07:25:04.095  5585  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-30 07:25:04.098  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15c3f51 added. We now have 1 listener(s)
09-30 07:25:04.098  5585  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 07:25:04.106   929  2908 D WifiService: New client listening to asynchronous messages
,09-30 07:25:04.107  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 07:25:04.107  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-30 07:25:04.107  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-30 07:25:04.107  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-30 07:25:04.107  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-30 07:25:04.109  5585  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:25:04.109  5585  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-30 07:25:04.114  5585  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-30 07:25:04.114  5585  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:25:04.114  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:04.114  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:04.114  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:04.114  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:25:04.114  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:04.114  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:04.114  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:04.114  5585  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-30 07:25:04.114  5585  5624 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 07:25:04.114  5585  5624 I io.jxcore.node.LifeCycleMonitor: start: OK
09-30 07:25:04.117  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:04.120  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:04.135  5585  5585 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-30 07:25:04.415  5585  5631 W jxcore-log: Initializing JXcore engine
09-30 07:25:04.415  5585  5631 W jxcore-log: JXcore engine is ready
,09-30 07:25:04.439  5631  5631 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12025 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-30 07:25:04.439  5631  5631 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15459]" dev="sockfs" ino=15459 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-30 07:25:04.439  5631  5631 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-30 07:25:04.439  5631  5631 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34120]" dev="sockfs" ino=34120 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-30 07:25:04.447  5585  5631 W jxcore-log: Starting JXcore engine
,09-30 07:25:04.495  5585  5631 W jxcore-log: Platform android
09-30 07:25:04.495  5585  5631 W jxcore-log: 
,09-30 07:25:04.496  5585  5631 W jxcore-log: Process ARCH arm
09-30 07:25:04.496  5585  5631 W jxcore-log: 
,09-30 07:25:04.592  5585  5631 I jxcore-log: JXcore Cordova bridge is ready!
09-30 07:25:04.592  5585  5631 I jxcore-log: 
,09-30 07:25:04.592  5585  5631 W jxcore-log: JXcore engine is started
,09-30 07:25:04.605  5585  5624 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-30 07:25:04.613  5585  5585 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-30 07:25:04.856   929  2906 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 07:25:12.381   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:12.694   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 07:25:13.383   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:14.384   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:14.445  5585  5631 I jxcore-log: 2016-09-30 11:25:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 07:25:14.445  5585  5631 I jxcore-log: 
,09-30 07:25:14.447  5585  5631 I jxcore-log: 2016-09-30 11:25:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 07:25:14.447  5585  5631 I jxcore-log: 
,09-30 07:25:14.451  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:25:14.451  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:14.451  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:14.451  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:14.451  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:25:14.451  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:14.451  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:14.451  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:25:14.452  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 07:25:14.454  5585  5631 I jxcore-log: 2016-09-30 11:25:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 07:25:14.454  5585  5631 I jxcore-log: 
09-30 07:25:14.455  5585  5631 I jxcore-log: 2016-09-30 11:25:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 07:25:14.455  5585  5631 I jxcore-log: 
,09-30 07:25:14.709  5585  5631 I jxcore-log: 2016-09-30 11:25:14 - DEBUG UnitTest_app: 'Running unit tests'
09-30 07:25:14.709  5585  5631 I jxcore-log: 
,09-30 07:25:14.710  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 07:25:14.710  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@877feff added. We now have 2 listener(s)
,09-30 07:25:14.711  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 07:25:14.711  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 07:25:14.711  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:25:14.711  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:25:14.711  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30374cc added. We now have 2 listener(s)
,09-30 07:25:14.711  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:25:14.712  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 07:25:14.714  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:25:14.720  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:25:14.720  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:14.720  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:14.720  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:14.720  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:25:14.720  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:14.720  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:14.720  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:25:14.725  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 07:25:14.725  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:25:14.726  5585  5631 D executeNativeTests: Running unit tests
,09-30 07:25:14.731  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:14.735  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:14.764  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 07:25:14.764  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda added. We now have 3 listener(s)
,09-30 07:25:14.765  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 07:25:14.765  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:25:14.765  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 07:25:14.765  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:25:14.765  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b added. We now have 3 listener(s)
,09-30 07:25:14.765  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:25:14.765  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 07:25:14.767  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:25:14.769  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:25:14.769  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:14.769  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:14.769  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:14.769  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:25:14.769  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:14.769  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:14.769  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:14.770  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:14.770  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:25:14.771  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 07:25:14.771  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 07:25:14.771  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 07:25:14.771  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 07:25:14.772  5585  5631 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-30 07:25:14.772  5585  5631 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 07:25:14.772  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 07:25:14.772  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 07:25:14.772  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 07:25:14.772  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 07:25:14.772  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:14.773  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:14.773  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:14.773  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:14.773  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:14.773  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:25:14.773  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:14.773  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
0,9-30 07:25:14.773  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda removed from the list
09-30 07:25:14.773  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:14.773  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b removed from the list
09-30 07:25:14.774  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:14.779  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:14.780  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:14.780  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:14.781  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:14.781  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:14.781  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:14.781  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:14.782  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:14.782  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:14.782  5585  5631 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-30 07:25:14.783  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:14.783  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:14.783  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:14.783  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:14.783  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:14.783  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:14.783  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:14.783  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:14.783  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:14.783  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:14.783  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:14.783  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:14.783  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:14.783  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:14.783  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:14.784  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:14.784  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:14.784  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:14.784  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 07:25:14.786  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 07:25:14.787  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:14.787  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:14.787  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:14.787  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:14.787  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:14.787  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:14.787  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:14.787  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:14.787  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:14.787  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:14.787  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:14.787  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:14.787  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:14.787  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:14.788  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:14.788  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:14.788  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:14.788  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:14.788  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:14.788  5585  5631 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 07:25:14.790  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:25:14.794  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:25:14.794  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:14.794  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:14.794  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:14.794  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:25:14.794  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:14.794  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:14.794  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:14.797  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:14.797  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:25:14.797  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:25:14.797  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 07:25:14.798  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 07:25:14.798  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:25:14.798  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 07:25:14.800  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:14.804  5585  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 07:25:14.804  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 07:25:14.806  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:14.808  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 07:25:14.809  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 07:25:14.809  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 07:25:14.810  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-30 07:25:14.811  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-30 07:25:14.811  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 07:25:14.812  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 07:25:14.812  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 07:25:14.812  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 07:25:14.812  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 07:25:14.812  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:25:14.814  4542  4801 D BtGatt.GattService: registerClient() - UUID=a7e292ca-8acf-4fd1-9a11-fa88ab8db2c1
09-30 07:25:14.815  4542  4629 D BtGatt.GattService: onClientRegistered() - UUID=a7e292ca-8acf-4fd1-9a11-fa88ab8db2c1, clientIf=5
,09-30 07:25:14.817  5585  5595 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 07:25:14.818  4542  4557 D BtGatt.GattService: start scan with filters
09-30 07:25:14.821  4542  4634 D BtGatt.ScanManager: handling starting scan
09-30 07:25:14.821  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 07:25:14.821  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 07:25:14.821  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:25:14.821  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 07:25:14.822  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 07:25:14.822  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 07:25:14.822  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 07:25:14.822  4542  4634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:25:14.823  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 07:25:14.823  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 07:25:14.824  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 07:25:14.824  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 07:25:14.825  5585  5631 I io.jxcore.node.ConnectionHelper: start: OK
09-30 07:25:14.829  4542  4629 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 07:25:14.829  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:14.830  4542  4634 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 07:25:14.836  4542  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 07:25:14.836  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:14.836  4542  4634 D BtGatt.ScanManager: Starting BLE batch scan
09-30 07:25:14.836  4542  4634 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 07:25:14.848  4542  4629 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 07:25:14.848  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:14.853  4542  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 07:25:14.853  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:25:15.325  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 07:25:15.326  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:25:15.326  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 07:25:15.385   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:15.723   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 07:25:15.727   929  2914 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-30 07:25:16.386   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:17.387   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 07:25:18.747   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 07:25:18.750   929  2914 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-30 07:25:19.829  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 07:25:19.830  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:19.830  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 07:25:19.830  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:25:19.830  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 07:25:19.830  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:19.830  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 07:25:19.830  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 07:25:19.830  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 07:25:19.830  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 07:25:19.831  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-30 07:25:19.831  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 07:25:19.832  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:25:19.833  4542  4801 D BtGatt.GattService: stopScan() - queue size =1
09-30 07:25:19.834  4542  4557 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 07:25:19.834  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 07:25:19.835  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-30 07:25:19.835  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 07:25:19.835  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:25:19.835  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 07:25:19.835  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 07:25:19.835  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-30 07:25:19.835  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 07:25:19.836  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:25:19.837  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-30 07:25:19.837  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 07:25:19.837  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 07:25:19.837  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 07:25:19.838  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:25:19.839  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:19.840  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:19.840  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:25:19.840  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:25:19.840  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 07:25:19.840  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:19.840  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:19.840  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:25:19.840  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:19.840  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:19.840  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 07:25:19.840  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:19.842  4542  4542 D BtGatt.ScanManager: awakened up at time 236075
,09-30 07:25:19.851  4542  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 07:25:19.851  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:25:19.852  4542  4634 D BtGatt.ScanManager: stopping BLe Batch
,09-30 07:25:19.862  4542  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 07:25:19.862  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:19.862  4542  4634 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 07:25:19.887  4542  4629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-30 07:25:19.887  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:19.887  4542  4629 D BtGatt.GattService: current time is 236121410914
09-30 07:25:19.888  4542  4629 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -79, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -74, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 123, -16, -50, 30, 32, 81, 1, -128, -99, 69, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 81, 34, 97, 112, -14, -5, 1, -128, -76, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -76, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-30 07:25:19.890  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 07:25:19.891  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-30 07:25:19.892  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 07:25:19.892  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
09-30 07:25:19.892  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 07:25:19.892  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 07:25:19.894  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 07:25:20.342  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 07:25:22.388   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:23.389   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:24.391   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:24.810   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 07:25:24.842  5585  5631 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 07:25:24.844  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:25:24.849  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:25:24.849  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:24.849  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:24.849  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:24.849  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:25:24.849  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:24.849  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:24.849  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:25:24.852  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 07:25:24.852  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:25:24.852  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 07:25:24.853  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 07:25:24.853  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 07:25:24.853  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:25:24.853  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 07:25:24.857  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:24.860  5585  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 07:25:24.860  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 07:25:24.862  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:24.871  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 07:25:24.872  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-30 07:25:24.872  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 07:25:24.878  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 07:25:24.878  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 07:25:24.878  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 07:25:24.878  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-30 07:25:24.878  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-30 07:25:24.879  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:25:24.882  4542  4801 D BtGatt.GattService: registerClient() - UUID=51d3d862-643a-417c-a2c5-b334cf111925
,09-30 07:25:24.883  4542  4629 D BtGatt.GattService: onClientRegistered() - UUID=51d3d862-643a-417c-a2c5-b334cf111925, clientIf=5
,09-30 07:25:24.883  5585  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 07:25:24.884  4542  4557 D BtGatt.GattService: start scan with filters
09-30 07:25:24.886  4542  4634 D BtGatt.ScanManager: handling starting scan
,09-30 07:25:24.886  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 07:25:24.887  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 07:25:24.887  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:25:24.887  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 07:25:24.887  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 07:25:24.887  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 07:25:24.887  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 07:25:24.890  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 07:25:24.890  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 07:25:24.890  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 07:25:24.892  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 07:25:24.894  5585  5631 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 07:25:24.897  4542  4629 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 07:25:24.897  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:24.897  4542  4634 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 07:25:24.898  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:24.898  5585  5631 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-30 07:25:24.898  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:25:24.898  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 07:25:24.898  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:24.898  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 07:25:24.898  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:24.898  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 07:25:24.898  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 07:25:24.898  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 07:25:24.898  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 07:25:24.898  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 07:25:24.898  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 07:25:24.899  5585  5631 D BluetoothAdapter: STATE_ON
,09-30 07:25:24.900  4542  4557 D BtGatt.GattService: stopScan() - queue size =1
09-30 07:25:24.901  4542  4555 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 07:25:24.901  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 07:25:24.901  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 07:25:24.901  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 07:25:24.901  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:25:24.901  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 07:25:24.901  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 07:25:24.901  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 07:25:24.901  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 07:25:24.902  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:25:24.903  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 07:25:24.903  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 07:25:24.903  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 07:25:24.903  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 07:25:24.903  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:25:24.905  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:25:24.905  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:24.905  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:24.905  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:25:24.905  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:25:24.905  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 07:25:24.905  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:24.905  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:24.905  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:24.905  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:24.905  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:24.905  4542  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 07:25:24.905  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:24.905  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:24.906  4542  4634 D BtGatt.ScanManager: Starting BLE batch scan
,09-30 07:25:24.906  4542  4634 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 07:25:24.906  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:24.906  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:24.907  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:25:24.907  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:24.907  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:24.907  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:24.908  5585  5631 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 07:25:24.910  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:25:24.916  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:25:24.916  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:24.916  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:24.916  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:24.916  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:25:24.916  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:24.916  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:24.916  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:25:24.918  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:24.919  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:25:24.919  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 07:25:24.919  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 07:25:24.919  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 07:25:24.919  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:25:24.919  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 07:25:24.919  4542  4629 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 07:25:24.919  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:25:24.922  5585  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 07:25:24.922  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 07:25:24.922  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:24.925  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:24.925  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 07:25:24.926  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 07:25:24.926  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 07:25:24.927  4542  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 07:25:24.927  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:24.929  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 07:25:24.929  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 07:25:24.929  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 07:25:24.929  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-30 07:25:24.929  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 07:25:24.930  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:25:24.933  4542  4801 D BtGatt.GattService: registerClient() - UUID=071daf8e-c968-4622-ba41-e423f5da2058
09-30 07:25:24.934  4542  4629 D BtGatt.GattService: onClientRegistered() - UUID=071daf8e-c968-4622-ba41-e423f5da2058, clientIf=5
,09-30 07:25:24.935  5585  5595 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 07:25:24.936  4542  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 07:25:24.936  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:24.936  4542  4557 D BtGatt.GattService: start scan with filters
09-30 07:25:24.936  4542  4634 D BtGatt.ScanManager: stopping BLe Batch
09-30 07:25:24.938  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 07:25:24.938  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 07:25:24.938  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:25:24.938  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 07:25:24.938  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 07:25:24.938  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 07:25:24.938  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 07:25:24.941  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 07:25:24.941  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 07:25:24.941  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 07:25:24.941  4542  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 07:25:24.941  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:24.941  4542  4634 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 07:25:24.942  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 07:25:24.946  5585  5631 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 07:25:24.947  4542  4629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 07:25:24.947  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:25:24.948  4542  4634 D BtGatt.ScanManager: handling starting scan
,09-30 07:25:24.954  4542  4629 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 07:25:24.954  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:24.954  4542  4634 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 07:25:24.960  4542  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 07:25:24.960  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:24.960  4542  4634 D BtGatt.ScanManager: Starting BLE batch scan
,09-30 07:25:24.960  4542  4634 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 07:25:24.970  4542  4629 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 07:25:24.970  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:25:24.975  4542  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 07:25:24.975  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:25:25.392   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:25.442  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-30 07:25:25.442  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 07:25:25.442  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 07:25:26.393   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:27.393   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 07:25:27.831   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 07:25:27.838   929  2914 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-30 07:25:29.946  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 07:25:29.947  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:29.947  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 07:25:29.947  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:25:29.947  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 07:25:29.947  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:29.947  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-30 07:25:29.947  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 07:25:29.948  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 07:25:29.948  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 07:25:29.948  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-30 07:25:29.948  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 07:25:29.950  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:25:29.951  4542  4555 D BtGatt.GattService: stopScan() - queue size =1
09-30 07:25:29.953  4542  4780 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 07:25:29.954  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 07:25:29.955  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 07:25:29.955  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 07:25:29.955  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:25:29.955  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 07:25:29.955  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 07:25:29.956  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 07:25:29.956  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 07:25:29.959  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:25:29.959  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 07:25:29.959  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 07:25:29.959  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 07:25:29.960  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 07:25:29.961  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:25:29.965  4542  4542 D BtGatt.ScanManager: awakened up at time 246198
09-30 07:25:29.968  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:25:29.968  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 07:25:29.969  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 07:25:29.973  4542  4629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-30 07:25:29.973  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:29.973  4542  4634 D BtGatt.ScanManager: stopping BLe Batch
,09-30 07:25:29.980  4542  4629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 07:25:29.980  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:25:29.980  4542  4634 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 07:25:29.996  4542  4629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-30 07:25:29.996  4542  4629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:25:29.996  4542  4629 D BtGatt.GattService: current time is 246230448531
,09-30 07:25:29.997  4542  4629 D BtGatt.GattService: Batch record : [123, -16, -50, 30, 32, 81, 1, -128, -95, 54, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0, 0, 81, 34, 97, 112, -14, -5, 1, -128, -76, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -77, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -77, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -79, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
09-30 07:25:29.997  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 3, 0]
09-30 07:25:29.997  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 07:25:29.997  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-30 07:25:29.997  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 07:25:29.998  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 07:25:29.998  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 07:25:29.998  4542  4629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-30 07:25:30.470  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 07:25:30.470  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:30.470  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 07:25:30.857   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 07:25:30.862   929  2914 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-30 07:25:34.967  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 07:25:34.968  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:34.968  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:34.968  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:34.968  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.968  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:25:34.969  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 07:25:34.969  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:34.969  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:34.970  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:34.970  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:34.970  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:34.971  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.972  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:34.976  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:25:34.976  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:34.976  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 07:25:34.977  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
,09-30 07:25:34.978  5585  5631 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-30 07:25:34.980  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 07:25:34.981  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:34.981  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 07:25:34.981  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:34.981  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.981  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:34.981  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:34.982  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
,09-30 07:25:34.982  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:34.982  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:34.982  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:34.982  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.982  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:34.982  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.982  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:34.985  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:34.986  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:34.986  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:34.986  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
,09-30 07:25:34.988  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 07:25:34.988  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:34.988  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:25:34.988  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:34.988  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:34.988  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.988  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:34.989  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:34.989  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
,09-30 07:25:34.989  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:34.989  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:34.989  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:34.989  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.989  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:34.989  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.989  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:34.990  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:25:34.990  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:34.990  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:34.991  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:34.991  5585  5631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-30 07:25:34.992  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:34.992  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:25:34.992  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:34.992  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:34.992  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.992  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:34.992  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:34.992  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:34.992  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 07:25:34.992  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:34.992  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:34.992  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.992  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:34.992  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.993  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:34.994  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:34.995  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 07:25:34.995  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:34.995  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:34.996  5585  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-30 07:25:34.996  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:34.996  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:34.996  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:34.996  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:34.996  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.996  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:34.996  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:34.996  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:34.996  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:34.996  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:34.996  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:34.997  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.997  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:34.997  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:34.997  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:34.998  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:25:34.998  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:34.998  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:34.998  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:34.999  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 07:25:34.999  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 07:25:35.000  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 07:25:35.000  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-30 07:25:35.000  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 07:25:35.000  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 07:25:35.000  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 07:25:35.000  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 07:25:35.000  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 07:25:35.000  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:35.000  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:25:35.000  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:35.000  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:35.001  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.001  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.001  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:35.001  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:35.001  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 07:25:35.001  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.001  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:35.001  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.001  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.001  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.001  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.006  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:25:35.006  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:35.006  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.006  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.007  5585  5631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 07:25:35.007  5585  5631 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 07:25:35.007  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 07:25:35.010  5585  5631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-30 07:25:35.010  5585  5631 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-30 07:25:35.010  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 07:25:35.010  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 07:25:35.010  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 07:25:35.010  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-30 07:25:35.010  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 07:25:35.010  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-30 07:25:35.011  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 07:25:35.012  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 07:25:35.012  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 07:25:35.012  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 07:25:35.012  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 07:25:35.012  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 07:25:35.012  5585  5631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-30 07:25:35.012  5585  5631 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 07:25:35.012  5585  5631 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-30 07:25:35.012  5585  5631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 07:25:35.012  5585  5631 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 07:25:35.012  5585  5631 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-30 07:25:35.013  5585  5631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-30 07:25:35.013  5585  5631 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 07:25:35.013  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-30 07:25:35.016  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-30 07:25:35.018  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-30 07:25:35.018  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-30 07:25:35.019  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-30 07:25:35.019  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-30 07:25:35.019  5585  5631 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-30 07:25:35.019  5585  5631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 07:25:35.019  5585  5631 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-30 07:25:35.019  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-30 07:25:35.019  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-30 07:25:35.020  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-30 07:25:35.020  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-30 07:25:35.020  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:35.020  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:35.021  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:35.021  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:35.021  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:25:35.021  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.021  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:35.021  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-30 07:25:35.022  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:35.022  5585  5632 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-30 07:25:35.022  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.022  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.022  5585  5632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 07:25:35.022  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:35.022  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.022  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.022  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.023  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.023  5585  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-30 07:25:35.023  5585  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-30 07:25:35.023  5585  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-30 07:25:35.022  4801  4801 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33030]" dev="sockfs" ino=33030 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 07:25:35.022  4801  4801 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33030]" dev="sockfs" ino=33030 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-30 07:25:35.024  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:35.024  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:35.024  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.024  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.025  5585  5632 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
09-30 07:25:35.025  5585  5631 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-30 07:25:35.025  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-30 07:25:35.025  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-30 07:25:35.025  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 07:25:35.025  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:35.026  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:35.026  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:35.026  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.026  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.026  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:35.026  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:35.026  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.026  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.026  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:35.026  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.026  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.026  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.026  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:35.027  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:35.027  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:35.027  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.027  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.028  5585  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-30 07:25:35.028  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:35.028  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:35.028  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:35.028  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:35.028  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.028  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.028  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 07:25:35.029  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:35.029  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.029  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.029  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:35.029  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.029  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.029  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.029  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.031  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:35.031  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:35.031  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.031  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.031  5585  5631 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-30 07:25:35.031  5585  5631 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-30 07:25:35.032  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 07:25:35.032  5585  5631 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-30 07:25:35.032  5585  5631 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 07:25:35.032  5585  5631 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-30 07:25:35.032  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 07:25:35.032  5585  5631 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-30 07:25:35.032  5585  5631 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 07:25:35.032  5585  5631 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 07:25:35.032  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 07:25:35.032  5585  5631 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-30 07:25:35.032  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:35.032  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:35.032  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:35.032  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 07:25:35.032  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.032  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.032  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:35.033  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:35.033  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.033  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.033  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:35.033  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.033  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.033  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.033  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.034  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:25:35.034  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:35.034  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.034  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.035  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:35.035  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.035  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:35.035  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:35.035  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:35.035  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:35.035  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:35.035  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 07:25:35.035  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:35.035  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:37.394   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:38.395   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:39.396   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:40.036  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 07:25:40.036  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.036  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:40.037  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.037  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:40.037  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:40.037  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:40.037  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:40.037  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:25:40.038  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:40.038  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:40.038  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.038  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.038  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 07:25:40.039  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:40.039  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.039  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.039  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 07:25:40.039  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.039  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.040  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:25:40.040  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:40.042  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:40.043  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:40.043  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.043  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.047  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-30 07:25:40.048  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:25:40.050  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-30 07:25:40.051  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-30 07:25:40.052  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,09-30 07:25:40.052  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-30 07:25:40.052  5585  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-30 07:25:40.053  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-30 07:25:40.053  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-30 07:25:40.053  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-30 07:25:40.054  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:40.054  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-30 07:25:40.054  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-30 07:25:40.054  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-30 07:25:40.054  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.054  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 07:25:40.054  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-30 07:25:40.055  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
,09-30 07:25:40.055  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-30 07:25:40.055  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.055  5585  5634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 07:25:40.055  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 07:25:40.055  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 07:25:40.055  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 07:25:40.055  4557  4557 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34190]" dev="sockfs" ino=34190 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 07:25:40.055  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.055  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.057  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:25:40.057  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.057  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:25:40.057  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:40.058  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:25:40.058  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:25:40.058  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:25:40.058  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:40.059  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 07:25:40.059  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.059  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.059  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 07:25:40.059  5585  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-30 07:25:40.059  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:40.059  5585  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-30 07:25:40.059  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.059  5585  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-30 07:25:40.059  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.059  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:40.059  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.060  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.060  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.060  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.060  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-30 07:25:40.060  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:40.055  4557  4557 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34190]" dev="sockfs" ino=34190 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 07:25:40.061  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:40.062  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 07:25:40.062  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.062  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.064  5585  5631 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-30 07:25:40.064  5585  5631 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 07:25:40.064  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-30 07:25:40.064  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 07:25:40.065  5585  5631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 07:25:40.065  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:40.065  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:25:40.065  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:40.065  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:40.065  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.065  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:40.065  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:25:40.066  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:40.066  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.066  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.066  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 07:25:40.066  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.066  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.066  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.066  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.068  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:25:40.068  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:40.068  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.069  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.076  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:40.076  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:25:40.076  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:40.076  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:40.076  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.076  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.076  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 07:25:40.076  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:40.077  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.077  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.077  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:40.077  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:25:40.077  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.077  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.077  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.078  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:25:40.078  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:25:40.078  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.079  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.080  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:25:40.080  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:25:40.080  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:25:40.080  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:25:40.080  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.080  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.080  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 07:25:40.080  5585  5631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2abfdda not in the list
09-30 07:25:40.080  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.080  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.081  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:40.081  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:25:40.081  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.081  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:40.081  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:40.082  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:25:40.082  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 07:25:40.082  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:40.082  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2fb20b not in the list
09-30 07:25:40.084  5585  5631 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-30 07:25:40.084  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 07:25:40.084  5585  5631 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-30 07:25:40.084  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 07:25:40.084  5585  5631 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-30 07:25:40.084  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-30 07:25:40.087  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 07:25:40.087  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-30 07:25:40.089  5585  5631 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-30 07:25:40.089  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 07:25:40.089  5585  5631 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-30 07:25:40.089  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 07:25:40.089  5585  5631 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-30 07:25:40.089  5585  5631 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-30 07:25:40.090  5585  5631 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-30 07:25:40.090  5585  5631 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-30 07:25:40.091  5585  5631 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-30 07:25:40.091  5585  5631 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-30 07:25:40.091  5585  5631 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-30 07:25:40.091  5585  5631 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-30 07:25:40.093  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:25:40.093  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9cfbff5 added. We now have 3 listener(s)
09-30 07:25:40.093  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 07:25:40.095  5585  5631 D BluetoothAdapter: enable(): BT is already enabled..!
,09-30 07:25:40.095   929  3772 D WifiService: setWifiEnabled: true pid=5585, uid=10077
09-30 07:25:40.095   929  3772 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 07:25:40.151  4542  4757 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-30 07:25:40.151  4542  4778 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-30 07:25:40.397   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:40.559  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 07:25:41.398   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:42.399   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 07:25:42.960   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 07:25:44.860   929  2906 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 07:25:45.100  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 07:25:45.101  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66f918a added. We now have 4 listener(s)
,09-30 07:25:45.101  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 07:25:45.113  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 07:25:45.114  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66f918a removed from the list
09-30 07:25:45.114  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:45.114  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:45.114  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:25:45.115  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 07:25:45.115  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69533fb added. We now have 4 listener(s)
09-30 07:25:45.115  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:25:45.117  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:25:45.118  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69533fb removed from the list
09-30 07:25:45.118  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:25:45.118  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:25:45.118  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:25:45.119  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:25:45.119  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27fcc18 added. We now have 4 listener(s)
,09-30 07:25:45.119  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:25:45.124   929  3115 D WifiService: setWifiEnabled: false pid=5585, uid=10077
09-30 07:25:45.124   929  3115 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 07:25:45.130   929  2906 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 07:25:45.130   929  2906 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 07:25:45.130   929  2906 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 07:25:45.130   929  2906 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 07:25:45.135  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:25:45.138  4542  4625 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 07:25:45.138  4542  4625 D BluetoothAdapterProperties: Setting state to 13
09-30 07:25:45.138  4542  4625 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 07:25:45.139  4542  4625 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 07:25:45.139  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.139  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:25:45.139  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.139  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.139  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:45.139  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:25:45.139  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:45.139  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:45.139  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:45.140  4542  4625 I BluetoothAdapterState: Entering PendingCommandState
09-30 07:25:45.141  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.141  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 07:25:45.141   929  5333 D DhcpClient: Clearing IP address
09-30 07:25:45.141  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 07:25:45.141   509   917 D CommandListener: Clearing all IP addresses on wlan0
,09-30 07:25:45.144   509   917 D CommandListener: Setting iface cfg
,09-30 07:25:45.144  4542  4629 D BluetoothAdapterProperties: Scan Mode:20
,09-30 07:25:45.144  4542  4625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-30 07:25:45.145  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.146  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.146  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.146  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.146  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:45.146  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.146  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:45.146  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:45.146  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:45.147  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.147  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:45.149  4542  4542 D HeadsetService: Received stop request...Stopping profile...
09-30 07:25:45.150   929  5334 D DhcpClient: Receive thread stopped
09-30 07:25:45.154  3537  5388 V NativeCrypto: Read error: ssl=0x7f8dfc5a80: I/O error during system call, Connection timed out
09-30 07:25:45.156  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:45.160  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.160  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.160  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.160  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.160  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:45.160  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.160  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.160  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:45.160  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:45.161  3537  5388 V NativeCrypto: SSL shutdown failed: ssl=0x7f8dfc5a80: I/O error during system call, Broken pipe
09-30 07:25:45.162  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.162  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 07:25:45.164   929  3800 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-30 07:25:45.165   929  5331 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-30 07:25:45.167   929  5331 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-30 07:25:45.167   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-30 07:25:45.167   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 07:25:45.169   929  2914 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-30 07:25:45.171  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.171  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.171  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.171  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.171  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:45.171  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.171  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.171  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:45.171  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:45.172  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:25:45.172  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:45.173   929   942 I ActivityManager: Start proc 5638:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-30 07:25:45.174  3723  3745 D BluetoothHeadset: Proxy object disconnected
09-30 07:25:45.175  4542  4542 D BluetoothMapService: onReceive
09-30 07:25:45.175   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 07:25:45.175  4542  4542 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 07:25:45.175  4542  4542 D BluetoothMapService: STATE_TURNING_OFF
09-30 07:25:45.175  3076  3090 D BluetoothHeadset: Proxy object disconnected
09-30 07:25:45.175  4542  4542 D A2dpService: Received stop request...Stopping profile...
,09-30 07:25:45.175   929   929 D BluetoothHeadset: Proxy object disconnected
,09-30 07:25:45.175   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 07:25:45.176  4542  4783 D A2dpStateMachine: Exit Disconnected: -1
09-30 07:25:45.179  3076  3076 D HeadsetProfile: Bluetooth service disconnected
09-30 07:25:45.179  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.179  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.179  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.179  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.179  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:45.179  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.179  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.179  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:45.179  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:45.179   538   538 E Parcel  : Reading a NULL string not supported here.
09-30 07:25:45.179   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 07:25:45.180   929   929 D BluetoothA2dp: Proxy object disconnected
,09-30 07:25:45.180   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-30 07:25:45.180  4542  4542 V BluetoothAdapterState: isTurningOff()=true
09-30 07:25:45.180  4542  4542 V BluetoothAdapterState: isTurningOn()=false
09-30 07:25:45.180  4542  4542 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 07:25:45.180  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:25:45.180  4542  4542 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:25:45.181  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:45.183  3076  3076 D BluetoothA2dp: Proxy object disconnected
09-30 07:25:45.184   929   929 D RttService: SCAN_AVAILABLE : 1
09-30 07:25:45.184   929  3017 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 07:25:45.185   929  2906 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-30 07:25:45.185  4542  4542 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 07:25:45.185  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.185  4542  4542 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-30 07:25:45.185  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.185  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.185  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.185  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:45.185  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.185  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.185  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:45.185  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:45.185  4542  4757 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:25:45.186  4542  4757 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:25:45.186  4542  4542 D BluetoothMapService: MAP Service closeService in
,09-30 07:25:45.186  4542  4757 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:25:45.186  4542  4542 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 07:25:45.186  4542  4629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 07:25:45.186  4542  4542 D ObexServerSockets0: shutdown(block = true)
09-30 07:25:45.186  4542  4629 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 07:25:45.186  4542  4542 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 07:25:45.187  4542  4542 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 07:25:45.187  4542  4802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-30 07:25:45.187  4542  4803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 07:25:45.188  4542  4778 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 07:25:45.189   929  2906 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 07:25:45.190  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.190  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.190  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.190  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.190  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:45.190  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.190  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.190  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:45.190  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:45.191   509   917 D CommandListener: Clearing all IP addresses on wlan0
09-30 07:25:45.191  4542  4542 I BtOppRfcommListener: stopping Accept Thread
09-30 07:25:45.191   929  2914 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-30 07:25:45.192  4542  5273 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-30 07:25:45.193  4542  5273 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 07:25:45.193  3687  3866 W QCNEJ   : |CORE| network lost: 100
09-30 07:25:45.194  3687  3866 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 07:25:45.195   929  2906 D DhcpClient: doQuit
09-30 07:25:45.195   929  2906 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 07:25:45.195   929  5333 D DhcpClient: onQuitting
09-30 07:25:45.196  4542  4542 D HidService: Received stop request...Stopping profile...
09-30 07:25:45.197  4542  4542 D HidService: Stopping Bluetooth HidService
09-30 07:25:45.197  3399  3399 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 07:25:45.198  4542  4542 V BluetoothAdapterState: isTurningOff()=true
09-30 07:25:45.198  4542  4542 V BluetoothAdapterState: isTurningOn()=false
09-30 07:25:45.198  4542  4542 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:25:45.198  4542  4542 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:25:45.199  4542  4542 D HealthService: Received stop request...Stopping profile...
,09-30 07:25:45.201  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:25:45.201  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.201  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.201  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.201  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:45.201  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.201  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.201  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:45.201  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:45.202  4542  4629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 07:25:45.202  4542  4757 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 07:25:45.202  4542  4757 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:25:45.202  4542  4757 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 07:25:45.202  4542  4757 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 07:25:45.202  4542  4757 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 07:25:45.202  4542  4757 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 07:25:45.203  4542  4542 D PanService: Received stop request...Stopping profile...
,09-30 07:25:45.207  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:25:45.207  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.207  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.207  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.207  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:25:45.207  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.207  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.207  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:45.207  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:25:45.208  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.208  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 07:25:45.209  3076  3076 D BluetoothInputDevice: Proxy object disconnected
,09-30 07:25:45.209  3076  3076 D HidProfile: Bluetooth service disconnected
,09-30 07:25:45.210  3076  3076 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 07:25:45.210  3076  3076 D PanProfile: Bluetooth service disconnected
09-30 07:25:45.210  4542  4542 D BluetoothMapService: Received stop request...Stopping profile...
09-30 07:25:45.210  4542  4542 D BluetoothMapService: stop()
09-30 07:25:45.211  4542  4542 D BluetoothMapAppObserver: deinitObservers()
09-30 07:25:45.211  4542  4542 D BluetoothMapAppObserver: removeReceiver()
,09-30 07:25:45.211  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.211  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.211  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.211  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.211  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:25:45.211  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.211  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.211  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:45.211  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:25:45.213  4542  4542 D SapService: Received stop request...Stopping profile...
09-30 07:25:45.213  4542  4542 V SapService: stop()
09-30 07:25:45.214  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.214  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:45.215  3076  3076 D BluetoothMap: Proxy object disconnected
09-30 07:25:45.215  3076  3076 D MapProfile: Bluetooth service disconnected
,09-30 07:25:45.216  4542  4542 V BluetoothAdapterState: isTurningOff()=true
,09-30 07:25:45.216  4542  4542 V BluetoothAdapterState: isTurningOn()=false
09-30 07:25:45.216  4542  4542 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:25:45.216  4542  4542 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:25:45.216  4542  4542 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 07:25:45.216  4542  4542 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 07:25:45.217  4542  4629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 07:25:45.217  4542  4542 V BluetoothAdapterState: isTurningOff()=true
09-30 07:25:45.217  4542  4542 V BluetoothAdapterState: isTurningOn()=false
09-30 07:25:45.217  4542  4542 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:25:45.217  4542  4542 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 07:25:45.217  4542  4542 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 07:25:45.217  4542  4629 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 07:25:45.217  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.217  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:45.217  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:45.217  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:45.217  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:25:45.217  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:45.217  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:45.217  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:45.217  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:25:45.217  4542  4542 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 07:25:45.217  3399  3399 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 07:25:45.217  4542  4542 V BluetoothAdapterState: isTurningOff()=true
09-30 07:25:45.217  4542  4542 V BluetoothAdapterState: isTurningOn()=false
09-30 07:25:45.217  4542  4542 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:25:45.218  4542  4542 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:25:45.218  4542  4542 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 07:25:45.218  4542  4542 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 07:25:45.218  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:45.218  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 07:25:45.220  4542  4542 D BluetoothMapService: MAP Service closeService in
09-30 07:25:45.220  4542  4542 V BluetoothAdapterState: isTurningOff()=true
,09-30 07:25:45.220  4542  4542 V BluetoothAdapterState: isTurningOn()=false
09-30 07:25:45.220  4542  4542 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:25:45.220  4542  4542 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:25:45.220  4542  4542 D BluetoothMapService: cleanup()
09-30 07:25:45.220  3399  3399 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-30 07:25:45.221  4542  4542 D BluetoothMapService: MAP Service closeService in
09-30 07:25:45.221  4542  4542 V BluetoothAdapterState: isTurningOff()=true
09-30 07:25:45.221  4542  4542 V BluetoothAdapterState: isTurningOn()=false
09-30 07:25:45.221  4542  4542 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:25:45.221  4542  4542 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:25:45.221  4542  4625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 07:25:45.221  4542  4625 D BluetoothAdapterProperties: Setting state to 15
09-30 07:25:45.221  4542  4625 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 07:25:45.222  4542  4625 I BluetoothAdapterState: Entering BleOnState
09-30 07:25:45.222  3076  3932 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 07:25:45.223   509   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 07:25:45.223  3076  3088 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-30 07:25:45.224   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 07:25:45.224  3076  3090 D BluetoothMap: onBluetoothStateChange: up=false
09-30 07:25:45.225   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:25:45.225  3076  3932 D BluetoothPan: onBluetoothStateChange on: false
09-30 07:25:45.226   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 07:25:45.226  3076  3088 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:25:45.227  3723  3745 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:25:45.227   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:25:45.227  3076  3090 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 07:25:45.228  4542  4625 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-30 07:25:45.228  4542  4625 D BluetoothAdapterProperties: Setting state to 16
09-30 07:25:45.228  4542  4625 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 07:25:45.229  4542  4625 D BluetoothAdapterProperties: onBleDisable
09-30 07:25:45.229  4542  4625 I BluetoothAdapterState: Entering PendingCommandState
09-30 07:25:45.229  5638  5638 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-30 07:25:45.229  4542  4626 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 07:25:45.230  4542  4629 D BluetoothAdapterProperties: Scan Mode:20
09-30 07:25:45.230  4542  4757 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 07:25:45.230  4542  4757 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 07:25:45.231  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:45.233  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:45.235  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:45.236  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:45.237  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:45.239  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:45.246  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 07:25:45.248   509   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 07:25:45.249   509   917 D TetherController: Setting IP forward enable = 0
09-30 07:25:45.250   929  2914 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-30 07:25:45.250   929  2914 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 07:25:45.252   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee5923f:true
,09-30 07:25:45.253   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-30 07:25:45.254  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 07:25:45.255  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:45.257  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:45.259  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:45.259  5230  5230 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@99ce619 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-30 07:25:45.264  5001  5024 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 07:25:45.265  5001  5024 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 07:25:45.265  5001  5024 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 07:25:45.265  5001  5024 E SarControlService: no key has been found,reset the power
09-30 07:25:45.265  5001  5038 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 07:25:45.265  5001  5038 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-30 07:25:45.265  5001  5038 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 07:25:45.266  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 07:25:45.266  5026  5026 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 07:25:45.267  5001  5038 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 07:25:45.268  5001  5038 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 07:25:45.268  5001  5038 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 07:25:45.269  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 07:25:45.269  5026  5026 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-30 07:25:45.269   929  3800 I ActivityManager: Start proc 5663:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-30 07:25:45.271  5026  5040 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e3d407 HexData = [00000000ea03000000000000ffffffff]
,09-30 07:25:45.271  5026  5040 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 07:25:45.272  5026  5040 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-30 07:25:45.272  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 07:25:45.272  5001  5011 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 07:25:45.274  5026  5040 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e3d407 HexData = [00000000eb03000000000000ffffffff]
,09-30 07:25:45.274  5026  5040 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 07:25:45.274  5026  5040 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-30 07:25:45.275  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 07:25:45.277  5001  5012 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 07:25:45.285  3399  3399 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 07:25:45.298   509   917 E Netd    : netlink response contains error (No such file or directory)
,09-30 07:25:45.299   929  2914 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 07:25:45.301  3399  3399 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 07:25:45.307  5638  5638 D LocalBluetoothProfileManager: Adding local MAP profile
,09-30 07:25:45.309  5638  5638 D BluetoothMap: Create BluetoothMap proxy object
,09-30 07:25:45.323  5663  5663 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-30 07:25:45.326  5638  5638 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-30 07:25:45.340  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,09-30 07:25:45.348   929  3821 I ActivityManager: Killing 4941:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-30 07:25:45.405   929  2906 D wifi    : In wifi stop Hal
,09-30 07:25:45.405  4976  4976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 07:25:45.405   929  2906 D wifi    : halHandle = 0x7f77a1e680, mVM = 0x7f9408d140, mCls = 0x100a02
09-30 07:25:45.405   929  3398 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 07:25:45.406   929  3398 D WifiHAL : Got a signal to exit!!!
09-30 07:25:45.406   929  3398 I WifiHAL : Exit wifi_event_loop
09-30 07:25:45.406   929  2906 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 07:25:45.406   929  2906 E WifiHAL : Event processing terminated
09-30 07:25:45.407   929  2906 D wifi    : In wifi cleaned up handler
09-30 07:25:45.407   929  2906 I WifiHAL : Internal cleanup completed
,09-30 07:25:45.408  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:45.409  4039  4175 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 07:25:45.410  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:45.411  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:45.429   929  3398 D wifi    : set interface wlan0 flags (DOWN)
,09-30 07:25:45.429   929  2906 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 07:25:45.437  4542  4629 I bt_hci  : shut_down
,09-30 07:25:45.442  4542  4635 D bt_hwcfg: hw_epilog_process
,09-30 07:25:45.442  4542  4635 I bt_vendor: low_power_mode_cb
,09-30 07:25:45.445  4542  4635 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-30 07:25:45.445  4542  4635 I bt_vendor: epilog_cb
09-30 07:25:45.445  4542  4635 I bt_hci  : epilog_finished_callback
,09-30 07:25:45.447  4542  4629 I bt_hci_h4: hal_close
,09-30 07:25:45.447  4542  4629 I bt_userial_vendor: device fd = 54 close
,09-30 07:25:45.527  5663  5663 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 07:25:45.527  5663  5663 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:25:45.527  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:25:45.528  5663  5663 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:25:45.528  5663  5663 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:25:45.528  5663  5663 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.k.d(PG:583)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:25:45.528  5663  5663 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:25:45.528  5663  5663 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:25:45.528  5663  5663 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:25:45.528  5663  5663 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:25:45.544   929  3772 I ActivityManager: Start proc 5695:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-30 07:25:45.545   929  3772 I ActivityManager: Killing 5362:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-30 07:25:45.588  4542  4626 D bt_stack_manager: event_shut_down_stack finished.
09-30 07:25:45.588  4542  4625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-30 07:25:45.589  4542  4625 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 07:25:45.590  4542  4542 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 07:25:45.590  4542  4542 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 07:25:45.590  4542  4542 D BtGatt.GattService: stop()
09-30 07:25:45.590  4542  4542 D BtGatt.AdvertiseManager: advertise clients cleared
09-30 07:25:45.591  4542  4542 V BluetoothAdapterState: isTurningOff()=false
09-30 07:25:45.591  4542  4542 V BluetoothAdapterState: isTurningOn()=false
09-30 07:25:45.592  4542  4542 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:25:45.592  4542  4542 V BluetoothAdapterState: isBleTurningOff()=true
09-30 07:25:45.592  4542  4625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 07:25:45.592  4542  4625 D BluetoothAdapterProperties: Setting state to 10
09-30 07:25:45.592  4542  4625 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 07:25:45.592  4542  4625 I BluetoothAdapterState: Entering OffState
09-30 07:25:45.593   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-30 07:25:45.600  4542  4542 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-30 07:25:45.600  4542  4542 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 07:25:45.600  4542  4542 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 07:25:45.601  4542  4626 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 07:25:45.610  4542  4626 D bt_stack_manager: event_clean_up_stack finished.
,09-30 07:25:45.621  5695  5695 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-30 07:25:45.631   929   946 D Tethering: InitialState.processMessage what=4
,09-30 07:25:45.633   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 07:25:45.633  4542  4542 I art     : System.exit called, status: 0
09-30 07:25:45.633  4542  4542 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 07:25:45.647   929  3821 I ActivityManager: Killing 5375:com.android.chrome/u0a39 (adj 15): empty #17
,09-30 07:25:45.708   929  3800 I ActivityManager: Process com.android.bluetooth (pid 4542) has died
,09-30 07:25:45.711  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 07:25:45.725   929   939 I ActivityManager: Start proc 5711:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-30 07:25:45.726  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,09-30 07:25:45.794  5711  5711 D AdapterServiceConfig: Adding HeadsetService
,09-30 07:25:45.794  5711  5711 D AdapterServiceConfig: Adding A2dpService
09-30 07:25:45.794  5711  5711 D AdapterServiceConfig: Adding HidService
09-30 07:25:45.794  5711  5711 D AdapterServiceConfig: Adding HealthService
09-30 07:25:45.794  5711  5711 D AdapterServiceConfig: Adding PanService
09-30 07:25:45.794  5711  5711 D AdapterServiceConfig: Adding GattService
09-30 07:25:45.794  5711  5711 D AdapterServiceConfig: Adding BluetoothMapService
09-30 07:25:45.795  5711  5711 D AdapterServiceConfig: Adding SapService
09-30 07:25:45.797   929  3115 I ActivityManager: Killing 5393:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-30 07:25:45.820  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 07:25:45.828  3799  3799 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 07:25:45.831  3799  3799 D SystemUpdateService: onCreate
,09-30 07:25:45.838  3799  3799 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 07:25:45.846  3799  3799 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 07:25:45.851  3799  5360 I iu.UploadsManager: num queued entries: 0
,09-30 07:25:45.851  3799  5360 I iu.UploadsManager: num updated entries: 0
09-30 07:25:45.852  3799  5360 I iu.SyncManager: NEXT; no task
,09-30 07:25:45.853  3799  3799 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 07:25:45.855  3799  3799 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 07:25:45.856  3799  5723 I SystemUpdateService: active receiver: enabled
,09-30 07:25:45.861  3799  5723 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 07:25:45.866  3799  5723 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 07:25:45.866  3799  5723 I SystemUpdateService: now status is 0 (complete)
09-30 07:25:45.866  3799  5723 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 07:25:45.866  3799  5723 I SystemUpdateService: file has been verified
,09-30 07:25:45.867  3799  5723 I SystemUpdateService: OTA package size = 21989297
,09-30 07:25:45.867   929   939 I ActivityManager: Start proc 5725:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-30 07:25:45.884  3799  5723 I SystemUpdateService: showing system update notification
,09-30 07:25:45.898  5725  5725 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-30 07:25:45.907  5725  5725 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 07:25:45.915  5725  5725 D SprintDMHelper: simOperator: 
,09-30 07:25:45.915  5725  5725 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 07:25:45.927   929  3115 I ActivityManager: Start proc 5737:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-30 07:25:45.931  3799  3799 D SystemUpdateService: onDestroy
,09-30 07:25:45.933   929  3160 I ActivityManager: Killing 5230:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-30 07:25:45.977  5663  5690 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-30 07:25:46.033  4976  5751 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 07:25:46.039   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f79d6c3:true
,09-30 07:25:46.042   929  3800 I ActivityManager: Start proc 5753:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-30 07:25:46.051   929   940 I ActivityManager: Killing 4639:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-30 07:25:46.111  5753  5753 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-30 07:25:46.302   509   917 D TetherController: Setting IP forward enable = 0
,09-30 07:25:46.310   929  3760 I ActivityManager: Killing 5447:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-30 07:25:50.145   929   940 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,09-30 07:25:50.146   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 07:25:50.155   509   917 D SoftapController: Softap fwReload - Ok
,09-30 07:25:50.160   509   917 D CommandListener: Setting iface cfg
09-30 07:25:50.160   509   917 D CommandListener: Trying to bring down wlan0
,09-30 07:25:50.162   509   917 D CommandListener: Clearing all IP addresses on wlan0
,09-30 07:25:50.167   929  2906 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 07:25:50.722   929  2906 D wifi    : set interface wlan0 flags (UP)
09-30 07:25:50.723   929  2906 I WifiHAL : Initializing wifi
,09-30 07:25:50.723   929  2906 I WifiHAL : Creating socket
09-30 07:25:50.730   929  2906 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-30 07:25:50.730   929  2906 D wifi    : Did set static halHandle = 0x7f77a1e680
09-30 07:25:50.730   929  2906 D wifi    : halHandle = 0x7f77a1e680, mVM = 0x7f9408d140, mCls = 0x195a
09-30 07:25:50.730   929  2906 D wifi    : array field set
09-30 07:25:50.731   929  2906 I WifiNative-HAL: interface[0] = wlan0
09-30 07:25:50.733   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-30 07:25:50.733   929  5776 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547467945600
09-30 07:25:50.738   929  5776 D wifi    : waitForHalEvents called, vm = 0x7f9408d140, obj = 0x195a, env = 0x7f7837a7c0
,09-30 07:25:50.810  5777  5777 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 07:25:50.834  5777  5777 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 07:25:50.835   929  2906 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 07:25:50.837  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:50.838  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:25:50.839  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:50.860  5777  5777 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-30 07:25:50.860  5777  5777 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 07:25:50.879  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:25:50.879  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:50.879  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:50.879  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:50.879  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:50.879  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:50.879  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:50.879  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:50.879  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 07:25:50.880  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:50.880  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:50.881   929  2906 D WifiConfigStore: Loading config and enabling all networks 
,09-30 07:25:50.882  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:50.883  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:50.883  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:50.883  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:50.883  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:50.883  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:50.883  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:50.883  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:50.883  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 07:25:50.883  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:50.883  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:50.886  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:50.886  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:50.886  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:50.886  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:50.886  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:50.886  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:50.886  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:50.886  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:50.886  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:25:50.886  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:50.887  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 07:25:50.898   929  2906 D WifiConfigStore: loaded 0 passpoint configs
,09-30 07:25:50.899   929  2906 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 07:25:50.899   929  2906 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-30 07:25:50.900   929  2906 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 07:25:50.902   929  2906 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 07:25:50.902   929  2906 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 07:25:50.902   929  2906 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 07:25:50.902   929  2906 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 07:25:50.906   929  2906 D WifiNative-HAL: Setting external_sim to 1
,09-30 07:25:50.906  4976  4976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 07:25:50.906   929  2906 D wifi    : setting dfs flag to true, 0x7f7c8eb4e0
09-30 07:25:50.907   929  2906 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 07:25:50.907   929  2906 D wifi    : setting scan oui 0x7f7c8eb4e0
09-30 07:25:50.907   929  2906 D WifiHAL : Sending mac address OUI
09-30 07:25:50.912   929  2906 E native  : do suspend false
,09-30 07:25:50.919   929  2906 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 07:25:50.919   929   929 D RttService: SCAN_AVAILABLE : 3
09-30 07:25:50.919   509   917 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 07:25:50.919   929  3017 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 07:25:50.920   509   917 D CommandListener: Setting iface cfg
,09-30 07:25:50.924   929  2905 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-30 07:25:50.924   929  2905 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 07:25:50.932   929  2905 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 07:25:50.933   929  2905 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 07:25:50.938   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267171 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-30 07:25:54.087  5777  5777 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 07:25:54.092  5777  5777 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 07:25:54.098  5777  5777 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 07:25:54.102  5777  5777 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 07:25:54.153   929  2906 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 07:25:54.154   929  2906 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 07:25:54.154   929  2906 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 07:25:54.165   929  2906 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 07:25:54.204   929  2906 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 07:25:54.208  5777  5777 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 07:25:54.630  5777  5777 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 07:25:54.663  5777  5777 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 07:25:54.664  5777  5777 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 07:25:54.675   929  2906 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-30 07:25:54.675   929  2906 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 07:25:54.675   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 07:25:54.691   929  2906 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 07:25:54.703   509   917 D CommandListener: Setting iface cfg
,09-30 07:25:54.708   929  2906 D WifiStateMachine: Start Dhcp Watchdog 2
,09-30 07:25:54.715   929  5785 D DhcpClient: Receive thread started
,09-30 07:25:54.718   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 07:25:54.718   929  2906 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 07:25:54.718   929  2914 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-30 07:25:54.800   929  2906 E native  : do suspend false
,09-30 07:25:54.811   929  5784 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 07:25:54.830   929  5785 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-30 07:25:54.831   929  5784 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-30 07:25:54.833   929  5784 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 07:25:54.847   929  5785 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 07:25:54.848   929  5784 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 07:25:54.851   509   917 D CommandListener: Setting iface cfg
,09-30 07:25:54.856   929  2906 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 07:25:54.861   929  5784 D DhcpClient: Scheduling renewal in 86399s
,09-30 07:25:54.870   929  2906 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 07:25:54.871   929  2906 D WifiConfigStore: No blacklist allowed without epno enabled
,09-30 07:25:54.872   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 07:25:54.874   929  2914 D ConnectivityService: Adding iface wlan0 to network 101
,09-30 07:25:54.882   929  2906 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 07:25:54.927   929  2914 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 07:25:54.928   929  2914 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-30 07:25:54.930   929  2914 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-30 07:25:54.933   929  2914 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-30 07:25:54.935   929  2914 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-30 07:25:54.943   929  2914 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 07:25:54.948   929  2914 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-30 07:25:54.948   929  2914 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-30 07:25:54.948   929  2914 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-30 07:25:54.948   929  2914 D ConnectivityService:    accepting network in place of null
09-30 07:25:54.948   929  2906 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 07:25:54.948   929  2906 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 07:25:54.949   929  2914 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 07:25:54.963   929  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271196, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 07:25:54.971   509   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 07:25:54.993   509   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 07:25:54.996   929  2914 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-30 07:25:54.997  3687  3866 W QCNEJ   : |CORE| network available: 101
09-30 07:25:54.997   929  2914 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 07:25:54.998   929  2914 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-30 07:25:55.001  3687  3866 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 07:25:55.002   929   946 D Tethering: MasterInitialState.processMessage what=3
09-30 07:25:55.003  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.003  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.003  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.003  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.003  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:55.003  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.003  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:55.003  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:55.003  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:55.003  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.003  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:55.003  3687  3866 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-30 07:25:55.004  3687  3866 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 07:25:55.005  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.005  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.005  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.005  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.005  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:55.005  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.005  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:55.005  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:55.005  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:55.005  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.005  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:55.009  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:25:55.009  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.009  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.009  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.009  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:55.009  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.009  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:25:55.009  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:25:55.009  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:25:55.009  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.009  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 07:25:55.014  5001  5024 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-30 07:25:55.014  5001  5024 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 07:25:55.014  5001  5024 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 07:25:55.015  5001  5024 E SarControlService: no key has been found,reset the power
09-30 07:25:55.015  5001  5038 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 07:25:55.015  5001  5038 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 07:25:55.015  5001  5038 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 07:25:55.016  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 07:25:55.016  5026  5026 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 07:25:55.018  3799  3799 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 07:25:55.021  3799  3799 D SystemUpdateService: onCreate
,09-30 07:25:55.021  5001  5038 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 07:25:55.022  5001  5038 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 07:25:55.022  5001  5038 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-30 07:25:55.023  5026  5040 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e3d407 HexData = [00000000ec03000000000000ffffffff]
09-30 07:25:55.023  5026  5040 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 07:25:55.023  5026  5040 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-30 07:25:55.024  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 07:25:55.024  5026  5026 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 07:25:55.024  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-30 07:25:55.024  5001  5011 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 07:25:55.026  5026  5040 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e3d407 HexData = [00000000ed03000000000000ffffffff]
,09-30 07:25:55.026  5026  5040 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 07:25:55.026  5026  5040 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-30 07:25:55.027  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-30 07:25:55.027  5001  5012 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 07:25:55.028  3799  3799 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 07:25:55.037  3799  3799 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-30 07:25:55.039   929  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-30 07:25:55.042  3799  5360 I iu.UploadsManager: num queued entries: 0
,09-30 07:25:55.042  3799  5360 I iu.UploadsManager: num updated entries: 0
,09-30 07:25:55.045  3799  5795 I SystemUpdateService: active receiver: enabled
,09-30 07:25:55.046  3799  3799 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 07:25:55.047  3799  3799 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 07:25:55.049  5725  5725 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 07:25:55.052  5725  5725 D SprintDMHelper: simOperator: 
09-30 07:25:55.052  5725  5725 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 07:25:55.076  3799  5795 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 07:25:55.077  3799  5360 I iu.SyncManager: NEXT; no task
,09-30 07:25:55.089   929  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 11:25:55 GMT], X-Android-Received-Millis=[1475234755088], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475234755067]}
,09-30 07:25:55.089   929  2914 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 07:25:55.089   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-30 07:25:55.089   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 07:25:55.090   929  2914 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-30 07:25:55.091  3799  5795 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-30 07:25:55.092  3799  5795 I SystemUpdateService: now status is 0 (complete)
09-30 07:25:55.092  3799  5795 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 07:25:55.092  3799  5795 I SystemUpdateService: file has been verified
09-30 07:25:55.092  3799  5795 I SystemUpdateService: OTA package size = 21989297
,09-30 07:25:55.097  3799  5795 I SystemUpdateService: showing system update notification
,09-30 07:25:55.107  3799  3799 D SystemUpdateService: onDestroy
,09-30 07:25:55.152   929   939 D WifiService: setWifiEnabled: false pid=5585, uid=10077
,09-30 07:25:55.152   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-30 07:25:55.153   929  2906 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 07:25:55.153   929  2906 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 07:25:55.153   929  2906 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 07:25:55.154   929  2906 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 07:25:55.160   929  5784 D DhcpClient: Clearing IP address
09-30 07:25:55.160   509   917 D CommandListener: Clearing all IP addresses on wlan0
,09-30 07:25:55.162   509   917 D CommandListener: Setting iface cfg
,09-30 07:25:55.164  3537  5796 V NativeCrypto: SSL handshake aborted: ssl=0x7f78b47e00: I/O error during system call, Connection timed out
,09-30 07:25:55.168   929  3115 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,09-30 07:25:55.169   929  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,09-30 07:25:55.169   929  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-30 07:25:55.171   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 07:25:55.172   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-30 07:25:55.173  4976  5799 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-30 07:25:55.174   929  5785 D DhcpClient: Receive thread stopped
,09-30 07:25:55.178   538   538 E Parcel  : Reading a NULL string not supported here.
09-30 07:25:55.180   929  2914 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-30 07:25:55.180   929  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-30 07:25:55.180   929   929 D RttService: SCAN_AVAILABLE : 1
09-30 07:25:55.181   929  3017 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 07:25:55.183  3687  3866 W QCNEJ   : |CORE| network lost: 101
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 07:25:55.183  4976  5799 W Babel_Netw,orkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
09-30 07:25:55.183  4976  5799 W Babel_NetworkConnectionCheckingService: 	... 21 more
09-30 07:25:55.183  3687  3866 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 07:25:55.184  4976  5799 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-30 07:25:55.185   929  2906 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-30 07:25:55.189   929  2906 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 07:25:55.205   509   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 07:25:55.226   509   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 07:25:55.226   929  2914 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 07:25:55.226   929  2914 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 07:25:55.226   509   917 D CommandListener: Clearing all IP addresses on wlan0
,09-30 07:25:55.228   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-30 07:25:55.230  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.230  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.230  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.230  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.230  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:55.230  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.230  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:55.230  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:55.230  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:25:55.230  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.230  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:55.232  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.233  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.233  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.233  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.233  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:55.233  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.233  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:55.233  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:55.233  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:25:55.233  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.233  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:55.234  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.234  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:25:55.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:55.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:55.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
09-30 07:25:55.234  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.234  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:55.236   929  2906 D DhcpClient: doQuit
09-30 07:25:55.236   929  2906 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 07:25:55.237   929  5784 D DhcpClient: onQuitting
09-30 07:25:55.238  5777  5777 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 07:25:55.241  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.241  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.241  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.241  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.241  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:25:55.241  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.241  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:55.241  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:55.241  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:25:55.241  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.241  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:55.242  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.242  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.242  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.242  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.242  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:25:55.242  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.242  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:55.242  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:55.242  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:25:55.242  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:25:55.242  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:55.243  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:25:55.243  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:25:55.243  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:25:55.243  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:25:55.243  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:25:55.243  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:25:55.243  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:25:55.243  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:25:55.243  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 07:25:55.243  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:25:55.243  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:25:55.244  3799  3799 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 07:25:55.245  5001  5024 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 07:25:55.245  5001  5024 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 07:25:55.245  5001  5024 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 07:25:55.245  5001  5024 E SarControlService: no key has been found,reset the power
09-30 07:25:55.245  5001  5038 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 07:25:55.245  5001  5038 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 07:25:55.245  5001  5038 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 07:25:55.246  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 07:25:55.246  5026  5026 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 07:25:55.247  5001  5038 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 07:25:55.247  5001  5038 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 07:25:55.247  5001  5038 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 07:25:55.248  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 07:25:55.248  5026  5026 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 07:25:55.251  3799  3799 D SystemUpdateService: onCreate
,09-30 07:25:55.252  5026  5040 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e3d407 HexData = [00000000ee03000000000000ffffffff]
,09-30 07:25:55.252  5026  5040 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 07:25:55.253  5777  5777 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 07:25:55.253  5026  5040 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-30 07:25:55.253  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 07:25:55.253  5001  5012 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-30 07:25:55.255  5026  5040 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e3d407 HexData = [00000000ef03000000000000ffffffff]
09-30 07:25:55.255  5026  5040 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 07:25:55.256  5026  5040 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-30 07:25:55.256  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 07:25:55.256  5001  5011 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 07:25:55.257  5777  5777 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-30 07:25:55.257  3799  3799 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 07:25:55.261  3799  5813 I SystemUpdateService: active receiver: enabled
,09-30 07:25:55.265  3799  3799 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 07:25:55.267  3799  5360 I iu.UploadsManager: num queued entries: 0
09-30 07:25:55.267  3799  5360 I iu.UploadsManager: num updated entries: 0
,09-30 07:25:55.268  3799  5360 I iu.SyncManager: NEXT; no task
,09-30 07:25:55.273  3799  3799 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 07:25:55.275  3799  3799 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 07:25:55.276  5725  5725 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 07:25:55.280  5725  5725 D SprintDMHelper: simOperator: 
09-30 07:25:55.280  5725  5725 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 07:25:55.285   509   917 E Netd    : netlink response contains error (No such file or directory)
,09-30 07:25:55.286   929  2914 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-30 07:25:55.286   929  2914 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 07:25:55.286  3799  5813 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 07:25:55.292  4976  5817 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 07:25:55.296  5777  5777 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 07:25:55.298  3799  5813 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 07:25:55.298  3799  5813 I SystemUpdateService: now status is 0 (complete)
09-30 07:25:55.298  3799  5813 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 07:25:55.298  3799  5813 I SystemUpdateService: file has been verified
09-30 07:25:55.298  3799  5813 I SystemUpdateService: OTA package size = 21989297
,09-30 07:25:55.309  3799  5813 I SystemUpdateService: showing system update notification
,09-30 07:25:55.313  5777  5777 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 07:25:55.319  3799  3799 D SystemUpdateService: onDestroy
,09-30 07:25:55.418   929  2906 D wifi    : In wifi stop Hal
,09-30 07:25:55.418   929  2906 D wifi    : halHandle = 0x7f77a1e680, mVM = 0x7f9408d140, mCls = 0x195a
09-30 07:25:55.418   929  5776 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-30 07:25:55.418   929  5776 D WifiHAL : Got a signal to exit!!!
,09-30 07:25:55.418   929  5776 I WifiHAL : Exit wifi_event_loop
09-30 07:25:55.419   929  2906 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 07:25:55.419   929  2906 E WifiHAL : Event processing terminated
09-30 07:25:55.419   929  2906 D wifi    : In wifi cleaned up handler
09-30 07:25:55.419   929  2906 I WifiHAL : Internal cleanup completed
09-30 07:25:55.422  4039  4175 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 07:25:55.422  4976  4976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 07:25:55.422  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:55.425  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:55.426  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:25:55.443   929  5776 D wifi    : set interface wlan0 flags (DOWN)
,09-30 07:25:55.444   929  2906 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 07:25:55.648   929   946 D Tethering: InitialState.processMessage what=4
,09-30 07:25:55.655   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 07:25:55.997   929  2914 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-30 07:25:57.400   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:58.401   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:25:59.402   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:26:00.184   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d1aeae2:true
,09-30 07:26:00.185  5711  5711 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 07:26:00.189  5711  5711 I bt_bluedroid: init
,09-30 07:26:00.189  5711  5819 I BluetoothAdapterState: Entering OffState
,09-30 07:26:00.192  5711  5820 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 07:26:00.192  5711  5820 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 07:26:00.192  5711  5820 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-30 07:26:00.193  5711  5820 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-30 07:26:00.194  5711  5711 I bt_bluedroid: get_profile_interface socket
,09-30 07:26:00.197  5711  5823 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 07:26:00.198  5711  5711 I bt_bluedroid: get_profile_interface sdp
09-30 07:26:00.199  5711  5823 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 07:26:00.206  5711  5722 I bt_bluedroid: config_hci_snoop_log
,09-30 07:26:00.208   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 07:26:00.214  5711  5819 D BluetoothAdapterState: Current state: OFF, message: 0
,09-30 07:26:00.214  5711  5819 D BluetoothAdapterProperties: Setting state to 14
,09-30 07:26:00.214  5711  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 07:26:00.217  5711  5819 D BluetoothBondStateMachine: make
,09-30 07:26:00.219  5711  5824 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 07:26:00.222  5711  5819 I BluetoothAdapterState: Entering PendingCommandState
,09-30 07:26:00.224  5711  5711 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 07:26:00.227  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:00.227  5711  5711 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 07:26:00.228  5711  5711 D BtGatt.GattService: Received start request. Starting profile...
09-30 07:26:00.228  5711  5711 D BtGatt.GattService: start()
,09-30 07:26:00.228  5711  5711 I bt_bluedroid: get_profile_interface gatt
,09-30 07:26:00.230  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:00.230  5711  5711 D BtGatt.AdvertiseManager: advertise manager created
,09-30 07:26:00.237  5711  5711 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:00.237  5711  5711 V BluetoothAdapterState: isTurningOn()=false
09-30 07:26:00.237  5711  5711 V BluetoothAdapterState: isBleTurningOn()=true
09-30 07:26:00.237  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:00.237  5711  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 07:26:00.239  5711  5819 I bt_bluedroid: bt_bluedroid
,09-30 07:26:00.239  5711  5820 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 07:26:00.240  5711  5820 I bt_hci  : start_up
,09-30 07:26:00.247  5711  5820 I bt_vendor: alloc value 0xf3af8871
,09-30 07:26:00.247  5711  5820 I bt_vendor: init
09-30 07:26:00.247  5711  5820 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 07:26:00.247  5711  5820 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 07:26:00.359  5711  5820 D bt_hci  : start_up starting async portion
,09-30 07:26:00.359  5711  5827 I bt_hci  : event_finish_startup
,09-30 07:26:00.360  5711  5827 I bt_hci_h4: hal_open
09-30 07:26:00.360  5711  5827 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 07:26:00.378  5711  5827 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 07:26:00.381  5711  5827 D bt_hwcfg: Chipset BCM4358A3
09-30 07:26:00.381  5711  5827 D bt_hwcfg: Target name = [BCM4358A3]
09-30 07:26:00.381  5711  5827 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 07:26:00.403   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:26:00.772  5711  5827 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 07:26:00.773  5711  5827 D bt_hwcfg: Settlement delay -- 100 ms
09-30 07:26:00.773  5711  5827 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 07:26:00.907  5711  5827 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 07:26:00.907  5711  5827 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 07:26:00.909  5711  5827 I bt_hwcfg: vendor lib fwcfg completed
09-30 07:26:00.909  5711  5827 I bt_vendor: firmware callback
,09-30 07:26:00.909  5711  5827 I bt_hci  : firmware_config_callback
09-30 07:26:00.919  5711  5830 I bt_btu  : btu_task pending for preload complete event
,09-30 07:26:00.919  5711  5830 I bt_btu_task: Bluetooth chip preload is complete
09-30 07:26:00.919  5711  5830 I bt_btu  : btu_task received preload complete event
,09-30 07:26:00.927  5711  5830 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 07:26:00.928  5711  5830 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 07:26:00.928  5711  5830 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 07:26:00.928  5711  5830 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 07:26:00.928  5711  5830 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 07:26:00.928  5711  5830 I         : BTE_InitTraceLevels -- TRC_A2D
,09-30 07:26:00.928  5711  5830 I         : BTE_InitTraceLevels -- TRC_BNEP
09-30 07:26:00.929  5711  5830 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 07:26:00.929  5711  5830 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 07:26:00.929  5711  5830 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 07:26:00.929  5711  5830 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 07:26:00.929  5711  5830 I         : BTE_InitTraceLevels -- TRC_GATT
,09-30 07:26:00.929  5711  5830 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 07:26:00.929  5711  5830 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 07:26:00.930  5711  5830 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 07:26:01.013  5711  5830 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a76549
09-30 07:26:01.014  5711  5830 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a76549 
,09-30 07:26:01.037  5711  5823 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 07:26:01.039  5711  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 07:26:01.039  5711  5823 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 07:26:01.042  5711  5823 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 07:26:01.045  5711  5823 D BluetoothAdapterProperties: Scan Mode:20
09-30 07:26:01.045  5711  5823 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 07:26:01.045  5711  5823 D bt_hci  : do_postload posting postload work item
09-30 07:26:01.046  5711  5827 I bt_hci  : event_postload
09-30 07:26:01.046  5711  5827 I bt_vendor: sco_config_cb
09-30 07:26:01.046  5711  5827 I bt_hci  : sco_config_callback postload finished.
09-30 07:26:01.050  5711  5823 D bt_bte_conf: Device ID record 1 : primary
09-30 07:26:01.050  5711  5823 D bt_bte_conf:   vendorId            = 000f
09-30 07:26:01.050  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:01.050  5711  5823 D bt_bte_conf:   vendorIdSource      = 0001
09-30 07:26:01.050  5711  5823 D bt_bte_conf:   product             = 1200
09-30 07:26:01.050  5711  5823 D bt_bte_conf:   version             = 1436
09-30 07:26:01.050  5711  5823 D bt_bte_conf:   clientExecutableURL = 
09-30 07:26:01.050  5711  5823 D bt_bte_conf:   serviceDescription  = 
09-30 07:26:01.050  5711  5823 D bt_bte_conf:   documentationURL    = 
,09-30 07:26:01.050  5711  5823 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-30 07:26:01.051  5711  5820 D bt_stack_manager: event_start_up_stack finished
09-30 07:26:01.052  5711  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 07:26:01.052  5711  5819 D BluetoothAdapterProperties: Setting state to 15
09-30 07:26:01.052  5711  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 07:26:01.055  5711  5827 I bt_vendor: low_power_mode_cb
09-30 07:26:01.055  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:01.057  5711  5819 I BluetoothAdapterState: Entering BleOnState
09-30 07:26:01.058  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:01.058  5711  5819 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 07:26:01.058  5711  5819 D BluetoothAdapterProperties: Setting state to 11
09-30 07:26:01.058  5711  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 07:26:01.062  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:01.063  5711  5711 D HeadsetService: Received start request. Starting profile...
,09-30 07:26:01.066  5711  5711 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 07:26:01.067  5711  5711 D HeadsetStateMachine: make
09-30 07:26:01.067  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:01.069  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:01.072  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:01.080  5711  5819 I BluetoothAdapterState: Entering PendingCommandState
,09-30 07:26:01.080  5711  5711 D HeadsetStateMachine: max_hf_connections = 1
09-30 07:26:01.080  5711  5711 I bt_bluedroid: get_profile_interface handsfree
09-30 07:26:01.080  5711  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 07:26:01.080  5711  5823 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-30 07:26:01.083  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:01.084  5711  5711 D A2dpService: Received start request. Starting profile...
09-30 07:26:01.084  5711  5711 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 07:26:01.085  5711  5711 I bt_bluedroid: get_profile_interface avrcp
,09-30 07:26:01.091  5711  5711 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 07:26:01.091  5711  5711 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 07:26:01.091  5711  5711 D A2dpStateMachine: make
09-30 07:26:01.092  5711  5711 I bt_bluedroid: get_profile_interface a2dp
,09-30 07:26:01.093  5711  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 07:26:01.096  5711  5839 D A2dpStateMachine: Enter Disconnected: -2
,09-30 07:26:01.096  5711  5711 I BluetoothHidServiceJni: classInitNative: succeeds
,09-30 07:26:01.097  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:01.098  5638  5638 D BluetoothInputDevice: Proxy object connected
,09-30 07:26:01.099  5638  5638 D HidProfile: Bluetooth service connected
09-30 07:26:01.100  5711  5711 D HidService: Received start request. Starting profile...
09-30 07:26:01.100  5711  5711 I bt_bluedroid: get_profile_interface hidhost
09-30 07:26:01.100  5711  5711 D HidService: setHidService(): set to: null
09-30 07:26:01.100  5711  5823 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a5756d
09-30 07:26:01.100  5711  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 07:26:01.102  5711  5711 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 07:26:01.102  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 07:26:01.103  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:01.103  5711  5711 D HealthService: Received start request. Starting profile...
,09-30 07:26:01.104  5711  5711 I bt_bluedroid: get_profile_interface health
,09-30 07:26:01.105  5711  5711 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-30 07:26:01.106  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:01.107  5638  5638 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 07:26:01.107  5711  5711 D PanService: Received start request. Starting profile...
09-30 07:26:01.107  5711  5711 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 07:26:01.108  5711  5711 I bt_bluedroid: get_profile_interface pan
09-30 07:26:01.108  5638  5638 D PanProfile: Bluetooth service connected
09-30 07:26:01.108  5711  5823 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 07:26:01.111  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:01.112  5711  5711 D BluetoothMapService: Received start request. Starting profile...
,09-30 07:26:01.112  5711  5711 D BluetoothMapService: start()
09-30 07:26:01.114  5711  5711 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 07:26:01.115  5711  5711 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 07:26:01.115  5711  5711 D BluetoothMapAppObserver: createReceiver()
09-30 07:26:01.116  5711  5711 D BluetoothMapAppObserver: initObservers()
09-30 07:26:01.116  5711  5711 D BluetoothMapAppObserver: getEnabledAccountItems()
09-30 07:26:01.119  5638  5638 D BluetoothMap: Proxy object connected
,09-30 07:26:01.120  5638  5638 D MapProfile: Bluetooth service connected
09-30 07:26:01.120  5638  5638 D BluetoothMap: getConnectedDevices()
,09-30 07:26:01.121  5638  5638 D BluetoothMap: Bluetooth is Not enabled
,09-30 07:26:01.122  5711  5711 V SapService: SapBinder()
09-30 07:26:01.123  5711  5711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:01.123  5711  5711 D SapService: Received start request. Starting profile...
,09-30 07:26:01.123  5711  5711 V SapService: start()
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:01.125  5711  5836 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:01.125  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:01.126  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:01.127  5711  5711 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:01.127  5711  5711 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:01.127  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:01.127  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:01.127  5711  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 07:26:01.127  5711  5819 D BluetoothAdapterProperties: ScanMode =  20
09-30 07:26:01.128  5711  5819 D BluetoothAdapterProperties: State =  11
09-30 07:26:01.128  5711  5819 D BluetoothAdapterProperties: Setting state to 12
09-30 07:26:01.128  5711  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 07:26:01.128  5711  5819 I BluetoothAdapterState: Entering OnState
,09-30 07:26:01.129  5638  5651 D BluetoothMap: onBluetoothStateChange: up=true
09-30 07:26:01.129  5711  5823 D BluetoothAdapterProperties: Scan Mode:21
,09-30 07:26:01.129  3076  3932 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 07:26:01.129  5711  5823 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 07:26:01.130  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 07:26:01.132  5638  5649 D BluetoothPan: onBluetoothStateChange on: true
09-30 07:26:01.132  3076  3076 D BluetoothA2dp: Proxy object connected
09-30 07:26:01.132  3076  3090 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 07:26:01.134  5638  5651 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 07:26:01.134  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:01.134  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:01.134  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:01.134  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:01.134  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:01.134  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:01.134  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:01.134  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:01.134  3076  3076 D BluetoothInputDevice: Proxy object connected
09-30 07:26:01.134  3076  3076 D HidProfile: Bluetooth service connected
09-30 07:26:01.135  5638  5649 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 07:26:01.135   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:01.135  3076  3088 D BluetoothMap: onBluetoothStateChange: up=true
,09-30 07:26:01.136  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:01.137   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:01.137  3076  3076 D BluetoothMap: Proxy object connected
09-30 07:26:01.137  3076  3076 D MapProfile: Bluetooth service connected
09-30 07:26:01.137  3076  3076 D BluetoothMap: getConnectedDevices()
09-30 07:26:01.137  3076  3090 D BluetoothPan: onBluetoothStateChange on: true
09-30 07:26:01.138   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 07:26:01.139  3076  3932 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:01.139   929   929 D BluetoothA2dp: Proxy object connected
09-30 07:26:01.140  3723  3749 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:01.140   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:01.140  3076  3090 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 07:26:01.141  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:01.141  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:01.141  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:01.141  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:01.141  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:01.141  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:01.141  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:01.141  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:01.142  5711  5711 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 07:26:01.142  5711  5711 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-30 07:26:01.144  3076  3076 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 07:26:01.144  3076  3076 D PanProfile: Bluetooth service connected
09-30 07:26:01.144  5711  5711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 07:26:01.144  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:01.144   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-30 07:26:01.148  5638  5638 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-30 07:26:01.148  5711  5711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 07:26:01.149  5711  5711 D ObexServerSockets: Succeed to create listening sockets 
09-30 07:26:01.149  5711  5711 D ObexServerSockets0: startAccept()
09-30 07:26:01.149  5711  5711 D ObexServerSockets0: prepareForNewConnect()
09-30 07:26:01.151  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:01.151  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:01.151  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:01.151  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:01.151  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:01.151  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:01.151  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:01.151  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:01.152  5638  5638 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-30 07:26:01.152  5711  5711 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 07:26:01.152  5711  5711 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 07:26:01.155  5711  5846 D ObexServerSockets0: Accepting socket connection...
09-30 07:26:01.155  5711  5847 D ObexServerSockets0: Accepting socket connection...
09-30 07:26:01.155  5711  5711 D BluetoothMapService: onReceive
09-30 07:26:01.155  5711  5711 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 07:26:01.155  5711  5711 D BluetoothMapService: STATE_ON
,09-30 07:26:01.155  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:01.155  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 07:26:01.157  5711  5848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 07:26:01.157  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:01.158  5711  5848 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 07:26:01.158  5711  5848 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-30 07:26:01.159  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 07:26:01.159  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:01.160  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:01.161  5638  5638 D BluetoothA2dp: Proxy object connected
,09-30 07:26:01.167  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 07:26:01.170  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,09-30 07:26:01.173  5638  5638 D BluetoothPbap: Proxy object connected
09-30 07:26:01.174  5638  5638 D PbapServerProfile: Bluetooth service connected
,09-30 07:26:01.175  3076  3076 D BluetoothPbap: Proxy object connected
,09-30 07:26:01.175  3076  3076 D PbapServerProfile: Bluetooth service connected
,09-30 07:26:01.179  5711  5711 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 07:26:01.179  5711  5711 D ObexServerSockets0: prepareForNewConnect()
,09-30 07:26:01.181  5711  5852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 07:26:01.193  5711  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 07:26:01.194  5711  5856 I BtOppRfcommListener: Accept thread started.
,09-30 07:26:01.237   929   946 D BluetoothHeadset: Proxy object connected
,09-30 07:26:01.237  3723  3950 D BluetoothHeadset: Proxy object connected
09-30 07:26:01.238   929   929 D BluetoothHeadset: Proxy object connected
,09-30 07:26:01.238  3076  3932 D BluetoothHeadset: Proxy object connected
09-30 07:26:01.238  3076  3076 D HeadsetProfile: Bluetooth service connected
09-30 07:26:01.238   929   929 D BluetoothHeadset: Proxy object connected
09-30 07:26:01.238   929   929 D BluetoothHeadset: Proxy object connected
,09-30 07:26:01.240  3076  3090 D BluetoothHeadset: Proxy object connected
,09-30 07:26:01.240  3723  3745 D BluetoothHeadset: Proxy object connected
09-30 07:26:01.241   929   946 D BluetoothHeadset: Proxy object connected
09-30 07:26:01.241  3076  3076 D HeadsetProfile: Bluetooth service connected
,09-30 07:26:01.255  5638  5651 D BluetoothHeadset: Proxy object connected
,09-30 07:26:01.256  5638  5638 D HeadsetProfile: Bluetooth service connected
,09-30 07:26:01.404   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:26:02.405   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 07:26:02.955   929  2914 D ConnectivityService: handlePromptUnvalidated 101
,09-30 07:26:05.165  5711  5819 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 07:26:05.165  5711  5819 D BluetoothAdapterProperties: Setting state to 13
,09-30 07:26:05.165  5711  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 07:26:05.166  5711  5819 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 07:26:05.167  5711  5819 I BluetoothAdapterState: Entering PendingCommandState
,09-30 07:26:05.176  5711  5823 D BluetoothAdapterProperties: Scan Mode:20
09-30 07:26:05.176  5711  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-30 07:26:05.181  5711  5711 D BluetoothMapService: onReceive
,09-30 07:26:05.181  5711  5711 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-30 07:26:05.181  5711  5711 D BluetoothMapService: STATE_TURNING_OFF
09-30 07:26:05.182  5711  5711 D BluetoothMapService: MAP Service closeService in
09-30 07:26:05.182  5711  5711 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 07:26:05.183  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:26:05.183  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:05.183  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:05.183  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:05.183  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:05.183  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:26:05.183  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:05.183  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:05.183  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:05.183  5711  5711 D ObexServerSockets0: shutdown(block = true)
09-30 07:26:05.185  5711  5711 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 07:26:05.185  5711  5846 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-30 07:26:05.186  5711  5711 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 07:26:05.186  5711  5832 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 07:26:05.186  5711  5847 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 07:26:05.187  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:26:05.187  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:05.188  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 07:26:05.190  5711  5711 I BtOppRfcommListener: stopping Accept Thread
09-30 07:26:05.190  5711  5856 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 07:26:05.190  5711  5856 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 07:26:05.192  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:26:05.192  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:05.192  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:05.192  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:05.192  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:05.192  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:26:05.192  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:05.192  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:05.192  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:05.193  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:26:05.193  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 07:26:05.196  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 07:26:05.197  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:05.197  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:05.197  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:05.197  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:05.197  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 07:26:05.197  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:05.197  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:05.197  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 07:26:05.198  5711  5711 D HeadsetService: Received stop request...Stopping profile...
09-30 07:26:05.198  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 07:26:05.198  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:05.200  3723  3749 D BluetoothHeadset: Proxy object disconnected
09-30 07:26:05.201  5638  5651 D BluetoothHeadset: Proxy object disconnected
,09-30 07:26:05.202  5711  5711 D A2dpService: Received stop request...Stopping profile...
09-30 07:26:05.202   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 07:26:05.202  5711  5839 D A2dpStateMachine: Exit Disconnected: -1
09-30 07:26:05.202  3076  3088 D BluetoothHeadset: Proxy object disconnected
,09-30 07:26:05.202  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:05.202   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 07:26:05.202   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 07:26:05.203   929   929 D BluetoothA2dp: Proxy object disconnected
09-30 07:26:05.204  3076  3076 D HeadsetProfile: Bluetooth service disconnected
09-30 07:26:05.205  3076  3076 D BluetoothA2dp: Proxy object disconnected
09-30 07:26:05.205  5711  5711 D HidService: Received stop request...Stopping profile...
09-30 07:26:05.205  5711  5711 D HidService: Stopping Bluetooth HidService
09-30 07:26:05.206  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:05.208  5711  5711 D HealthService: Received stop request...Stopping profile...
09-30 07:26:05.209  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:05.209  3076  3076 D BluetoothInputDevice: Proxy object disconnected
09-30 07:26:05.209  3076  3076 D HidProfile: Bluetooth service disconnected
09-30 07:26:05.210  5711  5711 D PanService: Received stop request...Stopping profile...
09-30 07:26:05.210  5638  5638 D DockEventReceiver: finishStartingService: stopping service
09-30 07:26:05.211  3076  3076 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 07:26:05.211  3076  3076 D PanProfile: Bluetooth service disconnected
09-30 07:26:05.211  5638  5638 D HeadsetProfile: Bluetooth service disconnected
,09-30 07:26:05.212  5711  5711 V BluetoothAdapterState: isTurningOff()=true
09-30 07:26:05.212  5711  5711 V BluetoothAdapterState: isTurningOn()=false
09-30 07:26:05.212  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:05.212  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:05.212  5638  5638 D BluetoothA2dp: Proxy object disconnected
09-30 07:26:05.212  5638  5638 D BluetoothInputDevice: Proxy object disconnected
09-30 07:26:05.212  5638  5638 D HidProfile: Bluetooth service disconnected
09-30 07:26:05.212  5711  5711 D BluetoothMapService: Received stop request...Stopping profile...
09-30 07:26:05.213  5711  5711 D BluetoothMapService: stop()
09-30 07:26:05.213  5638  5638 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 07:26:05.213  5638  5638 D PanProfile: Bluetooth service disconnected
09-30 07:26:05.214  5711  5711 D BluetoothMapAppObserver: deinitObservers()
09-30 07:26:05.214  5711  5711 D BluetoothMapAppObserver: removeReceiver()
09-30 07:26:05.215  3076  3076 D BluetoothMap: Proxy object disconnected
09-30 07:26:05.215  3076  3076 D MapProfile: Bluetooth service disconnected
09-30 07:26:05.216  5638  5638 D BluetoothMap: Proxy object disconnected
09-30 07:26:05.216  5638  5638 D MapProfile: Bluetooth service disconnected
09-30 07:26:05.217  5711  5711 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 07:26:05.217  5711  5711 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 07:26:05.217  5711  5830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:26:05.217  5711  5830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:26:05.217  5711  5711 V BluetoothAdapterState: isTurningOff()=true
09-30 07:26:05.217  5711  5830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:26:05.217  5711  5711 V BluetoothAdapterState: isTurningOn()=false
09-30 07:26:05.218  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:05.218  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:05.219  5711  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 07:26:05.219  5711  5823 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 07:26:05.219  5711  5830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:26:05.219  5711  5830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:26:05.219  5711  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 07:26:05.220  5711  5711 D SapService: Received stop request...Stopping profile...
09-30 07:26:05.220  5711  5711 V SapService: stop()
09-30 07:26:05.220  5711  5830 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 07:26:05.220  5711  5830 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 07:26:05.220  5711  5830 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 07:26:05.220  5711  5830 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 07:26:05.222  5711  5711 V BluetoothAdapterState: isTurningOff()=true
09-30 07:26:05.222  5711  5711 V BluetoothAdapterState: isTurningOn()=false
09-30 07:26:05.222  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:05.222  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:05.222  5711  5711 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 07:26:05.222  5711  5711 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 07:26:05.222  5711  5823 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 07:26:05.222  5711  5711 V BluetoothAdapterState: isTurningOff()=true
09-30 07:26:05.222  5711  5711 V BluetoothAdapterState: isTurningOn()=false
,09-30 07:26:05.222  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:05.222  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:05.223  5711  5711 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 07:26:05.223  5711  5711 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 07:26:05.223  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 07:26:05.224  5711  5711 V BluetoothAdapterState: isTurningOff()=true
09-30 07:26:05.224  5711  5711 V BluetoothAdapterState: isTurningOn()=false
,09-30 07:26:05.224  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:05.224  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:05.224  5711  5711 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 07:26:05.224  5711  5711 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 07:26:05.228  5711  5823 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 07:26:05.228  5711  5711 D BluetoothMapService: MAP Service closeService in
09-30 07:26:05.229  5711  5711 V BluetoothAdapterState: isTurningOff()=true
09-30 07:26:05.229  5711  5711 V BluetoothAdapterState: isTurningOn()=false
09-30 07:26:05.229  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:05.229  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:05.229  5711  5711 D BluetoothMapService: cleanup()
09-30 07:26:05.229  5711  5711 D BluetoothMapService: MAP Service closeService in
09-30 07:26:05.229  5711  5711 V BluetoothAdapterState: isTurningOff()=true
09-30 07:26:05.229  5711  5711 V BluetoothAdapterState: isTurningOn()=false
09-30 07:26:05.229  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:05.229  5711  5711 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:05.230  5711  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 07:26:05.230  5711  5819 D BluetoothAdapterProperties: Setting state to 15
09-30 07:26:05.230  5711  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 07:26:05.230  5711  5819 I BluetoothAdapterState: Entering BleOnState
09-30 07:26:05.231  5638  5638 D BluetoothPbap: Proxy object disconnected
,09-30 07:26:05.231  5638  5638 D PbapServerProfile: Bluetooth service disconnected
09-30 07:26:05.231  3076  3076 D BluetoothPbap: Proxy object disconnected
09-30 07:26:05.231  3076  3076 D PbapServerProfile: Bluetooth service disconnected
09-30 07:26:05.231  5638  5649 D BluetoothMap: onBluetoothStateChange: up=false
,09-30 07:26:05.236  3076  3088 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-30 07:26:05.237  5638  5651 D BluetoothPan: onBluetoothStateChange on: false
,09-30 07:26:05.238  3076  3932 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 07:26:05.238  5638  5649 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 07:26:05.239  5638  5651 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 07:26:05.240  5638  5649 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:26:05.241   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:26:05.241  3076  3090 D BluetoothMap: onBluetoothStateChange: up=false
09-30 07:26:05.242   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:26:05.242  3076  3088 D BluetoothPan: onBluetoothStateChange on: false
09-30 07:26:05.242   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 07:26:05.242  3076  3932 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:26:05.243  3723  3950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:26:05.243  5638  5651 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-30 07:26:05.244   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 07:26:05.244  3076  3090 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 07:26:05.244  5711  5819 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 07:26:05.244  5711  5819 D BluetoothAdapterProperties: Setting state to 16
09-30 07:26:05.244  5711  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 07:26:05.245  5711  5819 D BluetoothAdapterProperties: onBleDisable
09-30 07:26:05.245  5711  5819 I BluetoothAdapterState: Entering PendingCommandState
09-30 07:26:05.245  5711  5820 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 07:26:05.246  5711  5830 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-30 07:26:05.246  5711  5830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 07:26:05.249  5711  5823 D BluetoothAdapterProperties: Scan Mode:20
,09-30 07:26:05.250  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 07:26:05.251  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:05.252  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:05.254  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:05.257  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:05.258  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:05.258  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 07:26:05.262  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:05.262  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,09-30 07:26:05.462  5711  5823 I bt_hci  : shut_down
,09-30 07:26:05.472  5711  5827 D bt_hwcfg: hw_epilog_process
,09-30 07:26:05.472  5711  5827 I bt_vendor: low_power_mode_cb
,09-30 07:26:05.475  5711  5827 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-30 07:26:05.475  5711  5827 I bt_vendor: epilog_cb
09-30 07:26:05.475  5711  5827 I bt_hci  : epilog_finished_callback
,09-30 07:26:05.478  5711  5823 I bt_hci_h4: hal_close
,09-30 07:26:05.478  5711  5823 I bt_userial_vendor: device fd = 54 close
,09-30 07:26:05.601  5711  5820 D bt_stack_manager: event_shut_down_stack finished.
09-30 07:26:05.602  5711  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 07:26:05.606  5711  5819 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-30 07:26:05.606  5711  5711 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 07:26:05.609  5711  5711 D BtGatt.GattService: Received stop request...Stopping profile...
,09-30 07:26:05.609  5711  5711 D BtGatt.GattService: stop()
,09-30 07:26:05.609  5711  5711 D BtGatt.AdvertiseManager: advertise clients cleared
09-30 07:26:05.612  5711  5711 V BluetoothAdapterState: isTurningOff()=false
,09-30 07:26:05.612  5711  5711 V BluetoothAdapterState: isTurningOn()=false
,09-30 07:26:05.612  5711  5711 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 07:26:05.613  5711  5711 V BluetoothAdapterState: isBleTurningOff()=true
09-30 07:26:05.613  5711  5819 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 07:26:05.614  5711  5819 D BluetoothAdapterProperties: Setting state to 10
,09-30 07:26:05.614  5711  5819 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 07:26:05.615  5711  5819 I BluetoothAdapterState: Entering OffState
09-30 07:26:05.616   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-30 07:26:05.631  5711  5711 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 07:26:05.631  5711  5711 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 07:26:05.631  5711  5711 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-30 07:26:05.633  5711  5820 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 07:26:05.649  5711  5711 I art     : System.exit called, status: 0
,09-30 07:26:05.652  5711  5711 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 07:26:05.683   929  3551 I ActivityManager: Process com.android.bluetooth (pid 5711) has died
,09-30 07:26:10.163  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 07:26:10.163  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:10.169  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 07:26:10.171  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27fcc18 removed from the list
09-30 07:26:10.171  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:26:10.172  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:26:10.172  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:10.174  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:10.174  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23d3c56 added. We now have 4 listener(s)
09-30 07:26:10.175  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:10.177  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 07:26:10.177  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23d3c56 removed from the list
,09-30 07:26:10.177  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 07:26:10.177  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:10.177  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:10.179  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 07:26:10.199  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf914d7 added. We now have 4 listener(s)
09-30 07:26:10.199  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 07:26:15.207  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:15.245   929   946 I ActivityManager: Start proc 5866:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 07:26:15.325  5866  5866 D AdapterServiceConfig: Adding HeadsetService
,09-30 07:26:15.325  5866  5866 D AdapterServiceConfig: Adding A2dpService
09-30 07:26:15.325  5866  5866 D AdapterServiceConfig: Adding HidService
09-30 07:26:15.325  5866  5866 D AdapterServiceConfig: Adding HealthService
09-30 07:26:15.326  5866  5866 D AdapterServiceConfig: Adding PanService
09-30 07:26:15.326  5866  5866 D AdapterServiceConfig: Adding GattService
09-30 07:26:15.326  5866  5866 D AdapterServiceConfig: Adding BluetoothMapService
09-30 07:26:15.326  5866  5866 D AdapterServiceConfig: Adding SapService
,09-30 07:26:15.337  5866  5866 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 07:26:15.337   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@348bdf0:true
,09-30 07:26:15.339  5866  5866 I bt_bluedroid: init
09-30 07:26:15.339  5866  5878 I BluetoothAdapterState: Entering OffState
,09-30 07:26:15.342  5866  5879 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-30 07:26:15.342  5866  5879 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 07:26:15.342  5866  5879 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 07:26:15.342  5866  5879 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 07:26:15.343  5866  5866 I bt_bluedroid: get_profile_interface socket
,09-30 07:26:15.344  5866  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 07:26:15.345  5866  5866 I bt_bluedroid: get_profile_interface sdp
09-30 07:26:15.346  5866  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 07:26:15.354  5866  5877 I bt_bluedroid: config_hci_snoop_log
09-30 07:26:15.355   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 07:26:15.359  5866  5878 D BluetoothAdapterState: Current state: OFF, message: 0
09-30 07:26:15.359  5866  5878 D BluetoothAdapterProperties: Setting state to 14
09-30 07:26:15.359  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 07:26:15.361  5866  5878 D BluetoothBondStateMachine: make
,09-30 07:26:15.363  5866  5883 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 07:26:15.366  5866  5878 I BluetoothAdapterState: Entering PendingCommandState
,09-30 07:26:15.367  5866  5866 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-30 07:26:15.369  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:15.370  5866  5866 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 07:26:15.371  5866  5866 D BtGatt.GattService: Received start request. Starting profile...
09-30 07:26:15.371  5866  5866 D BtGatt.GattService: start()
09-30 07:26:15.371  5866  5866 I bt_bluedroid: get_profile_interface gatt
09-30 07:26:15.372  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:15.372  5866  5866 D BtGatt.AdvertiseManager: advertise manager created
,09-30 07:26:15.379  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,09-30 07:26:15.379  5866  5866 V BluetoothAdapterState: isTurningOn()=false
09-30 07:26:15.379  5866  5866 V BluetoothAdapterState: isBleTurningOn()=true
09-30 07:26:15.379  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:15.379  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 07:26:15.380  5866  5878 I bt_bluedroid: bt_bluedroid
09-30 07:26:15.381  5866  5879 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 07:26:15.381  5866  5879 I bt_hci  : start_up
,09-30 07:26:15.386  5866  5879 I bt_vendor: alloc value 0xf3b6d871
09-30 07:26:15.386  5866  5879 I bt_vendor: init
09-30 07:26:15.386  5866  5879 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 07:26:15.386  5866  5879 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 07:26:15.496  5866  5879 D bt_hci  : start_up starting async portion
09-30 07:26:15.497  5866  5886 I bt_hci  : event_finish_startup
,09-30 07:26:15.497  5866  5886 I bt_hci_h4: hal_open
09-30 07:26:15.497  5866  5886 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 07:26:15.501  5866  5886 I bt_userial_vendor: device fd = 54 open
,09-30 07:26:15.499  5887  5887 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 07:26:15.518  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 07:26:15.522  5866  5886 D bt_hwcfg: Chipset BCM4358A3
,09-30 07:26:15.522  5866  5886 D bt_hwcfg: Target name = [BCM4358A3]
09-30 07:26:15.523  5866  5886 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 07:26:16.038  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-30 07:26:16.038  5866  5886 D bt_hwcfg: Settlement delay -- 100 ms
,09-30 07:26:16.039  5866  5886 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 07:26:16.172  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 07:26:16.173  5866  5886 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 07:26:16.174  5866  5886 I bt_hwcfg: vendor lib fwcfg completed
09-30 07:26:16.174  5866  5886 I bt_vendor: firmware callback
09-30 07:26:16.175  5866  5886 I bt_hci  : firmware_config_callback
,09-30 07:26:16.185  5866  5889 I bt_btu  : btu_task pending for preload complete event
,09-30 07:26:16.185  5866  5889 I bt_btu_task: Bluetooth chip preload is complete
09-30 07:26:16.185  5866  5889 I bt_btu  : btu_task received preload complete event
,09-30 07:26:16.192  5866  5889 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 07:26:16.193  5866  5889 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 07:26:16.193  5866  5889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 07:26:16.193  5866  5889 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 07:26:16.193  5866  5889 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-30 07:26:16.193  5866  5889 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 07:26:16.193  5866  5889 I         : BTE_InitTraceLevels -- TRC_BNEP
09-30 07:26:16.194  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 07:26:16.194  5866  5889 I         : BTE_InitTraceLevels -- TRC_GAP
,09-30 07:26:16.194  5866  5889 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 07:26:16.194  5866  5889 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 07:26:16.194  5866  5889 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 07:26:16.194  5866  5889 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 07:26:16.194  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 07:26:16.194  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 07:26:16.296  5866  5889 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3aeb549
,09-30 07:26:16.296  5866  5889 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3aeb549 
,09-30 07:26:16.312  5866  5882 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 07:26:16.314  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 07:26:16.315  5866  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 07:26:16.318  5866  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 07:26:16.321  5866  5882 D BluetoothAdapterProperties: Scan Mode:20
09-30 07:26:16.321  5866  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 07:26:16.322  5866  5882 D bt_hci  : do_postload posting postload work item
09-30 07:26:16.322  5866  5886 I bt_hci  : event_postload
,09-30 07:26:16.322  5866  5886 I bt_vendor: sco_config_cb
09-30 07:26:16.322  5866  5886 I bt_hci  : sco_config_callback postload finished.
09-30 07:26:16.324  5866  5882 D bt_bte_conf: Device ID record 1 : primary
,09-30 07:26:16.324  5866  5882 D bt_bte_conf:   vendorId            = 000f
,09-30 07:26:16.324  5866  5882 D bt_bte_conf:   vendorIdSource      = 0001
09-30 07:26:16.325  5866  5882 D bt_bte_conf:   product             = 1200
09-30 07:26:16.325  5866  5882 D bt_bte_conf:   version             = 1436
09-30 07:26:16.325  5866  5882 D bt_bte_conf:   clientExecutableURL = 
,09-30 07:26:16.325  5866  5882 D bt_bte_conf:   serviceDescription  = 
09-30 07:26:16.325  5866  5882 D bt_bte_conf:   documentationURL    = 
09-30 07:26:16.325  5866  5882 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 07:26:16.325  5866  5879 D bt_stack_manager: event_start_up_stack finished
,09-30 07:26:16.326  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 07:26:16.326  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:16.326  5866  5878 D BluetoothAdapterProperties: Setting state to 15
09-30 07:26:16.327  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 07:26:16.327  5866  5878 I BluetoothAdapterState: Entering BleOnState
09-30 07:26:16.330  5866  5886 I bt_vendor: low_power_mode_cb
09-30 07:26:16.331  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:16.332  5866  5878 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 07:26:16.332  5866  5878 D BluetoothAdapterProperties: Setting state to 11
09-30 07:26:16.332  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-30 07:26:16.343  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:16.345  5866  5866 D HeadsetService: Received start request. Starting profile...
09-30 07:26:16.347  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:16.347  5866  5866 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-30 07:26:16.348  5866  5866 D HeadsetStateMachine: make
09-30 07:26:16.349  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:16.361  5866  5878 I BluetoothAdapterState: Entering PendingCommandState
,09-30 07:26:16.368  5866  5866 D HeadsetStateMachine: max_hf_connections = 1
09-30 07:26:16.369  5866  5866 I bt_bluedroid: get_profile_interface handsfree
,09-30 07:26:16.372  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 07:26:16.373  5866  5882 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-30 07:26:16.374  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:16.374  5866  5866 D A2dpService: Received start request. Starting profile...
09-30 07:26:16.375  5866  5866 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-30 07:26:16.375  5866  5866 I bt_bluedroid: get_profile_interface avrcp
,09-30 07:26:16.380  5866  5866 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 07:26:16.381  5866  5866 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 07:26:16.381  5866  5866 D A2dpStateMachine: make
09-30 07:26:16.382  5866  5866 I bt_bluedroid: get_profile_interface a2dp
,09-30 07:26:16.382  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-30 07:26:16.384  5866  5897 D A2dpStateMachine: Enter Disconnected: -2
09-30 07:26:16.385  5866  5866 I BluetoothHidServiceJni: classInitNative: succeeds
09-30 07:26:16.386  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:16.386  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 07:26:16.387  5866  5866 D HidService: Received start request. Starting profile...
09-30 07:26:16.387  5866  5866 I bt_bluedroid: get_profile_interface hidhost
09-30 07:26:16.387  5866  5866 D HidService: setHidService(): set to: null
09-30 07:26:16.388  5866  5866 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 07:26:16.389  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:16.390  5866  5866 D HealthService: Received start request. Starting profile...
,09-30 07:26:16.390  5866  5882 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3acc56d
09-30 07:26:16.390  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-30 07:26:16.391  5866  5866 I bt_bluedroid: get_profile_interface health
09-30 07:26:16.392  5866  5866 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 07:26:16.392  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:16.394  5866  5866 D PanService: Received start request. Starting profile...
09-30 07:26:16.394  5866  5866 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 07:26:16.394  5866  5866 I bt_bluedroid: get_profile_interface pan
09-30 07:26:16.394  5866  5882 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-30 07:26:16.396  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
09-30 07:26:16.397  5866  5866 D BluetoothMapService: Received start request. Starting profile...
09-30 07:26:16.397  5866  5866 D BluetoothMapService: start()
,09-30 07:26:16.400  5866  5866 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 07:26:16.400  5866  5866 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 07:26:16.401  5866  5866 D BluetoothMapAppObserver: createReceiver()
,09-30 07:26:16.402  5866  5866 D BluetoothMapAppObserver: initObservers()
,09-30 07:26:16.402  5866  5866 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 07:26:16.409  5866  5866 V SapService: SapBinder()
,09-30 07:26:16.409  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:16.409  5866  5866 D SapService: Received start request. Starting profile...
09-30 07:26:16.410  5866  5866 V SapService: start()
,09-30 07:26:16.412  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,09-30 07:26:16.413  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:16.413  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:16.413  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:16.413  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:16.413  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:16.413  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:16.413  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:16.414  5866  5895 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 07:26:16.414  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:16.414  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:16.414  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:16.414  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 07:26:16.414  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:16.414  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:16.415  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 07:26:16.416  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-30 07:26:16.416  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-30 07:26:16.416  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-30 07:26:16.417  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-30 07:26:16.417  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 07:26:16.417  5866  5878 D BluetoothAdapterProperties: ScanMode =  20
09-30 07:26:16.417  5866  5878 D BluetoothAdapterProperties: State =  11
09-30 07:26:16.417  5866  5878 D BluetoothAdapterProperties: Setting state to 12
,09-30 07:26:16.417  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 07:26:16.418  5638  5649 D BluetoothMap: onBluetoothStateChange: up=true
09-30 07:26:16.418  5866  5878 I BluetoothAdapterState: Entering OnState
09-30 07:26:16.418  5866  5882 D BluetoothAdapterProperties: Scan Mode:21
09-30 07:26:16.418  5866  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 07:26:16.419  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-30 07:26:16.420  3076  3090 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 07:26:16.422  5638  5649 D BluetoothPan: onBluetoothStateChange on: true
,09-30 07:26:16.423  3076  3076 D BluetoothA2dp: Proxy object connected
09-30 07:26:16.424  3076  3932 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 07:26:16.424  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:16.424  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:16.424  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:16.424  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:16.424  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:16.424  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:16.424  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:16.424  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:16.426  5638  5649 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 07:26:16.426  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:16.427  3076  3076 D BluetoothInputDevice: Proxy object connected
09-30 07:26:16.427  3076  3076 D HidProfile: Bluetooth service connected
09-30 07:26:16.427  5638  5651 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 07:26:16.429  5866  5866 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 07:26:16.429  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:16.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:16.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:16.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:16.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:16.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:16.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:16.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:16.429  5638  5638 D BluetoothMap: Proxy object connected
09-30 07:26:16.429  5638  5638 D MapProfile: Bluetooth service connected
09-30 07:26:16.429  5638  5638 D BluetoothMap: getConnectedDevices()
09-30 07:26:16.429  5638  5649 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:16.430   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:16.430  3076  3088 D BluetoothMap: onBluetoothStateChange: up=true
09-30 07:26:16.431  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:16.431   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:16.431  5866  5866 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 07:26:16.431  3076  3076 D BluetoothMap: Proxy object connected
,09-30 07:26:16.431  3076  3076 D MapProfile: Bluetooth service connected
09-30 07:26:16.431  3076  3076 D BluetoothMap: getConnectedDevices()
09-30 07:26:16.432  3076  3090 D BluetoothPan: onBluetoothStateChange on: true
09-30 07:26:16.433  3076  3076 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 07:26:16.433   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 07:26:16.433  3076  3076 D PanProfile: Bluetooth service connected
09-30 07:26:16.433  5866  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 07:26:16.434  3076  3932 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:16.434   929   929 D BluetoothA2dp: Proxy object connected
09-30 07:26:16.434  3723  3745 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:16.435  5866  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 07:26:16.435  5638  5651 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 07:26:16.436  5866  5866 D ObexServerSockets: Succeed to create listening sockets 
09-30 07:26:16.436  5866  5866 D ObexServerSockets0: startAccept()
09-30 07:26:16.436  5866  5866 D ObexServerSockets0: prepareForNewConnect()
09-30 07:26:16.438  5866  5866 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 07:26:16.438  5866  5866 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 07:26:16.439   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 07:26:16.439  5866  5904 D ObexServerSockets0: Accepting socket connection...
09-30 07:26:16.439  3076  3088 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 07:26:16.439  5866  5905 D ObexServerSockets0: Accepting socket connection...
09-30 07:26:16.442  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 07:26:16.442   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 07:26:16.443  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:16.443  5866  5866 D BluetoothMapService: onReceive
09-30 07:26:16.443  5866  5866 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 07:26:16.443  5866  5866 D BluetoothMapService: STATE_ON
,09-30 07:26:16.445  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:16.446  5638  5638 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 07:26:16.446  5638  5638 D PanProfile: Bluetooth service connected
09-30 07:26:16.446  5638  5638 D BluetoothInputDevice: Proxy object connected
09-30 07:26:16.446  5638  5638 D HidProfile: Bluetooth service connected
09-30 07:26:16.447  5866  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 07:26:16.448  5638  5638 D BluetoothA2dp: Proxy object connected
,09-30 07:26:16.448  5866  5906 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 07:26:16.448  5866  5906 D BluetoothSdpJni: SDP Create record success - handle: 1
09-30 07:26:16.453  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 07:26:16.460  3537  3537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 07:26:16.460  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,09-30 07:26:16.469  5866  5866 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 07:26:16.469  5638  5638 D BluetoothPbap: Proxy object connected
09-30 07:26:16.469  3076  3076 D BluetoothPbap: Proxy object connected
09-30 07:26:16.469  5866  5866 D ObexServerSockets0: prepareForNewConnect()
09-30 07:26:16.469  3076  3076 D PbapServerProfile: Bluetooth service connected
09-30 07:26:16.469  5638  5638 D PbapServerProfile: Bluetooth service connected
,09-30 07:26:16.476  5866  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 07:26:16.492  5866  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 07:26:16.494  5866  5914 I BtOppRfcommListener: Accept thread started.
,09-30 07:26:16.532  3723  3749 D BluetoothHeadset: Proxy object connected
,09-30 07:26:16.532   929   946 D BluetoothHeadset: Proxy object connected
09-30 07:26:16.532  5638  5903 D BluetoothHeadset: Proxy object connected
09-30 07:26:16.532   929   929 D BluetoothHeadset: Proxy object connected
,09-30 07:26:16.533  3076  3932 D BluetoothHeadset: Proxy object connected
,09-30 07:26:16.533  3076  3076 D HeadsetProfile: Bluetooth service connected
09-30 07:26:16.533   929   929 D BluetoothHeadset: Proxy object connected
09-30 07:26:16.533   929   929 D BluetoothHeadset: Proxy object connected
09-30 07:26:16.534  3076  3088 D BluetoothHeadset: Proxy object connected
09-30 07:26:16.535  3723  3950 D BluetoothHeadset: Proxy object connected
09-30 07:26:16.535  3076  3076 D HeadsetProfile: Bluetooth service connected
09-30 07:26:16.535  5638  5638 D HeadsetProfile: Bluetooth service connected
,09-30 07:26:16.538   929   946 D BluetoothHeadset: Proxy object connected
,09-30 07:26:20.225  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:20.225  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:20.225  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:20.225  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 07:26:20.225  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:20.225  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:20.225  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:20.225  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 07:26:20.231  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 07:26:20.232  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:20.232  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf914d7 removed from the list
09-30 07:26:20.232  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 07:26:20.232  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:20.232  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:20.235  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:20.235  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb191c4 added. We now have 4 listener(s)
09-30 07:26:20.235  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 07:26:20.238   929  3531 D WifiService: setWifiEnabled: false pid=5585, uid=10077
09-30 07:26:20.238   929  3531 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 07:26:22.406   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:26:23.407   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:26:24.408   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:26:25.249  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:25.250   929  3800 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,09-30 07:26:25.250   929  3800 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 07:26:25.257   509   917 D SoftapController: Softap fwReload - Ok
,09-30 07:26:25.262   509   917 D CommandListener: Setting iface cfg
,09-30 07:26:25.263   509   917 D CommandListener: Trying to bring down wlan0
,09-30 07:26:25.267   509   917 D CommandListener: Clearing all IP addresses on wlan0
,09-30 07:26:25.273   929  2906 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 07:26:25.410   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:26:25.951   929  2906 D wifi    : set interface wlan0 flags (UP)
,09-30 07:26:25.952   929  2906 I WifiHAL : Initializing wifi
,09-30 07:26:25.953   929  2906 I WifiHAL : Creating socket
,09-30 07:26:25.961   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 07:26:25.961   929  2906 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-30 07:26:25.961   929  2906 D wifi    : Did set static halHandle = 0x7f77a1e680
09-30 07:26:25.962   929  2906 D wifi    : halHandle = 0x7f77a1e680, mVM = 0x7f9408d140, mCls = 0x20157a
09-30 07:26:25.962   929  2906 D wifi    : array field set
,09-30 07:26:25.962   929  2906 I WifiNative-HAL: interface[0] = wlan0
,09-30 07:26:25.967   929  5919 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547467945600
,09-30 07:26:25.967   929  5919 D wifi    : waitForHalEvents called, vm = 0x7f9408d140, obj = 0x20157a, env = 0x7f7837ad00
,09-30 07:26:26.017  5920  5920 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 07:26:26.040  5920  5920 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 07:26:26.053  5920  5920 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 07:26:26.053  5920  5920 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 07:26:26.068   929  2906 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 07:26:26.075  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:26.082   929  2906 D WifiConfigStore: Loading config and enabling all networks 
,09-30 07:26:26.087  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:26.087  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:26.087  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:26.087  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:26.087  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:26.087  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:26.087  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:26.087  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:26.089  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:26.092  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:26.092  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:26.092  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:26.092  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:26.092  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:26.092  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 07:26:26.092  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 07:26:26.092  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 07:26:26.093   929  2906 D WifiConfigStore: loaded 0 passpoint configs
,09-30 07:26:26.093   929  2906 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 07:26:26.094   929  2906 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 07:26:26.094   929  2906 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-30 07:26:26.095  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 07:26:26.095   929  2906 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 07:26:26.096   929  2906 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 07:26:26.096   929  2906 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 07:26:26.096   929  2906 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-30 07:26:26.096  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:26.099   929  2906 D WifiNative-HAL: Setting external_sim to 1
09-30 07:26:26.100   929  2906 D wifi    : setting dfs flag to true, 0x7f7ba5fce0
09-30 07:26:26.100   929  2906 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 07:26:26.100   929  2906 D wifi    : setting scan oui 0x7f7ba5fce0
09-30 07:26:26.101   929  2906 D WifiHAL : Sending mac address OUI
,09-30 07:26:26.102  4976  4976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 07:26:26.105   929  2906 E native  : do suspend false
,09-30 07:26:26.116   929   929 D RttService: SCAN_AVAILABLE : 3
,09-30 07:26:26.116   929  3017 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-30 07:26:26.116   929  2906 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 07:26:26.116   509   917 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 07:26:26.117   509   917 D CommandListener: Setting iface cfg
,09-30 07:26:26.122   929  2905 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-30 07:26:26.122   929  2905 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 07:26:26.132   929  2905 D WifiNative-HAL: p2pGetDeviceAddress
09-30 07:26:26.132   929  2905 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 07:26:26.138   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302371 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-30 07:26:26.411   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:26:27.411   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 07:26:29.295  5920  5920 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 07:26:29.300  5920  5920 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 07:26:29.306  5920  5920 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 07:26:29.310  5920  5920 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 07:26:29.367   929  2906 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 07:26:29.368   929  2906 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 07:26:29.368   929  2906 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 07:26:29.379   929  2906 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 07:26:29.413   929  2906 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 07:26:29.415  5920  5920 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 07:26:29.838  5920  5920 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 07:26:29.879  5920  5920 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 07:26:29.880  5920  5920 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 07:26:29.888   929  2906 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-30 07:26:29.888   929  2906 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 07:26:29.888   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 07:26:29.904   929  2906 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 07:26:29.915   509   917 D CommandListener: Setting iface cfg
,09-30 07:26:29.921   929  2906 D WifiStateMachine: Start Dhcp Watchdog 3
,09-30 07:26:29.927   929  5925 D DhcpClient: Receive thread started
,09-30 07:26:29.932   929  2906 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 07:26:29.932   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 07:26:29.932   929  2914 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-30 07:26:30.012   929  2906 E native  : do suspend false
,09-30 07:26:30.026   929  5924 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 07:26:30.038   929  5925 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-30 07:26:30.039   929  5924 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-30 07:26:30.041   929  5924 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 07:26:30.058   929  5925 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 07:26:30.059   929  5924 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 07:26:30.062   509   917 D CommandListener: Setting iface cfg
,09-30 07:26:30.066   929  2906 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 07:26:30.073   929  5924 D DhcpClient: Scheduling renewal in 86399s
,09-30 07:26:30.087   929  2906 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 07:26:30.088   929  2906 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 07:26:30.089   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-30 07:26:30.091   929  2914 D ConnectivityService: Adding iface wlan0 to network 102
,09-30 07:26:30.103   929  2906 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 07:26:30.142   929  2914 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 07:26:30.142   929  2914 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-30 07:26:30.145   929  2914 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-30 07:26:30.150   929  2914 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-30 07:26:30.154   929  2914 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-30 07:26:30.162   929  2914 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 07:26:30.167   929  2914 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-30 07:26:30.167   929  2914 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-30 07:26:30.168   929  2914 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-30 07:26:30.168   929  2914 D ConnectivityService:    accepting network in place of null
09-30 07:26:30.168   929  2906 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 07:26:30.168   929  2906 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 07:26:30.168   929  2914 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 07:26:30.188   929  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306422, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 07:26:30.190   509   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 07:26:30.212   509   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 07:26:30.216   929  2914 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-30 07:26:30.216  3687  3866 W QCNEJ   : |CORE| network available: 102
09-30 07:26:30.216   929  2914 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 07:26:30.217   929  2914 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-30 07:26:30.219   929   946 D Tethering: MasterInitialState.processMessage what=3
09-30 07:26:30.222  3687  3866 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 07:26:30.223  3687  3866 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 07:26:30.223  3687  3866 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 07:26:30.227  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:30.227  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:30.227  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:30.227  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:30.227  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:30.227  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:30.227  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:26:30.227  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:26:30.228  5001  5024 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 07:26:30.228  5001  5024 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 07:26:30.230  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:30.229  5001  5024 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 07:26:30.230  5001  5024 E SarControlService: no key has been found,reset the power
09-30 07:26:30.231  3799  3799 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 07:26:30.234  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:30.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:30.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:30.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:30.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:30.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:30.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:26:30.234  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 07:26:30.234  5001  5038 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 07:26:30.235  5001  5038 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 07:26:30.235  5001  5038 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 07:26:30.235  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 07:26:30.235  5026  5026 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 07:26:30.237  5001  5038 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 07:26:30.237  5001  5038 D QC_RIL_,OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 07:26:30.237  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:30.237  5001  5038 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 07:26:30.237  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 07:26:30.237  5026  5026 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 07:26:30.238  3799  3799 D SystemUpdateService: onCreate
09-30 07:26:30.242  3799  3799 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 07:26:30.243  5026  5040 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e3d407 HexData = [00000000f003000000000000ffffffff]
09-30 07:26:30.243  5026  5040 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 07:26:30.244  5026  5040 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-30 07:26:30.244  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 07:26:30.244  5001  5012 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 07:26:30.245  5026  5040 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e3d407 HexData = [00000000f103000000000000ffffffff]
09-30 07:26:30.245  5026  5040 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 07:26:30.245  5026  5040 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-30 07:26:30.245  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 07:26:30.246  5001  5011 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 07:26:30.252  3799  3799 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 07:26:30.261  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 07:26:30.261  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:30.261  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:30.261  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:30.261  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:30.261  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:30.261  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:26:30.261  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:26:30.262  3799  5360 I iu.UploadsManager: num queued entries: 0
09-30 07:26:30.262   929  5922 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-30 07:26:30.262  3799  5360 I iu.UploadsManager: num updated entries: 0
09-30 07:26:30.262  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:30.263  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:30.263  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb191c4 removed from the list
09-30 07:26:30.263  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:26:30.263  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:30.263  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:30.264  3799  3799 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 07:26:30.266  3799  3799 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 07:26:30.267  5725  5725 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 07:26:30.270  5725  5725 D SprintDMHelper: simOperator: 
09-30 07:26:30.271  5725  5725 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 07:26:30.273  3799  5935 I SystemUpdateService: active receiver: enabled
,09-30 07:26:30.284  5585  5940 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-30 07:26:30.284  5585  5940 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 07:26:30.290  3799  5935 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 07:26:30.289  3799  5360 I iu.SyncManager: NEXT; no task
,09-30 07:26:30.307  3799  5935 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 07:26:30.307  3799  5935 I SystemUpdateService: now status is 0 (complete)
09-30 07:26:30.307  3799  5935 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 07:26:30.307  3799  5935 I SystemUpdateService: file has been verified
09-30 07:26:30.307  3799  5935 I SystemUpdateService: OTA package size = 21989297
,09-30 07:26:30.312  3799  5935 I SystemUpdateService: showing system update notification
,09-30 07:26:30.321  3799  3799 D SystemUpdateService: onDestroy
,09-30 07:26:30.330   929  5922 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 11:26:30 GMT], X-Android-Received-Millis=[1475234790329], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475234790290]}
,09-30 07:26:30.330   929  2914 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 07:26:30.330   929  2914 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-30 07:26:30.331   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 07:26:30.331   929  2914 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 07:26:30.435  4976  5941 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 07:26:32.955   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 07:26:33.297  5585  5949 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-30 07:26:33.297  5585  5940 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-30 07:26:33.298  5585  5940 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-30 07:26:33.298  5585  5949 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-30 07:26:33.299  5585  5949 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 07:26:33.299  5585  5940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 07:26:33.301  5585  5940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 07:26:33.301  5585  5949 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 07:26:33.303  5585  5951 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:33.303  5585  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:33.305  5585  5952 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:33.305  5585  5952 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 07:26:33.306  5585  5949 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 07:26:33.307  5585  5940 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 07:26:33.311  5585  5954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:33.311  5585  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:33.313  5585  5954 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:33.313  5585  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:33.313  5585  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 07:26:33.313  5585  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:33.313  5585  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 07:26:33.313  5585  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 07:26:33.314  5585  5953 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:33.314  5585  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 07:26:33.314  5585  5951 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 157, thread name: OutgoingSocketThread/Sender): Socket closed
,09-30 07:26:33.314  5585  5953 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:33.314  5585  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 07:26:33.314  5585  5952 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:33.314  5585  5952 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 07:26:33.314  5585  5953 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 07:26:33.314  5585  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 07:26:33.315  5585  5952 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 07:26:33.315  5585  5952 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 07:26:33.315  5585  5953 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 07:26:33.315  5585  5951 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:33.315  5585  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 07:26:33.315  5585  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-30 07:26:33.315  5585  5952 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 07:26:33.315  5585  5953 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 07:26:33.315  5585  5954 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 07:26:33.315  5585  5952 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 07:26:33.315  5585  5951 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 07:26:33.315  5585  5952 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 07:26:33.315  5585  5954 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 07:26:33.315  5585  5951 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 07:26:33.315  5585  5952 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 07:26:33.315  5585  5953 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 07:26:33.315  5585  5954 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 07:26:33.315  5585  5952 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 07:26:33.315  5585  5953 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 07:26:33.315  5585  5951 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:33.315  5585  5951 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 07:26:33.315  5585  5954 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:33.315  5585  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 07:26:33.315  5585  5952 I io.jxcore.node.IncomingSocketThread: The sending thread is done
,09-30 07:26:33.315  5585  5953 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 07:26:33.315  5585  5953 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 07:26:33.315  5585  5952 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
09-30 07:26:33.316  5585  5953 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
09-30 07:26:33.316  5585  5952 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:33.316  5585  5952 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 07:26:33.316  5585  5953 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:33.316  5585  5953 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-30 07:26:36.297  5585  5631 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-30 07:26:36.298  5585  5631 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-30 07:26:36.305  5585  5631 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@76eaa1b Bundle[{}]
,09-30 07:26:36.306  5585  5631 I io.jxcore.node.LifeCycleMonitor: start: OK
09-30 07:26:36.307  5585  5631 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-30 07:26:36.307  5585  5631 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-30 07:26:36.308  5585  5631 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-30 07:26:36.309  5585  5631 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-30 07:26:36.311  5585  5631 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-30 07:26:36.317  5585  5631 I System.out: Running OutgoingSocketThread
,09-30 07:26:36.320  5585  5955 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-30 07:26:36.320  5585  5955 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 07:26:38.173   929  2914 D ConnectivityService: handlePromptUnvalidated 102
,09-30 07:26:39.333  5585  5955 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-30 07:26:39.333  5585  5955 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-30 07:26:39.334  5585  5956 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-30 07:26:39.334  5585  5956 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 07:26:39.334  5585  5955 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 07:26:39.334  5585  5956 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 07:26:39.337  5585  5955 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 07:26:39.337  5585  5956 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 07:26:39.338  5585  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:39.338  5585  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 07:26:39.339  5585  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:39.339  5585  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 07:26:39.341  5585  5956 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 07:26:39.341  5585  5955 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 07:26:39.344  5585  5960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:39.344  5585  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 07:26:39.346  5585  5961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:39.346  5585  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:39.347  5585  5960 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:39.347  5585  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 07:26:39.347  5585  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 07:26:39.347  5585  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 07:26:39.347  5585  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 07:26:39.347  5585  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 07:26:39.348  5585  5961 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:39.348  5585  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 07:26:39.348  5585  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 07:26:39.348  5585  5959 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 170, thread name: IncomingSocketThread/Sender): Socket closed
09-30 07:26:39.348  5585  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 07:26:39.348  5585  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 07:26:39.348  5585  5960 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 07:26:39.348  5585  5960 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 07:26:39.348  5585  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 07:26:39.348  5585  5959 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:39.348  5585  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 07:26:39.348  5585  5958 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 169, thread name: OutgoingSocketThread/Sender): recvfrom failed: ECONNRESET (Connection reset by peer)
09-30 07:26:39.348  5585  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 07:26:39.348  5585  5960 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 07:26:39.348  5585  5959 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 07:26:39.348  5585  5958 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:39.348  5585  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 07:26:39.348  5585  5960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:39.348  5585  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 07:26:39.348  5585  5959 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 07:26:39.349  5585  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 07:26:39.349  5585  5958 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: ECONNRESET (Connection reset by peer)
09-30 07:26:39.349  5585  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:39.349  5585  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 07:26:39.349  5585  5961 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 07:26:39.349  5585  5958 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 07:26:39.349  5585  5961 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 07:26:39.349  5585  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 07:26:39.349  5585  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 07:26:39.349  5585  5961 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 07:26:39.349  5585  5961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 07:26:39.349  5585  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-30 07:26:41.142   929  2906 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-30 07:26:42.331  5585  5631 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-30 07:26:42.332  5585  5631 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-30 07:26:42.333  5585  5631 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-30 07:26:42.341  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 07:26:42.341  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9cf8ad added. We now have 3 listener(s)
,09-30 07:26:42.343  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 07:26:42.344  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.344  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.344  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:42.344  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b68c7e2 added. We now have 4 listener(s)
09-30 07:26:42.344  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.345  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 07:26:42.351  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:26:42.358  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:26:42.358  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:42.358  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:42.358  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:42.358  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:42.358  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:42.358  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:26:42.358  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:26:42.360  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:42.361  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:26:42.361  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 07:26:42.361  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b180630 added. We now have 4 listener(s)
09-30 07:26:42.363  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.363  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.363  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.363  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:42.364  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43d72a9 added. We now have 5 listener(s)
09-30 07:26:42.364  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.364  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:26:42.364  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:26:42.364  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 07:26:42.364  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:26:42.364  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.364  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:26:42.364  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.364  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 07:26:42.364  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:42.364  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9cf8ad removed from the list
09-30 07:26:42.364  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.365  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b68c7e2 removed from the list
09-30 07:26:42.368  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:42.369  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 07:26:42.369  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.369  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.370  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:42.371  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 07:26:42.371  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:26:42.371  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.371  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b68c7e2 not in the list
09-30 07:26:42.371  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.371  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.373  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:26:42.373  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.373  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.373  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43d72a9 removed from the list
09-30 07:26:42.373  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 07:26:42.373  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.373  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:42.373  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.373  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 07:26:42.373  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b180630 removed from the list
09-30 07:26:42.374  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 07:26:42.374  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecf802e added. We now have 3 listener(s)
09-30 07:26:42.376  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.376  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.376  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.377  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:42.377  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fbc7cf added. We now have 4 listener(s)
09-30 07:26:42.377  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.378  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 07:26:42.382  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:26:42.387  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:26:42.387  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:42.387  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:42.387  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:42.387  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:42.387  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:42.387  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:26:42.387  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:26:42.389  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:42.389  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:26:42.389  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 07:26:42.390  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8519065 added. We now have 4 listener(s)
,09-30 07:26:42.392  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.392  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.392  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.392  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:42.392  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d7713a added. We now have 5 listener(s)
09-30 07:26:42.392  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.393  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:26:42.393  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:42.393  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 07:26:42.393  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 07:26:42.393  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:26:42.393  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 07:26:42.397  5585  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 07:26:42.397  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 07:26:42.397  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 07:26:42.401  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 07:26:42.402  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 07:26:42.402  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 07:26:42.406  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 07:26:42.406  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 07:26:42.406  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-30 07:26:42.406  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 07:26:42.406  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 07:26:42.407  5585  5631 D BluetoothAdapter: STATE_ON
,09-30 07:26:42.410  5866  5902 D BtGatt.GattService: registerClient() - UUID=20e95949-d8f2-4bbf-8853-a8de28295cc4
09-30 07:26:42.411  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=20e95949-d8f2-4bbf-8853-a8de28295cc4, clientIf=5
,09-30 07:26:42.412  5585  5680 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 07:26:42.413  5866  5877 D BtGatt.GattService: start scan with filters
,09-30 07:26:42.417  5866  5885 D BtGatt.ScanManager: handling starting scan
09-30 07:26:42.417  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 07:26:42.417  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 07:26:42.417  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:26:42.417  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 07:26:42.417  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 07:26:42.417  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-30 07:26:42.417  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 07:26:42.419  5866  5885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d2edacc
,09-30 07:26:42.420  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 07:26:42.420  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 07:26:42.420  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 07:26:42.421  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 07:26:42.424  5585  5631 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 07:26:42.424  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 07:26:42.424  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 07:26:42.424  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.424  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 07:26:42.424  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.424  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 07:26:42.424  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 07:26:42.425  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 07:26:42.425  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 07:26:42.425  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 07:26:42.425  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 07:26:42.426  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:26:42.426  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 07:26:42.427  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:26:42.427  5866  5877 D BtGatt.GattService: stopScan() - queue size =1
09-30 07:26:42.427  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 07:26:42.428  5866  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 07:26:42.428  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 07:26:42.428  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 07:26:42.429  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 07:26:42.429  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:26:42.429  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 07:26:42.429  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 07:26:42.429  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 07:26:42.429  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 07:26:42.430  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:26:42.430  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-30 07:26:42.430  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 07:26:42.430  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 07:26:42.430  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 07:26:42.431  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:26:42.432  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:26:42.432  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:26:42.432  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:26:42.434  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:26:42.434  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:26:42.434  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:26:42.434  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:26:42.434  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.434  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:26:42.434  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.434  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 07:26:42.434  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 07:26:42.434  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecf802e removed from the list
09-30 07:26:42.435  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.435  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.435  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fbc7cf removed from the list
09-30 07:26:42.435  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:26:42.435  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.435  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
09-30 07:26:42.435  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 07:26:42.435  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.435  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:42.437  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.437  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:26:42.437  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.437  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fbc7cf not in the list
09-30 07:26:42.437  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.437  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.438  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:26:42.438  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.438  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.438  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d7713a removed from the list
09-30 07:26:42.438  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:26:42.438  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.438  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.438  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.438  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 07:26:42.438  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8519065 removed from the list
09-30 07:26:42.439  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 07:26:42.439  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b6706 added. We now have 3 listener(s)
09-30 07:26:42.441  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.441  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.441  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.441  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:42.441  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@752e1c7 added. We now have 4 listener(s)
09-30 07:26:42.441  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.442  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 07:26:42.446  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:26:42.446  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 07:26:42.447  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:26:42.450  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:26:42.450  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:42.450  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:42.450  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:42.450  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:42.450  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:42.450  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:26:42.450  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:26:42.452  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 07:26:42.452  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.452  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:42.452  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:26:42.452  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 07:26:42.453  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9a671d added. We now have 4 listener(s)
09-30 07:26:42.454  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.454  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.454  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.454  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 07:26:42.454  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96ed92 added. We now have 5 listener(s)
09-30 07:26:42.455  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.455  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:26:42.455  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:42.455  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:26:42.455  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 07:26:42.456  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 07:26:42.456  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:26:42.456  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 07:26:42.458  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:42.459  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 07:26:42.459  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.459  5585  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 07:26:42.459  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 07:26:42.460  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
,09-30 07:26:42.463  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 07:26:42.464  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 07:26:42.464  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 07:26:42.465  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 07:26:42.465  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.466  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 07:26:42.468  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 07:26:42.468  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 07:26:42.468  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 07:26:42.468  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 07:26:42.468  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 07:26:42.469  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:26:42.471  5866  5877 D BtGatt.GattService: registerClient() - UUID=db20adc5-fde9-42ee-90cc-cb46c8d8fde3
09-30 07:26:42.471  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 07:26:42.471  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.471  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=db20adc5-fde9-42ee-90cc-cb46c8d8fde3, clientIf=5
,09-30 07:26:42.472  5585  5680 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 07:26:42.472  5866  5893 D BtGatt.GattService: start scan with filters
09-30 07:26:42.474  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 07:26:42.474  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 07:26:42.474  5866  5885 D BtGatt.ScanManager: handling starting scan
09-30 07:26:42.474  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 07:26:42.474  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 07:26:42.474  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 07:26:42.474  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 07:26:42.474  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 07:26:42.476  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 07:26:42.476  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 07:26:42.476  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 07:26:42.477  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 07:26:42.479  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 07:26:42.479  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.480  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 07:26:42.480  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:26:42.481  5585  5631 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-30 07:26:42.481  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:26:42.481  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:26:42.481  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:26:42.481  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 07:26:42.481  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.481  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 07:26:42.481  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.481  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 07:26:42.481  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b6706 removed from the list
09-30 07:26:42.481  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.481  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@752e1c7 removed from the list
09-30 07:26:42.481  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:26:42.481  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 07:26:42.482  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:26:42.482  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 07:26:42.482  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.482  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:26:42.483  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.483  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:26:42.483  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.483  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@752e1c7 not in the list
09-30 07:26:42.483  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 07:26:42.483  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 07:26:42.483  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 07:26:42.484  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 07:26:42.484  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 07:26:42.484  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:26:42.485  5866  5902 D BtGatt.GattService: stopScan() - queue size =1
09-30 07:26:42.485  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 07:26:42.485  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:26:42.485  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
09-30 07:26:42.485  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 07:26:42.486  5866  5877 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 07:26:42.486  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 07:26:42.486  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 07:26:42.487  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 07:26:42.487  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:26:42.487  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 07:26:42.487  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 07:26:42.487  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-30 07:26:42.487  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 07:26:42.490  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:26:42.490  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 07:26:42.490  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 07:26:42.490  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-30 07:26:42.490  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 07:26:42.491  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:42.492  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 07:26:42.492  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.492  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.493  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:26:42.493  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96ed92 removed from the list
09-30 07:26:42.493  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:26:42.493  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:26:42.493  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 07:26:42.493  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.493  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.493  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.493  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 07:26:42.493  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9a671d removed from the list
09-30 07:26:42.494  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 07:26:42.494  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db250de added. We now have 3 listener(s)
,09-30 07:26:42.496  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.496  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.496  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.496  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:42.496  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34442bf added. We now have 4 listener(s)
09-30 07:26:42.496  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.497  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 07:26:42.497  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 07:26:42.497  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:26:42.499  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 07:26:42.503  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 07:26:42.503  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:26:42.503  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:26:42.503  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:42.503  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:42.503  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:42.503  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:42.503  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:42.503  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:26:42.503  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:26:42.505  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 07:26:42.506  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:26:42.506  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 07:26:42.506  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e05cd5 added. We now have 4 listener(s)
09-30 07:26:42.507  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.507  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.507  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.507  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 07:26:42.507  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8e9cea added. We now have 5 listener(s)
09-30 07:26:42.507  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.507  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:26:42.507  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-30 07:26:42.507  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 07:26:42.507  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:26:42.508  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 07:26:42.508  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:42.508  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 07:26:42.508  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.508  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
,09-30 07:26:42.510  5585  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 07:26:42.510  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 07:26:42.510  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:42.513  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 07:26:42.513  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.513  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 07:26:42.514  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 07:26:42.514  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 07:26:42.514  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 07:26:42.517  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 07:26:42.517  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-30 07:26:42.517  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 07:26:42.517  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 07:26:42.517  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 07:26:42.517  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 07:26:42.517  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.517  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:26:42.519  5866  5877 D BtGatt.GattService: registerClient() - UUID=846b46e0-fd11-4cf2-84e8-8e2023bf09a5
,09-30 07:26:42.520  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=846b46e0-fd11-4cf2-84e8-8e2023bf09a5, clientIf=5
,09-30 07:26:42.521  5585  5595 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 07:26:42.521  5866  5876 D BtGatt.GattService: start scan with filters
,09-30 07:26:42.523  5866  5885 D BtGatt.ScanManager: handling starting scan
09-30 07:26:42.523  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 07:26:42.523  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 07:26:42.523  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:26:42.524  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 07:26:42.524  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 07:26:42.524  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-30 07:26:42.524  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 07:26:42.527  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 07:26:42.527  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 07:26:42.527  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 07:26:42.528  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 07:26:42.529  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 07:26:42.529  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.529  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 07:26:42.532  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:26:42.532  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:26:42.532  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:26:42.532  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:26:42.532  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.532  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 07:26:42.532  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.532  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 07:26:42.532  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db250de removed from the list
09-30 07:26:42.532  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.532  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34442bf removed from the list
09-30 07:26:42.532  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:26:42.533  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 07:26:42.533  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.533  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 07:26:42.533  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 07:26:42.533  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:26:42.534  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 07:26:42.534  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.534  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
09-30 07:26:42.534  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 07:26:42.534  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.534  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:26:42.534  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.534  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34442bf not in the list
09-30 07:26:42.534  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 07:26:42.534  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 07:26:42.534  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 07:26:42.534  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 07:26:42.534  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 07:26:42.535  5585  5631 D BluetoothAdapter: STATE_ON
09-30 07:26:42.535  5866  5877 D BtGatt.GattService: stopScan() - queue size =1
09-30 07:26:42.536  5866  5893 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 07:26:42.536  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 07:26:42.536  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 07:26:42.536  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 07:26:42.536  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 07:26:42.537  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 07:26:42.537  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 07:26:42.537  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 07:26:42.537  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 07:26:42.537  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:26:42.538  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 07:26:42.538  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 07:26:42.538  5585  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 07:26:42.538  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 07:26:42.538  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:42.539  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 07:26:42.539  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.539  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.540  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:26:42.540  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8e9cea removed from the list
09-30 07:26:42.540  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:26:42.540  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 07:26:42.540  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.540  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 07:26:42.540  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.540  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.540  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 07:26:42.540  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e05cd5 removed from the list
09-30 07:26:42.540  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 07:26:42.540  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7319db6 added. We now have 3 listener(s)
09-30 07:26:42.542  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.542  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.542  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.542  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:42.542  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef1cab7 added. We now have 4 listener(s)
09-30 07:26:42.542  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.542  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 07:26:42.543  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 07:26:42.543  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.544  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 07:26:42.547  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 07:26:42.547  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.549  5585  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 07:26:42.549  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 07:26:42.549  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 07:26:42.549  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 07:26:42.549  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 07:26:42.549  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 07:26:42.549  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 07:26:42.549  5585  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 07:26:42.552  5585  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 07:26:42.552  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 07:26:42.553  5585  5631 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 07:26:42.553  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.553  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 07:26:42.553  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
09-30 07:26:42.553  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec8518d added. We now have 4 listener(s)
09-30 07:26:42.554  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 07:26:42.554  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 07:26:42.554  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 07:26:42.554  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 07:26:42.554  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@431df42 added. We now have 5 listener(s)
09-30 07:26:42.554  5585  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 07:26:42.554  5585  5631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 07:26:42.554  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:26:42.554  5585  5631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 07:26:42.554  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:26:42.554  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:42.554  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.555  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 07:26:42.555  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.555  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 07:26:42.555  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7319db6 removed from the list
09-30 07:26:42.555  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 07:26:42.555  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef1cab7 removed from the list
09-30 07:26:42.556  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 07:26:42.557  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 07:26:42.557  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 07:26:42.557  5585  5631 D io.jxcore.node.ConnectivityMonitor: stop
09-30 07:26:42.557  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 07:26:42.557  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.558  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.558  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.560  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.560  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 07:26:42.560  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.560  5585  5631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef1cab7 not in the list
09-30 07:26:42.560  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.560  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 07:26:42.561  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 07:26:42.562  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 07:26:42.562  5585  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 07:26:42.562  5585  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@431df42 removed from the list
09-30 07:26:42.562  5585  5631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 07:26:42.562  5585  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 07:26:42.562  5585  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 07:26:42.562  5585  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 07:26:42.562  5585  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 07:26:42.562  5585  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec8518d removed from the list
09-30 07:26:42.562  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 07:26:42.562  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 07:26:42.563  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-30 07:26:42.563  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-30 07:26:42.563  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-30 07:26:42.564  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:26:42.564  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-30 07:26:42.564  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 07:26:42.934  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 07:26:42.994  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 07:26:43.040  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 07:26:44.725  5585  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 07:26:44.725  5585  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:45.528  5585  5962 W !!      : call onHalfStreamCopied
,09-30 07:26:45.528  5585  5962 I testCopyDataAndClose: closing input stream
,09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 07:26:46.304  5585  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 07:26:50.065  5585  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-30 07:26:50.065  5585  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:50.504   929  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=326737, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 07:26:52.065  5585  5631 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 193. Connection data: Peer properties: [null null].
09-30 07:26:52.065  5585  5631 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:52.065  5585  5631 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 193, name: My test thread name)
,09-30 07:26:52.142  5585  5964 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-30 07:26:52.142  5585  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-30 07:26:52.142  5585  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-30 07:26:52.222  5585  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 07:26:52.222  5585  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:52.412   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 07:26:52.412   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 07:26:53.835  5585  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 07:26:57.550  5585  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-30 07:26:57.550  5585  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:57.550  5585  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 197, thread name: My test thread name). Connection data: Peer properties: [null null].
09-30 07:26:57.550  5585  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-30 07:26:57.551  5585  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-30 07:26:57.553  5585  5631 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 07:26:57.556  5585  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 07:26:57.556  5585  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 07:26:57.556  5585  5967 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 201, thread name: My test thread name): Test exception.
,09-30 07:26:57.557  5585  5967 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 07:26:57.557  5585  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 07:26:57.557  5585  5967 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,09-30 07:26:57.557  5585  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 07:26:57.557  5585  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 07:26:57.562  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-30 07:26:57.562  5585  5631 I jxcore-log: 
09-30 07:26:57.563  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-30 07:26:57.563  5585  5631 I jxcore-log: 
,09-30 07:26:57.563  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-30 07:26:57.563  5585  5631 I jxcore-log: 
09-30 07:26:57.563  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-30 07:26:57.563  5585  5631 I jxcore-log: 
09-30 07:26:57.563  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Total duration:  102796'
09-30 07:26:57.563  5585  5631 I jxcore-log: 
09-30 07:26:57.564  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Failures: 
09-30 07:26:57.564  5585  5631 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-30 07:26:57.564  5585  5631 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
09-30 07:26:57.564  5585  5631 I jxcore-log:      but: was ""
09-30 07:26:57.564  5585  5631 I jxcore-log: IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-30 07:26:57.564  5585  5631 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
09-30 07:26:57.564  5585  5631 I jxcore-log:      but: was ""
09-30 07:26:57.564  5585  5631 I jxcore-log: '
09-30 07:26:57.564  5585  5631 I jxcore-log: 
09-30 07:26:57.565  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-30 07:26:57.565  5585  5631 I jxcore-log: 
09-30 07:26:57.566  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-30 07:26:57.566  5585  5631 I jxcore-log: 
,09-30 07:26:57.569  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.569  5585  5631 I jxcore-log: 
09-30 07:26:57.570  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.570  5585  5631 I jxcore-log: 
09-30 07:26:57.570  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.570  5585  5631 I jxcore-log: 
09-30 07:26:57.570  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.570  5585  5631 I jxcore-log: 
09-30 07:26:57.571  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 07:26:57.571  5585  5631 I jxcore-log: 
,09-30 07:26:57.571  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 07:26:57.571  5585  5631 I jxcore-log: 
09-30 07:26:57.571  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.571  5585  5631 I jxcore-log: 
,09-30 07:26:57.572  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.572  5585  5631 I jxcore-log: 
09-30 07:26:57.572  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 07:26:57.572  5585  5631 I jxcore-log: 
09-30 07:26:57.572  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 07:26:57.572  5585  5631 I jxcore-log: 
09-30 07:26:57.572  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 07:26:57.572  5585  5631 I jxcore-log: 
,09-30 07:26:57.572  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.572  5585  5631 I jxcore-log: 
09-30 07:26:57.573  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.573  5585  5631 I jxcore-log: 
09-30 07:26:57.573  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.573  5585  5631 I jxcore-log: 
09-30 07:26:57.573  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.573  5585  5631 I jxcore-log: 
09-30 07:26:57.574  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.574  5585  5631 I jxcore-log: 
,09-30 07:26:57.574  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.574  5585  5631 I jxcore-log: 
09-30 07:26:57.574  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.574  5585  5631 I jxcore-log: 
09-30 07:26:57.574  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.574  5585  5631 I jxcore-log: 
09-30 07:26:57.575  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.575  5585  5631 I jxcore-log: 
,09-30 07:26:57.575  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.575  5585  5631 I jxcore-log: 
09-30 07:26:57.575  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.575  5585  5631 I jxcore-log: 
09-30 07:26:57.577  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.577  5585  5631 I jxcore-log: 
09-30 07:26:57.577  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.577  5585  5631 I jxcore-log: 
,09-30 07:26:57.577  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.577  5585  5631 I jxcore-log: 
09-30 07:26:57.577  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.577  5585  5631 I jxcore-log: 
09-30 07:26:57.578  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.578  5585  5631 I jxcore-log: 
09-30 07:26:57.578  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.578  5585  5631 I jxcore-log: 
,09-30 07:26:57.578  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.578  5585  5631 I jxcore-log: 
09-30 07:26:57.578  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.578  5585  5631 I jxcore-log: 
09-30 07:26:57.579  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.579  5585  5631 I jxcore-log: 
09-30 07:26:57.579  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.579  5585  5631 I jxcore-log: 
,09-30 07:26:57.579  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.579  5585  5631 I jxcore-log: 
09-30 07:26:57.579  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.579  5585  5631 I jxcore-log: 
09-30 07:26:57.579  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.579  5585  5631 I jxcore-log: 
09-30 07:26:57.580  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.580  5585  5631 I jxcore-log: 
09-30 07:26:57.580  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.580  5585  5631 I jxcore-log: 
09-30 07:26:57.580  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.580  5585  5631 I jxcore-log: 
09-30 07:26:57.580  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.580  5585  5631 I jxcore-log: 
09-30 07:26:57.581  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 07:26:57.581  5585  5631 I jxcore-log: 
09-30 07:26:57.581  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.581  5585  5631 I jxcore-log: 
09-30 07:26:57.581  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 07:26:57.581  5585  5631 I jxcore-log: 
09-30 07:26:57.581  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.581  5585  5631 I jxcore-log: 
09-30 07:26:57.581  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.581  5585  5631 I jxcore-log: 
09-30 07:26:57.582  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.582  5585  5631 I jxcore-log: 
09-30 07:26:57.582  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.582  5585  5631 I jxcore-log: 
09-30 07:26:57.582  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.582  5585  5631 I jxcore-log: 
09-30 07:26:57.582  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 07:26:57.582  ,5585  5631 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-30 07:26:57.583  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.583  5585  5631 I jxcore-log: 
09-30 07:26:57.583  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.583  5585  5631 I jxcore-log: 
09-30 07:26:57.583  5585  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 07:26:57.583  5585  5631 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-30 07:26:57.583  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 07:26:57.583  5585  5631 I jxcore-log: 
09-30 07:26:57.583  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 07:26:57.583  5585  5631 I jxcore-log: 
09-30 07:26:57.584  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 07:26:57.584  5585  5631 I jxcore-log: 
09-30 07:26:57.584  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 07:26:57.584  5585  5631 I jxcore-log: 
09-30 07:26:57.589  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-30 07:26:57.589  5585  5631 I jxcore-log: 
09-30 07:26:57.589  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - WARN testUtils: 'myNameCallback not set!'
09-30 07:26:57.589  5585  5631 I jxcore-log: 
,09-30 07:26:57.591  5585  5631 I jxcore-log: 2016-09-30 11:26:57 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-30 07:26:57.591  5585  5631 I jxcore-log: 
,09-30 07:26:57.595  5585  5585 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-30 07:26:59.622  5585  5631 I jxcore-log: 2016-09-30 11:26:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-30 07:26:59.622  5585  5631 I jxcore-log: 
,09-30 07:26:59.952  5585  5631 I jxcore-log: 2016-09-30 11:26:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-30 07:26:59.952  5585  5631 I jxcore-log: 
,09-30 07:26:59.967  5585  5631 I jxcore-log: 2016-09-30 11:26:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-30 07:26:59.967  5585  5631 I jxcore-log: 
,09-30 07:27:01.068  5585  5631 I jxcore-log: 2016-09-30 11:27:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-30 07:27:01.068  5585  5631 I jxcore-log: 
,09-30 07:27:01.230  5585  5631 I jxcore-log: 2016-09-30 11:27:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-30 07:27:01.230  5585  5631 I jxcore-log: 
,09-30 07:27:01.235  5585  5631 I jxcore-log: 2016-09-30 11:27:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-30 07:27:01.235  5585  5631 I jxcore-log: 
,09-30 07:27:01.240  5585  5631 I jxcore-log: 2016-09-30 11:27:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-30 07:27:01.240  5585  5631 I jxcore-log: 
,09-30 07:27:01.790  5585  5631 I jxcore-log: 2016-09-30 11:27:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-30 07:27:01.790  5585  5631 I jxcore-log: 
,09-30 07:27:01.842  5585  5631 I jxcore-log: 2016-09-30 11:27:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-30 07:27:01.842  5585  5631 I jxcore-log: 
,09-30 07:27:01.855  5585  5631 I jxcore-log: 2016-09-30 11:27:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-30 07:27:01.855  5585  5631 I jxcore-log: 
,09-30 07:27:01.859  5585  5631 I jxcore-log: 2016-09-30 11:27:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-30 07:27:01.859  5585  5631 I jxcore-log: 
,09-30 07:27:02.140  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-30 07:27:02.140  5585  5631 I jxcore-log: 
,09-30 07:27:02.265  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-30 07:27:02.265  5585  5631 I jxcore-log: 
,09-30 07:27:02.502  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-30 07:27:02.502  5585  5631 I jxcore-log: 
,09-30 07:27:02.513  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-30 07:27:02.513  5585  5631 I jxcore-log: 
,09-30 07:27:02.517  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-30 07:27:02.517  5585  5631 I jxcore-log: 
,09-30 07:27:02.652  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-30 07:27:02.652  5585  5631 I jxcore-log: 
,09-30 07:27:02.660  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-30 07:27:02.660  5585  5631 I jxcore-log: 
,09-30 07:27:02.688  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-30 07:27:02.688  5585  5631 I jxcore-log: 
,09-30 07:27:02.723  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-30 07:27:02.723  5585  5631 I jxcore-log: 
,09-30 07:27:02.730  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-30 07:27:02.730  5585  5631 I jxcore-log: 
,09-30 07:27:02.737  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-30 07:27:02.737  5585  5631 I jxcore-log: 
,09-30 07:27:02.752  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-30 07:27:02.752  5585  5631 I jxcore-log: 
,09-30 07:27:02.757  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-30 07:27:02.757  5585  5631 I jxcore-log: 
,09-30 07:27:02.762  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-30 07:27:02.762  5585  5631 I jxcore-log: 
,09-30 07:27:02.768  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-30 07:27:02.768  5585  5631 I jxcore-log: 
,09-30 07:27:02.781  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-30 07:27:02.781  5585  5631 I jxcore-log: 
,09-30 07:27:02.802  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-30 07:27:02.802  5585  5631 I jxcore-log: 
,09-30 07:27:02.811  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-30 07:27:02.811  5585  5631 I jxcore-log: 
,09-30 07:27:02.822  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-30 07:27:02.822  5585  5631 I jxcore-log: 
,09-30 07:27:02.831  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-30 07:27:02.831  5585  5631 I jxcore-log: 
,09-30 07:27:02.843  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-30 07:27:02.843  5585  5631 I jxcore-log: 
,09-30 07:27:02.853  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-30 07:27:02.853  5585  5631 I jxcore-log: 
,09-30 07:27:02.858  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-30 07:27:02.858  5585  5631 I jxcore-log: 
,09-30 07:27:02.879  5585  5631 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-30 07:27:02.880  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - INFO testUtils: 'BLE multiple advertisement supported'
09-30 07:27:02.880  5585  5631 I jxcore-log: 
,09-30 07:27:02.997  5585  5631 I jxcore-log: 2016-09-30 11:27:02 - DEBUG CoordinatedClient: 'connected to the test server'
09-30 07:27:02.997  5585  5631 I jxcore-log: 
,09-30 07:27:03.535  5585  5631 I jxcore-log: TAP version 13
09-30 07:27:03.535  5585  5631 I jxcore-log: 
,09-30 07:27:03.577  5585  5631 I jxcore-log: # setup
09-30 07:27:03.577  5585  5631 I jxcore-log: 
,09-30 07:27:04.498  5585  5631 I jxcore-log: # calling createNativeListener directly rejects
09-30 07:27:04.498  5585  5631 I jxcore-log: 
,09-30 07:27:04.528  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:04.528  5585  5631 I jxcore-log: 
,09-30 07:27:04.532  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'listening 44808'
09-30 07:27:04.532  5585  5631 I jxcore-log: 
,09-30 07:27:04.539  5585  5631 I jxcore-log: ok 1 Should throw
09-30 07:27:04.539  5585  5631 I jxcore-log: 
,09-30 07:27:04.549  5585  5631 I jxcore-log: # teardown
09-30 07:27:04.549  5585  5631 I jxcore-log: 
,09-30 07:27:04.634  5585  5631 I jxcore-log: # setup
09-30 07:27:04.634  5585  5631 I jxcore-log: 
,09-30 07:27:04.678  5585  5631 I jxcore-log: # emits incomingConnectionState
09-30 07:27:04.678  5585  5631 I jxcore-log: 
,09-30 07:27:04.722  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:04.722  5585  5631 I jxcore-log: 
,09-30 07:27:04.725  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'listening 39974'
09-30 07:27:04.725  5585  5631 I jxcore-log: 
,09-30 07:27:04.734  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:04.734  5585  5631 I jxcore-log: 
,09-30 07:27:04.737  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:04.737  5585  5631 I jxcore-log: 
,09-30 07:27:04.747  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'new mux'
09-30 07:27:04.747  5585  5631 I jxcore-log: 
,09-30 07:27:04.754  5585  5631 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-30 07:27:04.754  5585  5631 I jxcore-log: 
,09-30 07:27:04.771  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:04.771  5585  5631 I jxcore-log: 
,09-30 07:27:04.772  5585  5631 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-30 07:27:04.772  5585  5631 I jxcore-log: 
,09-30 07:27:04.779  5585  5631 I jxcore-log: # teardown
09-30 07:27:04.779  5585  5631 I jxcore-log: 
,09-30 07:27:04.823  5585  5631 I jxcore-log: # setup
09-30 07:27:04.823  5585  5631 I jxcore-log: 
,09-30 07:27:04.855  5585  5631 I jxcore-log: # emits routerPortConnectionFailed
09-30 07:27:04.855  5585  5631 I jxcore-log: 
,09-30 07:27:04.946  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:04.946  5585  5631 I jxcore-log: 
,09-30 07:27:04.948  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'listening 41353'
09-30 07:27:04.948  5585  5631 I jxcore-log: 
,09-30 07:27:04.954  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:04.954  5585  5631 I jxcore-log: 
,09-30 07:27:04.956  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:04.956  5585  5631 I jxcore-log: 
,09-30 07:27:04.958  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'new mux'
09-30 07:27:04.958  5585  5631 I jxcore-log: 
,09-30 07:27:04.984  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:04.984  5585  5631 I jxcore-log: 
,09-30 07:27:04.987  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:04.987  5585  5631 I jxcore-log: 
,09-30 07:27:04.991  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: ' $c@net.js:837:7
09-30 07:27:04.991  5585  5631 I jxcore-log: $09@net.js:829:13
09-30 07:27:04.991  5585  5631 I jxcore-log: '
09-30 07:27:04.991  5585  5631 I jxcore-log: 
,09-30 07:27:04.992  5585  5631 I jxcore-log: ok 4 tried to connect to right port
09-30 07:27:04.992  5585  5631 I jxcore-log: 
,09-30 07:27:04.993  5585  5631 I jxcore-log: ok 5 failed due to refused connection
09-30 07:27:04.993  5585  5631 I jxcore-log: 
09-30 07:27:04.994  5585  5631 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-30 07:27:04.994  5585  5631 I jxcore-log: 
,09-30 07:27:04.998  5585  5631 I jxcore-log: # teardown
09-30 07:27:04.998  5585  5631 I jxcore-log: 
,09-30 07:27:04.999  5585  5631 I jxcore-log: 2016-09-30 11:27:04 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:04.999  5585  5631 I jxcore-log: 
,09-30 07:27:05.081  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'mux close'
09-30 07:27:05.081  5585  5631 I jxcore-log: 
,09-30 07:27:05.088  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:05.088  5585  5631 I jxcore-log: 
,09-30 07:27:05.102  5585  5631 I jxcore-log: # setup
09-30 07:27:05.102  5585  5631 I jxcore-log: 
,09-30 07:27:05.148  5585  5631 I jxcore-log: # native server connections all up
09-30 07:27:05.148  5585  5631 I jxcore-log: 
,09-30 07:27:05.200  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:05.200  5585  5631 I jxcore-log: 
,09-30 07:27:05.205  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'listening 42348'
09-30 07:27:05.205  5585  5631 I jxcore-log: 
,09-30 07:27:05.215  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:05.215  5585  5631 I jxcore-log: 
,09-30 07:27:05.217  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:05.217  5585  5631 I jxcore-log: 
,09-30 07:27:05.219  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new mux'
09-30 07:27:05.219  5585  5631 I jxcore-log: 
,09-30 07:27:05.248  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:05.248  5585  5631 I jxcore-log: 
,09-30 07:27:05.252  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:05.252  5585  5631 I jxcore-log: 
,09-30 07:27:05.255  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:05.255  5585  5631 I jxcore-log: 
,09-30 07:27:05.258  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:05.258  5585  5631 I jxcore-log: 
,09-30 07:27:05.283  5585  5631 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-30 07:27:05.283  5585  5631 I jxcore-log: 
,09-30 07:27:05.284  5585  5631 I jxcore-log: ok 8 Send/recvd #1 should be same
09-30 07:27:05.284  5585  5631 I jxcore-log: 
,09-30 07:27:05.286  5585  5631 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-30 07:27:05.286  5585  5631 I jxcore-log: 
,09-30 07:27:05.287  5585  5631 I jxcore-log: ok 10 Send/recvd #2 should be same
09-30 07:27:05.287  5585  5631 I jxcore-log: 
09-30 07:27:05.290  5585  5631 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-30 07:27:05.290  5585  5631 I jxcore-log: 
,09-30 07:27:05.297  5585  5631 I jxcore-log: # teardown
09-30 07:27:05.297  5585  5631 I jxcore-log: 
,09-30 07:27:05.323  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:05.323  5585  5631 I jxcore-log: 
,09-30 07:27:05.325  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:05.325  5585  5631 I jxcore-log: 
09-30 07:27:05.327  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'mux close'
09-30 07:27:05.327  5585  5631 I jxcore-log: 
,09-30 07:27:05.331  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:05.331  5585  5631 I jxcore-log: 
,09-30 07:27:05.343  5585  5631 I jxcore-log: # setup
09-30 07:27:05.343  5585  5631 I jxcore-log: 
,09-30 07:27:05.379  5585  5631 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-30 07:27:05.379  5585  5631 I jxcore-log: 
,09-30 07:27:05.434  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:05.434  5585  5631 I jxcore-log: 
,09-30 07:27:05.440  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'listening 39508'
09-30 07:27:05.440  5585  5631 I jxcore-log: 
,09-30 07:27:05.448  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:05.448  5585  5631 I jxcore-log: 
,09-30 07:27:05.450  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:05.450  5585  5631 I jxcore-log: 
,09-30 07:27:05.457  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new mux'
09-30 07:27:05.457  5585  5631 I jxcore-log: 
,09-30 07:27:05.473  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:05.473  5585  5631 I jxcore-log: 
,09-30 07:27:05.477  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:05.477  5585  5631 I jxcore-log: 
,09-30 07:27:05.491  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:05.491  5585  5631 I jxcore-log: 
,09-30 07:27:05.505  5585  5631 I jxcore-log: ok 12 socket shouldn't close until after stream
09-30 07:27:05.505  5585  5631 I jxcore-log: 
,09-30 07:27:05.506  5585  5631 I jxcore-log: ok 13 incoming remains open
09-30 07:27:05.506  5585  5631 I jxcore-log: 
,09-30 07:27:05.513  5585  5631 I jxcore-log: # teardown
09-30 07:27:05.513  5585  5631 I jxcore-log: 
,09-30 07:27:05.542  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'mux close'
09-30 07:27:05.542  5585  5631 I jxcore-log: 
,09-30 07:27:05.546  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:05.546  5585  5631 I jxcore-log: 
,09-30 07:27:05.551  5585  5631 I jxcore-log: # setup
09-30 07:27:05.551  5585  5631 I jxcore-log: 
,09-30 07:27:05.645  5585  5631 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-30 07:27:05.645  5585  5631 I jxcore-log: 
,09-30 07:27:05.678  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:05.678  5585  5631 I jxcore-log: 
,09-30 07:27:05.682  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'listening 49511'
09-30 07:27:05.682  5585  5631 I jxcore-log: 
,09-30 07:27:05.691  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:05.691  5585  5631 I jxcore-log: 
,09-30 07:27:05.692  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:05.692  5585  5631 I jxcore-log: 
,09-30 07:27:05.694  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new mux'
09-30 07:27:05.694  5585  5631 I jxcore-log: 
,09-30 07:27:05.705  5585  5631 I jxcore-log: ok 14 we should not have gotten an error
09-30 07:27:05.705  5585  5631 I jxcore-log: 
,09-30 07:27:05.710  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:05.710  5585  5631 I jxcore-log: 
,09-30 07:27:05.715  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:05.715  5585  5631 I jxcore-log: 
,09-30 07:27:05.725  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:05.725  5585  5631 I jxcore-log: 
,09-30 07:27:05.727  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:05.727  5585  5631 I jxcore-log: 
,09-30 07:27:05.735  5585  5631 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-30 07:27:05.735  5585  5631 I jxcore-log: 
,09-30 07:27:05.736  5585  5631 I jxcore-log: ok 16 incoming is cleaned up
09-30 07:27:05.736  5585  5631 I jxcore-log: 
,09-30 07:27:05.744  5585  5631 I jxcore-log: # teardown
09-30 07:27:05.744  5585  5631 I jxcore-log: 
,09-30 07:27:05.813  5585  5631 I jxcore-log: # setup
09-30 07:27:05.813  5585  5631 I jxcore-log: 
,09-30 07:27:05.854  5585  5631 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-30 07:27:05.854  5585  5631 I jxcore-log: 
,09-30 07:27:05.898  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:05.898  5585  5631 I jxcore-log: 
,09-30 07:27:05.902  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'listening 38890'
09-30 07:27:05.902  5585  5631 I jxcore-log: 
,09-30 07:27:05.910  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:05.910  5585  5631 I jxcore-log: 
,09-30 07:27:05.911  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:05.911  5585  5631 I jxcore-log: 
09-30 07:27:05.914  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new mux'
09-30 07:27:05.914  5585  5631 I jxcore-log: 
,09-30 07:27:05.925  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:05.925  5585  5631 I jxcore-log: 
,09-30 07:27:05.928  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:05.928  5585  5631 I jxcore-log: 
,09-30 07:27:05.942  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:05.942  5585  5631 I jxcore-log: 
,09-30 07:27:05.951  5585  5631 I jxcore-log: ok 17 stream was closed
09-30 07:27:05.951  5585  5631 I jxcore-log: 
,09-30 07:27:05.952  5585  5631 I jxcore-log: ok 18 incoming should survive
09-30 07:27:05.952  5585  5631 I jxcore-log: 
09-30 07:27:05.952  5585  5631 I jxcore-log: ok 19 mux should have no streams
09-30 07:27:05.952  5585  5631 I jxcore-log: 
,09-30 07:27:05.958  5585  5631 I jxcore-log: # teardown
09-30 07:27:05.958  5585  5631 I jxcore-log: 
,09-30 07:27:05.977  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'mux close'
09-30 07:27:05.977  5585  5631 I jxcore-log: 
,09-30 07:27:05.987  5585  5631 I jxcore-log: 2016-09-30 11:27:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:05.987  5585  5631 I jxcore-log: 
,09-30 07:27:05.998  5585  5631 I jxcore-log: # setup
09-30 07:27:05.998  5585  5631 I jxcore-log: 
,09-30 07:27:06.098  5585  5631 I jxcore-log: # native server - closing the whole server cleans everything up
09-30 07:27:06.098  5585  5631 I jxcore-log: 
,09-30 07:27:06.140  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:06.140  5585  5631 I jxcore-log: 
,09-30 07:27:06.145  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'listening 49353'
09-30 07:27:06.145  5585  5631 I jxcore-log: 
,09-30 07:27:06.154  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.154  5585  5631 I jxcore-log: 
,09-30 07:27:06.156  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.156  5585  5631 I jxcore-log: 
,09-30 07:27:06.160  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.160  5585  5631 I jxcore-log: 
,09-30 07:27:06.169  5585  5631 I jxcore-log: ok 20 we should not have gotten an error
09-30 07:27:06.169  5585  5631 I jxcore-log: 
,09-30 07:27:06.175  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.175  5585  5631 I jxcore-log: 
,09-30 07:27:06.178  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.178  5585  5631 I jxcore-log: 
,09-30 07:27:06.187  5585  5631 I jxcore-log: ok 21 Buffers are identical
09-30 07:27:06.187  5585  5631 I jxcore-log: 
,09-30 07:27:06.189  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.189  5585  5631 I jxcore-log: 
,09-30 07:27:06.192  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.192  5585  5631 I jxcore-log: 
,09-30 07:27:06.194  5585  5631 I jxcore-log: ok 22 native server is nulled out
09-30 07:27:06.194  5585  5631 I jxcore-log: 
,09-30 07:27:06.195  5585  5631 I jxcore-log: ok 23 native server should be closed
09-30 07:27:06.195  5585  5631 I jxcore-log: 
09-30 07:27:06.195  5585  5631 I jxcore-log: ok 24 incoming has been removed
09-30 07:27:06.195  5585  5631 I jxcore-log: 
09-30 07:27:06.195  5585  5631 I jxcore-log: ok 25 Incoming should be done
09-30 07:27:06.195  5585  5631 I jxcore-log: 
09-30 07:27:06.195  5585  5631 I jxcore-log: ok 26 The mux object should be closed
09-30 07:27:06.195  5585  5631 I jxcore-log: 
09-30 07:27:06.196  5585  5631 I jxcore-log: ok 27 The mux stream should be closed
09-30 07:27:06.196  5585  5631 I jxcore-log: 
09-30 07:27:06.197  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.197  5585  5631 I jxcore-log: 
,09-30 07:27:06.209  5585  5631 I jxcore-log: # teardown
09-30 07:27:06.209  5585  5631 I jxcore-log: 
,09-30 07:27:06.245  5585  5631 I jxcore-log: # setup
09-30 07:27:06.245  5585  5631 I jxcore-log: 
,09-30 07:27:06.285  5585  5631 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-30 07:27:06.285  5585  5631 I jxcore-log: 
,09-30 07:27:06.321  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:06.321  5585  5631 I jxcore-log: 
,09-30 07:27:06.328  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'listening 42713'
09-30 07:27:06.328  5585  5631 I jxcore-log: 
,09-30 07:27:06.357  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.357  5585  5631 I jxcore-log: 
,09-30 07:27:06.358  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.358  5585  5631 I jxcore-log: 
09-30 07:27:06.359  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.359  5585  5631 I jxcore-log: 
,09-30 07:27:06.363  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.363  5585  5631 I jxcore-log: 
,09-30 07:27:06.364  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.364  5585  5631 I jxcore-log: 
09-30 07:27:06.365  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.365  5585  5631 I jxcore-log: 
,09-30 07:27:06.368  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.368  5585  5631 I jxcore-log: 
,09-30 07:27:06.369  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.369  5585  5631 I jxcore-log: 
,09-30 07:27:06.371  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.371  5585  5631 I jxcore-log: 
09-30 07:27:06.374  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.374  5585  5631 I jxcore-log: 
09-30 07:27:06.374  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.374  5585  5631 I jxcore-log: 
09-30 07:27:06.375  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.375  5585  5631 I jxcore-log: 
,09-30 07:27:06.379  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.379  5585  5631 I jxcore-log: 
,09-30 07:27:06.380  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.380  5585  5631 I jxcore-log: 
,09-30 07:27:06.383  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.383  5585  5631 I jxcore-log: 
,09-30 07:27:06.386  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.386  5585  5631 I jxcore-log: 
,09-30 07:27:06.387  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.387  5585  5631 I jxcore-log: 
,09-30 07:27:06.388  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.388  5585  5631 I jxcore-log: 
,09-30 07:27:06.390  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.390  5585  5631 I jxcore-log: 
,09-30 07:27:06.391  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.391  5585  5631 I jxcore-log: 
,09-30 07:27:06.392  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.392  5585  5631 I jxcore-log: 
,09-30 07:27:06.399  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.399  5585  5631 I jxcore-log: 
,09-30 07:27:06.399  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.399  5585  5631 I jxcore-log: 
,09-30 07:27:06.400  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.400  5585  5631 I jxcore-log: 
,09-30 07:27:06.401  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.401  5585  5631 I jxcore-log: 
,09-30 07:27:06.402  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.402  5585  5631 I jxcore-log: 
,09-30 07:27:06.402  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.402  5585  5631 I jxcore-log: 
,09-30 07:27:06.404  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:06.404  5585  5631 I jxcore-log: 
,09-30 07:27:06.404  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:06.404  5585  5631 I jxcore-log: 
,09-30 07:27:06.404  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new mux'
09-30 07:27:06.404  5585  5631 I jxcore-log: 
,09-30 07:27:06.460  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.460  5585  5631 I jxcore-log: 
,09-30 07:27:06.462  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.462  5585  5631 I jxcore-log: 
,09-30 07:27:06.463  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.463  5585  5631 I jxcore-log: 
,09-30 07:27:06.465  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.465  5585  5631 I jxcore-log: 
,09-30 07:27:06.465  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.465  5585  5631 I jxcore-log: 
09-30 07:27:06.466  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.466  5585  5631 I jxcore-log: 
,09-30 07:27:06.467  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.467  5585  5631 I jxcore-log: 
,09-30 07:27:06.468  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.468  5585  5631 I jxcore-log: 
,09-30 07:27:06.470  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.470  5585  5631 I jxcore-log: 
,09-30 07:27:06.471  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.471  5585  5631 I jxcore-log: 
,09-30 07:27:06.472  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.472  5585  5631 I jxcore-log: 
,09-30 07:27:06.473  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.473  5585  5631 I jxcore-log: 
,09-30 07:27:06.473  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.473  5585  5631 I jxcore-log: 
,09-30 07:27:06.474  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.474  5585  5631 I jxcore-log: 
09-30 07:27:06.475  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.475  5585  5631 I jxcore-log: 
09-30 07:27:06.476  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.476  5585  5631 I jxcore-log: 
09-30 07:27:06.477  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.477  5585  5631 I jxcore-log: 
,09-30 07:27:06.478  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.478  5585  5631 I jxcore-log: 
,09-30 07:27:06.479  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.479  5585  5631 I jxcore-log: 
,09-30 07:27:06.480  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.480  5585  5631 I jxcore-log: 
,09-30 07:27:06.480  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.480  5585  5631 I jxcore-log: 
,09-30 07:27:06.481  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.481  5585  5631 I jxcore-log: 
,09-30 07:27:06.482  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.482  5585  5631 I jxcore-log: 
09-30 07:27:06.483  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.483  5585  5631 I jxcore-log: 
09-30 07:27:06.484  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.484  5585  5631 I jxcore-log: 
,09-30 07:27:06.485  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.485  5585  5631 I jxcore-log: 
,09-30 07:27:06.485  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.485  5585  5631 I jxcore-log: 
,09-30 07:27:06.486  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.486  5585  5631 I jxcore-log: 
09-30 07:27:06.487  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.487  5585  5631 I jxcore-log: 
,09-30 07:27:06.488  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.488  5585  5631 I jxcore-log: 
09-30 07:27:06.488  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.488  5585  5631 I jxcore-log: 
,09-30 07:27:06.489  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.489  5585  5631 I jxcore-log: 
,09-30 07:27:06.490  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.490  5585  5631 I jxcore-log: 
09-30 07:27:06.491  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.491  5585  5631 I jxcore-log: 
,09-30 07:27:06.492  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.492  5585  5631 I jxcore-log: 
09-30 07:27:06.493  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.493  5585  5631 I jxcore-log: 
,09-30 07:27:06.493  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.493  5585  5631 I jxcore-log: 
,09-30 07:27:06.494  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.494  5585  5631 I jxcore-log: 
09-30 07:27:06.495  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.495  5585  5631 I jxcore-log: 
09-30 07:27:06.495  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.495  5585  5631 I jxcore-log: 
,09-30 07:27:06.497  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.497  5585  5631 I jxcore-log: 
,09-30 07:27:06.498  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.498  5585  5631 I jxcore-log: 
09-30 07:27:06.498  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.498  5585  5631 I jxcore-log: 
,09-30 07:27:06.499  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.499  5585  5631 I jxcore-log: 
09-30 07:27:06.500  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.500  5585  5631 I jxcore-log: 
,09-30 07:27:06.500  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.500  5585  5631 I jxcore-log: 
09-30 07:27:06.501  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.501  5585  5631 I jxcore-log: 
,09-30 07:27:06.502  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.502  5585  5631 I jxcore-log: 
,09-30 07:27:06.508  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.508  5585  5631 I jxcore-log: 
,09-30 07:27:06.510  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.510  5585  5631 I jxcore-log: 
,09-30 07:27:06.511  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.511  5585  5631 I jxcore-log: 
,09-30 07:27:06.512  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.512  5585  5631 I jxcore-log: 
,09-30 07:27:06.512  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.512  5585  5631 I jxcore-log: 
09-30 07:27:06.513  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.513  5585  5631 I jxcore-log: 
,09-30 07:27:06.514  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.514  5585  5631 I jxcore-log: 
09-30 07:27:06.515  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.515  5585  5631 I jxcore-log: 
,09-30 07:27:06.516  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.516  5585  5631 I jxcore-log: 
,09-30 07:27:06.517  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.517  5585  5631 I jxcore-log: 
09-30 07:27:06.518  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.518  5585  5631 I jxcore-log: 
,09-30 07:27:06.519  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.519  5585  5631 I jxcore-log: 
09-30 07:27:06.519  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.519  5585  5631 I jxcore-log: 
,09-30 07:27:06.520  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.520  5585  5631 I jxcore-log: 
09-30 07:27:06.521  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.521  5585  5631 I jxcore-log: 
,09-30 07:27:06.521  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.521  5585  5631 I jxcore-log: 
,09-30 07:27:06.522  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.522  5585  5631 I jxcore-log: 
,09-30 07:27:06.523  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.523  5585  5631 I jxcore-log: 
09-30 07:27:06.524  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.524  5585  5631 I jxcore-log: 
,09-30 07:27:06.525  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.525  5585  5631 I jxcore-log: 
09-30 07:27:06.525  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.525  5585  5631 I jxcore-log: 
,09-30 07:27:06.526  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.526  5585  5631 I jxcore-log: 
09-30 07:27:06.526  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.526  5585  5631 I jxcore-log: 
,09-30 07:27:06.527  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.527  5585  5631 I jxcore-log: 
,09-30 07:27:06.528  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.528  5585  5631 I jxcore-log: 
09-30 07:27:06.529  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.529  5585  5631 I jxcore-log: 
,09-30 07:27:06.529  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.529  5585  5631 I jxcore-log: 
09-30 07:27:06.530  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.530  5585  5631 I jxcore-log: 
,09-30 07:27:06.530  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.530  5585  5631 I jxcore-log: 
09-30 07:27:06.531  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.531  5585  5631 I jxcore-log: 
,09-30 07:27:06.532  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:06.532  5585  5631 I jxcore-log: 
09-30 07:27:06.532  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:06.532  5585  5631 I jxcore-log: 
,09-30 07:27:06.577  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.577  5585  5631 I jxcore-log: 
,09-30 07:27:06.578  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.578  5585  5631 I jxcore-log: 
,09-30 07:27:06.579  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.579  5585  5631 I jxcore-log: 
09-30 07:27:06.580  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.580  5585  5631 I jxcore-log: 
,09-30 07:27:06.581  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.581  5585  5631 I jxcore-log: 
,09-30 07:27:06.581  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.581  5585  5631 I jxcore-log: 
09-30 07:27:06.582  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.582  5585  5631 I jxcore-log: 
,09-30 07:27:06.582  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.582  5585  5631 I jxcore-log: 
09-30 07:27:06.583  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.583  5585  5631 I jxcore-log: 
,09-30 07:27:06.583  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.583  5585  5631 I jxcore-log: 
09-30 07:27:06.584  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.584  5585  5631 I jxcore-log: 
09-30 07:27:06.584  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.584  5585  5631 I jxcore-log: 
,09-30 07:27:06.584  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.584  5585  5631 I jxcore-log: 
09-30 07:27:06.585  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.585  5585  5631 I jxcore-log: 
,09-30 07:27:06.586  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.586  5585  5631 I jxcore-log: 
09-30 07:27:06.586  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.586  5585  5631 I jxcore-log: 
,09-30 07:27:06.587  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.587  5585  5631 I jxcore-log: 
09-30 07:27:06.587  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.587  5585  5631 I jxcore-log: 
,09-30 07:27:06.588  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.588  5585  5631 I jxcore-log: 
09-30 07:27:06.588  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.588  5585  5631 I jxcore-log: 
,09-30 07:27:06.588  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.588  5585  5631 I jxcore-log: 
09-30 07:27:06.589  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.589  5585  5631 I jxcore-log: 
,09-30 07:27:06.589  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.589  5585  5631 I jxcore-log: 
09-30 07:27:06.590  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.590  5585  5631 I jxcore-log: 
09-30 07:27:06.590  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.590  5585  5631 I jxcore-log: 
09-30 07:27:06.591  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.591  5585  5631 I jxcore-log: 
,09-30 07:27:06.591  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.591  5585  5631 I jxcore-log: 
09-30 07:27:06.592  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.592  5585  5631 I jxcore-log: 
09-30 07:27:06.592  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.592  5585  5631 I jxcore-log: 
09-30 07:27:06.593  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.593  5585  5631 I jxcore-log: 
,09-30 07:27:06.593  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.593  5585  5631 I jxcore-log: 
09-30 07:27:06.594  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.594  5585  5631 I jxcore-log: 
09-30 07:27:06.594  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.594  5585  5631 I jxcore-log: 
09-30 07:27:06.594  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.594  5585  5631 I jxcore-log: 
09-30 07:27:06.595  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.595  5585  5631 I jxcore-log: 
09-30 07:27:06.595  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.595  5585  5631 I jxcore-log: 
09-30 07:27:06.596  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.596  5585  5631 I jxcore-log: 
09-30 07:27:06.596  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.596  5585  5631 I jxcore-log: 
09-30 07:27:06.597  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.597  5585  5631 I jxcore-log: 
09-30 07:27:06.597  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.597  5585  5631 I jxcore-log: 
09-30 07:27:06.597  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.597  5585  5631 I jxcore-log: 
09-30 07:27:06.598  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.598  5585  5631 I jxcore-log: 
09-30 07:27:06.598  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.598  5585  5631 I jxcore-log: 
09-30 07:27:06.599  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.599  5585  5631 I jxcore-log: 
09-30 07:27:06.600  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.600  5585  5631 I jxcore-log: 
09-30 07:27:06.603  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.603  5585  5631 I jxcore-log: 
09-30 07:27:06.603  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.603  5585  5631 I jxcore-log: 
09-30 07:27:06.604  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.604  5585  5631 I jxcore-log: 
09-30 07:27:06.604  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:06.604  5585  5631 I jxcore-log: 
09-30 07:27:06.605  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'mux close'
09-30 07:27:06.605  5585  5631 I jxcore-log: 
09-30 07:27:06.607  5585  5631 I jxcore-log: ok 28 native server is nulled out
09-30 07:27:06.607  5585  5631 I jxcore-log: 
09-30 07:27:06.607  5585  5631 I jxcore-log: ok 29 native server should be closed
09-30 07:27:06.607  5585  5631 I jxcore-log: 
09-30 07:27:06.607  5585  5631 I jxcore-log: ok 30 incoming has been removed
09-30 07:27:06.607  5585  5631 I jxcore-log: 
09-30 07:27:06.608  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.608  5585  5631 I jxcore-log: 
09-30 07:27:06.608  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.608  5585  5631 I jxcore-log: 
09-30 07:27:06.609  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.609  5585  5631 I jxcore-log: 
09-30 07:27:06.609  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.609  5585  5631 I jxcore-log: 
09-30 07:27:06.609  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.609  5585  5631 I jxcore-log: 
09-30 07:27:06.610  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.610  5585  5631 I jxcore-log: 
09-30 07:27:06.610  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.610  5585  5631 I jxcore-log: 
09-30 07:27:06.610  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.610  5585  5631 I jxcore-log: 
09-30 07:27:06.610  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.610  5585  5631 I jxcore-log: 
09-30 07:27:06.610  5585  5631 I jxcore-log: 2016-09-30 11:27:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:06.610  5585  5631 I jxcore-log: 
,09-30 07:27:06.682  5585  5631 I jxcore-log: # teardown
09-30 07:27:06.682  5585  5631 I jxcore-log: 
,09-30 07:27:06.779  5585  5631 I jxcore-log: # setup
09-30 07:27:06.779  5585  5631 I jxcore-log: 
,09-30 07:27:07.414   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:07.950   929  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=344183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 07:27:08.415   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:08.558  5585  5631 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-30 07:27:08.558  5585  5631 I jxcore-log: 
,09-30 07:27:09.372  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:09.372  5585  5631 I jxcore-log: 
,09-30 07:27:09.378  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'listening 37789'
09-30 07:27:09.378  5585  5631 I jxcore-log: 
,09-30 07:27:09.388  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:09.388  5585  5631 I jxcore-log: 
,09-30 07:27:09.391  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:09.391  5585  5631 I jxcore-log: 
,09-30 07:27:09.393  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'new mux'
09-30 07:27:09.393  5585  5631 I jxcore-log: 
,09-30 07:27:09.403  5585  5631 I jxcore-log: ok 31 we should not have gotten an error
09-30 07:27:09.403  5585  5631 I jxcore-log: 
,09-30 07:27:09.407  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:09.407  5585  5631 I jxcore-log: 
,09-30 07:27:09.410  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:09.410  5585  5631 I jxcore-log: 
,09-30 07:27:09.415   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:09.419  5585  5631 I jxcore-log: ok 32 Buffers are identical
09-30 07:27:09.419  5585  5631 I jxcore-log: 
,09-30 07:27:09.421  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:09.421  5585  5631 I jxcore-log: 
,09-30 07:27:09.423  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'mux close'
09-30 07:27:09.423  5585  5631 I jxcore-log: 
,09-30 07:27:09.437  5585  5631 I jxcore-log: 2016-09-30 11:27:09 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:09.437  5585  5631 I jxcore-log: 
,09-30 07:27:09.438  5585  5631 I jxcore-log: ok 33 server should be fine
09-30 07:27:09.438  5585  5631 I jxcore-log: 
09-30 07:27:09.438  5585  5631 I jxcore-log: ok 34 server should be open
09-30 07:27:09.438  5585  5631 I jxcore-log: 
09-30 07:27:09.438  5585  5631 I jxcore-log: ok 35 incoming has been removed
09-30 07:27:09.438  5585  5631 I jxcore-log: 
09-30 07:27:09.438  5585  5631 I jxcore-log: ok 36 The mux object should be closed
09-30 07:27:09.438  5585  5631 I jxcore-log: 
09-30 07:27:09.439  5585  5631 I jxcore-log: ok 37 The mux stream should be closed
09-30 07:27:09.439  5585  5631 I jxcore-log: 
,09-30 07:27:09.445  5585  5631 I jxcore-log: # teardown
09-30 07:27:09.445  5585  5631 I jxcore-log: 
,09-30 07:27:09.890  5585  5631 I jxcore-log: # setup
09-30 07:27:09.890  5585  5631 I jxcore-log: 
,09-30 07:27:10.145   929  2906 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 07:27:10.416   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:10.565  5585  5631 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-30 07:27:10.565  5585  5631 I jxcore-log: 
,09-30 07:27:11.009  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'creating native server'
09-30 07:27:11.009  5585  5631 I jxcore-log: 
,09-30 07:27:11.016  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'listening 43940'
09-30 07:27:11.016  5585  5631 I jxcore-log: 
,09-30 07:27:11.025  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'new incoming socket'
09-30 07:27:11.025  5585  5631 I jxcore-log: 
,09-30 07:27:11.028  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'creating incoming mux'
09-30 07:27:11.028  5585  5631 I jxcore-log: 
,09-30 07:27:11.031  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'new mux'
09-30 07:27:11.031  5585  5631 I jxcore-log: 
,09-30 07:27:11.039  5585  5631 I jxcore-log: ok 38 we should not have gotten an error
09-30 07:27:11.039  5585  5631 I jxcore-log: 
,09-30 07:27:11.043  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'new stream: '
09-30 07:27:11.043  5585  5631 I jxcore-log: 
,09-30 07:27:11.047  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'new outgoing socket'
09-30 07:27:11.047  5585  5631 I jxcore-log: 
,09-30 07:27:11.054  5585  5631 I jxcore-log: ok 39 Buffers are identical
09-30 07:27:11.054  5585  5631 I jxcore-log: 
,09-30 07:27:11.059  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'incoming socket timeout'
09-30 07:27:11.059  5585  5631 I jxcore-log: 
,09-30 07:27:11.061  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'stream close:'
09-30 07:27:11.061  5585  5631 I jxcore-log: 
,09-30 07:27:11.063  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'mux close'
09-30 07:27:11.063  5585  5631 I jxcore-log: 
,09-30 07:27:11.068  5585  5631 I jxcore-log: 2016-09-30 11:27:11 - DEBUG createNativeListener: 'incoming socket close'
09-30 07:27:11.068  5585  5631 I jxcore-log: 
,09-30 07:27:11.070  5585  5631 I jxcore-log: ok 40 server should be fine
09-30 07:27:11.070  5585  5631 I jxcore-log: 
,09-30 07:27:11.071  5585  5631 I jxcore-log: ok 41 server should be open
09-30 07:27:11.071  5585  5631 I jxcore-log: 
,09-30 07:27:11.071  5585  5631 I jxcore-log: ok 42 incoming has been removed
09-30 07:27:11.071  5585  5631 I jxcore-log: 
09-30 07:27:11.072  5585  5631 I jxcore-log: ok 43 The mux object should be closed
09-30 07:27:11.072  5585  5631 I jxcore-log: 
,09-30 07:27:11.072  5585  5631 I jxcore-log: ok 44 The mux stream should be closed
09-30 07:27:11.072  5585  5631 I jxcore-log: 
,09-30 07:27:11.078  5585  5631 I jxcore-log: # teardown
09-30 07:27:11.078  5585  5631 I jxcore-log: 
,09-30 07:27:11.417   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:11.837  5585  5631 I jxcore-log: # setup
09-30 07:27:11.837  5585  5631 I jxcore-log: 
,09-30 07:27:12.350  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-30 07:27:12.350  5585  5631 I jxcore-log: 
,09-30 07:27:12.418   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 07:27:13.109  5585  5631 I jxcore-log: 2016-09-30 11:27:13 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-30 07:27:13.109  5585  5631 I jxcore-log: 
,09-30 07:27:13.110  5585  5631 I jxcore-log: ok 45 Got right error
09-30 07:27:13.110  5585  5631 I jxcore-log: 
,09-30 07:27:13.116  5585  5631 I jxcore-log: # teardown
09-30 07:27:13.116  5585  5631 I jxcore-log: 
,09-30 07:27:13.675  5585  5631 I jxcore-log: # setup
09-30 07:27:13.675  5585  5631 I jxcore-log: 
,09-30 07:27:14.285  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-30 07:27:14.285  5585  5631 I jxcore-log: 
,09-30 07:27:14.850  5585  5631 I jxcore-log: 2016-09-30 11:27:14 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-30 07:27:14.850  5585  5631 I jxcore-log: 
,09-30 07:27:14.852  5585  5631 I jxcore-log: ok 46 Got socket hang up
09-30 07:27:14.852  5585  5631 I jxcore-log: 
,09-30 07:27:14.857  5585  5631 I jxcore-log: # teardown
09-30 07:27:14.857  5585  5631 I jxcore-log: 
,09-30 07:27:15.618  5585  5631 I jxcore-log: # setup
09-30 07:27:15.618  5585  5631 I jxcore-log: 
,09-30 07:27:16.237  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-30 07:27:16.237  5585  5631 I jxcore-log: 
,09-30 07:27:16.966  5585  5631 I jxcore-log: 2016-09-30 11:27:16 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-30 07:27:16.966  5585  5631 I jxcore-log: 
09-30 07:27:16.966  5585  5631 I jxcore-log: ok 47 Got 500 as expected
09-30 07:27:16.966  5585  5631 I jxcore-log: 
,09-30 07:27:16.970  5585  5631 I jxcore-log: # teardown
09-30 07:27:16.970  5585  5631 I jxcore-log: 
,09-30 07:27:17.419   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:17.479  5585  5631 I jxcore-log: # setup
09-30 07:27:17.479  5585  5631 I jxcore-log: 
,09-30 07:27:18.075  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-30 07:27:18.075  5585  5631 I jxcore-log: 
,09-30 07:27:18.421   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:19.422   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:20.038  5585  5631 I jxcore-log: ok 48 should be equal
09-30 07:27:20.038  5585  5631 I jxcore-log: 
09-30 07:27:20.039  5585  5631 I jxcore-log: ok 49 revs are equal
09-30 07:27:20.039  5585  5631 I jxcore-log: 
,09-30 07:27:20.044  5585  5631 I jxcore-log: # teardown
09-30 07:27:20.044  5585  5631 I jxcore-log: 
,09-30 07:27:20.355  5585  5631 I jxcore-log: # setup
09-30 07:27:20.355  5585  5631 I jxcore-log: 
,09-30 07:27:20.424   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:20.745  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-30 07:27:20.745  5585  5631 I jxcore-log: 
,09-30 07:27:21.425   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:21.958  5585  5631 I jxcore-log: ok 50 should be equal
09-30 07:27:21.958  5585  5631 I jxcore-log: 
,09-30 07:27:21.958  5585  5631 I jxcore-log: ok 51 revs are equal
09-30 07:27:21.958  5585  5631 I jxcore-log: 
,09-30 07:27:21.964  5585  5631 I jxcore-log: # teardown
09-30 07:27:21.964  5585  5631 I jxcore-log: 
,09-30 07:27:22.426   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 07:27:22.620  5585  5631 I jxcore-log: # setup
09-30 07:27:22.620  5585  5631 I jxcore-log: 
,09-30 07:27:22.992  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-30 07:27:22.992  5585  5631 I jxcore-log: 
,09-30 07:27:23.525  5585  5631 I jxcore-log: ok 52 should be equal
09-30 07:27:23.525  5585  5631 I jxcore-log: 
,09-30 07:27:23.525  5585  5631 I jxcore-log: ok 53 revs are equal
09-30 07:27:23.525  5585  5631 I jxcore-log: 
,09-30 07:27:23.654  5585  5631 I jxcore-log: ok 54 should be equal
09-30 07:27:23.654  5585  5631 I jxcore-log: 
,09-30 07:27:23.654  5585  5631 I jxcore-log: ok 55 revs are equal
09-30 07:27:23.654  5585  5631 I jxcore-log: 
,09-30 07:27:23.787  5585  5631 I jxcore-log: ok 56 should be equal
09-30 07:27:23.787  5585  5631 I jxcore-log: 
,09-30 07:27:23.787  5585  5631 I jxcore-log: ok 57 revs are equal
09-30 07:27:23.787  5585  5631 I jxcore-log: 
,09-30 07:27:23.792  5585  5631 I jxcore-log: # teardown
09-30 07:27:23.792  5585  5631 I jxcore-log: 
,09-30 07:27:23.834  5585  5631 I jxcore-log: # setup
09-30 07:27:23.834  5585  5631 I jxcore-log: 
,09-30 07:27:23.904  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-30 07:27:23.904  5585  5631 I jxcore-log: 
,09-30 07:27:24.490  5585  5631 I jxcore-log: 2016-09-30 11:27:24 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-30 07:27:24.490  5585  5631 I jxcore-log: 
,09-30 07:27:24.490  5585  5631 I jxcore-log: ok 58 Our rev is old so we should fail
09-30 07:27:24.490  5585  5631 I jxcore-log: 
,09-30 07:27:24.494  5585  5631 I jxcore-log: # teardown
09-30 07:27:24.494  5585  5631 I jxcore-log: 
,09-30 07:27:24.641  5585  5631 I jxcore-log: # setup
09-30 07:27:24.641  5585  5631 I jxcore-log: 
,09-30 07:27:24.662  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-30 07:27:24.662  5585  5631 I jxcore-log: 
,09-30 07:27:24.752  5585  5631 I jxcore-log: ok 59 confirm stop caused failure
09-30 07:27:24.752  5585  5631 I jxcore-log: 
,09-30 07:27:24.764  5585  5631 I jxcore-log: # teardown
09-30 07:27:24.764  5585  5631 I jxcore-log: 
,09-30 07:27:24.803  5585  5631 I jxcore-log: # setup
09-30 07:27:24.803  5585  5631 I jxcore-log: 
,09-30 07:27:24.853  5585  5631 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-30 07:27:24.853  5585  5631 I jxcore-log: 
,09-30 07:27:25.170  5585  5631 I jxcore-log: 2016-09-30 11:27:25 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-30 07:27:25.170  5585  5631 I jxcore-log: 
,09-30 07:27:25.171  5585  5631 I jxcore-log: ok 60 stop caused us to fail
09-30 07:27:25.171  5585  5631 I jxcore-log: 
09-30 07:27:25.171  5585  5631 I jxcore-log: ok 61 We specifically failed on a stop before put
09-30 07:27:25.171  5585  5631 I jxcore-log: 
,09-30 07:27:25.177  5585  5631 I jxcore-log: # teardown
09-30 07:27:25.177  5585  5631 I jxcore-log: 
,09-30 07:27:25.274  5585  5631 I jxcore-log: # setup
09-30 07:27:25.274  5585  5631 I jxcore-log: 
,09-30 07:27:25.336  5585  5631 I jxcore-log: # #update - fail if stop is called
09-30 07:27:25.336  5585  5631 I jxcore-log: 
,09-30 07:27:25.417  5585  5631 I jxcore-log: ok 62 failed due to stop
09-30 07:27:25.417  5585  5631 I jxcore-log: 
,09-30 07:27:25.418  5585  5631 I jxcore-log: ok 63 failed due to stop
09-30 07:27:25.418  5585  5631 I jxcore-log: 
,09-30 07:27:25.427  5585  5631 I jxcore-log: # teardown
09-30 07:27:25.427  5585  5631 I jxcore-log: 
,09-30 07:27:25.490  5585  5631 I jxcore-log: # setup
09-30 07:27:25.490  5585  5631 I jxcore-log: 
,09-30 07:27:25.532  5585  5631 I jxcore-log: # #update - set seq for first time
09-30 07:27:25.532  5585  5631 I jxcore-log: 
,09-30 07:27:26.007  5585  5631 I jxcore-log: ok 64 should be equal
09-30 07:27:26.007  5585  5631 I jxcore-log: 
,09-30 07:27:26.013  5585  5631 I jxcore-log: # teardown
09-30 07:27:26.013  5585  5631 I jxcore-log: 
,09-30 07:27:26.118  5585  5631 I jxcore-log: # setup
09-30 07:27:26.118  5585  5631 I jxcore-log: 
,09-30 07:27:26.142  5585  5631 I jxcore-log: # #update - Fail on bad seq value
09-30 07:27:26.142  5585  5631 I jxcore-log: 
,09-30 07:27:26.553  5585  5631 I jxcore-log: 2016-09-30 11:27:26 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-30 07:27:26.553  5585  5631 I jxcore-log: 
,09-30 07:27:26.555  5585  5631 I jxcore-log: ok 65 Expected bad seq error
09-30 07:27:26.555  5585  5631 I jxcore-log: 
09-30 07:27:26.559  5585  5631 I jxcore-log: # teardown
09-30 07:27:26.559  5585  5631 I jxcore-log: 
,09-30 07:27:26.601  5585  5631 I jxcore-log: # setup
09-30 07:27:26.601  5585  5631 I jxcore-log: 
,09-30 07:27:26.775  5585  5631 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-30 07:27:26.775  5585  5631 I jxcore-log: 
,09-30 07:27:28.300  5585  5631 I jxcore-log: ok 66 Different promises
09-30 07:27:28.300  5585  5631 I jxcore-log: 
,09-30 07:27:28.303  5585  5631 I jxcore-log: ok 67 Timer was cancelled
09-30 07:27:28.303  5585  5631 I jxcore-log: 
,09-30 07:27:28.448  5585  5631 I jxcore-log: ok 68 should be equal
09-30 07:27:28.448  5585  5631 I jxcore-log: 
,09-30 07:27:28.455  5585  5631 I jxcore-log: # teardown
09-30 07:27:28.455  5585  5631 I jxcore-log: 
,09-30 07:27:28.508  5585  5631 I jxcore-log: # setup
09-30 07:27:28.508  5585  5631 I jxcore-log: 
,09-30 07:27:29.553  5585  5631 I jxcore-log: # #update - do we wait for blocked update
09-30 07:27:29.553  5585  5631 I jxcore-log: 
,09-30 07:27:29.650  5585  5631 I jxcore-log: ok 69 One go and one blocked
09-30 07:27:29.650  5585  5631 I jxcore-log: 
,09-30 07:27:29.651  5585  5631 I jxcore-log: ok 70 All blocked
09-30 07:27:29.651  5585  5631 I jxcore-log: 
09-30 07:27:29.652  5585  5631 I jxcore-log: ok 71 Still blocked
09-30 07:27:29.652  5585  5631 I jxcore-log: 
,09-30 07:27:30.056  5585  5631 I jxcore-log: ok 72 should be equal
09-30 07:27:30.056  5585  5631 I jxcore-log: 
,09-30 07:27:30.064  5585  5631 I jxcore-log: # teardown
09-30 07:27:30.064  5585  5631 I jxcore-log: 
,09-30 07:27:30.125  5585  5631 I jxcore-log: # setup
09-30 07:27:30.125  5585  5631 I jxcore-log: 
,09-30 07:27:30.147   929  2906 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 07:27:30.373  5585  5631 I jxcore-log: # #update - test that we wait long enough
09-30 07:27:30.373  5585  5631 I jxcore-log: 
,09-30 07:27:31.897  5585  5631 I jxcore-log: ok 73 We waited long enough
09-30 07:27:31.897  5585  5631 I jxcore-log: 
,09-30 07:27:31.999  5585  5631 I jxcore-log: ok 74 should be equal
09-30 07:27:31.999  5585  5631 I jxcore-log: 
,09-30 07:27:32.006  5585  5631 I jxcore-log: # teardown
09-30 07:27:32.006  5585  5631 I jxcore-log: 
,09-30 07:27:32.427   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:33.429   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:34.430   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:35.431   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:36.433   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:37.434   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 07:27:51.765   929  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=387998, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 07:27:52.435   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:53.437   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:54.439   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:55.440   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:56.441   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:27:57.441   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 07:27:58.030   929  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=394263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 07:28:10.152   929  2906 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 07:28:12.830   929  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 07:28:17.443   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:28:18.444   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:28:19.446   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:28:20.447   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:28:21.448   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 07:28:21.773   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 07:28:22.449   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 07:28:23.044   929  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=419277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 07:28:24.803   929  2914 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 07:28:30.155   929  2906 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 07:28:32.028  5585  5631 I jxcore-log: 2016-09-30 11:28:32 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
09-30 07:28:32.028  5585  5631 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-30 07:28:32.028  5585  5631 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-30 07:28:32.028  5585  5631 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-30 07:28:32.028  5585  5631 I jxcore-log:     at $9@timers.js:120:1
09-30 07:28:32.028  5585  5631 I jxcore-log: ''
09-30 07:28:32.028  5585  5631 I jxcore-log: 
09-30 07:28:32.030  5585  5631 I jxcore-log: 2016-09-30 11:28:32 - DEBUG CoordinatedClient: 'test client failed'
09-30 07:28:32.030  5585  5631 I jxcore-log: 
,09-30 07:28:32.040  5585  5631 I jxcore-log: 2016-09-30 11:28:32 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-30 07:28:32.040  5585  5631 I jxcore-log: 
,09-30 07:28:32.045  5585  5631 I jxcore-log: 2016-09-30 11:28:32 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
09-30 07:28:32.045  5585  5631 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-30 07:28:32.045  5585  5631 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-30 07:28:32.045  5585  5631 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-30 07:28:32.045  5585  5631 I jxcore-log:     at $9@timers.js:120:1
09-30 07:28:32.045  5585  5631 I jxcore-log: ''
09-30 07:28:32.045  5585  5631 I jxcore-log: 
,09-30 07:28:32.047  5585  5631 I jxcore-log: 2016-09-30 11:28:32 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-30 07:28:32.047  5585  5631 I jxcore-log: 
,09-30 07:28:32.691  5978  5978 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-30 07:28:32.715  5978  5978 D AndroidRuntime: CheckJNI is OFF
,09-30 07:28:32.743  5978  5978 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-30 07:28:32.776  5978  5978 I Radio-JNI: register_android_hardware_Radio DONE
,09-30 07:28:32.792  5978  5978 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-30 07:28:32.802   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-30 07:28:32.803   929   942 I ActivityManager: Killing 5585:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-30 07:28:32.911   929  3821 I WindowState: WIN DEATH: Window{5f48367 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-30 07:28:32.911   929  3772 D GraphicsStats: Buffer count: 2,
,09-30 07:28:32.912   929  2908 D WifiService: Client connection lost with reason: 4
,09-30 07:28:32.957   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-30 07:28:32.959   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-30 07:28:32.959   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-30 07:28:32.959   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-30 07:28:32.959   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:28:32.959   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:32.959   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 07:28:32.959   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 07:28:32.960   929   942 I ActivityManager:   Force finishing activity ActivityRecord{7ce0808 u0 com.test.thalitest/.MainActivity t2}
09-30 07:28:32.961   929   952 I art     : Starting a blocking GC Explicit
,09-30 07:28:32.974   929   939 W ActivityManager: Spurious death for ProcessRecord{b5dca0 0:com.test.thalitest/u0a77}, curProc for 5585: null
,09-30 07:28:32.978   929   947 W WindowManager: Attempted to add application window with unknown token Token{75c0ba1 ActivityRecord{7ce0808 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-30 07:28:32.978   929   947 W WindowManager: Token{75c0ba1 ActivityRecord{7ce0808 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{75c0ba1 ActivityRecord{7ce0808 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-30 07:28:32.978   929   947 W WindowManager: view not successfully added to wm, removing view
09-30 07:28:32.979   929   947 W WindowManager: Exception when adding starting window
09-30 07:28:32.979   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{5e2921b V.E...... R.....ID 0,0-0,0} not attached to window manager
09-30 07:28:32.979   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-30 07:28:32.979   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-30 07:28:32.979   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-30 07:28:32.979   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-30 07:28:32.979   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-30 07:28:32.979   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:28:32.979   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:32.979   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 07:28:32.979   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 07:28:33.054   929   952 I art     : Explicit concurrent mark sweep GC freed 87259(6MB) AllocSpace objects, 48(1840KB) LOS objects, 33% free, 29MB/43MB, paused 1.699ms total 92.087ms
,09-30 07:28:33.072   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-30 07:28:33.074  5978  5978 I art     : System.exit called, status: 0
,09-30 07:28:33.074  5978  5978 I AndroidRuntime: VM exiting with result code 0.
,09-30 07:28:33.089   929   952 I ActivityManager: Start proc 5988:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-30 07:28:33.089   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-30 07:28:33.095   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-30 07:28:33.099  5866  5866 D BluetoothMapAppObserver: onReceive
,09-30 07:28:33.100  5866  5866 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-30 07:28:33.102   929  2897 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-30 07:28:33.106  4039  4119 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-30 07:28:33.107  3613  3613 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-30 07:28:33.135  3613  6001 I Keyboard.Facilitator.DecoderInitializer: run()
,09-30 07:28:33.147  3613  6001 I Decoder : createOrResetDecoder
,09-30 07:28:33.165  3723  3723 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-30 07:28:33.169   315   315 W kworker/1:2: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 07:28:33.181   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-30 07:28:33.179   315   315 W kworker/1:2: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 07:28:33.185   315   315 W kworker/1:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 07:28:33.192  3761  3876 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-30 07:28:33.193   929   941 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-30 07:28:33.193  3357  6003 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-30 07:28:33.194   929   941 E PackageManager: Failed to write settings, restoring backup
09-30 07:28:33.194   929   941 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-30 07:28:33.194   929   941 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-30 07:28:33.194   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-30 07:28:33.194   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-30 07:28:33.194   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-30 07:28:33.194   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:28:33.194   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:33.194   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 07:28:33.197   929   942 E DropBoxManagerService: Can't write: system_server_wtf
09-30 07:28:33.197   929   942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 07:28:33.197   929   942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 07:28:33.197   929   942 E DropBoxManagerService: 	... 13 more
,09-30 07:28:33.201  3537  3537 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-30 07:28:33.202  3537  3537 D AndroidRuntime: Shutting down VM
09-30 07:28:33.202  3357  3381 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj44640890C) - 
--------- beginning of crash
09-30 07:28:33.203  3537  3537 E AndroidRuntime: FATAL EXCEPTION: main
09-30 07:28:33.203  3537  3537 E AndroidRuntime: Process: com.google.process.gapps, PID: 3537
09-30 07:28:33.203  3537  3537 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-30 07:28:33.203  3537  3537 E AndroidRuntime: 	... 8 more
,09-30 07:28:33.214   929   940 I ActivityManager: Start proc 6007:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-30 07:28:33.215  3761  3876 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-30 07:28:33.215  3761  3876 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3761
09-30 07:28:33.215  3761  3876 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:33.215  3761  3876 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 07:28:33.221   929  3551 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 07:28:33.225   929  6017 E DropBoxManagerService: Can't write: system_app_crash
09-30 07:28:33.225   929  6017 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 07:28:33.225   929  6017 E DropBoxManagerService: 	... 5 more
,09-30 07:28:33.230  3537  3537 I Process : Sending signal. PID: 3537 SIG: 9
09-30 07:28:33.229  3761  3876 I Process : Sending signal. PID: 3761 SIG: 9
,09-30 07:28:33.229   929  6020 E DropBoxManagerService: Can't write: system_app_crash
09-30 07:28:33.229   929  6020 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 07:28:33.229   929  6020 E DropBoxManagerService: 	... 5 more
,09-30 07:28:33.249   929  2908 D WifiService: Client connection lost with reason: 4
,09-30 07:28:33.265  3357  6003 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-30 07:28:33.265  3357  6003 I Process : Sending signal. PID: 3357 SIG: 9
,09-30 07:28:33.276   929  3115 I ActivityManager: Process com.google.process.gapps (pid 3537) has died
,09-30 07:28:33.276   929  3115 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-30 07:28:33.277   929  3115 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-30 07:28:33.277   929  3115 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-30 07:28:33.277   929  3115 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 30999ms
,09-30 07:28:33.300   929   940 I ActivityManager: Start proc 6023:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-30 07:28:33.339   929  2896 W InputDispatcher: channel '7bab198 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-30 07:28:33.339   929  2896 E InputDispatcher: channel '7bab198 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-30 07:28:33.340   929  3760 D GraphicsStats: Buffer count: 1
,09-30 07:28:33.340   929  3160 I WindowState: WIN DEATH: Window{7bab198 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-30 07:28:33.340   929  3160 W InputDispatcher: Attempted to unregister already unregistered input channel '7bab198 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-30 07:28:33.355   929  3772 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3761) has died
09-30 07:28:33.356   929  3772 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-30 07:28:33.357   929  3772 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 07:28:33.382   929   942 I ActivityManager: Start proc 6037:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 07:28:33.382   929   940 I ActivityManager: Process android.process.acore (pid 3357) has died
09-30 07:28:33.382   929   940 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-30 07:28:33.426  6037  6037 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:28:33.426  6037  6037 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 07:28:33.427  6037  6037 D AndroidRuntime: Shutting down VM
,09-30 07:28:33.432  6037  6037 E AndroidRuntime: FATAL EXCEPTION: main
09-30 07:28:33.432  6037  6037 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6037
09-30 07:28:33.432  6037  6037 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 07:28:33.432  6037  6037 E AndroidRuntime: 	... 10 more
09-30 07:28:33.435   929  3115 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-30 07:28:33.435   929  6050 E DropBoxManagerService: Can't write: system_app_crash
09-30 07:28:33.435   929  6050 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 07:28:33.435   929  6050 E DropBoxManagerService: 	... 5 more
09-30 07:28:33.436  6037  6037 I Process : Sending signal. PID: 6037 SIG: 9
,09-30 07:28:33.471   929   940 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6037) has died
,09-30 07:28:33.473   929   940 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 07:28:33.489   929   942 I ActivityManager: Start proc 6051:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 07:28:33.542  6051  6051 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:28:33.542  6051  6051 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 07:28:33.542  6051  6051 D AndroidRuntime: Shutting down VM
,09-30 07:28:33.550  6051  6051 E AndroidRuntime: FATAL EXCEPTION: main
09-30 07:28:33.550  6051  6051 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6051
09-30 07:28:33.550  6051  6051 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 07:28:33.550  6051  6051 E AndroidRuntime: 	... 10 more
09-30 07:28:33.553   929  3772 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-30 07:28:33.554   929  6063 E DropBoxManagerService: Can't write: system_app_crash
09-30 07:28:33.554   929  6063 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 07:28:33.554   929  6063 E DropBoxManagerService: 	... 5 more
09-30 07:28:33.555  6051  6051 I Process : Sending signal. PID: 6051 SIG: 9
,09-30 07:28:33.574   385   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
