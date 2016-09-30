#### Test 87339632b75737d_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-30 09:36:55.849   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 09:36:55.850   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-30 09:36:55.875   927  5309 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
09-30 09:36:56.375  5608  5608 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-30 09:36:56.380  5608  5608 D AndroidRuntime: CheckJNI is OFF
09-30 09:36:56.408  5608  5608 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-30 09:36:56.446  5608  5608 I Radio-JNI: register_android_hardware_Radio DONE
09-30 09:36:56.463  5608  5608 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-30 09:36:56.471   927  3153 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-30 09:36:56.520   927  3153 I ActivityManager: Start proc 5617:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-30 09:36:56.533  5608  5608 D AndroidRuntime: Shutting down VM
,09-30 09:36:56.861   927  3724 I WindowManager: Screenshot max retries 4 of Token{e0cef9d ActivityRecord{5fc4e74 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{11ef80c u0 Starting com.test.thalitest} drawState=2
,09-30 09:36:56.931  5617  5617 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-30 09:36:56.965  5617  5617 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-30 09:36:56.991  5617  5617 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 362-381)
,09-30 09:36:56.992  5617  5617 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 09:36:57.012  5617  5617 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d11b4c7}
09-30 09:36:57.012  5617  5617 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-30 09:36:57.013  5617  5617 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-30 09:36:57.018  5617  5617 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-30 09:36:57.019  5617  5617 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-30 09:36:57.055  5617  5617 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-30 09:36:57.069  5617  5617 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-30 09:36:57.069  5617  5617 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-30 09:36:57.069  5617  5617 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-30 09:36:57.069  5617  5617 I Adreno  : Build Date                       : 12/06/15
09-30 09:36:57.069  5617  5617 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-30 09:36:57.069  5617  5617 I Adreno  : Local Branch                     : mybranch17112971
09-30 09:36:57.069  5617  5617 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-30 09:36:57.069  5617  5617 I Adreno  : Remote Branch                    : NONE
09-30 09:36:57.069  5617  5617 I Adreno  : Reconstruct Branch               : NOTHING
,09-30 09:36:57.124   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35d77d3:true
,09-30 09:36:57.151  2552  2552 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14215]" dev="sockfs" ino=14215 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 09:36:57.151  2552  2552 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[14215]" dev="sockfs" ino=14215 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 09:36:57.163  5617  5617 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-30 09:36:57.173  5617  5617 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-30 09:36:57.197   401   401 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32433]" dev="sockfs" ino=32433 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 09:36:57.201  5617  5654 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-30 09:36:57.197   401   401 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32433]" dev="sockfs" ino=32433 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 09:36:57.201  3724  3724 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14227]" dev="sockfs" ino=14227 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 09:36:57.201  3724  3724 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14227]" dev="sockfs" ino=14227 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 09:36:57.209  5617  5641 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-30 09:36:57.233  5617  5654 I OpenGLRenderer: Initialized EGL, version 1.4
,09-30 09:36:57.308   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +442ms (total +814ms)
,09-30 09:36:57.333  5617  5617 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5617
,09-30 09:36:57.430  5617  5617 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-30 09:36:57.597  5617  5657 D jxcore_app_log: JniHelper::setJavaVM(0xf4fbc000), pthread_self() = -567015120
,09-30 09:36:57.602  5617  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-30 09:36:57.602  5617  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-30 09:36:57.602  5617  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-30 09:36:57.602  5617  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-30 09:36:57.602  5617  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-30 09:36:57.602  5617  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc19d4c added. We now have 1 listener(s)
,09-30 09:36:57.605  5617  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-30 09:36:57.605  5617  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:36:57.606  5617  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 09:36:57.606  5617  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-30 09:36:57.609  5617  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4882e9b added. We now have 1 listener(s)
09-30 09:36:57.609  5617  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:36:57.615   927  2908 D WifiService: New client listening to asynchronous messages
,09-30 09:36:57.615  5617  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 09:36:57.615  5617  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-30 09:36:57.615  5617  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-30 09:36:57.615  5617  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-30 09:36:57.615  5617  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-30 09:36:57.618  5617  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:36:57.619  5617  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-30 09:36:57.625  5617  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-30 09:36:57.625  5617  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:36:57.625  5617  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:36:57.625  5617  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:36:57.625  5617  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:36:57.625  5617  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:36:57.625  5617  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:36:57.625  5617  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:36:57.625  5617  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:36:57.625  5617  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-30 09:36:57.626  5617  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 09:36:57.626  5617  5657 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-30 09:36:57.628  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:36:57.633  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:36:57.758  5617  5617 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-30 09:36:57.940  5617  5663 W jxcore-log: Initializing JXcore engine
09-30 09:36:57.940  5617  5663 W jxcore-log: JXcore engine is ready
,09-30 09:36:57.955  5617  5626 I art     : Background sticky concurrent mark sweep GC freed 85551(8MB) AllocSpace objects, 18(1892KB) LOS objects, 26% free, 24MB/32MB, paused 1.721ms total 104.211ms
,09-30 09:36:57.961  5663  5663 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11641 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-30 09:36:57.961  5663  5663 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12990]" dev="sockfs" ino=12990 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-30 09:36:57.961  5663  5663 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-30 09:36:57.961  5663  5663 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[28594]" dev="sockfs" ino=28594 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-30 09:36:57.973  5617  5663 W jxcore-log: Starting JXcore engine
,09-30 09:36:58.032  5617  5663 W jxcore-log: Platform android
09-30 09:36:58.032  5617  5663 W jxcore-log: 
,09-30 09:36:58.032  5617  5663 W jxcore-log: Process ARCH arm
09-30 09:36:58.032  5617  5663 W jxcore-log: 
,09-30 09:36:58.131  5617  5663 I jxcore-log: JXcore Cordova bridge is ready!
09-30 09:36:58.131  5617  5663 I jxcore-log: 
,09-30 09:36:58.131  5617  5663 W jxcore-log: JXcore engine is started
,09-30 09:36:58.140  5617  5657 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-30 09:36:58.146  5617  5617 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-30 09:36:58.357   927  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 09:37:03.038   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 09:37:05.851   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:06.067   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 09:37:06.852   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:07.720  5617  5663 I jxcore-log: 2016-09-30 13:37:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 09:37:07.720  5617  5663 I jxcore-log: 
,09-30 09:37:07.722  5617  5663 I jxcore-log: 2016-09-30 13:37:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 09:37:07.722  5617  5663 I jxcore-log: 
,09-30 09:37:07.726  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:37:07.726  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:07.726  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:07.726  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:07.726  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:07.726  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:07.726  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:07.726  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:37:07.727  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:37:07.729  5617  5663 I jxcore-log: 2016-09-30 13:37:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 09:37:07.729  5617  5663 I jxcore-log: 
,09-30 09:37:07.730  5617  5663 I jxcore-log: 2016-09-30 13:37:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 09:37:07.730  5617  5663 I jxcore-log: 
,09-30 09:37:07.853   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:07.973  5617  5663 I jxcore-log: 2016-09-30 13:37:07 - DEBUG UnitTest_app: 'Running unit tests'
09-30 09:37:07.973  5617  5663 I jxcore-log: 
,09-30 09:37:07.974  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:37:07.974  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2820519 added. We now have 2 listener(s)
09-30 09:37:07.975  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:37:07.975  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 09:37:07.975  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:37:07.975  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:37:07.975  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93ff9de added. We now have 2 listener(s)
09-30 09:37:07.975  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:37:07.976  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 09:37:07.978  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:37:07.981  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:37:07.981  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:07.981  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:07.981  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:07.981  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:07.981  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:07.981  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:07.981  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:07.982  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:07.982  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:37:07.983  5617  5663 D executeNativeTests: Running unit tests
,09-30 09:37:07.989  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:07.994  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:08.022  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:37:08.022  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc added. We now have 3 listener(s)
,09-30 09:37:08.022  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:37:08.022  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:37:08.022  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:37:08.023  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:37:08.023  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 added. We now have 3 listener(s)
09-30 09:37:08.023  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:37:08.023  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 09:37:08.024  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:37:08.027  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:37:08.027  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:08.027  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:08.027  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:08.027  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:08.027  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:08.027  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:08.027  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:08.028  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:37:08.028  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:37:08.029  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 09:37:08.029  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 09:37:08.029  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 09:37:08.029  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 09:37:08.030  5617  5663 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-30 09:37:08.030  5617  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 09:37:08.030  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 09:37:08.030  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 09:37:08.030  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 09:37:08.030  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 09:37:08.030  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:08.030  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 09:37:08.031  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:08.031  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:08.031  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:08.031  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:37:08.031  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:08.031  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 09:37:08.031  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc removed from the list
09-30 09:37:08.031  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:08.031  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 removed from the list
09-30 09:37:08.032  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:08.039  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:08.039  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:08.040  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:08.040  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:08.040  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:08.040  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:08.040  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:08.041  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:08.041  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:08.041  5617  5663 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-30 09:37:08.042  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:08.042  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:08.042  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:08.042  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:08.042  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:08.042  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:08.042  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:08.042  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:08.042  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:08.042  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:08.042  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:08.042  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:08.042  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:08.042  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:08.042  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:08.043  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:08.043  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:08.043  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:08.043  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 09:37:08.045  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 09:37:08.046  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:08.046  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:08.046  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 09:37:08.046  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:08.046  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:08.046  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:08.046  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:08.046  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:08.046  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:08.046  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:08.046  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 09:37:08.046  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:08.047  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:08.047  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:08.047  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:08.047  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:08.047  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:08.047  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:08.047  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:08.047  5617  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 09:37:08.048  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:37:08.051  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:37:08.051  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:08.051  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:08.051  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:08.051  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:08.051  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:08.051  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:08.051  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:37:08.051  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:08.051  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:37:08.052  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:37:08.052  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 09:37:08.052  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 09:37:08.052  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:37:08.052  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 09:37:08.054  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 09:37:08.054  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 09:37:08.055  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:08.058  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:08.058  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 09:37:08.059  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 09:37:08.060  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 09:37:08.061  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-30 09:37:08.062  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-30 09:37:08.062  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 09:37:08.062  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 09:37:08.062  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 09:37:08.062  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 09:37:08.062  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 09:37:08.064  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:37:08.068  4569  4584 D BtGatt.GattService: registerClient() - UUID=bb5b326c-4b6e-46cc-a612-92f30223f687
09-30 09:37:08.068  4569  4630 D BtGatt.GattService: onClientRegistered() - UUID=bb5b326c-4b6e-46cc-a612-92f30223f687, clientIf=5
09-30 09:37:08.070  5617  5627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 09:37:08.071  4569  4583 D BtGatt.GattService: start scan with filters
09-30 09:37:08.075  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 09:37:08.075  4569  4635 D BtGatt.ScanManager: handling starting scan
09-30 09:37:08.075  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 09:37:08.075  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:37:08.075  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 09:37:08.076  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 09:37:08.076  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 09:37:08.076  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 09:37:08.077  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:37:08.077  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 09:37:08.077  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:37:08.077  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 09:37:08.079  5617  5663 I io.jxcore.node.ConnectionHelper: start: OK
09-30 09:37:08.080  4569  4635 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:37:08.087  4569  4630 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 09:37:08.088  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:08.088  4569  4635 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 09:37:08.095  4569  4630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 09:37:08.095  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:08.095  4569  4635 D BtGatt.ScanManager: Starting BLE batch scan
09-30 09:37:08.095  4569  4635 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 09:37:08.107  4569  4630 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 09:37:08.107  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:08.114  4569  4630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 09:37:08.114  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:37:08.579  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-30 09:37:08.580  5617  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:37:08.580  5617  5617 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 09:37:08.854   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:09.095   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 09:37:09.856   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:10.856   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 09:37:13.083  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:13.084  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:13.084  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 09:37:13.084  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:13.084  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 09:37:13.084  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:13.084  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 09:37:13.084  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 09:37:13.084  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 09:37:13.084  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 09:37:13.085  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 09:37:13.085  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 09:37:13.086  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:37:13.087  4569  4791 D BtGatt.GattService: stopScan() - queue size =1
09-30 09:37:13.088  4569  4789 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 09:37:13.090  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 09:37:13.090  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 09:37:13.090  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-30 09:37:13.090  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:37:13.090  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 09:37:13.090  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 09:37:13.090  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 09:37:13.091  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 09:37:13.093  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:37:13.094  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 09:37:13.094  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 09:37:13.094  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 09:37:13.094  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 09:37:13.095  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:37:13.095  4569  4569 D BtGatt.ScanManager: awakened up at time 236486
09-30 09:37:13.097  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:13.098  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:13.098  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:37:13.098  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:37:13.098  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:13.098  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:13.098  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:13.098  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:37:13.098  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:13.098  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:13.098  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:13.098  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:37:13.104  4569  4630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 09:37:13.104  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:13.105  4569  4635 D BtGatt.ScanManager: stopping BLe Batch
,09-30 09:37:13.116  4569  4630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 09:37:13.116  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:13.116  4569  4635 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 09:37:13.141  4569  4630 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-30 09:37:13.141  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:13.141  4569  4630 D BtGatt.GattService: current time is 236532009497
09-30 09:37:13.142  4569  4630 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -73, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -71, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -80, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -76, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -76, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -78, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-30 09:37:13.144  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 09:37:13.146  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 09:37:13.147  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 09:37:13.147  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-30 09:37:13.147  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 09:37:13.148  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-30 09:37:13.599  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 09:37:15.140   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 09:37:15.858   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:16.859   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:17.860   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:18.100  5617  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 09:37:18.106  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:37:18.116  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:37:18.116  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:18.116  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:18.116  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:18.116  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:18.116  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:18.116  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:18.116  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:37:18.121  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:37:18.122  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:37:18.122  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:37:18.122  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 09:37:18.122  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-30 09:37:18.122  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:37:18.122  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 09:37:18.127  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:18.130  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 09:37:18.130  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 09:37:18.132  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:18.138  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 09:37:18.140  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-30 09:37:18.140  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 09:37:18.146  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 09:37:18.146  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 09:37:18.146  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 09:37:18.147  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 09:37:18.147  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 09:37:18.148  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:37:18.152  4569  4583 D BtGatt.GattService: registerClient() - UUID=cab69901-e390-4ad5-ac43-f71d8661b314
09-30 09:37:18.153  4569  4630 D BtGatt.GattService: onClientRegistered() - UUID=cab69901-e390-4ad5-ac43-f71d8661b314, clientIf=5
,09-30 09:37:18.153  5617  5627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 09:37:18.154  4569  4800 D BtGatt.GattService: start scan with filters
,09-30 09:37:18.158  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 09:37:18.158  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 09:37:18.158  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:37:18.158  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 09:37:18.159  4569  4635 D BtGatt.ScanManager: handling starting scan
09-30 09:37:18.159  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 09:37:18.159  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-30 09:37:18.159  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 09:37:18.163  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:37:18.163  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 09:37:18.163  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:37:18.165  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 09:37:18.169  4569  4630 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 09:37:18.169  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:18.169  4569  4635 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 09:37:18.170  5617  5663 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 09:37:18.174  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 09:37:18.174  5617  5663 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 09:37:18.174  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:18.174  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 09:37:18.174  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:18.174  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 09:37:18.174  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:18.174  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 09:37:18.174  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 09:37:18.175  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 09:37:18.175  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 09:37:18.175  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 09:37:18.175  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 09:37:18.178  4569  4630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 09:37:18.178  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:18.178  4569  4635 D BtGatt.ScanManager: Starting BLE batch scan
09-30 09:37:18.178  4569  4635 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 09:37:18.178  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:37:18.179  4569  4789 D BtGatt.GattService: stopScan() - queue size =1
09-30 09:37:18.181  4569  4584 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 09:37:18.181  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 09:37:18.181  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 09:37:18.181  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 09:37:18.181  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:37:18.181  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 09:37:18.181  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 09:37:18.181  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 09:37:18.182  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 09:37:18.183  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:37:18.183  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 09:37:18.183  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 09:37:18.184  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 09:37:18.184  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 09:37:18.192  4569  4630 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 09:37:18.192  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:18.192  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 09:37:18.194  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:18.194  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:37:18.194  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:18.194  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 09:37:18.194  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:37:18.195  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:37:18.195  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:18.195  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:18.195  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:18.195  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:18.195  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:18.195  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:18.195  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:18.195  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:18.197  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:18.197  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:37:18.197  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:18.197  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:18.198  5617  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 09:37:18.200  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:37:18.200  4569  4630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 09:37:18.200  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:37:18.205  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:37:18.205  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:18.205  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:18.205  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:18.205  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:18.205  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:18.205  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:18.205  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:37:18.207  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:18.207  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:37:18.207  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:37:18.207  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-30 09:37:18.207  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 09:37:18.207  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:37:18.207  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 09:37:18.208  4569  4630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 09:37:18.208  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:18.209  4569  4635 D BtGatt.ScanManager: stopping BLe Batch
09-30 09:37:18.210  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 09:37:18.210  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 09:37:18.211  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:18.214  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:18.214  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 09:37:18.214  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 09:37:18.214  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 09:37:18.216  4569  4630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 09:37:18.216  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:18.216  4569  4635 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 09:37:18.219  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 09:37:18.219  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-30 09:37:18.219  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 09:37:18.219  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 09:37:18.219  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 09:37:18.220  5617  5663 D BluetoothAdapter: STATE_ON
,09-30 09:37:18.222  4569  4791 D BtGatt.GattService: registerClient() - UUID=0a453009-e52e-4ee8-89a2-00fe025dc46e
09-30 09:37:18.222  4569  4630 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 09:37:18.222  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:18.222  4569  4630 D BtGatt.GattService: onClientRegistered() - UUID=0a453009-e52e-4ee8-89a2-00fe025dc46e, clientIf=5
,09-30 09:37:18.223  5617  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 09:37:18.223  4569  4789 D BtGatt.GattService: start scan with filters
,09-30 09:37:18.226  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 09:37:18.226  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 09:37:18.226  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:37:18.226  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 09:37:18.226  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 09:37:18.226  4569  4635 D BtGatt.ScanManager: handling starting scan
09-30 09:37:18.226  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 09:37:18.226  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 09:37:18.229  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:37:18.229  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 09:37:18.229  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:37:18.230  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 09:37:18.232  4569  4630 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 09:37:18.233  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:37:18.233  5617  5663 I io.jxcore.node.ConnectionHelper: start: OK
09-30 09:37:18.233  4569  4635 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 09:37:18.238  4569  4630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 09:37:18.238  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:18.239  4569  4635 D BtGatt.ScanManager: Starting BLE batch scan
09-30 09:37:18.239  4569  4635 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 09:37:18.248  4569  4630 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 09:37:18.248  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:37:18.254  4569  4630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 09:37:18.254  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:37:18.730  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-30 09:37:18.730  5617  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 09:37:18.730  5617  5617 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 09:37:18.861   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:19.862   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:20.862   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 09:37:23.233  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 09:37:23.233  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:23.234  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 09:37:23.234  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:23.234  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 09:37:23.234  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:23.234  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 09:37:23.234  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 09:37:23.234  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 09:37:23.235  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 09:37:23.235  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-30 09:37:23.235  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 09:37:23.237  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:37:23.238  4569  4584 D BtGatt.GattService: stopScan() - queue size =1
09-30 09:37:23.240  4569  4789 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 09:37:23.241  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 09:37:23.241  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-30 09:37:23.241  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 09:37:23.242  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:37:23.242  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 09:37:23.242  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 09:37:23.242  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 09:37:23.242  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 09:37:23.245  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:37:23.245  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 09:37:23.245  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 09:37:23.245  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 09:37:23.246  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 09:37:23.247  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:37:23.248  4569  4569 D BtGatt.ScanManager: awakened up at time 246639
09-30 09:37:23.250  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:37:23.250  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:37:23.251  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 09:37:23.259  4569  4630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 09:37:23.259  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:37:23.261  4569  4635 D BtGatt.ScanManager: stopping BLe Batch
,09-30 09:37:23.269  4569  4630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 09:37:23.269  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:23.269  4569  4635 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 09:37:23.287  4569  4630 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-30 09:37:23.287  4569  4630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:37:23.287  4569  4630 D BtGatt.GattService: current time is 246677356384
09-30 09:37:23.287  4569  4630 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -74, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -81, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -77, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -76, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -72, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -80, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 09:37:23.287  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-30 09:37:23.288  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 09:37:23.288  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 09:37:23.288  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 09:37:23.288  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 09:37:23.288  4569  4630 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-30 09:37:23.752  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-30 09:37:23.752  5617  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 09:37:23.753  5617  5617 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 09:37:27.266   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 09:37:28.251  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 09:37:28.252  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.252  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:28.252  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.252  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:28.252  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:37:28.252  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.253  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.253  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.253  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:28.253  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.254  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.255  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.255  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:28.258  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 09:37:28.258  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:37:28.258  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.259  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.260  5617  5663 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-30 09:37:28.262  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 09:37:28.262  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.262  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 09:37:28.262  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.263  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.263  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:28.263  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.263  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.263  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.263  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:28.264  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.264  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.264  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.264  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.264  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.266  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:28.267  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:37:28.267  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.267  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.269  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 09:37:28.270  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:28.270  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 09:37:28.270  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:28.270  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.270  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.270  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.271  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 09:37:28.271  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.271  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.271  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.271  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.271  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:28.271  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.272  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.272  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.274  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 09:37:28.274  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:28.274  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.274  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.275  5617  5663 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-30 09:37:28.276  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:28.276  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.276  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 09:37:28.277  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.277  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.277  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.277  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.277  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.277  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.277  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:28.277  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.277  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.277  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.278  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.278  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:28.279  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:28.280  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:28.280  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.280  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:28.281  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-30 09:37:28.281  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:28.281  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.281  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:28.281  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.282  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.282  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.282  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 09:37:28.282  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.282  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.282  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.282  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.282  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.282  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.282  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:28.282  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:28.284  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:28.284  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:28.284  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.285  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.286  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 09:37:28.286  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 09:37:28.286  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-30 09:37:28.286  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 09:37:28.287  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 09:37:28.287  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 09:37:28.287  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 09:37:28.287  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 09:37:28.287  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 09:37:28.287  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:28.287  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.287  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:28.288  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.288  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.288  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.288  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.288  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.288  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.288  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.288  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.288  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:28.288  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.289  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.289  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.291  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:28.291  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:28.291  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.291  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.292  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-30 09:37:28.292  5617  5663 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 09:37:28.292  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-30 09:37:28.299  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-30 09:37:28.299  5617  5663 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-30 09:37:28.299  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 09:37:28.299  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-30 09:37:28.299  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 09:37:28.299  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 09:37:28.299  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 09:37:28.299  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 09:37:28.299  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 09:37:28.299  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 09:37:28.300  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 09:37:28.301  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 09:37:28.301  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 09:37:28.301  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-30 09:37:28.301  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 09:37:28.301  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 09:37:28.301  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 09:37:28.301  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 09:37:28.301  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 09:37:28.302  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 09:37:28.302  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-30 09:37:28.302  5617  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-30 09:37:28.302  5617  5663 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-30 09:37:28.303  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 09:37:28.303  5617  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 09:37:28.303  5617  5663 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-30 09:37:28.303  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 09:37:28.303  5617  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 09:37:28.303  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-30 09:37:28.309  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-30 09:37:28.310  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-30 09:37:28.310  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-30 09:37:28.311  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-30 09:37:28.311  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-30 09:37:28.311  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-30 09:37:28.311  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 09:37:28.311  5617  5663 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-30 09:37:28.311  5617  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
,09-30 09:37:28.312  5617  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-30 09:37:28.312  5617  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-30 09:37:28.312  5617  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-30 09:37:28.312  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:28.312  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.312  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:28.313  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.313  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.313  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.313  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.313  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-30 09:37:28.314  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.315  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.315  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.315  5617  5664 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-30 09:37:28.315  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.315  5617  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-30 09:37:28.315  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.315  5617  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 09:37:28.315  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.315  5617  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-30 09:37:28.315  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:28.315  5617  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-30 09:37:28.315  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.316  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:28.317  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:28.317  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 09:37:28.314  4584  4584 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32472]" dev="sockfs" ino=32472 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 09:37:28.317  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.318  5617  5663 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-30 09:37:28.314  4584  4584 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32472]" dev="sockfs" ino=32472 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 09:37:28.318  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:28.319  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.319  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:28.319  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.319  5617  5664 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
09-30 09:37:28.319  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:28.319  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.319  5617  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-30 09:37:28.319  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.319  5617  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-30 09:37:28.319  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.319  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.319  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.319  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 09:37:28.319  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.319  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.320  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.320  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:28.321  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 09:37:28.321  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:28.322  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.322  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.323  5617  5663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-30 09:37:28.323  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:28.323  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.323  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:28.323  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.323  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:28.323  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.323  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.324  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.324  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.324  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.324  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.324  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.324  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.324  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.324  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:28.326  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:28.326  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:28.326  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.326  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.327  5617  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-30 09:37:28.327  5617  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-30 09:37:28.327  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 09:37:28.327  5617  5663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-30 09:37:28.327  5617  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-30 09:37:28.327  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-30 09:37:28.327  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 09:37:28.327  5617  5663 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-30 09:37:28.328  5617  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 09:37:28.328  5617  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 09:37:28.328  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 09:37:28.328  5617  5663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-30 09:37:28.328  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 09:37:28.328  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:28.328  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:28.328  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.328  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.328  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.328  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.328  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.328  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.329  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:28.329  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.329  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.329  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.329  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.329  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:28.330  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:28.330  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:28.330  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.330  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.331  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:28.331  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.331  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:28.331  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:28.331  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:28.331  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:28.332  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:28.332  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:28.332  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:28.332  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:30.863   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:31.864   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:32.865   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:33.333  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 09:37:33.333  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:33.333  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:33.333  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.334  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.334  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:33.334  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:33.334  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 09:37:33.334  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:33.334  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:33.335  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:33.335  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:33.335  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.335  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:33.335  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:33.336  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.336  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:33.336  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:33.336  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.336  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.336  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.336  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:33.340  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:33.341  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:37:33.341  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.341  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:33.349  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-30 09:37:33.350  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:37:33.352  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-30 09:37:33.356  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-30 09:37:33.356  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,09-30 09:37:33.356  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-30 09:37:33.357  5617  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-30 09:37:33.357  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-30 09:37:33.357  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 09:37:33.357  5617  5617 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-30 09:37:33.359  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:33.359  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-30 09:37:33.359  5617  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 09:37:33.359  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-30 09:37:33.359  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-30 09:37:33.360  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.360  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,09-30 09:37:33.360  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-30 09:37:33.361  5617  5617 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-30 09:37:33.361  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:33.361  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.361  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 09:37:33.361  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 09:37:33.361  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 09:37:33.361  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.361  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.366  5617  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-30 09:37:33.366  5617  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-30 09:37:33.361  4789  4789 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32474]" dev="sockfs" ino=32474 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 09:37:33.361  4789  4789 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32474]" dev="sockfs" ino=32474 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 09:37:33.366  5617  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-30 09:37:33.367  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:37:33.367  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:37:33.367  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:33.367  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:37:33.367  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:33.368  5617  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-30 09:37:33.368  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:33.368  5617  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:33.368  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:33.368  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:37:33.368  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 09:37:33.368  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.368  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.368  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:33.368  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:33.368  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.368  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:33.369  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 09:37:33.369  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.369  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.369  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.369  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.371  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:33.371  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:33.372  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.372  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:33.374  5617  5663 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-30 09:37:33.375  5617  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 09:37:33.375  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 09:37:33.375  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 09:37:33.375  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 09:37:33.375  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:33.375  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:33.375  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 09:37:33.375  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 09:37:33.376  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.376  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.376  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:37:33.376  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:33.376  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.376  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:33.376  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 09:37:33.376  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.378  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.378  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.378  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:33.381  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 09:37:33.381  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:33.381  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.382  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:33.387  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:33.387  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:33.387  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 09:37:33.387  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:33.387  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.387  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.387  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 09:37:33.387  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:33.387  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.387  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:33.387  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:33.387  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.388  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:33.388  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.388  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.389  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:37:33.389  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:33.389  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.389  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:33.390  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:37:33.390  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:37:33.390  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:37:33.391  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:37:33.391  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.391  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.391  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 09:37:33.391  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93342bc not in the list
09-30 09:37:33.391  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:33.391  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
09-30 09:37:33.391  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:37:33.391  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.391  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.391  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:33.391  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:33.392  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 09:37:33.393  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:37:33.393  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 09:37:33.394  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290e245 not in the list
,09-30 09:37:33.395  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-30 09:37:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 09:37:33.395  5617  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-30 09:37:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 09:37:33.395  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-30 09:37:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-30 09:37:33.397  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 09:37:33.397  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-30 09:37:33.399  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-30 09:37:33.399  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 09:37:33.399  5617  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-30 09:37:33.399  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-30 09:37:33.399  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-30 09:37:33.399  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-30 09:37:33.400  5617  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-30 09:37:33.400  5617  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-30 09:37:33.400  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-30 09:37:33.400  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-30 09:37:33.401  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-30 09:37:33.401  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-30 09:37:33.401  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:37:33.402  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@587819f added. We now have 3 listener(s)
09-30 09:37:33.402  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:37:33.404  5617  5663 D BluetoothAdapter: enable(): BT is already enabled..!
,09-30 09:37:33.404   927  3744 D WifiService: setWifiEnabled: true pid=5617, uid=10077
09-30 09:37:33.404   927  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 09:37:33.446  4569  4774 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-30 09:37:33.447  4569  4777 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-30 09:37:33.866   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:33.869  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 09:37:34.867   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:35.220   927  5309 D NetlinkSocketObserver: NeighborEvent{elapsedMs=258610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 09:37:35.868   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 09:37:36.337   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 09:37:38.359   927  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 09:37:38.410  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 09:37:38.411  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42ad2ec added. We now have 4 listener(s)
,09-30 09:37:38.411  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:37:38.425  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 09:37:38.425  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42ad2ec removed from the list
,09-30 09:37:38.425  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 09:37:38.425  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:37:38.426  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:37:38.428  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 09:37:38.428  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@107e6b5 added. We now have 4 listener(s)
,09-30 09:37:38.429  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:37:38.431  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:37:38.431  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@107e6b5 removed from the list
,09-30 09:37:38.432  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 09:37:38.432  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:37:38.432  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:37:38.434  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:37:38.435  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da6914a added. We now have 4 listener(s)
09-30 09:37:38.435  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:37:38.438   927  3744 D WifiService: setWifiEnabled: false pid=5617, uid=10077
09-30 09:37:38.439   927  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 09:37:38.444   927  2907 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 09:37:38.444   927  2907 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 09:37:38.444   927  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 09:37:38.445   927  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 09:37:38.450  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:37:38.453  4569  4626 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 09:37:38.453  4569  4626 D BluetoothAdapterProperties: Setting state to 13
09-30 09:37:38.453  4569  4626 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-30 09:37:38.456  4569  4626 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 09:37:38.458  4569  4626 I BluetoothAdapterState: Entering PendingCommandState
09-30 09:37:38.459  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.459  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:37:38.459  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.459  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.459  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.459  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.459  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:38.459  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:38.459  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:38.459  4569  4569 D BluetoothMapService: onReceive
09-30 09:37:38.459  4569  4569 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 09:37:38.459  4569  4569 D BluetoothMapService: STATE_TURNING_OFF
09-30 09:37:38.460  4569  4569 D BluetoothMapService: MAP Service closeService in
09-30 09:37:38.460  4569  4569 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 09:37:38.460  4569  4569 D ObexServerSockets0: shutdown(block = true)
09-30 09:37:38.462  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.462  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:38.462   927  5310 D DhcpClient: Clearing IP address
09-30 09:37:38.462  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 09:37:38.463   507   926 D CommandListener: Clearing all IP addresses on wlan0
09-30 09:37:38.463  4569  4569 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 09:37:38.464  4569  4802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-30 09:37:38.464  4569  4569 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 09:37:38.465  4569  4803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 09:37:38.467  4569  4569 I BtOppRfcommListener: stopping Accept Thread
09-30 09:37:38.467  4569  5276 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 09:37:38.464  4569  4777 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-30 09:37:38.468  4569  5276 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-30 09:37:38.469   507   926 D CommandListener: Setting iface cfg
09-30 09:37:38.470  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:38.473  3539  5367 V NativeCrypto: Read error: ssl=0x7f735c7b00: I/O error during system call, Connection timed out
09-30 09:37:38.474  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:38.475  3539  5367 V NativeCrypto: SSL shutdown failed: ssl=0x7f735c7b00: I/O error during system call, Broken pipe
,09-30 09:37:38.483   927  3754 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-30 09:37:38.483   927  5308 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-30 09:37:38.484  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.484  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.484  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.484  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.484  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.484  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.484  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:38.484  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:38.484  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:38.485   927  5311 D DhcpClient: Receive thread stopped
09-30 09:37:38.486  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:38.486  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:38.487   927  5308 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-30 09:37:38.488   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-30 09:37:38.488   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 09:37:38.489   927  2909 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-30 09:37:38.492   927   940 I ActivityManager: Start proc 5670:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-30 09:37:38.492  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:38.492  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.492  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.492  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.492  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.492  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.492  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.492  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:38.492  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:38.494  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.494  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 09:37:38.495  4569  4630 D BluetoothAdapterProperties: Scan Mode:20
,09-30 09:37:38.495  4569  4626 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 09:37:38.498   533   533 E Parcel  : Reading a NULL string not supported here.
09-30 09:37:38.498   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 09:37:38.499   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-30 09:37:38.499  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:38.499  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.499  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.499  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.499  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.499  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.499  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.499  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:38.499  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:38.500  4569  4569 D HeadsetService: Received stop request...Stopping profile...
09-30 09:37:38.500  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.501  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:38.503  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:38.503  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.503  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.503  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.503  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.503  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.503  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.503  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:38.503  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:38.506   927   927 D RttService: SCAN_AVAILABLE : 1
09-30 09:37:38.506   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:38.506  4569  4569 D A2dpService: Received stop request...Stopping profile...
09-30 09:37:38.506  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:38.506   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:38.506  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:38.506   927  3017 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 09:37:38.506  4569  4795 D A2dpStateMachine: Exit Disconnected: -1
09-30 09:37:38.507  3727  3760 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:38.507   927  2909 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-30 09:37:38.508   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:38.508  3102  3115 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:38.509  3698  3846 W QCNEJ   : |CORE| network lost: 100
09-30 09:37:38.509   927   927 D BluetoothA2dp: Proxy object disconnected
09-30 09:37:38.509  3698  3846 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 09:37:38.510  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.510  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.510  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.510  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.510  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.510  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.510  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.510  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:38.510  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:38.510  4569  4569 D HidService: Received stop request...Stopping profile...
09-30 09:37:38.510  4569  4569 D HidService: Stopping Bluetooth HidService
09-30 09:37:38.512   927  2907 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-30 09:37:38.513  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.513  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.513  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.513  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.513  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.513  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.513  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.513  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:38.513  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:38.513  4569  4569 D HealthService: Received stop request...Stopping profile...
09-30 09:37:38.514  4569  4569 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:38.514  4569  4569 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:38.514  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:38.515  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 09:37:38.515  4569  4569 D PanService: Received stop request...Stopping profile...
,09-30 09:37:38.519  3102  3102 D HeadsetProfile: Bluetooth service disconnected
,09-30 09:37:38.519   927  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 09:37:38.519  3102  3102 D BluetoothA2dp: Proxy object disconnected
09-30 09:37:38.521  4569  4569 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-30 09:37:38.521  4569  4569 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 09:37:38.521  4569  4774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:38.521  4569  4774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:38.521  4569  4774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 09:37:38.521  4569  4630 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 09:37:38.522  4569  4630 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 09:37:38.522  4569  4569 D BluetoothMapService: Received stop request...Stopping profile...
09-30 09:37:38.522  4569  4569 D BluetoothMapService: stop()
09-30 09:37:38.522  4569  4569 D BluetoothMapAppObserver: deinitObservers()
09-30 09:37:38.523  4569  4569 D BluetoothMapAppObserver: removeReceiver()
09-30 09:37:38.523  3102  3102 D BluetoothInputDevice: Proxy object disconnected
09-30 09:37:38.523  3102  3102 D HidProfile: Bluetooth service disconnected
09-30 09:37:38.524  3102  3102 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 09:37:38.524  3102  3102 D PanProfile: Bluetooth service disconnected
,09-30 09:37:38.526  4569  4569 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:38.526  4569  4569 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:38.526  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:38.526  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:38.526  4569  4569 D SapService: Received stop request...Stopping profile...
09-30 09:37:38.526  4569  4569 V SapService: stop()
09-30 09:37:38.528  4569  4774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:38.529  4569  4774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:38.529  4569  4774 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 09:37:38.529  4569  4774 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-30 09:37:38.529  4569  4774 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 09:37:38.529  4569  4774 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 09:37:38.528  4569  4630 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 09:37:38.529  4569  4569 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:38.529  4569  4569 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:38.529  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:38.529  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:38.529  4569  4569 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 09:37:38.529  4569  4569 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 09:37:38.529  4569  4569 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:38.529  4569  4569 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:38.529  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:38.530  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:38.530  4569  4569 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 09:37:38.530  4569  4569 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 09:37:38.530  4569  4569 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:38.530  4569  4569 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:38.530  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:38.530  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:38.530  4569  4630 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 09:37:38.530  4569  4630 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 09:37:38.530  4569  4569 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 09:37:38.531  4569  4569 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 09:37:38.531   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 09:37:38.534  3102  3102 D BluetoothMap: Proxy object disconnected
09-30 09:37:38.534  3102  3102 D MapProfile: Bluetooth service disconnected
,09-30 09:37:38.537  4569  4569 D BluetoothMapService: MAP Service closeService in
09-30 09:37:38.537  4569  4569 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:38.537  4569  4569 V BluetoothAdapterState: isTurningOn()=false
,09-30 09:37:38.537  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:38.537  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:38.537  4569  4569 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:38.537  4569  4569 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:38.537  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:38.537  4569  4569 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:38.538  4569  4569 D BluetoothMapService: cleanup()
09-30 09:37:38.538  4569  4569 D BluetoothMapService: MAP Service closeService in
,09-30 09:37:38.538  4569  4626 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 09:37:38.538  4569  4626 D BluetoothAdapterProperties: Setting state to 15
09-30 09:37:38.538  4569  4626 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 09:37:38.540  4569  4626 I BluetoothAdapterState: Entering BleOnState
,09-30 09:37:38.542   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-30 09:37:38.542  3102  3115 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 09:37:38.543  3102  5681 D BluetoothMap: onBluetoothStateChange: up=false
09-30 09:37:38.543   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:38.544  3727  3750 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:38.544   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:38.544  3102  3114 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:38.544  3102  3879 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-30 09:37:38.545  3102  3115 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 09:37:38.546  5670  5670 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-30 09:37:38.546   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 09:37:38.547  3102  5681 D BluetoothPan: onBluetoothStateChange on: false
,09-30 09:37:38.549  4569  4626 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 09:37:38.549  4569  4626 D BluetoothAdapterProperties: Setting state to 16
,09-30 09:37:38.549  4569  4626 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-30 09:37:38.550  4569  4626 D BluetoothAdapterProperties: onBleDisable
,09-30 09:37:38.550  4569  4626 I BluetoothAdapterState: Entering PendingCommandState
09-30 09:37:38.550  4569  4627 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 09:37:38.551  4569  4630 D BluetoothAdapterProperties: Scan Mode:20
09-30 09:37:38.551  4569  4774 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-30 09:37:38.551  4569  4774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 09:37:38.553  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.553  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:38.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:38.555  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.555  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.555  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.555  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.555  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:38.555  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.555  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.555  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:38.555  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:38.557  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:38.558  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:38.559  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:38.561   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 09:37:38.561  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:38.561   507   926 D CommandListener: Clearing all IP addresses on wlan0
09-30 09:37:38.561   507   926 D TetherController: Setting IP forward enable = 0
09-30 09:37:38.563   927  2909 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-30 09:37:38.562  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 09:37:38.563   927  2909 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 09:37:38.567   927   944 D Tethering: MasterInitialState.processMessage what=3
09-30 09:37:38.568  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:38.569  5199  5199 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@90f1e23 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-30 09:37:38.570  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:38.572  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:38.576  4982  4995 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 09:37:38.576  4982  4995 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 09:37:38.576  4982  4995 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,09-30 09:37:38.576  4982  4995 E SarControlService: no key has been found,reset the power
09-30 09:37:38.576  4982  5020 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 09:37:38.576  4982  5020 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 09:37:38.576  4982  5020 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 09:37:38.577  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 09:37:38.577  5008  5008 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 09:37:38.578  4982  5020 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 09:37:38.578  4982  5020 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 09:37:38.578  4982  5020 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 09:37:38.579  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 09:37:38.579  5008  5008 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 09:37:38.582  5008  5022 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@65fa8e1 HexData = [00000000ea03000000000000ffffffff]
,09-30 09:37:38.582  5008  5022 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 09:37:38.582  5008  5022 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-30 09:37:38.583  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 09:37:38.583  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 09:37:38.586  5008  5022 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@65fa8e1 HexData = [00000000eb03000000000000ffffffff]
09-30 09:37:38.586  5008  5022 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 09:37:38.586  5008  5022 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-30 09:37:38.587  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 09:37:38.587  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 09:37:38.588  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 09:37:38.590   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b61581b:true
,09-30 09:37:38.602   927  3113 I ActivityManager: Start proc 5697:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-30 09:37:38.614  5670  5670 D LocalBluetoothProfileManager: Adding local MAP profile
,09-30 09:37:38.617   507   926 E Netd    : netlink response contains error (No such file or directory)
,09-30 09:37:38.617  5670  5670 D BluetoothMap: Create BluetoothMap proxy object
09-30 09:37:38.619   927  2909 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-30 09:37:38.619   927  2909 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 09:37:38.620   927  2907 D DhcpClient: doQuit
09-30 09:37:38.620   927  2907 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 09:37:38.621   927  5310 D DhcpClient: onQuitting
,09-30 09:37:38.621  3410  3410 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-30 09:37:38.624  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.624  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.624  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.624  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.624  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:38.624  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.624  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.624  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:38.624  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:38.625  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.625  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 09:37:38.626  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:38.626  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.626  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.626  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.626  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:38.626  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.626  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.626  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:38.626  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:38.626  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.626  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 09:37:38.628  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:38.628  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:38.628  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:38.628  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:38.628  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:38.628  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:38.628  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:38.628  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:38.628  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:38.628  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:38.628  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 09:37:38.632  5670  5670 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-30 09:37:38.633  3410  3410 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-30 09:37:38.636  3410  3410 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-30 09:37:38.639  5697  5697 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-30 09:37:38.645  5670  5670 D DockEventReceiver: finishStartingService: stopping service
,09-30 09:37:38.651   927   937 I ActivityManager: Killing 4946:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-30 09:37:38.658  3410  3410 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 09:37:38.666  3410  3410 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 09:37:38.671  4369  4369 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 09:37:38.671   927  2907 D wifi    : In wifi stop Hal
09-30 09:37:38.671   927  2907 D wifi    : halHandle = 0x7f71771480, mVM = 0x7f8ddcd140, mCls = 0x100a02
09-30 09:37:38.672   927  3409 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 09:37:38.672   927  3409 D WifiHAL : Got a signal to exit!!!
09-30 09:37:38.672   927  3409 I WifiHAL : Exit wifi_event_loop
,09-30 09:37:38.673   927  2907 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 09:37:38.673   927  2907 E WifiHAL : Event processing terminated
09-30 09:37:38.673   927  2907 D wifi    : In wifi cleaned up handler
09-30 09:37:38.673   927  2907 I WifiHAL : Internal cleanup completed
,09-30 09:37:38.674  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:38.675  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:38.677  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:38.680  3665  4135 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 09:37:38.696   927  3409 D wifi    : set interface wlan0 flags (DOWN)
,09-30 09:37:38.696   927  2907 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 09:37:38.756  4569  4630 I bt_hci  : shut_down
,09-30 09:37:38.761  4569  4638 D bt_hwcfg: hw_epilog_process
,09-30 09:37:38.761  4569  4638 I bt_vendor: low_power_mode_cb
,09-30 09:37:38.763  4569  4638 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 09:37:38.763  4569  4638 I bt_vendor: epilog_cb
,09-30 09:37:38.763  4569  4638 I bt_hci  : epilog_finished_callback
,09-30 09:37:38.766  4569  4630 I bt_hci_h4: hal_close
,09-30 09:37:38.767  4569  4630 I bt_userial_vendor: device fd = 54 close
,09-30 09:37:38.874  4569  4627 D bt_stack_manager: event_shut_down_stack finished.
,09-30 09:37:38.875  4569  4626 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 09:37:38.876  4569  4569 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 09:37:38.876  4569  4626 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 09:37:38.877  4569  4569 D BtGatt.GattService: Received stop request...Stopping profile...
,09-30 09:37:38.877  4569  4569 D BtGatt.GattService: stop()
09-30 09:37:38.877  4569  4569 D BtGatt.AdvertiseManager: advertise clients cleared
09-30 09:37:38.878  4569  4569 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:38.878  4569  4569 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:38.878  4569  4569 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:38.878  4569  4569 V BluetoothAdapterState: isBleTurningOff()=true
09-30 09:37:38.878  4569  4626 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 09:37:38.878  4569  4626 D BluetoothAdapterProperties: Setting state to 10
09-30 09:37:38.879  4569  4626 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 09:37:38.879  4569  4626 I BluetoothAdapterState: Entering OffState
,09-30 09:37:38.880   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-30 09:37:38.886  4569  4569 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 09:37:38.886  4569  4569 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 09:37:38.886  4569  4569 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-30 09:37:38.887  4569  4627 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 09:37:38.894  4569  4569 I art     : System.exit called, status: 0
,09-30 09:37:38.894  4569  4569 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 09:37:38.899   927   944 D Tethering: InitialState.processMessage what=4
,09-30 09:37:38.901   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 09:37:38.923  5697  5697 D StrictMode: StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 09:37:38.923  5697  5697 D StrictMode: StrictMode policy violation; ~duration=195 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 09:37:38.923  5697  5697 D StrictMode: StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 09:37:38.923  5697  5697 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 09:37:38.923  5697  5697 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.k.d(PG:583)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 09:37:38.923  5697  5697 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 09:37:38.923  5697  5697 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:37:38.923  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 09:37:38.924  5697  5697 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 09:37:38.924  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:37:38.924  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 09:37:38.929  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 09:37:38.932   927  3724 I ActivityManager: Process com.android.bluetooth (pid 4569) has died
09-30 09:37:38.945   927  3113 I ActivityManager: Start proc 5730:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-30 09:37:38.946  5670  5670 D DockEventReceiver: finishStartingService: stopping service
09-30 09:37:38.947   927  3744 I ActivityManager: Killing 5058:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-30 09:37:39.024  5730  5730 D AdapterServiceConfig: Adding HeadsetService
,09-30 09:37:39.024  5730  5730 D AdapterServiceConfig: Adding A2dpService
09-30 09:37:39.025  5730  5730 D AdapterServiceConfig: Adding HidService
09-30 09:37:39.025  5730  5730 D AdapterServiceConfig: Adding HealthService
09-30 09:37:39.025  5730  5730 D AdapterServiceConfig: Adding PanService
09-30 09:37:39.025  5730  5730 D AdapterServiceConfig: Adding GattService
09-30 09:37:39.025  5730  5730 D AdapterServiceConfig: Adding BluetoothMapService
09-30 09:37:39.025  5730  5730 D AdapterServiceConfig: Adding SapService
,09-30 09:37:39.028   927  3754 I ActivityManager: Killing 5387:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-30 09:37:39.056  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 09:37:39.063  3960  3960 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 09:37:39.067  3960  3960 D SystemUpdateService: onCreate
,09-30 09:37:39.071  3960  3960 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 09:37:39.079  3960  3960 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 09:37:39.084  3960  5336 I iu.UploadsManager: num queued entries: 0
,09-30 09:37:39.085  3960  5336 I iu.UploadsManager: num updated entries: 0
09-30 09:37:39.085  3960  5336 I iu.SyncManager: NEXT; no task
,09-30 09:37:39.087  3960  3960 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-30 09:37:39.089  3960  3960 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 09:37:39.095  3960  5742 I SystemUpdateService: active receiver: enabled
,09-30 09:37:39.101   927  3685 I ActivityManager: Start proc 5744:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-30 09:37:39.106  3960  5742 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 09:37:39.117  3960  5742 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 09:37:39.118  3960  5742 I SystemUpdateService: now status is 0 (complete)
09-30 09:37:39.118  3960  5742 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 09:37:39.118  3960  5742 I SystemUpdateService: file has been verified
09-30 09:37:39.119  3960  5742 I SystemUpdateService: OTA package size = 21989297
,09-30 09:37:39.142  5744  5744 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-30 09:37:39.144  5744  5744 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 09:37:39.152  5744  5744 D SprintDMHelper: simOperator: 
,09-30 09:37:39.152  5744  5744 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 09:37:39.160  3960  5742 I SystemUpdateService: showing system update notification
,09-30 09:37:39.165   927  3153 I ActivityManager: Start proc 5756:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-30 09:37:39.193  3960  3960 D SystemUpdateService: onDestroy
,09-30 09:37:39.195   927  3685 I ActivityManager: Killing 5371:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-30 09:37:39.266  4369  5770 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 09:37:39.273   927  3744 I ActivityManager: Start proc 5771:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-30 09:37:39.277   927  3721 I ActivityManager: Killing 5199:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-30 09:37:39.340  5771  5771 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-30 09:37:39.454  5697  5718 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-30 09:37:39.523   927  3744 I ActivityManager: Killing 4640:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-30 09:37:39.539   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27f0d8a:true
,09-30 09:37:39.566   927  3754 I ActivityManager: Start proc 5785:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-30 09:37:39.600  5785  5785 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-30 09:37:39.605   507   926 D TetherController: Setting IP forward enable = 0
,09-30 09:37:39.608   927  3721 I ActivityManager: Killing 5474:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-30 09:37:43.465   927  3113 D WifiService: setWifiEnabled: true pid=5617, uid=10077
,09-30 09:37:43.465   927  3113 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 09:37:43.473   507   926 D SoftapController: Softap fwReload - Ok
,09-30 09:37:43.477   507   926 D CommandListener: Setting iface cfg
,09-30 09:37:43.478   507   926 D CommandListener: Trying to bring down wlan0
,09-30 09:37:43.479   507   926 D CommandListener: Clearing all IP addresses on wlan0
,09-30 09:37:43.484   927  2907 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 09:37:44.055   927  2907 D wifi    : set interface wlan0 flags (UP)
,09-30 09:37:44.055   927  2907 I WifiHAL : Initializing wifi
09-30 09:37:44.055   927  2907 I WifiHAL : Creating socket
,09-30 09:37:44.059   927  2907 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-30 09:37:44.059   927  2907 D wifi    : Did set static halHandle = 0x7f71771480
09-30 09:37:44.059   927  2907 D wifi    : halHandle = 0x7f71771480, mVM = 0x7f8ddcd140, mCls = 0x10192a
09-30 09:37:44.059   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-30 09:37:44.059   927  2907 D wifi    : array field set
,09-30 09:37:44.059   927  2907 I WifiNative-HAL: interface[0] = wlan0
,09-30 09:37:44.061   927  5810 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547364476032
09-30 09:37:44.061   927  5810 D wifi    : waitForHalEvents called, vm = 0x7f8ddcd140, obj = 0x10192a, env = 0x7f72a83c80
,09-30 09:37:44.132  5811  5811 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 09:37:44.145  5811  5811 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 09:37:44.162   927  2907 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 09:37:44.165  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:44.167  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:44.168  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:44.195  5811  5811 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 09:37:44.195  5811  5811 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 09:37:44.212   927  2907 D WifiConfigStore: Loading config and enabling all networks 
,09-30 09:37:44.213  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:44.213  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:44.213  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:44.213  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:44.213  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:44.213  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:44.213  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:44.213  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:44.213  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:44.213  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:44.213  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:44.215  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:44.215  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:44.215  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:44.215  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:44.215  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:44.215  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:44.215  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:44.215  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:44.215  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:44.215  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:44.215  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:44.217  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 09:37:44.217  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:44.217  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:44.217  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:44.217  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:44.217  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:44.217  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:44.217  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:44.217  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:44.217  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:44.217  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:44.223   927  2907 D WifiConfigStore: loaded 0 passpoint configs
09-30 09:37:44.223   927  2907 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 09:37:44.224   927  2907 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 09:37:44.225   927  2907 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-30 09:37:44.225   927  2907 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 09:37:44.226   927  2907 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 09:37:44.226   927  2907 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 09:37:44.226   927  2907 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-30 09:37:44.228  4369  4369 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 09:37:44.229   927  2907 D WifiNative-HAL: Setting external_sim to 1
09-30 09:37:44.230   927  2907 D wifi    : setting dfs flag to true, 0x7f75727200
09-30 09:37:44.230   927  2907 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 09:37:44.230   927  2907 D wifi    : setting scan oui 0x7f75727200
09-30 09:37:44.230   927  2907 D WifiHAL : Sending mac address OUI
09-30 09:37:44.234   927  2907 E native  : do suspend false
09-30 09:37:44.241   927   927 D RttService: SCAN_AVAILABLE : 3
09-30 09:37:44.241   927  2907 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 09:37:44.241   507   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 09:37:44.241   927  3017 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-30 09:37:44.242   507   926 D CommandListener: Setting iface cfg
09-30 09:37:44.246   927  2906 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
09-30 09:37:44.246   927  2906 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-30 09:37:44.254   927  2906 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 09:37:44.259   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267649 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
09-30 09:37:44.259   927  2906 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 09:37:47.423  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 09:37:47.428  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 09:37:47.434  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 09:37:47.438  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 09:37:47.512   927  2907 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 09:37:47.513   927  2907 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 09:37:47.513   927  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 09:37:47.525   927  2907 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 09:37:47.561   927  2907 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 09:37:47.564  5811  5811 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 09:37:47.988  5811  5811 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 09:37:48.034  5811  5811 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 09:37:48.036  5811  5811 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 09:37:48.045   927  2907 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 09:37:48.046   927  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-30 09:37:48.046   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 09:37:48.061   927  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 09:37:48.075   507   926 D CommandListener: Setting iface cfg
,09-30 09:37:48.080   927  2907 D WifiStateMachine: Start Dhcp Watchdog 2
,09-30 09:37:48.086   927  5817 D DhcpClient: Receive thread started
,09-30 09:37:48.092   927  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-30 09:37:48.092   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-30 09:37:48.092   927  2909 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-30 09:37:48.173   927  2907 E native  : do suspend false
,09-30 09:37:48.188   927  5816 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 09:37:48.220   927  5817 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
09-30 09:37:48.221   927  5816 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-30 09:37:48.224   927  5816 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 09:37:48.242   927  5817 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 09:37:48.243   927  5816 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-30 09:37:48.246   507   926 D CommandListener: Setting iface cfg
,09-30 09:37:48.251   927  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 09:37:48.256   927  5816 D DhcpClient: Scheduling renewal in 86399s
,09-30 09:37:48.269   927  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 09:37:48.271   927  2907 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 09:37:48.272   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-30 09:37:48.274   927  2909 D ConnectivityService: Adding iface wlan0 to network 101
,09-30 09:37:48.278   927  2907 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 09:37:48.324   927  2909 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 09:37:48.324   927  2909 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-30 09:37:48.327   927  2909 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-30 09:37:48.329   927  2909 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-30 09:37:48.331   927  2909 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-30 09:37:48.337   927  2909 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 09:37:48.341   927  2909 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-30 09:37:48.341   927  2909 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-30 09:37:48.341   927  2909 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-30 09:37:48.341   927  2909 D ConnectivityService:    accepting network in place of null
09-30 09:37:48.342   927  2909 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-30 09:37:48.343   927  2907 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 09:37:48.344   927  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 09:37:48.361   927  5815 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271751, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 09:37:48.364   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 09:37:48.383   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 09:37:48.386   927  2909 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 09:37:48.386   927  2909 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 09:37:48.387  3698  3846 W QCNEJ   : |CORE| network available: 101
,09-30 09:37:48.388  3698  3846 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-30 09:37:48.388   927  2909 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-30 09:37:48.388   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-30 09:37:48.393  3698  3846 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-30 09:37:48.393  3698  3846 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 09:37:48.397  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.397  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:48.397  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:48.397  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:48.397  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:48.397  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:48.397  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:48.397  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:48.397  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:48.397  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.397  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:37:48.399  4982  4995 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 09:37:48.401  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.401  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:48.401  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:48.401  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:48.401  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:48.401  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:48.401  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:48.401  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:48.401  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:37:48.401  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.401  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:37:48.402  3960  3960 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 09:37:48.401  4982  4995 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 09:37:48.403  4982  4995 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 09:37:48.403  4982  4995 E SarControlService: no key has been found,reset the power
09-30 09:37:48.404  4982  5020 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 09:37:48.404  4982  5020 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 09:37:48.404  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.404  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:48.404  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:48.404  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:48.404  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:48.404  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:48.404  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:48.404  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:37:48.404  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:37:48.404  4982  5020 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 09:37:48.404  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.404  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:37:48.405  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 09:37:48.405  5008  5008 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 09:37:48.406  4982  5020 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 09:37:48.406  4982  5020 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 09:37:48.406  4982  5020 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-30 09:37:48.407  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-30 09:37:48.407  5008  5008 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-30 09:37:48.411  3960  3960 D SystemUpdateService: onCreate
,09-30 09:37:48.412  5008  5022 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@65fa8e1 HexData = [00000000ec03000000000000ffffffff]
09-30 09:37:48.412  5008  5022 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 09:37:48.412  5008  5022 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-30 09:37:48.412  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 09:37:48.413  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 09:37:48.414  5008  5022 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@65fa8e1 HexData = [00000000ed03000000000000ffffffff]
09-30 09:37:48.414  5008  5022 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 09:37:48.414  5008  5022 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,09-30 09:37:48.415  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 09:37:48.415  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 09:37:48.417  3960  3960 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 09:37:48.428  3960  3960 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 09:37:48.434  3960  5336 I iu.UploadsManager: num queued entries: 0
,09-30 09:37:48.434  3960  5336 I iu.UploadsManager: num updated entries: 0
09-30 09:37:48.435  3960  5336 I iu.SyncManager: NEXT; no task
09-30 09:37:48.435   927  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-30 09:37:48.437  3960  5827 I SystemUpdateService: active receiver: enabled
,09-30 09:37:48.440  3960  3960 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 09:37:48.441  3960  3960 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 09:37:48.443  5744  5744 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 09:37:48.446  5744  5744 D SprintDMHelper: simOperator: 
09-30 09:37:48.446  5744  5744 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 09:37:48.468  3960  5827 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 09:37:48.470   927  3685 D WifiService: setWifiEnabled: false pid=5617, uid=10077
09-30 09:37:48.470   927  3685 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 09:37:48.471   927  2907 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-30 09:37:48.471   927  2907 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 09:37:48.471   927  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 09:37:48.471   927  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 09:37:48.481   927  5816 D DhcpClient: Clearing IP address
,09-30 09:37:48.481   507   926 D CommandListener: Clearing all IP addresses on wlan0
,09-30 09:37:48.483   507   926 D CommandListener: Setting iface cfg
,09-30 09:37:48.484   927  5817 D DhcpClient: Receive thread stopped
09-30 09:37:48.488  3960  5827 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 09:37:48.488  3960  5827 I SystemUpdateService: now status is 0 (complete)
,09-30 09:37:48.488  3960  5827 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 09:37:48.488  3960  5827 I SystemUpdateService: file has been verified
,09-30 09:37:48.488  3960  5827 I SystemUpdateService: OTA package size = 21989297
09-30 09:37:48.490   927  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-30 09:37:48.490   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-30 09:37:48.496   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-30 09:37:48.496   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-30 09:37:48.496  3960  5827 I SystemUpdateService: showing system update notification
,09-30 09:37:48.499   927   927 D RttService: SCAN_AVAILABLE : 1
09-30 09:37:48.499   533   533 E Parcel  : Reading a NULL string not supported here.
09-30 09:37:48.499   927  3017 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 09:37:48.501   927  2909 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-30 09:37:48.503  3698  3846 W QCNEJ   : |CORE| network lost: 101
,09-30 09:37:48.504  3698  3846 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-30 09:37:48.507   927  2907 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-30 09:37:48.507   927  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 09:37:48.511  3960  3960 D SystemUpdateService: onDestroy
,09-30 09:37:48.524   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 09:37:48.543   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 09:37:48.544   507   926 D CommandListener: Clearing all IP addresses on wlan0
09-30 09:37:48.544   927  2909 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 09:37:48.544   927  2909 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 09:37:48.548   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-30 09:37:48.548  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.548  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:48.548  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:48.548  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:48.548  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:48.548  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:48.548  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:48.548  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:48.548  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:48.548  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.548  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:48.549   927  2907 D DhcpClient: doQuit
09-30 09:37:48.549   927  2907 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 09:37:48.549   927  5816 D DhcpClient: onQuitting
09-30 09:37:48.549  5811  5811 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 09:37:48.550  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.550  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:48.550  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:48.550  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:48.550  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:37:48.550  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:48.550  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:48.550  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:48.550  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:48.550  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.550  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:48.552  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.552  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:48.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:48.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:48.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:48.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:48.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:48.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:48.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:48.552  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.552  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:48.553  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.553  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:48.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:48.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:48.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:48.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:48.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:48.553  5617  5,617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:48.553  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:48.553  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.554  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:48.556  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.556  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:48.556  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:48.556  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:48.556  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:48.556  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:48.556  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:48.556  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:48.556  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:48.556  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:48.556  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:48.557  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:48.559  3960  3960 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 09:37:48.561  4982  4995 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 09:37:48.561  4982  4995 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 09:37:48.561  4982  4995 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 09:37:48.561  4982  4995 E SarControlService: no key has been found,reset the power
09-30 09:37:48.561  4982  5020 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 09:37:48.561  4982  5020 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 09:37:48.561  4982  5020 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 09:37:48.562  5811  5811 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 09:37:48.562  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 09:37:48.562  5008  5008 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 09:37:48.563  4982  5020 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 09:37:48.563  4982  5020 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 09:37:48.563  4982  5020 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 09:37:48.564  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 09:37:48.564  5008  5008 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 09:37:48.566  5811  5811 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-30 09:37:48.567  3960  3960 D SystemUpdateService: onCreate
09-30 09:37:48.567  5008  5022 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@65fa8e1 HexData = [00000000ee03000000000000ffffffff]
09-30 09:37:48.568  5008  5022 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 09:37:48.568  5008  5022 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-30 09:37:48.568  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 09:37:48.568  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 09:37:48.570  5008  5022 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@65fa8e1 HexData = [00000000ef03000000000000ffffffff]
09-30 09:37:48.571  5008  5022 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 09:37:48.571  5008  5022 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-30 09:37:48.571  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 09:37:48.571  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 09:37:48.572  3960  3960 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 09:37:48.575  3960  5844 I SystemUpdateService: active receiver: enabled
09-30 09:37:48.580  3960  3960 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-30 09:37:48.584  3960  5336 I iu.UploadsManager: num queued entries: 0
09-30 09:37:48.585  3960  5336 I iu.UploadsManager: num updated entries: 0
09-30 09:37:48.585  3960  5336 I iu.SyncManager: NEXT; no task
09-30 09:37:48.586  3960  5844 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 09:37:48.588  3960  3960 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-30 09:37:48.589  3960  3960 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 09:37:48.591  5744  5744 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-30 09:37:48.595  5744  5744 D SprintDMHelper: simOperator: 
09-30 09:37:48.595  5744  5744 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-30 09:37:48.602  3960  5844 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-30 09:37:48.602  3960  5844 I SystemUpdateService: now status is 0 (complete)
09-30 09:37:48.603  3960  5844 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 09:37:48.603  3960  5844 I SystemUpdateService: file has been verified
09-30 09:37:48.603  3960  5844 I SystemUpdateService: OTA package size = 21989297
09-30 09:37:48.610  5811  5811 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-30 09:37:48.610  3960  5844 I SystemUpdateService: showing system update notification
09-30 09:37:48.617   507   926 E Netd    : netlink response contains error (No such file or directory)
09-30 09:37:48.618   927  2909 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-30 09:37:48.620  5811  5811 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 09:37:48.629  3960  3960 D SystemUpdateService: onDestroy
,09-30 09:37:48.724   927  2907 D wifi    : In wifi stop Hal
,09-30 09:37:48.724   927  2907 D wifi    : halHandle = 0x7f71771480, mVM = 0x7f8ddcd140, mCls = 0x10192a
09-30 09:37:48.725   927  5810 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 09:37:48.725   927  5810 D WifiHAL : Got a signal to exit!!!
,09-30 09:37:48.725   927  5810 I WifiHAL : Exit wifi_event_loop
,09-30 09:37:48.725   927  2907 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 09:37:48.725   927  2907 E WifiHAL : Event processing terminated
09-30 09:37:48.725   927  2907 D wifi    : In wifi cleaned up handler
09-30 09:37:48.725   927  2907 I WifiHAL : Internal cleanup completed
09-30 09:37:48.726  4369  4369 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 09:37:48.727  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:48.731  3665  4135 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 09:37:48.733  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:48.735  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:48.753   927  5810 D wifi    : set interface wlan0 flags (DOWN)
,09-30 09:37:48.753   927  2907 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 09:37:48.956   927   944 D Tethering: InitialState.processMessage what=4
,09-30 09:37:48.962   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 09:37:49.387   927  2909 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-30 09:37:50.869   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:51.870   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:52.871   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:53.475  4369  5832 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-30 09:37:53.476  4369  5832 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-30 09:37:53.482  4369  5832 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 09:37:53.503   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@164bef0:true
,09-30 09:37:53.504  5730  5730 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 09:37:53.509  5730  5730 I bt_bluedroid: init
,09-30 09:37:53.509  5730  5849 I BluetoothAdapterState: Entering OffState
,09-30 09:37:53.513  5730  5850 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 09:37:53.514  5730  5850 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 09:37:53.514  5730  5850 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 09:37:53.514  5730  5850 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 09:37:53.515  5730  5730 I bt_bluedroid: get_profile_interface socket
,09-30 09:37:53.517  5730  5853 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 09:37:53.518  5730  5730 I bt_bluedroid: get_profile_interface sdp
09-30 09:37:53.519  5730  5853 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 09:37:53.525  5730  5741 I bt_bluedroid: config_hci_snoop_log
,09-30 09:37:53.527   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 09:37:53.532  5730  5849 D BluetoothAdapterState: Current state: OFF, message: 0
,09-30 09:37:53.532  5730  5849 D BluetoothAdapterProperties: Setting state to 14
09-30 09:37:53.533  5730  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 09:37:53.535  5730  5849 D BluetoothBondStateMachine: make
,09-30 09:37:53.538  5730  5854 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 09:37:53.543  5730  5849 I BluetoothAdapterState: Entering PendingCommandState
,09-30 09:37:53.544  5730  5730 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 09:37:53.548  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:37:53.549  5730  5730 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 09:37:53.549  5730  5730 D BtGatt.GattService: Received start request. Starting profile...
,09-30 09:37:53.550  5730  5730 D BtGatt.GattService: start()
09-30 09:37:53.550  5730  5730 I bt_bluedroid: get_profile_interface gatt
,09-30 09:37:53.551  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:37:53.551  5730  5730 D BtGatt.AdvertiseManager: advertise manager created
,09-30 09:37:53.560  5730  5730 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:53.560  5730  5730 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:53.560  5730  5730 V BluetoothAdapterState: isBleTurningOn()=true
09-30 09:37:53.560  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:53.561  5730  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 09:37:53.563  5730  5849 I bt_bluedroid: bt_bluedroid
,09-30 09:37:53.563  5730  5850 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 09:37:53.564  5730  5850 I bt_hci  : start_up
,09-30 09:37:53.572  5730  5850 I bt_vendor: alloc value 0xf3bf8871
,09-30 09:37:53.573  5730  5850 I bt_vendor: init
09-30 09:37:53.573  5730  5850 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 09:37:53.573  5730  5850 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 09:37:53.686  5730  5850 D bt_hci  : start_up starting async portion
,09-30 09:37:53.687  5730  5857 I bt_hci  : event_finish_startup
09-30 09:37:53.687  5730  5857 I bt_hci_h4: hal_open
09-30 09:37:53.687  5730  5857 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 09:37:53.684  5858  5858 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 09:37:53.690  5730  5857 I bt_userial_vendor: device fd = 54 open
,09-30 09:37:53.706  5730  5857 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 09:37:53.710  5730  5857 D bt_hwcfg: Chipset BCM4358A3
,09-30 09:37:53.710  5730  5857 D bt_hwcfg: Target name = [BCM4358A3]
09-30 09:37:53.711  5730  5857 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 09:37:53.872   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:54.097  5730  5857 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 09:37:54.098  5730  5857 D bt_hwcfg: Settlement delay -- 100 ms
09-30 09:37:54.098  5730  5857 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 09:37:54.233  5730  5857 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 09:37:54.233  5730  5857 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-30 09:37:54.234  5730  5857 I bt_hwcfg: vendor lib fwcfg completed
,09-30 09:37:54.235  5730  5857 I bt_vendor: firmware callback
09-30 09:37:54.235  5730  5857 I bt_hci  : firmware_config_callback
,09-30 09:37:54.243  5730  5860 I bt_btu  : btu_task pending for preload complete event
,09-30 09:37:54.243  5730  5860 I bt_btu_task: Bluetooth chip preload is complete
09-30 09:37:54.243  5730  5860 I bt_btu  : btu_task received preload complete event
,09-30 09:37:54.250  5730  5860 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 09:37:54.251  5730  5860 I         : BTE_InitTraceLevels -- TRC_PAN
,09-30 09:37:54.252  5730  5860 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 09:37:54.252  5730  5860 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 09:37:54.252  5730  5860 I         : BTE_InitTraceLevels -- TRC_SMP
,09-30 09:37:54.252  5730  5860 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 09:37:54.252  5730  5860 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 09:37:54.335  5730  5860 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b76549
09-30 09:37:54.335  5730  5860 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b76549 
,09-30 09:37:54.352  5730  5853 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 09:37:54.353  5730  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 09:37:54.354  5730  5853 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 09:37:54.356  5730  5853 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 09:37:54.359  5730  5853 D BluetoothAdapterProperties: Scan Mode:20
09-30 09:37:54.360  5730  5853 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 09:37:54.360  5730  5853 D bt_hci  : do_postload posting postload work item
,09-30 09:37:54.360  5730  5857 I bt_hci  : event_postload
,09-30 09:37:54.360  5730  5857 I bt_vendor: sco_config_cb
09-30 09:37:54.360  5730  5857 I bt_hci  : sco_config_callback postload finished.
09-30 09:37:54.363  5730  5853 D bt_bte_conf: Device ID record 1 : primary
09-30 09:37:54.363  5730  5853 D bt_bte_conf:   vendorId            = 000f
09-30 09:37:54.363  5730  5853 D bt_bte_conf:   vendorIdSource      = 0001
09-30 09:37:54.364  5730  5853 D bt_bte_conf:   product             = 1200
09-30 09:37:54.364  5730  5853 D bt_bte_conf:   version             = 1436
09-30 09:37:54.364  5730  5853 D bt_bte_conf:   clientExecutableURL = 
09-30 09:37:54.364  5730  5853 D bt_bte_conf:   serviceDescription  = 
09-30 09:37:54.364  5730  5853 D bt_bte_conf:   documentationURL    = 
09-30 09:37:54.364  5730  5853 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 09:37:54.364  5730  5850 D bt_stack_manager: event_start_up_stack finished
09-30 09:37:54.365  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:54.365  5730  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 09:37:54.366  5730  5849 D BluetoothAdapterProperties: Setting state to 15
09-30 09:37:54.366  5730  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 09:37:54.368  5730  5849 I BluetoothAdapterState: Entering BleOnState
,09-30 09:37:54.371  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:54.372  5730  5857 I bt_vendor: low_power_mode_cb
09-30 09:37:54.373  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:54.373  5730  5849 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-30 09:37:54.374  5730  5849 D BluetoothAdapterProperties: Setting state to 11
09-30 09:37:54.374  5730  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-30 09:37:54.378  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:37:54.380  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:54.382  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:54.383  5730  5730 D HeadsetService: Received start request. Starting profile...
09-30 09:37:54.384  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:54.386  5730  5730 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 09:37:54.387  5730  5730 D HeadsetStateMachine: make
,09-30 09:37:54.393  5730  5849 I BluetoothAdapterState: Entering PendingCommandState
,09-30 09:37:54.398  5730  5730 D HeadsetStateMachine: max_hf_connections = 1
,09-30 09:37:54.398  5730  5730 I bt_bluedroid: get_profile_interface handsfree
,09-30 09:37:54.401  5730  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-30 09:37:54.401  5730  5853 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-30 09:37:54.401  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:37:54.402  5730  5730 D A2dpService: Received start request. Starting profile...
09-30 09:37:54.403  5730  5730 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 09:37:54.403  5730  5730 I bt_bluedroid: get_profile_interface avrcp
,09-30 09:37:54.409  5730  5730 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-30 09:37:54.409  5730  5730 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 09:37:54.409  5730  5730 D A2dpStateMachine: make
,09-30 09:37:54.411  5730  5730 I bt_bluedroid: get_profile_interface a2dp
09-30 09:37:54.412  5730  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-30 09:37:54.414  5730  5868 D A2dpStateMachine: Enter Disconnected: -2
09-30 09:37:54.414  5730  5730 I BluetoothHidServiceJni: classInitNative: succeeds
09-30 09:37:54.415  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:37:54.417  5670  5670 D BluetoothInputDevice: Proxy object connected
09-30 09:37:54.417  5670  5670 D HidProfile: Bluetooth service connected
09-30 09:37:54.418  5730  5730 D HidService: Received start request. Starting profile...
,09-30 09:37:54.418  5730  5730 I bt_bluedroid: get_profile_interface hidhost
,09-30 09:37:54.418  5730  5730 D HidService: setHidService(): set to: null
09-30 09:37:54.418  5730  5853 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b5756d
09-30 09:37:54.419  5730  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 09:37:54.419  5730  5730 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 09:37:54.420  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:37:54.421  5730  5730 D HealthService: Received start request. Starting profile...
,09-30 09:37:54.422  5730  5730 I bt_bluedroid: get_profile_interface health
,09-30 09:37:54.423  5730  5730 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-30 09:37:54.424  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:37:54.425  5670  5670 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 09:37:54.425  5730  5730 D PanService: Received start request. Starting profile...
09-30 09:37:54.425  5730  5730 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 09:37:54.425  5730  5730 I bt_bluedroid: get_profile_interface pan
09-30 09:37:54.426  5670  5670 D PanProfile: Bluetooth service connected
09-30 09:37:54.426  5730  5853 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 09:37:54.428  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:37:54.430  5670  5670 D BluetoothMap: Proxy object connected
,09-30 09:37:54.430  5670  5670 D MapProfile: Bluetooth service connected
09-30 09:37:54.430  5670  5670 D BluetoothMap: getConnectedDevices()
09-30 09:37:54.431  5730  5730 D BluetoothMapService: Received start request. Starting profile...
09-30 09:37:54.431  5730  5730 D BluetoothMapService: start()
09-30 09:37:54.434  5730  5730 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 09:37:54.435  5730  5730 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 09:37:54.435  5730  5730 D BluetoothMapAppObserver: createReceiver()
09-30 09:37:54.436  5730  5730 D BluetoothMapAppObserver: initObservers()
09-30 09:37:54.437  5730  5730 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 09:37:54.443  5730  5730 V SapService: SapBinder()
,09-30 09:37:54.443  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:37:54.444  5730  5730 D SapService: Received start request. Starting profile...
,09-30 09:37:54.444  5730  5730 V SapService: start()
09-30 09:37:54.447  5730  5730 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:54.447  5730  5730 V BluetoothAdapterState: isTurningOn()=true
09-30 09:37:54.447  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:54.447  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:54.447  5730  5730 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOn()=true
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:54.448  5730  5866 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOn()=true
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOn()=true
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:54.448  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOn()=true
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:54.448  5730  5730 V BluetoothAdapterState: isTurningOn()=true
09-30 09:37:54.449  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:54.449  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:54.449  5730  5730 V BluetoothAdapterState: isTurningOff()=false
09-30 09:37:54.449  5730  5730 V BluetoothAdapterState: isTurningOn()=true
09-30 09:37:54.450  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:54.450  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:54.450  5730  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 09:37:54.450  5730  5849 D BluetoothAdapterProperties: ScanMode =  20
09-30 09:37:54.450  5730  5849 D BluetoothAdapterProperties: State =  11
09-30 09:37:54.450  5670  5670 D BluetoothMap: Bluetooth is Not enabled
,09-30 09:37:54.450  5730  5849 D BluetoothAdapterProperties: Setting state to 12
09-30 09:37:54.450  5730  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 09:37:54.451   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 09:37:54.451  5730  5849 I BluetoothAdapterState: Entering OnState
09-30 09:37:54.452  5730  5853 D BluetoothAdapterProperties: Scan Mode:21
09-30 09:37:54.452  5730  5853 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 09:37:54.453  5617  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 09:37:54.454  3102  5681 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 09:37:54.455   927   927 D BluetoothA2dp: Proxy object connected
09-30 09:37:54.457  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:54.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:54.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:54.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:54.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:54.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:54.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:54.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:54.458  5670  5684 D BluetoothPan: onBluetoothStateChange on: true
09-30 09:37:54.458  3102  3114 D BluetoothMap: onBluetoothStateChange: up=true
09-30 09:37:54.459  3102  3102 D BluetoothA2dp: Proxy object connected
09-30 09:37:54.460  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:54.460   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:37:54.461  5670  5682 D BluetoothPbap: onBluetoothStateChange: up=true
,09-30 09:37:54.462  3102  3102 D BluetoothMap: Proxy object connected
,09-30 09:37:54.462  3102  3102 D MapProfile: Bluetooth service connected
09-30 09:37:54.462  3102  3102 D BluetoothMap: getConnectedDevices()
09-30 09:37:54.462  5730  5730 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 09:37:54.463  5730  5730 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 09:37:54.463  5670  5684 D BluetoothMap: onBluetoothStateChange: up=true
09-30 09:37:54.464  3727  3750 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:37:54.464   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:37:54.464  5730  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 09:37:54.464  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:54.464  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:54.464  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:54.464  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:54.464  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:54.464  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:54.464  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:54.464  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:54.464  3102  3115 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 09:37:54.465  3102  3879 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 09:37:54.466  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:54.466  3102  3102 D BluetoothInputDevice: Proxy object connected
09-30 09:37:54.467  3102  5681 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 09:37:54.467  3102  3102 D HidProfile: Bluetooth service connected
09-30 09:37:54.468  5730  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 09:37:54.468  5670  5682 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 09:37:54.468   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:37:54.468  3102  3115 D BluetoothPan: onBluetoothStateChange on: true
09-30 09:37:54.469  5730  5730 D ObexServerSockets: Succeed to create listening sockets 
,09-30 09:37:54.469  5730  5730 D ObexServerSockets0: startAccept()
09-30 09:37:54.469  5730  5730 D ObexServerSockets0: prepareForNewConnect()
09-30 09:37:54.470  3102  3102 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 09:37:54.470  3102  3102 D PanProfile: Bluetooth service connected
,09-30 09:37:54.470  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:54.470  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:54.470  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:54.470  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:54.470  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:37:54.470  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:54.470  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:54.470  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:54.471   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,09-30 09:37:54.472  5730  5730 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 09:37:54.472  5730  5730 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 09:37:54.473  5670  5670 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-30 09:37:54.474  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:54.474  5617  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 09:37:54.476  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:54.478  5730  5730 D BluetoothMapService: onReceive
09-30 09:37:54.478  5730  5730 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 09:37:54.478  5730  5730 D BluetoothMapService: STATE_ON
09-30 09:37:54.479  5730  5875 D ObexServerSockets0: Accepting socket connection...
09-30 09:37:54.479  5670  5670 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-30 09:37:54.479  5730  5876 D ObexServerSockets0: Accepting socket connection...
09-30 09:37:54.479  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:54.481  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:54.482  5730  5877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 09:37:54.483  5730  5877 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 09:37:54.483  5730  5877 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-30 09:37:54.486  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 09:37:54.488  5670  5670 D BluetoothA2dp: Proxy object connected
,09-30 09:37:54.492  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 09:37:54.495  5670  5670 D DockEventReceiver: finishStartingService: stopping service
,09-30 09:37:54.498  5670  5670 D BluetoothPbap: Proxy object connected
,09-30 09:37:54.499  5670  5670 D PbapServerProfile: Bluetooth service connected
,09-30 09:37:54.501  3102  3102 D BluetoothPbap: Proxy object connected
,09-30 09:37:54.501  3102  3102 D PbapServerProfile: Bluetooth service connected
,09-30 09:37:54.506  5730  5730 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 09:37:54.506  5730  5730 D ObexServerSockets0: prepareForNewConnect()
09-30 09:37:54.509  5730  5881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 09:37:54.520  5730  5885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 09:37:54.521  5730  5885 I BtOppRfcommListener: Accept thread started.
,09-30 09:37:54.562   927   927 D BluetoothHeadset: Proxy object connected
09-30 09:37:54.562   927   927 D BluetoothHeadset: Proxy object connected
,09-30 09:37:54.562  3727  3760 D BluetoothHeadset: Proxy object connected
09-30 09:37:54.562   927   927 D BluetoothHeadset: Proxy object connected
09-30 09:37:54.563  3102  5681 D BluetoothHeadset: Proxy object connected
09-30 09:37:54.563  3102  3102 D HeadsetProfile: Bluetooth service connected
,09-30 09:37:54.564  3727  4123 D BluetoothHeadset: Proxy object connected
09-30 09:37:54.565   927   944 D BluetoothHeadset: Proxy object connected
09-30 09:37:54.565  3102  3115 D BluetoothHeadset: Proxy object connected
,09-30 09:37:54.566  3102  3102 D HeadsetProfile: Bluetooth service connected
,09-30 09:37:54.568   927   944 D BluetoothHeadset: Proxy object connected
,09-30 09:37:54.582  5670  5684 D BluetoothHeadset: Proxy object connected
,09-30 09:37:54.584  5670  5670 D HeadsetProfile: Bluetooth service connected
,09-30 09:37:54.873   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:37:55.873   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 09:37:56.348   927  2909 D ConnectivityService: handlePromptUnvalidated 101
,09-30 09:37:58.491  5730  5849 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 09:37:58.491  5730  5849 D BluetoothAdapterProperties: Setting state to 13
,09-30 09:37:58.491  5730  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 09:37:58.493  5730  5849 D BluetoothAdapterProperties: onBluetoothDisable()
,09-30 09:37:58.494  5730  5849 I BluetoothAdapterState: Entering PendingCommandState
09-30 09:37:58.498  5730  5730 D BluetoothMapService: onReceive
09-30 09:37:58.499  5730  5730 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 09:37:58.499  5730  5730 D BluetoothMapService: STATE_TURNING_OFF
09-30 09:37:58.500  5730  5730 D BluetoothMapService: MAP Service closeService in
09-30 09:37:58.500  5730  5730 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 09:37:58.500  5730  5730 D ObexServerSockets0: shutdown(block = true)
09-30 09:37:58.502  5730  5730 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 09:37:58.503  5730  5875 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-30 09:37:58.503  5730  5730 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 09:37:58.504  5730  5862 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 09:37:58.504  5730  5876 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 09:37:58.508  5730  5730 I BtOppRfcommListener: stopping Accept Thread
09-30 09:37:58.508  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 09:37:58.509  5730  5885 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 09:37:58.509  5730  5885 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-30 09:37:58.511  5730  5853 D BluetoothAdapterProperties: Scan Mode:20
09-30 09:37:58.511  5730  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-30 09:37:58.514  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:58.514  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:58.514  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:58.514  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:58.514  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:58.514  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:58.514  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:58.514  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:58.514  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 09:37:58.515  5670  5670 D DockEventReceiver: finishStartingService: stopping service
09-30 09:37:58.517  5730  5730 D HeadsetService: Received stop request...Stopping profile...
,09-30 09:37:58.518   927   927 D BluetoothHeadset: Proxy object disconnected
,09-30 09:37:58.518   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:58.519  5670  5682 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:58.519  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:58.519  3727  3976 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:58.519  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:58.520   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:58.520  3102  3114 D BluetoothHeadset: Proxy object disconnected
09-30 09:37:58.521  5670  5670 D HeadsetProfile: Bluetooth service disconnected
,09-30 09:37:58.523  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:58.524  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:58.524  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:58.524  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:58.524  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:58.524  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:58.524  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:58.524  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:58.524  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 09:37:58.525  5730  5730 D A2dpService: Received stop request...Stopping profile...
,09-30 09:37:58.525  5730  5868 D A2dpStateMachine: Exit Disconnected: -1
09-30 09:37:58.527  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:58.527  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 09:37:58.528   927   927 D BluetoothA2dp: Proxy object disconnected
09-30 09:37:58.528  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 09:37:58.529  5670  5670 D BluetoothA2dp: Proxy object disconnected
09-30 09:37:58.529  5730  5730 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:58.529  5730  5730 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:58.529  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:58.529  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:58.530  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:58.530  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:37:58.530  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:37:58.530  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:37:58.530  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:37:58.530  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 09:37:58.530  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:37:58.530  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:37:58.530  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:37:58.530  3102  3102 D HeadsetProfile: Bluetooth service disconnected
09-30 09:37:58.530  3102  3102 D BluetoothA2dp: Proxy object disconnected
09-30 09:37:58.530  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 09:37:58.530  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:37:58.532  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:37:58.532  5730  5730 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 09:37:58.532  5730  5730 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 09:37:58.532  5730  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 09:37:58.533  5730  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:58.533  5730  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:58.533  5730  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:58.533  5730  5853 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 09:37:58.533  5730  5730 D HidService: Received stop request...Stopping profile...
09-30 09:37:58.533  5730  5730 D HidService: Stopping Bluetooth HidService
09-30 09:37:58.533  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:58.534  3102  3102 D BluetoothInputDevice: Proxy object disconnected
,09-30 09:37:58.534  3102  3102 D HidProfile: Bluetooth service disconnected
09-30 09:37:58.534  5670  5670 D BluetoothInputDevice: Proxy object disconnected
09-30 09:37:58.534  5670  5670 D HidProfile: Bluetooth service disconnected
09-30 09:37:58.535  5730  5730 D HealthService: Received stop request...Stopping profile...
09-30 09:37:58.536  5730  5730 D PanService: Received stop request...Stopping profile...
09-30 09:37:58.537  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:58.537  3102  3102 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 09:37:58.537  3102  3102 D PanProfile: Bluetooth service disconnected
09-30 09:37:58.539  5730  5730 D BluetoothMapService: Received stop request...Stopping profile...
09-30 09:37:58.539  5730  5730 D BluetoothMapService: stop()
09-30 09:37:58.539  5670  5670 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 09:37:58.540  5670  5670 D PanProfile: Bluetooth service disconnected
09-30 09:37:58.540  5670  5670 D BluetoothPbap: Proxy object disconnected
09-30 09:37:58.540  5670  5670 D PbapServerProfile: Bluetooth service disconnected
09-30 09:37:58.540  5730  5730 D BluetoothMapAppObserver: deinitObservers()
,09-30 09:37:58.540  5730  5730 D BluetoothMapAppObserver: removeReceiver()
09-30 09:37:58.541  5670  5670 D BluetoothMap: Proxy object disconnected
09-30 09:37:58.541  5670  5670 D MapProfile: Bluetooth service disconnected
09-30 09:37:58.542  3102  3102 D BluetoothPbap: Proxy object disconnected
09-30 09:37:58.542  5730  5730 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:58.542  3102  3102 D PbapServerProfile: Bluetooth service disconnected
09-30 09:37:58.542  5730  5730 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:58.542  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:58.542  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:58.542  3102  3102 D BluetoothMap: Proxy object disconnected
09-30 09:37:58.542  3102  3102 D MapProfile: Bluetooth service disconnected
09-30 09:37:58.543  5730  5730 D SapService: Received stop request...Stopping profile...
09-30 09:37:58.543  5730  5730 V SapService: stop()
09-30 09:37:58.544  5730  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:58.544  5730  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 09:37:58.545  5730  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 09:37:58.545  5730  5860 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 09:37:58.545  5730  5860 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 09:37:58.545  5730  5860 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-30 09:37:58.545  5730  5860 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-30 09:37:58.546  5730  5730 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:58.547  5730  5730 V BluetoothAdapterState: isTurningOn()=false
,09-30 09:37:58.547  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 09:37:58.547  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:58.547  5730  5730 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 09:37:58.547  5730  5730 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 09:37:58.547  5730  5730 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:58.547  5730  5730 V BluetoothAdapterState: isTurningOn()=false
,09-30 09:37:58.547  5730  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 09:37:58.547  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:58.547  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:58.547  5730  5730 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 09:37:58.548  5730  5853 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 09:37:58.548  5730  5730 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 09:37:58.548  5730  5730 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:58.548  5730  5730 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:58.548  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:58.548  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:58.548  5730  5730 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 09:37:58.548  5730  5730 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 09:37:58.549  5730  5730 D BluetoothMapService: MAP Service closeService in
09-30 09:37:58.549  5730  5730 V BluetoothAdapterState: isTurningOff()=true
09-30 09:37:58.549  5730  5730 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:58.549  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:58.550  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:58.550  5730  5730 D BluetoothMapService: cleanup()
09-30 09:37:58.550  5730  5730 D BluetoothMapService: MAP Service closeService in
09-30 09:37:58.550  5730  5730 V BluetoothAdapterState: isTurningOff()=true
,09-30 09:37:58.550  5730  5730 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:58.550  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:58.550  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:37:58.550  5730  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 09:37:58.550  5730  5849 D BluetoothAdapterProperties: Setting state to 15
09-30 09:37:58.550  5730  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 09:37:58.551  5730  5849 I BluetoothAdapterState: Entering BleOnState
09-30 09:37:58.551   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 09:37:58.552  3102  3114 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-30 09:37:58.552  5670  5684 D BluetoothPan: onBluetoothStateChange on: false
09-30 09:37:58.553  3102  3879 D BluetoothMap: onBluetoothStateChange: up=false
09-30 09:37:58.554  5670  5891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 09:37:58.554  5670  5682 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:58.555   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:58.555  5670  5684 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 09:37:58.555  5670  5891 D BluetoothMap: onBluetoothStateChange: up=false
,09-30 09:37:58.556  3727  3750 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:58.556   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:58.556  3102  5681 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:58.556  3102  3115 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 09:37:58.557  3102  3114 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 09:37:58.558  5670  5682 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 09:37:58.559   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 09:37:58.559  3102  3879 D BluetoothPan: onBluetoothStateChange on: false
09-30 09:37:58.559  5730  5849 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 09:37:58.559  5730  5849 D BluetoothAdapterProperties: Setting state to 16
09-30 09:37:58.559  5730  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 09:37:58.560  5730  5849 D BluetoothAdapterProperties: onBleDisable
09-30 09:37:58.560  5730  5849 I BluetoothAdapterState: Entering PendingCommandState
09-30 09:37:58.560  5730  5850 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-30 09:37:58.562  5730  5860 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 09:37:58.562  5730  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 09:37:58.562  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:58.563  5730  5853 D BluetoothAdapterProperties: Scan Mode:20
,09-30 09:37:58.563  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 09:37:58.564  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:58.566  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:58.575  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:58.576  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 09:37:58.579  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:58.581  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:37:58.582  5670  5670 D DockEventReceiver: finishStartingService: stopping service
,09-30 09:37:58.767  5730  5853 I bt_hci  : shut_down
,09-30 09:37:58.771  5730  5857 D bt_hwcfg: hw_epilog_process
,09-30 09:37:58.771  5730  5857 I bt_vendor: low_power_mode_cb
,09-30 09:37:58.773  5730  5857 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 09:37:58.773  5730  5857 I bt_vendor: epilog_cb
09-30 09:37:58.773  5730  5857 I bt_hci  : epilog_finished_callback
,09-30 09:37:58.775  5730  5853 I bt_hci_h4: hal_close
09-30 09:37:58.775  5730  5853 I bt_userial_vendor: device fd = 54 close
,09-30 09:37:58.887  5730  5850 D bt_stack_manager: event_shut_down_stack finished.
,09-30 09:37:58.888  5730  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 09:37:58.891  5730  5849 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-30 09:37:58.891  5730  5730 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 09:37:58.892  5730  5730 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 09:37:58.892  5730  5730 D BtGatt.GattService: stop()
,09-30 09:37:58.893  5730  5730 D BtGatt.AdvertiseManager: advertise clients cleared
,09-30 09:37:58.896  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,09-30 09:37:58.896  5730  5730 V BluetoothAdapterState: isTurningOn()=false
09-30 09:37:58.896  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:37:58.896  5730  5730 V BluetoothAdapterState: isBleTurningOff()=true
,09-30 09:37:58.896  5730  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 09:37:58.897  5730  5849 D BluetoothAdapterProperties: Setting state to 10
,09-30 09:37:58.897  5730  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 09:37:58.898  5730  5849 I BluetoothAdapterState: Entering OffState
09-30 09:37:58.899   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-30 09:37:58.908  5730  5730 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 09:37:58.909  5730  5730 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 09:37:58.909  5730  5730 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-30 09:37:58.911  5730  5850 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 09:37:58.915  5730  5730 I art     : System.exit called, status: 0
,09-30 09:37:58.916  5730  5730 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 09:37:58.941   927  3555 I ActivityManager: Process com.android.bluetooth (pid 5730) has died
,09-30 09:38:03.488  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 09:38:03.488  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:38:03.496  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 09:38:03.496  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da6914a removed from the list
,09-30 09:38:03.497  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:38:03.497  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:38:03.497  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:03.499  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:03.499  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@56831d8 added. We now have 4 listener(s)
09-30 09:38:03.500  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:38:03.501  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:03.502  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@56831d8 removed from the list
09-30 09:38:03.502  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:38:03.502  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:03.502  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:03.505  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:03.505  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19d3931 added. We now have 4 listener(s)
09-30 09:38:03.506  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:38:08.517  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:38:08.553   927   944 I ActivityManager: Start proc 5896:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 09:38:08.634  5896  5896 D AdapterServiceConfig: Adding HeadsetService
,09-30 09:38:08.635  5896  5896 D AdapterServiceConfig: Adding A2dpService
09-30 09:38:08.635  5896  5896 D AdapterServiceConfig: Adding HidService
09-30 09:38:08.635  5896  5896 D AdapterServiceConfig: Adding HealthService
09-30 09:38:08.635  5896  5896 D AdapterServiceConfig: Adding PanService
09-30 09:38:08.635  5896  5896 D AdapterServiceConfig: Adding GattService
09-30 09:38:08.635  5896  5896 D AdapterServiceConfig: Adding BluetoothMapService
09-30 09:38:08.636  5896  5896 D AdapterServiceConfig: Adding SapService
,09-30 09:38:08.647   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@90f5a29:true
,09-30 09:38:08.647  5896  5896 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 09:38:08.651  5896  5896 I bt_bluedroid: init
,09-30 09:38:08.651  5896  5908 I BluetoothAdapterState: Entering OffState
,09-30 09:38:08.654  5896  5909 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-30 09:38:08.655  5896  5909 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 09:38:08.655  5896  5909 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 09:38:08.655  5896  5909 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 09:38:08.656  5896  5896 I bt_bluedroid: get_profile_interface socket
,09-30 09:38:08.657  5896  5896 I bt_bluedroid: get_profile_interface sdp
,09-30 09:38:08.662  5896  5907 I bt_bluedroid: config_hci_snoop_log
09-30 09:38:08.657  5896  5912 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 09:38:08.670  5896  5912 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 09:38:08.671   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 09:38:08.676  5896  5908 D BluetoothAdapterState: Current state: OFF, message: 0
09-30 09:38:08.676  5896  5908 D BluetoothAdapterProperties: Setting state to 14
09-30 09:38:08.676  5896  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-30 09:38:08.678  5896  5908 D BluetoothBondStateMachine: make
,09-30 09:38:08.679  5896  5914 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 09:38:08.682  5896  5908 I BluetoothAdapterState: Entering PendingCommandState
,09-30 09:38:08.683  5896  5896 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 09:38:08.685  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:38:08.686  5896  5896 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 09:38:08.687  5896  5896 D BtGatt.GattService: Received start request. Starting profile...
09-30 09:38:08.687  5896  5896 D BtGatt.GattService: start()
09-30 09:38:08.687  5896  5896 I bt_bluedroid: get_profile_interface gatt
09-30 09:38:08.688  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:38:08.688  5896  5896 D BtGatt.AdvertiseManager: advertise manager created
,09-30 09:38:08.693  5896  5896 V BluetoothAdapterState: isTurningOff()=false
09-30 09:38:08.693  5896  5896 V BluetoothAdapterState: isTurningOn()=false
09-30 09:38:08.694  5896  5896 V BluetoothAdapterState: isBleTurningOn()=true
,09-30 09:38:08.694  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:38:08.694  5896  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-30 09:38:08.695  5896  5908 I bt_bluedroid: bt_bluedroid
09-30 09:38:08.695  5896  5909 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 09:38:08.696  5896  5909 I bt_hci  : start_up
,09-30 09:38:08.700  5896  5909 I bt_vendor: alloc value 0xf3c69871
,09-30 09:38:08.701  5896  5909 I bt_vendor: init
09-30 09:38:08.701  5896  5909 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 09:38:08.701  5896  5909 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 09:38:08.810  5896  5909 D bt_hci  : start_up starting async portion
,09-30 09:38:08.811  5896  5917 I bt_hci  : event_finish_startup
,09-30 09:38:08.811  5896  5917 I bt_hci_h4: hal_open
09-30 09:38:08.811  5896  5917 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 09:38:08.807  5918  5918 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-30 09:38:08.814  5896  5917 I bt_userial_vendor: device fd = 54 open
,09-30 09:38:08.831  5896  5917 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 09:38:08.835  5896  5917 D bt_hwcfg: Chipset BCM4358A3
09-30 09:38:08.835  5896  5917 D bt_hwcfg: Target name = [BCM4358A3]
,09-30 09:38:08.835  5896  5917 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 09:38:09.351  5896  5917 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 09:38:09.352  5896  5917 D bt_hwcfg: Settlement delay -- 100 ms
09-30 09:38:09.352  5896  5917 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 09:38:09.486  5896  5917 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 09:38:09.487  5896  5917 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-30 09:38:09.488  5896  5917 I bt_hwcfg: vendor lib fwcfg completed
,09-30 09:38:09.488  5896  5917 I bt_vendor: firmware callback
09-30 09:38:09.488  5896  5917 I bt_hci  : firmware_config_callback
,09-30 09:38:09.497  5896  5920 I bt_btu  : btu_task pending for preload complete event
09-30 09:38:09.498  5896  5920 I bt_btu_task: Bluetooth chip preload is complete
,09-30 09:38:09.498  5896  5920 I bt_btu  : btu_task received preload complete event
,09-30 09:38:09.505  5896  5920 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 09:38:09.505  5896  5920 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 09:38:09.505  5896  5920 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 09:38:09.505  5896  5920 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 09:38:09.505  5896  5920 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 09:38:09.505  5896  5920 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 09:38:09.506  5896  5920 I         : BTE_InitTraceLevels -- TRC_BNEP
09-30 09:38:09.506  5896  5920 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 09:38:09.506  5896  5920 I         : BTE_InitTraceLevels -- TRC_GAP
,09-30 09:38:09.506  5896  5920 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 09:38:09.506  5896  5920 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 09:38:09.506  5896  5920 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 09:38:09.506  5896  5920 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 09:38:09.506  5896  5920 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 09:38:09.507  5896  5920 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 09:38:09.605  5896  5920 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3be7549
,09-30 09:38:09.605  5896  5920 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3be7549 
,09-30 09:38:09.622  5896  5912 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,09-30 09:38:09.625  5896  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 09:38:09.625  5896  5912 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-30 09:38:09.628  5896  5912 D BluetoothAdapterProperties: Name is: Nexus 6P
09-30 09:38:09.630  5896  5912 D BluetoothAdapterProperties: Scan Mode:20
,09-30 09:38:09.631  5896  5912 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 09:38:09.631  5896  5912 D bt_hci  : do_postload posting postload work item
09-30 09:38:09.631  5896  5917 I bt_hci  : event_postload
,09-30 09:38:09.631  5896  5917 I bt_vendor: sco_config_cb
09-30 09:38:09.631  5896  5917 I bt_hci  : sco_config_callback postload finished.
09-30 09:38:09.634  5896  5912 D bt_bte_conf: Device ID record 1 : primary
,09-30 09:38:09.634  5896  5912 D bt_bte_conf:   vendorId            = 000f
,09-30 09:38:09.634  5896  5912 D bt_bte_conf:   vendorIdSource      = 0001
09-30 09:38:09.634  5896  5912 D bt_bte_conf:   product             = 1200
09-30 09:38:09.634  5896  5912 D bt_bte_conf:   version             = 1436
09-30 09:38:09.634  5896  5912 D bt_bte_conf:   clientExecutableURL = 
09-30 09:38:09.634  5896  5912 D bt_bte_conf:   serviceDescription  = 
,09-30 09:38:09.634  5896  5912 D bt_bte_conf:   documentationURL    = 
09-30 09:38:09.635  5896  5912 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 09:38:09.635  5896  5909 D bt_stack_manager: event_start_up_stack finished
09-30 09:38:09.637  5896  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-30 09:38:09.638  5896  5908 D BluetoothAdapterProperties: Setting state to 15
09-30 09:38:09.638  5896  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-30 09:38:09.640  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:09.641  5896  5908 I BluetoothAdapterState: Entering BleOnState
09-30 09:38:09.643  5896  5917 I bt_vendor: low_power_mode_cb
09-30 09:38:09.644  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:09.646  5896  5908 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 09:38:09.646  5896  5908 D BluetoothAdapterProperties: Setting state to 11
09-30 09:38:09.646  5896  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 09:38:09.654  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:38:09.656  5896  5896 D HeadsetService: Received start request. Starting profile...
,09-30 09:38:09.660  5896  5896 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 09:38:09.661  5896  5896 D HeadsetStateMachine: make
,09-30 09:38:09.662  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:38:09.667  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:38:09.672  5896  5908 I BluetoothAdapterState: Entering PendingCommandState
,09-30 09:38:09.678  5896  5896 D HeadsetStateMachine: max_hf_connections = 1
,09-30 09:38:09.678  5896  5896 I bt_bluedroid: get_profile_interface handsfree
09-30 09:38:09.678  5896  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 09:38:09.678  5896  5912 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-30 09:38:09.683  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
,09-30 09:38:09.683  5896  5896 D A2dpService: Received start request. Starting profile...
,09-30 09:38:09.684  5896  5896 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 09:38:09.684  5896  5896 I bt_bluedroid: get_profile_interface avrcp
,09-30 09:38:09.690  5896  5896 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 09:38:09.690  5896  5896 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 09:38:09.690  5896  5896 D A2dpStateMachine: make
09-30 09:38:09.691  5896  5896 I bt_bluedroid: get_profile_interface a2dp
09-30 09:38:09.692  5896  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 09:38:09.693  5896  5928 D A2dpStateMachine: Enter Disconnected: -2
,09-30 09:38:09.694  5896  5896 I BluetoothHidServiceJni: classInitNative: succeeds
,09-30 09:38:09.695  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:38:09.695  5896  5896 D HidService: Received start request. Starting profile...
09-30 09:38:09.696  5896  5896 I bt_bluedroid: get_profile_interface hidhost
09-30 09:38:09.696  5896  5912 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bc856d
09-30 09:38:09.696  5896  5896 D HidService: setHidService(): set to: null
09-30 09:38:09.696  5896  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 09:38:09.696  5896  5896 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 09:38:09.697  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:38:09.698  5896  5896 D HealthService: Received start request. Starting profile...
,09-30 09:38:09.699  5896  5896 I bt_bluedroid: get_profile_interface health
,09-30 09:38:09.701  5896  5896 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 09:38:09.702  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:38:09.702  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 09:38:09.703  5896  5896 D PanService: Received start request. Starting profile...
,09-30 09:38:09.703  5896  5896 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 09:38:09.703  5896  5896 I bt_bluedroid: get_profile_interface pan
09-30 09:38:09.704  5896  5912 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-30 09:38:09.706  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:38:09.706  5896  5896 D BluetoothMapService: Received start request. Starting profile...
09-30 09:38:09.706  5896  5896 D BluetoothMapService: start()
09-30 09:38:09.708  5896  5896 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 09:38:09.709  5896  5896 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 09:38:09.709  5896  5896 D BluetoothMapAppObserver: createReceiver()
09-30 09:38:09.710  5896  5896 D BluetoothMapAppObserver: initObservers()
09-30 09:38:09.710  5896  5896 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 09:38:09.716  5896  5896 V SapService: SapBinder()
,09-30 09:38:09.716  5896  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:38:09.717  5896  5896 D SapService: Received start request. Starting profile...
09-30 09:38:09.717  5896  5896 V SapService: start()
,09-30 09:38:09.720  5896  5896 V BluetoothAdapterState: isTurningOff()=false
09-30 09:38:09.720  5896  5896 V BluetoothAdapterState: isTurningOn()=true
09-30 09:38:09.720  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:38:09.720  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:38:09.721  5896  5925 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isTurningOff()=false
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isTurningOn()=true
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isTurningOff()=false
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isTurningOn()=true
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:38:09.721  5896  5896 V BluetoothAdapterState: isTurningOff()=false
09-30 09:38:09.722  5896  5896 V BluetoothAdapterState: isTurningOn()=true
09-30 09:38:09.722  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:38:09.722  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:38:09.722  5896  5896 V BluetoothAdapterState: isTurningOff()=false
09-30 09:38:09.722  5896  5896 V BluetoothAdapterState: isTurningOn()=true
,09-30 09:38:09.723  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:38:09.723  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
09-30 09:38:09.723  5896  5896 V BluetoothAdapterState: isTurningOff()=false
09-30 09:38:09.723  5896  5896 V BluetoothAdapterState: isTurningOn()=true
09-30 09:38:09.723  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:38:09.723  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 09:38:09.724  5896  5896 V BluetoothAdapterState: isTurningOff()=false
09-30 09:38:09.724  5896  5896 V BluetoothAdapterState: isTurningOn()=true
09-30 09:38:09.724  5896  5896 V BluetoothAdapterState: isBleTurningOn()=false
09-30 09:38:09.724  5896  5896 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 09:38:09.724  5896  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 09:38:09.724  5896  5908 D BluetoothAdapterProperties: ScanMode =  20
09-30 09:38:09.725  5896  5908 D BluetoothAdapterProperties: State =  11
09-30 09:38:09.725  5896  5908 D BluetoothAdapterProperties: Setting state to 12
09-30 09:38:09.725  5896  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 09:38:09.725   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 09:38:09.725  5896  5908 I BluetoothAdapterState: Entering OnState
09-30 09:38:09.726  3102  3115 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 09:38:09.726  5896  5912 D BluetoothAdapterProperties: Scan Mode:21
09-30 09:38:09.726  5896  5912 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 09:38:09.727  5617  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 09:38:09.727   927   927 D BluetoothA2dp: Proxy object connected
09-30 09:38:09.730  3102  3102 D BluetoothA2dp: Proxy object connected
09-30 09:38:09.730  5670  5682 D BluetoothPan: onBluetoothStateChange on: true
,09-30 09:38:09.732  3102  3879 D BluetoothMap: onBluetoothStateChange: up=true
09-30 09:38:09.732  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:38:09.732  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:09.732  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:09.732  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:38:09.732  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:09.732  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:38:09.732  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:38:09.732  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:38:09.733  5670  5684 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 09:38:09.734  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:38:09.735  5670  5682 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:38:09.735   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:38:09.735  5670  5891 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 09:38:09.736  5670  5670 D BluetoothA2dp: Proxy object connected
,09-30 09:38:09.737  3102  3102 D BluetoothMap: Proxy object connected
09-30 09:38:09.737  3102  3102 D MapProfile: Bluetooth service connected
09-30 09:38:09.738  3102  3102 D BluetoothMap: getConnectedDevices()
09-30 09:38:09.738  5670  5682 D BluetoothMap: onBluetoothStateChange: up=true
09-30 09:38:09.738  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:38:09.738  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:09.738  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:09.738  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:38:09.738  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:09.738  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:38:09.738  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:38:09.738  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:38:09.740  3727  3750 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:38:09.740   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:38:09.740  3102  3115 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:38:09.740  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:38:09.740  5896  5896 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 09:38:09.741  3102  3114 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 09:38:09.741  5896  5896 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 09:38:09.742  3102  3879 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 09:38:09.742  5896  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 09:38:09.743  5670  5891 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 09:38:09.744  5896  5896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 09:38:09.745   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 09:38:09.745  3102  5681 D BluetoothPan: onBluetoothStateChange on: true
09-30 09:38:09.745  5896  5896 D ObexServerSockets: Succeed to create listening sockets 
09-30 09:38:09.745  5896  5896 D ObexServerSockets0: startAccept()
09-30 09:38:09.745  5896  5896 D ObexServerSockets0: prepareForNewConnect()
,09-30 09:38:09.747  3102  3102 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 09:38:09.747  3102  3102 D PanProfile: Bluetooth service connected
09-30 09:38:09.747  5670  5670 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 09:38:09.747  5670  5670 D PanProfile: Bluetooth service connected
09-30 09:38:09.747  5670  5670 D BluetoothMap: Proxy object connected
,09-30 09:38:09.747  5670  5670 D MapProfile: Bluetooth service connected
09-30 09:38:09.747  5670  5670 D BluetoothMap: getConnectedDevices()
,09-30 09:38:09.748  5617  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 09:38:09.749   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 09:38:09.749  5896  5896 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 09:38:09.749  5896  5896 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 09:38:09.751  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:09.751  5896  5935 D ObexServerSockets0: Accepting socket connection...
,09-30 09:38:09.751  5896  5936 D ObexServerSockets0: Accepting socket connection...
09-30 09:38:09.751  5896  5896 D BluetoothMapService: onReceive
09-30 09:38:09.752  3102  3102 D BluetoothInputDevice: Proxy object connected
09-30 09:38:09.752  5896  5896 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 09:38:09.752  3102  3102 D HidProfile: Bluetooth service connected
09-30 09:38:09.752  5896  5896 D BluetoothMapService: STATE_ON
09-30 09:38:09.752  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:09.756  5896  5937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 09:38:09.757  5670  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 09:38:09.758  5896  5937 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 09:38:09.758  5896  5937 D BluetoothSdpJni: SDP Create record success - handle: 1
09-30 09:38:09.760  5670  5670 D BluetoothInputDevice: Proxy object connected
09-30 09:38:09.760  5670  5670 D HidProfile: Bluetooth service connected
,09-30 09:38:09.764  3539  3539 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 09:38:09.766  5670  5670 D DockEventReceiver: finishStartingService: stopping service
,09-30 09:38:09.771  3102  3102 D BluetoothPbap: Proxy object connected
09-30 09:38:09.771  3102  3102 D PbapServerProfile: Bluetooth service connected
09-30 09:38:09.771  5670  5670 D BluetoothPbap: Proxy object connected
09-30 09:38:09.771  5670  5670 D PbapServerProfile: Bluetooth service connected
,09-30 09:38:09.778  5896  5941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 09:38:09.777  5896  5896 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 09:38:09.778  5896  5896 D ObexServerSockets0: prepareForNewConnect()
,09-30 09:38:09.796  5896  5945 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 09:38:09.797  5896  5945 I BtOppRfcommListener: Accept thread started.
,09-30 09:38:09.837   927   927 D BluetoothHeadset: Proxy object connected
09-30 09:38:09.837   927   927 D BluetoothHeadset: Proxy object connected
,09-30 09:38:09.838  5670  5891 D BluetoothHeadset: Proxy object connected
09-30 09:38:09.838  3727  3760 D BluetoothHeadset: Proxy object connected
09-30 09:38:09.838   927   927 D BluetoothHeadset: Proxy object connected
09-30 09:38:09.838  3102  3879 D BluetoothHeadset: Proxy object connected
09-30 09:38:09.839  3102  3102 D HeadsetProfile: Bluetooth service connected
09-30 09:38:09.840  3727  4123 D BluetoothHeadset: Proxy object connected
09-30 09:38:09.840   927   944 D BluetoothHeadset: Proxy object connected
09-30 09:38:09.841  5670  5670 D HeadsetProfile: Bluetooth service connected
09-30 09:38:09.841  3102  5681 D BluetoothHeadset: Proxy object connected
,09-30 09:38:09.841  3102  3102 D HeadsetProfile: Bluetooth service connected
,09-30 09:38:09.845   927   944 D BluetoothHeadset: Proxy object connected
,09-30 09:38:13.535  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:38:13.535  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:13.535  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:13.535  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 09:38:13.535  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:13.535  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:38:13.535  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:38:13.535  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:38:13.540  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 09:38:13.541  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:13.541  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19d3931 removed from the list
09-30 09:38:13.541  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:38:13.541  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:13.541  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:38:13.544  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 09:38:13.544  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4447816 added. We now have 4 listener(s)
09-30 09:38:13.544  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:38:13.548   927  3113 D WifiService: setWifiEnabled: false pid=5617, uid=10077
09-30 09:38:13.548   927  3113 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 09:38:15.875   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:38:16.876   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:38:17.878   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:38:18.559  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:38:18.560   927  3113 D WifiService: setWifiEnabled: true pid=5617, uid=10077
,09-30 09:38:18.560   927  3113 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-30 09:38:18.568   507   926 D SoftapController: Softap fwReload - Ok
,09-30 09:38:18.574   507   926 D CommandListener: Setting iface cfg
09-30 09:38:18.575   507   926 D CommandListener: Trying to bring down wlan0
09-30 09:38:18.577   507   926 D CommandListener: Clearing all IP addresses on wlan0
,09-30 09:38:18.582   927  2907 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 09:38:18.880   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:38:19.245   927  2907 D wifi    : set interface wlan0 flags (UP)
,09-30 09:38:19.245   927  2907 I WifiHAL : Initializing wifi
09-30 09:38:19.245   927  2907 I WifiHAL : Creating socket
09-30 09:38:19.252   927  2907 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-30 09:38:19.252   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-30 09:38:19.252   927  2907 D wifi    : Did set static halHandle = 0x7f71771480
09-30 09:38:19.252   927  2907 D wifi    : halHandle = 0x7f71771480, mVM = 0x7f8ddcd140, mCls = 0x10132e
,09-30 09:38:19.253   927  2907 D wifi    : array field set
09-30 09:38:19.254   927  2907 I WifiNative-HAL: interface[0] = wlan0
09-30 09:38:19.258   927  5951 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547364476032
09-30 09:38:19.258   927  5951 D wifi    : waitForHalEvents called, vm = 0x7f8ddcd140, obj = 0x10132e, env = 0x7f72a84ac0
,09-30 09:38:19.318  5952  5952 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 09:38:19.339  5952  5952 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 09:38:19.359   927  2907 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 09:38:19.368  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:19.372  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:38:19.380  5952  5952 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-30 09:38:19.380  5952  5952 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 09:38:19.398   927  2907 D WifiConfigStore: Loading config and enabling all networks 
,09-30 09:38:19.402  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:38:19.402  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:19.402  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:19.402  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:19.402  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:19.402  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:38:19.402  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:38:19.402  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 09:38:19.405  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 09:38:19.408  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:38:19.408  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:19.408  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:19.408  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:19.408  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:19.408  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 09:38:19.408  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 09:38:19.408  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 09:38:19.410  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 09:38:19.415   927  2907 D WifiConfigStore: loaded 0 passpoint configs
,09-30 09:38:19.416   927  2907 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 09:38:19.416   927  2907 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 09:38:19.417   927  2907 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 09:38:19.418   927  2907 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 09:38:19.419   927  2907 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 09:38:19.419   927  2907 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 09:38:19.419   927  2907 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 09:38:19.422   927  2907 D WifiNative-HAL: Setting external_sim to 1
,09-30 09:38:19.422   927  2907 D wifi    : setting dfs flag to true, 0x7f72a4acc0
09-30 09:38:19.422  4369  4369 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 09:38:19.423   927  2907 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 09:38:19.423   927  2907 D wifi    : setting scan oui 0x7f72a4acc0
09-30 09:38:19.423   927  2907 D WifiHAL : Sending mac address OUI
,09-30 09:38:19.427   927  2907 E native  : do suspend false
,09-30 09:38:19.436   927  2907 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 09:38:19.436   927   927 D RttService: SCAN_AVAILABLE : 3
09-30 09:38:19.437   507   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 09:38:19.437   927  3017 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 09:38:19.438   507   926 D CommandListener: Setting iface cfg
,09-30 09:38:19.443   927  2906 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-30 09:38:19.443   927  2906 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 09:38:19.457   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302847 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-30 09:38:19.459   927  2906 D WifiNative-HAL: p2pGetDeviceAddress
09-30 09:38:19.460   927  2906 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 09:38:19.882   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:38:20.883   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 09:38:22.622  5952  5952 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 09:38:22.627  5952  5952 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 09:38:22.632  5952  5952 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 09:38:22.637  5952  5952 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 09:38:22.683   927  2907 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 09:38:22.684   927  2907 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 09:38:22.685   927  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 09:38:22.696   927  2907 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 09:38:22.729   927  2907 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 09:38:22.731  5952  5952 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 09:38:23.159  5952  5952 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 09:38:23.196  5952  5952 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 09:38:23.197  5952  5952 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 09:38:23.205   927  2907 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 09:38:23.206   927  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 09:38:23.207   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 09:38:23.223   927  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 09:38:23.236   507   926 D CommandListener: Setting iface cfg
,09-30 09:38:23.241   927  2907 D WifiStateMachine: Start Dhcp Watchdog 3
,09-30 09:38:23.246   927  5957 D DhcpClient: Receive thread started
,09-30 09:38:23.250   927  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 09:38:23.250   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 09:38:23.250   927  2909 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-30 09:38:23.330   927  2907 E native  : do suspend false
,09-30 09:38:23.345   927  5956 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 09:38:23.360   927  5957 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-30 09:38:23.361   927  5956 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-30 09:38:23.363   927  5956 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 09:38:23.379   927  5957 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 09:38:23.379   927  5956 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-30 09:38:23.382   507   926 D CommandListener: Setting iface cfg
,09-30 09:38:23.386   927  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 09:38:23.390   927  5956 D DhcpClient: Scheduling renewal in 86399s
,09-30 09:38:23.397   927  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 09:38:23.398   927  2907 D WifiConfigStore: No blacklist allowed without epno enabled
,09-30 09:38:23.399   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 09:38:23.402   927  2909 D ConnectivityService: Adding iface wlan0 to network 102
,09-30 09:38:23.414   927  2907 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 09:38:23.451   927  2909 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-30 09:38:23.451   927  2909 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-30 09:38:23.455   927  2909 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-30 09:38:23.457   927  2909 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-30 09:38:23.458   927  2909 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-30 09:38:23.465   927  2909 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 09:38:23.469   927  2909 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-30 09:38:23.470   927  2909 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-30 09:38:23.470   927  2909 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-30 09:38:23.470   927  2909 D ConnectivityService:    accepting network in place of null
09-30 09:38:23.470   927  2907 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 09:38:23.470   927  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 09:38:23.471   927  2909 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 09:38:23.489   927  5955 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306879, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 09:38:23.493   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 09:38:23.513   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 09:38:23.516   927  2909 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-30 09:38:23.516   927  2909 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 09:38:23.517  3698  3846 W QCNEJ   : |CORE| network available: 102
,09-30 09:38:23.517   927  2909 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-30 09:38:23.519   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-30 09:38:23.521  3698  3846 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-30 09:38:23.522  3698  3846 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 09:38:23.523  3698  3846 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-30 09:38:23.526  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:38:23.526  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:23.526  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:23.526  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:23.526  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:23.526  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:23.526  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:38:23.526  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:38:23.528  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:23.532  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:38:23.532  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:23.532  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:23.532  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:23.532  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:23.532  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:23.532  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:38:23.532  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:38:23.532  4982  4995 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 09:38:23.533  4982  4995 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 09:38:23.533  4982  4995 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 09:38:23.535  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:23.535  4982  4995 E SarControlService: no key has been found,reset the power
09-30 09:38:23.536  4982  5020 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 09:38:23.536  4982  5020 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 09:38:23.537  3960  3960 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 09:38:23.538  4982  5020 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 09:38:23.538  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 09:38:23.538  5008  5008 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 09:38:23.540  4982  5020 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 09:38:23.540  4982  5020 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-30 09:38:23.540  4982  5020 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-30 09:38:23.540  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-30 09:38:23.540  5008  5008 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 09:38:23.543  3960  3960 D SystemUpdateService: onCreate
09-30 09:38:23.545  5008  5022 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@65fa8e1 HexData = [00000000f003000000000000ffffffff]
09-30 09:38:23.545  5008  5022 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 09:38:23.545  5008  5022 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-30 09:38:23.545  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 09:38:23.545  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 09:38:23.545  5008  5022 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@65fa8e1 HexData = [00000000f103000000000000ffffffff]
09-30 09:38:23.546  5008  5022 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 09:38:23.546  5008  5022 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-30 09:38:23.546  5008  5008 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 09:38:23.546  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 09:38:23.548  3960  3960 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 09:38:23.558  3960  3960 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 09:38:23.559   927  5954 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-30 09:38:23.565  3960  5967 I SystemUpdateService: active receiver: enabled
,09-30 09:38:23.567  3960  5336 I iu.UploadsManager: num queued entries: 0
,09-30 09:38:23.567  3960  5336 I iu.UploadsManager: num updated entries: 0
09-30 09:38:23.568  3960  5336 I iu.SyncManager: NEXT; no task
,09-30 09:38:23.570  3960  3960 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 09:38:23.571  3960  3960 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 09:38:23.573  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 09:38:23.573  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:23.573  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:23.573  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:23.573  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:23.573  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:23.573  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:38:23.573  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:38:23.573  5744  5744 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-30 09:38:23.574  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:23.575  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:23.575  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4447816 removed from the list
09-30 09:38:23.575  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 09:38:23.575  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:23.575  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:38:23.577  5744  5744 D SprintDMHelper: simOperator: 
09-30 09:38:23.577  5744  5744 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-30 09:38:23.578  5617  5972 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-30 09:38:23.578  5617  5972 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 09:38:23.598  3960  5967 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 09:38:23.609   927  5954 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 13:38:23 GMT], X-Android-Received-Millis=[1475242703608], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475242703583]}
,09-30 09:38:23.609   927  2909 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 09:38:23.609   927  2909 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-30 09:38:23.609   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 09:38:23.611   927  2909 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-30 09:38:23.611  3960  5967 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 09:38:23.611  3960  5967 I SystemUpdateService: now status is 0 (complete)
09-30 09:38:23.612  3960  5967 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 09:38:23.612  3960  5967 I SystemUpdateService: file has been verified
09-30 09:38:23.612  3960  5967 I SystemUpdateService: OTA package size = 21989297
,09-30 09:38:23.616  3960  5967 I SystemUpdateService: showing system update notification
,09-30 09:38:23.628  3960  3960 D SystemUpdateService: onDestroy
,09-30 09:38:23.740  4369  5973 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 09:38:26.273   927  2909 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 09:38:26.612  5617  5980 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-30 09:38:26.611  5617  5972 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-30 09:38:26.613  5617  5972 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-30 09:38:26.613  5617  5980 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-30 09:38:26.614  5617  5980 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 09:38:26.615  5617  5972 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 09:38:26.615  5617  5980 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 09:38:26.619  5617  5980 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 09:38:26.619  5617  5982 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:26.619  5617  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 09:38:26.619  5617  5972 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 09:38:26.621  5617  5984 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:26.621  5617  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 09:38:26.621  5617  5983 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:26.621  5617  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:26.622  5617  5972 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 09:38:26.622  5617  5984 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:26.622  5617  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 09:38:26.623  5617  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 09:38:26.623  5617  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 09:38:26.623  5617  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 09:38:26.623  5617  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 09:38:26.624  5617  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-30 09:38:26.625  5617  5984 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 09:38:26.625  5617  5984 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 09:38:26.627  5617  5982 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 152, thread name: IncomingSocketThread/Sender): Socket closed
09-30 09:38:26.627  5617  5984 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 09:38:26.628  5617  5983 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 153, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:26.628  5617  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 09:38:26.629  5617  5985 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:26.629  5617  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:26.629  5617  5982 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 152, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:26.629  5617  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 09:38:26.629  5617  5984 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:26.629  5617  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-30 09:38:26.629  5617  5983 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
09-30 09:38:26.629  5617  5982 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 09:38:26.629  5617  5982 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:26.629  5617  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 09:38:26.630  5617  5985 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:26.630  5617  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:26.630  5617  5982 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 152, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:26.630  5617  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 09:38:26.630  5617  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 09:38:26.630  5617  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:26.631  5617  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 09:38:26.631  5617  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 09:38:26.631  5617  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 09:38:26.631  5617  5985 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 09:38:26.631  5617  5985 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 09:38:26.631  5617  5985 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 09:38:26.631  5617  5985 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-30 09:38:26.631  5617  5985 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:26.631  5617  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 09:38:29.590  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-30 09:38:29.593  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-30 09:38:29.598  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e7947d5 Bundle[{}]
,09-30 09:38:29.599  5617  5663 I io.jxcore.node.LifeCycleMonitor: start: OK
09-30 09:38:29.600  5617  5663 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-30 09:38:29.600  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-30 09:38:29.601  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-30 09:38:29.602  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-30 09:38:29.603  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-30 09:38:29.610  5617  5663 I System.out: Running OutgoingSocketThread
,09-30 09:38:29.612  5617  5986 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-30 09:38:29.612  5617  5986 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 09:38:31.475   927  2909 D ConnectivityService: handlePromptUnvalidated 102
,09-30 09:38:32.622  5617  5986 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-30 09:38:32.622  5617  5987 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-30 09:38:32.623  5617  5987 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 09:38:32.623  5617  5986 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-30 09:38:32.623  5617  5987 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 09:38:32.623  5617  5986 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 09:38:32.625  5617  5986 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 09:38:32.625  5617  5987 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 09:38:32.627  5617  5989 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:32.627  5617  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:32.628  5617  5986 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 09:38:32.629  5617  5987 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 09:38:32.633  5617  5990 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:32.633  5617  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 09:38:32.634  5617  5991 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:32.634  5617  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:32.636  5617  5992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:32.636  5617  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 09:38:32.636  5617  5991 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:32.636  5617  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:32.636  5617  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 09:38:32.636  5617  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:32.636  5617  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 09:38:32.636  5617  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 09:38:32.637  5617  5992 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:32.637  5617  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 09:38:32.637  5617  5989 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 164, thread name: OutgoingSocketThread/Sender): Socket closed
09-30 09:38:32.637  5617  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 09:38:32.637  5617  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 09:38:32.637  5617  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 09:38:32.637  5617  5991 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 09:38:32.637  5617  5989 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 164, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:32.637  5617  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 09:38:32.637  5617  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 09:38:32.637  5617  5991 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 09:38:32.637  5617  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 09:38:32.637  5617  5989 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,09-30 09:38:32.638  5617  5991 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 09:38:32.638  5617  5989 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 09:38:32.638  5617  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 09:38:32.638  5617  5991 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:32.638  5617  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 09:38:32.638  5617  5989 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:32.638  5617  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 09:38:32.638  5617  5992 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 09:38:32.638  5617  5992 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 09:38:32.638  5617  5992 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 09:38:32.638  5617  5992 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 09:38:32.638  5617  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 09:38:32.641  5617  5990 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 165, thread name: IncomingSocketThread/Sender): Socket closed
09-30 09:38:32.641  5617  5990 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:32.641  5617  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 09:38:32.641  5617  5990 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,09-30 09:38:32.642  5617  5990 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 09:38:32.642  5617  5990 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 09:38:32.642  5617  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 09:38:34.460   927  2907 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-30 09:38:35.623  5617  5663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-30 09:38:35.624  5617  5663 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-30 09:38:35.624  5617  5663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-30 09:38:35.630  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 09:38:35.631  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c20597 added. We now have 3 listener(s)
,09-30 09:38:35.634  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 09:38:35.634  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.635  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.635  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.635  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1a9384 added. We now have 4 listener(s)
,09-30 09:38:35.635  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:38:35.636  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 09:38:35.642  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:38:35.649  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:38:35.649  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:35.649  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:35.649  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:35.649  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:35.649  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:35.649  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:38:35.649  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:38:35.651  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:35.652  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:38:35.652  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.652  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b07ffa2 added. We now have 4 listener(s)
09-30 09:38:35.654  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.654  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.655  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 09:38:35.655  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:35.655  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.655  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b976433 added. We now have 5 listener(s)
09-30 09:38:35.655  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:38:35.655  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:38:35.655  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:38:35.655  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:38:35.655  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 09:38:35.655  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.655  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:38:35.655  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.655  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 09:38:35.655  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c20597 removed from the list
,09-30 09:38:35.655  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.656  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1a9384 removed from the list
09-30 09:38:35.657  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:35.658  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:38:35.658  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.658  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.658  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.660  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.660  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:38:35.660  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.660  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1a9384 not in the list
09-30 09:38:35.660  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.660  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:38:35.661  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:38:35.661  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.661  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.661  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b976433 removed from the list
09-30 09:38:35.662  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:38:35.662  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.662  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:38:35.662  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.662  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 09:38:35.662  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b07ffa2 removed from the list
09-30 09:38:35.662  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.663  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f63f0 added. We now have 3 listener(s)
,09-30 09:38:35.664  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.664  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.664  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.664  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.665  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@580dd69 added. We now have 4 listener(s)
,09-30 09:38:35.665  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:38:35.665  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 09:38:35.669  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:38:35.673  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:38:35.673  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:35.673  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:35.673  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:35.673  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:35.673  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:35.673  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:38:35.673  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:38:35.675  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:38:35.675  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:38:35.676  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.676  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95a108f added. We now have 4 listener(s)
09-30 09:38:35.677  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.677  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.677  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.678  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.678  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fecf1c added. We now have 5 listener(s)
,09-30 09:38:35.678  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:38:35.678  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:38:35.678  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 09:38:35.678  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 09:38:35.678  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:38:35.678  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 09:38:35.679  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:35.682  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:38:35.683  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 09:38:35.683  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 09:38:35.687  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 09:38:35.688  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 09:38:35.688  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 09:38:35.691  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 09:38:35.691  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 09:38:35.691  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 09:38:35.691  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 09:38:35.692  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 09:38:35.692  5617  5663 D BluetoothAdapter: STATE_ON
,09-30 09:38:35.695  5896  5933 D BtGatt.GattService: registerClient() - UUID=f45e3c08-6f82-4a48-be9a-e4c5b96dc1bb
09-30 09:38:35.696  5896  5912 D BtGatt.GattService: onClientRegistered() - UUID=f45e3c08-6f82-4a48-be9a-e4c5b96dc1bb, clientIf=5
,09-30 09:38:35.697  5617  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 09:38:35.697  5896  5907 D BtGatt.GattService: start scan with filters
,09-30 09:38:35.701  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 09:38:35.701  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 09:38:35.701  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:38:35.701  5896  5916 D BtGatt.ScanManager: handling starting scan
09-30 09:38:35.701  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 09:38:35.701  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 09:38:35.701  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 09:38:35.701  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 09:38:35.702  5896  5916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7d56fde
09-30 09:38:35.703  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:38:35.703  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 09:38:35.703  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 09:38:35.705  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 09:38:35.708  5617  5663 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 09:38:35.708  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 09:38:35.708  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 09:38:35.708  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.708  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 09:38:35.708  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.708  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 09:38:35.708  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 09:38:35.708  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 09:38:35.708  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 09:38:35.708  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 09:38:35.709  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 09:38:35.710  5896  5912 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 09:38:35.710  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:38:35.710  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:38:35.710  5896  5913 D BtGatt.GattService: stopScan() - queue size =1
09-30 09:38:35.710  5896  5916 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 09:38:35.711  5896  5933 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 09:38:35.712  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 09:38:35.712  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-30 09:38:35.712  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 09:38:35.712  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:38:35.712  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 09:38:35.712  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 09:38:35.712  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-30 09:38:35.712  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 09:38:35.713  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:38:35.714  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 09:38:35.714  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 09:38:35.714  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 09:38:35.714  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 09:38:35.714  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:38:35.715  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:38:35.715  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:38:35.715  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:38:35.717  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 09:38:35.717  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.718  5896  5916 D BtGatt.ScanManager: Starting BLE batch scan
,09-30 09:38:35.718  5896  5916 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 09:38:35.719  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:38:35.719  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:38:35.719  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:38:35.719  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:38:35.719  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.719  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:38:35.719  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.719  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 09:38:35.719  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f63f0 removed from the list
09-30 09:38:35.719  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 09:38:35.719  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@580dd69 removed from the list
09-30 09:38:35.719  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:38:35.719  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.720  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.720  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.721  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.721  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:38:35.721  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.721  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@580dd69 not in the list
09-30 09:38:35.722  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.722  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:38:35.723  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:38:35.723  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.723  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.723  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fecf1c removed from the list
09-30 09:38:35.723  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 09:38:35.723  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.723  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.723  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.723  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 09:38:35.723  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95a108f removed from the list
09-30 09:38:35.724  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.724  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb7c108 added. We now have 3 listener(s)
,09-30 09:38:35.725  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.725  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.725  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.725  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.726  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3dd0a1 added. We now have 4 listener(s)
09-30 09:38:35.726  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:38:35.726  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 09:38:35.729  5896  5912 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 09:38:35.729  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.730  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:38:35.735  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 09:38:35.735  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:38:35.738  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:38:35.738  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:35.738  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:35.738  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:35.738  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:35.738  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:35.738  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:38:35.738  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:38:35.740  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:35.740  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 09:38:35.740  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.740  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2998287 added. We now have 4 listener(s)
09-30 09:38:35.741  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.742  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.742  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.742  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.742  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be5b4 added. We now have 5 listener(s)
09-30 09:38:35.742  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:38:35.742  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:38:35.742  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-30 09:38:35.742  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.742  5896  5916 D BtGatt.ScanManager: stopping BLe Batch
09-30 09:38:35.742  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:35.743  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:38:35.743  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 09:38:35.743  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 09:38:35.743  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:38:35.743  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 09:38:35.745  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:38:35.747  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 09:38:35.747  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 09:38:35.748  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 09:38:35.748  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:38:35.748  5896  5916 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 09:38:35.751  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 09:38:35.752  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 09:38:35.752  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 09:38:35.754  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 09:38:35.754  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:38:35.755  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 09:38:35.756  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 09:38:35.756  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-30 09:38:35.756  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 09:38:35.756  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 09:38:35.757  5617  5663 D BluetoothAdapter: STATE_ON
,09-30 09:38:35.759  5896  5934 D BtGatt.GattService: registerClient() - UUID=17304aa3-0f55-4126-8def-0297ba899769
,09-30 09:38:35.760  5896  5912 D BtGatt.GattService: onClientRegistered() - UUID=17304aa3-0f55-4126-8def-0297ba899769, clientIf=5
,09-30 09:38:35.760  5617  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 09:38:35.761  5896  5926 D BtGatt.GattService: start scan with filters
,09-30 09:38:35.763  5896  5916 D BtGatt.ScanManager: handling starting scan
09-30 09:38:35.763  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 09:38:35.763  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 09:38:35.763  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:38:35.763  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 09:38:35.763  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-30 09:38:35.764  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 09:38:35.764  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 09:38:35.766  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:38:35.767  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 09:38:35.767  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 09:38:35.768  5896  5912 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 09:38:35.768  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.768  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 09:38:35.768  5896  5916 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 09:38:35.771  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:38:35.771  5617  5663 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-30 09:38:35.771  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:38:35.771  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 09:38:35.771  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:38:35.771  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:38:35.771  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.772  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 09:38:35.772  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.772  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 09:38:35.772  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb7c108 removed from the list
09-30 09:38:35.772  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.772  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3dd0a1 removed from the list
09-30 09:38:35.772  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:38:35.772  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 09:38:35.773  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.773  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 09:38:35.773  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.773  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 09:38:35.775  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 09:38:35.775  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.775  5896  5916 D BtGatt.ScanManager: Starting BLE batch scan
09-30 09:38:35.775  5896  5916 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 09:38:35.775  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.775  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:38:35.775  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.775  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3dd0a1 not in the list
09-30 09:38:35.775  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 09:38:35.775  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 09:38:35.775  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 09:38:35.775  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 09:38:35.775  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 09:38:35.776  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:38:35.776  5896  5934 D BtGatt.GattService: stopScan() - queue size =1
,09-30 09:38:35.777  5896  5926 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 09:38:35.777  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 09:38:35.777  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 09:38:35.778  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 09:38:35.778  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:38:35.778  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 09:38:35.778  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 09:38:35.778  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 09:38:35.778  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 09:38:35.781  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 09:38:35.781  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 09:38:35.781  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 09:38:35.781  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 09:38:35.781  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 09:38:35.782  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.783  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 09:38:35.783  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.783  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.783  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:38:35.783  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be5b4 removed from the list
09-30 09:38:35.783  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:38:35.784  5896  5912 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 09:38:35.784  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 09:38:35.784  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:38:35.784  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.784  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:38:35.784  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.784  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.784  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 09:38:35.784  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2998287 removed from the list
09-30 09:38:35.785  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.785  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdba920 added. We now have 3 listener(s)
09-30 09:38:35.786  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.786  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.786  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.787  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.787  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cef2d9 added. We now have 4 listener(s)
09-30 09:38:35.787  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:38:35.789  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 09:38:35.789  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 09:38:35.789  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:38:35.792  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:38:35.795  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-30 09:38:35.795  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.795  5896  5916 D BtGatt.ScanManager: stopping BLe Batch
09-30 09:38:35.795  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:38:35.795  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:35.795  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:35.795  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:35.795  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:35.795  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:35.795  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:38:35.795  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:38:35.797  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:38:35.797  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:38:35.798  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.798  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3263b7f added. We now have 4 listener(s)
09-30 09:38:35.799  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.799  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.799  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.799  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.799  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2374c added. We now have 5 listener(s)
09-30 09:38:35.799  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:38:35.799  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 09:38:35.799  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 09:38:35.799  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 09:38:35.799  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:35.799  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:38:35.799  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 09:38:35.800  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 09:38:35.800  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.801  5896  5916 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 09:38:35.802  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:38:35.802  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 09:38:35.803  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 09:38:35.805  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 09:38:35.805  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 09:38:35.805  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.806  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 09:38:35.806  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 09:38:35.808  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 09:38:35.808  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 09:38:35.808  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 09:38:35.808  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 09:38:35.808  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 09:38:35.809  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:38:35.810  5896  5907 D BtGatt.GattService: registerClient() - UUID=3d83e747-3e27-4a89-97c8-8611a373eb3b
09-30 09:38:35.811  5896  5912 D BtGatt.GattService: onClientRegistered() - UUID=3d83e747-3e27-4a89-97c8-8611a373eb3b, clientIf=5
09-30 09:38:35.811  5617  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 09:38:35.811  5896  5906 D BtGatt.GattService: start scan with filters
,09-30 09:38:35.813  5896  5916 D BtGatt.ScanManager: handling starting scan
09-30 09:38:35.813  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 09:38:35.813  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-30 09:38:35.813  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 09:38:35.813  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 09:38:35.813  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 09:38:35.814  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 09:38:35.814  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 09:38:35.816  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 09:38:35.816  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 09:38:35.816  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 09:38:35.817  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 09:38:35.818  5896  5912 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 09:38:35.818  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.818  5896  5916 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 09:38:35.821  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:38:35.821  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:38:35.821  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:38:35.821  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:38:35.821  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.821  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 09:38:35.821  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.821  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 09:38:35.821  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdba920 removed from the list
09-30 09:38:35.821  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.821  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cef2d9 removed from the list
09-30 09:38:35.821  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:38:35.821  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:38:35.822  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.822  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 09:38:35.822  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.822  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 09:38:35.823  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.823  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:38:35.823  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.823  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cef2d9 not in the list
09-30 09:38:35.824  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 09:38:35.824  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 09:38:35.824  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 09:38:35.824  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 09:38:35.824  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 09:38:35.824  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 09:38:35.824  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.824  5896  5916 D BtGatt.ScanManager: Starting BLE batch scan
09-30 09:38:35.824  5896  5916 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 09:38:35.825  5617  5663 D BluetoothAdapter: STATE_ON
09-30 09:38:35.825  5896  5933 D BtGatt.GattService: stopScan() - queue size =1
09-30 09:38:35.826  5896  5913 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 09:38:35.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 09:38:35.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 09:38:35.826  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 09:38:35.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 09:38:35.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 09:38:35.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 09:38:35.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 09:38:35.826  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 09:38:35.827  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:38:35.827  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 09:38:35.827  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 09:38:35.827  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 09:38:35.827  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 09:38:35.830  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:38:35.830  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:38:35.830  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.831  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.831  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2374c removed from the list
09-30 09:38:35.831  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:38:35.831  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:38:35.831  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.831  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 09:38:35.831  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.831  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 09:38:35.831  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.831  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 09:38:35.831  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3263b7f removed from the list
09-30 09:38:35.831  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.832  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e617c38 added. We now have 3 listener(s)
09-30 09:38:35.833  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.833  5896  5912 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 09:38:35.833  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.833  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.833  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.833  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.833  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab2411 added. We now have 4 listener(s)
,09-30 09:38:35.834  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:38:35.834  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 09:38:35.838  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:38:35.839  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 09:38:35.839  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:38:35.843  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:38:35.843  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:38:35.843  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:38:35.843  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:38:35.843  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:38:35.843  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:35.843  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:38:35.843  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:38:35.845  5896  5912 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-30 09:38:35.845  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.845  5896  5916 D BtGatt.ScanManager: stopping BLe Batch
,09-30 09:38:35.845  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:38:35.845  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:38:35.845  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 09:38:35.845  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@821b77 added. We now have 4 listener(s)
09-30 09:38:35.847  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:38:35.847  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:38:35.847  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:38:35.847  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:38:35.847  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce23e4 added. We now have 5 listener(s)
09-30 09:38:35.847  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:38:35.847  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:35.847  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:38:35.847  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:38:35.847  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 09:38:35.847  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:38:35.848  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 09:38:35.848  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 09:38:35.848  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.848  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 09:38:35.848  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e617c38 removed from the list
09-30 09:38:35.848  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 09:38:35.848  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab2411 removed from the list
09-30 09:38:35.850  5896  5912 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 09:38:35.850  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 09:38:35.850  5896  5916 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 09:38:35.851  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:38:35.851  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
09-30 09:38:35.851  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 09:38:35.851  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.851  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.852  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.852  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:38:35.852  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.852  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab2411 not in the list
09-30 09:38:35.852  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.852  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.854  5896  5912 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 09:38:35.854  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 09:38:35.854  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 09:38:35.854  5896  5912 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 09:38:35.854  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 09:38:35.854  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce23e4 removed from the list
09-30 09:38:35.854  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 09:38:35.854  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 09:38:35.854  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 09:38:35.854  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 09:38:35.854  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 09:38:35.855  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@821b77 removed from the list
09-30 09:38:35.855  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-30 09:38:35.855  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-30 09:38:35.855  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-30 09:38:35.855  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:38:35.855  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-30 09:38:35.855  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 09:38:36.217  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 09:38:36.284  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 09:38:36.332  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 09:38:38.000  5617  5993 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 09:38:38.000  5617  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:38.796  5617  5993 W !!      : call onHalfStreamCopied
,09-30 09:38:38.796  5617  5993 I testCopyDataAndClose: closing input stream
,09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 09:38:39.569  5617  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 09:38:43.671  5617  5994 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
09-30 09:38:43.671  5617  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:45.671  5617  5663 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 188. Connection data: Peer properties: [null null].
09-30 09:38:45.671  5617  5663 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:45.671  5617  5663 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 188, name: My test thread name)
,09-30 09:38:45.751  5617  5994 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-30 09:38:45.752  5617  5994 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
09-30 09:38:45.752  5617  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187
,09-30 09:38:45.816  5617  5995 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 09:38:45.816  5617  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:45.884   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 09:38:45.884   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 09:38:47.442  5617  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 09:38:51.506  5617  5996 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-30 09:38:51.506  5617  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 09:38:51.506  5617  5996 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name). Connection data: Peer properties: [null null].
09-30 09:38:51.506  5617  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-30 09:38:51.507  5617  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-30 09:38:51.509  5617  5663 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 09:38:51.512  5617  5997 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 09:38:51.512  5617  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 09:38:51.512  5617  5997 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
09-30 09:38:51.513  5617  5997 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 09:38:51.513  5617  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 09:38:51.513  5617  5997 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-30 09:38:51.513  5617  5997 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 09:38:51.513  5617  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-30 09:38:51.519  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-30 09:38:51.519  5617  5663 I jxcore-log: 
09-30 09:38:51.519  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-30 09:38:51.519  5617  5663 I jxcore-log: 
09-30 09:38:51.519  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-30 09:38:51.519  5617  5663 I jxcore-log: 
09-30 09:38:51.520  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-30 09:38:51.520  5617  5663 I jxcore-log: 
09-30 09:38:51.521  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Total duration:  103494'
09-30 09:38:51.521  5617  5663 I jxcore-log: 
,09-30 09:38:51.523  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Failures: 
09-30 09:38:51.523  5617  5663 I jxcore-log:  IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-30 09:38:51.523  5617  5663 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-30 09:38:51.523  5617  5663 I jxcore-log:      but: was ""
09-30 09:38:51.523  5617  5663 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-30 09:38:51.523  5617  5663 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-30 09:38:51.523  5617  5663 I jxcore-log:      but: was ""
09-30 09:38:51.523  5617  5663 I jxcore-log: '
09-30 09:38:51.523  5617  5663 I jxcore-log: 
09-30 09:38:51.524  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-30 09:38:51.524  5617  5663 I jxcore-log: 
09-30 09:38:51.525  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-30 09:38:51.525  5617  5663 I jxcore-log: 
,09-30 09:38:51.528  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.528  5617  5663 I jxcore-log: 
,09-30 09:38:51.529  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.529  5617  5663 I jxcore-log: 
09-30 09:38:51.529  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.529  5617  5663 I jxcore-log: 
09-30 09:38:51.529  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.529  5617  5663 I jxcore-log: 
,09-30 09:38:51.530  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 09:38:51.530  5617  5663 I jxcore-log: 
09-30 09:38:51.530  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 09:38:51.530  5617  5663 I jxcore-log: 
09-30 09:38:51.530  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.530  5617  5663 I jxcore-log: 
09-30 09:38:51.531  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.531  5617  5663 I jxcore-log: 
,09-30 09:38:51.531  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 09:38:51.531  5617  5663 I jxcore-log: 
09-30 09:38:51.531  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 09:38:51.531  5617  5663 I jxcore-log: 
09-30 09:38:51.531  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 09:38:51.531  5617  5663 I jxcore-log: 
09-30 09:38:51.532  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.532  5617  5663 I jxcore-log: 
09-30 09:38:51.532  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.532  5617  5663 I jxcore-log: 
09-30 09:38:51.532  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.532  5617  5663 I jxcore-log: 
,09-30 09:38:51.532  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.532  5617  5663 I jxcore-log: 
09-30 09:38:51.533  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.533  5617  5663 I jxcore-log: 
09-30 09:38:51.533  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.533  5617  5663 I jxcore-log: 
09-30 09:38:51.533  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.533  5617  5663 I jxcore-log: 
09-30 09:38:51.534  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.534  5617  5663 I jxcore-log: 
09-30 09:38:51.534  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.534  5617  5663 I jxcore-log: 
09-30 09:38:51.534  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.534  5617  5663 I jxcore-log: 
,09-30 09:38:51.534  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.534  5617  5663 I jxcore-log: 
09-30 09:38:51.536  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.536  5617  5663 I jxcore-log: 
09-30 09:38:51.536  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.536  5617  5663 I jxcore-log: 
,09-30 09:38:51.536  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.536  5617  5663 I jxcore-log: 
09-30 09:38:51.537  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.537  5617  5663 I jxcore-log: 
,09-30 09:38:51.537  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.537  5617  5663 I jxcore-log: 
09-30 09:38:51.537  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.537  5617  5663 I jxcore-log: 
09-30 09:38:51.537  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.537  5617  5663 I jxcore-log: 
09-30 09:38:51.538  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.538  5617  5663 I jxcore-log: 
09-30 09:38:51.538  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.538  5617  5663 I jxcore-log: 
,09-30 09:38:51.538  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.538  5617  5663 I jxcore-log: 
09-30 09:38:51.538  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.538  5617  5663 I jxcore-log: 
09-30 09:38:51.538  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.538  5617  5663 I jxcore-log: 
09-30 09:38:51.539  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.539  5617  5663 I jxcore-log: 
09-30 09:38:51.539  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.539  5617  5663 I jxcore-log: 
09-30 09:38:51.539  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.539  5617  5663 I jxcore-log: 
09-30 09:38:51.539  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.539  5617  5663 I jxcore-log: 
,09-30 09:38:51.539  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 09:38:51.539  5617  5663 I jxcore-log: 
09-30 09:38:51.540  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.540  5617  5663 I jxcore-log: 
09-30 09:38:51.540  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 09:38:51.540  5617  5663 I jxcore-log: 
09-30 09:38:51.540  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.540  5617  5663 I jxcore-log: 
09-30 09:38:51.540  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.540  5617  5663 I jxcore-log: 
,09-30 09:38:51.541  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.541  5617  5663 I jxcore-log: 
09-30 09:38:51.541  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.541  5617  5663 I jxcore-log: 
09-30 09:38:51.541  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.541  5617  5663 I jxcore-log: 
09-30 09:38:51.541  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:38:51.541  5617  5663 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-30 09:38:51.542  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.542  5617  5663 I jxcore-log: 
09-30 09:38:51.542  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.542  5617  5663 I jxcore-log: 
09-30 09:38:51.542  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 09:38:51.542  5617  5663 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-30 09:38:51.542  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:38:51.542  5617  5663 I jxcore-log: 
09-30 09:38:51.542  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 09:38:51.542  5617  5663 I jxcore-log: 
,09-30 09:38:51.543  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 09:38:51.543  5617  5663 I jxcore-log: 
09-30 09:38:51.543  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 09:38:51.543  5617  5663 I jxcore-log: 
09-30 09:38:51.544  5617  5617 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-30 09:38:51.548  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-30 09:38:51.548  5617  5663 I jxcore-log: 
09-30 09:38:51.548  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - WARN testUtils: 'myNameCallback not set!'
09-30 09:38:51.548  5617  5663 I jxcore-log: 
,09-30 09:38:51.550  5617  5663 I jxcore-log: 2016-09-30 13:38:51 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-30 09:38:51.550  5617  5663 I jxcore-log: 
,09-30 09:38:53.533  5617  5663 I jxcore-log: 2016-09-30 13:38:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-30 09:38:53.533  5617  5663 I jxcore-log: 
,09-30 09:38:53.858  5617  5663 I jxcore-log: 2016-09-30 13:38:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-30 09:38:53.858  5617  5663 I jxcore-log: 
,09-30 09:38:53.873  5617  5663 I jxcore-log: 2016-09-30 13:38:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-30 09:38:53.873  5617  5663 I jxcore-log: 
,09-30 09:38:54.957  5617  5663 I jxcore-log: 2016-09-30 13:38:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-30 09:38:54.957  5617  5663 I jxcore-log: 
,09-30 09:38:55.119  5617  5663 I jxcore-log: 2016-09-30 13:38:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-30 09:38:55.119  5617  5663 I jxcore-log: 
,09-30 09:38:55.124  5617  5663 I jxcore-log: 2016-09-30 13:38:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-30 09:38:55.124  5617  5663 I jxcore-log: 
,09-30 09:38:55.128  5617  5663 I jxcore-log: 2016-09-30 13:38:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-30 09:38:55.128  5617  5663 I jxcore-log: 
,09-30 09:38:55.669  5617  5663 I jxcore-log: 2016-09-30 13:38:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-30 09:38:55.669  5617  5663 I jxcore-log: 
,09-30 09:38:55.720  5617  5663 I jxcore-log: 2016-09-30 13:38:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-30 09:38:55.720  5617  5663 I jxcore-log: 
,09-30 09:38:55.732  5617  5663 I jxcore-log: 2016-09-30 13:38:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-30 09:38:55.732  5617  5663 I jxcore-log: 
,09-30 09:38:55.737  5617  5663 I jxcore-log: 2016-09-30 13:38:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-30 09:38:55.737  5617  5663 I jxcore-log: 
,09-30 09:38:56.011  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-30 09:38:56.011  5617  5663 I jxcore-log: 
,09-30 09:38:56.132  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-30 09:38:56.132  5617  5663 I jxcore-log: 
,09-30 09:38:56.363  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-30 09:38:56.363  5617  5663 I jxcore-log: 
,09-30 09:38:56.373  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-30 09:38:56.373  5617  5663 I jxcore-log: 
,09-30 09:38:56.377  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-30 09:38:56.377  5617  5663 I jxcore-log: 
,09-30 09:38:56.510  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-30 09:38:56.510  5617  5663 I jxcore-log: 
,09-30 09:38:56.518  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-30 09:38:56.518  5617  5663 I jxcore-log: 
,09-30 09:38:56.544  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-30 09:38:56.544  5617  5663 I jxcore-log: 
,09-30 09:38:56.578  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-30 09:38:56.578  5617  5663 I jxcore-log: 
,09-30 09:38:56.584  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-30 09:38:56.584  5617  5663 I jxcore-log: 
,09-30 09:38:56.589  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-30 09:38:56.589  5617  5663 I jxcore-log: 
,09-30 09:38:56.603  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-30 09:38:56.603  5617  5663 I jxcore-log: 
,09-30 09:38:56.606  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-30 09:38:56.606  5617  5663 I jxcore-log: 
,09-30 09:38:56.612  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-30 09:38:56.612  5617  5663 I jxcore-log: 
,09-30 09:38:56.616  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-30 09:38:56.616  5617  5663 I jxcore-log: 
,09-30 09:38:56.628  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-30 09:38:56.628  5617  5663 I jxcore-log: 
,09-30 09:38:56.648  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-30 09:38:56.648  5617  5663 I jxcore-log: 
,09-30 09:38:56.656  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-30 09:38:56.656  5617  5663 I jxcore-log: 
,09-30 09:38:56.666  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-30 09:38:56.666  5617  5663 I jxcore-log: 
,09-30 09:38:56.675  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-30 09:38:56.675  5617  5663 I jxcore-log: 
,09-30 09:38:56.685  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-30 09:38:56.685  5617  5663 I jxcore-log: 
,09-30 09:38:56.694  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-30 09:38:56.694  5617  5663 I jxcore-log: 
,09-30 09:38:56.698  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-30 09:38:56.698  5617  5663 I jxcore-log: 
,09-30 09:38:56.716  5617  5663 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-30 09:38:56.717  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - INFO testUtils: 'BLE multiple advertisement supported'
09-30 09:38:56.717  5617  5663 I jxcore-log: 
,09-30 09:38:56.821  5617  5663 I jxcore-log: 2016-09-30 13:38:56 - DEBUG CoordinatedClient: 'connected to the test server'
09-30 09:38:56.821  5617  5663 I jxcore-log: 
,09-30 09:38:57.397  5617  5663 I jxcore-log: TAP version 13
09-30 09:38:57.397  5617  5663 I jxcore-log: 
,09-30 09:38:57.438  5617  5663 I jxcore-log: # setup
09-30 09:38:57.438  5617  5663 I jxcore-log: 
,09-30 09:38:58.211  5617  5663 I jxcore-log: # calling createNativeListener directly rejects
09-30 09:38:58.211  5617  5663 I jxcore-log: 
,09-30 09:38:58.792  5617  5663 I jxcore-log: 2016-09-30 13:38:58 - DEBUG createNativeListener: 'creating native server'
09-30 09:38:58.792  5617  5663 I jxcore-log: 
,09-30 09:38:58.798  5617  5663 I jxcore-log: 2016-09-30 13:38:58 - DEBUG createNativeListener: 'listening 47919'
09-30 09:38:58.798  5617  5663 I jxcore-log: 
,09-30 09:38:58.807  5617  5663 I jxcore-log: ok 1 Should throw
09-30 09:38:58.807  5617  5663 I jxcore-log: 
,09-30 09:38:58.818  5617  5663 I jxcore-log: # teardown
09-30 09:38:58.818  5617  5663 I jxcore-log: 
,09-30 09:38:59.728  5617  5663 I jxcore-log: # setup
09-30 09:38:59.728  5617  5663 I jxcore-log: 
,09-30 09:39:00.641  5617  5663 I jxcore-log: # emits incomingConnectionState
09-30 09:39:00.641  5617  5663 I jxcore-log: 
,09-30 09:39:00.814  5617  5663 I jxcore-log: 2016-09-30 13:39:00 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:00.814  5617  5663 I jxcore-log: 
,09-30 09:39:00.819  5617  5663 I jxcore-log: 2016-09-30 13:39:00 - DEBUG createNativeListener: 'listening 43066'
09-30 09:39:00.819  5617  5663 I jxcore-log: 
,09-30 09:39:00.831  5617  5663 I jxcore-log: 2016-09-30 13:39:00 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:00.831  5617  5663 I jxcore-log: 
,09-30 09:39:00.835  5617  5663 I jxcore-log: 2016-09-30 13:39:00 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:00.835  5617  5663 I jxcore-log: 
,09-30 09:39:00.844  5617  5663 I jxcore-log: 2016-09-30 13:39:00 - DEBUG createNativeListener: 'new mux'
09-30 09:39:00.844  5617  5663 I jxcore-log: 
,09-30 09:39:00.849  5617  5663 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-30 09:39:00.849  5617  5663 I jxcore-log: 
,09-30 09:39:00.870  5617  5663 I jxcore-log: 2016-09-30 13:39:00 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:00.870  5617  5663 I jxcore-log: 
,09-30 09:39:00.871  5617  5663 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-30 09:39:00.871  5617  5663 I jxcore-log: 
,09-30 09:39:00.877  5617  5663 I jxcore-log: # teardown
09-30 09:39:00.877  5617  5663 I jxcore-log: 
,09-30 09:39:00.884   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:01.867  5617  5663 I jxcore-log: # setup
09-30 09:39:01.867  5617  5663 I jxcore-log: 
,09-30 09:39:01.885   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:02.047  5617  5663 I jxcore-log: # emits routerPortConnectionFailed
09-30 09:39:02.047  5617  5663 I jxcore-log: 
,09-30 09:39:02.886   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:03.109  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:03.109  5617  5663 I jxcore-log: 
,09-30 09:39:03.114  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'listening 39295'
09-30 09:39:03.114  5617  5663 I jxcore-log: 
,09-30 09:39:03.122  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:03.122  5617  5663 I jxcore-log: 
,09-30 09:39:03.124  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:03.124  5617  5663 I jxcore-log: 
,09-30 09:39:03.126  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'new mux'
09-30 09:39:03.126  5617  5663 I jxcore-log: 
,09-30 09:39:03.152  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:03.152  5617  5663 I jxcore-log: 
,09-30 09:39:03.155  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:03.155  5617  5663 I jxcore-log: 
,09-30 09:39:03.159  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: ' $c@net.js:837:7
09-30 09:39:03.159  5617  5663 I jxcore-log: $09@net.js:829:13
09-30 09:39:03.159  5617  5663 I jxcore-log: '
09-30 09:39:03.159  5617  5663 I jxcore-log: 
,09-30 09:39:03.160  5617  5663 I jxcore-log: ok 4 tried to connect to right port
09-30 09:39:03.160  5617  5663 I jxcore-log: 
09-30 09:39:03.161  5617  5663 I jxcore-log: ok 5 failed due to refused connection
09-30 09:39:03.161  5617  5663 I jxcore-log: 
,09-30 09:39:03.162  5617  5663 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-30 09:39:03.162  5617  5663 I jxcore-log: 
,09-30 09:39:03.165  5617  5663 I jxcore-log: # teardown
09-30 09:39:03.165  5617  5663 I jxcore-log: 
,09-30 09:39:03.168  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:03.168  5617  5663 I jxcore-log: 
,09-30 09:39:03.355  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'mux close'
09-30 09:39:03.355  5617  5663 I jxcore-log: 
,09-30 09:39:03.360  5617  5663 I jxcore-log: 2016-09-30 13:39:03 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:03.360  5617  5663 I jxcore-log: 
,09-30 09:39:03.372  5617  5663 I jxcore-log: # setup
09-30 09:39:03.372  5617  5663 I jxcore-log: 
,09-30 09:39:03.452   927  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 09:39:03.855  5617  5663 I jxcore-log: # native server connections all up
09-30 09:39:03.855  5617  5663 I jxcore-log: 
,09-30 09:39:03.887   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:04.624  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:04.624  5617  5663 I jxcore-log: 
,09-30 09:39:04.631  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'listening 49593'
09-30 09:39:04.631  5617  5663 I jxcore-log: 
,09-30 09:39:04.642  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:04.642  5617  5663 I jxcore-log: 
,09-30 09:39:04.644  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:04.644  5617  5663 I jxcore-log: 
,09-30 09:39:04.646  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'new mux'
09-30 09:39:04.646  5617  5663 I jxcore-log: 
,09-30 09:39:04.678  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:04.678  5617  5663 I jxcore-log: 
,09-30 09:39:04.682  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:04.682  5617  5663 I jxcore-log: 
,09-30 09:39:04.685  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:04.685  5617  5663 I jxcore-log: 
,09-30 09:39:04.689  5617  5663 I jxcore-log: 2016-09-30 13:39:04 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:04.689  5617  5663 I jxcore-log: 
,09-30 09:39:04.714  5617  5663 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-30 09:39:04.714  5617  5663 I jxcore-log: 
,09-30 09:39:04.715  5617  5663 I jxcore-log: ok 8 Send/recvd #1 should be same
09-30 09:39:04.715  5617  5663 I jxcore-log: 
,09-30 09:39:04.718  5617  5663 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-30 09:39:04.718  5617  5663 I jxcore-log: 
09-30 09:39:04.718  5617  5663 I jxcore-log: ok 10 Send/recvd #2 should be same
09-30 09:39:04.718  5617  5663 I jxcore-log: 
,09-30 09:39:04.722  5617  5663 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-30 09:39:04.722  5617  5663 I jxcore-log: 
,09-30 09:39:04.731  5617  5663 I jxcore-log: # teardown
09-30 09:39:04.731  5617  5663 I jxcore-log: 
,09-30 09:39:04.888   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:05.246  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:05.246  5617  5663 I jxcore-log: 
,09-30 09:39:05.250  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:05.250  5617  5663 I jxcore-log: 
,09-30 09:39:05.252  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'mux close'
09-30 09:39:05.252  5617  5663 I jxcore-log: 
,09-30 09:39:05.258  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:05.258  5617  5663 I jxcore-log: 
,09-30 09:39:05.272  5617  5663 I jxcore-log: # setup
09-30 09:39:05.272  5617  5663 I jxcore-log: 
,09-30 09:39:05.424  5617  5663 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-30 09:39:05.424  5617  5663 I jxcore-log: 
,09-30 09:39:05.463  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:05.463  5617  5663 I jxcore-log: 
,09-30 09:39:05.468  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'listening 49255'
09-30 09:39:05.468  5617  5663 I jxcore-log: 
,09-30 09:39:05.476  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:05.476  5617  5663 I jxcore-log: 
,09-30 09:39:05.477  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:05.477  5617  5663 I jxcore-log: 
09-30 09:39:05.481  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new mux'
09-30 09:39:05.481  5617  5663 I jxcore-log: 
,09-30 09:39:05.494  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:05.494  5617  5663 I jxcore-log: 
,09-30 09:39:05.496  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:05.496  5617  5663 I jxcore-log: 
,09-30 09:39:05.508  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:05.508  5617  5663 I jxcore-log: 
,09-30 09:39:05.519  5617  5663 I jxcore-log: ok 12 socket shouldn't close until after stream
09-30 09:39:05.519  5617  5663 I jxcore-log: 
,09-30 09:39:05.520  5617  5663 I jxcore-log: ok 13 incoming remains open
09-30 09:39:05.520  5617  5663 I jxcore-log: 
,09-30 09:39:05.527  5617  5663 I jxcore-log: # teardown
09-30 09:39:05.527  5617  5663 I jxcore-log: 
,09-30 09:39:05.559  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'mux close'
09-30 09:39:05.559  5617  5663 I jxcore-log: 
,09-30 09:39:05.562  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:05.562  5617  5663 I jxcore-log: 
,09-30 09:39:05.569  5617  5663 I jxcore-log: # setup
09-30 09:39:05.569  5617  5663 I jxcore-log: 
,09-30 09:39:05.651  5617  5663 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-30 09:39:05.651  5617  5663 I jxcore-log: 
,09-30 09:39:05.715  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:05.715  5617  5663 I jxcore-log: 
,09-30 09:39:05.721  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'listening 41114'
09-30 09:39:05.721  5617  5663 I jxcore-log: 
,09-30 09:39:05.728  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:05.728  5617  5663 I jxcore-log: 
,09-30 09:39:05.730  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:05.730  5617  5663 I jxcore-log: 
09-30 09:39:05.731  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new mux'
09-30 09:39:05.731  5617  5663 I jxcore-log: 
,09-30 09:39:05.743  5617  5663 I jxcore-log: ok 14 we should not have gotten an error
09-30 09:39:05.743  5617  5663 I jxcore-log: 
,09-30 09:39:05.748  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:05.748  5617  5663 I jxcore-log: 
,09-30 09:39:05.753  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:05.753  5617  5663 I jxcore-log: 
,09-30 09:39:05.762  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:05.762  5617  5663 I jxcore-log: 
,09-30 09:39:05.764  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:05.764  5617  5663 I jxcore-log: 
,09-30 09:39:05.771  5617  5663 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-30 09:39:05.771  5617  5663 I jxcore-log: 
,09-30 09:39:05.772  5617  5663 I jxcore-log: ok 16 incoming is cleaned up
09-30 09:39:05.772  5617  5663 I jxcore-log: 
,09-30 09:39:05.780  5617  5663 I jxcore-log: # teardown
09-30 09:39:05.780  5617  5663 I jxcore-log: 
,09-30 09:39:05.814  5617  5663 I jxcore-log: # setup
09-30 09:39:05.814  5617  5663 I jxcore-log: 
,09-30 09:39:05.852  5617  5663 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-30 09:39:05.852  5617  5663 I jxcore-log: 
,09-30 09:39:05.889   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 09:39:05.928  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:05.928  5617  5663 I jxcore-log: 
,09-30 09:39:05.932  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'listening 41038'
09-30 09:39:05.932  5617  5663 I jxcore-log: 
,09-30 09:39:05.938  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:05.938  5617  5663 I jxcore-log: 
,09-30 09:39:05.940  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:05.940  5617  5663 I jxcore-log: 
,09-30 09:39:05.942  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new mux'
09-30 09:39:05.942  5617  5663 I jxcore-log: 
,09-30 09:39:05.955  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:05.955  5617  5663 I jxcore-log: 
,09-30 09:39:05.958  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:05.958  5617  5663 I jxcore-log: 
,09-30 09:39:05.972  5617  5663 I jxcore-log: 2016-09-30 13:39:05 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:05.972  5617  5663 I jxcore-log: 
,09-30 09:39:05.981  5617  5663 I jxcore-log: ok 17 stream was closed
09-30 09:39:05.981  5617  5663 I jxcore-log: 
,09-30 09:39:05.982  5617  5663 I jxcore-log: ok 18 incoming should survive
09-30 09:39:05.982  5617  5663 I jxcore-log: 
09-30 09:39:05.982  5617  5663 I jxcore-log: ok 19 mux should have no streams
09-30 09:39:05.982  5617  5663 I jxcore-log: 
,09-30 09:39:05.989  5617  5663 I jxcore-log: # teardown
09-30 09:39:05.989  5617  5663 I jxcore-log: 
,09-30 09:39:06.050  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.050  5617  5663 I jxcore-log: 
,09-30 09:39:06.071  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.071  5617  5663 I jxcore-log: 
,09-30 09:39:06.085  5617  5663 I jxcore-log: # setup
09-30 09:39:06.085  5617  5663 I jxcore-log: 
,09-30 09:39:06.132  5617  5663 I jxcore-log: # native server - closing the whole server cleans everything up
09-30 09:39:06.132  5617  5663 I jxcore-log: 
,09-30 09:39:06.210  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:06.210  5617  5663 I jxcore-log: 
,09-30 09:39:06.217  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'listening 39296'
09-30 09:39:06.217  5617  5663 I jxcore-log: 
,09-30 09:39:06.225  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.225  5617  5663 I jxcore-log: 
,09-30 09:39:06.227  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.227  5617  5663 I jxcore-log: 
,09-30 09:39:06.229  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.229  5617  5663 I jxcore-log: 
,09-30 09:39:06.239  5617  5663 I jxcore-log: ok 20 we should not have gotten an error
09-30 09:39:06.239  5617  5663 I jxcore-log: 
,09-30 09:39:06.245  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.245  5617  5663 I jxcore-log: 
,09-30 09:39:06.248  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.248  5617  5663 I jxcore-log: 
,09-30 09:39:06.256  5617  5663 I jxcore-log: ok 21 Buffers are identical
09-30 09:39:06.256  5617  5663 I jxcore-log: 
,09-30 09:39:06.257  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.257  5617  5663 I jxcore-log: 
,09-30 09:39:06.260  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.260  5617  5663 I jxcore-log: 
09-30 09:39:06.262  5617  5663 I jxcore-log: ok 22 native server is nulled out
09-30 09:39:06.262  5617  5663 I jxcore-log: 
09-30 09:39:06.262  5617  5663 I jxcore-log: ok 23 native server should be closed
09-30 09:39:06.262  5617  5663 I jxcore-log: 
09-30 09:39:06.262  5617  5663 I jxcore-log: ok 24 incoming has been removed
09-30 09:39:06.262  5617  5663 I jxcore-log: 
09-30 09:39:06.263  5617  5663 I jxcore-log: ok 25 Incoming should be done
09-30 09:39:06.263  5617  5663 I jxcore-log: 
,09-30 09:39:06.263  5617  5663 I jxcore-log: ok 26 The mux object should be closed
09-30 09:39:06.263  5617  5663 I jxcore-log: 
09-30 09:39:06.263  5617  5663 I jxcore-log: ok 27 The mux stream should be closed
09-30 09:39:06.263  5617  5663 I jxcore-log: 
,09-30 09:39:06.265  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.265  5617  5663 I jxcore-log: 
,09-30 09:39:06.277  5617  5663 I jxcore-log: # teardown
09-30 09:39:06.277  5617  5663 I jxcore-log: 
,09-30 09:39:06.315  5617  5663 I jxcore-log: # setup
09-30 09:39:06.315  5617  5663 I jxcore-log: 
,09-30 09:39:06.352  5617  5663 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-30 09:39:06.352  5617  5663 I jxcore-log: 
,09-30 09:39:06.403  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:06.403  5617  5663 I jxcore-log: 
,09-30 09:39:06.407  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'listening 38258'
09-30 09:39:06.407  5617  5663 I jxcore-log: 
,09-30 09:39:06.432  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.432  5617  5663 I jxcore-log: 
,09-30 09:39:06.433  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.433  5617  5663 I jxcore-log: 
,09-30 09:39:06.434  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.434  5617  5663 I jxcore-log: 
,09-30 09:39:06.437  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.437  5617  5663 I jxcore-log: 
,09-30 09:39:06.438  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.438  5617  5663 I jxcore-log: 
09-30 09:39:06.439  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.439  5617  5663 I jxcore-log: 
,09-30 09:39:06.441  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.441  5617  5663 I jxcore-log: 
,09-30 09:39:06.442  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.442  5617  5663 I jxcore-log: 
,09-30 09:39:06.444  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.444  5617  5663 I jxcore-log: 
,09-30 09:39:06.447  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.447  5617  5663 I jxcore-log: 
,09-30 09:39:06.448  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.448  5617  5663 I jxcore-log: 
,09-30 09:39:06.450  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.450  5617  5663 I jxcore-log: 
09-30 09:39:06.452  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.452  5617  5663 I jxcore-log: 
09-30 09:39:06.453  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.453  5617  5663 I jxcore-log: 
,09-30 09:39:06.456  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.456  5617  5663 I jxcore-log: 
,09-30 09:39:06.465  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.465  5617  5663 I jxcore-log: 
,09-30 09:39:06.466  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.466  5617  5663 I jxcore-log: 
,09-30 09:39:06.467  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.467  5617  5663 I jxcore-log: 
,09-30 09:39:06.470  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.470  5617  5663 I jxcore-log: 
,09-30 09:39:06.470  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.470  5617  5663 I jxcore-log: 
,09-30 09:39:06.471  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.471  5617  5663 I jxcore-log: 
,09-30 09:39:06.474  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.474  5617  5663 I jxcore-log: 
,09-30 09:39:06.474  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.474  5617  5663 I jxcore-log: 
09-30 09:39:06.475  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.475  5617  5663 I jxcore-log: 
,09-30 09:39:06.476  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.476  5617  5663 I jxcore-log: 
09-30 09:39:06.476  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.476  5617  5663 I jxcore-log: 
09-30 09:39:06.477  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.477  5617  5663 I jxcore-log: 
,09-30 09:39:06.478  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:06.478  5617  5663 I jxcore-log: 
,09-30 09:39:06.478  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:06.478  5617  5663 I jxcore-log: 
09-30 09:39:06.479  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new mux'
09-30 09:39:06.479  5617  5663 I jxcore-log: 
,09-30 09:39:06.534  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.534  5617  5663 I jxcore-log: 
,09-30 09:39:06.536  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.536  5617  5663 I jxcore-log: 
,09-30 09:39:06.538  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.538  5617  5663 I jxcore-log: 
,09-30 09:39:06.539  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.539  5617  5663 I jxcore-log: 
,09-30 09:39:06.540  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.540  5617  5663 I jxcore-log: 
,09-30 09:39:06.541  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.541  5617  5663 I jxcore-log: 
,09-30 09:39:06.542  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.542  5617  5663 I jxcore-log: 
,09-30 09:39:06.543  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.543  5617  5663 I jxcore-log: 
,09-30 09:39:06.544  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.544  5617  5663 I jxcore-log: 
,09-30 09:39:06.545  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.545  5617  5663 I jxcore-log: 
,09-30 09:39:06.546  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.546  5617  5663 I jxcore-log: 
,09-30 09:39:06.547  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.547  5617  5663 I jxcore-log: 
,09-30 09:39:06.547  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.547  5617  5663 I jxcore-log: 
,09-30 09:39:06.548  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.548  5617  5663 I jxcore-log: 
,09-30 09:39:06.549  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.549  5617  5663 I jxcore-log: 
,09-30 09:39:06.550  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.550  5617  5663 I jxcore-log: 
,09-30 09:39:06.551  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.551  5617  5663 I jxcore-log: 
,09-30 09:39:06.552  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.552  5617  5663 I jxcore-log: 
,09-30 09:39:06.553  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.553  5617  5663 I jxcore-log: 
,09-30 09:39:06.554  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.554  5617  5663 I jxcore-log: 
,09-30 09:39:06.554  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.554  5617  5663 I jxcore-log: 
,09-30 09:39:06.555  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.555  5617  5663 I jxcore-log: 
,09-30 09:39:06.556  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.556  5617  5663 I jxcore-log: 
09-30 09:39:06.557  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.557  5617  5663 I jxcore-log: 
,09-30 09:39:06.558  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.558  5617  5663 I jxcore-log: 
,09-30 09:39:06.559  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.559  5617  5663 I jxcore-log: 
09-30 09:39:06.560  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.560  5617  5663 I jxcore-log: 
,09-30 09:39:06.560  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.560  5617  5663 I jxcore-log: 
,09-30 09:39:06.561  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.561  5617  5663 I jxcore-log: 
09-30 09:39:06.562  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.562  5617  5663 I jxcore-log: 
09-30 09:39:06.562  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.562  5617  5663 I jxcore-log: 
,09-30 09:39:06.563  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.563  5617  5663 I jxcore-log: 
,09-30 09:39:06.564  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.564  5617  5663 I jxcore-log: 
,09-30 09:39:06.565  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.565  5617  5663 I jxcore-log: 
,09-30 09:39:06.566  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.566  5617  5663 I jxcore-log: 
09-30 09:39:06.567  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.567  5617  5663 I jxcore-log: 
,09-30 09:39:06.567  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.567  5617  5663 I jxcore-log: 
,09-30 09:39:06.568  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.568  5617  5663 I jxcore-log: 
09-30 09:39:06.569  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.569  5617  5663 I jxcore-log: 
,09-30 09:39:06.569  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.569  5617  5663 I jxcore-log: 
,09-30 09:39:06.570  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.570  5617  5663 I jxcore-log: 
,09-30 09:39:06.571  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.571  5617  5663 I jxcore-log: 
09-30 09:39:06.572  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.572  5617  5663 I jxcore-log: 
,09-30 09:39:06.573  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.573  5617  5663 I jxcore-log: 
,09-30 09:39:06.573  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.573  5617  5663 I jxcore-log: 
,09-30 09:39:06.574  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.574  5617  5663 I jxcore-log: 
09-30 09:39:06.575  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.575  5617  5663 I jxcore-log: 
,09-30 09:39:06.575  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.575  5617  5663 I jxcore-log: 
,09-30 09:39:06.582  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.582  5617  5663 I jxcore-log: 
,09-30 09:39:06.584  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.584  5617  5663 I jxcore-log: 
,09-30 09:39:06.584  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.584  5617  5663 I jxcore-log: 
,09-30 09:39:06.585  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.585  5617  5663 I jxcore-log: 
09-30 09:39:06.586  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.586  5617  5663 I jxcore-log: 
,09-30 09:39:06.587  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.587  5617  5663 I jxcore-log: 
,09-30 09:39:06.587  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.587  5617  5663 I jxcore-log: 
09-30 09:39:06.588  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.588  5617  5663 I jxcore-log: 
,09-30 09:39:06.589  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.589  5617  5663 I jxcore-log: 
09-30 09:39:06.590  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.590  5617  5663 I jxcore-log: 
,09-30 09:39:06.590  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.590  5617  5663 I jxcore-log: 
,09-30 09:39:06.591  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.591  5617  5663 I jxcore-log: 
09-30 09:39:06.592  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.592  5617  5663 I jxcore-log: 
,09-30 09:39:06.592  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.592  5617  5663 I jxcore-log: 
09-30 09:39:06.593  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.593  5617  5663 I jxcore-log: 
,09-30 09:39:06.594  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.594  5617  5663 I jxcore-log: 
,09-30 09:39:06.594  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.594  5617  5663 I jxcore-log: 
,09-30 09:39:06.595  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.595  5617  5663 I jxcore-log: 
09-30 09:39:06.596  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.596  5617  5663 I jxcore-log: 
09-30 09:39:06.597  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.597  5617  5663 I jxcore-log: 
,09-30 09:39:06.597  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.597  5617  5663 I jxcore-log: 
09-30 09:39:06.598  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.598  5617  5663 I jxcore-log: 
,09-30 09:39:06.598  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.598  5617  5663 I jxcore-log: 
09-30 09:39:06.599  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.599  5617  5663 I jxcore-log: 
,09-30 09:39:06.600  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.600  5617  5663 I jxcore-log: 
,09-30 09:39:06.601  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.601  5617  5663 I jxcore-log: 
09-30 09:39:06.601  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.601  5617  5663 I jxcore-log: 
,09-30 09:39:06.602  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.602  5617  5663 I jxcore-log: 
09-30 09:39:06.602  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.602  5617  5663 I jxcore-log: 
09-30 09:39:06.603  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.603  5617  5663 I jxcore-log: 
,09-30 09:39:06.604  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:06.604  5617  5663 I jxcore-log: 
09-30 09:39:06.604  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:06.604  5617  5663 I jxcore-log: 
,09-30 09:39:06.649  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.649  5617  5663 I jxcore-log: 
,09-30 09:39:06.650  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.650  5617  5663 I jxcore-log: 
,09-30 09:39:06.651  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.651  5617  5663 I jxcore-log: 
09-30 09:39:06.652  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.652  5617  5663 I jxcore-log: 
,09-30 09:39:06.652  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.652  5617  5663 I jxcore-log: 
09-30 09:39:06.653  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.653  5617  5663 I jxcore-log: 
,09-30 09:39:06.653  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.653  5617  5663 I jxcore-log: 
09-30 09:39:06.654  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.654  5617  5663 I jxcore-log: 
09-30 09:39:06.654  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.654  5617  5663 I jxcore-log: 
,09-30 09:39:06.655  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.655  5617  5663 I jxcore-log: 
09-30 09:39:06.655  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.655  5617  5663 I jxcore-log: 
,09-30 09:39:06.656  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.656  5617  5663 I jxcore-log: 
,09-30 09:39:06.656  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.656  5617  5663 I jxcore-log: 
09-30 09:39:06.657  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.657  5617  5663 I jxcore-log: 
,09-30 09:39:06.657  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.657  5617  5663 I jxcore-log: 
09-30 09:39:06.658  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.658  5617  5663 I jxcore-log: 
,09-30 09:39:06.658  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.658  5617  5663 I jxcore-log: 
09-30 09:39:06.659  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.659  5617  5663 I jxcore-log: 
,09-30 09:39:06.659  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.659  5617  5663 I jxcore-log: 
09-30 09:39:06.660  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.660  5617  5663 I jxcore-log: 
,09-30 09:39:06.660  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.660  5617  5663 I jxcore-log: 
09-30 09:39:06.660  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.660  5617  5663 I jxcore-log: 
,09-30 09:39:06.661  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.661  5617  5663 I jxcore-log: 
09-30 09:39:06.661  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.661  5617  5663 I jxcore-log: 
,09-30 09:39:06.662  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.662  5617  5663 I jxcore-log: 
09-30 09:39:06.662  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.662  5617  5663 I jxcore-log: 
,09-30 09:39:06.663  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.663  5617  5663 I jxcore-log: 
09-30 09:39:06.663  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.663  5617  5663 I jxcore-log: 
09-30 09:39:06.664  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.664  5617  5663 I jxcore-log: 
,09-30 09:39:06.664  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.664  5617  5663 I jxcore-log: 
09-30 09:39:06.665  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.665  5617  5663 I jxcore-log: 
09-30 09:39:06.665  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.665  5617  5663 I jxcore-log: 
09-30 09:39:06.666  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.666  5617  5663 I jxcore-log: 
,09-30 09:39:06.666  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.666  5617  5663 I jxcore-log: 
09-30 09:39:06.666  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.666  5617  5663 I jxcore-log: 
09-30 09:39:06.667  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.667  5617  5663 I jxcore-log: 
,09-30 09:39:06.667  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.667  5617  5663 I jxcore-log: 
09-30 09:39:06.668  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.668  5617  5663 I jxcore-log: 
09-30 09:39:06.668  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.668  5617  5663 I jxcore-log: 
09-30 09:39:06.669  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.669  5617  5663 I jxcore-log: 
09-30 09:39:06.669  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.669  5617  5663 I jxcore-log: 
,09-30 09:39:06.669  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.669  5617  5663 I jxcore-log: 
09-30 09:39:06.670  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.670  5617  5663 I jxcore-log: 
09-30 09:39:06.670  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.670  5617  5663 I jxcore-log: 
,09-30 09:39:06.672  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.672  5617  5663 I jxcore-log: 
,09-30 09:39:06.672  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.672  5617  5663 I jxcore-log: 
,09-30 09:39:06.675  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.675  5617  5663 I jxcore-log: 
,09-30 09:39:06.675  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.675  5617  5663 I jxcore-log: 
,09-30 09:39:06.676  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:06.676  5617  5663 I jxcore-log: 
09-30 09:39:06.676  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'mux close'
09-30 09:39:06.676  5617  5663 I jxcore-log: 
,09-30 09:39:06.678  5617  5663 I jxcore-log: ok 28 native server is nulled out
09-30 09:39:06.678  5617  5663 I jxcore-log: 
,09-30 09:39:06.678  5617  5663 I jxcore-log: ok 29 native server should be closed
09-30 09:39:06.678  5617  5663 I jxcore-log: 
09-30 09:39:06.679  5617  5663 I jxcore-log: ok 30 incoming has been removed
09-30 09:39:06.679  5617  5663 I jxcore-log: 
,09-30 09:39:06.679  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.679  5617  5663 I jxcore-log: 
09-30 09:39:06.680  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.680  5617  5663 I jxcore-log: 
,09-30 09:39:06.680  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.680  5617  5663 I jxcore-log: 
09-30 09:39:06.681  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.681  5617  5663 I jxcore-log: 
09-30 09:39:06.681  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.681  5617  5663 I jxcore-log: 
09-30 09:39:06.681  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.681  5617  5663 I jxcore-log: 
,09-30 09:39:06.681  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.681  5617  5663 I jxcore-log: 
09-30 09:39:06.682  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.682  5617  5663 I jxcore-log: 
09-30 09:39:06.682  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.682  5617  5663 I jxcore-log: 
09-30 09:39:06.682  5617  5663 I jxcore-log: 2016-09-30 13:39:06 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:06.682  5617  5663 I jxcore-log: 
,09-30 09:39:06.754  5617  5663 I jxcore-log: # teardown
09-30 09:39:06.754  5617  5663 I jxcore-log: 
,09-30 09:39:06.844  5617  5663 I jxcore-log: # setup
09-30 09:39:06.844  5617  5663 I jxcore-log: 
,09-30 09:39:08.725  5617  5663 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-30 09:39:08.725  5617  5663 I jxcore-log: 
,09-30 09:39:08.763  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:08.763  5617  5663 I jxcore-log: 
,09-30 09:39:08.768  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'listening 39241'
09-30 09:39:08.768  5617  5663 I jxcore-log: 
,09-30 09:39:08.776  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:08.776  5617  5663 I jxcore-log: 
,09-30 09:39:08.778  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:08.778  5617  5663 I jxcore-log: 
,09-30 09:39:08.780  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'new mux'
09-30 09:39:08.780  5617  5663 I jxcore-log: 
,09-30 09:39:08.789  5617  5663 I jxcore-log: ok 31 we should not have gotten an error
09-30 09:39:08.789  5617  5663 I jxcore-log: 
,09-30 09:39:08.793  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:08.793  5617  5663 I jxcore-log: 
,09-30 09:39:08.798  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:08.798  5617  5663 I jxcore-log: 
,09-30 09:39:08.805  5617  5663 I jxcore-log: ok 32 Buffers are identical
09-30 09:39:08.805  5617  5663 I jxcore-log: 
,09-30 09:39:08.806  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:08.806  5617  5663 I jxcore-log: 
,09-30 09:39:08.807  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'mux close'
09-30 09:39:08.807  5617  5663 I jxcore-log: 
,09-30 09:39:08.818  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:08.818  5617  5663 I jxcore-log: 
,09-30 09:39:08.819  5617  5663 I jxcore-log: ok 33 server should be fine
09-30 09:39:08.819  5617  5663 I jxcore-log: 
09-30 09:39:08.819  5617  5663 I jxcore-log: ok 34 server should be open
09-30 09:39:08.819  5617  5663 I jxcore-log: 
09-30 09:39:08.820  5617  5663 I jxcore-log: ok 35 incoming has been removed
09-30 09:39:08.820  5617  5663 I jxcore-log: 
09-30 09:39:08.820  5617  5663 I jxcore-log: ok 36 The mux object should be closed
09-30 09:39:08.820  5617  5663 I jxcore-log: 
09-30 09:39:08.820  5617  5663 I jxcore-log: ok 37 The mux stream should be closed
09-30 09:39:08.820  5617  5663 I jxcore-log: 
,09-30 09:39:08.826  5617  5663 I jxcore-log: # teardown
09-30 09:39:08.826  5617  5663 I jxcore-log: 
,09-30 09:39:08.896  5617  5663 I jxcore-log: # setup
09-30 09:39:08.896  5617  5663 I jxcore-log: 
,09-30 09:39:08.948  5617  5663 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-30 09:39:08.948  5617  5663 I jxcore-log: 
,09-30 09:39:08.977  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'creating native server'
09-30 09:39:08.977  5617  5663 I jxcore-log: 
,09-30 09:39:08.981  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'listening 41328'
09-30 09:39:08.981  5617  5663 I jxcore-log: 
,09-30 09:39:08.987  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'new incoming socket'
09-30 09:39:08.987  5617  5663 I jxcore-log: 
,09-30 09:39:08.989  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'creating incoming mux'
09-30 09:39:08.989  5617  5663 I jxcore-log: 
09-30 09:39:08.990  5617  5663 I jxcore-log: 2016-09-30 13:39:08 - DEBUG createNativeListener: 'new mux'
09-30 09:39:08.990  5617  5663 I jxcore-log: 
,09-30 09:39:08.996  5617  5663 I jxcore-log: ok 38 we should not have gotten an error
09-30 09:39:08.996  5617  5663 I jxcore-log: 
,09-30 09:39:09.000  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG createNativeListener: 'new stream: '
09-30 09:39:09.000  5617  5663 I jxcore-log: 
,09-30 09:39:09.003  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG createNativeListener: 'new outgoing socket'
09-30 09:39:09.003  5617  5663 I jxcore-log: 
,09-30 09:39:09.011  5617  5663 I jxcore-log: ok 39 Buffers are identical
09-30 09:39:09.011  5617  5663 I jxcore-log: 
,09-30 09:39:09.015  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG createNativeListener: 'incoming socket timeout'
09-30 09:39:09.015  5617  5663 I jxcore-log: 
,09-30 09:39:09.017  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG createNativeListener: 'stream close:'
09-30 09:39:09.017  5617  5663 I jxcore-log: 
,09-30 09:39:09.019  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG createNativeListener: 'mux close'
09-30 09:39:09.019  5617  5663 I jxcore-log: 
,09-30 09:39:09.024  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG createNativeListener: 'incoming socket close'
09-30 09:39:09.024  5617  5663 I jxcore-log: 
,09-30 09:39:09.025  5617  5663 I jxcore-log: ok 40 server should be fine
09-30 09:39:09.025  5617  5663 I jxcore-log: 
09-30 09:39:09.025  5617  5663 I jxcore-log: ok 41 server should be open
09-30 09:39:09.025  5617  5663 I jxcore-log: 
09-30 09:39:09.026  5617  5663 I jxcore-log: ok 42 incoming has been removed
09-30 09:39:09.026  5617  5663 I jxcore-log: 
09-30 09:39:09.026  5617  5663 I jxcore-log: ok 43 The mux object should be closed
09-30 09:39:09.026  5617  5663 I jxcore-log: 
,09-30 09:39:09.026  5617  5663 I jxcore-log: ok 44 The mux stream should be closed
09-30 09:39:09.026  5617  5663 I jxcore-log: 
,09-30 09:39:09.034  5617  5663 I jxcore-log: # teardown
09-30 09:39:09.034  5617  5663 I jxcore-log: 
,09-30 09:39:09.060  5617  5663 I jxcore-log: # setup
09-30 09:39:09.060  5617  5663 I jxcore-log: 
,09-30 09:39:09.088  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-30 09:39:09.088  5617  5663 I jxcore-log: 
,09-30 09:39:09.273  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-30 09:39:09.273  5617  5663 I jxcore-log: 
,09-30 09:39:09.274  5617  5663 I jxcore-log: ok 45 Got right error
09-30 09:39:09.274  5617  5663 I jxcore-log: 
,09-30 09:39:09.279  5617  5663 I jxcore-log: # teardown
09-30 09:39:09.279  5617  5663 I jxcore-log: 
,09-30 09:39:09.306  5617  5663 I jxcore-log: # setup
09-30 09:39:09.306  5617  5663 I jxcore-log: 
,09-30 09:39:09.372  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-30 09:39:09.372  5617  5663 I jxcore-log: 
,09-30 09:39:09.456  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-30 09:39:09.456  5617  5663 I jxcore-log: 
,09-30 09:39:09.457  5617  5663 I jxcore-log: ok 46 Got socket hang up
09-30 09:39:09.457  5617  5663 I jxcore-log: 
,09-30 09:39:09.462  5617  5663 I jxcore-log: # teardown
09-30 09:39:09.462  5617  5663 I jxcore-log: 
,09-30 09:39:09.497  5617  5663 I jxcore-log: # setup
09-30 09:39:09.497  5617  5663 I jxcore-log: 
,09-30 09:39:09.584  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-30 09:39:09.584  5617  5663 I jxcore-log: 
,09-30 09:39:09.800  5617  5663 I jxcore-log: 2016-09-30 13:39:09 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-30 09:39:09.800  5617  5663 I jxcore-log: 
,09-30 09:39:09.800  5617  5663 I jxcore-log: ok 47 Got 500 as expected
09-30 09:39:09.800  5617  5663 I jxcore-log: 
,09-30 09:39:09.804  5617  5663 I jxcore-log: # teardown
09-30 09:39:09.804  5617  5663 I jxcore-log: 
,09-30 09:39:09.832  5617  5663 I jxcore-log: # setup
09-30 09:39:09.832  5617  5663 I jxcore-log: 
,09-30 09:39:09.891  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-30 09:39:09.891  5617  5663 I jxcore-log: 
,09-30 09:39:10.889   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:11.446  5617  5663 I jxcore-log: ok 48 should be equal
09-30 09:39:11.446  5617  5663 I jxcore-log: 
,09-30 09:39:11.447  5617  5663 I jxcore-log: ok 49 revs are equal
09-30 09:39:11.447  5617  5663 I jxcore-log: 
,09-30 09:39:11.456  5617  5663 I jxcore-log: # teardown
09-30 09:39:11.456  5617  5663 I jxcore-log: 
,09-30 09:39:11.500  5617  5663 I jxcore-log: # setup
09-30 09:39:11.500  5617  5663 I jxcore-log: 
,09-30 09:39:11.890   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:12.211  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-30 09:39:12.211  5617  5663 I jxcore-log: 
,09-30 09:39:12.887  5617  5663 I jxcore-log: ok 50 should be equal
09-30 09:39:12.887  5617  5663 I jxcore-log: 
,09-30 09:39:12.888  5617  5663 I jxcore-log: ok 51 revs are equal
09-30 09:39:12.888  5617  5663 I jxcore-log: 
,09-30 09:39:12.891   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:12.893  5617  5663 I jxcore-log: # teardown
09-30 09:39:12.893  5617  5663 I jxcore-log: 
,09-30 09:39:12.932  5617  5663 I jxcore-log: # setup
09-30 09:39:12.932  5617  5663 I jxcore-log: 
,09-30 09:39:12.998  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-30 09:39:12.998  5617  5663 I jxcore-log: 
,09-30 09:39:13.572  5617  5663 I jxcore-log: ok 52 should be equal
09-30 09:39:13.572  5617  5663 I jxcore-log: 
,09-30 09:39:13.573  5617  5663 I jxcore-log: ok 53 revs are equal
09-30 09:39:13.573  5617  5663 I jxcore-log: 
,09-30 09:39:13.733  5617  5663 I jxcore-log: ok 54 should be equal
09-30 09:39:13.733  5617  5663 I jxcore-log: 
,09-30 09:39:13.734  5617  5663 I jxcore-log: ok 55 revs are equal
09-30 09:39:13.734  5617  5663 I jxcore-log: 
,09-30 09:39:13.892   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:13.929  5617  5663 I jxcore-log: ok 56 should be equal
09-30 09:39:13.929  5617  5663 I jxcore-log: 
,09-30 09:39:13.930  5617  5663 I jxcore-log: ok 57 revs are equal
09-30 09:39:13.930  5617  5663 I jxcore-log: 
,09-30 09:39:13.937  5617  5663 I jxcore-log: # teardown
09-30 09:39:13.937  5617  5663 I jxcore-log: 
,09-30 09:39:14.051  5617  5663 I jxcore-log: # setup
09-30 09:39:14.051  5617  5663 I jxcore-log: 
,09-30 09:39:14.455  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-30 09:39:14.455  5617  5663 I jxcore-log: 
,09-30 09:39:14.893   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:15.019  5617  5663 I jxcore-log: 2016-09-30 13:39:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-30 09:39:15.019  5617  5663 I jxcore-log: 
,09-30 09:39:15.020  5617  5663 I jxcore-log: ok 58 Our rev is old so we should fail
09-30 09:39:15.020  5617  5663 I jxcore-log: 
,09-30 09:39:15.024  5617  5663 I jxcore-log: # teardown
09-30 09:39:15.024  5617  5663 I jxcore-log: 
,09-30 09:39:15.192  5617  5663 I jxcore-log: # setup
09-30 09:39:15.192  5617  5663 I jxcore-log: 
,09-30 09:39:15.225  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-30 09:39:15.225  5617  5663 I jxcore-log: 
,09-30 09:39:15.308  5617  5663 I jxcore-log: ok 59 confirm stop caused failure
09-30 09:39:15.308  5617  5663 I jxcore-log: 
,09-30 09:39:15.316  5617  5663 I jxcore-log: # teardown
09-30 09:39:15.316  5617  5663 I jxcore-log: 
,09-30 09:39:15.380  5617  5663 I jxcore-log: # setup
09-30 09:39:15.380  5617  5663 I jxcore-log: 
,09-30 09:39:15.413  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-30 09:39:15.413  5617  5663 I jxcore-log: 
,09-30 09:39:15.722  5617  5663 I jxcore-log: 2016-09-30 13:39:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-30 09:39:15.722  5617  5663 I jxcore-log: 
,09-30 09:39:15.724  5617  5663 I jxcore-log: ok 60 stop caused us to fail
09-30 09:39:15.724  5617  5663 I jxcore-log: 
09-30 09:39:15.724  5617  5663 I jxcore-log: ok 61 We specifically failed on a stop before put
09-30 09:39:15.724  5617  5663 I jxcore-log: 
,09-30 09:39:15.729  5617  5663 I jxcore-log: # teardown
09-30 09:39:15.729  5617  5663 I jxcore-log: 
,09-30 09:39:15.818  5617  5663 I jxcore-log: # setup
09-30 09:39:15.818  5617  5663 I jxcore-log: 
,09-30 09:39:15.864  5617  5663 I jxcore-log: # #update - fail if stop is called
09-30 09:39:15.864  5617  5663 I jxcore-log: 
,09-30 09:39:15.893   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 09:39:15.971  5617  5663 I jxcore-log: ok 62 failed due to stop
09-30 09:39:15.971  5617  5663 I jxcore-log: 
,09-30 09:39:15.973  5617  5663 I jxcore-log: ok 63 failed due to stop
09-30 09:39:15.973  5617  5663 I jxcore-log: 
,09-30 09:39:15.981  5617  5663 I jxcore-log: # teardown
09-30 09:39:15.981  5617  5663 I jxcore-log: 
,09-30 09:39:16.053  5617  5663 I jxcore-log: # setup
09-30 09:39:16.053  5617  5663 I jxcore-log: 
,09-30 09:39:16.084  5617  5663 I jxcore-log: # #update - set seq for first time
09-30 09:39:16.084  5617  5663 I jxcore-log: 
,09-30 09:39:16.563  5617  5663 I jxcore-log: ok 64 should be equal
09-30 09:39:16.563  5617  5663 I jxcore-log: 
,09-30 09:39:16.570  5617  5663 I jxcore-log: # teardown
09-30 09:39:16.570  5617  5663 I jxcore-log: 
,09-30 09:39:16.658  5617  5663 I jxcore-log: # setup
09-30 09:39:16.658  5617  5663 I jxcore-log: 
,09-30 09:39:16.675  5617  5663 I jxcore-log: # #update - Fail on bad seq value
09-30 09:39:16.675  5617  5663 I jxcore-log: 
,09-30 09:39:17.091  5617  5663 I jxcore-log: 2016-09-30 13:39:17 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-30 09:39:17.091  5617  5663 I jxcore-log: 
,09-30 09:39:17.093  5617  5663 I jxcore-log: ok 65 Expected bad seq error
09-30 09:39:17.093  5617  5663 I jxcore-log: 
,09-30 09:39:17.098  5617  5663 I jxcore-log: # teardown
09-30 09:39:17.098  5617  5663 I jxcore-log: 
,09-30 09:39:17.232  5617  5663 I jxcore-log: # setup
09-30 09:39:17.232  5617  5663 I jxcore-log: 
,09-30 09:39:17.263  5617  5663 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-30 09:39:17.263  5617  5663 I jxcore-log: 
,09-30 09:39:18.724  5617  5663 I jxcore-log: ok 66 Different promises
09-30 09:39:18.724  5617  5663 I jxcore-log: 
,09-30 09:39:18.726  5617  5663 I jxcore-log: ok 67 Timer was cancelled
09-30 09:39:18.726  5617  5663 I jxcore-log: 
,09-30 09:39:18.869  5617  5663 I jxcore-log: ok 68 should be equal
09-30 09:39:18.869  5617  5663 I jxcore-log: 
,09-30 09:39:18.876  5617  5663 I jxcore-log: # teardown
09-30 09:39:18.876  5617  5663 I jxcore-log: 
,09-30 09:39:19.080  5617  5663 I jxcore-log: # setup
09-30 09:39:19.080  5617  5663 I jxcore-log: 
,09-30 09:39:19.579  5617  5663 I jxcore-log: # #update - do we wait for blocked update
09-30 09:39:19.579  5617  5663 I jxcore-log: 
,09-30 09:39:19.673  5617  5663 I jxcore-log: ok 69 One go and one blocked
09-30 09:39:19.673  5617  5663 I jxcore-log: 
09-30 09:39:19.673  5617  5663 I jxcore-log: ok 70 All blocked
09-30 09:39:19.673  5617  5663 I jxcore-log: 
,09-30 09:39:19.674  5617  5663 I jxcore-log: ok 71 Still blocked
09-30 09:39:19.674  5617  5663 I jxcore-log: 
,09-30 09:39:20.129  5617  5663 I jxcore-log: ok 72 should be equal
09-30 09:39:20.129  5617  5663 I jxcore-log: 
,09-30 09:39:20.137  5617  5663 I jxcore-log: # teardown
09-30 09:39:20.137  5617  5663 I jxcore-log: 
,09-30 09:39:20.195  5617  5663 I jxcore-log: # setup
09-30 09:39:20.195  5617  5663 I jxcore-log: 
,09-30 09:39:20.248  5617  5663 I jxcore-log: # #update - test that we wait long enough
09-30 09:39:20.248  5617  5663 I jxcore-log: 
,09-30 09:39:21.943  5617  5663 I jxcore-log: ok 73 We waited long enough
09-30 09:39:21.943  5617  5663 I jxcore-log: 
,09-30 09:39:22.037  5617  5663 I jxcore-log: ok 74 should be equal
09-30 09:39:22.037  5617  5663 I jxcore-log: 
,09-30 09:39:22.043  5617  5663 I jxcore-log: # teardown
09-30 09:39:22.043  5617  5663 I jxcore-log: 
,09-30 09:39:22.096  5617  5663 I jxcore-log: # setup
09-30 09:39:22.096  5617  5663 I jxcore-log: 
,09-30 09:39:22.120  5617  5663 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-30 09:39:22.120  5617  5663 I jxcore-log: 
,09-30 09:39:22.523  5617  5663 I jxcore-log: ok 75 Should have gotten same timer promise
09-30 09:39:22.523  5617  5663 I jxcore-log: 
,09-30 09:39:22.524  5617  5663 I jxcore-log: ok 76 Still same timer promise
09-30 09:39:22.524  5617  5663 I jxcore-log: 
,09-30 09:39:23.321  5617  5663 I jxcore-log: ok 77 We waited long enough
09-30 09:39:23.321  5617  5663 I jxcore-log: 
,09-30 09:39:23.384  5617  5663 I jxcore-log: ok 78 should be equal
09-30 09:39:23.384  5617  5663 I jxcore-log: 
,09-30 09:39:23.391  5617  5663 I jxcore-log: # teardown
09-30 09:39:23.391  5617  5663 I jxcore-log: 
,09-30 09:39:23.454   927  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 09:39:23.528  5617  5663 I jxcore-log: # setup
09-30 09:39:23.528  5617  5663 I jxcore-log: 
,09-30 09:39:23.587  5617  5663 I jxcore-log: # Coordinated seq test
09-30 09:39:23.587  5617  5663 I jxcore-log: 
,09-30 09:39:23.593  5617  5663 I jxcore-log: 2016-09-30 13:39:23 - INFO CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
09-30 09:39:23.593  5617  5663 I jxcore-log: 
,09-30 09:39:23.648  5617  5663 I jxcore-log: # teardown
09-30 09:39:23.648  5617  5663 I jxcore-log: 
,09-30 09:39:23.710  5617  5663 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-30 09:39:23.711  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 09:39:23.711  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 09:39:23.711  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 09:39:23.725  5617  5663 I jxcore-log: # setup
09-30 09:39:23.725  5617  5663 I jxcore-log: 
,09-30 09:39:23.771  5617  5663 I jxcore-log: # closeAll can close even when connections open
09-30 09:39:23.771  5617  5663 I jxcore-log: 
,09-30 09:39:23.938  5617  5663 I jxcore-log: ok 79 not possible to connect to the server anymore
09-30 09:39:23.938  5617  5663 I jxcore-log: 
,09-30 09:39:23.946  5617  5663 I jxcore-log: # teardown
09-30 09:39:23.946  5617  5663 I jxcore-log: 
,09-30 09:39:23.998  5617  5663 I jxcore-log: # setup
09-30 09:39:23.998  5617  5663 I jxcore-log: 
,09-30 09:39:24.038  5617  5663 I jxcore-log: # closeAll with promise
09-30 09:39:24.038  5617  5663 I jxcore-log: 
,09-30 09:39:24.186  5617  5663 I jxcore-log: ok 80 not possible to connect to the server anymore
09-30 09:39:24.186  5617  5663 I jxcore-log: 
,09-30 09:39:24.194  5617  5663 I jxcore-log: # teardown
09-30 09:39:24.194  5617  5663 I jxcore-log: 
,09-30 09:39:24.238  5617  5663 I jxcore-log: # setup
09-30 09:39:24.238  5617  5663 I jxcore-log: 
,09-30 09:39:24.281  5617  5663 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
09-30 09:39:24.281  5617  5663 I jxcore-log: 
,09-30 09:39:24.421  5617  5663 I jxcore-log: ok 81 Got the right error
09-30 09:39:24.421  5617  5663 I jxcore-log: 
,09-30 09:39:24.430  5617  5663 I jxcore-log: # teardown
09-30 09:39:24.430  5617  5663 I jxcore-log: 
,09-30 09:39:24.469  5617  5663 I jxcore-log: # setup
09-30 09:39:24.469  5617  5663 I jxcore-log: 
,09-30 09:39:24.517  5617  5663 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-30 09:39:24.517  5617  5663 I jxcore-log: 
,09-30 09:39:24.667  5617  5663 I jxcore-log: # teardown
09-30 09:39:24.667  5617  5663 I jxcore-log: 
,09-30 09:39:24.725  5617  5663 I jxcore-log: # setup
09-30 09:39:24.725  5617  5663 I jxcore-log: 
,09-30 09:39:24.767  5617  5663 I jxcore-log: # onPeerLost calls jxcore
09-30 09:39:24.767  5617  5663 I jxcore-log: 
,09-30 09:39:24.821  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 09:39:24.821  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0cf04d added. We now have 3 listener(s)
09-30 09:39:24.825  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 09:39:24.825  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:39:24.825  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 09:39:24.826  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:39:24.826  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@847f702 added. We now have 4 listener(s)
09-30 09:39:24.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 09:39:24.827  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 09:39:24.833  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 09:39:24.840  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:39:24.840  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:39:24.840  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:39:24.840  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:39:24.840  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:39:24.840  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:39:24.840  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:39:24.840  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 09:39:24.842  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:39:24.843  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:39:24.843  5617  5663 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-30 09:39:24.843  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
09-30 09:39:24.849  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 09:39:24.853  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:39:25.895   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:26.847  5617  5663 I jxcore-log: onPeerLost
09-30 09:39:26.847  5617  5663 I jxcore-log: 
,09-30 09:39:26.850  5617  5663 I jxcore-log: 2016-09-30 13:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:39:26.850  5617  5663 I jxcore-log: 
,09-30 09:39:26.864  5617  5663 I jxcore-log: # teardown
09-30 09:39:26.864  5617  5663 I jxcore-log: 
,09-30 09:39:26.868  5617  5663 I jxcore-log: ok 82 check if callback was fired by onPeerLost
09-30 09:39:26.868  5617  5663 I jxcore-log: 
,09-30 09:39:26.868  5617  5663 I jxcore-log: ok 83 check if peerAvailable is false
09-30 09:39:26.868  5617  5663 I jxcore-log: 
,09-30 09:39:26.895   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:26.943  5617  5663 I jxcore-log: 2016-09-30 13:39:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 09:39:26.943  5617  5663 I jxcore-log: 
,09-30 09:39:26.947  5617  5663 I jxcore-log: 2016-09-30 13:39:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 09:39:26.947  5617  5663 I jxcore-log: 
,09-30 09:39:26.956  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:39:26.956  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:39:26.956  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:39:26.956  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:39:26.956  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:39:26.956  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:39:26.956  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:39:26.956  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:39:26.959  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:39:26.961  5617  5663 I jxcore-log: 2016-09-30 13:39:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 09:39:26.961  5617  5663 I jxcore-log: 
,09-30 09:39:26.963  5617  5663 I jxcore-log: 2016-09-30 13:39:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 09:39:26.963  5617  5663 I jxcore-log: 
,09-30 09:39:26.967  5617  5663 I jxcore-log: 2016-09-30 13:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:39:26.967  5617  5663 I jxcore-log: 
,09-30 09:39:26.970  5617  5663 I jxcore-log: # setup
09-30 09:39:26.970  5617  5663 I jxcore-log: 
,09-30 09:39:27.356  5617  5663 I jxcore-log: # onPeerDiscovered calls jxcore
09-30 09:39:27.356  5617  5663 I jxcore-log: 
,09-30 09:39:27.404  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 09:39:27.405  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73b9a50 added. We now have 4 listener(s)
09-30 09:39:27.406  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 09:39:27.407  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 09:39:27.407  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 09:39:27.407  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 09:39:27.407  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7454449 added. We now have 5 listener(s)
09-30 09:39:27.407  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 09:39:27.408  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 09:39:27.413  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 09:39:27.419  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:39:27.419  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:39:27.419  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:39:27.419  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:39:27.419  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:39:27.419  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:39:27.419  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:39:27.419  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:39:27.422  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 09:39:27.422  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 09:39:27.423  5617  5663 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-30 09:39:27.427  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:39:27.430  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 09:39:27.896   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:28.897   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:29.425  5617  5663 I jxcore-log: onPeerDiscovered
09-30 09:39:29.425  5617  5663 I jxcore-log: 
,09-30 09:39:29.428  5617  5663 I jxcore-log: 2016-09-30 13:39:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:39:29.428  5617  5663 I jxcore-log: 
,09-30 09:39:29.440  5617  5663 I jxcore-log: # teardown
09-30 09:39:29.440  5617  5663 I jxcore-log: 
,09-30 09:39:29.445  5617  5663 I jxcore-log: ok 84 check if callback was fired by onPeerDiscovered
09-30 09:39:29.445  5617  5663 I jxcore-log: 
,09-30 09:39:29.446  5617  5663 I jxcore-log: ok 85 check if peerAvailable is true
09-30 09:39:29.446  5617  5663 I jxcore-log: 
,09-30 09:39:29.496  5617  5663 I jxcore-log: 2016-09-30 13:39:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 09:39:29.496  5617  5663 I jxcore-log: 
,09-30 09:39:29.499  5617  5663 I jxcore-log: 2016-09-30 13:39:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 09:39:29.499  5617  5663 I jxcore-log: 
,09-30 09:39:29.511  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 09:39:29.511  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 09:39:29.511  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 09:39:29.511  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 09:39:29.511  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 09:39:29.511  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 09:39:29.511  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 09:39:29.511  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 09:39:29.515  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 09:39:29.517  5617  5663 I jxcore-log: 2016-09-30 13:39:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 09:39:29.517  5617  5663 I jxcore-log: 
,09-30 09:39:29.519  5617  5663 I jxcore-log: 2016-09-30 13:39:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 09:39:29.519  5617  5663 I jxcore-log: 
,09-30 09:39:29.523  5617  5663 I jxcore-log: 2016-09-30 13:39:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 09:39:29.523  5617  5663 I jxcore-log: 
,09-30 09:39:29.527  5617  5663 I jxcore-log: # setup
09-30 09:39:29.527  5617  5663 I jxcore-log: 
,09-30 09:39:29.656  5617  5663 I jxcore-log: # Call of onCheckpointReached handler on a single db change
09-30 09:39:29.656  5617  5663 I jxcore-log: 
,09-30 09:39:29.898   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 09:39:29.988  5617  5663 I jxcore-log: # teardown
09-30 09:39:29.988  5617  5663 I jxcore-log: 
,09-30 09:39:30.088  5617  5663 I jxcore-log: # setup
09-30 09:39:30.088  5617  5663 I jxcore-log: 
,09-30 09:39:30.130  5617  5663 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
09-30 09:39:30.130  5617  5663 I jxcore-log: 
,09-30 09:39:30.446  5617  5663 I jxcore-log: # teardown
09-30 09:39:30.446  5617  5663 I jxcore-log: 
,09-30 09:39:30.508  5617  5663 I jxcore-log: # setup
09-30 09:39:30.508  5617  5663 I jxcore-log: 
,09-30 09:39:30.580  5617  5663 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
09-30 09:39:30.580  5617  5663 I jxcore-log: 
,09-30 09:39:30.899   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 09:39:31.883  5617  5663 I jxcore-log: ok 86 the checkpointReached handler should be called once. Called 1 time(s)
09-30 09:39:31.883  5617  5663 I jxcore-log: 
,09-30 09:39:31.897  5617  5663 I jxcore-log: # teardown
09-30 09:39:31.897  5617  5663 I jxcore-log: 
,09-30 09:39:31.981  5617  5663 I jxcore-log: # setup
09-30 09:39:31.981  5617  5663 I jxcore-log: 
,09-30 09:39:32.093  5617  5663 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
09-30 09:39:32.093  5617  5663 I jxcore-log: 
,09-30 09:39:32.688  5617  5663 I jxcore-log: # teardown
09-30 09:39:32.688  5617  5663 I jxcore-log: 
,09-30 09:39:32.738  5617  5663 I jxcore-log: # setup
09-30 09:39:32.738  5617  5663 I jxcore-log: 
,09-30 09:39:32.793  5617  5663 I jxcore-log: # test defaultDirectory
09-30 09:39:32.793  5617  5663 I jxcore-log: 
,09-30 09:39:32.843  5617  5663 I jxcore-log: ok 87 should be equal
09-30 09:39:32.843  5617  5663 I jxcore-log: 
,09-30 09:39:32.848  5617  5663 I jxcore-log: ok 88 should be equal
09-30 09:39:32.848  5617  5663 I jxcore-log: 
,09-30 09:39:32.854  5617  5663 I jxcore-log: ok 89 should be equal
09-30 09:39:32.854  5617  5663 I jxcore-log: 
,09-30 09:39:32.865  5617  5663 I jxcore-log: # teardown
09-30 09:39:32.865  5617  5663 I jxcore-log: 
,09-30 09:39:32.898  5617  5663 I jxcore-log: # setup
09-30 09:39:32.898  5617  5663 I jxcore-log: 
,09-30 09:39:32.958  5617  5663 I jxcore-log: # test defaultAdapter
09-30 09:39:32.958  5617  5663 I jxcore-log: 
,09-30 09:39:33.002  5617  5663 I jxcore-log: ok 90 should be equal
09-30 09:39:33.002  5617  5663 I jxcore-log: 
,09-30 09:39:33.003  5617  5663 I jxcore-log: ok 91 should be equal
09-30 09:39:33.003  5617  5663 I jxcore-log: 
,09-30 09:39:33.005  5617  5663 I jxcore-log: ok 92 should be equal
09-30 09:39:33.005  5617  5663 I jxcore-log: 
,09-30 09:39:33.006  5617  5663 I jxcore-log: ok 93 should be equal
09-30 09:39:33.006  5617  5663 I jxcore-log: 
,09-30 09:39:33.009  5617  5663 I jxcore-log: ok 94 should be equal
09-30 09:39:33.009  5617  5663 I jxcore-log: 
,09-30 09:39:33.010  5617  5663 I jxcore-log: ok 95 should be equal
09-30 09:39:33.010  5617  5663 I jxcore-log: 
,09-30 09:39:33.147  5617  5663 I jxcore-log: ok 96 should be equal
09-30 09:39:33.147  5617  5663 I jxcore-log: 
,09-30 09:39:33.147  5617  5663 I jxcore-log: ok 97 should be equal
09-30 09:39:33.147  5617  5663 I jxcore-log: 
,09-30 09:39:33.155  5617  5663 I jxcore-log: # teardown
09-30 09:39:33.155  5617  5663 I jxcore-log: 
,09-30 09:39:33.277  5617  5663 I jxcore-log: # setup
09-30 09:39:33.277  5617  5663 I jxcore-log: 
,09-30 09:39:33.311  5617  5663 I jxcore-log: # enqueue and run in order
09-30 09:39:33.311  5617  5663 I jxcore-log: 
,09-30 09:39:33.452  5617  5663 I jxcore-log: ok 98 firstPromise setTimeout
09-30 09:39:33.452  5617  5663 I jxcore-log: 
,09-30 09:39:33.457  5617  5663 I jxcore-log: ok 99 firstPromise result
09-30 09:39:33.457  5617  5663 I jxcore-log: 
09-30 09:39:33.458  5617  5663 I jxcore-log: ok 100 firstPromise testValue
09-30 09:39:33.458  5617  5663 I jxcore-log: 
,09-30 09:39:33.565  5617  5663 I jxcore-log: ok 101 secondPromise setTimeout
09-30 09:39:33.565  5617  5663 I jxcore-log: 
,09-30 09:39:33.568  5617  5663 I jxcore-log: ok 102 secondPromise result
09-30 09:39:33.568  5617  5663 I jxcore-log: 
09-30 09:39:33.569  5617  5663 I jxcore-log: ok 103 secondPromise testValue
09-30 09:39:33.569  5617  5663 I jxcore-log: 
09-30 09:39:33.571  5617  5663 I jxcore-log: ok 104 thirdPromise in promise
09-30 09:39:33.571  5617  5663 I jxcore-log: 
,09-30 09:39:33.576  5617  5663 I jxcore-log: ok 105 thirdPromise result
09-30 09:39:33.576  5617  5663 I jxcore-log: 
09-30 09:39:33.578  5617  5663 I jxcore-log: ok 106 thirdPromise testValue
09-30 09:39:33.578  5617  5663 I jxcore-log: 
,09-30 09:39:33.589  5617  5663 I jxcore-log: # teardown
09-30 09:39:33.589  5617  5663 I jxcore-log: 
,09-30 09:39:33.624  5617  5663 I jxcore-log: # setup
09-30 09:39:33.624  5617  5663 I jxcore-log: 
,09-30 09:39:33.657  5617  5663 I jxcore-log: # enqueueAtTop and run backwards
09-30 09:39:33.657  5617  5663 I jxcore-log: 
,09-30 09:39:33.707  5617  5663 I jxcore-log: ok 107 thirdPromise - first to run
09-30 09:39:33.707  5617  5663 I jxcore-log: 
,09-30 09:39:33.708  5617  5663 I jxcore-log: ok 108 thirdPromise - in resolve
09-30 09:39:33.708  5617  5663 I jxcore-log: 
,09-30 09:39:33.709  5617  5663 I jxcore-log: ok 109 secondPromise - second to run
09-30 09:39:33.709  5617  5663 I jxcore-log: 
,09-30 09:39:33.712  5617  5663 I jxcore-log: ok 110 secondPromise - in catch
09-30 09:39:33.712  5617  5663 I jxcore-log: 
09-30 09:39:33.714  5617  5663 I jxcore-log: ok 111 firstPromise - third to run
09-30 09:39:33.714  5617  5663 I jxcore-log: 
09-30 09:39:33.715  5617  5663 I jxcore-log: ok 112 firstPromise - in then
09-30 09:39:33.715  5617  5663 I jxcore-log: 
09-30 09:39:33.717  5617  5663 I jxcore-log: ok 113 testing promises
09-30 09:39:33.717  5617  5663 I jxcore-log: 
,09-30 09:39:33.726  5617  5663 I jxcore-log: # teardown
09-30 09:39:33.726  5617  5663 I jxcore-log: 
,09-30 09:39:33.755  5617  5663 I jxcore-log: # setup
09-30 09:39:33.755  5617  5663 I jxcore-log: 
,09-30 09:39:33.795  5617  5663 I jxcore-log: # mix enqueue and enqueueAtTop
09-30 09:39:33.795  5617  5663 I jxcore-log: 
,09-30 09:39:33.838  5617  5663 I jxcore-log: ok 114 fourth
09-30 09:39:33.838  5617  5663 I jxcore-log: 
,09-30 09:39:33.854  5617  5663 I jxcore-log: ok 115 fourth
09-30 09:39:33.854  5617  5663 I jxcore-log: 
,09-30 09:39:33.857  5617  5663 I jxcore-log: ok 116 second
09-30 09:39:33.857  5617  5663 I jxcore-log: 
09-30 09:39:33.858  5617  5663 I jxcore-log: ok 117 secondPromise - in then
09-30 09:39:33.858  5617  5663 I jxcore-log: 
,09-30 09:39:33.962  5617  5663 I jxcore-log: ok 118 first
09-30 09:39:33.962  5617  5663 I jxcore-log: 
,09-30 09:39:33.965  5617  5663 I jxcore-log: ok 119 firstPromise - in catch
09-30 09:39:33.965  5617  5663 I jxcore-log: 
09-30 09:39:33.966  5617  5663 I jxcore-log: ok 120 third
09-30 09:39:33.966  5617  5663 I jxcore-log: 
,09-30 09:39:33.969  5617  5663 I jxcore-log: ok 121 thirdPromise - in then
09-30 09:39:33.969  5617  5663 I jxcore-log: 
,09-30 09:39:33.971  5617  5663 I jxcore-log: ok 122 testingPromises
09-30 09:39:33.971  5617  5663 I jxcore-log: 
,09-30 09:39:33.984  5617  5663 I jxcore-log: # teardown
09-30 09:39:33.984  5617  5663 I jxcore-log: 
,09-30 09:39:34.024  5617  5663 I jxcore-log: # setup
09-30 09:39:34.024  5617  5663 I jxcore-log: 
,09-30 09:39:34.180  5617  5663 I jxcore-log: # queues handled independently
09-30 09:39:34.180  5617  5663 I jxcore-log: 
,09-30 09:39:34.248  5617  5663 I jxcore-log: ok 123 all short operations completed before the long resolves
09-30 09:39:34.248  5617  5663 I jxcore-log: 
,09-30 09:39:34.257  5617  5663 I jxcore-log: # teardown
09-30 09:39:34.257  5617  5663 I jxcore-log: 
,09-30 09:39:34.306  5617  5663 I jxcore-log: # setup
09-30 09:39:34.306  5617  5663 I jxcore-log: 
,09-30 09:39:34.348  5617  5663 I jxcore-log: # basic
09-30 09:39:34.348  5617  5663 I jxcore-log: 
,09-30 09:39:34.377  5617  5663 I jxcore-log: ok 124 sane
09-30 09:39:34.377  5617  5663 I jxcore-log: 
,09-30 09:39:34.389  5617  5663 I jxcore-log: # teardown
09-30 09:39:34.389  5617  5663 I jxcore-log: 
,09-30 09:39:34.420  5617  5663 I jxcore-log: # setup
09-30 09:39:34.420  5617  5663 I jxcore-log: 
,09-30 09:39:34.452  5617  5663 I jxcore-log: # another
09-30 09:39:34.452  5617  5663 I jxcore-log: 
,09-30 09:39:34.482  5617  5663 I jxcore-log: ok 125 sane
09-30 09:39:34.482  5617  5663 I jxcore-log: 
,09-30 09:39:34.490  5617  5663 I jxcore-log: # teardown
09-30 09:39:34.490  5617  5663 I jxcore-log: 
,09-30 09:39:34.528  5617  5663 I jxcore-log: # setup
09-30 09:39:34.528  5617  5663 I jxcore-log: 
,09-30 09:39:34.572  5617  5663 I jxcore-log: # can pass data in setup
09-30 09:39:34.572  5617  5663 I jxcore-log: 
,09-30 09:39:34.617  5617  5663 I jxcore-log: ok 126 test participant has uuid
09-30 09:39:34.617  5617  5663 I jxcore-log: 
,09-30 09:39:34.618  5617  5663 I jxcore-log: ok 127 participant data matches
09-30 09:39:34.618  5617  5663 I jxcore-log: 
09-30 09:39:34.619  5617  5663 I jxcore-log: ok 128 test participant has uuid
09-30 09:39:34.619  5617  5663 I jxcore-log: 
09-30 09:39:34.619  5617  5663 I jxcore-log: ok 129 participant data matches
09-30 09:39:34.619  5617  5663 I jxcore-log: 
,09-30 09:39:34.620  5617  5663 I jxcore-log: ok 130 test participant has uuid
09-30 09:39:34.620  5617  5663 I jxcore-log: 
09-30 09:39:34.621  5617  5663 I jxcore-log: ok 131 participant data matches
09-30 09:39:34.621  5617  5663 I jxcore-log: 
09-30 09:39:34.621  5617  5663 I jxcore-log: ok 132 own UUID is found from the participants list
09-30 09:39:34.621  5617  5663 I jxcore-log: 
,09-30 09:39:34.630  5617  5663 I jxcore-log: # teardown
09-30 09:39:34.630  5617  5663 I jxcore-log: 
,09-30 09:39:34.672  5617  5663 I jxcore-log: # setup
09-30 09:39:34.672  5617  5663 I jxcore-log: 
,09-30 09:39:34.715  5617  5663 I jxcore-log: # test thali manager spies
09-30 09:39:34.715  5617  5663 I jxcore-log: 
,09-30 09:39:34.859  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 09:39:34.859  5617  5663 I jxcore-log: 
,09-30 09:39:34.864  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 09:39:34.864  5617  5663 I jxcore-log: 
,09-30 09:39:34.865  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 09:39:34.865  5617  5663 I jxcore-log: 
,09-30 09:39:34.882  5617  5663 I jxcore-log: ok 133 expressPouchDB was called once
09-30 09:39:34.882  5617  5663 I jxcore-log: 
,09-30 09:39:34.883  5617  5663 I jxcore-log: ok 134 expressPouchDB was called with 2 arguments
09-30 09:39:34.883  5617  5663 I jxcore-log: 
09-30 09:39:34.883  5617  5663 I jxcore-log: ok 135 expressPouchDB was called with 'PouchDB' as 1-st argument
09-30 09:39:34.883  5617  5663 I jxcore-log: 
09-30 09:39:34.883  5617  5663 I jxcore-log: ok 136 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-30 09:39:34.883  5617  5663 I jxcore-log: 
09-30 09:39:34.883  5617  5663 I jxcore-log: ok 137 PouchDB was called once
09-30 09:39:34.883  5617  5663 I jxcore-log: 
09-30 09:39:34.884  5617  5663 I jxcore-log: ok 138 PouchDB was called with 1 arguments
09-30 09:39:34.884  5617  5663 I jxcore-log: 
09-30 09:39:34.884  5617  5663 I jxcore-log: ok 139 PouchDB was called with 'dbName' as 1-st argument
09-30 09:39:34.884  5617  5663 I jxcore-log: 
09-30 09:39:34.884  5617  5663 I jxcore-log: ok 140 ThaliSendNotificationBasedOnReplication was called once
09-30 09:39:34.884  5617  5663 I jxcore-log: 
,09-30 09:39:34.885  5617  5663 I jxcore-log: ok 141 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-30 09:39:34.885  5617  5663 I jxcore-log: 
09-30 09:39:34.885  5617  5663 I jxcore-log: ok 142 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-30 09:39:34.885  5617  5663 I jxcore-log: 
09-30 09:39:34.885  5617  5663 I jxcore-log: ok 143 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-30 09:39:34.885  5617  5663 I jxcore-log: 
,09-30 09:39:34.885  5617  5663 I jxcore-log: ok 144 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-30 09:39:34.885  5617  5663 I jxcore-log: 
09-30 09:39:34.886  5617  5663 I jxcore-log: ok 145 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-30 09:39:34.886  5617  5663 I jxcore-log: 
09-30 09:39:34.886  5617  5663 I jxcore-log: ok 146 ThaliPullReplicationFromNotification was called once
09-30 09:39:34.886  5617  5663 I jxcore-log: 
09-30 09:39:34.886  5617  5663 I jxcore-log: ok 147 ThaliPullReplicationFromNotification was called with 4 arguments
09-30 09:39:34.886  5617  5663 I jxcore-log: 
09-30 09:39:34.886  5617  5663 I jxcore-log: ok 148 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-30 09:39:34.886  5617  5663 I jxcore-log: 
09-30 09:39:34.887  5617  5663 I jxcore-log: ok 149 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-30 09:39:34.887  5617  5663 I jxcore-log: 
09-30 09:39:34.887  5617  5663 I jxcore-log: ok 150 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-30 09:39:34.887  5617  5663 I jxcore-log: 
09-30 09:39:34.887  5617  5663 I jxcore-log: ok 151 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-30 09:39:34.887  5617  5663 I jxcore-log: 
09-30 09:39:34.887  5617  5663 I jxcore-log: ok 152 Salti was called once
09-30 09:39:34.887  5617  5663 I jxcore-log: 
09-30 09:39:34.888  5617  5663 I jxcore-log: ok 153 Salti was called with 4 arguments
09-30 09:39:34.888  5617  5663 I jxcore-log: 
09-30 09:39:34.888  5617  5663 I jxcore-log: ok 154 Salti was called with 'dbName' as 1-st argument
09-30 09:39:34.888  5617  5663 I jxcore-log: 
09-30 09:39:34.888  5617  5663 I jxcore-log: ok 155 Salti was called with 'acl' as 2-st argument
09-30 09:39:34.888  5617  5663 I jxcore-log: 
,09-30 09:39:34.889  5617  5663 I jxcore-log: ok 156 Salti was called with 'thaliIdCallback' as 3-st argument
09-30 09:39:34.889  5617  5663 I jxcore-log: 
,09-30 09:39:34.889  5617  5663 I jxcore-log: ok 157 Salti was called with 'options' as 4-st argument
09-30 09:39:34.889  5617  5663 I jxcore-log: 
,09-30 09:39:34.890  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 09:39:34.890  5617  5663 I jxcore-log: 
,09-30 09:39:34.891  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 09:39:34.891  5617  5663 I jxcore-log: 
,09-30 09:39:34.892  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 09:39:34.892  5617  5663 I jxcore-log: 
,09-30 09:39:34.895  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'start listening for advertisements'
09-30 09:39:34.895  5617  5663 I jxcore-log: 
,09-30 09:39:34.899  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'start update advertising and listening'
09-30 09:39:34.899  5617  5663 I jxcore-log: 
,09-30 09:39:34.925  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliWifiInfrastructure: 'listening 40638'
09-30 09:39:34.925  5617  5663 I jxcore-log: 
,09-30 09:39:34.928  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 09:39:34.928  5617  5663 I jxcore-log: 
,09-30 09:39:34.948  5617  5663 I jxcore-log: ok 158 ThaliMobile.start was called once
09-30 09:39:34.948  5617  5663 I jxcore-log: 
,09-30 09:39:34.948  5617  5663 I jxcore-log: ok 159 ThaliMobile.start was called with 3 arguments
09-30 09:39:34.948  5617  5663 I jxcore-log: 
09-30 09:39:34.948  5617  5663 I jxcore-log: ok 160 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 09:39:34.948  5617  5663 I jxcore-log: 
09-30 09:39:34.949  5617  5663 I jxcore-log: ok 161 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 09:39:34.949  5617  5663 I jxcore-log: 
,09-30 09:39:34.949  5617  5663 I jxcore-log: ok 162 ThaliMobile.start was called with 'networkType' as 3-st argument
09-30 09:39:34.949  5617  5663 I jxcore-log: 
09-30 09:39:34.949  5617  5663 I jxcore-log: ok 163 ThaliMobile.startListeningForAdvertisements was called once
09-30 09:39:34.949  5617  5663 I jxcore-log: 
09-30 09:39:34.949  5617  5663 I jxcore-log: ok 164 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 09:39:34.949  5617  5663 I jxcore-log: 
09-30 09:39:34.949  5617  5663 I jxcore-log: ok 165 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 09:39:34.949  5617  5663 I jxcore-log: 
09-30 09:39:34.949  5617  5663 I jxcore-log: ok 166 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 09:39:34.949  5617  5663 I jxcore-log: 
,09-30 09:39:34.950  5617  5663 I jxcore-log: ok 167 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 09:39:34.950  5617  5663 I jxcore-log: 
09-30 09:39:34.950  5617  5663 I jxcore-log: ok 168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 09:39:34.950  5617  5663 I jxcore-log: 
09-30 09:39:34.950  5617  5663 I jxcore-log: ok 169 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 09:39:34.950  5617  5663 I jxcore-log: 
09-30 09:39:34.950  5617  5663 I jxcore-log: ok 170 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 09:39:34.950  5617  5663 I jxcore-log: 
09-30 09:39:34.950  5617  5663 I jxcore-log: ok 171 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 09:39:34.950  5617  5663 I jxcore-log: 
09-30 09:39:34.951  5617  5663 I jxcore-log: ok 172 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 09:39:34.951  5617  5663 I jxcore-log: 
09-30 09:39:34.951  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 09:39:34.951  5617  5663 I jxcore-log: 
,09-30 09:39:34.952  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 09:39:34.952  5617  5663 I jxcore-log: 
09-30 09:39:34.954  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 09:39:34.954  5617  5663 I jxcore-log: 
,09-30 09:39:34.955  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 09:39:34.955  5617  5663 I jxcore-log: 
,09-30 09:39:34.960  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 09:39:34.960  5617  5663 I jxcore-log: 
,09-30 09:39:34.962  5617  5663 I jxcore-log: 2016-09-30 13:39:34 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 09:39:34.962  5617  5663 I jxcore-log: 
,09-30 09:39:34.964  5617  5663 I jxcore-log: ok 173 ThaliMobile.stop was called once
09-30 09:39:34.964  5617  5663 I jxcore-log: 
,09-30 09:39:34.965  5617  5663 I jxcore-log: ok 174 ThaliMobile.stop was called with 0 arguments
09-30 09:39:34.965  5617  5663 I jxcore-log: 
09-30 09:39:34.965  5617  5663 I jxcore-log: ok 175 ThaliMobile.stopListeningForAdvertisements was called once
09-30 09:39:34.965  5617  5663 I jxcore-log: 
09-30 09:39:34.965  5617  5663 I jxcore-log: ok 176 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-30 09:39:34.965  5617  5663 I jxcore-log: 
,09-30 09:39:34.965  5617  5663 I jxcore-log: ok 177 ThaliMobile.stopAdvertisingAndListening was called once
09-30 09:39:34.965  5617  5663 I jxcore-log: 
09-30 09:39:34.965  5617  5663 I jxcore-log: ok 178 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-30 09:39:34.965  5617  5663 I jxcore-log: 
09-30 09:39:34.966  5617  5663 I jxcore-log: ok 179 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-30 09:39:34.966  5617  5663 I jxcore-log: 
09-30 09:39:34.966  5617  5663 I jxcore-log: ok 180 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-30 09:39:34.966  5617  5663 I jxcore-log: 
09-30 09:39:34.966  5617  5663 I jxcore-log: ok 181 ThaliPullReplicationFromNotification.prototype.stop was called once
09-30 09:39:34.966  5617  5663 I jxcore-log: 
09-30 09:39:34.966  5617  5663 I jxcore-log: ok 182 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-30 09:39:34.966  5617  5663 I jxcore-log: 
,09-30 09:39:34.975  5617  5663 I jxcore-log: # teardown
09-30 09:39:34.975  5617  5663 I jxcore-log: 
,09-30 09:39:35.118  5617  5663 I jxcore-log: # setup
09-30 09:39:35.118  5617  5663 I jxcore-log: 
,09-30 09:39:35.183  5617  5663 I jxcore-log: # test thali manager multiple starts and stops
09-30 09:39:35.183  5617  5663 I jxcore-log: 
,09-30 09:39:35.381  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 09:39:35.381  5617  5663 I jxcore-log: 
,09-30 09:39:35.387  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 09:39:35.387  5617  5663 I jxcore-log: 
,09-30 09:39:35.389  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 09:39:35.389  5617  5663 I jxcore-log: 
,09-30 09:39:35.408  5617  5663 I jxcore-log: ok 183 expressPouchDB was called once
09-30 09:39:35.408  5617  5663 I jxcore-log: 
,09-30 09:39:35.409  5617  5663 I jxcore-log: ok 184 expressPouchDB was called with 2 arguments
09-30 09:39:35.409  5617  5663 I jxcore-log: 
09-30 09:39:35.409  5617  5663 I jxcore-log: ok 185 expressPouchDB was called with 'PouchDB' as 1-st argument
09-30 09:39:35.409  5617  5663 I jxcore-log: 
09-30 09:39:35.409  5617  5663 I jxcore-log: ok 186 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-30 09:39:35.409  5617  5663 I jxcore-log: 
,09-30 09:39:35.409  5617  5663 I jxcore-log: ok 187 PouchDB was called once
09-30 09:39:35.409  5617  5663 I jxcore-log: 
09-30 09:39:35.410  5617  5663 I jxcore-log: ok 188 PouchDB was called with 1 arguments
09-30 09:39:35.410  5617  5663 I jxcore-log: 
09-30 09:39:35.410  5617  5663 I jxcore-log: ok 189 PouchDB was called with 'dbName' as 1-st argument
09-30 09:39:35.410  5617  5663 I jxcore-log: 
09-30 09:39:35.410  5617  5663 I jxcore-log: ok 190 ThaliSendNotificationBasedOnReplication was called once
09-30 09:39:35.410  5617  5663 I jxcore-log: 
,09-30 09:39:35.411  5617  5663 I jxcore-log: ok 191 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-30 09:39:35.411  5617  5663 I jxcore-log: 
09-30 09:39:35.411  5617  5663 I jxcore-log: ok 192 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-30 09:39:35.411  5617  5663 I jxcore-log: 
09-30 09:39:35.411  5617  5663 I jxcore-log: ok 193 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-30 09:39:35.411  5617  5663 I jxcore-log: 
,09-30 09:39:35.411  5617  5663 I jxcore-log: ok 194 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-30 09:39:35.411  5617  5663 I jxcore-log: 
09-30 09:39:35.411  5617  5663 I jxcore-log: ok 195 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-30 09:39:35.411  5617  5663 I jxcore-log: 
09-30 09:39:35.412  5617  5663 I jxcore-log: ok 196 ThaliPullReplicationFromNotification was called once
09-30 09:39:35.412  5617  5663 I jxcore-log: 
09-30 09:39:35.412  5617  5663 I jxcore-log: ok 197 ThaliPullReplicationFromNotification was called with 4 arguments
09-30 09:39:35.412  5617  5663 I jxcore-log: 
,09-30 09:39:35.412  5617  5663 I jxcore-log: ok 198 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-30 09:39:35.412  5617  5663 I jxcore-log: 
09-30 09:39:35.412  5617  5663 I jxcore-log: ok 199 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-30 09:39:35.412  5617  5663 I jxcore-log: 
09-30 09:39:35.412  5617  5663 I jxcore-log: ok 200 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-30 09:39:35.412  5617  5663 I jxcore-log: 
09-30 09:39:35.412  5617  5663 I jxcore-log: ok 201 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-30 09:39:35.412  5617  5663 I jxcore-log: 
09-30 09:39:35.413  5617  5663 I jxcore-log: ok 202 Salti was called once
09-30 09:39:35.413  5617  5663 I jxcore-log: 
,09-30 09:39:35.413  5617  5663 I jxcore-log: ok 203 Salti was called with 4 arguments
09-30 09:39:35.413  5617  5663 I jxcore-log: 
09-30 09:39:35.413  5617  5663 I jxcore-log: ok 204 Salti was called with 'dbName' as 1-st argument
09-30 09:39:35.413  5617  5663 I jxcore-log: 
09-30 09:39:35.413  5617  5663 I jxcore-log: ok 205 Salti was called with 'acl' as 2-st argument
09-30 09:39:35.413  5617  5663 I jxcore-log: 
09-30 09:39:35.413  5617  5663 I jxcore-log: ok 206 Salti was called with 'thaliIdCallback' as 3-st argument
09-30 09:39:35.413  5617  5663 I jxcore-log: 
09-30 09:39:35.413  5617  5663 I jxcore-log: ok 207 Salti was called with 'options' as 4-st argument
09-30 09:39:35.413  5617  5663 I jxcore-log: 
,09-30 09:39:35.414  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 09:39:35.414  5617  5663 I jxcore-log: 
09-30 09:39:35.415  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 09:39:35.415  5617  5663 I jxcore-log: 
,09-30 09:39:35.415  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 09:39:35.415  5617  5663 I jxcore-log: 
,09-30 09:39:35.418  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start listening for advertisements'
09-30 09:39:35.418  5617  5663 I jxcore-log: 
,09-30 09:39:35.421  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start update advertising and listening'
09-30 09:39:35.421  5617  5663 I jxcore-log: 
,09-30 09:39:35.426  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliWifiInfrastructure: 'listening 43518'
09-30 09:39:35.426  5617  5663 I jxcore-log: 
,09-30 09:39:35.428  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 09:39:35.428  5617  5663 I jxcore-log: 
,09-30 09:39:35.463  5617  5663 I jxcore-log: ok 208 ThaliMobile.start was called once
09-30 09:39:35.463  5617  5663 I jxcore-log: 
,09-30 09:39:35.463  5617  5663 I jxcore-log: ok 209 ThaliMobile.start was called with 3 arguments
09-30 09:39:35.463  5617  5663 I jxcore-log: 
09-30 09:39:35.463  5617  5663 I jxcore-log: ok 210 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 09:39:35.463  5617  5663 I jxcore-log: 
09-30 09:39:35.464  5617  5663 I jxcore-log: ok 211 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 09:39:35.464  5617  5663 I jxcore-log: 
09-30 09:39:35.464  5617  5663 I jxcore-log: ok 212 ThaliMobile.start was called with 'networkType' as 3-st argument
09-30 09:39:35.464  5617  5663 I jxcore-log: 
09-30 09:39:35.464  5617  5663 I jxcore-log: ok 213 ThaliMobile.startListeningForAdvertisements was called once
09-30 09:39:35.464  5617  5663 I jxcore-log: 
,09-30 09:39:35.464  5617  5663 I jxcore-log: ok 214 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 09:39:35.464  5617  5663 I jxcore-log: 
09-30 09:39:35.464  5617  5663 I jxcore-log: ok 215 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 09:39:35.464  5617  5663 I jxcore-log: 
09-30 09:39:35.464  5617  5663 I jxcore-log: ok 216 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 09:39:35.464  5617  5663 I jxcore-log: 
09-30 09:39:35.465  5617  5663 I jxcore-log: ok 217 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 09:39:35.465  5617  5663 I jxcore-log: 
09-30 09:39:35.465  5617  5663 I jxcore-log: ok 218 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 09:39:35.465  5617  5663 I jxcore-log: 
09-30 09:39:35.465  5617  5663 I jxcore-log: ok 219 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 09:39:35.465  5617  5663 I jxcore-log: 
,09-30 09:39:35.465  5617  5663 I jxcore-log: ok 220 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 09:39:35.465  5617  5663 I jxcore-log: 
09-30 09:39:35.465  5617  5663 I jxcore-log: ok 221 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 09:39:35.465  5617  5663 I jxcore-log: 
09-30 09:39:35.465  5617  5663 I jxcore-log: ok 222 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 09:39:35.465  5617  5663 I jxcore-log: 
,09-30 09:39:35.466  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 09:39:35.466  5617  5663 I jxcore-log: 
09-30 09:39:35.467  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 09:39:35.467  5617  5663 I jxcore-log: 
,09-30 09:39:35.469  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 09:39:35.469  5617  5663 I jxcore-log: 
,09-30 09:39:35.470  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 09:39:35.470  5617  5663 I jxcore-log: 
,09-30 09:39:35.474  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 09:39:35.474  5617  5663 I jxcore-log: 
,09-30 09:39:35.476  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 09:39:35.476  5617  5663 I jxcore-log: 
,09-30 09:39:35.481  5617  5663 I jxcore-log: ok 223 ThaliMobile.stop was called once
09-30 09:39:35.481  5617  5663 I jxcore-log: 
,09-30 09:39:35.482  5617  5663 I jxcore-log: ok 224 ThaliMobile.stop was called with 0 arguments
09-30 09:39:35.482  5617  5663 I jxcore-log: 
,09-30 09:39:35.482  5617  5663 I jxcore-log: ok 225 ThaliMobile.stopListeningForAdvertisements was called once
09-30 09:39:35.482  5617  5663 I jxcore-log: 
09-30 09:39:35.482  5617  5663 I jxcore-log: ok 226 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-30 09:39:35.482  5617  5663 I jxcore-log: 
09-30 09:39:35.482  5617  5663 I jxcore-log: ok 227 ThaliMobile.stopAdvertisingAndListening was called once
09-30 09:39:35.482  5617  5663 I jxcore-log: 
09-30 09:39:35.482  5617  5663 I jxcore-log: ok 228 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-30 09:39:35.482  5617  5663 I jxcore-log: 
,09-30 09:39:35.483  5617  5663 I jxcore-log: ok 229 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-30 09:39:35.483  5617  5663 I jxcore-log: 
09-30 09:39:35.483  5617  5663 I jxcore-log: ok 230 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-30 09:39:35.483  5617  5663 I jxcore-log: 
,09-30 09:39:35.483  5617  5663 I jxcore-log: ok 231 ThaliPullReplicationFromNotification.prototype.stop was called once
09-30 09:39:35.483  5617  5663 I jxcore-log: 
09-30 09:39:35.483  5617  5663 I jxcore-log: ok 232 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-30 09:39:35.483  5617  5663 I jxcore-log: 
,09-30 09:39:35.484  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 09:39:35.484  5617  5663 I jxcore-log: 
09-30 09:39:35.484  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 09:39:35.484  5617  5663 I jxcore-log: 
,09-30 09:39:35.485  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 09:39:35.485  5617  5663 I jxcore-log: 
09-30 09:39:35.487  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start listening for advertisements'
09-30 09:39:35.487  5617  5663 I jxcore-log: 
,09-30 09:39:35.489  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start update advertising and listening'
09-30 09:39:35.489  5617  5663 I jxcore-log: 
,09-30 09:39:35.493  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliWifiInfrastructure: 'listening 41065'
09-30 09:39:35.493  5617  5663 I jxcore-log: 
,09-30 09:39:35.495  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 09:39:35.495  5617  5663 I jxcore-log: 
,09-30 09:39:35.497  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 09:39:35.497  5617  5663 I jxcore-log: 
,09-30 09:39:35.498  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 09:39:35.498  5617  5663 I jxcore-log: 
,09-30 09:39:35.500  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 09:39:35.500  5617  5663 I jxcore-log: 
,09-30 09:39:35.501  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 09:39:35.501  5617  5663 I jxcore-log: 
,09-30 09:39:35.506  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 09:39:35.506  5617  5663 I jxcore-log: 
,09-30 09:39:35.507  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 09:39:35.507  5617  5663 I jxcore-log: 
,09-30 09:39:35.510  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 09:39:35.510  5617  5663 I jxcore-log: 
,09-30 09:39:35.511  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 09:39:35.511  5617  5663 I jxcore-log: 
,09-30 09:39:35.511  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 09:39:35.511  5617  5663 I jxcore-log: 
,09-30 09:39:35.514  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start listening for advertisements'
09-30 09:39:35.514  5617  5663 I jxcore-log: 
,09-30 09:39:35.516  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start update advertising and listening'
09-30 09:39:35.516  5617  5663 I jxcore-log: 
,09-30 09:39:35.521  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliWifiInfrastructure: 'listening 44488'
09-30 09:39:35.521  5617  5663 I jxcore-log: 
,09-30 09:39:35.522  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 09:39:35.522  5617  5663 I jxcore-log: 
,09-30 09:39:35.524  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 09:39:35.524  5617  5663 I jxcore-log: 
,09-30 09:39:35.525  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 09:39:35.525  5617  5663 I jxcore-log: 
,09-30 09:39:35.527  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 09:39:35.527  5617  5663 I jxcore-log: 
,09-30 09:39:35.528  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 09:39:35.528  5617  5663 I jxcore-log: 
,09-30 09:39:35.538  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 09:39:35.538  5617  5663 I jxcore-log: 
,09-30 09:39:35.540  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 09:39:35.540  5617  5663 I jxcore-log: 
,09-30 09:39:35.543  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 09:39:35.543  5617  5663 I jxcore-log: 
,09-30 09:39:35.544  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 09:39:35.544  5617  5663 I jxcore-log: 
09-30 09:39:35.544  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 09:39:35.544  5617  5663 I jxcore-log: 
,09-30 09:39:35.546  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start listening for advertisements'
09-30 09:39:35.546  5617  5663 I jxcore-log: 
,09-30 09:39:35.548  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start update advertising and listening'
09-30 09:39:35.548  5617  5663 I jxcore-log: 
,09-30 09:39:35.552  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliWifiInfrastructure: 'listening 37294'
09-30 09:39:35.552  5617  5663 I jxcore-log: 
,09-30 09:39:35.554  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 09:39:35.554  5617  5663 I jxcore-log: 
,09-30 09:39:35.557  5617  5663 I jxcore-log: ok 233 ThaliMobile.start was called once
09-30 09:39:35.557  5617  5663 I jxcore-log: 
,09-30 09:39:35.557  5617  5663 I jxcore-log: ok 234 ThaliMobile.start was called with 3 arguments
09-30 09:39:35.557  5617  5663 I jxcore-log: 
09-30 09:39:35.558  5617  5663 I jxcore-log: ok 235 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 09:39:35.558  5617  5663 I jxcore-log: 
09-30 09:39:35.558  5617  5663 I jxcore-log: ok 236 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 09:39:35.558  5617  5663 I jxcore-log: 
,09-30 09:39:35.558  5617  5663 I jxcore-log: ok 237 ThaliMobile.start was called with 'networkType' as 3-st argument
09-30 09:39:35.558  5617  5663 I jxcore-log: 
09-30 09:39:35.558  5617  5663 I jxcore-log: ok 238 ThaliMobile.startListeningForAdvertisements was called once
09-30 09:39:35.558  5617  5663 I jxcore-log: 
,09-30 09:39:35.558  5617  5663 I jxcore-log: ok 239 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 09:39:35.558  5617  5663 I jxcore-log: 
09-30 09:39:35.559  5617  5663 I jxcore-log: ok 240 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 09:39:35.559  5617  5663 I jxcore-log: 
09-30 09:39:35.559  5617  5663 I jxcore-log: ok 241 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 09:39:35.559  5617  5663 I jxcore-log: 
09-30 09:39:35.559  5617  5663 I jxcore-log: ok 242 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 09:39:35.559  5617  5663 I jxcore-log: 
09-30 09:39:35.559  5617  5663 I jxcore-log: ok 243 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 09:39:35.559  5617  5663 I jxcore-log: 
,09-30 09:39:35.559  5617  5663 I jxcore-log: ok 244 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 09:39:35.559  5617  5663 I jxcore-log: 
09-30 09:39:35.560  5617  5663 I jxcore-log: ok 245 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 09:39:35.560  5617  5663 I jxcore-log: 
09-30 09:39:35.560  5617  5663 I jxcore-log: ok 246 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 09:39:35.560  5617  5663 I jxcore-log: 
09-30 09:39:35.560  5617  5663 I jxcore-log: ok 247 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 09:39:35.560  5617  5663 I jxcore-log: 
09-30 09:39:35.560  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 09:39:35.560  5617  5663 I jxcore-log: 
,09-30 09:39:35.561  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 09:39:35.561  5617  5663 I jxcore-log: 
09-30 09:39:35.563  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 09:39:35.563  5617  5663 I jxcore-log: 
,09-30 09:39:35.564  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 09:39:35.564  5617  5663 I jxcore-log: 
,09-30 09:39:35.568  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 09:39:35.568  5617  5663 I jxcore-log: 
,09-30 09:39:35.569  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 09:39:35.569  5617  5663 I jxcore-log: 
,09-30 09:39:35.575  5617  5663 I jxcore-log: # teardown
09-30 09:39:35.575  5617  5663 I jxcore-log: 
,09-30 09:39:35.601  5617  5663 I jxcore-log: # setup
09-30 09:39:35.601  5617  5663 I jxcore-log: 
,09-30 09:39:35.667  5617  5663 I jxcore-log: # test write,
09-30 09:39:35.667  5617  5663 I jxcore-log: 
,09-30 09:39:35.875  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 09:39:35.875  5617  5663 I jxcore-log: 
,09-30 09:39:35.878  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 09:39:35.878  5617  5663 I jxcore-log: 
,09-30 09:39:35.880  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 09:39:35.880  5617  5663 I jxcore-log: 
,09-30 09:39:35.903  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 09:39:35.903  5617  5663 I jxcore-log: 
,09-30 09:39:35.904  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 09:39:35.904  5617  5663 I jxcore-log: 
,09-30 09:39:35.904  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 09:39:35.904  5617  5663 I jxcore-log: 
,09-30 09:39:35.906  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start listening for advertisements'
09-30 09:39:35.906  5617  5663 I jxcore-log: 
,09-30 09:39:35.911  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'start update advertising and listening'
09-30 09:39:35.911  5617  5663 I jxcore-log: 
,09-30 09:39:35.916  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliWifiInfrastructure: 'listening 43383'
09-30 09:39:35.916  5617  5663 I jxcore-log: 
,09-30 09:39:35.919  5617  5663 I jxcore-log: 2016-09-30 13:39:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 09:39:35.919  5617  5663 I jxcore-log: 
,09-30 09:39:36.728  5617  5663 I jxcore-log: 2016-09-30 13:39:36 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-30 09:39:36.728  5617  5663 I jxcore-log: 
,09-30 09:39:36.756  5617  5663 I jxcore-log: 2016-09-30 13:39:36 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-30 09:39:36.756  5617  5663 I jxcore-log: 
,09-30 09:39:37.086  5617  5663 I jxcore-log: 2016-09-30 13:39:37 - ERROR thaliSendNotificationBasedOnReplication: 'Got an error on the replication change listener - {"name":"AssertionError","actual":null,"expected":true,"operator":"==","message":"If beacons werepreviously updated then there has to be a refresh timer for them.","stack":"ok@assert.js:126:1\nThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9\nPouchDBGenerator/PouchAlt.prototype.addListener/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:9"}'
09-30 09:39:37.086  5617  5663 I jxcore-log: 
,09-30 09:39:37.087  5617  5663 I jxcore-log: 2016-09-30 13:39:37 - ERROR TestsProcess: 'uncaught promise rejection, error: 'AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.', stack: 'ok@assert.js:126:1
09-30 09:39:37.087  5617  5663 I jxcore-log: ThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9
09-30 09:39:37.087  5617  5663 I jxcore-log: PouchDBGenerator/PouchAlt.prototype.addListener/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:9''
09-30 09:39:37.087  5617  5663 I jxcore-log: 
09-30 09:39:37.087  5617  5663 I jxcore-log: 2016-09-30 13:39:37 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-30 09:39:37.087  5617  5663 I jxcore-log: 
,09-30 09:39:37.695  6006  6006 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-30 09:39:37.719  6006  6006 D AndroidRuntime: CheckJNI is OFF
,09-30 09:39:37.748  6006  6006 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-30 09:39:37.775  6006  6006 I Radio-JNI: register_android_hardware_Radio DONE
,09-30 09:39:37.790  6006  6006 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-30 09:39:37.799   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-30 09:39:37.800   927   940 I ActivityManager: Killing 5617:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-30 09:39:37.918   927  3685 I WindowState: WIN DEATH: Window{f43fbc3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-30 09:39:37.919   927  2908 D WifiService: Client connection lost with reason: 4
,09-30 09:39:37.919   927   937 D GraphicsStats: Buffer count: 2
,09-30 09:39:37.962   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-30 09:39:37.962   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-30 09:39:37.964   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-30 09:39:37.964   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-30 09:39:37.964   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:39:37.964   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:37.964   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 09:39:37.964   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 09:39:37.965   927   940 I ActivityManager:   Force finishing activity ActivityRecord{5fc4e74 u0 com.test.thalitest/.MainActivity t2}
09-30 09:39:37.965   927   950 I art     : Starting a blocking GC Explicit
,09-30 09:39:37.975   927  3555 W ActivityManager: Spurious death for ProcessRecord{d1696db 0:com.test.thalitest/u0a77}, curProc for 5617: null
,09-30 09:39:37.979   927   945 W WindowManager: Attempted to add application window with unknown token Token{e0cef9d ActivityRecord{5fc4e74 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-30 09:39:37.979   927   945 W WindowManager: Token{e0cef9d ActivityRecord{5fc4e74 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{e0cef9d ActivityRecord{5fc4e74 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-30 09:39:37.979   927   945 W WindowManager: view not successfully added to wm, removing view
09-30 09:39:37.979   927   945 W WindowManager: Exception when adding starting window
09-30 09:39:37.979   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{75e5642 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-30 09:39:37.979   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-30 09:39:37.979   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-30 09:39:37.979   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-30 09:39:37.979   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-30 09:39:37.979   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-30 09:39:37.979   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:39:37.979   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:37.979   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 09:39:37.979   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 09:39:38.055   927   950 I art     : Explicit concurrent mark sweep GC freed 75731(5MB) AllocSpace objects, 30(1240KB) LOS objects, 33% free, 29MB/43MB, paused 1.581ms total 89.589ms
,09-30 09:39:38.079   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-30 09:39:38.082  6006  6006 I art     : System.exit called, status: 0
,09-30 09:39:38.082  6006  6006 I AndroidRuntime: VM exiting with result code 0.
,09-30 09:39:38.098   927   950 I ActivityManager: Start proc 6016:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-30 09:39:38.098   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-30 09:39:38.104   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-30 09:39:38.109  5896  5896 D BluetoothMapAppObserver: onReceive
,09-30 09:39:38.109  5896  5896 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-30 09:39:38.116   927  2899 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-30 09:39:38.120  3614  3614 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-30 09:39:38.122  3665  4028 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-30 09:39:38.140  3727  3727 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-30 09:39:38.143  3614  6028 I Keyboard.Facilitator.DecoderInitializer: run()
,09-30 09:39:38.162  3614  6028 I Decoder : createOrResetDecoder
,09-30 09:39:38.165  3356  6031 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-30 09:39:38.196  3539  3539 E NetworkScheduler.SchedulerReceiver: Invalid parameter app,
,09-30 09:39:38.196  3539  3539 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-30 09:39:38.201   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-30 09:39:38.197   435   435 W kworker/5:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 09:39:38.201   435   435 W kworker/5:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 09:39:38.211   435   435 W kworker/5:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-30 09:39:38.217  3539  3539 I ConfigService: onCreate
,09-30 09:39:38.217  3960  6036 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-30 09:39:38.218  3960  6036 D AccountUtils: Clearing selected account for com.test.thalitest
,09-30 09:39:38.221   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-30 09:39:38.221  3755  3905 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-30 09:39:38.221  3539  6037 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(,SQLiteDatabase.java:694)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-30 09:39:38.221  3539  6037 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-30 09:39:38.222   927   939 E PackageManager: Failed to write settings, restoring backup
09-30 09:39:38.222   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-30 09:39:38.222   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-30 09:39:38.222   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-30 09:39:38.222   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-30 09:39:38.222   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-30 09:39:38.222   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:39:38.222   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:38.222   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 09:39:38.223  3539  6037 W SQLiteOpenHelper: Opened config.db in read-only mode
09-30 09:39:38.224   927   940 E DropBoxManagerService: Can't write: system_server_wtf
09-30 09:39:38.224   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 09:39:38.224   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 09:39:38.224   927   940 E DropBoxManagerService: 	... 13 more
09-30 09:39:38.239   927  3721 I ActivityManager: Start proc 6040:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-30 09:39:38.240  3755  3905 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-30 09:39:38.240  3755  3905 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3755
09-30 09:39:38.240  3755  3905 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:38.240  3755  3905 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 09:39:38.244   927  3153 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-30 09:39:38.245   927  6050 E DropBoxManagerService: Can't write: system_app_crash
09-30 09:39:38.245   927  6050 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 09:39:38.245   927  6050 E DropBoxManagerService: 	... 5 more
09-30 09:39:38.248  3755  3905 I Process : Sending signal. PID: 3755 SIG: 9
09-30 09:39:38.258  3614  6028 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-30 09:39:38.263  3356  6031 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-30 09:39:38.286  3960  6036 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
09-30 09:39:38.300  3356  6031 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-30 09:39:38.300  3356  6031 E AndroidRuntime: Process: android.process.acore, PID: 3356
09-30 09:39:38.300  3356  6031 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:38.300  3356  6031 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: Can't write: system_app_crash
09-30 09:39:38.302   927  6056 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 09:39:38.302   927  6056 E DropBoxManagerService: 	... 5 more
,09-30 09:39:38.305  3960  6036 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:38.305  3960  6036 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:38.306  3960  6036 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 09:39:38.307  3960  6036 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-30 09:39:38.320  3356  6031 I Process : Sending signal. PID: 3356 SIG: 9
,09-30 09:39:38.401  3960  6058 I GMPM-SVC: App measurement is starting up
,09-30 09:39:38.409  3960  6058 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-30 09:39:38.410  3960  6058 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-30 09:39:38.436   927   937 I WindowState: WIN DEATH: Window{7bb1446 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-30 09:39:38.436   927  3158 D GraphicsStats: Buffer count: 1
,09-30 09:39:38.440   927   938 I ActivityManager: Process android.process.acore (pid 3356) has died
,09-30 09:39:38.441   927   938 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-30 09:39:38.442   927  3685 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3755) has died
,09-30 09:39:38.442   927  3685 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-30 09:39:38.444   927  3685 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 09:39:38.460   927   940 I ActivityManager: Start proc 6061:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 09:39:38.507  6061  6061 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:39:38.507  6061  6061 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 09:39:38.507  6061  6061 D AndroidRuntime: Shutting down VM
,09-30 09:39:38.514  6061  6061 E AndroidRuntime: FATAL EXCEPTION: main
09-30 09:39:38.514  6061  6061 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6061
09-30 09:39:38.514  6061  6061 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 09:39:38.514  6061  6061 E AndroidRuntime: 	... 10 more
,09-30 09:39:38.516   927  3158 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 09:39:38.516   927  6074 E DropBoxManagerService: Can't write: system_app_crash
09-30 09:39:38.516   927  6074 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 09:39:38.516   927  6074 E DropBoxManagerService: 	... 5 more
,09-30 09:39:38.517  6061  6061 I Process : Sending signal. PID: 6061 SIG: 9
,09-30 09:39:38.532   927  3724 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6061) has died
,09-30 09:39:38.533   927  3724 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 09:39:38.548   927   940 I ActivityManager: Start proc 6075:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
