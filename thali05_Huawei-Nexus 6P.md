#### Test 8689130568a1443_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-27 06:54:38.839   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-27 06:54:40.159  5624  5624 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-27 06:54:40.165  5624  5624 D AndroidRuntime: CheckJNI is OFF
09-27 06:54:40.194  5624  5624 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-27 06:54:40.229  5624  5624 I Radio-JNI: register_android_hardware_Radio DONE
09-27 06:54:40.245  5624  5624 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-27 06:54:40.251   933  3637 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-27 06:54:40.296   933  3637 I ActivityManager: Start proc 5633:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-27 06:54:40.311  5624  5624 D AndroidRuntime: Shutting down VM
,09-27 06:54:40.646   933  3877 I WindowManager: Screenshot max retries 4 of Token{a0dc783 ActivityRecord{1b79e32 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{7c0c18a u0 Starting com.test.thalitest} drawState=4
,09-27 06:54:40.711  5633  5633 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-27 06:54:40.746  5633  5633 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-27 06:54:40.768  5633  5633 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 6061-6079)
,09-27 06:54:40.768  5633  5633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-27 06:54:40.788  5633  5633 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {332a216}
,09-27 06:54:40.788  5633  5633 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-27 06:54:40.789  5633  5633 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-27 06:54:40.794  5633  5633 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-27 06:54:40.795  5633  5633 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-27 06:54:40.831  5633  5633 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-27 06:54:40.848  5633  5633 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-27 06:54:40.848  5633  5633 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-27 06:54:40.848  5633  5633 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-27 06:54:40.848  5633  5633 I Adreno  : Build Date                       : 12/06/15
09-27 06:54:40.848  5633  5633 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-27 06:54:40.848  5633  5633 I Adreno  : Local Branch                     : mybranch17112971
09-27 06:54:40.848  5633  5633 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-27 06:54:40.848  5633  5633 I Adreno  : Remote Branch                    : NONE
09-27 06:54:40.848  5633  5633 I Adreno  : Reconstruct Branch               : NOTHING
,09-27 06:54:40.894   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d262a9:true
,09-27 06:54:40.923   405   405 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33818]" dev="sockfs" ino=33818 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 06:54:40.923   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33818]" dev="sockfs" ino=33818 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 06:54:40.938  5633  5633 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-27 06:54:40.947  5633  5633 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-27 06:54:40.966   403   403 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[29643]" dev="sockfs" ino=29643 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 06:54:40.966   403   403 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[29643]" dev="sockfs" ino=29643 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-27 06:54:40.972  5633  5670 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-27 06:54:40.970  3183  3183 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15247]" dev="sockfs" ino=15247 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 06:54:40.970  3183  3183 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15247]" dev="sockfs" ino=15247 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 06:54:40.978  5633  5657 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-27 06:54:41.010  5633  5670 I OpenGLRenderer: Initialized EGL, version 1.4
,09-27 06:54:41.088   933   951 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +437ms (total +823ms)
,09-27 06:54:41.117  5633  5633 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5633
,09-27 06:54:41.247  5633  5633 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-27 06:54:41.336  5633  5673 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -579860176
,09-27 06:54:41.340  5633  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-27 06:54:41.340  5633  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-27 06:54:41.340  5633  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-27 06:54:41.340  5633  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-27 06:54:41.340  5633  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-27 06:54:41.340  5633  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3da864f added. We now have 1 listener(s)
,09-27 06:54:41.343  5633  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-27 06:54:41.343  5633  5673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 06:54:41.344  5633  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 06:54:41.344  5633  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-27 06:54:41.346  5633  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@863386b added. We now have 1 listener(s)
09-27 06:54:41.346  5633  5673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 06:54:41.351   933  3001 D WifiService: New client listening to asynchronous messages
,09-27 06:54:41.352  5633  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 06:54:41.352  5633  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-27 06:54:41.352  5633  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-27 06:54:41.352  5633  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-27 06:54:41.352  5633  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-27 06:54:41.354  5633  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 06:54:41.354  5633  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-27 06:54:41.358  5633  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-27 06:54:41.358  5633  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 06:54:41.358  5633  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:54:41.358  5633  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:54:41.358  5633  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:54:41.358  5633  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:54:41.358  5633  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 06:54:41.358  5633  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 06:54:41.358  5633  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 06:54:41.358  5633  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-27 06:54:41.358  5633  5673 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 06:54:41.359  5633  5673 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-27 06:54:41.362  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:54:41.364  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:54:41.443  5633  5633 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-27 06:54:41.657  5633  5679 W jxcore-log: Initializing JXcore engine
09-27 06:54:41.657  5633  5679 W jxcore-log: JXcore engine is ready
,09-27 06:54:41.682  5633  5642 I art     : Background sticky concurrent mark sweep GC freed 85462(8MB) AllocSpace objects, 19(2MB) LOS objects, 25% free, 24MB/32MB, paused 3.034ms total 105.159ms
,09-27 06:54:41.680  5679  5679 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12553 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-27 06:54:41.680  5679  5679 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13349]" dev="sockfs" ino=13349 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-27 06:54:41.680  5679  5679 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-27 06:54:41.680  5679  5679 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[29618]" dev="sockfs" ino=29618 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-27 06:54:41.689  5633  5679 W jxcore-log: Starting JXcore engine
,09-27 06:54:41.745  5633  5679 W jxcore-log: Platform android
09-27 06:54:41.745  5633  5679 W jxcore-log: 
,09-27 06:54:41.745  5633  5679 W jxcore-log: Process ARCH arm
09-27 06:54:41.745  5633  5679 W jxcore-log: 
,09-27 06:54:41.849  5633  5679 I jxcore-log: JXcore Cordova bridge is ready!
09-27 06:54:41.849  5633  5679 I jxcore-log: 
,09-27 06:54:41.849  5633  5679 W jxcore-log: JXcore engine is started
,09-27 06:54:41.861  5633  5673 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-27 06:54:41.867  5633  5633 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-27 06:54:41.892   933  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 06:54:43.993   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 06:54:47.012   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 06:54:48.828  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-27 06:54:48.828  5633  5679 I jxcore-log: 
,09-27 06:54:48.829  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-27 06:54:48.829  5633  5679 I jxcore-log: 
,09-27 06:54:48.833  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 06:54:48.833  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:54:48.833  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:54:48.833  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:54:48.833  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:54:48.833  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 06:54:48.833  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 06:54:48.833  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 06:54:48.835  5633  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 06:54:48.836  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-27 06:54:48.836  5633  5679 I jxcore-log: 
09-27 06:54:48.837  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-27 06:54:48.837  5633  5679 I jxcore-log: 
,09-27 06:54:49.076  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 06:54:49.076  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1b0dd7 added. We now have 2 listener(s)
09-27 06:54:49.077  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 06:54:49.077  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 06:54:49.077  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 06:54:49.077  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 06:54:49.077  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40696c4 added. We now have 2 listener(s)
09-27 06:54:49.077  5633  5679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 06:54:49.078  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 06:54:49.080  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 06:54:49.083  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 06:54:49.083  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:54:49.083  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:54:49.083  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:54:49.083  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:54:49.083  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 06:54:49.083  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 06:54:49.083  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 06:54:49.084  5633  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 06:54:49.084  5633  5679 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 06:54:49.084  5633  5679 D ExecuteNativeTests: Running unit tests
,09-27 06:54:49.085  5633  5679 D BluetoothAdapter: enable(): BT is already enabled..!
,09-27 06:54:49.085   933  3902 D WifiService: setWifiEnabled: true pid=5633, uid=10077
09-27 06:54:49.085   933  3902 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:54:49.091  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:54:49.096  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:54:59.092  5633  5679 I com.test.thalitest.ThaliTestRunner: Running UT
,09-27 06:54:59.144   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 06:54:59.154  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 06:54:59.154  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0e5ab6 added. We now have 3 listener(s)
09-27 06:54:59.155  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 06:54:59.155  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 06:54:59.155  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 06:54:59.155  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 06:54:59.156  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38443b7 added. We now have 3 listener(s)
09-27 06:54:59.156  5633  5679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 06:54:59.156  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 06:54:59.159  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 06:54:59.163  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 06:54:59.163  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:54:59.163  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:54:59.163  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:54:59.163  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:54:59.163  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 06:54:59.163  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 06:54:59.163  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 06:54:59.164  5633  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 06:54:59.164  5633  5679 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 06:54:59.173  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:54:59.174  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-27 06:54:59.174  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 06:54:59.174  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 06:54:59.174  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 06:54:59.174  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 06:54:59.175  5633  5679 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-27 06:54:59.176  5633  5679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 06:54:59.176  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 06:54:59.176  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 06:54:59.176  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-27 06:54:59.176  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 06:54:59.176  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-27 06:54:59.178  5633  5679 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-27 06:54:59.179  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-27 06:54:59.181  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
09-27 06:54:59.181  5633  5679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-27 06:54:59.181  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:54:59.182  5633  5679 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 06:54:59.183  5633  5679 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-27 06:54:59.183  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-27 06:54:59.183  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 06:54:59.183  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 06:54:59.183  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 06:54:59.183  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:54:59.184  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 06:54:59.184  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 06:54:59.184  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 06:54:59.185  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 06:54:59.185  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 06:54:59.185  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 06:54:59.185  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 06:54:59.185  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 06:54:59.187  5633  5679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 06:54:59.187  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 06:54:59.187  5633  5682 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:54:59.186  4847  4847 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33055]" dev="sockfs" ino=33055 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 06:54:59.186  4847  4847 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33055]" dev="sockfs" ino=33055 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:54:59.191  5633  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 06:54:59.191  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 06:54:59.192  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 06:54:59.192  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 06:54:59.195  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 06:54:59.197  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 06:54:59.197  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-27 06:54:59.197  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:54:59.197  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:54:59.197  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-27 06:54:59.198  5633  5679 D BluetoothAdapter: STATE_ON
,09-27 06:54:59.201  4638  4657 D BtGatt.GattService: registerClient() - UUID=b877a092-1058-421c-849a-8d29e620d935
,09-27 06:54:59.202  4638  4710 D BtGatt.GattService: onClientRegistered() - UUID=b877a092-1058-421c-849a-8d29e620d935, clientIf=5
,09-27 06:54:59.203  5633  5643 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 06:54:59.205  4638  4715 D BtGatt.AdvertiseManager: message : 0
,09-27 06:54:59.211  4638  4715 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 06:54:59.228  4638  4710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 06:54:59.236  4638  4710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 06:54:59.238  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 06:54:59.239  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 06:54:59.239  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 06:54:59.240  5633  5679 I io.jxcore.node.ConnectionHelper: start: OK
09-27 06:54:59.240  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-27 06:54:59.241  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 06:54:59.241  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-27 06:54:59.241  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 06:54:59.242  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 06:54:59.242  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 06:54:59.245  5633  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 06:54:59.246  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 06:54:59.746  5633  5679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 06:54:59.746  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-27 06:54:59.746  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 06:54:59.746  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 06:54:59.746  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-27 06:54:59.746  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 06:54:59.746  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 06:54:59.747  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 06:54:59.747  5633  5633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 06:54:59.748  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 06:54:59.748  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 06:54:59.748  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-27 06:54:59.748  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 06:54:59.748  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 06:54:59.748  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 06:54:59.748  5633  5633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 06:54:59.748  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 06:54:59.748  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 06:54:59.748  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 06:54:59.749  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 06:54:59.749  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-27 06:54:59.749  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 06:54:59.749  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 06:54:59.749  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 06:54:59.749  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-27 06:54:59.749  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 06:54:59.749  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-27 06:54:59.750  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 06:54:59.750  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 06:54:59.750  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 06:54:59.750  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 06:54:59.750  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 06:54:59.750  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 06:54:59.750  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 06:54:59.751  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 06:54:59.751  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 06:54:59.751  5633  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 06:54:59.751  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-27 06:54:59.751  5633  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 06:54:59.751  5633  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 06:54:59.751  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 06:54:59.751  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 06:54:59.753  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:54:59.753  5633  5679 D BluetoothLeScanner: could not find callback wrapper
09-27 06:54:59.753  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 06:54:59.753  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 06:54:59.754  4638  4715 D BtGatt.AdvertiseManager: message : 1
09-27 06:54:59.757  4638  4715 D BtGatt.AdvertiseManager: stop advertise for client 5
09-27 06:54:59.772  4638  4710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-27 06:54:59.772  4638  4710 D BtGatt.GattService: Client app is not null!
,09-27 06:54:59.774  4638  4657 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 06:54:59.776  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 06:54:59.776  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-27 06:54:59.776  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 06:54:59.776  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 06:54:59.776  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 06:54:59.778  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:54:59.778  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 06:54:59.779  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 06:54:59.780  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 06:54:59.783  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 06:54:59.783  5633  5633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 06:54:59.784  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 06:54:59.784  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:54:59.784  5633  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 06:54:59.784  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:54:59.785  5633  5679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 06:54:59.785  5633  5679 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 06:54:59.785  5633  5679 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-27 06:54:59.785  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-27 06:54:59.786  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 06:54:59.786  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 06:54:59.786  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 06:54:59.786  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:54:59.787  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 06:54:59.790  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-27 06:54:59.790  4660  4660 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33060]" dev="sockfs" ino=33060 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:54:59.790  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 06:54:59.790  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 06:54:59.790  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 06:54:59.790  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 06:54:59.790  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:54:59.790  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 06:54:59.791  5633  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:54:59.794  5633  5679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 06:54:59.795  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 06:54:59.795  5633  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 06:54:59.790  4660  4660 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33060]" dev="sockfs" ino=33060 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 06:54:59.801  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 06:54:59.803  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 06:54:59.803  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 06:54:59.806  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 06:54:59.806  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 06:54:59.806  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
,09-27 06:54:59.806  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:54:59.806  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:54:59.807  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 06:54:59.808  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:54:59.811  4638  4847 D BtGatt.GattService: registerClient() - UUID=5856f30e-eaba-4fc3-96f1-eb8e89c9e0dc
09-27 06:54:59.811  4638  4710 D BtGatt.GattService: onClientRegistered() - UUID=5856f30e-eaba-4fc3-96f1-eb8e89c9e0dc, clientIf=5
,09-27 06:54:59.812  5633  5643 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 06:54:59.813  4638  4715 D BtGatt.AdvertiseManager: message : 0
,09-27 06:54:59.817  4638  4715 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 06:54:59.831  4638  4710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 06:54:59.839  4638  4710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 06:54:59.840  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 06:54:59.840  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 06:54:59.841  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 06:54:59.843  5633  5679 I io.jxcore.node.ConnectionHelper: start: OK
09-27 06:54:59.843  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 06:54:59.844  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 06:54:59.844  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 06:54:59.844  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 06:54:59.844  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 06:54:59.844  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-27 06:54:59.848  5633  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 06:54:59.848  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 06:55:00.348  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,09-27 06:55:00.349  5633  5679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 06:55:00.349  5633  5633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-27 06:55:00.350  5633  5679 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-27 06:55:00.350  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 06:55:00.350  5633  5633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 06:55:00.350  5633  5679 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-27 06:55:00.351  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-27 06:55:00.355  4638  4715 D BtGatt.AdvertiseManager: message : 1
,09-27 06:55:00.356  4638  4715 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 06:55:00.374  4638  4710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 06:55:00.374  4638  4710 D BtGatt.GattService: Client app is not null!
09-27 06:55:00.375  4638  4660 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 06:55:00.376  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 06:55:00.376  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 06:55:00.376  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 06:55:00.376  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 06:55:00.376  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 06:55:00.376  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-27 06:55:00.376  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:55:00.377  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:55:00.377  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 06:55:00.378  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:55:00.381  4638  4660 D BtGatt.GattService: registerClient() - UUID=b108920f-76b2-40b2-ab2a-dd0bce807797
09-27 06:55:00.382  4638  4710 D BtGatt.GattService: onClientRegistered() - UUID=b108920f-76b2-40b2-ab2a-dd0bce807797, clientIf=5
09-27 06:55:00.382  5633  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 06:55:00.383  4638  4715 D BtGatt.AdvertiseManager: message : 0
,09-27 06:55:00.388  4638  4715 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 06:55:00.402  4638  4710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 06:55:00.411  4638  4710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 06:55:00.412  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 06:55:00.412  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 06:55:00.412  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 06:55:00.412  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 06:55:00.412  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-27 06:55:00.412  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 06:55:00.412  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 06:55:00.412  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 06:55:00.412  5633  5679 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 06:55:00.414  5633  5679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 06:55:00.414  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-27 06:55:00.414  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 06:55:00.414  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 06:55:00.414  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 06:55:00.414  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 06:55:00.414  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-27 06:55:00.414  5633  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 06:55:00.414  5633  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 06:55:00.414  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 06:55:00.415  5633  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 06:55:00.415  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 06:55:00.415  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-27 06:55:00.415  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 06:55:00.415  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 06:55:00.415  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 06:55:00.415  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 06:55:00.416  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:55:00.416  5633  5679 D BluetoothLeScanner: could not find callback wrapper
,09-27 06:55:00.416  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 06:55:00.416  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 06:55:00.417  4638  4715 D BtGatt.AdvertiseManager: message : 1
09-27 06:55:00.418  4638  4715 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 06:55:00.425  4638  4710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 06:55:00.425  4638  4710 D BtGatt.GattService: Client app is not null!
,09-27 06:55:00.426  4638  4660 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 06:55:00.427  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 06:55:00.427  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 06:55:00.427  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 06:55:00.427  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 06:55:00.427  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 06:55:00.429  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 06:55:00.429  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 06:55:00.429  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 06:55:00.430  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 06:55:00.431  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 06:55:00.431  5633  5633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 06:55:00.431  5633  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 06:55:00.431  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:00.431  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:00.431  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 06:55:00.433  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-27 06:55:00.433  5633  5679 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-27 06:55:00.434  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-27 06:55:00.435  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-27 06:55:00.437  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,09-27 06:55:00.437  5633  5679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-27 06:55:00.438  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-27 06:55:00.438  5633  5679 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-27 06:55:00.439  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-27 06:55:00.439  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 06:55:00.439  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 06:55:00.439  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 06:55:00.439  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 06:55:00.440  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 06:55:00.440  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 06:55:00.440  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 06:55:00.440  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 06:55:00.440  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 06:55:00.440  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 06:55:00.440  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 06:55:00.440  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 06:55:00.441  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-27 06:55:00.441  5633  5679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 06:55:00.443  5633  5679 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 06:55:00.443  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-27 06:55:00.449  5633  5679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-27 06:55:00.450  5633  5679 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 06:55:00.450  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 06:55:00.451  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-27 06:55:00.452  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 06:55:00.452  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 06:55:00.452  5633  5679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-27 06:55:00.452  5633  5679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 06:55:00.452  5633  5679 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-27 06:55:00.452  5633  5679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 06:55:00.452  5633  5679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 06:55:00.452  5633  5679 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-27 06:55:00.452  5633  5679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 06:55:00.452  5633  5679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 06:55:00.453  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-27 06:55:00.460  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-27 06:55:00.460  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-27 06:55:00.460  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-27 06:55:00.461  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-27 06:55:00.461  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-27 06:55:00.461  5633  5679 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-27 06:55:00.461  5633  5679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 06:55:00.461  5633  5679 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-27 06:55:00.461  5633  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
09-27 06:55:00.462  5633  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-27 06:55:00.462  5633  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:55:00.464  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-27 06:55:00.460  4660  4660 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29675]" dev="sockfs" ino=29675 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:55:00.464  5633  5679 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-27 06:55:00.460  4660  4660 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29675]" dev="sockfs" ino=29675 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:55:00.465  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,09-27 06:55:00.465  5633  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-27 06:55:00.466  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-27 06:55:00.466  5633  5679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-27 06:55:00.466  5633  5679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-27 06:55:00.467  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 06:55:00.467  5633  5679 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-27 06:55:00.467  5633  5679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 06:55:00.467  5633  5679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-27 06:55:00.467  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 06:55:00.467  5633  5679 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-27 06:55:00.467  5633  5679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 06:55:00.467  5633  5679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 06:55:00.467  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 06:55:00.467  5633  5679 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-27 06:55:00.468  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-27 06:55:00.468  5633  5679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 06:55:00.468  5633  5679 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 06:55:00.468  5633  5679 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-27 06:55:00.468  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-27 06:55:00.469  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 06:55:00.469  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 06:55:00.469  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 06:55:00.469  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:55:00.470  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 06:55:00.470  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 06:55:00.471  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 06:55:00.471  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 06:55:00.471  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-27 06:55:00.471  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 06:55:00.471  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:55:00.471  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 06:55:00.472  5633  5690 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:55:00.474  5633  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-27 06:55:00.470  4847  4847 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29678]" dev="sockfs" ino=29678 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:55:00.470  4847  4847 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[29678]" dev="sockfs" ino=29678 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:55:00.475  5633  5679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 06:55:00.475  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 06:55:00.479  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 06:55:00.479  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 06:55:00.480  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 06:55:00.482  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 06:55:00.482  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 06:55:00.482  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
,09-27 06:55:00.483  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:55:00.483  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:55:00.483  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 06:55:00.483  5633  5679 D BluetoothAdapter: STATE_ON
,09-27 06:55:00.485  4638  4847 D BtGatt.GattService: registerClient() - UUID=0fae65b2-1785-46a7-8c66-298d32a67eb2
,09-27 06:55:00.485  4638  4710 D BtGatt.GattService: onClientRegistered() - UUID=0fae65b2-1785-46a7-8c66-298d32a67eb2, clientIf=5
09-27 06:55:00.485  5633  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 06:55:00.487  4638  4715 D BtGatt.AdvertiseManager: message : 0
,09-27 06:55:00.489  4638  4715 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 06:55:00.500  4638  4710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 06:55:00.507  4638  4710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 06:55:00.507  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 06:55:00.508  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 06:55:00.509  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 06:55:00.511  5633  5679 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 06:55:00.511  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 06:55:00.511  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 06:55:00.511  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 06:55:00.511  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 06:55:00.511  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 06:55:00.511  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 06:55:00.514  5633  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 06:55:00.514  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 06:55:01.012  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 06:55:01.013  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-27 06:55:01.013  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 06:55:01.013  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 06:55:01.014  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 06:55:01.014  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 06:55:01.014  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-27 06:55:01.014  5633  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 06:55:01.014  5633  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 06:55:01.014  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-27 06:55:01.014  5633  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-27 06:55:01.015  5633  5633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-27 06:55:01.018  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 06:55:01.018  5633  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-27 06:55:01.019  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0e5ab6 removed from the list
,09-27 06:55:01.020  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 06:55:01.020  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 06:55:01.021  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 06:55:01.021  5633  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
,09-27 06:55:01.021  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 06:55:01.021  5633  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
09-27 06:55:01.021  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 06:55:01.022  5633  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
09-27 06:55:01.022  5633  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
09-27 06:55:01.023  4638  4844 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-27 06:55:01.026  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:55:01.026  5633  5679 D BluetoothLeScanner: could not find callback wrapper
09-27 06:55:01.026  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 06:55:01.026  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 06:55:01.029  4638  4715 D BtGatt.AdvertiseManager: message : 1
09-27 06:55:01.030  4638  4715 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 06:55:01.043  4638  4710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 06:55:01.043  4638  4710 D BtGatt.GattService: Client app is not null!
09-27 06:55:01.044  4638  4660 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 06:55:01.045  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 06:55:01.045  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 06:55:01.045  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 06:55:01.045  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 06:55:01.045  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 06:55:01.047  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:55:01.047  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 06:55:01.047  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 06:55:01.048  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 06:55:01.049  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38443b7 removed from the list
09-27 06:55:01.049  5633  5679 D io.jxcore.node.ConnectivityMonitor: stop
09-27 06:55:01.049  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:01.049  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 06:55:01.050  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:01.050  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 06:55:01.053  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,09-27 06:55:01.054  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 06:55:01.054  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 06:55:01.056  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 06:55:01.057  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-27 06:55:01.057  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 06:55:01.057  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 06:55:01.056  4855  4855 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30585]" dev="sockfs" ino=30585 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:55:01.057  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 06:55:01.058  5633  5692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 06:55:01.058  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 06:55:01.058  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
09-27 06:55:01.059  5633  5679 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-27 06:55:01.061  5633  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 06:55:01.059  5633  5679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 06:55:01.061  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-27 06:55:01.056  4855  4855 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30585]" dev="sockfs" ino=30585 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 06:55:01.062  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 06:55:01.062  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-27 06:55:01.066  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,09-27 06:55:01.073  5633  5679 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
09-27 06:55:01.074  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 06:55:01.074  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-27 06:55:01.074  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 06:55:01.074  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 06:55:01.074  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 06:55:01.074  5633  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 06:55:01.074  5633  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 06:55:01.074  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 06:55:01.074  5633  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 06:55:01.074  5633  5679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0e5ab6 not in the list
09-27 06:55:01.074  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 06:55:01.074  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 06:55:01.074  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 06:55:01.074  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-27 06:55:01.074  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 06:55:01.074  5633  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 06:55:01.075  5633  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 06:55:01.075  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 06:55:01.076  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:55:01.076  5633  5679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38443b7 not in the list
09-27 06:55:01.076  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:01.076  5633  5679 D io.jxcore.node.ConnectivityMonitor: stop
09-27 06:55:01.076  5633  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 06:55:01.076  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 06:55:01.076  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:55:01.076  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 06:55:01.078  5633  5679 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-27 06:55:01.078  5633  5679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-27 06:55:01.078  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 06:55:01.078  5633  5679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-27 06:55:01.078  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 06:55:01.078  5633  5679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-27 06:55:01.079  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 06:55:01.079  5633  5679 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
09-27 06:55:01.080  5633  5679 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
09-27 06:55:01.081  5633  5679 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-27 06:55:01.081  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-27 06:55:01.081  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-27 06:55:01.081  5633  5679 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
09-27 06:55:01.081  5633  5679 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-27 06:55:01.081  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 06:55:01.081  5633  5679 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-27 06:55:01.081  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 06:55:01.081  5633  5679 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-27 06:55:01.081  5633  5679 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-27 06:55:01.082  5633  5679 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-27 06:55:01.082  5633  5679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-27 06:55:01.082  5633  5679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-27 06:55:01.082  5633  5679 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-27 06:55:01.082  5633  5679 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-27 06:55:01.083  5633  5679 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-27 06:55:01.083  5633  5679 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-27 06:55:01.083  5633  5679 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-27 06:55:01.083  5633  5679 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-27 06:55:01.083  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 06:55:01.083  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf788a7 added. We now have 3 listener(s)
09-27 06:55:01.085  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 06:55:01.085  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 06:55:01.085  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 06:55:01.085  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 06:55:01.085  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c324154 added. We now have 3 listener(s)
09-27 06:55:01.085  5633  5679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 06:55:01.086  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 06:55:01.090  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:55:01.095  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 06:55:01.095  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:01.095  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:01.095  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:01.095  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:01.095  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 06:55:01.095  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 06:55:01.095  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 06:55:01.097  5633  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 06:55:01.097  5633  5679 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 06:55:01.100  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:01.102  5633  5679 D BluetoothAdapter: enable(): BT is already enabled..!
09-27 06:55:01.102   933  3637 D WifiService: setWifiEnabled: true pid=5633, uid=10077
09-27 06:55:01.102   933  3637 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:01.104  5633  5679 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
09-27 06:55:01.104  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:01.107  5633  5679 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
09-27 06:55:01.108  5633  5679 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-27 06:55:01.112   933  3437 D WifiService: setWifiEnabled: false pid=5633, uid=10077
09-27 06:55:01.112   933  3437 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:01.115   933  3000 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-27 06:55:01.115   933  3000 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-27 06:55:01.115   933  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 06:55:01.115   933  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 06:55:01.125   933  5396 D DhcpClient: Clearing IP address
09-27 06:55:01.125   511   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 06:55:01.133   511   920 D CommandListener: Setting iface cfg
,09-27 06:55:01.136  3605  5449 V NativeCrypto: Read error: ssl=0x7f85e06880: I/O error during system call, Connection timed out
,09-27 06:55:01.136   933  5397 D DhcpClient: Receive thread stopped
09-27 06:55:01.138  3605  5449 V NativeCrypto: SSL shutdown failed: ssl=0x7f85e06880: I/O error during system call, Broken pipe
09-27 06:55:01.140   933  3877 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-27 06:55:01.141   933  5394 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-27 06:55:01.143   933  5394 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-27 06:55:01.143   933  3002 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-27 06:55:01.144   933  3002 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,09-27 06:55:01.144   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 06:55:01.145   933  3002 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-27 06:55:01.145   933  3002 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-27 06:55:01.146   537   537 E Parcel  : Reading a NULL string not supported here.
09-27 06:55:01.150   933   933 D RttService: SCAN_AVAILABLE : 1
09-27 06:55:01.150   933  3106 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-27 06:55:01.151   933  3002 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-27 06:55:01.154  3778  3931 W QCNEJ   : |CORE| network lost: 100
,09-27 06:55:01.154  3778  3931 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-27 06:55:01.173   933  3000 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-27 06:55:01.182   933  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 06:55:01.189   511   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 06:55:01.208   511   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 06:55:01.209   511   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 06:55:01.210   933  3002 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-27 06:55:01.210   933  3002 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 06:55:01.211   511   920 D TetherController: Setting IP forward enable = 0
09-27 06:55:01.214  5291  5291 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@197e862 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-27 06:55:01.215   933   950 D Tethering: MasterInitialState.processMessage what=3
09-27 06:55:01.216   933  3000 D DhcpClient: doQuit
09-27 06:55:01.216   933  3000 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 06:55:01.217   933  5396 D DhcpClient: onQuitting
09-27 06:55:01.217  3484  3484 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-27 06:55:01.220  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:01.220  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:01.220  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:01.220  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:01.220  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:01.220  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:01.220  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:01.220  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:01.224  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:01.228  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:01.228  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:01.228  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:01.228  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 06:55:01.228  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:01.228  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:01.228  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:01.228  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:01.231  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:01.237  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:01.237  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:01.237  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:01.237  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 06:55:01.237  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:01.237  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:01.237  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:01.237  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:01.237  3484  3484 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-27 06:55:01.240  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:01.242  3484  3484 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-27 06:55:01.243   511   913 W SocketClient: write error (Broken pipe)
,09-27 06:55:01.243   511   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-27 06:55:01.243   511   913 W SocketListener: Error sending broadcast (Broken pipe)
,09-27 06:55:01.245  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:01.245  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:01.245  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:01.245  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 06:55:01.245  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:01.245  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:01.245  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:01.245  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:01.245  3900  3900 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 06:55:01.247  5044  5068 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 06:55:01.247  5044  5068 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 06:55:01.247  5044  5068 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 06:55:01.247  5044  5068 E SarControlService: no key has been found,reset the power
09-27 06:55:01.247  5044  5081 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 06:55:01.247  5044  5081 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 06:55:01.247  5044  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 06:55:01.248  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-27 06:55:01.248  5069  5069 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 06:55:01.248  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:01.250  5044  5081 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 06:55:01.250  5044  5081 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 06:55:01.250  5044  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 06:55:01.250  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 06:55:01.251  5069  5069 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 06:55:01.251  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:01.253  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:01.256  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3bbcbd8 HexData = [00000000ea03000000000000ffffffff]
,09-27 06:55:01.256  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 06:55:01.256  5069  5083 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-27 06:55:01.260  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 06:55:01.260  5044  5055 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 06:55:01.260  3900  3900 D SystemUpdateService: onCreate
09-27 06:55:01.264  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3bbcbd8 HexData = [00000000eb03000000000000ffffffff]
09-27 06:55:01.264  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 06:55:01.264  5069  5083 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-27 06:55:01.265  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-27 06:55:01.265  5044  5054 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 06:55:01.266  3900  3900 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 06:55:01.274  3900  5713 I SystemUpdateService: active receiver: enabled
09-27 06:55:01.274  3484  3484 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-27 06:55:01.275   511   913 W SocketClient: write error (Broken pipe)
09-27 06:55:01.275   511   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-27 06:55:01.275   511   913 W SocketListener: Error sending broadcast (Broken pipe)
,09-27 06:55:01.276  3484  3484 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 06:55:01.277   511   920 E Netd    : netlink response contains error (No such file or directory)
09-27 06:55:01.277  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-27 06:55:01.278   933  3002 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-27 06:55:01.279   933  3002 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-27 06:55:01.279   511   920 D TetherController: Setting IP forward enable = 0
,09-27 06:55:01.284  3900  5419 I iu.UploadsManager: num queued entries: 0
,09-27 06:55:01.284  3900  5419 I iu.UploadsManager: num updated entries: 0
09-27 06:55:01.285  3900  5419 I iu.SyncManager: NEXT; no task
,09-27 06:55:01.287  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-27 06:55:01.288  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 06:55:01.290  5424  5424 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-27 06:55:01.294  5424  5424 D SprintDMHelper: simOperator: 
09-27 06:55:01.294  5424  5424 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 06:55:01.306  5019  5717 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-27 06:55:01.308  3900  5713 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 06:55:01.310  3900  5713 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-27 06:55:01.310  3900  5713 I SystemUpdateService: now status is 0 (complete)
,09-27 06:55:01.310  3900  5713 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 06:55:01.310  3900  5713 I SystemUpdateService: file has been verified
09-27 06:55:01.310  3900  5713 I SystemUpdateService: OTA package size = 21989297
,09-27 06:55:01.316  3900  5713 I SystemUpdateService: showing system update notification
,09-27 06:55:01.318   933  3437 I ActivityManager: Start proc 5718:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-27 06:55:01.331  3900  3900 D SystemUpdateService: onDestroy
,09-27 06:55:01.351  5718  5718 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-27 06:55:01.358   933  3902 I ActivityManager: Killing 4984:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-27 06:55:01.380   933  3000 D wifi    : In wifi stop Hal
,09-27 06:55:01.380   933  3000 D wifi    : halHandle = 0x7f6f8a6f00, mVM = 0x7f8becd140, mCls = 0x100a02
09-27 06:55:01.380   933  3483 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 06:55:01.380   933  3483 D WifiHAL : Got a signal to exit!!!
09-27 06:55:01.380   933  3483 I WifiHAL : Exit wifi_event_loop
09-27 06:55:01.381   933  3000 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-27 06:55:01.381   933  3000 E WifiHAL : Event processing terminated
09-27 06:55:01.381   933  3000 D wifi    : In wifi cleaned up handler
09-27 06:55:01.381   933  3000 I WifiHAL : Internal cleanup completed
,09-27 06:55:01.383  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:01.384  5019  5019 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 06:55:01.385  4107  4246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 06:55:01.385  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:01.387  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:01.405   933  3483 D wifi    : set interface wlan0 flags (DOWN)
,09-27 06:55:01.405   933  3000 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 06:55:01.577  5633  5633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 06:55:01.611   933   950 D Tethering: InitialState.processMessage what=4
,09-27 06:55:01.619   933   950 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 06:55:01.620  5633  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:01.625   933  3173 D WifiService: setWifiEnabled: true pid=5633, uid=10077
,09-27 06:55:01.625   933  3173 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:01.630   511   920 D SoftapController: Softap fwReload - Ok
,09-27 06:55:01.634   511   920 D CommandListener: Setting iface cfg
,09-27 06:55:01.634   511   920 D CommandListener: Trying to bring down wlan0
,09-27 06:55:01.635   511   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 06:55:01.640   933  3000 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 06:55:02.129   933  3976 D WifiService: setWifiEnabled: true pid=5633, uid=10077
,09-27 06:55:02.132   933  3976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:02.248   933  3000 D wifi    : set interface wlan0 flags (UP)
09-27 06:55:02.249   933  3000 I WifiHAL : Initializing wifi
09-27 06:55:02.249   933  3000 I WifiHAL : Creating socket
,09-27 06:55:02.253   933   950 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-27 06:55:02.259   933  3000 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 06:55:02.259   933  3000 D wifi    : Did set static halHandle = 0x7f6f8a6f00
,09-27 06:55:02.259   933  3000 D wifi    : halHandle = 0x7f6f8a6f00, mVM = 0x7f8becd140, mCls = 0x183e
,09-27 06:55:02.259   933  3000 D wifi    : array field set
09-27 06:55:02.260   933  3000 I WifiNative-HAL: interface[0] = wlan0
,09-27 06:55:02.262   933  5733 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547332189952
09-27 06:55:02.262   933  5733 D wifi    : waitForHalEvents called, vm = 0x7f8becd140, obj = 0x183e, env = 0x7f8139a780
,09-27 06:55:02.340  5734  5734 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 06:55:02.362  5734  5734 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 06:55:02.364   933  3000 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-27 06:55:02.374  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:02.375  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:02.376  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:02.381  5734  5734 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 06:55:02.381  5734  5734 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 06:55:02.393   933  3000 D WifiConfigStore: Loading config and enabling all networks 
,09-27 06:55:02.397  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:02.397  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:02.397  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:02.397  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:02.397  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:02.397  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:02.397  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:02.397  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:02.400  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:02.401   933  3000 D WifiConfigStore: loaded 0 passpoint configs
09-27 06:55:02.401   933  3000 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 06:55:02.402   933  3000 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-27 06:55:02.402   933  3000 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-27 06:55:02.403  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:02.403  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:02.403  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:02.403  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:02.403  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:02.403  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:02.403  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:02.403  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:02.403   933  3000 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 06:55:02.403   933  3000 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-27 06:55:02.403   933  3000 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 06:55:02.403   933  3000 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-27 06:55:02.404  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:02.405   933  3000 D WifiNative-HAL: Setting external_sim to 1
09-27 06:55:02.406   933  3000 D wifi    : setting dfs flag to true, 0x7f83a4da40
09-27 06:55:02.406   933  3000 D WifiStateMachine: Setting OUI to DA-A1-19
09-27 06:55:02.406   933  3000 D wifi    : setting scan oui 0x7f83a4da40
09-27 06:55:02.406   933  3000 D WifiHAL : Sending mac address OUI
09-27 06:55:02.407  5019  5019 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 06:55:02.407  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:02.407  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:02.407  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:02.407  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:02.407  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:02.407  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:02.407  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:02.407  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:02.409  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:02.409   933  3000 E native  : do suspend false
,09-27 06:55:02.416   933  3000 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-27 06:55:02.416   933   933 D RttService: SCAN_AVAILABLE : 3
09-27 06:55:02.416   933  3106 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 06:55:02.420   511   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-27 06:55:02.421   511   920 D CommandListener: Setting iface cfg
,09-27 06:55:02.424   933  2999 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-27 06:55:02.424   933  2999 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 06:55:02.429   933  2999 D WifiNative-HAL: p2pGetDeviceAddress
09-27 06:55:02.430   933  2999 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-27 06:55:02.434   933   948 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=217745 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-27 06:55:02.638  5633  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:02.651  4638  4706 D BluetoothAdapterState: Current state: ON, message: 23
,09-27 06:55:02.652  4638  4706 D BluetoothAdapterProperties: Setting state to 13
09-27 06:55:02.652  4638  4706 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 06:55:02.653  4638  4706 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 06:55:02.655  4638  4706 I BluetoothAdapterState: Entering PendingCommandState
,09-27 06:55:02.659  4638  4638 D BluetoothMapService: onReceive
,09-27 06:55:02.660  4638  4638 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 06:55:02.660  4638  4638 D BluetoothMapService: STATE_TURNING_OFF
09-27 06:55:02.661  4638  4638 D BluetoothMapService: MAP Service closeService in
09-27 06:55:02.661  4638  4638 D BluetoothMapMasInstance0: MAP Service shutdown
,09-27 06:55:02.661  4638  4638 D ObexServerSockets0: shutdown(block = true)
09-27 06:55:02.662  4638  4638 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 06:55:02.662  4638  4857 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-27 06:55:02.662  4638  4638 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 06:55:02.663  4638  4858 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-27 06:55:02.663  4638  4844 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-27 06:55:02.666  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 06:55:02.666  4638  4638 I BtOppRfcommListener: stopping Accept Thread
09-27 06:55:02.666  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:02.666  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:02.666  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:02.666  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:02.666  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 06:55:02.666  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:02.666  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:02.666  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:02.667  4638  5305 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-27 06:55:02.668  4638  5305 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-27 06:55:02.668  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 06:55:02.668  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:02.676  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 06:55:02.676  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:02.676  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:02.676  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:02.676  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:02.676  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 06:55:02.676  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:02.676  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:02.676  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:02.677  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 06:55:02.677  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:02.682   933   946 I ActivityManager: Start proc 5738:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-27 06:55:02.682  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 06:55:02.682  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:02.682  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:02.682  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:02.682  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:02.682  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 06:55:02.682  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:02.682  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:02.682  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:02.683  4638  4710 D BluetoothAdapterProperties: Scan Mode:20
09-27 06:55:02.683  4638  4706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 06:55:02.684  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 06:55:02.684  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:02.691  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:02.693  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:02.693  4638  4638 D HeadsetService: Received stop request...Stopping profile...
,09-27 06:55:02.695  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:02.696   933   933 D BluetoothHeadset: Proxy object disconnected
09-27 06:55:02.696   933   933 D BluetoothHeadset: Proxy object disconnected
09-27 06:55:02.696   933   933 D BluetoothHeadset: Proxy object disconnected
09-27 06:55:02.696  3153  3997 D BluetoothHeadset: Proxy object disconnected
09-27 06:55:02.697  3153  3153 D HeadsetProfile: Bluetooth service disconnected
09-27 06:55:02.697  3811  4020 D BluetoothHeadset: Proxy object disconnected
09-27 06:55:02.697  4638  4638 D A2dpService: Received stop request...Stopping profile...
09-27 06:55:02.697  4638  4850 D A2dpStateMachine: Exit Disconnected: -1
,09-27 06:55:02.699   933   933 D BluetoothA2dp: Proxy object disconnected
09-27 06:55:02.699  3153  3153 D BluetoothA2dp: Proxy object disconnected
,09-27 06:55:02.700  4638  4638 D HidService: Received stop request...Stopping profile...
09-27 06:55:02.702  4638  4638 D HidService: Stopping Bluetooth HidService
09-27 06:55:02.703  3153  3153 D BluetoothInputDevice: Proxy object disconnected
09-27 06:55:02.704  3153  3153 D HidProfile: Bluetooth service disconnected
09-27 06:55:02.704  4638  4638 D HealthService: Received stop request...Stopping profile...
,09-27 06:55:02.708  4638  4638 D PanService: Received stop request...Stopping profile...
09-27 06:55:02.709  3153  3153 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 06:55:02.709  3153  3153 D PanProfile: Bluetooth service disconnected
09-27 06:55:02.709  4638  4638 D BluetoothMapService: Received stop request...Stopping profile...
09-27 06:55:02.709  4638  4638 D BluetoothMapService: stop()
09-27 06:55:02.710  4638  4638 D BluetoothMapAppObserver: deinitObservers()
09-27 06:55:02.710  4638  4638 D BluetoothMapAppObserver: removeReceiver()
09-27 06:55:02.711  3153  3153 D BluetoothMap: Proxy object disconnected
09-27 06:55:02.711  3153  3153 D MapProfile: Bluetooth service disconnected
,09-27 06:55:02.711  4638  4638 D SapService: Received stop request...Stopping profile...
,09-27 06:55:02.711  4638  4638 V SapService: stop()
09-27 06:55:02.712  4638  4638 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:02.713  4638  4638 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:02.713  4638  4638 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:02.713  4638  4638 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:02.715  4638  4638 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-27 06:55:02.715  4638  4638 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 06:55:02.715  4638  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:02.715  4638  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:02.715  4638  4638 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:02.715  4638  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:02.715  4638  4638 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:02.715  4638  4638 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:02.716  4638  4638 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:02.717  4638  4638 V BluetoothAdapterState: isTurningOff()=true
,09-27 06:55:02.717  4638  4638 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:02.717  4638  4710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 06:55:02.717  4638  4638 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:02.717  4638  4638 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:02.717  4638  4710 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-27 06:55:02.717  4638  4710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 06:55:02.717  4638  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:02.717  4638  4638 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-27 06:55:02.717  4638  4638 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 06:55:02.717  4638  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:02.717  4638  4710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 06:55:02.717  4638  4826 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 06:55:02.717  4638  4826 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 06:55:02.717  4638  4826 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 06:55:02.717  4638  4638 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:02.717  4638  4826 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 06:55:02.717  4638  4638 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:02.717  4638  4638 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:02.718  4638  4638 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:02.718  4638  4638 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 06:55:02.718  4638  4710 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-27 06:55:02.718  4638  4638 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 06:55:02.720  4638  4638 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:02.720  4638  4638 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:02.720  4638  4638 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:02.720  4638  4638 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:02.720  4638  4638 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 06:55:02.720  4638  4638 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 06:55:02.721  4638  4638 D BluetoothMapService: MAP Service closeService in
09-27 06:55:02.721  4638  4638 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:02.721  4638  4638 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:02.721  4638  4638 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:02.721  4638  4638 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:02.721  4638  4638 D BluetoothMapService: cleanup()
09-27 06:55:02.722  4638  4638 D BluetoothMapService: MAP Service closeService in
09-27 06:55:02.722  4638  4638 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:02.722  4638  4638 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:02.722  4638  4638 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:02.722  4638  4638 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:02.722  4638  4706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 06:55:02.722  4638  4706 D BluetoothAdapterProperties: Setting state to 15
09-27 06:55:02.722  4638  4706 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 06:55:02.722  4638  4706 I BluetoothAdapterState: Entering BleOnState
,09-27 06:55:02.731  3153  3170 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 06:55:02.731  3153  3164 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 06:55:02.732   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 06:55:02.732   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 06:55:02.732  3811  3844 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 06:55:02.733  3153  3997 D BluetoothMap: onBluetoothStateChange: up=false
09-27 06:55:02.733  5738  5738 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-27 06:55:02.733   933   950 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 06:55:02.733  3153  3983 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 06:55:02.734   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 06:55:02.734  3153  3170 D BluetoothPan: onBluetoothStateChange on: false
09-27 06:55:02.734  3153  3164 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 06:55:02.735  4638  4706 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 06:55:02.735  4638  4706 D BluetoothAdapterProperties: Setting state to 16
09-27 06:55:02.735  4638  4706 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 06:55:02.736  4638  4706 D BluetoothAdapterProperties: onBleDisable
09-27 06:55:02.736  4638  4706 I BluetoothAdapterState: Entering PendingCommandState
09-27 06:55:02.737  4638  4707 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 06:55:02.737  4638  4710 D BluetoothAdapterProperties: Scan Mode:20
09-27 06:55:02.738  4638  4826 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 06:55:02.738  4638  4826 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:02.739  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:02.742  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:02.744  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:02.745  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:02.746  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:02.747  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 06:55:02.750  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:02.757   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c678a6d:true
09-27 06:55:02.758  3605  3605 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 06:55:02.770   933   944 I ActivityManager: Start proc 5750:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-27 06:55:02.784  5738  5738 D LocalBluetoothProfileManager: Adding local MAP profile
09-27 06:55:02.788  5738  5738 D BluetoothMap: Create BluetoothMap proxy object
09-27 06:55:02.808  5750  5750 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-27 06:55:02.809  5738  5738 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-27 06:55:02.822  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,09-27 06:55:02.826   933  3637 I ActivityManager: Killing 5291:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-27 06:55:02.947  4638  4710 I bt_hci  : shut_down
,09-27 06:55:02.951  4638  4717 D bt_hwcfg: hw_epilog_process
09-27 06:55:02.951  4638  4717 I bt_vendor: low_power_mode_cb
09-27 06:55:02.954  4638  4717 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-27 06:55:02.954  4638  4717 I bt_vendor: epilog_cb
09-27 06:55:02.954  4638  4717 I bt_hci  : epilog_finished_callback
09-27 06:55:02.956  4638  4710 I bt_hci_h4: hal_close
09-27 06:55:02.956  4638  4710 I bt_userial_vendor: device fd = 54 close
,09-27 06:55:03.027  5750  5750 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 06:55:03.027  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-27 06:55:03.028  5750  5750 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 06:55:03.028  5750  5750 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 06:55:03.028  5750  5750 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 06:55:03.028  5750  5750 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:583)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 06:55:03.028  5750  5750 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 06:55:03.028  5750  5750 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 06:55:03.028  5750  5750 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 06:55:03.028  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 06:55:03.032  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 06:55:03.038  3605  3605 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 06:55:03.055  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-27 06:55:03.064  4638  4707 D bt_stack_manager: event_shut_down_stack finished.
09-27 06:55:03.064  4638  4706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-27 06:55:03.066  4638  4638 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 06:55:03.066  4638  4706 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-27 06:55:03.067  4638  4638 D BtGatt.GattService: Received stop request...Stopping profile...
,09-27 06:55:03.067  4638  4638 D BtGatt.GattService: stop()
09-27 06:55:03.067  4638  4638 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 06:55:03.069  4638  4638 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:03.069  4638  4638 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:03.069  4638  4638 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:03.069  4638  4638 V BluetoothAdapterState: isBleTurningOff()=true
09-27 06:55:03.069  4638  4706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-27 06:55:03.069  4638  4706 D BluetoothAdapterProperties: Setting state to 10
09-27 06:55:03.069  4638  4706 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 06:55:03.070  4638  4706 I BluetoothAdapterState: Entering OffState
09-27 06:55:03.071   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-27 06:55:03.077  4638  4638 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-27 06:55:03.077  4638  4638 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 06:55:03.077  4638  4638 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 06:55:03.078  4638  4707 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-27 06:55:03.083  4638  4638 I art     : System.exit called, status: 0
09-27 06:55:03.083  4638  4638 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-27 06:55:03.105   933  3173 I ActivityManager: Killing 4721:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-27 06:55:03.133   933   943 I ActivityManager: Process com.android.bluetooth (pid 4638) has died
,09-27 06:55:03.148  5633  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:03.161   933   950 I ActivityManager: Start proc 5783:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 06:55:03.220  5783  5783 D AdapterServiceConfig: Adding HeadsetService
,09-27 06:55:03.221  5783  5783 D AdapterServiceConfig: Adding A2dpService
09-27 06:55:03.221  5783  5783 D AdapterServiceConfig: Adding HidService
09-27 06:55:03.221  5783  5783 D AdapterServiceConfig: Adding HealthService
09-27 06:55:03.221  5783  5783 D AdapterServiceConfig: Adding PanService
09-27 06:55:03.221  5783  5783 D AdapterServiceConfig: Adding GattService
09-27 06:55:03.221  5783  5783 D AdapterServiceConfig: Adding BluetoothMapService
09-27 06:55:03.221  5783  5783 D AdapterServiceConfig: Adding SapService
,09-27 06:55:03.228   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@87973aa:true
,09-27 06:55:03.228  5783  5783 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 06:55:03.230  5783  5783 I bt_bluedroid: init
,09-27 06:55:03.230  5783  5795 I BluetoothAdapterState: Entering OffState
,09-27 06:55:03.232  5783  5796 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 06:55:03.232  5783  5796 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 06:55:03.232  5783  5796 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 06:55:03.232  5783  5796 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 06:55:03.233  5783  5783 I bt_bluedroid: get_profile_interface socket
,09-27 06:55:03.234  5783  5783 I bt_bluedroid: get_profile_interface sdp
,09-27 06:55:03.235  5783  5799 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 06:55:03.236  5783  5799 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 06:55:03.237  5783  5794 I bt_bluedroid: config_hci_snoop_log
,09-27 06:55:03.238   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-27 06:55:03.241  5783  5795 D BluetoothAdapterState: Current state: OFF, message: 0
,09-27 06:55:03.241  5783  5795 D BluetoothAdapterProperties: Setting state to 14
09-27 06:55:03.241  5783  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-27 06:55:03.243  5783  5795 D BluetoothBondStateMachine: make
,09-27 06:55:03.244  5783  5800 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 06:55:03.246  5783  5795 I BluetoothAdapterState: Entering PendingCommandState
,09-27 06:55:03.246  5783  5783 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 06:55:03.248  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:03.248  5783  5783 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 06:55:03.249  5783  5783 D BtGatt.GattService: Received start request. Starting profile...
09-27 06:55:03.249  5783  5783 D BtGatt.GattService: start()
09-27 06:55:03.249  5783  5783 I bt_bluedroid: get_profile_interface gatt
,09-27 06:55:03.249  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
09-27 06:55:03.249  5783  5783 D BtGatt.AdvertiseManager: advertise manager created
,09-27 06:55:03.252  5783  5783 V BluetoothAdapterState: isTurningOff()=false
,09-27 06:55:03.253  5783  5783 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:03.253  5783  5783 V BluetoothAdapterState: isBleTurningOn()=true
09-27 06:55:03.253  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:03.253  5783  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 06:55:03.254  5783  5795 I bt_bluedroid: bt_bluedroid
09-27 06:55:03.254  5783  5796 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-27 06:55:03.254  5783  5796 I bt_hci  : start_up
,09-27 06:55:03.259  5783  5796 I bt_vendor: alloc value 0xf3fc9871
,09-27 06:55:03.259  5783  5796 I bt_vendor: init
09-27 06:55:03.259  5783  5796 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 06:55:03.259  5783  5796 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 06:55:03.265  5750  5778 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-27 06:55:03.273   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5508313:true
,09-27 06:55:03.366  5783  5796 D bt_hci  : start_up starting async portion
,09-27 06:55:03.363  5806  5806 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-27 06:55:03.366  5783  5803 I bt_hci  : event_finish_startup
09-27 06:55:03.366  5783  5803 I bt_hci_h4: hal_open
09-27 06:55:03.366  5783  5803 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-27 06:55:03.367  5783  5803 I bt_userial_vendor: device fd = 54 open
,09-27 06:55:03.379  5783  5803 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 06:55:03.381  5783  5803 D bt_hwcfg: Chipset BCM4358A3
,09-27 06:55:03.381  5783  5803 D bt_hwcfg: Target name = [BCM4358A3]
09-27 06:55:03.381  5783  5803 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 06:55:03.654  5783  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-27 06:55:03.770  5783  5803 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 06:55:03.771  5783  5803 D bt_hwcfg: Settlement delay -- 100 ms
,09-27 06:55:03.771  5783  5803 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 06:55:03.840   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-27 06:55:03.840   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 06:55:03.895  5783  5803 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 06:55:03.895  5783  5803 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-27 06:55:03.897  5783  5803 I bt_hwcfg: vendor lib fwcfg completed
,09-27 06:55:03.897  5783  5803 I bt_vendor: firmware callback
,09-27 06:55:03.897  5783  5803 I bt_hci  : firmware_config_callback
,09-27 06:55:03.906  5783  5810 I bt_btu  : btu_task pending for preload complete event
,09-27 06:55:03.906  5783  5810 I bt_btu_task: Bluetooth chip preload is complete
09-27 06:55:03.906  5783  5810 I bt_btu  : btu_task received preload complete event
,09-27 06:55:03.912  5783  5810 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 06:55:03.912  5783  5810 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 06:55:03.912  5783  5810 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-27 06:55:03.912  5783  5810 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 06:55:03.912  5783  5810 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 06:55:03.913  5783  5810 I         : BTE_InitTraceLevels -- TRC_A2D
,09-27 06:55:03.913  5783  5810 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-27 06:55:03.913  5783  5810 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 06:55:03.913  5783  5810 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 06:55:03.913  5783  5810 I         : BTE_InitTraceLevels -- TRC_PAN
,09-27 06:55:03.913  5783  5810 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 06:55:03.913  5783  5810 I         : BTE_InitTraceLevels -- TRC_GATT
09-27 06:55:03.913  5783  5810 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 06:55:03.914  5783  5810 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 06:55:03.914  5783  5810 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 06:55:03.997  5783  5810 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f47549
,09-27 06:55:03.997  5783  5810 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f47549 
,09-27 06:55:04.013  5783  5799 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 06:55:04.015  5783  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 06:55:04.015  5783  5799 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 06:55:04.018  5783  5799 D BluetoothAdapterProperties: Name is: Nexus 6P
09-27 06:55:04.020  5783  5799 D BluetoothAdapterProperties: Scan Mode:20
09-27 06:55:04.020  5783  5799 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 06:55:04.021  5783  5799 D bt_hci  : do_postload posting postload work item
09-27 06:55:04.021  5783  5803 I bt_hci  : event_postload
09-27 06:55:04.021  5783  5803 I bt_vendor: sco_config_cb
09-27 06:55:04.021  5783  5803 I bt_hci  : sco_config_callback postload finished.
,09-27 06:55:04.026  5783  5799 D bt_bte_conf: Device ID record 1 : primary
09-27 06:55:04.027  5783  5799 D bt_bte_conf:   vendorId            = 000f
,09-27 06:55:04.027  5783  5799 D bt_bte_conf:   vendorIdSource      = 0001
09-27 06:55:04.027  5783  5799 D bt_bte_conf:   product             = 1200
09-27 06:55:04.027  5783  5799 D bt_bte_conf:   version             = 1436
09-27 06:55:04.027  5783  5799 D bt_bte_conf:   clientExecutableURL = 
09-27 06:55:04.027  5783  5799 D bt_bte_conf:   serviceDescription  = 
09-27 06:55:04.027  5783  5799 D bt_bte_conf:   documentationURL    = 
09-27 06:55:04.027  5783  5799 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 06:55:04.027  5783  5796 D bt_stack_manager: event_start_up_stack finished
09-27 06:55:04.028  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:04.030  5783  5803 I bt_vendor: low_power_mode_cb
,09-27 06:55:04.030  5783  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 06:55:04.031  5783  5795 D BluetoothAdapterProperties: Setting state to 15
09-27 06:55:04.031  5783  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 06:55:04.032  5783  5795 I BluetoothAdapterState: Entering BleOnState
09-27 06:55:04.034  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:04.039  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.040  5783  5795 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-27 06:55:04.040  5783  5795 D BluetoothAdapterProperties: Setting state to 11
09-27 06:55:04.040  5783  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 06:55:04.045  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.048  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
09-27 06:55:04.049  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.050  5783  5783 D HeadsetService: Received start request. Starting profile...
,09-27 06:55:04.051  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.053  5783  5783 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 06:55:04.053  5783  5783 D HeadsetStateMachine: make
,09-27 06:55:04.060  5783  5795 I BluetoothAdapterState: Entering PendingCommandState
,09-27 06:55:04.062  5783  5783 D HeadsetStateMachine: max_hf_connections = 1
,09-27 06:55:04.062  5783  5783 I bt_bluedroid: get_profile_interface handsfree
09-27 06:55:04.062  5783  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 06:55:04.063  5783  5799 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,09-27 06:55:04.066  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:04.067  5783  5783 D A2dpService: Received start request. Starting profile...
09-27 06:55:04.067  3605  3605 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 06:55:04.067  5783  5783 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 06:55:04.068  5783  5783 I bt_bluedroid: get_profile_interface avrcp
,09-27 06:55:04.073  5783  5783 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 06:55:04.073  5783  5783 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 06:55:04.073  5783  5783 D A2dpStateMachine: make
09-27 06:55:04.074  5783  5783 I bt_bluedroid: get_profile_interface a2dp
,09-27 06:55:04.075  5783  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 06:55:04.076  5783  5819 D A2dpStateMachine: Enter Disconnected: -2
,09-27 06:55:04.077  5783  5783 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 06:55:04.077  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:04.079  5783  5783 D HidService: Received start request. Starting profile...
,09-27 06:55:04.079  5783  5783 I bt_bluedroid: get_profile_interface hidhost
09-27 06:55:04.079  5783  5783 D HidService: setHidService(): set to: null
09-27 06:55:04.079  5783  5799 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f2856d
09-27 06:55:04.079  5783  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 06:55:04.079  5738  5738 D BluetoothInputDevice: Proxy object connected
09-27 06:55:04.080  5783  5783 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 06:55:04.080  5738  5738 D HidProfile: Bluetooth service connected
09-27 06:55:04.080  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
09-27 06:55:04.081  5783  5783 D HealthService: Received start request. Starting profile...
,09-27 06:55:04.082  5783  5783 I bt_bluedroid: get_profile_interface health
,09-27 06:55:04.083  5783  5783 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 06:55:04.084  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:04.085  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 06:55:04.085  5783  5783 D PanService: Received start request. Starting profile...
09-27 06:55:04.085  5783  5783 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 06:55:04.085  5783  5783 I bt_bluedroid: get_profile_interface pan
09-27 06:55:04.085  5738  5738 D PanProfile: Bluetooth service connected
09-27 06:55:04.085  5783  5799 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-27 06:55:04.087  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
09-27 06:55:04.088  5738  5738 D BluetoothMap: Proxy object connected
09-27 06:55:04.088  5783  5783 D BluetoothMapService: Received start request. Starting profile...
09-27 06:55:04.088  5783  5783 D BluetoothMapService: start()
09-27 06:55:04.089  5738  5738 D MapProfile: Bluetooth service connected
09-27 06:55:04.089  5738  5738 D BluetoothMap: getConnectedDevices()
09-27 06:55:04.090  5738  5738 D BluetoothMap: Bluetooth is Not enabled
09-27 06:55:04.091  5783  5783 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-27 06:55:04.092  5783  5783 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-27 06:55:04.092  5783  5783 D BluetoothMapAppObserver: createReceiver()
09-27 06:55:04.093  5783  5783 D BluetoothMapAppObserver: initObservers()
09-27 06:55:04.093  5783  5783 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-27 06:55:04.099  5783  5783 V SapService: SapBinder()
,09-27 06:55:04.099  5783  5783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:04.100  5783  5783 D SapService: Received start request. Starting profile...
09-27 06:55:04.100  5783  5783 V SapService: start()
,09-27 06:55:04.103  5783  5783 V BluetoothAdapterState: isTurningOff()=false
,09-27 06:55:04.103  5783  5783 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:04.103  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.103  5783  5817 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 06:55:04.103  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 06:55:04.103  5783  5783 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:04.103  5783  5783 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:04.103  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 06:55:04.103  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.104  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.105  5783  5783 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:04.105  5783  5783 V BluetoothAdapterState: isTurningOn()=true
,09-27 06:55:04.105  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.105  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.106  5783  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 06:55:04.106  5783  5795 D BluetoothAdapterProperties: ScanMode =  20
09-27 06:55:04.106  5783  5795 D BluetoothAdapterProperties: State =  11
,09-27 06:55:04.107  5783  5799 D BluetoothAdapterProperties: Scan Mode:21
,09-27 06:55:04.107  5783  5799 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 06:55:04.107  5783  5795 D BluetoothAdapterProperties: Setting state to 12
,09-27 06:55:04.107  5783  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 06:55:04.108  5783  5795 I BluetoothAdapterState: Entering OnState
09-27 06:55:04.108  3153  3997 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:04.109  3153  3983 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 06:55:04.109  5633  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-27 06:55:04.111  3153  3153 D BluetoothInputDevice: Proxy object connected
09-27 06:55:04.111  3153  3153 D HidProfile: Bluetooth service connected
09-27 06:55:04.111  5633  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-27 06:55:04.113   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:04.113   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:04.113  3811  3844 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:04.114  3153  3170 D BluetoothMap: onBluetoothStateChange: up=true
09-27 06:55:04.114  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:04.114  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:04.114  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:04.114  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:04.114  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:04.114  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:04.114  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:04.114  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:04.116   933   950 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 06:55:04.117  3153  3153 D BluetoothMap: Proxy object connected
09-27 06:55:04.117  3153  3153 D MapProfile: Bluetooth service connected
09-27 06:55:04.117  3153  3153 D BluetoothMap: getConnectedDevices()
09-27 06:55:04.117  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:04.117  5738  5748 D BluetoothPan: onBluetoothStateChange on: true
09-27 06:55:04.118  5738  5749 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 06:55:04.118   933   933 D BluetoothA2dp: Proxy object connected
09-27 06:55:04.118  3153  3164 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 06:55:04.119  5783  5783 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 06:55:04.119  5783  5783 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-27 06:55:04.122  5783  5783 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:55:04.122  3153  3153 D BluetoothA2dp: Proxy object connected
09-27 06:55:04.122  5738  5748 D BluetoothMap: onBluetoothStateChange: up=true
09-27 06:55:04.123   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:04.123  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:04.123  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:04.123  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:04.123  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:04.123  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:04.123  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:04.123  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:04.123  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:04.123  3153  3170 D BluetoothPan: onBluetoothStateChange on: true
09-27 06:55:04.125  5783  5783 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:55:04.127  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:04.127  5783  5783 D ObexServerSockets: Succeed to create listening sockets 
,09-27 06:55:04.127  5783  5783 D ObexServerSockets0: startAccept()
09-27 06:55:04.127  5783  5783 D ObexServerSockets0: prepareForNewConnect()
09-27 06:55:04.129  3153  3153 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 06:55:04.129  3153  3153 D PanProfile: Bluetooth service connected
09-27 06:55:04.130  3153  3997 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 06:55:04.130  5783  5783 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 06:55:04.130  5783  5783 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-27 06:55:04.131  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:04.131  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:04.131  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:04.131  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:04.131  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:04.131  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:04.131  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:04.131  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:04.132  5783  5826 D ObexServerSockets0: Accepting socket connection...
09-27 06:55:04.132  5783  5827 D ObexServerSockets0: Accepting socket connection...
09-27 06:55:04.132  5738  5749 D BluetoothPbap: onBluetoothStateChange: up=true
,09-27 06:55:04.133  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:04.134   933   933 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 06:55:04.135  5783  5783 D BluetoothMapService: onReceive
09-27 06:55:04.135  5783  5783 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 06:55:04.135  5783  5783 D BluetoothMapService: STATE_ON
,09-27 06:55:04.136  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.137  5783  5828 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 06:55:04.138  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:04.139  5783  5828 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 06:55:04.139  5783  5828 D BluetoothSdpJni: SDP Create record success - handle: 1
09-27 06:55:04.139  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:04.139  5738  5738 D LocalBluetoothProfileManager: Adding local A2DP profile
09-27 06:55:04.142  5738  5738 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-27 06:55:04.148  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 06:55:04.150  5738  5738 D BluetoothA2dp: Proxy object connected
,09-27 06:55:04.155  3605  3605 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 06:55:04.155  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-27 06:55:04.157  5633  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:04.158  5633  5679 D io.jxcore.node.ConnectivityMonitor: stop
09-27 06:55:04.158  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 06:55:04.160  5633  5679 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-27 06:55:04.160  5633  5679 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
09-27 06:55:04.162  3153  3153 D BluetoothPbap: Proxy object connected
09-27 06:55:04.162  3153  3153 D PbapServerProfile: Bluetooth service connected
,09-27 06:55:04.162  5783  5783 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-27 06:55:04.162  5783  5783 D ObexServerSockets0: prepareForNewConnect()
09-27 06:55:04.164  5783  5795 D BluetoothAdapterState: Current state: ON, message: 23
09-27 06:55:04.164  5783  5795 D BluetoothAdapterProperties: Setting state to 13
09-27 06:55:04.165  5783  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 06:55:04.165  5783  5795 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 06:55:04.165  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.166  5783  5795 I BluetoothAdapterState: Entering PendingCommandState
09-27 06:55:04.166  5738  5738 D BluetoothPbap: Proxy object connected
,09-27 06:55:04.167  5738  5738 D PbapServerProfile: Bluetooth service connected
09-27 06:55:04.167  5783  5799 D BluetoothAdapterProperties: Scan Mode:20
09-27 06:55:04.168  5783  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-27 06:55:04.170  5738  5738 D BluetoothPbap: Proxy object disconnected
,09-27 06:55:04.170  5738  5738 D PbapServerProfile: Bluetooth service disconnected
09-27 06:55:04.172  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 06:55:04.172  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:04.172  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:04.172  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:04.172  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:04.172  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 06:55:04.172  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:04.172  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:04.172  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:04.173  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 06:55:04.173  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:04.175  3153  3153 D BluetoothPbap: Proxy object disconnected
09-27 06:55:04.175  3153  3153 D PbapServerProfile: Bluetooth service disconnected
09-27 06:55:04.175  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 06:55:04.176  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 06:55:04.176  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:04.176  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:04.176  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:04.176  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:04.176  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 06:55:04.176  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:04.176  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:04.176  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:04.177  5633  5633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 06:55:04.177  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:04.178  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:04.180  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.183  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,09-27 06:55:04.184  5783  5783 D BluetoothMapService: onReceive
09-27 06:55:04.184  5783  5783 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 06:55:04.185  5783  5783 D BluetoothMapService: STATE_TURNING_OFF
09-27 06:55:04.185  5783  5783 D HeadsetService: Received stop request...Stopping profile...
,09-27 06:55:04.187  5783  5783 D A2dpService: Received stop request...Stopping profile...
,09-27 06:55:04.187  5783  5819 D A2dpStateMachine: Exit Disconnected: -1
09-27 06:55:04.188   933   933 D BluetoothA2dp: Proxy object disconnected
09-27 06:55:04.189  5783  5783 D HidService: Received stop request...Stopping profile...
09-27 06:55:04.189  5783  5783 D HidService: Stopping Bluetooth HidService
09-27 06:55:04.190  5783  5783 D HealthService: Received stop request...Stopping profile...
,09-27 06:55:04.192  5783  5783 D PanService: Received stop request...Stopping profile...
09-27 06:55:04.192  3153  3153 D BluetoothA2dp: Proxy object disconnected
09-27 06:55:04.192  3153  3153 D BluetoothInputDevice: Proxy object disconnected
09-27 06:55:04.192  3153  3153 D HidProfile: Bluetooth service disconnected
09-27 06:55:04.193  3153  3153 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 06:55:04.193  3153  3153 D PanProfile: Bluetooth service disconnected
09-27 06:55:04.193  5738  5738 D BluetoothA2dp: Proxy object disconnected
09-27 06:55:04.194  5738  5738 D BluetoothInputDevice: Proxy object disconnected
09-27 06:55:04.194  5738  5738 D HidProfile: Bluetooth service disconnected
09-27 06:55:04.194  5783  5783 D BluetoothMapService: Received stop request...Stopping profile...
09-27 06:55:04.194  5783  5783 D BluetoothMapService: stop()
09-27 06:55:04.194  5738  5738 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 06:55:04.194  5738  5738 D PanProfile: Bluetooth service disconnected
09-27 06:55:04.196  5783  5783 D BluetoothMapAppObserver: deinitObservers()
09-27 06:55:04.196  5783  5783 D BluetoothMapAppObserver: removeReceiver()
09-27 06:55:04.197  3153  3153 D BluetoothMap: Proxy object disconnected
,09-27 06:55:04.197  3153  3153 D MapProfile: Bluetooth service disconnected
09-27 06:55:04.197  5738  5738 D BluetoothMap: Proxy object disconnected
09-27 06:55:04.197  5738  5738 D MapProfile: Bluetooth service disconnected
09-27 06:55:04.199  5783  5783 D SapService: Received stop request...Stopping profile...
09-27 06:55:04.199  5783  5783 V SapService: stop()
09-27 06:55:04.200  3605  3605 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 06:55:04.203  5783  5783 V BluetoothAdapterState: isTurningOff()=true
,09-27 06:55:04.203  5783  5783 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:04.203  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.203  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.204  5783  5783 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-27 06:55:04.204  5783  5783 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 06:55:04.204  5783  5810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:04.204  5783  5810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:04.204  5783  5783 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:04.204  5783  5810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:04.204  5783  5783 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:04.204  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.204  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.205  5783  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-27 06:55:04.205  5783  5799 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-27 06:55:04.206  5783  5810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:04.206  5783  5783 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:04.206  5783  5783 V BluetoothAdapterState: isTurningOn()=false
,09-27 06:55:04.206  5783  5810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:04.206  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.206  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.206  5783  5810 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 06:55:04.206  5783  5810 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 06:55:04.206  5783  5810 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 06:55:04.206  5783  5810 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 06:55:04.206  5783  5783 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 06:55:04.207  5783  5783 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 06:55:04.207  5783  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 06:55:04.207  5783  5783 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:04.207  5783  5783 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:04.207  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.207  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.207  5783  5783 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 06:55:04.207  5783  5799 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 06:55:04.207  5783  5799 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-27 06:55:04.208  5783  5783 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 06:55:04.208  5783  5783 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:04.208  5783  5783 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:04.208  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.208  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 06:55:04.209  5783  5783 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-27 06:55:04.209  5783  5783 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 06:55:04.209  5783  5783 D BluetoothMapService: MAP Service closeService in
09-27 06:55:04.209  5783  5783 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 06:55:04.210  5783  5783 D ObexServerSockets0: shutdown(block = true)
09-27 06:55:04.210  5783  5826 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-27 06:55:04.210  5783  5783 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 06:55:04.210  5783  5783 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 06:55:04.210  5783  5827 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-27 06:55:04.211  5783  5783 V BluetoothAdapterState: isTurningOff()=true
09-27 06:55:04.211  5783  5783 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:04.211  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 06:55:04.211  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.211  5783  5812 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-27 06:55:04.211  5783  5783 D BluetoothMapService: cleanup()
09-27 06:55:04.212  5783  5783 D BluetoothMapService: MAP Service closeService in
,09-27 06:55:04.214  5783  5783 V BluetoothAdapterState: isTurningOff()=true
,09-27 06:55:04.215  5783  5783 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:04.215  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.215  5783  5783 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.215  5783  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 06:55:04.215  5783  5795 D BluetoothAdapterProperties: Setting state to 15
09-27 06:55:04.215  5783  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 06:55:04.216  5783  5795 I BluetoothAdapterState: Entering BleOnState
,09-27 06:55:04.217  3153  3170 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 06:55:04.218  3153  3997 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 06:55:04.218   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 06:55:04.218   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 06:55:04.219  3811  4018 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 06:55:04.219  5738  5749 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 06:55:04.219  3153  3983 D BluetoothMap: onBluetoothStateChange: up=false
09-27 06:55:04.220   933   950 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 06:55:04.220  5738  5748 D BluetoothPan: onBluetoothStateChange on: false
09-27 06:55:04.221  5738  5749 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 06:55:04.221  3153  3164 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 06:55:04.221  5738  5748 D BluetoothMap: onBluetoothStateChange: up=false
09-27 06:55:04.222   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 06:55:04.222  3153  3170 D BluetoothPan: onBluetoothStateChange on: false
09-27 06:55:04.222  5738  5749 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 06:55:04.223  3153  3997 D BluetoothPbap: onBluetoothStateChange: up=false
,09-27 06:55:04.223  5738  5748 D BluetoothPbap: onBluetoothStateChange: up=false
,09-27 06:55:04.224  5783  5795 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 06:55:04.224  5783  5795 D BluetoothAdapterProperties: Setting state to 16
09-27 06:55:04.224  5783  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 06:55:04.224  5783  5795 D BluetoothAdapterProperties: onBleDisable
09-27 06:55:04.224  5783  5795 I BluetoothAdapterState: Entering PendingCommandState
09-27 06:55:04.224  5783  5796 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 06:55:04.225  5783  5810 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 06:55:04.225  5783  5810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 06:55:04.226  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:04.226  5783  5799 D BluetoothAdapterProperties: Scan Mode:20
09-27 06:55:04.227  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 06:55:04.228  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.230  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:04.231  3605  3605 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 06:55:04.232  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.235  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,09-27 06:55:04.426  5783  5799 I bt_hci  : shut_down
,09-27 06:55:04.427  5783  5803 D bt_hwcfg: hw_epilog_process
09-27 06:55:04.428  5783  5803 I bt_vendor: low_power_mode_cb
,09-27 06:55:04.431  5783  5803 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-27 06:55:04.431  5783  5803 I bt_vendor: epilog_cb
09-27 06:55:04.432  5783  5803 I bt_hci  : epilog_finished_callback
,09-27 06:55:04.433  5783  5799 I bt_hci_h4: hal_close
09-27 06:55:04.434  5783  5799 I bt_userial_vendor: device fd = 54 close
,09-27 06:55:04.555  5783  5796 D bt_stack_manager: event_shut_down_stack finished.
,09-27 06:55:04.556  5783  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-27 06:55:04.560  5783  5795 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-27 06:55:04.561  5783  5783 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 06:55:04.562  5783  5783 D BtGatt.GattService: Received stop request...Stopping profile...
,09-27 06:55:04.562  5783  5783 D BtGatt.GattService: stop()
,09-27 06:55:04.562  5783  5783 D BtGatt.AdvertiseManager: advertise clients cleared
,09-27 06:55:04.566  5783  5783 V BluetoothAdapterState: isTurningOff()=false
,09-27 06:55:04.566  5783  5783 V BluetoothAdapterState: isTurningOn()=false
09-27 06:55:04.566  5783  5783 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:04.566  5783  5783 V BluetoothAdapterState: isBleTurningOff()=true
,09-27 06:55:04.567  5783  5795 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-27 06:55:04.567  5783  5795 D BluetoothAdapterProperties: Setting state to 10
09-27 06:55:04.567  5783  5795 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 06:55:04.568  5783  5795 I BluetoothAdapterState: Entering OffState
09-27 06:55:04.570   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-27 06:55:04.586  5783  5783 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-27 06:55:04.586  5783  5783 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-27 06:55:04.586  5783  5783 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 06:55:04.589  5783  5796 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-27 06:55:04.597  5783  5783 I art     : System.exit called, status: 0
,09-27 06:55:04.598  5783  5783 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 06:55:04.641   933  3173 I ActivityManager: Process com.android.bluetooth (pid 5783) has died
,09-27 06:55:04.666  5633  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 06:55:04.667  5633  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:04.667  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:04.667  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:04.667  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:04.667  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 06:55:04.667  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:04.667  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:04.667  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:04.667  5633  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 06:55:04.667  5633  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:04.669  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:04.699   933   950 I ActivityManager: Start proc 5840:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 06:55:04.790  5840  5840 D AdapterServiceConfig: Adding HeadsetService
,09-27 06:55:04.790  5840  5840 D AdapterServiceConfig: Adding A2dpService
09-27 06:55:04.790  5840  5840 D AdapterServiceConfig: Adding HidService
,09-27 06:55:04.790  5840  5840 D AdapterServiceConfig: Adding HealthService
09-27 06:55:04.791  5840  5840 D AdapterServiceConfig: Adding PanService
09-27 06:55:04.791  5840  5840 D AdapterServiceConfig: Adding GattService
09-27 06:55:04.791  5840  5840 D AdapterServiceConfig: Adding BluetoothMapService
,09-27 06:55:04.791  5840  5840 D AdapterServiceConfig: Adding SapService
,09-27 06:55:04.804   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb14610:true
09-27 06:55:04.805  5840  5840 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 06:55:04.808  5840  5840 I bt_bluedroid: init
,09-27 06:55:04.808  5840  5852 I BluetoothAdapterState: Entering OffState
,09-27 06:55:04.810  5840  5853 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 06:55:04.811  5840  5853 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 06:55:04.811  5840  5853 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 06:55:04.811  5840  5853 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 06:55:04.811  5840  5840 I bt_bluedroid: get_profile_interface socket
,09-27 06:55:04.814  5840  5856 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 06:55:04.814  5840  5840 I bt_bluedroid: get_profile_interface sdp
09-27 06:55:04.815  5840  5856 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 06:55:04.818  5840  5851 I bt_bluedroid: config_hci_snoop_log
,09-27 06:55:04.819   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-27 06:55:04.823  5840  5852 D BluetoothAdapterState: Current state: OFF, message: 0
09-27 06:55:04.823  5840  5852 D BluetoothAdapterProperties: Setting state to 14
09-27 06:55:04.823  5840  5852 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-27 06:55:04.825  5840  5852 D BluetoothBondStateMachine: make
,09-27 06:55:04.826  5840  5857 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 06:55:04.828  5840  5852 I BluetoothAdapterState: Entering PendingCommandState
,09-27 06:55:04.829  5840  5840 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 06:55:04.831  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
09-27 06:55:04.832  5840  5840 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 06:55:04.832  5840  5840 D BtGatt.GattService: Received start request. Starting profile...
09-27 06:55:04.832  5840  5840 D BtGatt.GattService: start()
09-27 06:55:04.832  5840  5840 I bt_bluedroid: get_profile_interface gatt
09-27 06:55:04.833  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:04.833  5840  5840 D BtGatt.AdvertiseManager: advertise manager created
,09-27 06:55:04.837  5840  5840 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:04.838  5840  5840 V BluetoothAdapterState: isTurningOn()=false
,09-27 06:55:04.838  5840  5840 V BluetoothAdapterState: isBleTurningOn()=true
09-27 06:55:04.838  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:04.838  5840  5852 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 06:55:04.840  5840  5852 I bt_bluedroid: bt_bluedroid
09-27 06:55:04.840  5840  5853 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-27 06:55:04.840  5840  5853 I bt_hci  : start_up
,09-27 06:55:04.845  5840  5853 I bt_vendor: alloc value 0xf3fc9871
09-27 06:55:04.845  5840  5853 I bt_vendor: init
09-27 06:55:04.845  5840  5853 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 06:55:04.845  5840  5853 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 06:55:04.956  5840  5853 D bt_hci  : start_up starting async portion
,09-27 06:55:04.956  5840  5860 I bt_hci  : event_finish_startup
09-27 06:55:04.956  5840  5860 I bt_hci_h4: hal_open
09-27 06:55:04.957  5840  5860 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-27 06:55:04.953  5861  5861 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 06:55:04.959  5840  5860 I bt_userial_vendor: device fd = 54 open
,09-27 06:55:04.973  5840  5860 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 06:55:04.976  5840  5860 D bt_hwcfg: Chipset BCM4358A3
,09-27 06:55:04.976  5840  5860 D bt_hwcfg: Target name = [BCM4358A3]
09-27 06:55:04.976  5840  5860 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 06:55:05.176  5840  5852 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-27 06:55:05.371  5840  5860 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 06:55:05.371  5840  5860 D bt_hwcfg: Settlement delay -- 100 ms
09-27 06:55:05.371  5840  5860 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 06:55:05.495  5840  5860 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 06:55:05.496  5840  5860 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-27 06:55:05.497  5840  5860 I bt_hwcfg: vendor lib fwcfg completed
,09-27 06:55:05.497  5840  5860 I bt_vendor: firmware callback
09-27 06:55:05.497  5840  5860 I bt_hci  : firmware_config_callback
,09-27 06:55:05.506  5840  5863 I bt_btu  : btu_task pending for preload complete event
09-27 06:55:05.507  5840  5863 I bt_btu_task: Bluetooth chip preload is complete
,09-27 06:55:05.507  5840  5863 I bt_btu  : btu_task received preload complete event
,09-27 06:55:05.514  5840  5863 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 06:55:05.514  5840  5863 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 06:55:05.514  5840  5863 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-27 06:55:05.514  5840  5863 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 06:55:05.515  5840  5863 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 06:55:05.515  5840  5863 I         : BTE_InitTraceLevels -- TRC_A2D
09-27 06:55:05.515  5840  5863 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-27 06:55:05.515  5840  5863 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 06:55:05.515  5840  5863 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 06:55:05.515  5840  5863 I         : BTE_InitTraceLevels -- TRC_PAN
09-27 06:55:05.515  5840  5863 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 06:55:05.515  5840  5863 I         : BTE_InitTraceLevels -- TRC_GATT
09-27 06:55:05.516  5840  5863 I         : BTE_InitTraceLevels -- TRC_SMP
,09-27 06:55:05.516  5840  5863 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 06:55:05.516  5840  5863 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 06:55:05.542  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 06:55:05.553  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 06:55:05.561  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 06:55:05.569  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 06:55:05.589  5840  5863 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f47549
,09-27 06:55:05.589  5840  5863 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f47549 
,09-27 06:55:05.605  5840  5856 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 06:55:05.606  5840  5856 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 06:55:05.607  5840  5856 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 06:55:05.608  5840  5856 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 06:55:05.610  5840  5856 D BluetoothAdapterProperties: Scan Mode:20
,09-27 06:55:05.610  5840  5856 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 06:55:05.610  5840  5856 D bt_hci  : do_postload posting postload work item
09-27 06:55:05.610  5840  5860 I bt_hci  : event_postload
,09-27 06:55:05.610  5840  5860 I bt_vendor: sco_config_cb
09-27 06:55:05.610  5840  5860 I bt_hci  : sco_config_callback postload finished.
09-27 06:55:05.613  5840  5856 D bt_bte_conf: Device ID record 1 : primary
09-27 06:55:05.613  5840  5856 D bt_bte_conf:   vendorId            = 000f
09-27 06:55:05.613  5840  5856 D bt_bte_conf:   vendorIdSource      = 0001
09-27 06:55:05.613  5840  5856 D bt_bte_conf:   product             = 1200
09-27 06:55:05.613  5840  5856 D bt_bte_conf:   version             = 1436
09-27 06:55:05.613  5840  5856 D bt_bte_conf:   clientExecutableURL = 
09-27 06:55:05.613  5840  5856 D bt_bte_conf:   serviceDescription  = 
09-27 06:55:05.613  5840  5856 D bt_bte_conf:   documentationURL    = 
09-27 06:55:05.613  5840  5856 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 06:55:05.613  5840  5853 D bt_stack_manager: event_start_up_stack finished
09-27 06:55:05.614  5840  5852 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 06:55:05.614  5840  5852 D BluetoothAdapterProperties: Setting state to 15
09-27 06:55:05.614  5840  5852 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 06:55:05.614  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:05.615  5840  5852 I BluetoothAdapterState: Entering BleOnState
09-27 06:55:05.618  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:05.619  5840  5852 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-27 06:55:05.619  5840  5860 I bt_vendor: low_power_mode_cb
09-27 06:55:05.619  5840  5852 D BluetoothAdapterProperties: Setting state to 11
09-27 06:55:05.619  5840  5852 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 06:55:05.626  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:05.628   933   933 D BluetoothHeadset: Proxy object connected
09-27 06:55:05.628   933   933 D BluetoothHeadset: Proxy object connected
09-27 06:55:05.628   933   933 D BluetoothHeadset: Proxy object connected
09-27 06:55:05.628  5840  5840 D HeadsetService: Received start request. Starting profile...
09-27 06:55:05.628  3153  3997 D BluetoothHeadset: Proxy object connected
09-27 06:55:05.629  3153  3153 D HeadsetProfile: Bluetooth service connected
,09-27 06:55:05.631  3811  3844 D BluetoothHeadset: Proxy object connected
09-27 06:55:05.632  5738  5749 D BluetoothHeadset: Proxy object connected
09-27 06:55:05.633  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:05.634  5840  5840 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 06:55:05.634  5840  5840 D HeadsetStateMachine: make
09-27 06:55:05.634  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:05.635  5738  5738 D HeadsetProfile: Bluetooth service connected
,09-27 06:55:05.642  5840  5852 I BluetoothAdapterState: Entering PendingCommandState
,09-27 06:55:05.643  5840  5840 D HeadsetStateMachine: max_hf_connections = 1
,09-27 06:55:05.643  5840  5840 I bt_bluedroid: get_profile_interface handsfree
09-27 06:55:05.643  5840  5856 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-27 06:55:05.644  5840  5856 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-27 06:55:05.646  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
09-27 06:55:05.647  5840  5840 D A2dpService: Received start request. Starting profile...
09-27 06:55:05.648  5840  5840 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 06:55:05.648  5840  5840 I bt_bluedroid: get_profile_interface avrcp
,09-27 06:55:05.654  5840  5840 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 06:55:05.654  5840  5840 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 06:55:05.654  5840  5840 D A2dpStateMachine: make
09-27 06:55:05.656  5840  5840 I bt_bluedroid: get_profile_interface a2dp
,09-27 06:55:05.656  5840  5856 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 06:55:05.659  5840  5871 D A2dpStateMachine: Enter Disconnected: -2
09-27 06:55:05.659  5840  5840 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 06:55:05.660  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
09-27 06:55:05.661  5840  5840 D HidService: Received start request. Starting profile...
09-27 06:55:05.661  5840  5840 I bt_bluedroid: get_profile_interface hidhost
09-27 06:55:05.661  5840  5840 D HidService: setHidService(): set to: null
,09-27 06:55:05.663  5840  5840 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-27 06:55:05.663  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
09-27 06:55:05.664  5840  5840 D HealthService: Received start request. Starting profile...
09-27 06:55:05.665  5840  5840 I bt_bluedroid: get_profile_interface health
09-27 06:55:05.666  5840  5856 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f2856d
09-27 06:55:05.666  5840  5856 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 06:55:05.666  5840  5840 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 06:55:05.667  3605  3605 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 06:55:05.667  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:05.667  5840  5840 D PanService: Received start request. Starting profile...
09-27 06:55:05.667  5840  5840 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 06:55:05.668  5840  5840 I bt_bluedroid: get_profile_interface pan
09-27 06:55:05.668  5840  5856 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-27 06:55:05.671  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:05.672  5840  5840 D BluetoothMapService: Received start request. Starting profile...
09-27 06:55:05.672  5840  5840 D BluetoothMapService: start()
,09-27 06:55:05.675  5840  5840 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-27 06:55:05.676  5840  5840 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 06:55:05.676  5840  5840 D BluetoothMapAppObserver: createReceiver()
,09-27 06:55:05.677  5840  5840 D BluetoothMapAppObserver: initObservers()
,09-27 06:55:05.677  5840  5840 D BluetoothMapAppObserver: getEnabledAccountItems()
09-27 06:55:05.677  5840  5852 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-27 06:55:05.682  5840  5840 V SapService: SapBinder()
09-27 06:55:05.682  5840  5840 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:05.683  5840  5840 D SapService: Received start request. Starting profile...
09-27 06:55:05.683  5840  5840 V SapService: start()
,09-27 06:55:05.684  5840  5840 V BluetoothAdapterState: isTurningOff()=false
,09-27 06:55:05.684  5840  5840 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:05.684  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:05.684  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:05.684  5840  5840 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:05.685  5840  5869 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:05.685  5840  5840 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:05.686  5840  5840 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:05.686  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:05.686  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:05.686  5840  5840 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:05.686  5840  5840 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:05.686  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:05.686  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
09-27 06:55:05.686  5840  5840 V BluetoothAdapterState: isTurningOff()=false
09-27 06:55:05.687  5840  5840 V BluetoothAdapterState: isTurningOn()=true
09-27 06:55:05.687  5840  5840 V BluetoothAdapterState: isBleTurningOn()=false
09-27 06:55:05.687  5840  5840 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 06:55:05.688  5840  5852 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-27 06:55:05.688  5840  5852 D BluetoothAdapterProperties: ScanMode =  20
09-27 06:55:05.688  5840  5852 D BluetoothAdapterProperties: State =  11
09-27 06:55:05.689  5840  5856 D BluetoothAdapterProperties: Scan Mode:21
09-27 06:55:05.689  5840  5856 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 06:55:05.691  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:05.691  5840  5852 D BluetoothAdapterProperties: Setting state to 12
09-27 06:55:05.691  5840  5852 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 06:55:05.691  3153  3170 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:05.691  3153  3997 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 06:55:05.692  5840  5852 I BluetoothAdapterState: Entering OnState
09-27 06:55:05.693   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:05.693   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:05.693  3811  3837 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:05.694  3153  3153 D BluetoothInputDevice: Proxy object connected
09-27 06:55:05.694  5738  5749 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:05.694  3153  3153 D HidProfile: Bluetooth service connected
09-27 06:55:05.694  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:05.694  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:05.694  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:05.694  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:05.694  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:05.694  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:05.694  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:05.694  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:05.694  3153  3164 D BluetoothMap: onBluetoothStateChange: up=true
,09-27 06:55:05.696   933   950 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 06:55:05.697  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:05.697  3153  3153 D BluetoothMap: Proxy object connected
09-27 06:55:05.697  3153  3153 D MapProfile: Bluetooth service connected
09-27 06:55:05.697  3153  3153 D BluetoothMap: getConnectedDevices()
09-27 06:55:05.697  5738  5748 D BluetoothPan: onBluetoothStateChange on: true
09-27 06:55:05.697   933   933 D BluetoothA2dp: Proxy object connected
09-27 06:55:05.699  5738  5749 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 06:55:05.701  3153  3997 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 06:55:05.702  5840  5840 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 06:55:05.702  3153  3153 D BluetoothA2dp: Proxy object connected
09-27 06:55:05.702  5738  5749 D BluetoothMap: onBluetoothStateChange: up=true
09-27 06:55:05.702  5840  5840 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 06:55:05.703  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 06:55:05.703  5738  5738 D PanProfile: Bluetooth service connected
09-27 06:55:05.703  5738  5738 D BluetoothInputDevice: Proxy object connected
09-27 06:55:05.703  5738  5738 D HidProfile: Bluetooth service connected
09-27 06:55:05.704   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 06:55:05.704  3153  3164 D BluetoothPan: onBluetoothStateChange on: true
09-27 06:55:05.704  5840  5840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:55:05.705  3153  3153 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 06:55:05.705  3153  3153 D PanProfile: Bluetooth service connected
09-27 06:55:05.706  5738  5748 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 06:55:05.706  5840  5840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 06:55:05.707  5840  5840 D ObexServerSockets: Succeed to create listening sockets 
09-27 06:55:05.707  5840  5840 D ObexServerSockets0: startAccept()
09-27 06:55:05.707  5840  5840 D ObexServerSockets0: prepareForNewConnect()
,09-27 06:55:05.708  3153  3997 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 06:55:05.709  5840  5840 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 06:55:05.709  5840  5840 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 06:55:05.709  5738  5877 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 06:55:05.710  5840  5878 D ObexServerSockets0: Accepting socket connection...
09-27 06:55:05.710  5840  5879 D ObexServerSockets0: Accepting socket connection...
09-27 06:55:05.711   933   933 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 06:55:05.712   933   933 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-27 06:55:05.712  5840  5840 D BluetoothMapService: onReceive
09-27 06:55:05.712  5840  5840 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 06:55:05.712  5840  5840 D BluetoothMapService: STATE_ON
09-27 06:55:05.713  5738  5738 D BluetoothMap: Proxy object connected
09-27 06:55:05.713  5738  5738 D MapProfile: Bluetooth service connected
09-27 06:55:05.713  5738  5738 D BluetoothMap: getConnectedDevices()
09-27 06:55:05.715  5840  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 06:55:05.716  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:05.716  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:05.716  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:05.716  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:05.716  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:05.716  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:05.716  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:05.716  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:05.716  5840  5882 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 06:55:05.716  5840  5882 D BluetoothSdpJni: SDP Create record success - handle: 1
09-27 06:55:05.716  5738  5738 D BluetoothA2dp: Proxy object connected
09-27 06:55:05.717  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:05.718  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:05.721  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 06:55:05.727  3605  3605 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 06:55:05.728  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-27 06:55:05.733  5738  5738 D BluetoothPbap: Proxy object connected
09-27 06:55:05.733  5738  5738 D PbapServerProfile: Bluetooth service connected
,09-27 06:55:05.734  3153  3153 D BluetoothPbap: Proxy object connected
09-27 06:55:05.734  3153  3153 D PbapServerProfile: Bluetooth service connected
,09-27 06:55:05.738  5840  5840 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 06:55:05.738  5840  5840 D ObexServerSockets0: prepareForNewConnect()
,09-27 06:55:05.741  5840  5886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:55:05.755  5840  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:55:05.756  5840  5890 I BtOppRfcommListener: Accept thread started.
,09-27 06:55:06.187  5633  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:06.187  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:06.187  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:06.187  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:06.187  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:06.187  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:06.187  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:06.187  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:06.192  5633  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:06.196  5633  5679 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,09-27 06:55:06.198   933  3173 D WifiService: setWifiEnabled: false pid=5633, uid=10077
,09-27 06:55:06.198   933  3173 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:06.200  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:06.205   933   933 D RttService: SCAN_AVAILABLE : 1
09-27 06:55:06.205   933  3106 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 06:55:06.216   933  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 06:55:06.217   511   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 06:55:06.224   933  3000 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 06:55:06.225  5734  5734 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-27 06:55:06.236  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:06.236  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:06.236  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:06.236  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 06:55:06.236  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:06.236  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:06.236  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:06.236  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:06.239  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-27 06:55:06.241  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:06.246  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:06.246  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:06.246  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:06.246  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 06:55:06.246  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:06.246  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:06.246  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:06.246  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:06.249  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:06.259  5734  5734 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 06:55:06.262  5734  5734 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 06:55:06.366  5019  5019 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 06:55:06.366   933  3000 D wifi    : In wifi stop Hal
,09-27 06:55:06.368   933  3000 D wifi    : halHandle = 0x7f6f8a6f00, mVM = 0x7f8becd140, mCls = 0x183e
09-27 06:55:06.368   933  5733 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 11
09-27 06:55:06.368   933  5733 D WifiHAL : Got a signal to exit!!!
09-27 06:55:06.369   933  5733 I WifiHAL : Exit wifi_event_loop
,09-27 06:55:06.370   933  3000 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-27 06:55:06.371   933  3000 E WifiHAL : Event processing terminated
09-27 06:55:06.372   933  3000 D wifi    : In wifi cleaned up handler
09-27 06:55:06.372   933  3000 I WifiHAL : Internal cleanup completed
09-27 06:55:06.376  4107  4246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 06:55:06.378  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:06.383  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:06.395   933  5733 D wifi    : set interface wlan0 flags (DOWN)
,09-27 06:55:06.395   933  3000 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 06:55:06.601   933   950 D Tethering: InitialState.processMessage what=4
,09-27 06:55:06.608   933   950 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 06:55:06.715  5633  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:06.715  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:06.715  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:06.715  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 06:55:06.715  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:06.715  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:06.715  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:06.715  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:06.720  5633  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:06.724   933  3637 D WifiService: setWifiEnabled: true pid=5633, uid=10077
09-27 06:55:06.724   933  3637 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-27 06:55:06.726  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:06.729   511   920 D SoftapController: Softap fwReload - Ok
,09-27 06:55:06.732   511   920 D CommandListener: Setting iface cfg
,09-27 06:55:06.733   511   920 D CommandListener: Trying to bring down wlan0
09-27 06:55:06.734   511   920 D CommandListener: Clearing all IP addresses on wlan0
09-27 06:55:06.736   933  3000 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 06:55:07.229   933  3637 D WifiService: setWifiEnabled: true pid=5633, uid=10077
,09-27 06:55:07.233   933  3637 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:07.348   933  3000 D wifi    : set interface wlan0 flags (UP)
09-27 06:55:07.349   933  3000 I WifiHAL : Initializing wifi
09-27 06:55:07.349   933  3000 I WifiHAL : Creating socket
,09-27 06:55:07.355   933   950 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-27 06:55:07.358   933  3000 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 06:55:07.359   933  3000 D wifi    : Did set static halHandle = 0x7f6f8a6f00
,09-27 06:55:07.359   933  3000 D wifi    : halHandle = 0x7f6f8a6f00, mVM = 0x7f8becd140, mCls = 0x200e36
,09-27 06:55:07.359   933  3000 D wifi    : array field set
09-27 06:55:07.360   933  3000 I WifiNative-HAL: interface[0] = wlan0
,09-27 06:55:07.361   933  5894 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547332189952
,09-27 06:55:07.362   933  5894 D wifi    : waitForHalEvents called, vm = 0x7f8becd140, obj = 0x200e36, env = 0x7f8139b5c0
09-27 06:55:07.365   933  3000 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-27 06:55:07.366   933  3000 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
09-27 06:55:07.371  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 06:55:07.375  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:07.420  5895  5895 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 06:55:07.440  5895  5895 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 06:55:07.450  5895  5895 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 06:55:07.450  5895  5895 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 06:55:07.736   933   944 D WifiService: setWifiEnabled: true pid=5633, uid=10077
,09-27 06:55:07.737   933   944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:08.240   933  3889 D WifiService: setWifiEnabled: true pid=5633, uid=10077
,09-27 06:55:08.240   933  3889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:08.380   933  3000 D WifiConfigStore: Loading config and enabling all networks 
,09-27 06:55:08.391  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:08.391  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:08.391  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:08.391  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:08.391  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:08.391  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:08.391  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:08.391  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:08.393  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:08.398  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:08.398  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:08.398  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:08.398  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:08.398  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:08.398  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:08.398  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:08.398  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 06:55:08.398   933  3000 D WifiConfigStore: loaded 0 passpoint configs
09-27 06:55:08.399   933  3000 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 06:55:08.399   933  3000 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-27 06:55:08.401   933  3000 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-27 06:55:08.401  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:08.402   933  3000 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 06:55:08.402   933  3000 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 06:55:08.403   933  3000 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 06:55:08.403   933  3000 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 06:55:08.407   933  3000 D WifiNative-HAL: Setting external_sim to 1
,09-27 06:55:08.407  5019  5019 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 06:55:08.407   933  3000 D wifi    : setting dfs flag to true, 0x7f73a7eb60
09-27 06:55:08.408   933  3000 D WifiStateMachine: Setting OUI to DA-A1-19
09-27 06:55:08.408   933  3000 D wifi    : setting scan oui 0x7f73a7eb60
09-27 06:55:08.408   933  3000 D WifiHAL : Sending mac address OUI
,09-27 06:55:08.413   933  3000 E native  : do suspend false
,09-27 06:55:08.421   933  3000 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-27 06:55:08.421   511   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 06:55:08.422   933   933 D RttService: SCAN_AVAILABLE : 3
09-27 06:55:08.422   933  3106 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 06:55:08.423   511   920 D CommandListener: Setting iface cfg
,09-27 06:55:08.427   933  2999 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
09-27 06:55:08.427   933  2999 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 06:55:08.436   933  2999 D WifiNative-HAL: p2pGetDeviceAddress
,09-27 06:55:08.441   933  2999 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-27 06:55:08.441   933   948 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=223752 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-27 06:55:08.751  5633  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:08.751  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:08.751  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:08.751  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:08.751  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:08.751  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:08.751  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:08.751  5633  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:08.757  5633  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 06:55:08.760  5633  5679 D BluetoothAdapter: enable(): BT is already enabled..!
09-27 06:55:08.761   933  3977 D WifiService: setWifiEnabled: true pid=5633, uid=10077
09-27 06:55:08.761   933  3977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 06:55:08.762  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 06:55:08.763  5633  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 06:55:08.763  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 06:55:08.763  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 06:55:08.763  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf788a7 removed from the list
,09-27 06:55:08.763  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 06:55:08.763  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c324154 removed from the list
09-27 06:55:08.763  5633  5679 D io.jxcore.node.ConnectivityMonitor: stop
09-27 06:55:08.763  5633  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 06:55:08.764  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 06:55:08.767  5633  5679 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,09-27 06:55:08.770  5633  5679 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-27 06:55:08.774  5633  5897 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-27 06:55:08.774  5633  5897 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 06:55:09.287  5633  5899 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-27 06:55:09.287  5633  5897 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-27 06:55:09.288  5633  5897 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 06:55:09.288  5633  5899 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 06:55:09.290  5633  5899 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 06:55:09.290  5633  5897 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 06:55:09.291  5633  5899 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 06:55:09.292  5633  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: IncomingSocketThread/Sender)
09-27 06:55:09.294  5633  5897 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 06:55:09.294  5633  5899 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-27 06:55:09.295  5633  5897 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 06:55:09.300  5633  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: OutgoingSocketThread/Sender)
,09-27 06:55:09.302  5633  5904 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver)
,09-27 06:55:09.303  5633  5903 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Receiver)
,09-27 06:55:09.303  5633  5904 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver)
,09-27 06:55:09.303  5633  5904 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 06:55:09.303  5633  5903 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: IncomingSocketThread/Receiver)
09-27 06:55:09.303  5633  5903 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-27 06:55:09.303  5633  5904 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-27 06:55:09.304  5633  5903 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-27 06:55:09.780  5633  5679 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-27 06:55:09.782  5633  5679 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,09-27 06:55:09.784  5633  5679 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,09-27 06:55:09.788  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-27 06:55:09.789  5633  5679 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-27 06:55:09.791  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,09-27 06:55:09.791  5633  5679 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-27 06:55:09.793  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-27 06:55:09.797  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-27 06:55:09.797  5633  5679 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2df491c Bundle[{}]
09-27 06:55:09.798  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-27 06:55:09.798  5633  5679 I io.jxcore.node.LifeCycleMonitor: start: OK
09-27 06:55:09.798  5633  5679 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-27 06:55:09.799  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-27 06:55:09.799  5633  5679 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-27 06:55:09.800  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,09-27 06:55:09.800  5633  5679 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-27 06:55:09.801  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
09-27 06:55:09.801  5633  5679 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-27 06:55:09.802  5633  5679 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,09-27 06:55:09.803  5633  5679 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-27 06:55:09.805  5633  5679 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,09-27 06:55:09.807  5633  5679 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-27 06:55:09.808  5633  5679 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
09-27 06:55:09.809  5633  5679 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,09-27 06:55:09.810  5633  5679 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,09-27 06:55:09.811  5633  5679 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
09-27 06:55:09.813  5633  5679 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-27 06:55:09.815  5633  5905 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-27 06:55:09.815  5633  5905 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 06:55:09.819  5633  5905 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-27 06:55:09.819  5633  5905 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 06:55:09.819  5633  5905 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 06:55:09.820  5633  5905 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 06:55:09.820  5633  5907 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-27 06:55:09.821  5633  5907 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-27 06:55:09.821  5633  5907 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 06:55:09.821  5633  5908 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: OutgoingSocketThread/Sender)
09-27 06:55:09.821  5633  5905 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 06:55:09.822  5633  5907 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 06:55:09.823  5633  5909 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: OutgoingSocketThread/Receiver)
,09-27 06:55:09.824  5633  5909 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: OutgoingSocketThread/Receiver)
09-27 06:55:09.824  5633  5909 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 06:55:09.824  5633  5910 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: IncomingSocketThread/Sender)
09-27 06:55:09.824  5633  5909 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-27 06:55:09.824  5633  5907 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-27 06:55:09.826  5633  5911 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: IncomingSocketThread/Receiver)
,09-27 06:55:09.827  5633  5911 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: IncomingSocketThread/Receiver)
09-27 06:55:09.827  5633  5911 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-27 06:55:09.827  5633  5911 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-27 06:55:10.320  5633  5679 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-27 06:55:10.322  5633  5679 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
09-27 06:55:10.324  5633  5679 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-27 06:55:10.328  5633  5679 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-27 06:55:10.330  5633  5679 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-27 06:55:10.331  5633  5679 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
09-27 06:55:10.332  5633  5679 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 188)
09-27 06:55:10.333  5633  5679 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,09-27 06:55:10.334  5633  5679 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-27 06:55:10.334  5633  5679 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 189)
,09-27 06:55:10.336  5633  5679 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-27 06:55:10.337  5633  5679 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
09-27 06:55:10.338  5633  5679 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,09-27 06:55:10.339  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 06:55:10.340  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d7c7f9 added. We now have 3 listener(s)
09-27 06:55:10.341  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 06:55:10.341  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 06:55:10.342  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 06:55:10.342  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 06:55:10.342  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364333e added. We now have 3 listener(s)
09-27 06:55:10.342  5633  5679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 06:55:10.343  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 06:55:10.347  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 06:55:10.351  5633  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 06:55:10.351  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:10.351  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:10.351  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:10.351  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:10.351  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 06:55:10.351  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 06:55:10.351  5633  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 06:55:10.355  5633  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 06:55:10.355  5633  5679 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 06:55:10.359  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:10.360  5633  5679 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
09-27 06:55:10.360  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 06:55:10.361  5633  5679 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,09-27 06:55:10.361  5633  5679 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-27 06:55:10.361  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-27 06:55:10.361  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-27 06:55:10.361  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-27 06:55:10.361  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 06:55:10.361  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:55:10.362  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 06:55:10.363  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-27 06:55:10.363  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 06:55:10.363  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 06:55:10.363  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 06:55:10.363  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:55:10.363  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 06:55:10.363  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 06:55:10.367  5633  5679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 06:55:10.368  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 06:55:10.369  5633  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 06:55:10.372  5633  5912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-27 06:55:10.372  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 06:55:10.366  5851  5851 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35880]" dev="sockfs" ino=35880 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:55:10.366  5851  5851 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[35880]" dev="sockfs" ino=35880 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 06:55:10.374  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 06:55:10.374  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 06:55:10.377  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-27 06:55:10.377  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 06:55:10.377  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-27 06:55:10.377  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:55:10.378  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:55:10.378  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-27 06:55:10.378  5633  5679 D BluetoothAdapter: STATE_ON
,09-27 06:55:10.383  5840  5880 D BtGatt.GattService: registerClient() - UUID=0f63b98f-2e63-4586-b7fc-76f23ac4787d
,09-27 06:55:10.384  5840  5856 D BtGatt.GattService: onClientRegistered() - UUID=0f63b98f-2e63-4586-b7fc-76f23ac4787d, clientIf=5
,09-27 06:55:10.384  5633  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 06:55:10.386  5840  5858 D BtGatt.AdvertiseManager: message : 0
,09-27 06:55:10.388  5840  5858 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 06:55:10.398  5840  5856 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 06:55:10.403  5840  5856 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 06:55:10.404  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 06:55:10.404  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 06:55:10.405  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 06:55:10.407  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-27 06:55:10.407  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-27 06:55:10.407  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 06:55:10.407  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 06:55:10.407  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 06:55:10.407  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 06:55:10.410  5633  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 06:55:10.410  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 06:55:10.911  5633  5633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 06:55:10.911  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 06:55:10.911  5633  5633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 06:55:11.635   933  3000 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-27 06:55:11.636   933  3000 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-27 06:55:11.636   933  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 06:55:11.648   933  3000 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 06:55:11.679   933  3000 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 06:55:11.681  5895  5895 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 06:55:12.128  5895  5895 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 06:55:12.169  5895  5895 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-27 06:55:12.171  5895  5895 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 06:55:12.183   933  3000 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
09-27 06:55:12.183   933  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 06:55:12.183   933  3002 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-27 06:55:12.203   933  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 06:55:12.215   511   920 D CommandListener: Setting iface cfg
,09-27 06:55:12.220   933  3000 D WifiStateMachine: Start Dhcp Watchdog 2
,09-27 06:55:12.225   933  5917 D DhcpClient: Receive thread started
,09-27 06:55:12.230   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-27 06:55:12.230   933  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-27 06:55:12.230   933  3002 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-27 06:55:12.310   933  3000 E native  : do suspend false
,09-27 06:55:12.323   933  5916 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 06:55:12.350   933  5917 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172630, domain null
,09-27 06:55:12.351   933  5916 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172630 seconds
,09-27 06:55:12.353   933  5916 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 06:55:12.370   933  5917 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 06:55:12.371   933  5916 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 06:55:12.374   511   920 D CommandListener: Setting iface cfg
,09-27 06:55:12.379   933  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 06:55:12.384   933  5916 D DhcpClient: Scheduling renewal in 86399s
,09-27 06:55:12.396   933  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-27 06:55:12.396   933  3000 D WifiConfigStore: No blacklist allowed without epno enabled
,09-27 06:55:12.397   933  3002 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-27 06:55:12.405   933  3000 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-27 06:55:12.411   933  3002 D ConnectivityService: Adding iface wlan0 to network 101
,09-27 06:55:12.459   933  3002 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 06:55:12.459   933  3002 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-27 06:55:12.462   933  3002 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-27 06:55:12.464   933  3002 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-27 06:55:12.466   933  3002 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-27 06:55:12.473   933  3002 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 06:55:12.477   933  3002 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-27 06:55:12.477   933  3002 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-27 06:55:12.477   933  3002 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-27 06:55:12.477   933  3002 D ConnectivityService:    accepting network in place of null
,09-27 06:55:12.478   933  3000 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 06:55:12.478   933  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 06:55:12.478   933  3002 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 06:55:12.501   511   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 06:55:12.506   933  5915 D NetlinkSocketObserver: NeighborEvent{elapsedMs=227816, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-27 06:55:12.525   511   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 06:55:12.529   933  3002 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-27 06:55:12.529  3778  3931 W QCNEJ   : |CORE| network available: 101
09-27 06:55:12.529   933  3002 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 06:55:12.531   933  3002 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-27 06:55:12.531   933   950 D Tethering: MasterInitialState.processMessage what=3
09-27 06:55:12.539  3778  3931 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-27 06:55:12.539  5044  5068 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 06:55:12.539  5044  5068 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 06:55:12.539  5044  5068 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-27 06:55:12.540  5044  5068 E SarControlService: no key has been found,reset the power
,09-27 06:55:12.540  5044  5081 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 06:55:12.540  5044  5081 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 06:55:12.540  5044  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 06:55:12.541  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 06:55:12.541  5069  5069 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 06:55:12.542  3778  3931 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-27 06:55:12.542  3778  3931 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-27 06:55:12.545  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:12.545  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:12.545  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:12.545  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:12.545  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:12.545  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 06:55:12.545  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 06:55:12.545  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 06:55:12.549  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 06:55:12.549  3900  3900 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 06:55:12.545  5044  5081 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 06:55:12.550  5044  5081 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-27 06:55:12.550  5044  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 06:55:12.553  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-27 06:55:12.553  5069  5069 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-27 06:55:12.553  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:12.553  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:12.553  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:12.553  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:12.553  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:12.553  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 06:55:12.553  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 06:55:12.553  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 06:55:12.555  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 06:55:12.556  3900  3900 D SystemUpdateService: onCreate
09-27 06:55:12.559  5633  5633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 06:55:12.559  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 06:55:12.559  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 06:55:12.559  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 06:55:12.559  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 06:55:12.559  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 06:55:12.559  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 06:55:12.559  5633  5633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 06:55:12.560  3900  3900 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-27 06:55:12.561  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3bbcbd8 HexData = [00000000ec03000000000000ffffffff]
09-27 06:55:12.561  5633  5633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 06:55:12.561  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 06:55:12.561  5069  5083 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-27 06:55:12.561  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 06:55:12.562  5044  5055 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-27 06:55:12.563  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3bbcbd8 HexData = [00000000ed03000000000000ffffffff]
09-27 06:55:12.563  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 06:55:12.563  5069  5083 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-27 06:55:12.564  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 06:55:12.564  5044  5054 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 06:55:12.571  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 06:55:12.574  3900  5419 I iu.UploadsManager: num queued entries: 0
,09-27 06:55:12.574  3900  5419 I iu.UploadsManager: num updated entries: 0
09-27 06:55:12.575  3900  5419 I iu.SyncManager: NEXT; no task
,09-27 06:55:12.582  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 06:55:12.584  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 06:55:12.587  5424  5424 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 06:55:12.591  5424  5424 D SprintDMHelper: simOperator: 
09-27 06:55:12.591  5424  5424 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 06:55:12.595  3900  5928 I SystemUpdateService: active receiver: enabled
,09-27 06:55:12.616  3900  5928 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 06:55:12.627  3900  5928 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-27 06:55:12.627  3900  5928 I SystemUpdateService: now status is 0 (complete)
09-27 06:55:12.627  3900  5928 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 06:55:12.627  3900  5928 I SystemUpdateService: file has been verified
09-27 06:55:12.628  3900  5928 I SystemUpdateService: OTA package size = 21989297
,09-27 06:55:12.633  3900  5928 I SystemUpdateService: showing system update notification
,09-27 06:55:12.642  3900  3900 D SystemUpdateService: onDestroy
,09-27 06:55:12.677   933  5914 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-27 06:55:12.700  5019  5933 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-27 06:55:12.727   933  5914 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 27 Sep 2016 10:55:12 GMT], X-Android-Received-Millis=[1474973712726], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474973712700]}
,09-27 06:55:12.728   933  3002 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-27 06:55:12.728   933  3002 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-27 06:55:12.728   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-27 06:55:12.730   933  3002 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-27 06:55:13.530   933  3002 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-27 06:55:13.841   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 06:55:13.909  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-27 06:55:13.909  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-27 06:55:13.909  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-27 06:55:13.910  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-27 06:55:13.910  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-27 06:55:13.910  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-27 06:55:13.910  5633  5912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-27 06:55:13.911  5633  5912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 06:55:13.911  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-27 06:55:13.911  5633  5912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 06:55:13.911  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 06:55:13.911  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 06:55:13.911  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 06:55:13.911  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 06:55:13.911  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 06:55:13.911  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 06:55:13.916  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:55:13.916  5633  5679 D BluetoothLeScanner: could not find callback wrapper
,09-27 06:55:13.916  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 06:55:13.933  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-27 06:55:13.935  5840  5858 D BtGatt.AdvertiseManager: message : 1
09-27 06:55:13.935  5840  5858 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 06:55:13.943  5840  5856 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 06:55:13.944  5840  5856 D BtGatt.GattService: Client app is not null!
,09-27 06:55:13.947  5840  5850 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 06:55:13.948  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 06:55:13.948  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 06:55:13.948  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 06:55:13.948  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 06:55:13.948  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 06:55:13.950  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:55:13.950  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 06:55:13.950  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 06:55:13.951  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 06:55:13.952  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 06:55:13.952  5633  5633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 06:55:13.952  5633  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 06:55:13.953  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:13.953  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:13.953  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 06:55:13.955  5633  5679 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
09-27 06:55:13.955  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 06:55:13.956  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 06:55:13.956  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 06:55:13.956  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 06:55:13.956  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 06:55:13.956  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 06:55:13.960  5633  5679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 06:55:13.960  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 06:55:13.964  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 06:55:13.964  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 06:55:13.965  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 06:55:13.969  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 06:55:13.969  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 06:55:13.970  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 06:55:13.971  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:55:13.973  5840  5850 D BtGatt.GattService: registerClient() - UUID=f6a74caf-d9fe-452d-a17e-2dd30d2788fd
,09-27 06:55:13.973  5840  5856 D BtGatt.GattService: onClientRegistered() - UUID=f6a74caf-d9fe-452d-a17e-2dd30d2788fd, clientIf=5
,09-27 06:55:13.974  5633  5644 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 06:55:13.975  5840  5876 D BtGatt.GattService: start scan with filters
,09-27 06:55:13.978  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-27 06:55:13.978  5840  5859 D BtGatt.ScanManager: handling starting scan
09-27 06:55:13.979  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 06:55:13.979  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 06:55:13.979  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 06:55:13.981  5840  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c5af69
,09-27 06:55:13.983  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 06:55:13.983  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 06:55:13.983  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 06:55:13.984  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 06:55:13.989  5840  5856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 06:55:13.989  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:13.989  5840  5859 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 06:55:13.995  5840  5856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 06:55:13.995  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 06:55:13.996  5840  5859 D BtGatt.ScanManager: Starting BLE batch scan
09-27 06:55:13.996  5840  5859 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 06:55:14.006  5840  5856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-27 06:55:14.006  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:14.012  5840  5856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 06:55:14.012  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:14.484  5633  5633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-27 06:55:14.485  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 06:55:14.485  5633  5633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 06:55:14.842   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 06:55:15.240   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 06:55:15.843   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 06:55:16.844   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 06:55:16.989  5633  5679 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-27 06:55:16.990  5633  5679 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-27 06:55:16.990  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-27 06:55:16.991  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 06:55:16.991  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 06:55:16.994  5633  5679 D BluetoothAdapter: STATE_ON
,09-27 06:55:17.001  5840  5851 D BtGatt.GattService: stopScan() - queue size =1
,09-27 06:55:17.008  5840  5850 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 06:55:17.008  5840  5840 D BtGatt.ScanManager: awakened up at time 232319
09-27 06:55:17.009  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 06:55:17.009  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 06:55:17.009  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 06:55:17.009  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 06:55:17.009  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 06:55:17.009  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 06:55:17.010  5633  5679 D BluetoothAdapter: STATE_ON
,09-27 06:55:17.013  5840  5856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 06:55:17.014  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:17.014  5840  5859 D BtGatt.ScanManager: stopping BLe Batch
09-27 06:55:17.016  5840  5876 D BtGatt.GattService: registerClient() - UUID=1bb165d2-8372-426b-8cae-50dba2b2058a
,09-27 06:55:17.017  5840  5856 D BtGatt.GattService: onClientRegistered() - UUID=1bb165d2-8372-426b-8cae-50dba2b2058a, clientIf=5
,09-27 06:55:17.017  5633  5765 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 06:55:17.018  5840  5850 D BtGatt.GattService: start scan with filters
,09-27 06:55:17.022  5840  5856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 06:55:17.022  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:17.023  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 06:55:17.023  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 06:55:17.024  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 06:55:17.024  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-27 06:55:17.024  5633  5679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 06:55:17.024  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 06:55:17.024  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 06:55:17.025  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 06:55:17.023  5851  5851 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[35068]" dev="sockfs" ino=35068 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 06:55:17.026  5851  5851 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35068]" dev="sockfs" ino=35068 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 06:55:17.026  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 06:55:17.026  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 06:55:17.026  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 06:55:17.026  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 06:55:17.026  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 06:55:17.026  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 06:55:17.026  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 06:55:17.027  5633  5941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 06:55:17.027  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:55:17.028  5840  5880 D BtGatt.GattService: stopScan() - queue size =0
09-27 06:55:17.029  5840  5850 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 06:55:17.029  5633  5941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 06:55:17.029  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 06:55:17.029  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-27 06:55:17.030  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 06:55:17.030  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 06:55:17.030  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 06:55:17.032  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 06:55:17.034  5633  5679 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 06:55:17.036  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 06:55:17.036  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 06:55:17.036  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-27 06:55:17.036  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:55:17.036  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 06:55:17.036  5633  5679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 06:55:17.037  5633  5679 D BluetoothAdapter: STATE_ON
,09-27 06:55:17.040  5840  5880 D BtGatt.GattService: registerClient() - UUID=4c69def5-eac3-4e16-8bba-a48950f661f3
,09-27 06:55:17.040  5840  5856 D BtGatt.GattService: onClientRegistered() - UUID=4c69def5-eac3-4e16-8bba-a48950f661f3, clientIf=5
09-27 06:55:17.041  5633  5643 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 06:55:17.042  5840  5858 D BtGatt.AdvertiseManager: message : 0
,09-27 06:55:17.044  5840  5858 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 06:55:17.046  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,09-27 06:55:17.046  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:17.046  5840  5856 D BtGatt.GattService: current time is 232357507285
09-27 06:55:17.047  5840  5856 D BtGatt.GattService: Batch record : [-57, 38, 45, -35, 20, 127, 1, -128, -71, 39, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, -46, -4, -117, 6, 105, -37, 1, -128, -71, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -77, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -77, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -77, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -73, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 57, -8, 54, 105, 113, 117, 1, -128, -61, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, 57, -8, 54, 105, 113, 117, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0]
09-27 06:55:17.048  5840  5859 D BtGatt.ScanManager: handling starting scan
09-27 06:55:17.048  5840  5856 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-27 06:55:17.050  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-27 06:55:17.050  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 06:55:17.050  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-27 06:55:17.050  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 06:55:17.050  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 06:55:17.051  5840  5856 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 06:55:17.051  5840  5856 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
09-27 06:55:17.051  5840  5856 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
,09-27 06:55:17.062  5840  5856 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 06:55:17.067  5840  5856 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-27 06:55:17.067  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 06:55:17.067  5840  5859 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 06:55:17.072  5840  5856 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 06:55:17.072  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 06:55:17.073  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 06:55:17.074  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 06:55:17.075  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-27 06:55:17.075  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:55:17.075  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 06:55:17.075  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 06:55:17.075  5633  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 06:55:17.076  5633  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 06:55:17.076  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-27 06:55:17.078  5840  5856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 06:55:17.078  5633  5633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 06:55:17.078  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 06:55:17.078  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 06:55:17.078  5840  5859 D BtGatt.ScanManager: Starting BLE batch scan
09-27 06:55:17.078  5840  5859 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 06:55:17.087  5840  5856 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 06:55:17.088  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:17.093  5840  5856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 06:55:17.093  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:17.099  5840  5856 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-27 06:55:17.099  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 06:55:17.099  5840  5859 D BtGatt.ScanManager: stopping BLe Batch
,09-27 06:55:17.104  5840  5856 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 06:55:17.104  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 06:55:17.104  5840  5859 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 06:55:17.109  5840  5856 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-27 06:55:17.109  5840  5856 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 06:55:17.437   933  3000 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 15 -> obsolete
,09-27 06:55:17.579  5633  5633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 06:55:17.579  5633  5633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 06:55:17.579  5633  5633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 06:55:17.845   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 06:55:18.274   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 06:55:18.846   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 06:55:20.479   933  3002 D ConnectivityService: handlePromptUnvalidated 101
,09-27 06:55:20.579  5633  5679 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-27 06:55:20.580  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 06:55:20.580  5633  5679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 06:55:20.580  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 06:55:20.580  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 06:55:20.581  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-27 06:55:20.581  5633  5941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 06:55:20.581  5633  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 06:55:20.581  5633  5941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 06:55:20.581  5633  5941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-27 06:55:20.581  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 06:55:20.581  5633  5633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 06:55:20.581  5633  5679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d7c7f9 removed from the list
09-27 06:55:20.582  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 06:55:20.582  5633  5633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 06:55:20.582  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 06:55:20.582  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 06:55:20.582  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 06:55:20.582  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-27 06:55:20.587  5633  5679 D BluetoothAdapter: STATE_ON
09-27 06:55:20.587  5633  5679 D BluetoothLeScanner: could not find callback wrapper
09-27 06:55:20.587  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 06:55:20.587  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 06:55:20.589  5840  5858 D BtGatt.AdvertiseManager: message : 1
09-27 06:55:20.590  5840  5858 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 06:55:20.604  5840  5856 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-27 06:55:20.604  5840  5856 D BtGatt.GattService: Client app is not null!
,09-27 06:55:20.605  5840  5850 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 06:55:20.606  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 06:55:20.607  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 06:55:20.607  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 06:55:20.607  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 06:55:20.607  5633  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 06:55:20.610  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:55:20.610  5633  5679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 06:55:20.610  5633  5679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 06:55:20.611  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 06:55:20.613  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:20.614  5633  5633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 06:55:20.614  5633  5633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 06:55:20.615  5633  5679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364333e removed from the list
09-27 06:55:20.615  5633  5679 D io.jxcore.node.ConnectivityMonitor: stop
09-27 06:55:20.615  5633  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 06:55:20.619  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,09-27 06:55:20.620  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-27 06:55:20.620  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 06:55:20.620  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-27 06:55:20.620  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 06:55:20.620  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-27 06:55:20.621  5633  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 06:55:20.622  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
09-27 06:55:20.624  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
09-27 06:55:20.626  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,09-27 06:55:20.627  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
09-27 06:55:20.628  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,09-27 06:55:20.630  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,09-27 06:55:20.631  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,09-27 06:55:20.632  5633  5679 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
09-27 06:55:20.634  5633  5679 I StreamCopyingThreadTest: Starting test: testRun
09-27 06:55:20.637  5633  5943 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 202, name: My test thread name)
,09-27 06:55:21.115  5633  5633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 06:55:22.575  5633  5943 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 202
,09-27 06:55:22.576  5633  5943 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 202, name: My test thread name)
09-27 06:55:22.576  5633  5943 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 202, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-27 06:55:22.642  5633  5679 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-27 06:55:22.645  5633  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: My test thread name)
,09-27 06:55:22.645  5633  5945 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 204, thread name: My test thread name)
,09-27 06:55:22.645  5633  5945 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-27 06:55:22.649  5633  5679 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-27 06:55:22.650  5633  5679 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 06:55:22.654  5633  5679 I StreamCopyingThreadTest: Starting test: testRunWithException
09-27 06:55:22.657  5633  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 208, name: My test thread name)
09-27 06:55:22.657  5633  5946 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 208, thread name: My test thread name): Test exception.
09-27 06:55:22.658  5633  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 208, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-27 06:55:22.663  5633  5679 I jxcore-log: *Native tests were executed*
09-27 06:55:22.663  5633  5679 I jxcore-log: 
09-27 06:55:22.663  5633  5679 I jxcore-log: Total number of executed tests:  82
09-27 06:55:22.663  5633  5679 I jxcore-log: 
09-27 06:55:22.664  5633  5679 I jxcore-log: Number of passed tests:  82
09-27 06:55:22.664  5633  5679 I jxcore-log: 
09-27 06:55:22.664  5633  5679 I jxcore-log: Number of failed tests:  0
09-27 06:55:22.664  5633  5679 I jxcore-log: 
09-27 06:55:22.665  5633  5679 I jxcore-log: Number of ignored tests:  0
09-27 06:55:22.665  5633  5679 I jxcore-log: 
09-27 06:55:22.666  5633  5679 I jxcore-log: Total duration:  23506
09-27 06:55:22.666  5633  5679 I jxcore-log: 
09-27 06:55:22.667  5633  5679 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-27 06:55:22.667  5633  5679 I jxcore-log: 
09-27 06:55:22.674  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 06:55:22.674  5633  5679 I jxcore-log: 
09-27 06:55:22.680  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 06:55:22.680  5633  5679 I jxcore-log: 
09-27 06:55:22.682  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 06:55:22.682  5633  5679 I jxcore-log: 
09-27 06:55:22.684  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 06:55:22.684  5633  5679 I jxcore-log: 
09-27 06:55:22.685  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 06:55:22.685  5633  5679 I jxcore-log: 
09-27 06:55:22.688  5633  5633 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-27 06:55:22.688  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 06:55:22.688  5633  5679 I jxcore-log: 
09-27 06:55:22.691  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 06:55:22.691  5633  5679 I jxcore-log: 
09-27 06:55:22.694  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.694  5633  5679 I jxcore-log: 
09-27 06:55:22.695  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 06:55:22.695  5633  5679 I jxcore-log: 
09-27 06:55:22.696  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 06:55:22.696  5633  5679 I jxcore-log: 
09-27 06:55:22.697  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 06:55:22.697  5633  5679 I jxcore-log: 
09-27 06:55:22.699  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-27 06:55:22.699  5633  5679 I jxcore-log: 
09-27 06:55:22.700  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.700  5633  5679 I jxcore-log: 
09-27 06:55:22.701  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.701  5633  5679 I jxcore-log: 
09-27 06:55:22.703  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.703  5633  5679 I jxcore-log: 
09-27 06:55:22.704  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.704  5633  5679 I jxcore-log: 
09-27 06:55:22.705  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.705  5633  5679 I jxcore-log: 
09-27 06:55:22.705  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.705  5633  5679 I jxcore-log: 
,09-27 06:55:22.706  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.706  5633  5679 I jxcore-log: 
09-27 06:55:22.707  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.707  5633  5679 I jxcore-log: 
09-27 06:55:22.708  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.708  5633  5679 I jxcore-log: 
09-27 06:55:22.709  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.709  5633  5679 I jxcore-log: 
09-27 06:55:22.710  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.710  5633  5679 I jxcore-log: 
09-27 06:55:22.711  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.711  5633  5679 I jxcore-log: 
09-27 06:55:22.712  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.712  5633  5679 I jxcore-log: 
09-27 06:55:22.713  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.713  5633  5679 I jxcore-log: 
09-27 06:55:22.714  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.714  5633  5679 I jxcore-log: 
09-27 06:55:22.715  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 06:55:22.715  5633  5679 I jxcore-log: 
09-27 06:55:22.715  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 06:55:22.715  5633  5679 I jxcore-log: 
09-27 06:55:22.717  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 06:55:22.717  5633  5679 I jxcore-log: 
09-27 06:55:22.717  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.717  5633  5679 I jxcore-log: 
09-27 06:55:22.718  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.718  5633  5679 I jxcore-log: 
09-27 06:55:22.719  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.719  5633  5679 I jxcore-log: 
09-27 06:55:22.720  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 06:55:22.720  5633  5679 I jxcore-log: 
09-27 06:55:22.721  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 06:55:22.721  5633  5679 I jxcore-log: 
09-27 06:55:22.722  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 06:55:22.722  5633  5679 I jxcore-log: 
09-27 06:55:22.723  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 06:55:22.723  5633  5679 I jxcore-log: 
09-27 06:55:22.724  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 06:55:22.724  5633  5679 I jxcore-log: 
09-27 06:55:22.725  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-27 06:55:22.725  5633  5679 I jxcore-log: 
09-27 06:55:22.725  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 06:55:22.725  5633  5679 I jxcore-log: 
09-27 06:55:22.726  5633  5679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-27 06:55:22.726  5633  5679 I jxcore-log: 
,09-27 06:55:23.226  5947  5947 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-27 06:55:23.233  5947  5947 D AndroidRuntime: CheckJNI is OFF
,09-27 06:55:23.264  5947  5947 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-27 06:55:23.298  5947  5947 I Radio-JNI: register_android_hardware_Radio DONE
,09-27 06:55:23.314  5947  5947 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-27 06:55:23.321   933   946 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-27 06:55:23.321   933   946 I ActivityManager: Killing 5633:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-27 06:55:23.368   933  3173 D GraphicsStats: Buffer count: 2
,09-27 06:55:23.368   933  3183 I WindowState: WIN DEATH: Window{d2c4819 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-27 06:55:23.368   933  3001 D WifiService: Client connection lost with reason: 4
,09-27 06:55:23.445   933  3000 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,09-27 06:55:23.467   933   946 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-27 06:55:23.467   933   946 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-27 06:55:23.468   933   956 I art     : Starting a blocking GC Explicit
09-27 06:55:23.468   933   946 E ActivityManager: Failure starting process com.test.thalitest
09-27 06:55:23.468   933   946 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-27 06:55:23.468   933   946 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:23.468   933   946 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:23.468   933   946 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 06:55:23.468   933   946 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-27 06:55:23.471   933   946 I ActivityManager:   Force finishing activity ActivityRecord{1b79e32 u0 com.test.thalitest/.MainActivity t2}
,09-27 06:55:23.477   933  3889 W ActivityManager: Spurious death for ProcessRecord{4807f90 0:com.test.thalitest/u0a77}, curProc for 5633: null
,09-27 06:55:23.483   933   951 W WindowManager: Attempted to add application window with unknown token Token{a0dc783 ActivityRecord{1b79e32 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-27 06:55:23.483   933   951 W WindowManager: Token{a0dc783 ActivityRecord{1b79e32 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{a0dc783 ActivityRecord{1b79e32 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-27 06:55:23.483   933   951 W WindowManager: view not successfully added to wm, removing view
09-27 06:55:23.484   933   951 W WindowManager: Exception when adding starting window
09-27 06:55:23.484   933   951 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{75b90cb V.E...... R.....ID 0,0-0,0} not attached to window manager
09-27 06:55:23.484   933   951 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-27 06:55:23.484   933   951 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-27 06:55:23.484   933   951 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-27 06:55:23.484   933   951 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-27 06:55:23.484   933   951 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-27 06:55:23.484   933   951 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:23.484   933   951 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:23.484   933   951 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 06:55:23.484   933   951 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-27 06:55:23.556   933   956 I art     : Explicit concurrent mark sweep GC freed 21943(1333KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 2.093ms total 87.575ms
,09-27 06:55:23.578   933   956 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-27 06:55:23.581  5947  5947 I art     : System.exit called, status: 0
09-27 06:55:23.581  5947  5947 I AndroidRuntime: VM exiting with result code 0.
,09-27 06:55:23.586   933   956 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-27 06:55:23.597   933   946 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-27 06:55:23.602  5840  5840 D BluetoothMapAppObserver: onReceive
,09-27 06:55:23.602  5840  5840 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-27 06:55:23.611  3672  3672 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-27 06:55:23.612   933  2989 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-27 06:55:23.617  4107  4215 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-27 06:55:23.634  3672  5959 I Keyboard.Facilitator.DecoderInitializer: run()
,09-27 06:55:23.643  3672  5959 I Decoder : createOrResetDecoder
09-27 06:55:23.650  3424  5961 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-27 06:55:23.662   933   933 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-27 06:55:23.663  3811  3811 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-27 06:55:23.663    17    17 W kworker/2:0: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 06:55:23.671  3605  3605 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-27 06:55:23.672  3605  3605 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-27 06:55:23.666    17    17 W kworker/2:0: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 06:55:23.680    17    17 W kworker/2:0: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 06:55:23.692   933  3977 I ActivityManager: Start proc 5964:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-27 06:55:23.693  3849  3982 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-27 06:55:23.693  3849  3982 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3849
09-27 06:55:23.693  3849  3982 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:23.693  3849  3982 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 06:55:23.696   933  5970 E DropBoxManagerService: Can't write: system_app_crash
09-27 06:55:23.696   933  5970 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 06:55:23.696   933  5970 E DropBoxManagerService: 	... 5 more
,09-27 06:55:23.700   933  3976 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-27 06:55:23.706  3849  3982 I Process : Sending signal. PID: 3849 SIG: 9
,09-27 06:55:23.711  3900  5977 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-27 06:55:23.711  3900  5977 D AccountUtils: Clearing selected account for com.test.thalitest
,09-27 06:55:23.731  3605  3605 I ConfigService: onCreate
,09-27 06:55:23.734  3605  5980 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-27 06:55:23.734  3605  5980 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-27 06:55:23.734  3605  5980 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-27 06:55:23.736  3605  5980 W SQLiteOpenHelper: Opened config.db in read-only mode
09-27 06:55:23.736  3424  3448 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj998B3692D) - 
,09-27 06:55:23.744  3672  5959 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-27 06:55:23.816  3424  3448 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-27 06:55:23.816  3424  3448 E AndroidRuntime: Process: android.process.acore, PID: 3424
09-27 06:55:23.816  3424  3448 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-27 06:55:23.816  3424  3448 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 06:55:23.822  3424  3448 I Process : Sending signal. PID: 3424 SIG: 9
,09-27 06:55:23.830   933  3637 D GraphicsStats: Buffer count: 1
09-27 06:55:23.830   933  3902 I WindowState: WIN DEATH: Window{5344f01 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-27 06:55:23.835   933   944 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3849) has died
,09-27 06:55:23.836   933   944 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-27 06:55:23.846   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 06:55:24.058   384   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
