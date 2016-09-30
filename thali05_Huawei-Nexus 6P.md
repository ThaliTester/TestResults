#### Test 87463757dc979f8_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-30 06:36:16.191   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-30 06:36:16.191   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-30 06:36:16.249   927  5443 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
--------- beginning of system
09-30 06:36:16.896   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 06:36:17.932  5684  5684 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-30 06:36:17.938  5684  5684 D AndroidRuntime: CheckJNI is OFF
09-30 06:36:17.967  5684  5684 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-30 06:36:18.002  5684  5684 I Radio-JNI: register_android_hardware_Radio DONE
09-30 06:36:18.017  5684  5684 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-30 06:36:18.021   927  3311 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-30 06:36:18.065   927  3311 I ActivityManager: Start proc 5693:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-30 06:36:18.070  5684  5684 D AndroidRuntime: Shutting down VM
09-30 06:36:18.226   927  3066 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 06:36:18.422   927  3901 I WindowManager: Screenshot max retries 4 of Token{281d14f ActivityRecord{8e9bfae u0 com.test.thalitest/.MainActivity t2}} appWin=Window{c6e1686 u0 Starting com.test.thalitest} drawState=2
,09-30 06:36:18.498  5693  5693 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-30 06:36:18.534  5693  5693 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-30 06:36:18.557  5693  5693 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 1753-1772)
,09-30 06:36:18.558  5693  5693 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 06:36:18.578  5693  5693 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5e5546f}
,09-30 06:36:18.578  5693  5693 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-30 06:36:18.579  5693  5693 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-30 06:36:18.584  5693  5693 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-30 06:36:18.586  5693  5693 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-30 06:36:18.619  5693  5693 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-30 06:36:18.638  5693  5693 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-30 06:36:18.639  5693  5693 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-30 06:36:18.639  5693  5693 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-30 06:36:18.639  5693  5693 I Adreno  : Build Date                       : 12/06/15
09-30 06:36:18.639  5693  5693 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-30 06:36:18.639  5693  5693 I Adreno  : Local Branch                     : mybranch17112971
09-30 06:36:18.639  5693  5693 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-30 06:36:18.639  5693  5693 I Adreno  : Remote Branch                    : NONE
09-30 06:36:18.639  5693  5693 I Adreno  : Reconstruct Branch               : NOTHING
,09-30 06:36:18.684   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@155a255:true
,09-30 06:36:18.719   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22473]" dev="sockfs" ino=22473 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-30 06:36:18.719   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22473]" dev="sockfs" ino=22473 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 06:36:18.732  5693  5693 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-30 06:36:18.740  5693  5693 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-30 06:36:18.767  5693  5730 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-30 06:36:18.762   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32768]" dev="sockfs" ino=32768 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-30 06:36:18.762   406   406 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32768]" dev="sockfs" ino=32768 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 06:36:18.766  3845  3845 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[29826]" dev="sockfs" ino=29826 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 06:36:18.766  3845  3845 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29826]" dev="sockfs" ino=29826 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 06:36:18.772  5693  5717 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-30 06:36:18.803  5693  5730 I OpenGLRenderer: Initialized EGL, version 1.4
,09-30 06:36:18.873   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +450ms (total +831ms)
,09-30 06:36:18.897  5693  5693 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5693
,09-30 06:36:19.003  5693  5693 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-30 06:36:19.103  5693  5733 D jxcore_app_log: JniHelper::setJavaVM(0xf4ebc000), pthread_self() = -583792336
,09-30 06:36:19.107  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-30 06:36:19.107  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-30 06:36:19.107  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-30 06:36:19.107  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-30 06:36:19.107  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-30 06:36:19.107  5693  5733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de49a7d added. We now have 1 listener(s)
,09-30 06:36:19.109  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-30 06:36:19.110  5693  5733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:36:19.110  5693  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 06:36:19.110  5693  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-30 06:36:19.112  5693  5733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a222e40 added. We now have 1 listener(s)
,09-30 06:36:19.113  5693  5733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:36:19.117   927  3076 D WifiService: New client listening to asynchronous messages
,09-30 06:36:19.117  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 06:36:19.117  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-30 06:36:19.118  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-30 06:36:19.118  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-30 06:36:19.118  5693  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-30 06:36:19.119  5693  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:36:19.119  5693  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-30 06:36:19.123  5693  5733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-30 06:36:19.123  5693  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:36:19.123  5693  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:19.123  5693  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:19.123  5693  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:19.123  5693  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:36:19.123  5693  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:19.123  5693  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:19.123  5693  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:19.123  5693  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-30 06:36:19.123  5693  5733 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:36:19.124  5693  5733 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-30 06:36:19.193  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:19.195  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:19.198  5693  5693 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-30 06:36:19.408  5693  5739 W jxcore-log: Initializing JXcore engine
,09-30 06:36:19.408  5693  5739 W jxcore-log: JXcore engine is ready
,09-30 06:36:19.436  5739  5739 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12347 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-30 06:36:19.436  5739  5739 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16391]" dev="sockfs" ino=16391 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-30 06:36:19.436  5739  5739 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-30 06:36:19.436  5739  5739 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33174]" dev="sockfs" ino=33174 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-30 06:36:19.445  5693  5739 W jxcore-log: Starting JXcore engine
,09-30 06:36:19.503  5693  5739 W jxcore-log: Platform android
09-30 06:36:19.503  5693  5739 W jxcore-log: 
,09-30 06:36:19.503  5693  5739 W jxcore-log: Process ARCH arm
09-30 06:36:19.503  5693  5739 W jxcore-log: 
,09-30 06:36:19.600  5693  5739 I jxcore-log: JXcore Cordova bridge is ready!
09-30 06:36:19.600  5693  5739 I jxcore-log: 
,09-30 06:36:19.600  5693  5739 W jxcore-log: JXcore engine is started
,09-30 06:36:19.607  5693  5733 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-30 06:36:19.613  5693  5693 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-30 06:36:19.924   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 06:36:22.947   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 06:36:26.192   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:27.193   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:28.195   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:29.196   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:29.201  5693  5739 I jxcore-log: 2016-09-30 10:36:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 06:36:29.201  5693  5739 I jxcore-log: 
,09-30 06:36:29.203  5693  5739 I jxcore-log: 2016-09-30 10:36:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 06:36:29.203  5693  5739 I jxcore-log: 
,09-30 06:36:29.208  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:36:29.208  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:29.208  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:29.208  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:29.208  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:36:29.208  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:29.208  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:29.208  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:36:29.209  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:36:29.210  5693  5739 I jxcore-log: 2016-09-30 10:36:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 06:36:29.210  5693  5739 I jxcore-log: 
09-30 06:36:29.212  5693  5739 I jxcore-log: 2016-09-30 10:36:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 06:36:29.212  5693  5739 I jxcore-log: 
,09-30 06:36:29.459  5693  5739 I jxcore-log: 2016-09-30 10:36:29 - DEBUG UnitTest_app: 'Running unit tests'
09-30 06:36:29.459  5693  5739 I jxcore-log: 
,09-30 06:36:29.459  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:36:29.459  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2092781 added. We now have 2 listener(s)
09-30 06:36:29.460  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:36:29.460  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:36:29.460  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 06:36:29.460  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:36:29.460  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b55026 added. We now have 2 listener(s)
09-30 06:36:29.460  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:36:29.461  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 06:36:29.463  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:36:29.466  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:36:29.466  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:29.466  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:29.466  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:29.466  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:36:29.466  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:29.466  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:29.466  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:36:29.467  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:29.467  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:36:29.467  5693  5739 D executeNativeTests: Running unit tests
,09-30 06:36:29.475  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:29.481  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:29.506  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 06:36:29.506  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 added. We now have 3 listener(s)
,09-30 06:36:29.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:36:29.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 06:36:29.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 06:36:29.506  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:36:29.506  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d added. We now have 3 listener(s)
,09-30 06:36:29.506  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:36:29.507  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 06:36:29.508  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:36:29.511  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:36:29.511  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:29.511  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:29.511  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:29.511  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:36:29.511  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:29.511  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:29.511  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:29.511  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:29.511  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 06:36:29.513  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 06:36:29.513  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 06:36:29.513  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 06:36:29.513  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 06:36:29.514  5693  5739 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-30 06:36:29.514  5693  5739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 06:36:29.514  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-30 06:36:29.514  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 06:36:29.514  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 06:36:29.514  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 06:36:29.514  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:29.514  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:29.514  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:29.514  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:29.514  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:29.514  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:36:29.515  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:29.515  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:36:29.515  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 removed from the list
09-30 06:36:29.515  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:29.515  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d removed from the list
09-30 06:36:29.517  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:36:29.526  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:36:29.526  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:29.526  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:29.527  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:29.527  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:29.527  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:29.527  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:29.527  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:29.527  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:29.528  5693  5739 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-30 06:36:29.529  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:29.529  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 06:36:29.529  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:29.529  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:29.529  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:29.529  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:29.529  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 06:36:29.529  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:29.529  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:29.529  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:29.529  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:29.529  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:29.529  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:29.529  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:29.529  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:29.530  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:29.530  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 06:36:29.530  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:29.530  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 06:36:29.532  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 06:36:29.533  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:29.533  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:29.533  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:29.533  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 06:36:29.533  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:29.533  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:29.533  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:29.533  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
,09-30 06:36:29.533  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:29.533  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:29.533  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:29.533  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:29.533  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:29.533  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:29.534  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:29.534  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:29.534  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:29.534  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-30 06:36:29.534  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:29.534  5693  5739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 06:36:29.535  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:36:29.537  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:36:29.537  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:29.537  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:29.537  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:29.537  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:36:29.537  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:29.537  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:29.537  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:29.538  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:29.538  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:36:29.538  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:36:29.539  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 06:36:29.539  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 06:36:29.539  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:36:29.539  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 06:36:29.540  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:36:29.542  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 06:36:29.542  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 06:36:29.543  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:36:29.544  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 06:36:29.546  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 06:36:29.546  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 06:36:29.547  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-30 06:36:29.548  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-30 06:36:29.548  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 06:36:29.548  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 06:36:29.548  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 06:36:29.549  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetoot,h.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 06:36:29.549  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 06:36:29.549  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:36:29.551  4684  4697 D BtGatt.GattService: registerClient() - UUID=b3c57d8f-a7c4-482b-9f05-b86a9d54b4a7
09-30 06:36:29.552  4684  4780 D BtGatt.GattService: onClientRegistered() - UUID=b3c57d8f-a7c4-482b-9f05-b86a9d54b4a7, clientIf=5
09-30 06:36:29.553  5693  5703 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 06:36:29.554  4684  4895 D BtGatt.GattService: start scan with filters
09-30 06:36:29.558  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 06:36:29.558  4684  4790 D BtGatt.ScanManager: handling starting scan
09-30 06:36:29.559  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 06:36:29.559  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:36:29.559  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 06:36:29.559  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 06:36:29.559  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 06:36:29.559  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 06:36:29.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 06:36:29.560  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 06:36:29.561  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 06:36:29.561  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 06:36:29.562  4684  4790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:36:29.562  5693  5739 I io.jxcore.node.ConnectionHelper: start: OK
09-30 06:36:29.570  4684  4780 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 06:36:29.570  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:29.570  4684  4790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 06:36:29.577  4684  4780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 06:36:29.577  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:29.578  4684  4790 D BtGatt.ScanManager: Starting BLE batch scan
09-30 06:36:29.578  4684  4790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 06:36:29.588  4684  4780 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 06:36:29.588  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:36:29.595  4684  4780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 06:36:29.595  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:36:30.063  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 06:36:30.063  5693  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:36:30.063  5693  5693 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 06:36:30.198   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:31.198   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 06:36:34.566  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 06:36:34.566  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:34.567  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 06:36:34.567  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:34.567  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 06:36:34.567  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 06:36:34.567  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 06:36:34.567  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 06:36:34.567  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 06:36:34.567  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 06:36:34.568  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 06:36:34.568  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 06:36:34.569  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:36:34.570  4684  4697 D BtGatt.GattService: stopScan() - queue size =1
09-30 06:36:34.571  4684  4895 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 06:36:34.571  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 06:36:34.571  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 06:36:34.571  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 06:36:34.572  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:36:34.572  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 06:36:34.572  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 06:36:34.572  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 06:36:34.572  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 06:36:34.573  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:36:34.573  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-30 06:36:34.574  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 06:36:34.574  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 06:36:34.574  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 06:36:34.575  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 06:36:34.577  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:34.577  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:34.577  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:36:34.577  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:34.577  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:34.577  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:34.577  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:34.577  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:36:34.577  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:34.577  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:34.577  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:36:34.578  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:36:34.579  4684  4684 D BtGatt.ScanManager: awakened up at time 237793
,09-30 06:36:34.586  4684  4780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 06:36:34.586  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:36:34.587  4684  4790 D BtGatt.ScanManager: stopping BLe Batch
,09-30 06:36:34.596  4684  4780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 06:36:34.597  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:34.597  4684  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 06:36:34.626  4684  4780 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-30 06:36:34.627  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:36:34.627  4684  4780 D BtGatt.GattService: current time is 237842175465
,09-30 06:36:34.628  4684  4780 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -71, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -77, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -77, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -73, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -76, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 06:36:34.630  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 06:36:34.631  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-30 06:36:34.631  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 06:36:34.632  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-30 06:36:34.633  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 06:36:34.633  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-30 06:36:35.079  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 06:36:36.199   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:37.201   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:38.202   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:39.204   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:39.580  5693  5739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 06:36:39.586  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:36:39.597  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:36:39.597  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:39.597  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:39.597  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:39.597  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:36:39.597  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:39.597  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:39.597  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:36:39.602  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:36:39.602  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:36:39.602  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:36:39.602  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 06:36:39.602  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 06:36:39.602  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:36:39.603  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 06:36:39.607  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:39.609  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 06:36:39.609  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 06:36:39.611  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:39.614  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 06:36:39.616  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-30 06:36:39.616  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 06:36:39.620  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 06:36:39.620  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 06:36:39.620  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 06:36:39.621  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 06:36:39.621  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 06:36:39.621  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:36:39.624  4684  4697 D BtGatt.GattService: registerClient() - UUID=ba1c48f4-63d7-468a-81d7-ec183abae68e
09-30 06:36:39.624  4684  4780 D BtGatt.GattService: onClientRegistered() - UUID=ba1c48f4-63d7-468a-81d7-ec183abae68e, clientIf=5
09-30 06:36:39.625  5693  5704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 06:36:39.625  4684  4895 D BtGatt.GattService: start scan with filters
09-30 06:36:39.629  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 06:36:39.629  4684  4790 D BtGatt.ScanManager: handling starting scan
,09-30 06:36:39.629  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 06:36:39.629  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:36:39.629  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 06:36:39.629  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 06:36:39.629  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 06:36:39.629  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 06:36:39.632  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 06:36:39.632  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 06:36:39.632  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 06:36:39.634  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 06:36:39.635  3544  3544 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:36:39.636  4684  4780 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 06:36:39.636  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:39.636  4684  4790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 06:36:39.637  5693  5739 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 06:36:39.640  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:39.640  5693  5739 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 06:36:39.640  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:39.641  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 06:36:39.641  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:39.641  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 06:36:39.641  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:39.641  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 06:36:39.641  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 06:36:39.641  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 06:36:39.641  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 06:36:39.641  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 06:36:39.641  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 06:36:39.642  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:36:39.643  4684  4780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 06:36:39.643  4684  4697 D BtGatt.GattService: stopScan() - queue size =1
,09-30 06:36:39.643  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:39.643  4684  4790 D BtGatt.ScanManager: Starting BLE batch scan
09-30 06:36:39.643  4684  4790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 06:36:39.644  4684  4895 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 06:36:39.644  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 06:36:39.644  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 06:36:39.644  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 06:36:39.644  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:36:39.644  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 06:36:39.644  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 06:36:39.644  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 06:36:39.644  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 06:36:39.646  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 06:36:39.646  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 06:36:39.646  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 06:36:39.646  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 06:36:39.646  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 06:36:39.647  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 06:36:39.654  4684  4780 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 06:36:39.655  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:39.655  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:39.655  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:39.655  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:36:39.655  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:39.655  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:36:39.655  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:39.655  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:36:39.655  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:39.655  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:36:39.655  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:39.655  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 06:36:39.655  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:39.656  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:39.656  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:39.657  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 06:36:39.657  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 06:36:39.657  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:39.657  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:39.658  5693  5739 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 06:36:39.660  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:36:39.661  4684  4780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 06:36:39.661  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:39.666  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:36:39.666  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:39.666  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:39.666  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:39.666  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:36:39.666  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:39.666  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:39.666  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:36:39.668  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:36:39.668  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:36:39.668  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:36:39.668  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 06:36:39.668  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 06:36:39.668  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:36:39.668  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 06:36:39.669  4684  4780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 06:36:39.669  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:39.669  4684  4790 D BtGatt.ScanManager: stopping BLe Batch
,09-30 06:36:39.671  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 06:36:39.671  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 06:36:39.672  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:39.674  4684  4780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 06:36:39.674  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:39.674  4684  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 06:36:39.675  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:39.675  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 06:36:39.676  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 06:36:39.676  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 06:36:39.679  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 06:36:39.679  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 06:36:39.679  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 06:36:39.679  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 06:36:39.679  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 06:36:39.679  4684  4780 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 06:36:39.679  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:39.679  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:36:39.681  4684  4702 D BtGatt.GattService: registerClient() - UUID=c6cd4e44-407e-4de8-9c29-a7eed97a7816
09-30 06:36:39.681  4684  4780 D BtGatt.GattService: onClientRegistered() - UUID=c6cd4e44-407e-4de8-9c29-a7eed97a7816, clientIf=5
,09-30 06:36:39.682  5693  5703 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 06:36:39.682  4684  4895 D BtGatt.GattService: start scan with filters
,09-30 06:36:39.684  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 06:36:39.684  4684  4790 D BtGatt.ScanManager: handling starting scan
,09-30 06:36:39.684  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 06:36:39.684  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:36:39.684  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 06:36:39.684  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 06:36:39.684  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 06:36:39.684  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 06:36:39.687  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 06:36:39.687  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 06:36:39.688  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 06:36:39.689  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 06:36:39.691  4684  4780 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 06:36:39.691  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:39.691  4684  4790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 06:36:39.691  5693  5739 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 06:36:39.695  4684  4780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 06:36:39.695  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:36:39.696  4684  4790 D BtGatt.ScanManager: Starting BLE batch scan
09-30 06:36:39.696  4684  4790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 06:36:39.703  4684  4780 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 06:36:39.704  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:36:39.708  4684  4780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 06:36:39.708  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:36:40.188  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 06:36:40.189  5693  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:36:40.189  5693  5693 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 06:36:40.205   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:41.205   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 06:36:44.692  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 06:36:44.692  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 06:36:44.692  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 06:36:44.692  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:44.692  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 06:36:44.693  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:44.693  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-30 06:36:44.693  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 06:36:44.693  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 06:36:44.693  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 06:36:44.693  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 06:36:44.694  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 06:36:44.696  5693  5739 D BluetoothAdapter: STATE_ON
,09-30 06:36:44.698  4684  4697 D BtGatt.GattService: stopScan() - queue size =1
,09-30 06:36:44.702  4684  4928 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 06:36:44.702  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 06:36:44.703  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 06:36:44.703  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-30 06:36:44.703  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 06:36:44.703  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 06:36:44.703  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 06:36:44.703  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 06:36:44.703  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 06:36:44.706  4684  4684 D BtGatt.ScanManager: awakened up at time 247921
,09-30 06:36:44.707  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:36:44.707  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 06:36:44.707  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 06:36:44.707  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 06:36:44.707  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 06:36:44.710  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 06:36:44.713  4684  4780 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 06:36:44.713  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:44.713  4684  4790 D BtGatt.ScanManager: stopping BLe Batch
09-30 06:36:44.714  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:36:44.714  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 06:36:44.714  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 06:36:44.719  4684  4780 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 06:36:44.720  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:44.720  4684  4790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 06:36:44.737  4684  4780 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-30 06:36:44.737  4684  4780 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:36:44.737  4684  4780 D BtGatt.GattService: current time is 247952588474
09-30 06:36:44.738  4684  4780 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -72, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -74, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -78, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 06:36:44.739  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 06:36:44.739  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 06:36:44.739  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 06:36:44.739  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 06:36:44.739  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-30 06:36:44.740  4684  4780 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-30 06:36:45.215  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 06:36:45.216  5693  5693 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 06:36:45.216  5693  5693 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 06:36:49.715  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 06:36:49.716  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:49.716  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:49.716  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.716  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.717  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 06:36:49.717  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.717  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.717  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.717  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.717  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 06:36:49.717  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.720  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.720  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:49.725  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.725  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:49.725  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.725  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:49.726  5693  5739 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-30 06:36:49.728  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.728  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:49.729  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 06:36:49.729  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.729  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.729  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.729  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.729  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.730  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:49.730  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.730  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:49.730  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.730  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.730  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:49.730  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.733  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.733  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:49.733  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.733  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:49.735  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 06:36:49.736  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.736  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:49.736  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:49.736  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.736  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:49.736  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.736  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.737  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.737  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.737  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.737  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 06:36:49.737  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.737  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.737  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.737  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:49.740  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.740  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 06:36:49.740  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.740  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.742  5693  5739 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-30 06:36:49.742  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.742  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:49.742  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:49.742  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 06:36:49.743  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.743  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.743  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.743  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.743  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.743  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.743  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 06:36:49.743  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.743  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.744  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.744  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.747  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.747  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:49.747  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.747  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:49.749  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-30 06:36:49.749  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.749  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 06:36:49.749  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 06:36:49.750  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.750  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.750  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.750  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.750  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.750  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.750  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:49.751  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:49.751  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.751  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.751  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.751  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.753  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.753  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:49.753  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:49.754  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.755  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 06:36:49.755  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 06:36:49.755  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 06:36:49.755  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 06:36:49.755  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 06:36:49.756  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-30 06:36:49.756  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 06:36:49.756  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 06:36:49.756  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 06:36:49.756  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.756  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:49.756  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:49.756  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.757  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:49.757  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.757  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.757  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.757  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.757  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.757  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:49.757  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.757  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:49.757  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.759  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:49.761  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.761  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:49.761  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:49.761  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.762  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 06:36:49.763  5693  5739 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 06:36:49.763  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 06:36:49.768  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 06:36:49.769  5693  5739 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-30 06:36:49.769  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 06:36:49.769  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 06:36:49.769  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 06:36:49.769  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 06:36:49.769  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 06:36:49.769  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 06:36:49.769  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 06:36:49.770  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 06:36:49.771  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 06:36:49.772  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-30 06:36:49.772  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 06:36:49.772  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 06:36:49.772  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-30 06:36:49.772  5693  5739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 06:36:49.773  5693  5739 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-30 06:36:49.773  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 06:36:49.773  5693  5739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 06:36:49.773  5693  5739 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-30 06:36:49.773  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 06:36:49.773  5693  5739 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 06:36:49.773  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-30 06:36:49.778  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-30 06:36:49.779  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-30 06:36:49.779  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-30 06:36:49.780  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-30 06:36:49.780  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-30 06:36:49.780  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-30 06:36:49.780  5693  5739 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 06:36:49.780  5693  5739 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-30 06:36:49.780  5693  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-30 06:36:49.780  5693  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-30 06:36:49.781  5693  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-30 06:36:49.781  5693  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,09-30 06:36:49.781  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.782  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:49.782  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:49.782  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.782  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.782  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.782  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.782  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-30 06:36:49.783  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.783  5693  5740 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-30 06:36:49.783  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.783  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.783  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 06:36:49.783  5693  5740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 06:36:49.783  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.783  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.783  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.784  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.784  5693  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-30 06:36:49.784  5693  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-30 06:36:49.785  5693  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-30 06:36:49.785  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.785  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:49.785  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.785  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:49.786  5693  5739 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-30 06:36:49.787  5693  5740 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
09-30 06:36:49.787  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.787  5693  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-30 06:36:49.787  5693  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-30 06:36:49.787  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:49.787  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:49.787  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.787  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.788  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.788  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.782  4702  4702 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[34851]" dev="sockfs" ino=34851 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 06:36:49.788  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
,09-30 06:36:49.788  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.788  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.788  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:49.788  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.788  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.788  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.788  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.782  4702  4702 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34851]" dev="sockfs" ino=34851 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 06:36:49.792  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.792  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:49.792  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.792  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.793  5693  5739 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-30 06:36:49.793  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.793  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 06:36:49.793  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:49.793  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.793  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.793  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.794  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.794  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.794  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.794  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.794  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:49.794  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.794  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.794  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.794  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.796  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.796  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:49.796  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.796  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.797  5693  5739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-30 06:36:49.797  5693  5739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-30 06:36:49.797  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 06:36:49.797  5693  5739 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-30 06:36:49.797  5693  5739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 06:36:49.797  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-30 06:36:49.798  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 06:36:49.798  5693  5739 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-30 06:36:49.798  5693  5739 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 06:36:49.798  5693  5739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 06:36:49.798  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 06:36:49.798  5693  5739 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-30 06:36:49.798  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:49.798  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:49.798  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 06:36:49.799  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.799  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.799  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.799  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.800  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.800  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.800  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.800  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:49.800  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.800  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.800  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.800  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.802  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:49.802  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 06:36:49.802  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.802  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.803  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:49.803  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.803  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:49.803  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:49.803  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:49.803  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:49.803  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:49.803  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:49.803  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:49.803  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:51.206   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:52.207   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:53.208   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:54.209   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:54.804  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:54.804  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:54.804  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:54.805  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.805  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.805  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:54.805  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:54.805  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:54.806  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 06:36:54.806  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:54.806  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:54.806  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.806  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.807  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:54.807  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:54.807  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:54.807  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.807  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:54.807  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.807  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.808  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.808  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:54.811  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:54.811  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 06:36:54.811  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:54.812  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.816  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-30 06:36:54.816  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:36:54.819  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-30 06:36:54.821  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-30 06:36:54.821  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-30 06:36:54.821  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-30 06:36:54.822  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-30 06:36:54.822  5693  5693 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-30 06:36:54.822  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-30 06:36:54.822  5693  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-30 06:36:54.823  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:54.823  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-30 06:36:54.824  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-30 06:36:54.824  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-30 06:36:54.824  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.824  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 06:36:54.824  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-30 06:36:54.824  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:54.825  5693  5693 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-30 06:36:54.825  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:54.825  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 06:36:54.825  5693  5742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 06:36:54.825  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 06:36:54.825  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 06:36:54.826  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.826  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.828  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:36:54.828  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.828  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:36:54.828  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:54.828  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 06:36:54.828  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:36:54.828  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:54.829  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:36:54.829  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:54.829  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.829  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.829  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 06:36:54.829  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:54.829  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:54.829  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:54.830  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:54.830  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.830  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.829  4697  4697 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31620]" dev="sockfs" ino=31620 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-30 06:36:54.829  4697  4697 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31620]" dev="sockfs" ino=31620 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 06:36:54.830  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.830  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.833  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 06:36:54.833  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:54.833  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:54.833  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
,09-30 06:36:54.836  5693  5739 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-30 06:36:54.836  5693  5742 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-30 06:36:54.836  5693  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-30 06:36:54.836  5693  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-30 06:36:54.836  5693  5739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 06:36:54.836  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 06:36:54.836  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 06:36:54.837  5693  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-30 06:36:54.837  5693  5739 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-30 06:36:54.837  5693  5693 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:54.837  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:54.837  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:54.837  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:54.837  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:54.837  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:54.838  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.838  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:54.838  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:54.838  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:54.838  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.838  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:54.838  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:54.839  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.839  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.839  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.841  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:54.841  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:36:54.841  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:54.841  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.851  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 06:36:54.851  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:54.851  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:54.851  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:54.851  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.851  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.851  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:54.851  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:54.851  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:54.851  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.851  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:54.852  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.852  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.852  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.852  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.853  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:36:54.853  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 06:36:54.853  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:54.853  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.855  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:36:54.855  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:36:54.855  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:36:54.855  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:36:54.855  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.855  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:54.855  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:36:54.856  5693  5739 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e82e844 not in the list
09-30 06:36:54.856  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:54.856  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.856  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:54.856  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:54.856  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.856  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:54.856  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:54.858  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 06:36:54.858  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 06:36:54.858  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:54.858  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919cd2d not in the list
09-30 06:36:54.860  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-30 06:36:54.860  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 06:36:54.860  5693  5739 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-30 06:36:54.860  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 06:36:54.860  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-30 06:36:54.860  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 06:36:54.863  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 06:36:54.863  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-30 06:36:54.864  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-30 06:36:54.864  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 06:36:54.864  5693  5739 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-30 06:36:54.864  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 06:36:54.864  5693  5739 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-30 06:36:54.865  5693  5739 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-30 06:36:54.865  5693  5739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-30 06:36:54.865  5693  5739 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-30 06:36:54.866  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-30 06:36:54.866  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-30 06:36:54.866  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-30 06:36:54.866  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-30 06:36:54.867  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:36:54.867  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3faa247 added. We now have 3 listener(s)
09-30 06:36:54.868  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:36:54.870  5693  5739 D BluetoothAdapter: enable(): BT is already enabled..!
,09-30 06:36:54.870   927   937 D WifiService: setWifiEnabled: true pid=5693, uid=10077
09-30 06:36:54.870   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 06:36:54.913  4684  4888 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-30 06:36:54.914  4684  4893 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-30 06:36:55.210   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:36:55.330  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 06:36:56.211   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 06:36:56.224   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 06:36:58.229   927  3066 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 06:36:59.250   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 06:36:59.876  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 06:36:59.876  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@912ea74 added. We now have 4 listener(s)
09-30 06:36:59.876  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:36:59.889  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:36:59.889  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@912ea74 removed from the list
09-30 06:36:59.890  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:36:59.890  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:36:59.890  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:36:59.893  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:36:59.893  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a355b9d added. We now have 4 listener(s)
09-30 06:36:59.893  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:36:59.897  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:36:59.897  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a355b9d removed from the list
,09-30 06:36:59.897  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 06:36:59.897  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:36:59.898  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:36:59.900  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:36:59.900  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3100812 added. We now have 4 listener(s)
09-30 06:36:59.901  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:36:59.907   927  3244 D WifiService: setWifiEnabled: false pid=5693, uid=10077
,09-30 06:36:59.907   927  3244 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 06:36:59.916   927  3066 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-30 06:36:59.916   927  3066 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-30 06:36:59.916   927  3066 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 06:36:59.916   927  3066 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 06:36:59.921  4684  4773 D BluetoothAdapterState: Current state: ON, message: 23
09-30 06:36:59.921  4684  4773 D BluetoothAdapterProperties: Setting state to 13
09-30 06:36:59.921  4684  4773 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 06:36:59.923  4684  4773 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 06:36:59.924  4684  4773 I BluetoothAdapterState: Entering PendingCommandState
09-30 06:36:59.925  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:36:59.928  4684  4780 D BluetoothAdapterProperties: Scan Mode:20
09-30 06:36:59.929  4684  4773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-30 06:36:59.935  4684  4684 D HeadsetService: Received stop request...Stopping profile...
09-30 06:36:59.936  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.936  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:36:59.936  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:59.936  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:59.936  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:59.936  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:36:59.936  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:59.936  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:59.936  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:59.936  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 06:36:59.936  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:36:59.936   506   925 D CommandListener: Clearing all IP addresses on wlan0
09-30 06:36:59.937  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:36:59.938   927  5444 D DhcpClient: Clearing IP address
,09-30 06:36:59.940   506   925 D CommandListener: Setting iface cfg
,09-30 06:36:59.941  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:36:59.944  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:36:59.948  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.948  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:36:59.948  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:59.948  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:59.948  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:59.948  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:36:59.948  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:59.948  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:59.948  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:59.948  3672  5498 V NativeCrypto: Read error: ssl=0x7f61bb4700: I/O error during system call, Connection timed out
09-30 06:36:59.949  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.949  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:59.950  3672  5498 V NativeCrypto: SSL shutdown failed: ssl=0x7f61bb4700: I/O error during system call, Broken pipe
09-30 06:36:59.954  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.954  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:36:59.954  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:59.954  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:59.954  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:59.954  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:36:59.954  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:59.954  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:59.954  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:59.955  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 06:36:59.955  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:36:59.959  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.959  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:36:59.959  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:59.959  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:59.959  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:59.959  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:36:59.959  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:36:59.959  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:59.959  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:59.960  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.961  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:36:59.962   927   940 I ActivityManager: Start proc 5746:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-30 06:36:59.964  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.964  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:36:59.964  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:59.964  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:59.964  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:59.964  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:36:59.964  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:36:59.964  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:36:59.964  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:59.964   927   937 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-30 06:36:59.965   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 06:36:59.965   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 06:36:59.965   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 06:36:59.965  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.965   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 06:36:59.965  3233  3245 D BluetoothHeadset: Proxy object disconnected
,09-30 06:36:59.965  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:36:59.965   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-30 06:36:59.965  4684  4684 D BluetoothMapService: onReceive
09-30 06:36:59.965  4684  4684 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 06:36:59.965  4684  4684 D BluetoothMapService: STATE_TURNING_OFF
09-30 06:36:59.965   927  5442 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-30 06:36:59.966  3866  4095 D BluetoothHeadset: Proxy object disconnected
09-30 06:36:59.967  3233  3233 D HeadsetProfile: Bluetooth service disconnected
09-30 06:36:59.969   535   535 E Parcel  : Reading a NULL string not supported here.
09-30 06:36:59.970  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.970  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:36:59.970  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:59.970  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:59.970  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:59.970  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:36:59.970  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:36:59.970  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:36:59.970  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:36:59.970   927   927 D RttService: SCAN_AVAILABLE : 1
09-30 06:36:59.970   927  3183 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 06:36:59.971  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.971  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:36:59.972   927  5442 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-30 06:36:59.972  4684  4684 D A2dpService: Received stop request...Stopping profile...
,09-30 06:36:59.972  4684  4901 D A2dpStateMachine: Exit Disconnected: -1
09-30 06:36:59.974  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:36:59.974  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:36:59.974  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:36:59.974  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:36:59.974  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:36:59.974  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:36:59.974  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:36:59.974  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:36:59.974  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:36:59.975   927   927 D BluetoothA2dp: Proxy object disconnected
,09-30 06:36:59.976  4684  4684 V BluetoothAdapterState: isTurningOff()=true
,09-30 06:36:59.977   927  3066 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-30 06:36:59.977  4684  4684 V BluetoothAdapterState: isTurningOn()=false
09-30 06:36:59.977   927  3079 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-30 06:36:59.977  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 06:36:59.977  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:36:59.978   927  5445 D DhcpClient: Receive thread stopped
09-30 06:36:59.978  3819  4008 W QCNEJ   : |CORE| network lost: 100
,09-30 06:36:59.978  3819  4008 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 06:36:59.979  4684  4684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 06:36:59.979  4684  4684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 06:36:59.979  4684  4780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 06:36:59.979  4684  4684 D BluetoothMapService: MAP Service closeService in
09-30 06:36:59.979  4684  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:36:59.980  3233  3233 D BluetoothA2dp: Proxy object disconnected
09-30 06:36:59.980  4684  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:36:59.980  4684  4684 D BluetoothMapMasInstance0: MAP Service shutdown
,09-30 06:36:59.980  4684  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:36:59.980  4684  4684 D ObexServerSockets0: shutdown(block = true)
09-30 06:36:59.980  4684  4780 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 06:36:59.981   927  3066 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 06:36:59.981  4684  4684 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 06:36:59.981  4684  4931 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,09-30 06:36:59.981  4684  4684 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-30 06:36:59.981  4684  4893 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 06:36:59.982  4684  4932 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 06:36:59.982  4684  4684 I BtOppRfcommListener: stopping Accept Thread
09-30 06:36:59.982  4684  5381 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 06:36:59.983  4684  5381 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-30 06:36:59.984  4684  4684 D HidService: Received stop request...Stopping profile...
09-30 06:36:59.984  4684  4684 D HidService: Stopping Bluetooth HidService
09-30 06:36:59.985  4684  4684 D HealthService: Received stop request...Stopping profile...
09-30 06:36:59.986  4684  4684 D PanService: Received stop request...Stopping profile...
,09-30 06:36:59.988  4684  4684 D BluetoothMapService: Received stop request...Stopping profile...
,09-30 06:36:59.988  4684  4684 D BluetoothMapService: stop()
,09-30 06:36:59.989  4684  4684 D BluetoothMapAppObserver: deinitObservers()
,09-30 06:36:59.989  4684  4684 D BluetoothMapAppObserver: removeReceiver()
09-30 06:36:59.990  4684  4684 D SapService: Received stop request...Stopping profile...
,09-30 06:36:59.990  4684  4684 V SapService: stop()
,09-30 06:36:59.993  4684  4684 V BluetoothAdapterState: isTurningOff()=true
,09-30 06:36:59.993  4684  4684 V BluetoothAdapterState: isTurningOn()=false
09-30 06:36:59.993  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:36:59.993  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:36:59.995  4684  4780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 06:36:59.995  4684  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:36:59.995  4684  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:36:59.995  4684  4888 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 06:36:59.995  4684  4888 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-30 06:36:59.995  4684  4888 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 06:36:59.995  4684  4888 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 06:36:59.996  3233  3233 D BluetoothInputDevice: Proxy object disconnected
09-30 06:36:59.996  3233  3233 D HidProfile: Bluetooth service disconnected
,09-30 06:36:59.997  3233  3233 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-30 06:36:59.997  3233  3233 D PanProfile: Bluetooth service disconnected
09-30 06:36:59.997  3233  3233 D BluetoothMap: Proxy object disconnected
09-30 06:36:59.997  3233  3233 D MapProfile: Bluetooth service disconnected
09-30 06:36:59.999  4684  4684 V BluetoothAdapterState: isTurningOff()=true
09-30 06:36:59.999  4684  4684 V BluetoothAdapterState: isTurningOn()=false
,09-30 06:36:59.999  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:36:59.999  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:36:59.999  4684  4684 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 06:37:00.000  4684  4684 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 06:37:00.000  4684  4780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 06:37:00.000  4684  4684 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:00.000  4684  4684 V BluetoothAdapterState: isTurningOn()=false
,09-30 06:37:00.000  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:00.000  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:00.000  4684  4684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 06:37:00.000  4684  4684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 06:37:00.001  4684  4684 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:00.001  4684  4684 V BluetoothAdapterState: isTurningOn()=false
,09-30 06:37:00.001  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:00.001  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:00.001  4684  4684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 06:37:00.001  4684  4684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 06:37:00.002  4684  4684 D BluetoothMapService: MAP Service closeService in
09-30 06:37:00.002  4684  4684 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:00.002  4684  4684 V BluetoothAdapterState: isTurningOn()=false
,09-30 06:37:00.002  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 06:37:00.002  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 06:37:00.002  4684  4780 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-30 06:37:00.002  4684  4684 D BluetoothMapService: cleanup()
09-30 06:37:00.002  4684  4684 D BluetoothMapService: MAP Service closeService in
09-30 06:37:00.002  4684  4684 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:00.002  4684  4684 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:00.002  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:00.002  4684  4684 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 06:37:00.002  4684  4773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-30 06:37:00.002  4684  4773 D BluetoothAdapterProperties: Setting state to 15
,09-30 06:37:00.003  4684  4773 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-30 06:37:00.003  4684  4773 I BluetoothAdapterState: Entering BleOnState
,09-30 06:37:00.003  3233  3247 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 06:37:00.004   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:00.004   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:00.004   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:00.005  3233  3245 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 06:37:00.005  3233  4076 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-30 06:37:00.006   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-30 06:37:00.006  3233  3247 D BluetoothPan: onBluetoothStateChange on: false
09-30 06:37:00.006   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 06:37:00.007  3866  3884 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:00.007  3233  3245 D BluetoothMap: onBluetoothStateChange: up=false
09-30 06:37:00.007  3233  4076 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:00.011  4684  4773 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 06:37:00.011  4684  4773 D BluetoothAdapterProperties: Setting state to 16
,09-30 06:37:00.011  4684  4773 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 06:37:00.012  4684  4773 D BluetoothAdapterProperties: onBleDisable
09-30 06:37:00.012  4684  4775 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 06:37:00.013  4684  4780 D BluetoothAdapterProperties: Scan Mode:20
09-30 06:37:00.013  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.013  4684  4888 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 06:37:00.013  4684  4888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:37:00.013  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:00.013  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:00.013  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:00.013  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:00.013  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:00.013  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:00.013  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:00.013  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:00.013  4684  4773 I BluetoothAdapterState: Entering PendingCommandState
,09-30 06:37:00.015  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.015  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:00.015  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:00.015  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:00.015  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:00.015  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:00.015  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:00.015  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:00.015  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:00.017  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.017  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:00.017  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:00.017  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:00.017  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:00.017  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:00.017  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:00.017  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:00.017  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:00.018  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:00.019  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:00.019  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:00.015  5746  5746 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-30 06:37:00.029   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 06:37:00.029   506   925 D CommandListener: Clearing all IP addresses on wlan0
09-30 06:37:00.029   506   925 D TetherController: Setting IP forward enable = 0
,09-30 06:37:00.031   927  3079 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-30 06:37:00.031   927  3079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 06:37:00.032   927  3066 D DhcpClient: doQuit
09-30 06:37:00.032   927  3066 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 06:37:00.032   927   944 D Tethering: MasterInitialState.processMessage what=3
09-30 06:37:00.032   927  5444 D DhcpClient: onQuitting
09-30 06:37:00.033  3544  3544 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 06:37:00.035  5351  5351 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@53f1ffa and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-30 06:37:00.036  4019  4019 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-30 06:37:00.038  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.038  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:00.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:00.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:00.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:00.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:00.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:00.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:00.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:00.039  5101  5124 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 06:37:00.039  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.039  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:00.039  5101  5124 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 06:37:00.039  5101  5124 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 06:37:00.039  5101  5124 E SarControlService: no key has been found,reset the power
09-30 06:37:00.039  5101  5138 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-30 06:37:00.040  5101  5138 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 06:37:00.040  5101  5138 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 06:37:00.040  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 06:37:00.041  5126  5126 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 06:37:00.042  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.042  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:00.042  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:00.042  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:00.042  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:00.042  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:00.042  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:00.042  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:00.042  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:00.044  5101  5138 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 06:37:00.044  5101  5138 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 06:37:00.044  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.044  5101  5138 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 06:37:00.044  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:00.045  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 06:37:00.045  5126  5126 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 06:37:00.047  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.047  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:00.047  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:00.047  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:00.047  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:00.047  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:00.047  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:00.047  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:00.047  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:00.047  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:00.047  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:00.048  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@928fe30 He,xData = [00000000ea03000000000000ffffffff]
09-30 06:37:00.048  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 06:37:00.048  5126  5140 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-30 06:37:00.049  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 06:37:00.049  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:00.049  5101  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 06:37:00.050  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:00.052  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:00.057  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@928fe30 HexData = [00000000eb03000000000000ffffffff]
09-30 06:37:00.057  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 06:37:00.057  5126  5140 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-30 06:37:00.058  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 06:37:00.058  5101  5112 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 06:37:00.059  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 06:37:00.067   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5248e5d:true
09-30 06:37:00.067  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 06:37:00.071  3544  3544 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 06:37:00.075  3544  3544 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-30 06:37:00.083   927  3811 I ActivityManager: Start proc 5776:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-30 06:37:00.096   506   925 E Netd    : netlink response contains error (No such file or directory)
09-30 06:37:00.098   927  3079 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-30 06:37:00.099   506   925 D TetherController: Setting IP forward enable = 0
09-30 06:37:00.106  5746  5746 D LocalBluetoothProfileManager: Adding local MAP profile
,09-30 06:37:00.109  5746  5746 D BluetoothMap: Create BluetoothMap proxy object
,09-30 06:37:00.123  3544  3544 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 06:37:00.125  5746  5746 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-30 06:37:00.136  5776  5776 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-30 06:37:00.139  5746  5746 D DockEventReceiver: finishStartingService: stopping service
,09-30 06:37:00.147   927  3885 I ActivityManager: Killing 5034:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-30 06:37:00.155  3544  3544 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 06:37:00.217  4684  4780 I bt_hci  : shut_down
,09-30 06:37:00.221  4684  4791 D bt_hwcfg: hw_epilog_process
,09-30 06:37:00.221  4684  4791 I bt_vendor: low_power_mode_cb
,09-30 06:37:00.224  4684  4791 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 06:37:00.224  4684  4791 I bt_vendor: epilog_cb
09-30 06:37:00.224  4684  4791 I bt_hci  : epilog_finished_callback
,09-30 06:37:00.226  4684  4780 I bt_hci_h4: hal_close
,09-30 06:37:00.227  4684  4780 I bt_userial_vendor: device fd = 54 close
,09-30 06:37:00.257   927  3066 D wifi    : In wifi stop Hal
,09-30 06:37:00.257   927  3066 D wifi    : halHandle = 0x7f602c9f80, mVM = 0x7f7c94d140, mCls = 0x100a02
09-30 06:37:00.258   927  3542 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 06:37:00.258   927  3542 D WifiHAL : Got a signal to exit!!!
09-30 06:37:00.258   927  3542 I WifiHAL : Exit wifi_event_loop
09-30 06:37:00.258  5075  5075 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 06:37:00.258   927  3066 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 06:37:00.259   927  3066 E WifiHAL : Event processing terminated
09-30 06:37:00.259   927  3066 D wifi    : In wifi cleaned up handler
09-30 06:37:00.259   927  3066 I WifiHAL : Internal cleanup completed
,09-30 06:37:00.261  4195  4336 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 06:37:00.262  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:00.263  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:00.265  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:00.278   927  3542 D wifi    : set interface wlan0 flags (DOWN)
,09-30 06:37:00.278   927  3066 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 06:37:00.327  5776  5776 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 06:37:00.327  5776  5776 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 06:37:00.327  5776  5776 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 06:37:00.327  5776  5776 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 06:37:00.327  5776  5776 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.k.d(PG:583)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 06:37:00.327  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 06:37:00.328  5776  5776 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 06:37:00.328  5776  5776 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 06:37:00.328  5776  5776 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 06:37:00.328  5776  5776 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 06:37:00.334  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 06:37:00.334  4684  4775 D bt_stack_manager: event_shut_down_stack finished.
09-30 06:37:00.334  4684  4773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-30 06:37:00.336  4684  4773 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 06:37:00.337  4684  4684 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 06:37:00.338  4684  4684 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 06:37:00.338  4684  4684 D BtGatt.GattService: stop()
09-30 06:37:00.338  4684  4684 D BtGatt.AdvertiseManager: advertise clients cleared
09-30 06:37:00.340  4684  4684 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:00.340  4684  4684 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:00.340  4684  4684 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:00.340  4684  4684 V BluetoothAdapterState: isBleTurningOff()=true
09-30 06:37:00.340  4684  4773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 06:37:00.341  4684  4773 D BluetoothAdapterProperties: Setting state to 10
09-30 06:37:00.341  4684  4773 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 06:37:00.341  4684  4773 I BluetoothAdapterState: Entering OffState
09-30 06:37:00.342  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 06:37:00.342   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-30 06:37:00.350  4684  4684 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-30 06:37:00.351  3952  3952 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 06:37:00.355  4684  4684 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 06:37:00.355  4684  4684 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 06:37:00.356  4684  4775 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-30 06:37:00.358  3952  3952 D SystemUpdateService: onCreate
09-30 06:37:00.365  3952  3952 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 06:37:00.366  4684  4775 D bt_stack_manager: event_clean_up_stack finished.
,09-30 06:37:00.367  5746  5746 D DockEventReceiver: finishStartingService: stopping service
09-30 06:37:00.375  3952  3952 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-30 06:37:00.380  4684  4684 I art     : System.exit called, status: 0
09-30 06:37:00.380  4684  4684 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-30 06:37:00.389  3952  5469 I iu.UploadsManager: num queued entries: 0
09-30 06:37:00.389  3952  5469 I iu.UploadsManager: num updated entries: 0
09-30 06:37:00.390  3952  5469 I iu.SyncManager: NEXT; no task
09-30 06:37:00.392  3952  5809 I SystemUpdateService: active receiver: enabled
09-30 06:37:00.393  3952  3952 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-30 06:37:00.395  3952  3952 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 06:37:00.397  5471  5471 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-30 06:37:00.401  5471  5471 D SprintDMHelper: simOperator: 
09-30 06:37:00.401  5471  5471 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 06:37:00.418  5075  5811 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 06:37:00.421  3952  5809 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 06:37:00.426   927  3261 I ActivityManager: Start proc 5812:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-30 06:37:00.429   927   938 I ActivityManager: Process com.android.bluetooth (pid 4684) has died
,09-30 06:37:00.462  5812  5812 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-30 06:37:00.462  3952  5809 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 06:37:00.462  3952  5809 I SystemUpdateService: now status is 0 (complete)
09-30 06:37:00.463  3952  5809 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 06:37:00.463  3952  5809 I SystemUpdateService: file has been verified
09-30 06:37:00.463  3952  5809 I SystemUpdateService: OTA package size = 21989297
,09-30 06:37:00.478   927  3261 I ActivityManager: Killing 5351:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-30 06:37:00.480   927   944 D Tethering: InitialState.processMessage what=4
,09-30 06:37:00.498  3952  5809 I SystemUpdateService: showing system update notification
,09-30 06:37:00.505   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 06:37:00.551  3952  3952 D SystemUpdateService: onDestroy
,09-30 06:37:00.552   927  3261 I ActivityManager: Killing 4795:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-30 06:37:00.701  5776  5800 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-30 06:37:00.709   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7652a6:true
,09-30 06:37:04.940   927  3244 D WifiService: setWifiEnabled: true pid=5693, uid=10077
,09-30 06:37:04.940   927  3244 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 06:37:04.947   506   925 D SoftapController: Softap fwReload - Ok
,09-30 06:37:04.953   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:04.953   506   925 D CommandListener: Trying to bring down wlan0
09-30 06:37:04.954   506   925 D CommandListener: Clearing all IP addresses on wlan0
,09-30 06:37:04.960   927  3066 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 06:37:05.529   927  3066 D wifi    : set interface wlan0 flags (UP)
,09-30 06:37:05.532   927  3066 I WifiHAL : Initializing wifi
,09-30 06:37:05.532   927  3066 I WifiHAL : Creating socket
09-30 06:37:05.532   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 06:37:05.536   927  3066 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-30 06:37:05.536   927  3066 D wifi    : Did set static halHandle = 0x7f602c9f80
,09-30 06:37:05.536   927  3066 D wifi    : halHandle = 0x7f602c9f80, mVM = 0x7f7c94d140, mCls = 0x18ee
09-30 06:37:05.536   927  3066 D wifi    : array field set
,09-30 06:37:05.537   927  3066 I WifiNative-HAL: interface[0] = wlan0
09-30 06:37:05.538   927  5830 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547074383744
09-30 06:37:05.540   927  5830 D wifi    : waitForHalEvents called, vm = 0x7f7c94d140, obj = 0x18ee, env = 0x7f5df83b00
,09-30 06:37:05.608  5831  5831 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 06:37:05.624  5831  5831 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 06:37:05.640   927  3066 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 06:37:05.647  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:05.652  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:05.653  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:05.677  5831  5831 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 06:37:05.677  5831  5831 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 06:37:05.692   927  3066 D WifiConfigStore: Loading config and enabling all networks 
,09-30 06:37:05.693  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:05.693  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:05.693  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:05.693  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:05.693  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:05.693  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:05.693  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:05.693  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:05.693  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:05.693  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:05.693  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:05.695  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:05.695  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:05.695  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:05.695  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:05.695  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:05.695  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:05.695  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:05.695  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:05.695  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 06:37:05.695  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:05.695  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 06:37:05.696  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:05.696  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:05.696  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:05.696  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:05.696  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:05.696  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:05.696  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:05.696  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:05.696  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:05.696  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:05.696  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 06:37:05.706   927  3066 D WifiConfigStore: loaded 0 passpoint configs
,09-30 06:37:05.706   927  3066 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 06:37:05.707   927  3066 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-30 06:37:05.708   927  3066 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 06:37:05.709   927  3066 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 06:37:05.709   927  3066 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 06:37:05.709   927  3066 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 06:37:05.710   927  3066 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 06:37:05.713   927  3066 D WifiNative-HAL: Setting external_sim to 1
,09-30 06:37:05.714  5075  5075 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 06:37:05.714   927  3066 D wifi    : setting dfs flag to true, 0x7f620f4d00
09-30 06:37:05.714   927  3066 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 06:37:05.714   927  3066 D wifi    : setting scan oui 0x7f620f4d00
09-30 06:37:05.714   927  3066 D WifiHAL : Sending mac address OUI
,09-30 06:37:05.719   927  3066 E native  : do suspend false
,09-30 06:37:05.725   927  3066 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-30 06:37:05.725   927   927 D RttService: SCAN_AVAILABLE : 3
09-30 06:37:05.726   927  3183 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-30 06:37:05.726   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 06:37:05.727   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:05.731   927  3050 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-30 06:37:05.731   927  3050 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 06:37:05.740   927  3050 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 06:37:05.746   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268960 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-30 06:37:05.746   927  3050 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 06:37:08.948  5831  5831 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:08.953  5831  5831 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:08.959  5831  5831 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-30 06:37:08.964  5831  5831 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:08.966  5831  5831 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:09.017   927  3066 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 06:37:09.018   927  3066 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 06:37:09.019   927  3066 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 06:37:09.030   927  3066 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 06:37:09.062   927  3066 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 06:37:09.064  5831  5831 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 06:37:09.492  5831  5831 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 06:37:09.525  5831  5831 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 06:37:09.526  5831  5831 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 06:37:09.535   927  3066 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-30 06:37:09.535   927  3066 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 06:37:09.535   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 06:37:09.551   927  3066 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 06:37:09.562   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:09.569   927  3066 D WifiStateMachine: Start Dhcp Watchdog 2
,09-30 06:37:09.575   927  5837 D DhcpClient: Receive thread started
,09-30 06:37:09.581   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 06:37:09.581   927  3066 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 06:37:09.581   927  3079 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-30 06:37:09.662   927  3066 E native  : do suspend false
,09-30 06:37:09.673   927  5836 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 06:37:09.695   927  5837 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,09-30 06:37:09.695   927  5836 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
,09-30 06:37:09.697   927  5836 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 06:37:09.716   927  5837 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 06:37:09.717   927  5836 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 06:37:09.719   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:09.724   927  3066 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 06:37:09.729   927  5836 D DhcpClient: Scheduling renewal in 86399s
,09-30 06:37:09.738   927  3066 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 06:37:09.739   927  3066 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 06:37:09.740   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 06:37:09.742   927  3066 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 06:37:09.749   927  3079 D ConnectivityService: Adding iface wlan0 to network 101
,09-30 06:37:09.798   927  3079 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-30 06:37:09.798   927  3079 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-30 06:37:09.802   927  3079 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-30 06:37:09.804   927  3079 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-30 06:37:09.805   927  3079 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-30 06:37:09.812   927  3079 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 06:37:09.817   927  3079 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-30 06:37:09.817   927  3079 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-30 06:37:09.817   927  3079 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-30 06:37:09.817   927  3079 D ConnectivityService:    accepting network in place of null
09-30 06:37:09.817   927  3066 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-30 06:37:09.818   927  3066 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 06:37:09.819   927  3079 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 06:37:09.825   927  5835 D NetlinkSocketObserver: NeighborEvent{elapsedMs=273039, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 06:37:09.847   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 06:37:09.868   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 06:37:09.871   927  3079 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-30 06:37:09.872   927  3079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 06:37:09.872  3819  4008 W QCNEJ   : |CORE| network available: 101
,09-30 06:37:09.872   927  3079 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-30 06:37:09.876   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-30 06:37:09.878  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:09.878  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:09.878  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:09.878  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:09.878  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:09.878  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:09.878  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:09.878  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:09.878  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:37:09.878  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:09.878  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:09.879  3819  4008 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 06:37:09.880  3819  4008 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 06:37:09.881  3819  4008 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 06:37:09.881  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 06:37:09.881  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:09.881  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:09.881  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:09.881  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:09.881  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:09.881  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:09.881  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:09.881  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:37:09.883  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:09.883  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:37:09.885  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:09.885  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:09.885  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:09.885  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:09.885  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:09.885  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:09.885  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:09.885  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:09.885  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:37:09.885  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:09.885  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:37:09.892  5101  5124 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-30 06:37:09.892  5101  5124 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-30 06:37:09.892  5101  5124 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 06:37:09.893  5101  5124 E SarControlService: no key has been found,reset the power
09-30 06:37:09.893  5101  5138 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 06:37:09.893  5101  5138 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 06:37:09.893  5101  5138 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 06:37:09.893  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 06:37:09.893  5126  5126 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 06:37:09.894  5101  5138 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 06:37:09.895  5101  5138 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 06:37:09.895  5101  5138 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-30 06:37:09.895  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-30 06:37:09.895  5126  5126 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 06:37:09.896  4019  4019 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-30 06:37:09.896   927  5834 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-30 06:37:09.900  3952  3952 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 06:37:09.901  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@928fe30 HexData = [00000000ec03000000000000ffffffff]
09-30 06:37:09.901  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 06:37:09.901  5126  5140 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-30 06:37:09.901  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 06:37:09.902  5101  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-30 06:37:09.905  3952  3952 D SystemUpdateService: onCreate
,09-30 06:37:09.909  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@928fe30 HexData = [00000000ed03000000000000ffffffff]
09-30 06:37:09.909  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 06:37:09.909  5126  5140 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-30 06:37:09.909  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 06:37:09.910  5101  5112 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 06:37:09.910  3952  3952 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 06:37:09.923  3952  3952 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 06:37:09.929  3952  5469 I iu.UploadsManager: num queued entries: 0
,09-30 06:37:09.929  3952  5469 I iu.UploadsManager: num updated entries: 0
09-30 06:37:09.930  3952  5469 I iu.SyncManager: NEXT; no task
,09-30 06:37:09.931  3952  5847 I SystemUpdateService: active receiver: enabled
,09-30 06:37:09.933  3952  3952 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 06:37:09.934  3952  3952 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 06:37:09.936  5471  5471 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 06:37:09.940  5471  5471 D SprintDMHelper: simOperator: 
09-30 06:37:09.940  5471  5471 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 06:37:09.945   927  3885 D WifiService: setWifiEnabled: false pid=5693, uid=10077
,09-30 06:37:09.945   927  3885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-30 06:37:09.947   927  3066 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-30 06:37:09.947   927  3066 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 06:37:09.947   927  3066 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 06:37:09.947   927  3066 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 06:37:09.951   927  5834 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 10:37:09 GMT], X-Android-Received-Millis=[1475231829948], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475231829919]}
,09-30 06:37:09.951   927  3079 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-30 06:37:09.951   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-30 06:37:09.951   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 06:37:09.952   927  3079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 06:37:09.955   927  5836 D DhcpClient: Clearing IP address
09-30 06:37:09.956   506   925 D CommandListener: Clearing all IP addresses on wlan0
,09-30 06:37:09.957   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:09.961  5075  5851 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-30 06:37:09.961  5075  5851 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 06:37:09.964  3952  5847 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 06:37:09.973   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 06:37:09.973   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-30 06:37:09.976   535   535 E Parcel  : Reading a NULL string not supported here.
09-30 06:37:09.977   927  3079 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-30 06:37:09.978   927   927 D RttService: SCAN_AVAILABLE : 1
09-30 06:37:09.978   927  3066 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-30 06:37:09.979   927  3183 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 06:37:09.979  3819  4008 W QCNEJ   : |CORE| network lost: 101
,09-30 06:37:09.980  3819  4008 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 06:37:09.981   927  3066 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 06:37:09.994  3952  5847 I SystemUpdateService: network: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 06:37:09.994  3952  5847 I SystemUpdateService: now status is 0 (complete)
,09-30 06:37:09.994  3952  5847 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 06:37:09.994  3952  5847 I SystemUpdateService: file has been verified
09-30 06:37:09.994  3952  5847 I SystemUpdateService: OTA package size = 21989297
09-30 06:37:09.996   927  5837 D DhcpClient: Receive thread stopped
09-30 06:37:10.002  3952  5847 I SystemUpdateService: showing system update notification
,09-30 06:37:10.003   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 06:37:10.013  3952  3952 D SystemUpdateService: onDestroy
,09-30 06:37:10.024   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 06:37:10.025   506   925 D CommandListener: Clearing all IP addresses on wlan0
09-30 06:37:10.025   927  3079 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 06:37:10.026   927  3079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 06:37:10.027   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-30 06:37:10.030  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.030  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:10.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:10.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:10.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:10.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:10.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:10.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:10.030  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:10.030  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.030  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:10.031  4019  4019 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-30 06:37:10.031   927  3066 D DhcpClient: doQuit
09-30 06:37:10.031   927  3066 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 06:37:10.032   927  5836 D DhcpClient: onQuitting
09-30 06:37:10.032  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.032  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:10.032  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:10.032  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:10.032  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:10.032  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:10.032  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:10.032  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:10.032  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:10.032  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 06:37:10.032  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:10.032  5831  5831 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 06:37:10.034  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.034  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:10.034  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:10.034  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:10.034  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:10.034  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:10.034  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:10.034  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:10.034  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:10.034  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.034  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:10.035  3952  3952 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 06:37:10.036  5101  5124 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 06:37:10.036  5101  5124 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 06:37:10.036  5101  5124 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 06:37:10.036  5101  5124 E SarControlService: no key has been found,reset the power
09-30 06:37:10.036  5101  5138 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 06:37:10.036  5101  5138 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 06:37:10.036  5101  5138 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 06:37:10.037  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 06:37:10.038  5126  5126 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 06:37:10.038  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 06:37:10.039  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:10.039  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:10.039  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:10.039  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:10.039  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:10.039  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:10.039  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:10.039  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:10.039  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.039  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:10.039  5101  5138 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 06:37:10.039  5101  5138 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 06:37:10.039  5101  5138 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 06:37:10.040  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 06:37:10.040  5126  5126 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 06:37:10.040  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.040  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:10.040  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:10.040  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:10.040  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:10.040  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:10.040  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:10.040  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:10.040  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 06:37:10.040  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.040  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:10.041  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.041  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:10.041  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:10.041  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:10.041  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:10.041  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:10.041  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:10.041  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:10.041  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:10.041  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:10.041  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 06:37:10.043  3952  3952 D SystemUpdateService: onCreate
,09-30 06:37:10.044  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@928fe30 HexData = [00000000ee03000000000000ffffffff]
09-30 06:37:10.044  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 06:37:10.044  5126  5140 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-30 06:37:10.044  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 06:37:10.045  5101  5112 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 06:37:10.046  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@928fe30 HexData = [00000000ef03000000000000ffffffff]
09-30 06:37:10.046  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 06:37:10.046  5126  5140 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-30 06:37:10.046  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 06:37:10.047  5101  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 06:37:10.047  5831  5831 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 06:37:10.049  3952  3952 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 06:37:10.052  5831  5831 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-30 06:37:10.060  3952  3952 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 06:37:10.065  3952  5863 I SystemUpdateService: active receiver: enabled
,09-30 06:37:10.066  3952  5469 I iu.UploadsManager: num queued entries: 0
,09-30 06:37:10.068  3952  3952 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 06:37:10.069  3952  3952 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 06:37:10.071  5471  5471 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 06:37:10.076  5471  5471 D SprintDMHelper: simOperator: 
09-30 06:37:10.076  5471  5471 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 06:37:10.083  5831  5831 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 06:37:10.086   506   925 E Netd    : netlink response contains error (No such file or directory)
09-30 06:37:10.086  3952  5469 I iu.UploadsManager: num updated entries: 0
,09-30 06:37:10.087  3952  5469 I iu.SyncManager: NEXT; no task
,09-30 06:37:10.090  5075  5869 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 06:37:10.092  5831  5831 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 06:37:10.094  3952  5863 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 06:37:10.101  3952  5863 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-30 06:37:10.101  3952  5863 I SystemUpdateService: now status is 0 (complete)
,09-30 06:37:10.101  3952  5863 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 06:37:10.101  3952  5863 I SystemUpdateService: file has been verified
09-30 06:37:10.101  3952  5863 I SystemUpdateService: OTA package size = 21989297
,09-30 06:37:10.110  3952  5863 I SystemUpdateService: showing system update notification
,09-30 06:37:10.119  3952  3952 D SystemUpdateService: onDestroy
,09-30 06:37:10.196   927  3066 D wifi    : In wifi stop Hal
,09-30 06:37:10.197   927  3066 D wifi    : halHandle = 0x7f602c9f80, mVM = 0x7f7c94d140, mCls = 0x18ee
09-30 06:37:10.197   927  5830 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 06:37:10.197   927  5830 D WifiHAL : Got a signal to exit!!!
09-30 06:37:10.197   927  5830 I WifiHAL : Exit wifi_event_loop
09-30 06:37:10.197   927  3066 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 06:37:10.197   927  3066 E WifiHAL : Event processing terminated
09-30 06:37:10.198   927  3066 D wifi    : In wifi cleaned up handler
,09-30 06:37:10.198   927  3066 I WifiHAL : Internal cleanup completed
09-30 06:37:10.199  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:10.199  5075  5075 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 06:37:10.200  4195  4336 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 06:37:10.200  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:10.202  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:10.220   927  5830 D wifi    : set interface wlan0 flags (DOWN)
,09-30 06:37:10.220   927  3066 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 06:37:10.427   927   944 D Tethering: InitialState.processMessage what=4
,09-30 06:37:10.433   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 06:37:10.872   927  3079 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-30 06:37:11.213   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:12.214   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:13.215   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:14.216   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:14.982   927   944 I ActivityManager: Start proc 5871:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 06:37:15.063  5871  5871 D AdapterServiceConfig: Adding HeadsetService
,09-30 06:37:15.063  5871  5871 D AdapterServiceConfig: Adding A2dpService
09-30 06:37:15.063  5871  5871 D AdapterServiceConfig: Adding HidService
09-30 06:37:15.064  5871  5871 D AdapterServiceConfig: Adding HealthService
,09-30 06:37:15.064  5871  5871 D AdapterServiceConfig: Adding PanService
09-30 06:37:15.064  5871  5871 D AdapterServiceConfig: Adding GattService
,09-30 06:37:15.064  5871  5871 D AdapterServiceConfig: Adding BluetoothMapService
09-30 06:37:15.064  5871  5871 D AdapterServiceConfig: Adding SapService
,09-30 06:37:15.078   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f4b82b5:true
,09-30 06:37:15.078  5871  5871 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 06:37:15.081  5871  5871 I bt_bluedroid: init
09-30 06:37:15.081  5871  5883 I BluetoothAdapterState: Entering OffState
,09-30 06:37:15.083  5871  5884 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 06:37:15.084  5871  5884 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 06:37:15.084  5871  5884 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 06:37:15.084  5871  5884 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 06:37:15.084  5871  5871 I bt_bluedroid: get_profile_interface socket
,09-30 06:37:15.086  5871  5887 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 06:37:15.086  5871  5871 I bt_bluedroid: get_profile_interface sdp
09-30 06:37:15.088  5871  5887 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 06:37:15.091  5871  5882 I bt_bluedroid: config_hci_snoop_log
,09-30 06:37:15.093   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 06:37:15.097  5871  5883 D BluetoothAdapterState: Current state: OFF, message: 0
,09-30 06:37:15.097  5871  5883 D BluetoothAdapterProperties: Setting state to 14
09-30 06:37:15.097  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-30 06:37:15.099  5871  5883 D BluetoothBondStateMachine: make
,09-30 06:37:15.101  5871  5888 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 06:37:15.104  5871  5883 I BluetoothAdapterState: Entering PendingCommandState
,09-30 06:37:15.105  5871  5871 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 06:37:15.107  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:15.108  5871  5871 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 06:37:15.109  5871  5871 D BtGatt.GattService: Received start request. Starting profile...
09-30 06:37:15.109  5871  5871 D BtGatt.GattService: start()
09-30 06:37:15.109  5871  5871 I bt_bluedroid: get_profile_interface gatt
,09-30 06:37:15.110  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:15.110  5871  5871 D BtGatt.AdvertiseManager: advertise manager created
,09-30 06:37:15.115  5871  5871 V BluetoothAdapterState: isTurningOff()=false
,09-30 06:37:15.115  5871  5871 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:15.116  5871  5871 V BluetoothAdapterState: isBleTurningOn()=true
09-30 06:37:15.116  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:15.116  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 06:37:15.117  5871  5883 I bt_bluedroid: bt_bluedroid
09-30 06:37:15.117  5871  5884 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 06:37:15.118  5871  5884 I bt_hci  : start_up
,09-30 06:37:15.123  5871  5884 I bt_vendor: alloc value 0xf3b7f871
,09-30 06:37:15.123  5871  5884 I bt_vendor: init
09-30 06:37:15.123  5871  5884 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 06:37:15.124  5871  5884 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 06:37:15.216   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:15.235  5871  5884 D bt_hci  : start_up starting async portion
,09-30 06:37:15.236  5871  5891 I bt_hci  : event_finish_startup
09-30 06:37:15.236  5871  5891 I bt_hci_h4: hal_open
09-30 06:37:15.236  5871  5891 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 06:37:15.232  5892  5892 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 06:37:15.239  5871  5891 I bt_userial_vendor: device fd = 54 open
,09-30 06:37:15.254  5871  5891 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 06:37:15.257  5871  5891 D bt_hwcfg: Chipset BCM4358A3
,09-30 06:37:15.257  5871  5891 D bt_hwcfg: Target name = [BCM4358A3]
09-30 06:37:15.258  5871  5891 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 06:37:15.657  5871  5891 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 06:37:15.657  5871  5891 D bt_hwcfg: Settlement delay -- 100 ms
09-30 06:37:15.657  5871  5891 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 06:37:15.791  5871  5891 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 06:37:15.792  5871  5891 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 06:37:15.794  5871  5891 I bt_hwcfg: vendor lib fwcfg completed
09-30 06:37:15.794  5871  5891 I bt_vendor: firmware callback
09-30 06:37:15.794  5871  5891 I bt_hci  : firmware_config_callback
,09-30 06:37:15.803  5871  5894 I bt_btu  : btu_task pending for preload complete event
,09-30 06:37:15.803  5871  5894 I bt_btu_task: Bluetooth chip preload is complete
,09-30 06:37:15.804  5871  5894 I bt_btu  : btu_task received preload complete event
,09-30 06:37:15.811  5871  5894 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 06:37:15.811  5871  5894 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 06:37:15.811  5871  5894 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-30 06:37:15.812  5871  5894 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 06:37:15.813  5871  5894 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 06:37:15.813  5871  5894 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 06:37:15.813  5871  5894 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 06:37:15.813  5871  5894 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 06:37:15.813  5871  5894 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 06:37:15.813  5871  5894 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 06:37:15.813  5871  5894 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 06:37:15.814  5871  5894 I         : BTE_InitTraceLevels -- TRC_GATT
,09-30 06:37:15.814  5871  5894 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 06:37:15.814  5871  5894 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 06:37:15.814  5871  5894 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 06:37:15.897  5871  5894 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3afd549
09-30 06:37:15.897  5871  5894 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3afd549 
,09-30 06:37:15.908  5871  5887 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 06:37:15.909  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 06:37:15.910  5871  5887 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 06:37:15.913  5871  5887 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 06:37:15.916  5871  5887 D BluetoothAdapterProperties: Scan Mode:20
,09-30 06:37:15.917  5871  5887 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 06:37:15.917  5871  5887 D bt_hci  : do_postload posting postload work item
09-30 06:37:15.917  5871  5891 I bt_hci  : event_postload
,09-30 06:37:15.917  5871  5891 I bt_vendor: sco_config_cb
09-30 06:37:15.917  5871  5891 I bt_hci  : sco_config_callback postload finished.
,09-30 06:37:15.924  5871  5887 D bt_bte_conf: Device ID record 1 : primary
,09-30 06:37:15.924  5871  5887 D bt_bte_conf:   vendorId            = 000f
09-30 06:37:15.924  5871  5887 D bt_bte_conf:   vendorIdSource      = 0001
09-30 06:37:15.924  5871  5887 D bt_bte_conf:   product             = 1200
09-30 06:37:15.924  5871  5887 D bt_bte_conf:   version             = 1436
09-30 06:37:15.924  5871  5887 D bt_bte_conf:   clientExecutableURL = 
09-30 06:37:15.924  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:15.924  5871  5887 D bt_bte_conf:   serviceDescription  = 
09-30 06:37:15.924  5871  5887 D bt_bte_conf:   documentationURL    = 
09-30 06:37:15.924  5871  5887 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 06:37:15.925  5871  5884 D bt_stack_manager: event_start_up_stack finished
,09-30 06:37:15.927  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 06:37:15.927  5871  5883 D BluetoothAdapterProperties: Setting state to 15
09-30 06:37:15.927  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 06:37:15.928  5871  5891 I bt_vendor: low_power_mode_cb
09-30 06:37:15.928  5871  5883 I BluetoothAdapterState: Entering BleOnState
09-30 06:37:15.929  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:15.932  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:15.932  5871  5883 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 06:37:15.932  5871  5883 D BluetoothAdapterProperties: Setting state to 11
09-30 06:37:15.932  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 06:37:15.937  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:15.937  5871  5871 D HeadsetService: Received start request. Starting profile...
,09-30 06:37:15.940  5871  5871 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-30 06:37:15.940  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:15.940  5871  5871 D HeadsetStateMachine: make
09-30 06:37:15.943  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:15.945  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:15.951  5871  5883 I BluetoothAdapterState: Entering PendingCommandState
,09-30 06:37:15.951  5871  5871 D HeadsetStateMachine: max_hf_connections = 1
,09-30 06:37:15.951  5871  5871 I bt_bluedroid: get_profile_interface handsfree
09-30 06:37:15.952  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 06:37:15.952  5871  5887 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,09-30 06:37:15.955  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:15.955  5871  5871 D A2dpService: Received start request. Starting profile...
,09-30 06:37:15.956  5871  5871 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 06:37:15.956  5871  5871 I bt_bluedroid: get_profile_interface avrcp
,09-30 06:37:15.961  5871  5871 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 06:37:15.961  5871  5871 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 06:37:15.962  5871  5871 D A2dpStateMachine: make
,09-30 06:37:15.963  5871  5871 I bt_bluedroid: get_profile_interface a2dp
,09-30 06:37:15.963  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 06:37:15.965  5871  5902 D A2dpStateMachine: Enter Disconnected: -2
,09-30 06:37:15.965  5871  5871 I BluetoothHidServiceJni: classInitNative: succeeds
,09-30 06:37:15.966  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:15.967  5746  5746 D BluetoothInputDevice: Proxy object connected
,09-30 06:37:15.968  5871  5871 D HidService: Received start request. Starting profile...
09-30 06:37:15.968  5746  5746 D HidProfile: Bluetooth service connected
09-30 06:37:15.968  5871  5871 I bt_bluedroid: get_profile_interface hidhost
09-30 06:37:15.968  5871  5887 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ade56d
09-30 06:37:15.968  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 06:37:15.968  5871  5871 D HidService: setHidService(): set to: null
,09-30 06:37:15.970  5871  5871 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-30 06:37:15.971  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:15.971  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 06:37:15.972  5871  5871 D HealthService: Received start request. Starting profile...
,09-30 06:37:15.973  5871  5871 I bt_bluedroid: get_profile_interface health
,09-30 06:37:15.974  5871  5871 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 06:37:15.975  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:15.976  5746  5746 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 06:37:15.976  5871  5871 D PanService: Received start request. Starting profile...
09-30 06:37:15.976  5871  5871 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 06:37:15.976  5871  5871 I bt_bluedroid: get_profile_interface pan
09-30 06:37:15.976  5746  5746 D PanProfile: Bluetooth service connected
09-30 06:37:15.977  5871  5887 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 06:37:15.980  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:15.981  5746  5746 D BluetoothMap: Proxy object connected
,09-30 06:37:15.981  5871  5871 D BluetoothMapService: Received start request. Starting profile...
09-30 06:37:15.981  5871  5871 D BluetoothMapService: start()
09-30 06:37:15.982  5746  5746 D MapProfile: Bluetooth service connected
09-30 06:37:15.982  5746  5746 D BluetoothMap: getConnectedDevices()
09-30 06:37:15.982  5746  5746 D BluetoothMap: Bluetooth is Not enabled
,09-30 06:37:15.984  5871  5871 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-30 06:37:15.985  5871  5871 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-30 06:37:15.985  5871  5871 D BluetoothMapAppObserver: createReceiver()
09-30 06:37:15.986  5871  5871 D BluetoothMapAppObserver: initObservers()
09-30 06:37:15.986  5871  5871 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 06:37:15.992  5871  5871 V SapService: SapBinder()
,09-30 06:37:15.992  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:15.993  5871  5871 D SapService: Received start request. Starting profile...
09-30 06:37:15.993  5871  5871 V SapService: start()
,09-30 06:37:15.994  5871  5871 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:15.994  5871  5871 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:15.994  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:15.994  5871  5900 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 06:37:15.994  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isTurningOff()=false
,09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:15.995  5871  5871 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:15.996  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:15.997  5871  5871 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:15.997  5871  5871 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:15.997  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:15.997  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:15.997  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 06:37:15.997  5871  5883 D BluetoothAdapterProperties: ScanMode =  20
09-30 06:37:15.997  5871  5883 D BluetoothAdapterProperties: State =  11
09-30 06:37:15.997  5871  5883 D BluetoothAdapterProperties: Setting state to 12
09-30 06:37:15.997  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 06:37:15.998  5871  5883 I BluetoothAdapterState: Entering OnState
09-30 06:37:15.998  3233  3245 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 06:37:15.999  5871  5887 D BluetoothAdapterProperties: Scan Mode:21
,09-30 06:37:16.000  5871  5887 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 06:37:16.000   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:16.000  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 06:37:16.000   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:16.000   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:16.001  3233  3247 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 06:37:16.003  3233  3233 D BluetoothA2dp: Proxy object connected
,09-30 06:37:16.003  5746  5759 D BluetoothPan: onBluetoothStateChange on: true
09-30 06:37:16.004  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:16.004  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:16.004  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:16.004  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:16.004  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:16.004  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:16.004  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:16.004  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 06:37:16.006  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:16.008  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:16.008  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:16.008  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:16.008  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:16.008  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:16.008  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:16.008  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:16.008  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 06:37:16.010  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:16.011  5871  5871 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 06:37:16.011  5871  5871 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 06:37:16.012  3233  3245 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-30 06:37:16.012  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:16.012  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:16.012  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:16.012  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:16.012  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:16.012  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:16.012  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:16.012  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:16.013  5871  5871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 06:37:16.013  5746  5758 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 06:37:16.013  3233  3233 D BluetoothInputDevice: Proxy object connected
09-30 06:37:16.013  3233  3233 D HidProfile: Bluetooth service connected
09-30 06:37:16.014  5871  5871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 06:37:16.014  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:16.014   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 06:37:16.015   927   927 D BluetoothA2dp: Proxy object connected
09-30 06:37:16.015  5746  5759 D BluetoothMap: onBluetoothStateChange: up=true
09-30 06:37:16.015  5746  5758 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-30 06:37:16.016  3233  3247 D BluetoothPan: onBluetoothStateChange on: true
09-30 06:37:16.016  5871  5871 D ObexServerSockets: Succeed to create listening sockets 
09-30 06:37:16.016  5871  5871 D ObexServerSockets0: startAccept()
09-30 06:37:16.016  5871  5871 D ObexServerSockets0: prepareForNewConnect()
09-30 06:37:16.017  3866  4095 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:16.017  3233  3233 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 06:37:16.017  3233  3233 D PanProfile: Bluetooth service connected
09-30 06:37:16.018  3233  4076 D BluetoothMap: onBluetoothStateChange: up=true
09-30 06:37:16.018  5871  5871 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 06:37:16.018  5871  5871 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 06:37:16.018  5871  5908 D ObexServerSockets0: Accepting socket connection...
,09-30 06:37:16.019  3233  3247 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:16.019  3233  3233 D BluetoothMap: Proxy object connected
,09-30 06:37:16.020  3233  3233 D MapProfile: Bluetooth service connected
,09-30 06:37:16.020  3233  3233 D BluetoothMap: getConnectedDevices()
09-30 06:37:16.020  5871  5909 D ObexServerSockets0: Accepting socket connection...
09-30 06:37:16.023   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 06:37:16.024  5871  5871 D BluetoothMapService: onReceive
09-30 06:37:16.024  5871  5871 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 06:37:16.024  5871  5871 D BluetoothMapService: STATE_ON
09-30 06:37:16.024  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 06:37:16.026  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:16.026  5871  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 06:37:16.028  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:16.028  5746  5746 D LocalBluetoothProfileManager: Adding local A2DP profile
09-30 06:37:16.029  5871  5910 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 06:37:16.029  5871  5910 D BluetoothSdpJni: SDP Create record success - handle: 1
09-30 06:37:16.029  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:16.032  5746  5746 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-30 06:37:16.037  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 06:37:16.039  5746  5746 D BluetoothA2dp: Proxy object connected
,09-30 06:37:16.045  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 06:37:16.047  5746  5746 D DockEventReceiver: finishStartingService: stopping service
,09-30 06:37:16.052  3233  3233 D BluetoothPbap: Proxy object connected
,09-30 06:37:16.052  3233  3233 D PbapServerProfile: Bluetooth service connected
,09-30 06:37:16.052  5871  5871 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 06:37:16.052  5871  5871 D ObexServerSockets0: prepareForNewConnect()
,09-30 06:37:16.055  5746  5746 D BluetoothPbap: Proxy object connected
09-30 06:37:16.055  5746  5746 D PbapServerProfile: Bluetooth service connected
,09-30 06:37:16.060  5871  5915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 06:37:16.074  5871  5919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 06:37:16.076  5871  5919 I BtOppRfcommListener: Accept thread started.
,09-30 06:37:16.102   927   927 D BluetoothHeadset: Proxy object connected
,09-30 06:37:16.102   927   927 D BluetoothHeadset: Proxy object connected
09-30 06:37:16.102   927   927 D BluetoothHeadset: Proxy object connected
09-30 06:37:16.102  3233  3245 D BluetoothHeadset: Proxy object connected
09-30 06:37:16.102  3233  3233 D HeadsetProfile: Bluetooth service connected
,09-30 06:37:16.103  3866  3884 D BluetoothHeadset: Proxy object connected
,09-30 06:37:16.117  3866  3883 D BluetoothHeadset: Proxy object connected
,09-30 06:37:16.123  3233  3247 D BluetoothHeadset: Proxy object connected
,09-30 06:37:16.123  3233  3233 D HeadsetProfile: Bluetooth service connected
,09-30 06:37:16.133  5746  5759 D BluetoothHeadset: Proxy object connected
,09-30 06:37:16.134  5746  5746 D HeadsetProfile: Bluetooth service connected
,09-30 06:37:16.216   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 06:37:17.824   927  3079 D ConnectivityService: handlePromptUnvalidated 101
,09-30 06:37:19.963  5871  5883 D BluetoothAdapterState: Current state: ON, message: 23
09-30 06:37:19.963  5871  5883 D BluetoothAdapterProperties: Setting state to 13
,09-30 06:37:19.964  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-30 06:37:19.965  5871  5883 D BluetoothAdapterProperties: onBluetoothDisable()
,09-30 06:37:19.966  5871  5883 I BluetoothAdapterState: Entering PendingCommandState
09-30 06:37:19.970  5871  5871 D BluetoothMapService: onReceive
09-30 06:37:19.971  5871  5871 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 06:37:19.971  5871  5871 D BluetoothMapService: STATE_TURNING_OFF
09-30 06:37:19.971  5871  5871 D BluetoothMapService: MAP Service closeService in
09-30 06:37:19.972  5871  5871 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 06:37:19.972  5871  5871 D ObexServerSockets0: shutdown(block = true)
09-30 06:37:19.973  5871  5871 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 06:37:19.974  5871  5871 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 06:37:19.974  5871  5909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-30 06:37:19.976  5871  5887 D BluetoothAdapterProperties: Scan Mode:20
09-30 06:37:19.976  5871  5908 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-30 06:37:19.976  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 06:37:19.977  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:19.978  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:19.978  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:19.978  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:19.978  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:19.978  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:19.978  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:19.978  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:19.978  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:19.979  5871  5896 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-30 06:37:19.979  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:19.979  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:19.980  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 06:37:19.980  5871  5871 I BtOppRfcommListener: stopping Accept Thread
09-30 06:37:19.980  5871  5919 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 06:37:19.981  5871  5919 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 06:37:19.982  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:19.982  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:19.982  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:19.982  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:19.982  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:19.982  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:19.982  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:19.982  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:19.982  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 06:37:19.985  5871  5871 D HeadsetService: Received stop request...Stopping profile...
09-30 06:37:19.985  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 06:37:19.985  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 06:37:19.988  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 06:37:19.988  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:19.988  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:19.988  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:19.988  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:19.988  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 06:37:19.988  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:19.988  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:19.988  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:19.990  5693  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 06:37:19.990  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:19.992  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:19.993   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 06:37:19.993   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 06:37:19.993   927   927 D BluetoothHeadset: Proxy object disconnected
,09-30 06:37:19.993  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:19.993  5746  5759 D BluetoothHeadset: Proxy object disconnected
09-30 06:37:19.994  3233  3245 D BluetoothHeadset: Proxy object disconnected
,09-30 06:37:19.994  3866  4095 D BluetoothHeadset: Proxy object disconnected
,09-30 06:37:19.995  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:19.997  5746  5746 D DockEventReceiver: finishStartingService: stopping service
09-30 06:37:19.998  5746  5746 D HeadsetProfile: Bluetooth service disconnected
09-30 06:37:19.998  5871  5871 D A2dpService: Received stop request...Stopping profile...
09-30 06:37:20.000  5871  5902 D A2dpStateMachine: Exit Disconnected: -1
09-30 06:37:20.001  3233  3233 D HeadsetProfile: Bluetooth service disconnected
09-30 06:37:20.002  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 06:37:20.003   927   927 D BluetoothA2dp: Proxy object disconnected
09-30 06:37:20.003  5746  5746 D BluetoothA2dp: Proxy object disconnected
09-30 06:37:20.004  5871  5871 D HidService: Received stop request...Stopping profile...
,09-30 06:37:20.004  5871  5871 D HidService: Stopping Bluetooth HidService
09-30 06:37:20.005  5746  5746 D BluetoothInputDevice: Proxy object disconnected
09-30 06:37:20.005  3233  3233 D BluetoothA2dp: Proxy object disconnected
09-30 06:37:20.005  5746  5746 D HidProfile: Bluetooth service disconnected
09-30 06:37:20.005  3233  3233 D BluetoothInputDevice: Proxy object disconnected
,09-30 06:37:20.005  3233  3233 D HidProfile: Bluetooth service disconnected
,09-30 06:37:20.006  5871  5871 D HealthService: Received stop request...Stopping profile...
09-30 06:37:20.007  5871  5871 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:20.007  5871  5871 V BluetoothAdapterState: isTurningOn()=false
,09-30 06:37:20.007  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:20.007  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:20.007  5871  5871 D PanService: Received stop request...Stopping profile...
09-30 06:37:20.009  3233  3233 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 06:37:20.009  3233  3233 D PanProfile: Bluetooth service disconnected
09-30 06:37:20.009  5746  5746 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 06:37:20.009  5746  5746 D PanProfile: Bluetooth service disconnected
09-30 06:37:20.010  5871  5871 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 06:37:20.010  5871  5871 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 06:37:20.010  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-30 06:37:20.010  5871  5894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:37:20.010  5871  5894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:37:20.010  5871  5894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:37:20.010  5871  5871 D BluetoothMapService: Received stop request...Stopping profile...
09-30 06:37:20.010  5871  5887 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 06:37:20.010  5871  5871 D BluetoothMapService: stop()
09-30 06:37:20.011  5871  5871 D BluetoothMapAppObserver: deinitObservers()
09-30 06:37:20.011  5871  5871 D BluetoothMapAppObserver: removeReceiver()
09-30 06:37:20.012  3233  3233 D BluetoothMap: Proxy object disconnected
09-30 06:37:20.012  3233  3233 D MapProfile: Bluetooth service disconnected
09-30 06:37:20.013  5871  5871 D SapService: Received stop request...Stopping profile...
09-30 06:37:20.013  5871  5871 V SapService: stop()
,09-30 06:37:20.014  5746  5746 D BluetoothMap: Proxy object disconnected
09-30 06:37:20.014  5746  5746 D MapProfile: Bluetooth service disconnected
,09-30 06:37:20.016  5746  5746 D BluetoothPbap: Proxy object disconnected
09-30 06:37:20.016  5746  5746 D PbapServerProfile: Bluetooth service disconnected
09-30 06:37:20.016  5871  5871 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:20.016  5871  5871 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:20.016  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:20.016  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 06:37:20.017  3233  3233 D BluetoothPbap: Proxy object disconnected
,09-30 06:37:20.017  3233  3233 D PbapServerProfile: Bluetooth service disconnected
09-30 06:37:20.017  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 06:37:20.018  5871  5871 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:20.018  5871  5871 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:20.018  5871  5894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:37:20.018  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:20.018  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:20.018  5871  5894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 06:37:20.018  5871  5894 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-30 06:37:20.018  5871  5871 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 06:37:20.018  5871  5894 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-30 06:37:20.018  5871  5871 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 06:37:20.018  5871  5894 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 06:37:20.018  5871  5894 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 06:37:20.018  5871  5871 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:20.018  5871  5871 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:20.018  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:20.018  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:20.018  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 06:37:20.018  5871  5871 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 06:37:20.019  5871  5871 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-30 06:37:20.019  5871  5887 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 06:37:20.019  5871  5871 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:20.019  5871  5871 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:20.019  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:20.019  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:20.019  5871  5871 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 06:37:20.019  5871  5871 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 06:37:20.020  5871  5871 D BluetoothMapService: MAP Service closeService in
09-30 06:37:20.020  5871  5871 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:20.020  5871  5871 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:20.020  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:20.020  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:20.020  5871  5871 D BluetoothMapService: cleanup()
09-30 06:37:20.020  5871  5871 D BluetoothMapService: MAP Service closeService in
09-30 06:37:20.021  5871  5871 V BluetoothAdapterState: isTurningOff()=true
09-30 06:37:20.021  5871  5871 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:20.021  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:20.021  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:20.021  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 06:37:20.021  5871  5883 D BluetoothAdapterProperties: Setting state to 15
09-30 06:37:20.021  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 06:37:20.022  3233  4076 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 06:37:20.022  5871  5883 I BluetoothAdapterState: Entering BleOnState
09-30 06:37:20.024   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:20.027   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:20.027   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:20.027  5746  5758 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 06:37:20.028  3233  3247 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 06:37:20.029  5746  5759 D BluetoothPan: onBluetoothStateChange on: false
09-30 06:37:20.029  3233  3245 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 06:37:20.030  5746  5758 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 06:37:20.031   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 06:37:20.031  5746  5759 D BluetoothMap: onBluetoothStateChange: up=false
09-30 06:37:20.031  5746  5758 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 06:37:20.032  3233  4076 D BluetoothPan: onBluetoothStateChange on: false
09-30 06:37:20.033  3866  3884 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:20.033  5746  5759 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:20.033  3233  3247 D BluetoothMap: onBluetoothStateChange: up=false
09-30 06:37:20.034  3233  3245 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 06:37:20.034  5871  5883 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 06:37:20.034  5871  5883 D BluetoothAdapterProperties: Setting state to 16
09-30 06:37:20.034  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-30 06:37:20.037  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:20.037  5871  5883 D BluetoothAdapterProperties: onBleDisable
09-30 06:37:20.037  5871  5883 I BluetoothAdapterState: Entering PendingCommandState
09-30 06:37:20.037  5871  5884 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 06:37:20.038  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:20.038  5871  5887 D BluetoothAdapterProperties: Scan Mode:20
09-30 06:37:20.038  5871  5894 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 06:37:20.039  5871  5894 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 06:37:20.039  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:20.041  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 06:37:20.041  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:20.043  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:20.044  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:20.046  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 06:37:20.051  5746  5746 D DockEventReceiver: finishStartingService: stopping service
,09-30 06:37:20.248  5871  5887 I bt_hci  : shut_down
,09-30 06:37:20.253  5871  5891 D bt_hwcfg: hw_epilog_process
,09-30 06:37:20.254  5871  5891 I bt_vendor: low_power_mode_cb
,09-30 06:37:20.258  5871  5891 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 06:37:20.258  5871  5891 I bt_vendor: epilog_cb
09-30 06:37:20.258  5871  5891 I bt_hci  : epilog_finished_callback
,09-30 06:37:20.263  5871  5887 I bt_hci_h4: hal_close
,09-30 06:37:20.264  5871  5887 I bt_userial_vendor: device fd = 54 close
,09-30 06:37:20.380  5871  5884 D bt_stack_manager: event_shut_down_stack finished.
,09-30 06:37:20.381  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 06:37:20.387  5871  5883 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 06:37:20.387  5871  5871 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 06:37:20.388  5871  5871 D BtGatt.GattService: Received stop request...Stopping profile...
,09-30 06:37:20.389  5871  5871 D BtGatt.GattService: stop()
09-30 06:37:20.389  5871  5871 D BtGatt.AdvertiseManager: advertise clients cleared
,09-30 06:37:20.392  5871  5871 V BluetoothAdapterState: isTurningOff()=false
,09-30 06:37:20.393  5871  5871 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:20.393  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:20.393  5871  5871 V BluetoothAdapterState: isBleTurningOff()=true
09-30 06:37:20.393  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-30 06:37:20.394  5871  5883 D BluetoothAdapterProperties: Setting state to 10
09-30 06:37:20.394  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 06:37:20.395  5871  5883 I BluetoothAdapterState: Entering OffState
09-30 06:37:20.397   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-30 06:37:20.410  5871  5871 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 06:37:20.410  5871  5871 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 06:37:20.411  5871  5871 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-30 06:37:20.412  5871  5884 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 06:37:20.421  5871  5871 I art     : System.exit called, status: 0
,09-30 06:37:20.421  5871  5871 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 06:37:20.447   927   938 I ActivityManager: Process com.android.bluetooth (pid 5871) has died
,09-30 06:37:24.964  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:24.964  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:37:24.970  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:37:24.970  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3100812 removed from the list
09-30 06:37:24.970  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:24.970  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:24.970  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:24.973  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 06:37:24.973  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ae39e0 added. We now have 4 listener(s)
09-30 06:37:24.973  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:24.975  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:37:24.975  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ae39e0 removed from the list
09-30 06:37:24.975  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:24.975  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:37:24.975  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:24.978  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:24.979  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8111499 added. We now have 4 listener(s)
,09-30 06:37:24.979  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:37:29.992  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:30.029   927   944 I ActivityManager: Start proc 5927:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 06:37:30.126  5927  5927 D AdapterServiceConfig: Adding HeadsetService
,09-30 06:37:30.127  5927  5927 D AdapterServiceConfig: Adding A2dpService
09-30 06:37:30.127  5927  5927 D AdapterServiceConfig: Adding HidService
09-30 06:37:30.128  5927  5927 D AdapterServiceConfig: Adding HealthService
09-30 06:37:30.128  5927  5927 D AdapterServiceConfig: Adding PanService
09-30 06:37:30.128  5927  5927 D AdapterServiceConfig: Adding GattService
,09-30 06:37:30.128  5927  5927 D AdapterServiceConfig: Adding BluetoothMapService
09-30 06:37:30.129  5927  5927 D AdapterServiceConfig: Adding SapService
,09-30 06:37:30.144   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e11040a:true
,09-30 06:37:30.144  5927  5927 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 06:37:30.148  5927  5927 I bt_bluedroid: init
,09-30 06:37:30.148  5927  5939 I BluetoothAdapterState: Entering OffState
,09-30 06:37:30.151  5927  5940 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 06:37:30.151  5927  5940 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 06:37:30.151  5927  5940 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 06:37:30.151  5927  5940 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-30 06:37:30.152  5927  5927 I bt_bluedroid: get_profile_interface socket
,09-30 06:37:30.154  5927  5943 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 06:37:30.155  5927  5927 I bt_bluedroid: get_profile_interface sdp
09-30 06:37:30.156  5927  5943 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 06:37:30.161  5927  5938 I bt_bluedroid: config_hci_snoop_log
,09-30 06:37:30.163   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-30 06:37:30.168  5927  5939 D BluetoothAdapterState: Current state: OFF, message: 0
09-30 06:37:30.168  5927  5939 D BluetoothAdapterProperties: Setting state to 14
09-30 06:37:30.168  5927  5939 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 06:37:30.170  5927  5939 D BluetoothBondStateMachine: make
,09-30 06:37:30.173  5927  5944 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 06:37:30.176  5927  5939 I BluetoothAdapterState: Entering PendingCommandState
,09-30 06:37:30.177  5927  5927 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 06:37:30.181  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:30.181  5927  5927 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 06:37:30.182  5927  5927 D BtGatt.GattService: Received start request. Starting profile...
09-30 06:37:30.182  5927  5927 D BtGatt.GattService: start()
09-30 06:37:30.182  5927  5927 I bt_bluedroid: get_profile_interface gatt
,09-30 06:37:30.184  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:30.184  5927  5927 D BtGatt.AdvertiseManager: advertise manager created
,09-30 06:37:30.191  5927  5927 V BluetoothAdapterState: isTurningOff()=false
,09-30 06:37:30.191  5927  5927 V BluetoothAdapterState: isTurningOn()=false
09-30 06:37:30.191  5927  5927 V BluetoothAdapterState: isBleTurningOn()=true
09-30 06:37:30.191  5927  5927 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:30.192  5927  5939 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 06:37:30.193  5927  5939 I bt_bluedroid: bt_bluedroid
09-30 06:37:30.193  5927  5940 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 06:37:30.194  5927  5940 I bt_hci  : start_up
,09-30 06:37:30.200  5927  5940 I bt_vendor: alloc value 0xf3b7f871
,09-30 06:37:30.200  5927  5940 I bt_vendor: init
09-30 06:37:30.200  5927  5940 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 06:37:30.200  5927  5940 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 06:37:30.309  5927  5940 D bt_hci  : start_up starting async portion
,09-30 06:37:30.309  5927  5947 I bt_hci  : event_finish_startup
09-30 06:37:30.310  5927  5947 I bt_hci_h4: hal_open
09-30 06:37:30.310  5927  5947 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 06:37:30.313  5927  5947 I bt_userial_vendor: device fd = 54 open
,09-30 06:37:30.309  5948  5948 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 06:37:30.331  5927  5947 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 06:37:30.334  5927  5947 D bt_hwcfg: Chipset BCM4358A3
,09-30 06:37:30.334  5927  5947 D bt_hwcfg: Target name = [BCM4358A3]
09-30 06:37:30.335  5927  5947 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 06:37:30.850  5927  5947 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 06:37:30.851  5927  5947 D bt_hwcfg: Settlement delay -- 100 ms
09-30 06:37:30.851  5927  5947 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 06:37:30.985  5927  5947 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 06:37:30.986  5927  5947 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 06:37:30.988  5927  5947 I bt_hwcfg: vendor lib fwcfg completed
09-30 06:37:30.988  5927  5947 I bt_vendor: firmware callback
09-30 06:37:30.988  5927  5947 I bt_hci  : firmware_config_callback
,09-30 06:37:30.997  5927  5950 I bt_btu  : btu_task pending for preload complete event
,09-30 06:37:30.997  5927  5950 I bt_btu_task: Bluetooth chip preload is complete
09-30 06:37:30.997  5927  5950 I bt_btu  : btu_task received preload complete event
,09-30 06:37:31.004  5927  5950 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 06:37:31.004  5927  5950 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 06:37:31.004  5927  5950 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 06:37:31.004  5927  5950 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 06:37:31.005  5927  5950 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 06:37:31.005  5927  5950 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 06:37:31.005  5927  5950 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 06:37:31.005  5927  5950 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 06:37:31.005  5927  5950 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 06:37:31.005  5927  5950 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 06:37:31.005  5927  5950 I         : BTE_InitTraceLevels -- TRC_SDP
,09-30 06:37:31.005  5927  5950 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 06:37:31.006  5927  5950 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 06:37:31.006  5927  5950 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-30 06:37:31.006  5927  5950 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 06:37:31.107  5927  5950 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3afd549
09-30 06:37:31.107  5927  5950 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3afd549 
,09-30 06:37:31.135  5927  5943 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 06:37:31.137  5927  5943 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 06:37:31.138  5927  5943 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 06:37:31.140  5927  5943 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 06:37:31.143  5927  5943 D BluetoothAdapterProperties: Scan Mode:20
09-30 06:37:31.143  5927  5943 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 06:37:31.145  5927  5943 D bt_hci  : do_postload posting postload work item
,09-30 06:37:31.145  5927  5947 I bt_hci  : event_postload
09-30 06:37:31.146  5927  5947 I bt_vendor: sco_config_cb
09-30 06:37:31.146  5927  5947 I bt_hci  : sco_config_callback postload finished.
,09-30 06:37:31.148  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:31.148  5927  5943 D bt_bte_conf: Device ID record 1 : primary
09-30 06:37:31.148  5927  5943 D bt_bte_conf:   vendorId            = 000f
09-30 06:37:31.148  5927  5943 D bt_bte_conf:   vendorIdSource      = 0001
09-30 06:37:31.149  5927  5943 D bt_bte_conf:   product             = 1200
09-30 06:37:31.149  5927  5943 D bt_bte_conf:   version             = 1436
09-30 06:37:31.149  5927  5943 D bt_bte_conf:   clientExecutableURL = 
09-30 06:37:31.149  5927  5943 D bt_bte_conf:   serviceDescription  = 
09-30 06:37:31.149  5927  5943 D bt_bte_conf:   documentationURL    = 
09-30 06:37:31.149  5927  5943 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 06:37:31.149  5927  5940 D bt_stack_manager: event_start_up_stack finished
09-30 06:37:31.150  5927  5939 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 06:37:31.150  5927  5939 D BluetoothAdapterProperties: Setting state to 15
09-30 06:37:31.150  5927  5939 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 06:37:31.150  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:31.151  5927  5939 I BluetoothAdapterState: Entering BleOnState
,09-30 06:37:31.155  5927  5947 I bt_vendor: low_power_mode_cb
,09-30 06:37:31.156  5927  5939 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 06:37:31.156  5927  5939 D BluetoothAdapterProperties: Setting state to 11
09-30 06:37:31.156  5927  5939 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-30 06:37:31.160  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:31.161  5927  5927 D HeadsetService: Received start request. Starting profile...
09-30 06:37:31.164  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:31.168  5927  5927 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 06:37:31.168  5927  5927 D HeadsetStateMachine: make
09-30 06:37:31.169  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:31.179  5927  5939 I BluetoothAdapterState: Entering PendingCommandState
,09-30 06:37:31.183  5927  5927 D HeadsetStateMachine: max_hf_connections = 1
,09-30 06:37:31.184  5927  5927 I bt_bluedroid: get_profile_interface handsfree
09-30 06:37:31.184  5927  5943 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 06:37:31.187  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:31.187  5927  5943 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-30 06:37:31.191  5927  5927 D A2dpService: Received start request. Starting profile...
09-30 06:37:31.201  5927  5927 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-30 06:37:31.202  5927  5927 I bt_bluedroid: get_profile_interface avrcp
,09-30 06:37:31.208  5927  5927 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 06:37:31.208  5927  5927 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 06:37:31.208  5927  5927 D A2dpStateMachine: make
09-30 06:37:31.210  5927  5927 I bt_bluedroid: get_profile_interface a2dp
,09-30 06:37:31.210  5927  5943 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 06:37:31.212  5927  5958 D A2dpStateMachine: Enter Disconnected: -2
,09-30 06:37:31.212  5927  5927 I BluetoothHidServiceJni: classInitNative: succeeds
,09-30 06:37:31.213  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:31.214  5927  5927 D HidService: Received start request. Starting profile...
09-30 06:37:31.214  5927  5927 I bt_bluedroid: get_profile_interface hidhost
09-30 06:37:31.215  5927  5943 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ade56d
09-30 06:37:31.215  5927  5927 D HidService: setHidService(): set to: null
09-30 06:37:31.215  5927  5943 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 06:37:31.217  5927  5927 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 06:37:31.217  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:31.218  5927  5927 D HealthService: Received start request. Starting profile...
09-30 06:37:31.218  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 06:37:31.220  5927  5927 I bt_bluedroid: get_profile_interface health
,09-30 06:37:31.221  5927  5927 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-30 06:37:31.222  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
09-30 06:37:31.222  5927  5927 D PanService: Received start request. Starting profile...
,09-30 06:37:31.222  5927  5927 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 06:37:31.222  5927  5927 I bt_bluedroid: get_profile_interface pan
09-30 06:37:31.223  5927  5943 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-30 06:37:31.226  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:31.227  5927  5927 D BluetoothMapService: Received start request. Starting profile...
09-30 06:37:31.227  5927  5927 D BluetoothMapService: start()
,09-30 06:37:31.230  5927  5927 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 06:37:31.231  5927  5927 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 06:37:31.231  5927  5927 D BluetoothMapAppObserver: createReceiver()
09-30 06:37:31.233  5927  5927 D BluetoothMapAppObserver: initObservers()
09-30 06:37:31.233  5927  5927 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 06:37:31.237  5927  5927 V SapService: SapBinder()
09-30 06:37:31.238  5927  5927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:31.238  5927  5927 D SapService: Received start request. Starting profile...
09-30 06:37:31.239  5927  5927 V SapService: start()
,09-30 06:37:31.240  5927  5927 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:31.240  5927  5927 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:31.240  5927  5927 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:31.240  5927  5927 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 06:37:31.241  5927  5927 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:31.241  5927  5927 V BluetoothAdapterState: isTurningOn()=true
,09-30 06:37:31.241  5927  5927 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:31.241  5927  5927 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:31.241  5927  5927 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:31.241  5927  5927 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:31.241  5927  5927 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:31.241  5927  5927 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:31.241  5927  5956 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isTurningOff()=false
,09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:31.242  5927  5927 V BluetoothAdapterState: isBleTurningOff()=false
09-30 06:37:31.243  5927  5927 V BluetoothAdapterState: isTurningOff()=false
09-30 06:37:31.243  5927  5927 V BluetoothAdapterState: isTurningOn()=true
09-30 06:37:31.243  5927  5927 V BluetoothAdapterState: isBleTurningOn()=false
09-30 06:37:31.243  5927  5927 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 06:37:31.243  5927  5939 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 06:37:31.243  5927  5939 D BluetoothAdapterProperties: ScanMode =  20
09-30 06:37:31.243  5927  5939 D BluetoothAdapterProperties: State =  11
09-30 06:37:31.244  5927  5939 D BluetoothAdapterProperties: Setting state to 12
09-30 06:37:31.244  5927  5939 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 06:37:31.244  5927  5939 I BluetoothAdapterState: Entering OnState
09-30 06:37:31.244  5927  5943 D BluetoothAdapterProperties: Scan Mode:21
09-30 06:37:31.245  5927  5943 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 06:37:31.245  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-30 06:37:31.245  3233  4076 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 06:37:31.248   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 06:37:31.248   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:31.248   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:31.248  5746  5759 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 06:37:31.249  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:31.249  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:31.249  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:31.249  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:31.249  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:31.249  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:31.249  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:31.249  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:31.250  3233  4076 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 06:37:31.252  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:31.253  3233  3233 D BluetoothA2dp: Proxy object connected
09-30 06:37:31.254  5746  5759 D BluetoothPan: onBluetoothStateChange on: true
09-30 06:37:31.256  3233  3245 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-30 06:37:31.256  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:31.256  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:31.256  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:31.256  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:31.256  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:31.256  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:31.256  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:31.256  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:31.257  5746  5963 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 06:37:31.257  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 06:37:31.258  5927  5927 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 06:37:31.258  5927  5927 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 06:37:31.258   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 06:37:31.259  5927  5927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 06:37:31.259  5746  5759 D BluetoothMap: onBluetoothStateChange: up=true
09-30 06:37:31.259   927   927 D BluetoothA2dp: Proxy object connected
,09-30 06:37:31.259  5746  5746 D BluetoothA2dp: Proxy object connected
09-30 06:37:31.260  5927  5927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 06:37:31.261  5746  5758 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 06:37:31.261  5927  5927 D ObexServerSockets: Succeed to create listening sockets 
09-30 06:37:31.261  5927  5927 D ObexServerSockets0: startAccept()
09-30 06:37:31.261  5927  5927 D ObexServerSockets0: prepareForNewConnect()
09-30 06:37:31.262  3233  4076 D BluetoothPan: onBluetoothStateChange on: true
09-30 06:37:31.263  5927  5927 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 06:37:31.263  5927  5927 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 06:37:31.263  5927  5965 D ObexServerSockets0: Accepting socket connection...
,09-30 06:37:31.264  5927  5966 D ObexServerSockets0: Accepting socket connection...
09-30 06:37:31.264  3233  3233 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 06:37:31.264  3233  3233 D PanProfile: Bluetooth service connected
09-30 06:37:31.264  3233  3233 D BluetoothInputDevice: Proxy object connected
09-30 06:37:31.264  3233  3233 D HidProfile: Bluetooth service connected
09-30 06:37:31.264  3866  3883 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:31.265  5746  5758 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 06:37:31.265  3233  3247 D BluetoothMap: onBluetoothStateChange: up=true
09-30 06:37:31.266  3233  3233 D BluetoothMap: Proxy object connected
09-30 06:37:31.266  3233  3245 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 06:37:31.267  3233  3233 D MapProfile: Bluetooth service connected
09-30 06:37:31.267  3233  3233 D BluetoothMap: getConnectedDevices()
09-30 06:37:31.267  5746  5746 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 06:37:31.267  5746  5746 D PanProfile: Bluetooth service connected
09-30 06:37:31.267  5746  5746 D BluetoothInputDevice: Proxy object connected
09-30 06:37:31.267  5746  5746 D HidProfile: Bluetooth service connected
09-30 06:37:31.267   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 06:37:31.268  5693  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 06:37:31.269  5927  5927 D BluetoothMapService: onReceive
09-30 06:37:31.269  5927  5927 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 06:37:31.269  5927  5927 D BluetoothMapService: STATE_ON
,09-30 06:37:31.270  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:31.270  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:31.271  5746  5746 D BluetoothMap: Proxy object connected
09-30 06:37:31.271  5746  5746 D MapProfile: Bluetooth service connected
09-30 06:37:31.271  5746  5746 D BluetoothMap: getConnectedDevices()
09-30 06:37:31.272  5927  5968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 06:37:31.274  5927  5968 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 06:37:31.274  5927  5968 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-30 06:37:31.276  5746  5746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 06:37:31.282  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 06:37:31.282  5746  5746 D DockEventReceiver: finishStartingService: stopping service
,09-30 06:37:31.285  5746  5746 D BluetoothPbap: Proxy object connected
09-30 06:37:31.285  5746  5746 D PbapServerProfile: Bluetooth service connected
,09-30 06:37:31.290  3233  3233 D BluetoothPbap: Proxy object connected
,09-30 06:37:31.290  3233  3233 D PbapServerProfile: Bluetooth service connected
,09-30 06:37:31.295  5927  5972 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 06:37:31.303  5927  5927 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 06:37:31.303  5927  5927 D ObexServerSockets0: prepareForNewConnect()
,09-30 06:37:31.308  5927  5976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 06:37:31.309  5927  5976 I BtOppRfcommListener: Accept thread started.
,09-30 06:37:31.350   927   927 D BluetoothHeadset: Proxy object connected
,09-30 06:37:31.350   927   927 D BluetoothHeadset: Proxy object connected
09-30 06:37:31.350   927   927 D BluetoothHeadset: Proxy object connected
09-30 06:37:31.350  5746  5963 D BluetoothHeadset: Proxy object connected
09-30 06:37:31.351  3233  4076 D BluetoothHeadset: Proxy object connected
09-30 06:37:31.351  3233  3233 D HeadsetProfile: Bluetooth service connected
09-30 06:37:31.351  3866  4095 D BluetoothHeadset: Proxy object connected
09-30 06:37:31.352  5746  5746 D HeadsetProfile: Bluetooth service connected
,09-30 06:37:31.364  3866  3884 D BluetoothHeadset: Proxy object connected
,09-30 06:37:31.366  5746  5759 D BluetoothHeadset: Proxy object connected
09-30 06:37:31.367  3233  3245 D BluetoothHeadset: Proxy object connected
09-30 06:37:31.367  3233  3233 D HeadsetProfile: Bluetooth service connected
,09-30 06:37:31.367  5746  5746 D HeadsetProfile: Bluetooth service connected
,09-30 06:37:35.008  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:35.008  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:35.008  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:35.008  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 06:37:35.008  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:35.008  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:35.008  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:35.008  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 06:37:35.014  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 06:37:35.016  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:37:35.017  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8111499 removed from the list
09-30 06:37:35.017  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:35.017  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:35.017  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:35.018  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:35.018  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae2935e added. We now have 4 listener(s)
09-30 06:37:35.018  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:35.020   927  3885 D WifiService: setWifiEnabled: false pid=5693, uid=10077
,09-30 06:37:35.020   927  3885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 06:37:36.217   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:37.219   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:38.220   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:39.222   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:40.028  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:40.030   927  3244 D WifiService: setWifiEnabled: true pid=5693, uid=10077
09-30 06:37:40.030   927  3244 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 06:37:40.039   506   925 D SoftapController: Softap fwReload - Ok
,09-30 06:37:40.045   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:40.045   506   925 D CommandListener: Trying to bring down wlan0
09-30 06:37:40.047   506   925 D CommandListener: Clearing all IP addresses on wlan0
09-30 06:37:40.051   927  3066 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 06:37:40.224   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:37:40.723   927  3066 D wifi    : set interface wlan0 flags (UP)
,09-30 06:37:40.724   927  3066 I WifiHAL : Initializing wifi
09-30 06:37:40.724   927  3066 I WifiHAL : Creating socket
09-30 06:37:40.730   927  3066 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-30 06:37:40.730   927  3066 D wifi    : Did set static halHandle = 0x7f602c9f80
,09-30 06:37:40.730   927  3066 D wifi    : halHandle = 0x7f602c9f80, mVM = 0x7f7c94d140, mCls = 0x1592
09-30 06:37:40.730   927  3066 D wifi    : array field set
09-30 06:37:40.730   927  3066 I WifiNative-HAL: interface[0] = wlan0
09-30 06:37:40.731   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 06:37:40.733   927  5981 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547074383744
09-30 06:37:40.733   927  5981 D wifi    : waitForHalEvents called, vm = 0x7f7c94d140, obj = 0x1592, env = 0x7f71e82b40
,09-30 06:37:40.797  5982  5982 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 06:37:40.819  5982  5982 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 06:37:40.834   927  3066 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-30 06:37:40.840  5982  5982 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-30 06:37:40.840  5982  5982 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
09-30 06:37:40.845  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:40.848  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:40.860   927  3066 D WifiConfigStore: Loading config and enabling all networks 
,09-30 06:37:40.862  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:40.862  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:40.862  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:40.862  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:40.862  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:40.862  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:40.862  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:40.862  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 06:37:40.865  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 06:37:40.870  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:40.870  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:40.870  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:40.870  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:40.870  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:40.870  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 06:37:40.870  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 06:37:40.870  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 06:37:40.872  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 06:37:40.875   927  3066 D WifiConfigStore: loaded 0 passpoint configs
,09-30 06:37:40.876   927  3066 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 06:37:40.876   927  3066 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 06:37:40.877   927  3066 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-30 06:37:40.878   927  3066 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 06:37:40.878   927  3066 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 06:37:40.878   927  3066 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-30 06:37:40.878   927  3066 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-30 06:37:40.881   927  3066 D WifiNative-HAL: Setting external_sim to 1
09-30 06:37:40.881  5075  5075 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 06:37:40.881   927  3066 D wifi    : setting dfs flag to true, 0x7f611f11a0
09-30 06:37:40.882   927  3066 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 06:37:40.882   927  3066 D wifi    : setting scan oui 0x7f611f11a0
09-30 06:37:40.882   927  3066 D WifiHAL : Sending mac address OUI
,09-30 06:37:40.886   927  3066 E native  : do suspend false
,09-30 06:37:40.895   927  3066 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-30 06:37:40.895   927   927 D RttService: SCAN_AVAILABLE : 3
09-30 06:37:40.895   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 06:37:40.896   927  3183 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-30 06:37:40.897   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:40.901   927  3050 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-30 06:37:40.901   927  3050 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 06:37:40.911   927  3050 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 06:37:40.912   927  3050 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 06:37:40.917   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=304132 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-30 06:37:41.224   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 06:37:44.097  5982  5982 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:44.102  5982  5982 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:44.109  5982  5982 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:44.113  5982  5982 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:44.115  5982  5982 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 06:37:44.159   927  3066 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-30 06:37:44.160   927  3066 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 06:37:44.160   927  3066 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 06:37:44.172   927  3066 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 06:37:44.207   927  3066 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 06:37:44.209  5982  5982 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 06:37:44.655  5982  5982 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 06:37:44.692  5982  5982 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 06:37:44.694  5982  5982 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 06:37:44.705   927  3066 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 06:37:44.705   927  3066 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 06:37:44.706   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 06:37:44.725   927  3066 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 06:37:44.741   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:44.746   927  3066 D WifiStateMachine: Start Dhcp Watchdog 3
,09-30 06:37:44.752   927  5987 D DhcpClient: Receive thread started
,09-30 06:37:44.757   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 06:37:44.757   927  3066 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 06:37:44.757   927  3079 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-30 06:37:44.837   927  3066 E native  : do suspend false
,09-30 06:37:44.852   927  5986 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 06:37:44.866   927  5987 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-30 06:37:44.866   927  5986 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-30 06:37:44.868   927  5986 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 06:37:44.881   927  5987 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 06:37:44.881   927  5986 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 06:37:44.884   506   925 D CommandListener: Setting iface cfg
,09-30 06:37:44.889   927  3066 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 06:37:44.894   927  5986 D DhcpClient: Scheduling renewal in 86399s
,09-30 06:37:44.903   927  3066 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-30 06:37:44.903   927  3066 D WifiConfigStore: No blacklist allowed without epno enabled
,09-30 06:37:44.904   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-30 06:37:44.909   927  3079 D ConnectivityService: Adding iface wlan0 to network 102
,09-30 06:37:44.918   927  3066 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 06:37:44.957   927  3079 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 06:37:44.958   927  3079 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-30 06:37:44.960   927  3079 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-30 06:37:44.962   927  3079 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-30 06:37:44.963   927  3079 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-30 06:37:44.970   927  3079 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 06:37:44.974   927  3079 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-30 06:37:44.974   927  3079 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-30 06:37:44.974   927  3079 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-30 06:37:44.974   927  3079 D ConnectivityService:    accepting network in place of null
09-30 06:37:44.974   927  3066 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 06:37:44.974   927  3066 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 06:37:44.975   927  3079 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 06:37:44.998   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 06:37:45.008   927  5985 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 06:37:45.018   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 06:37:45.021   927  3079 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-30 06:37:45.021  3819  4008 W QCNEJ   : |CORE| network available: 102
09-30 06:37:45.021   927  3079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 06:37:45.022   927  3079 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-30 06:37:45.022  3819  4008 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 06:37:45.027   927   944 D Tethering: MasterInitialState.processMessage what=3
09-30 06:37:45.028  3819  4008 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 06:37:45.028  3819  4008 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-30 06:37:45.033  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:45.033  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:45.033  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:45.033  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:45.033  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:45.033  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:45.033  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:45.033  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:37:45.034  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:37:45.038  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:45.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:45.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:45.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:45.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:45.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:45.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:45.038  5693  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:37:45.040  5693  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:45.042  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 06:37:45.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:45.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:45.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:45.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:45.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:45.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:45.042  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:37:45.044  5101  5124 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 06:37:45.044  5101  5124 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 06:37:45.044  5101  5124 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 06:37:45.044  5101  5124 E SarControlService: no key has been found,reset the power
,09-30 06:37:45.044  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:45.045  5101  5138 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 06:37:45.045  5101  5138 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 06:37:45.045  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:45.045  5101  5138 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 06:37:45.045  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae2935e removed from the list
09-30 06:37:45.045  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:45.045  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:45.045  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:45.045  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-30 06:37:45.045  5126  5126 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 06:37:45.047  4019  4019 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-30 06:37:45.048  5693  5997 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-30 06:37:45.048  5693  5997 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-30 06:37:45.048  5101  5138 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 06:37:45.049  5101  5138 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 06:37:45.049  5101  5138 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 06:37:45.050  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 06:37:45.050  5126  5126 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 06:37:45.051  3952  3952 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 06:37:45.054  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@928fe30 HexData = [00000000f003000000000000ffffffff]
,09-30 06:37:45.054  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 06:37:45.054  5126  5140 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-30 06:37:45.055  3952  3952 D SystemUpdateService: onCreate
,09-30 06:37:45.057  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-30 06:37:45.057  5101  5112 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 06:37:45.060  3952  3952 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 06:37:45.062  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@928fe30 HexData = [00000000f103000000000000ffffffff]
,09-30 06:37:45.062  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 06:37:45.062  5126  5140 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-30 06:37:45.062  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 06:37:45.063  5101  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 06:37:45.074  3952  3952 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-30 06:37:45.076   927  5984 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-30 06:37:45.080  3952  5469 I iu.UploadsManager: num queued entries: 0
,09-30 06:37:45.080  3952  5469 I iu.UploadsManager: num updated entries: 0
09-30 06:37:45.081  3952  5469 I iu.SyncManager: NEXT; no task
,09-30 06:37:45.084  3952  5999 I SystemUpdateService: active receiver: enabled
,09-30 06:37:45.086  3952  3952 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 06:37:45.087  3952  3952 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 06:37:45.090  5471  5471 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 06:37:45.093  5471  5471 D SprintDMHelper: simOperator: 
09-30 06:37:45.093  5471  5471 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 06:37:45.114  3952  5999 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 06:37:45.128  3952  5999 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 06:37:45.128  3952  5999 I SystemUpdateService: now status is 0 (complete)
09-30 06:37:45.128  3952  5999 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 06:37:45.128  3952  5999 I SystemUpdateService: file has been verified
09-30 06:37:45.129  3952  5999 I SystemUpdateService: OTA package size = 21989297
,09-30 06:37:45.134  3952  5999 I SystemUpdateService: showing system update notification
,09-30 06:37:45.145  3952  3952 D SystemUpdateService: onDestroy
,09-30 06:37:45.153   927  5984 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 10:37:45 GMT], X-Android-Received-Millis=[1475231865152], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475231865101]}
,09-30 06:37:45.153   927  3079 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-30 06:37:45.153   927  3079 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-30 06:37:45.153   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 06:37:45.155   927  3079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 06:37:45.209  5075  6004 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 06:37:47.777   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 06:37:48.072  5693  6012 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-30 06:37:48.073  5693  5997 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-30 06:37:48.073  5693  6012 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 06:37:48.073  5693  5997 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-30 06:37:48.074  5693  6012 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 06:37:48.074  5693  5997 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 06:37:48.074  5693  6012 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 06:37:48.075  5693  5997 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 06:37:48.077  5693  6014 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:48.077  5693  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 06:37:48.078  5693  6012 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 06:37:48.078  5693  5997 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 06:37:48.078  5693  6015 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:48.078  5693  6015 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:37:48.080  5693  6017 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:48.080  5693  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 06:37:48.082  5693  6016 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:48.082  5693  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:37:48.082  5693  6017 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:48.082  5693  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 06:37:48.082  5693  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:37:48.082  5693  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 06:37:48.082  5693  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 06:37:48.083  5693  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 06:37:48.083  5693  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:37:48.083  5693  6017 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 06:37:48.083  5693  6017 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 06:37:48.083  5693  6017 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:37:48.084  5693  6017 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:48.084  5693  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 06:37:48.084  5693  6015 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 06:37:48.084  5693  6014 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 156, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
09-30 06:37:48.085  5693  6015 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
,09-30 06:37:48.085  5693  6014 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 156, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:48.085  5693  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 06:37:48.085  5693  6014 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
09-30 06:37:48.085  5693  6015 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:48.085  5693  6015 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 06:37:48.085  5693  6014 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 06:37:48.085  5693  6014 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:48.085  5693  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 06:37:48.086  5693  6016 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:48.086  5693  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:37:48.086  5693  6016 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:37:48.086  5693  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:37:48.086  5693  6016 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 06:37:48.086  5693  6016 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 06:37:48.087  5693  6016 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:37:48.087  5693  6016 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 06:37:48.087  5693  6016 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 06:37:48.087  5693  6016 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 06:37:48.087  5693  6016 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-30 06:37:48.087  5693  6016 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:48.087  5693  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 06:37:51.058  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-30 06:37:51.059  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-30 06:37:51.064  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ab968bd Bundle[{}]
,09-30 06:37:51.066  5693  5739 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-30 06:37:51.067  5693  5739 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-30 06:37:51.068  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-30 06:37:51.069  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-30 06:37:51.070  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-30 06:37:51.071  5693  5739 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-30 06:37:51.077  5693  5739 I System.out: Running OutgoingSocketThread
,09-30 06:37:51.079  5693  6018 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-30 06:37:51.079  5693  6018 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 06:37:52.980   927  3079 D ConnectivityService: handlePromptUnvalidated 102
,09-30 06:37:54.089  5693  6018 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-30 06:37:54.089  5693  6019 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-30 06:37:54.089  5693  6019 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 06:37:54.089  5693  6018 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-30 06:37:54.090  5693  6018 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 06:37:54.090  5693  6019 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 06:37:54.092  5693  6018 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 06:37:54.092  5693  6019 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 06:37:54.094  5693  6021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:54.094  5693  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 06:37:54.095  5693  6019 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 06:37:54.096  5693  6018 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-30 06:37:54.099  5693  6022 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:54.099  5693  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:37:54.101  5693  6024 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:54.101  5693  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:37:54.102  5693  6023 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:54.102  5693  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 06:37:54.103  5693  6024 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:54.103  5693  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:37:54.103  5693  6024 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:37:54.103  5693  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:37:54.103  5693  6024 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 06:37:54.103  5693  6024 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 06:37:54.103  5693  6024 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:37:54.104  5693  6022 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 168, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
09-30 06:37:54.104  5693  6024 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 06:37:54.104  5693  6024 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 06:37:54.104  5693  6022 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:54.104  5693  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 06:37:54.104  5693  6024 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 06:37:54.104  5693  6022 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
,09-30 06:37:54.104  5693  6024 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:54.104  5693  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 06:37:54.104  5693  6022 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 06:37:54.104  5693  6022 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:54.104  5693  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 06:37:54.105  5693  6023 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:54.105  5693  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 06:37:54.105  5693  6021 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:54.105  5693  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 06:37:54.105  5693  6023 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:37:54.105  5693  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 06:37:54.105  5693  6023 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 06:37:54.105  5693  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:37:54.105  5693  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 06:37:54.105  5693  6023 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 06:37:54.105  5693  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 06:37:54.105  5693  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 06:37:54.106  5693  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:37:54.106  5693  6021 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 06:37:54.106  5693  6021 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 06:37:54.106  5693  6021 I io.jxcore.node.IncomingSocketThread: The sending thread is done
09-30 06:37:54.106  5693  6021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 06:37:54.106  5693  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-30 06:37:54.106  5693  6023 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:37:54.106  5693  6023 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 06:37:54.106  5693  6023 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 06:37:54.106  5693  6023 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 06:37:54.107  5693  6023 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
09-30 06:37:54.107  5693  6023 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 06:37:54.107  5693  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 06:37:55.913   927  3066 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-30 06:37:57.088  5693  5739 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 180)
,09-30 06:37:57.089  5693  5739 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-30 06:37:57.089  5693  5739 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-30 06:37:57.096  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.096  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@413933f added. We now have 3 listener(s)
,09-30 06:37:57.101  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 06:37:57.101  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.101  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.101  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:57.101  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed140c added. We now have 4 listener(s)
09-30 06:37:57.101  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:57.102  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 06:37:57.106  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:37:57.112  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:37:57.112  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:57.112  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:57.112  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:57.112  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:57.112  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:57.112  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:57.112  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:37:57.114  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:57.115  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:37:57.115  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.115  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec0876a added. We now have 4 listener(s)
,09-30 06:37:57.117  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 06:37:57.118  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.118  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.118  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:57.118  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@738245b added. We now have 5 listener(s)
09-30 06:37:57.118  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:37:57.118  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:37:57.119  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:37:57.119  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 06:37:57.119  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:37:57.119  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.119  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:57.119  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:37:57.119  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.119  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.119  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@413933f removed from the list
09-30 06:37:57.119  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:37:57.119  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed140c removed from the list
09-30 06:37:57.123  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:57.124  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:57.124  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:37:57.125  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.125  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:37:57.127  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.127  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.127  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.127  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed140c not in the list
09-30 06:37:57.127  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.127  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:37:57.128  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.128  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.128  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.128  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@738245b removed from the list
09-30 06:37:57.128  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 06:37:57.128  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.128  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.129  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.129  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 06:37:57.129  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec0876a removed from the list
09-30 06:37:57.129  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.129  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75d64f8 added. We now have 3 listener(s)
,09-30 06:37:57.131  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:37:57.131  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.131  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.131  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:57.131  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@757bdd1 added. We now have 4 listener(s)
,09-30 06:37:57.131  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:37:57.132  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 06:37:57.135  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:37:57.139  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:37:57.139  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:57.139  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:57.139  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:57.139  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:57.139  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:57.139  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:57.139  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 06:37:57.141  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:37:57.141  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:37:57.141  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.141  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4aab37 added. We now have 4 listener(s)
09-30 06:37:57.143  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:37:57.143  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.143  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.143  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 06:37:57.143  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67fd8a4 added. We now have 5 listener(s)
09-30 06:37:57.143  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:57.143  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:37:57.143  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 06:37:57.143  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 06:37:57.143  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:37:57.143  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 06:37:57.144  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:57.147  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 06:37:57.147  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 06:37:57.148  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:57.151  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 06:37:57.152  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 06:37:57.152  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 06:37:57.154  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 06:37:57.154  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 06:37:57.154  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 06:37:57.155  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 06:37:57.155  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 06:37:57.155  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:37:57.157  5927  5967 D BtGatt.GattService: registerClient() - UUID=1a3fc240-8b1d-48ad-938a-0320faf397ce
09-30 06:37:57.158  5927  5943 D BtGatt.GattService: onClientRegistered() - UUID=1a3fc240-8b1d-48ad-938a-0320faf397ce, clientIf=5
09-30 06:37:57.159  5693  5703 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 06:37:57.160  5927  5937 D BtGatt.GattService: start scan with filters
,09-30 06:37:57.164  5927  5946 D BtGatt.ScanManager: handling starting scan
,09-30 06:37:57.164  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 06:37:57.164  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 06:37:57.164  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:37:57.164  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 06:37:57.164  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 06:37:57.164  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 06:37:57.164  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 06:37:57.165  5927  5946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6830626
,09-30 06:37:57.167  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 06:37:57.167  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-30 06:37:57.167  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 06:37:57.168  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 06:37:57.171  5693  5739 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 06:37:57.171  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 06:37:57.171  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 06:37:57.171  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.171  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 06:37:57.171  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.171  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 06:37:57.171  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 06:37:57.171  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 06:37:57.171  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 06:37:57.171  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 06:37:57.171  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 06:37:57.172  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:37:57.173  5927  5943 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 06:37:57.173  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.173  5927  5937 D BtGatt.GattService: stopScan() - queue size =1
,09-30 06:37:57.173  5927  5946 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 06:37:57.174  5927  5938 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 06:37:57.174  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 06:37:57.174  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 06:37:57.174  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 06:37:57.174  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:37:57.175  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 06:37:57.175  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 06:37:57.175  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-30 06:37:57.175  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 06:37:57.176  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:37:57.176  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 06:37:57.176  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 06:37:57.176  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 06:37:57.176  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 06:37:57.177  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:37:57.178  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 06:37:57.178  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:37:57.178  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 06:37:57.180  5927  5943 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 06:37:57.180  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:37:57.180  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.180  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:37:57.180  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 06:37:57.180  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:37:57.180  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.180  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:37:57.180  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.180  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.180  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75d64f8 removed from the list
,09-30 06:37:57.180  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.180  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@757bdd1 removed from the list
09-30 06:37:57.180  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:57.180  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.180  5927  5946 D BtGatt.ScanManager: Starting BLE batch scan
09-30 06:37:57.180  5927  5946 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 06:37:57.181  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 06:37:57.181  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:37:57.182  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 06:37:57.182  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.182  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.182  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@757bdd1 not in the list
09-30 06:37:57.182  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.182  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.183  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.183  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.183  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 06:37:57.183  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67fd8a4 removed from the list
09-30 06:37:57.183  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:37:57.184  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.184  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.184  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.184  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.184  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4aab37 removed from the list
09-30 06:37:57.184  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.185  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33db10 added. We now have 3 listener(s)
09-30 06:37:57.186  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:37:57.186  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.186  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.186  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:57.186  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a335609 added. We now have 4 listener(s)
09-30 06:37:57.186  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:57.187  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 06:37:57.189  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:37:57.191  5927  5943 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 06:37:57.191  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:37:57.194  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:37:57.194  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:57.194  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:57.194  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:57.194  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:57.194  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:57.194  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:57.194  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:37:57.197  5927  5943 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 06:37:57.197  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.198  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:57.199  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:37:57.199  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.199  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85dca2f added. We now have 4 listener(s)
,09-30 06:37:57.200  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:37:57.200  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.200  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.200  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 06:37:57.200  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3983c added. We now have 5 listener(s)
09-30 06:37:57.200  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:57.200  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:37:57.201  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:57.201  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:37:57.201  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 06:37:57.201  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 06:37:57.201  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:37:57.201  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 06:37:57.203  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:57.204  5927  5943 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 06:37:57.204  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.205  5927  5946 D BtGatt.ScanManager: stopping BLe Batch
,09-30 06:37:57.205  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 06:37:57.205  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 06:37:57.208  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 06:37:57.209  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 06:37:57.209  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 06:37:57.210  5927  5943 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 06:37:57.210  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.210  5927  5946 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 06:37:57.212  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 06:37:57.212  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 06:37:57.212  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 06:37:57.212  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 06:37:57.212  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 06:37:57.213  5693  5739 D BluetoothAdapter: STATE_ON
,09-30 06:37:57.215  5927  5943 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 06:37:57.215  5927  5937 D BtGatt.GattService: registerClient() - UUID=93feb384-fbe4-4e55-94ff-2d054731d7e7
09-30 06:37:57.215  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.215  5927  5943 D BtGatt.GattService: onClientRegistered() - UUID=93feb384-fbe4-4e55-94ff-2d054731d7e7, clientIf=5
,09-30 06:37:57.216  5693  5703 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 06:37:57.216  5927  5964 D BtGatt.GattService: start scan with filters
,09-30 06:37:57.218  5927  5946 D BtGatt.ScanManager: handling starting scan
09-30 06:37:57.218  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 06:37:57.218  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 06:37:57.218  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:37:57.219  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 06:37:57.219  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-30 06:37:57.219  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 06:37:57.219  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 06:37:57.222  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 06:37:57.222  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 06:37:57.222  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 06:37:57.223  5927  5943 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 06:37:57.223  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.223  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 06:37:57.223  5927  5946 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 06:37:57.226  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 06:37:57.226  5693  5739 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-30 06:37:57.226  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:37:57.226  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:37:57.226  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:37:57.226  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:37:57.227  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.227  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 06:37:57.227  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.227  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.227  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33db10 removed from the list
09-30 06:37:57.227  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.227  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a335609 removed from the list
09-30 06:37:57.227  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:57.227  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 06:37:57.228  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.228  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 06:37:57.228  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.228  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:37:57.228  5927  5943 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 06:37:57.228  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.229  5927  5946 D BtGatt.ScanManager: Starting BLE batch scan
09-30 06:37:57.229  5927  5946 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 06:37:57.229  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.229  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.229  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.230  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a335609 not in the list
09-30 06:37:57.230  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 06:37:57.230  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 06:37:57.230  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 06:37:57.230  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 06:37:57.230  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 06:37:57.231  5693  5739 D BluetoothAdapter: STATE_ON
,09-30 06:37:57.232  5927  5964 D BtGatt.GattService: stopScan() - queue size =1
09-30 06:37:57.232  5927  5938 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 06:37:57.233  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 06:37:57.233  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 06:37:57.233  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 06:37:57.233  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:37:57.233  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,09-30 06:37:57.233  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 06:37:57.233  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 06:37:57.233  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 06:37:57.234  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:37:57.234  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-30 06:37:57.235  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 06:37:57.235  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 06:37:57.235  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 06:37:57.235  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 06:37:57.237  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.237  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.237  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.237  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:37:57.237  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e3983c removed from the list
09-30 06:37:57.237  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:37:57.237  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 06:37:57.237  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:37:57.237  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.237  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.237  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.237  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.237  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85dca2f removed from the list
,09-30 06:37:57.238  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.238  5927  5943 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 06:37:57.238  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.238  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96ffc28 added. We now have 3 listener(s)
09-30 06:37:57.239  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:37:57.239  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.239  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.240  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 06:37:57.240  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@272bd41 added. We now have 4 listener(s)
09-30 06:37:57.240  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:57.240  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 06:37:57.242  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:37:57.243  5927  5943 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 06:37:57.243  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:37:57.246  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:37:57.246  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:57.246  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:57.246  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:57.246  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:57.246  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:57.246  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:57.246  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:37:57.247  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:57.247  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:37:57.247  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.248  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe6d027 added. We now have 4 listener(s)
,09-30 06:37:57.249  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:37:57.249  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.249  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.250  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:57.250  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddcb2d4 added. We now have 5 listener(s)
09-30 06:37:57.250  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 06:37:57.250  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 06:37:57.250  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 06:37:57.250  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 06:37:57.250  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 06:37:57.250  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 06:37:57.250  5927  5943 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 06:37:57.250  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.250  5927  5946 D BtGatt.ScanManager: stopping BLe Batch
09-30 06:37:57.250  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:57.252  5693  5739 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 06:37:57.252  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 06:37:57.253  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:37:57.254  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 06:37:57.255  5927  5943 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 06:37:57.255  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 06:37:57.255  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.255  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 06:37:57.256  5927  5946 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 06:37:57.259  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 06:37:57.259  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 06:37:57.259  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 06:37:57.259  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-30 06:37:57.259  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 06:37:57.260  5927  5943 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 06:37:57.260  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.260  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:37:57.261  5927  5964 D BtGatt.GattService: registerClient() - UUID=67d3c6cf-933b-40bd-95b3-e5db1625efed
09-30 06:37:57.261  5927  5943 D BtGatt.GattService: onClientRegistered() - UUID=67d3c6cf-933b-40bd-95b3-e5db1625efed, clientIf=5
09-30 06:37:57.262  5693  5704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 06:37:57.262  5927  5938 D BtGatt.GattService: start scan with filters
09-30 06:37:57.264  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 06:37:57.264  5927  5946 D BtGatt.ScanManager: handling starting scan
09-30 06:37:57.264  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 06:37:57.264  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:37:57.264  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 06:37:57.264  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 06:37:57.264  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-30 06:37:57.264  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 06:37:57.266  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 06:37:57.266  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 06:37:57.266  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 06:37:57.267  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 06:37:57.271  5927  5943 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 06:37:57.271  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.271  5927  5946 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 06:37:57.271  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 06:37:57.271  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:37:57.271  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:37:57.271  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:37:57.271  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.271  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 06:37:57.271  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.271  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.271  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96ffc28 removed from the list
,09-30 06:37:57.271  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.271  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@272bd41 removed from the list
09-30 06:37:57.271  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:57.271  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:37:57.274  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.274  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 06:37:57.274  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.274  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 06:37:57.275  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.275  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.275  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.275  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@272bd41 not in the list
09-30 06:37:57.275  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 06:37:57.275  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 06:37:57.275  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 06:37:57.275  5927  5943 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 06:37:57.275  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 06:37:57.275  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 06:37:57.275  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.275  5927  5946 D BtGatt.ScanManager: Starting BLE batch scan
09-30 06:37:57.275  5927  5946 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 06:37:57.276  5693  5739 D BluetoothAdapter: STATE_ON
09-30 06:37:57.276  5927  5967 D BtGatt.GattService: stopScan() - queue size =1
,09-30 06:37:57.277  5927  5964 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 06:37:57.277  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 06:37:57.277  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 06:37:57.277  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 06:37:57.277  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 06:37:57.277  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 06:37:57.277  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 06:37:57.277  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-30 06:37:57.277  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 06:37:57.278  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:37:57.278  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 06:37:57.278  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 06:37:57.278  5693  5739 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 06:37:57.278  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 06:37:57.279  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.279  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.279  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.279  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.280  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddcb2d4 removed from the list
,09-30 06:37:57.280  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:37:57.280  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:37:57.280  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.280  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.280  5693  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 06:37:57.280  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.280  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.280  5693  5693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 06:37:57.280  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe6d027 removed from the list
09-30 06:37:57.280  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.280  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bc2840 added. We now have 3 listener(s)
09-30 06:37:57.282  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:37:57.282  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.282  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.282  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:57.282  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0d379 added. We now have 4 listener(s)
,09-30 06:37:57.282  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:57.282  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 06:37:57.283  5927  5943 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 06:37:57.284  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.285  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:37:57.288  5927  5943 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 06:37:57.288  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:37:57.290  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:37:57.290  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:37:57.290  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:37:57.290  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:37:57.290  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:37:57.290  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:37:57.290  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:37:57.290  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:37:57.293  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:37:57.293  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:37:57.293  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 06:37:57.293  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3db9d1f added. We now have 4 listener(s)
09-30 06:37:57.294  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:37:57.294  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:37:57.294  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:37:57.294  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:37:57.295  5927  5943 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 06:37:57.295  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35b886c added. We now have 5 listener(s)
09-30 06:37:57.295  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:37:57.295  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:37:57.295  5927  5946 D BtGatt.ScanManager: stopping BLe Batch
09-30 06:37:57.295  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:57.295  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:37:57.295  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:37:57.295  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 06:37:57.295  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 06:37:57.295  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.295  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 06:37:57.295  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.295  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.295  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bc2840 removed from the list
09-30 06:37:57.295  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.295  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0d379 removed from the list
09-30 06:37:57.297  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 06:37:57.297  5693  5739 D io.jxcore.node.ConnectivityMonitor: stop
09-30 06:37:57.297  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.297  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.297  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.298  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.298  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.298  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.298  5693  5739 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0d379 not in the list
09-30 06:37:57.298  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.298  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.299  5927  5943 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 06:37:57.299  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 06:37:57.299  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 06:37:57.299  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 06:37:57.299  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 06:37:57.299  5927  5946 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 06:37:57.299  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35b886c removed from the list
,09-30 06:37:57.299  5693  5739 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 06:37:57.299  5693  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 06:37:57.299  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 06:37:57.299  5693  5739 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 06:37:57.299  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 06:37:57.300  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3db9d1f removed from the list
09-30 06:37:57.300  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-30 06:37:57.300  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-30 06:37:57.300  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-30 06:37:57.300  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:37:57.300  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-30 06:37:57.301  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 06:37:57.304  5927  5943 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 06:37:57.304  5927  5943 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 06:37:57.679  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 06:37:57.738  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 06:37:57.781  5693  5693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 06:37:59.480  5693  6025 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 06:37:59.480  5693  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:38:00.267  5693  6025 W !!      : call onHalfStreamCopied
,09-30 06:38:00.267  5693  6025 I testCopyDataAndClose: closing input stream
,09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 06:38:01.049  5693  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 06:38:02.029   927  5985 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325243, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 06:38:04.832  5693  6027 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-30 06:38:04.832  5693  6027 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:38:06.226   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 06:38:06.226   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 06:38:06.832  5693  5739 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 192. Connection data: Peer properties: [null null].
09-30 06:38:06.832  5693  5739 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:38:06.832  5693  5739 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 192, name: My test thread name)
,09-30 06:38:06.870  5693  6027 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-30 06:38:06.871  5693  6027 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-30 06:38:06.871  5693  6027 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-30 06:38:06.995  5693  6028 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 06:38:06.995  5693  6028 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 06:38:08.622  5693  6028 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 06:38:12.371  5693  6029 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 06:38:12.371  5693  6029 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:38:12.372  5693  6029 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
09-30 06:38:12.372  5693  6029 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 06:38:12.372  5693  6029 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 06:38:12.372  5693  6029 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:38:12.372  5693  6029 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 06:38:12.372  5693  6029 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 06:38:12.372  5693  6029 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 06:38:12.372  5693  6029 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 06:38:12.373  5693  6029 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 06:38:12.373  5693  6029 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 06:38:12.373  5693  6029 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-30 06:38:12.374  5693  5739 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 06:38:12.377  5693  6030 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-30 06:38:12.377  5693  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 06:38:12.378  5693  6030 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
,09-30 06:38:12.378  5693  6030 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-30 06:38:12.378  5693  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 06:38:12.378  5693  6030 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-30 06:38:12.379  5693  6030 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-30 06:38:12.379  5693  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 06:38:12.383  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-30 06:38:12.383  5693  5739 I jxcore-log: 
09-30 06:38:12.383  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG UnitTest_app: 'Number of passed tests:  84'
09-30 06:38:12.383  5693  5739 I jxcore-log: 
09-30 06:38:12.384  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-30 06:38:12.384  5693  5739 I jxcore-log: 
,09-30 06:38:12.384  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-30 06:38:12.384  5693  5739 I jxcore-log: 
09-30 06:38:12.384  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG UnitTest_app: 'Total duration:  102876'
09-30 06:38:12.384  5693  5739 I jxcore-log: 
,09-30 06:38:12.386  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-30 06:38:12.386  5693  5739 I jxcore-log: 
,09-30 06:38:12.389  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.389  5693  5739 I jxcore-log: 
09-30 06:38:12.390  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.390  5693  5739 I jxcore-log: 
09-30 06:38:12.390  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.390  5693  5739 I jxcore-log: 
,09-30 06:38:12.391  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.391  5693  5739 I jxcore-log: 
09-30 06:38:12.391  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 06:38:12.391  5693  5739 I jxcore-log: 
09-30 06:38:12.392  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 06:38:12.392  5693  5739 I jxcore-log: 
09-30 06:38:12.392  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.392  5693  5739 I jxcore-log: 
09-30 06:38:12.392  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.392  5693  5739 I jxcore-log: 
09-30 06:38:12.392  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 06:38:12.392  5693  5739 I jxcore-log: 
,09-30 06:38:12.393  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 06:38:12.393  5693  5739 I jxcore-log: 
09-30 06:38:12.393  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 06:38:12.393  5693  5739 I jxcore-log: 
09-30 06:38:12.393  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.393  5693  5739 I jxcore-log: 
09-30 06:38:12.393  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.393  5693  5739 I jxcore-log: 
09-30 06:38:12.394  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.394  5693  5739 I jxcore-log: 
,09-30 06:38:12.394  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.394  5693  5739 I jxcore-log: 
09-30 06:38:12.394  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.394  5693  5739 I jxcore-log: 
09-30 06:38:12.394  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.394  5693  5739 I jxcore-log: 
09-30 06:38:12.395  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.395  5693  5739 I jxcore-log: 
,09-30 06:38:12.395  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.395  5693  5739 I jxcore-log: 
09-30 06:38:12.395  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.395  5693  5739 I jxcore-log: 
09-30 06:38:12.395  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.395  5693  5739 I jxcore-log: 
09-30 06:38:12.396  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.396  5693  5739 I jxcore-log: 
09-30 06:38:12.396  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.396  5693  5739 I jxcore-log: 
,09-30 06:38:12.397  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.397  5693  5739 I jxcore-log: 
09-30 06:38:12.398  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.398  5693  5739 I jxcore-log: 
09-30 06:38:12.398  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.398  5693  5739 I jxcore-log: 
09-30 06:38:12.398  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.398  5693  5739 I jxcore-log: 
09-30 06:38:12.399  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.399  5693  5739 I jxcore-log: 
,09-30 06:38:12.399  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.399  5693  5739 I jxcore-log: 
09-30 06:38:12.399  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.399  5693  5739 I jxcore-log: 
09-30 06:38:12.399  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.399  5693  5739 I jxcore-log: 
09-30 06:38:12.399  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.399  5693  5739 I jxcore-log: 
,09-30 06:38:12.400  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.400  5693  5739 I jxcore-log: 
09-30 06:38:12.400  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.400  5693  5739 I jxcore-log: 
09-30 06:38:12.400  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.400  5693  5739 I jxcore-log: 
09-30 06:38:12.400  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.400  5693  5739 I jxcore-log: 
09-30 06:38:12.401  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.401  5693  5739 I jxcore-log: 
09-30 06:38:12.401  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.401  5693  5739 I jxcore-log: 
09-30 06:38:12.401  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.401  5693  5739 I jxcore-log: 
,09-30 06:38:12.401  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.401  5693  5739 I jxcore-log: 
09-30 06:38:12.401  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 06:38:12.401  5693  5739 I jxcore-log: 
09-30 06:38:12.402  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.402  5693  5739 I jxcore-log: 
09-30 06:38:12.402  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 06:38:12.402  5693  5739 I jxcore-log: 
09-30 06:38:12.402  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.402  5693  5739 I jxcore-log: 
09-30 06:38:12.402  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.402  5693  5739 I jxcore-log: 
09-30 06:38:12.403  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.403  5693  5739 I jxcore-log: 
09-30 06:38:12.403  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.403  5693  5739 I jxcore-log: 
09-30 06:38:12.403  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.403  5693  5739 I jxcore-log: 
09-30 06:38:12.403  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:38:12.403  5693  5739 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,09-30 06:38:12.403  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.403  5693  5739 I jxcore-log: 
09-30 06:38:12.404  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.404  5693  5739 I jxcore-log: 
09-30 06:38:12.404  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 06:38:12.404  5693  5739 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-30 06:38:12.404  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:12.404  5693  5739 I jxcore-log: 
,09-30 06:38:12.404  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 06:38:12.404  5693  5739 I jxcore-log: 
09-30 06:38:12.405  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 06:38:12.405  5693  5739 I jxcore-log: 
09-30 06:38:12.405  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 06:38:12.405  5693  5739 I jxcore-log: 
09-30 06:38:12.409  5693  5693 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-30 06:38:12.410  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-30 06:38:12.410  5693  5739 I jxcore-log: 
,09-30 06:38:12.410  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - WARN testUtils: 'myNameCallback not set!'
09-30 06:38:12.410  5693  5739 I jxcore-log: 
09-30 06:38:12.412  5693  5739 I jxcore-log: 2016-09-30 10:38:12 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-30 06:38:12.412  5693  5739 I jxcore-log: 
,09-30 06:38:14.382  5693  5739 I jxcore-log: 2016-09-30 10:38:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-30 06:38:14.382  5693  5739 I jxcore-log: 
,09-30 06:38:14.706  5693  5739 I jxcore-log: 2016-09-30 10:38:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-30 06:38:14.706  5693  5739 I jxcore-log: 
,09-30 06:38:14.721  5693  5739 I jxcore-log: 2016-09-30 10:38:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-30 06:38:14.721  5693  5739 I jxcore-log: 
,09-30 06:38:15.795  5693  5739 I jxcore-log: 2016-09-30 10:38:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-30 06:38:15.795  5693  5739 I jxcore-log: 
,09-30 06:38:15.957  5693  5739 I jxcore-log: 2016-09-30 10:38:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-30 06:38:15.957  5693  5739 I jxcore-log: 
,09-30 06:38:15.961  5693  5739 I jxcore-log: 2016-09-30 10:38:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-30 06:38:15.961  5693  5739 I jxcore-log: 
,09-30 06:38:15.966  5693  5739 I jxcore-log: 2016-09-30 10:38:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-30 06:38:15.966  5693  5739 I jxcore-log: 
,09-30 06:38:16.495  5693  5739 I jxcore-log: 2016-09-30 10:38:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-30 06:38:16.495  5693  5739 I jxcore-log: 
,09-30 06:38:16.546  5693  5739 I jxcore-log: 2016-09-30 10:38:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-30 06:38:16.546  5693  5739 I jxcore-log: 
,09-30 06:38:16.559  5693  5739 I jxcore-log: 2016-09-30 10:38:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-30 06:38:16.559  5693  5739 I jxcore-log: 
,09-30 06:38:16.563  5693  5739 I jxcore-log: 2016-09-30 10:38:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-30 06:38:16.563  5693  5739 I jxcore-log: 
,09-30 06:38:16.836  5693  5739 I jxcore-log: 2016-09-30 10:38:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-30 06:38:16.836  5693  5739 I jxcore-log: 
,09-30 06:38:16.958  5693  5739 I jxcore-log: 2016-09-30 10:38:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-30 06:38:16.958  5693  5739 I jxcore-log: 
,09-30 06:38:17.190  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-30 06:38:17.190  5693  5739 I jxcore-log: 
,09-30 06:38:17.199  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-30 06:38:17.199  5693  5739 I jxcore-log: 
,09-30 06:38:17.203  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-30 06:38:17.203  5693  5739 I jxcore-log: 
,09-30 06:38:17.335  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-30 06:38:17.335  5693  5739 I jxcore-log: 
,09-30 06:38:17.343  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-30 06:38:17.343  5693  5739 I jxcore-log: 
,09-30 06:38:17.369  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-30 06:38:17.369  5693  5739 I jxcore-log: 
,09-30 06:38:17.402  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-30 06:38:17.402  5693  5739 I jxcore-log: 
,09-30 06:38:17.409  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-30 06:38:17.409  5693  5739 I jxcore-log: 
,09-30 06:38:17.414  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-30 06:38:17.414  5693  5739 I jxcore-log: 
,09-30 06:38:17.428  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-30 06:38:17.428  5693  5739 I jxcore-log: 
,09-30 06:38:17.431  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-30 06:38:17.431  5693  5739 I jxcore-log: 
,09-30 06:38:17.437  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-30 06:38:17.437  5693  5739 I jxcore-log: 
,09-30 06:38:17.441  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-30 06:38:17.441  5693  5739 I jxcore-log: 
,09-30 06:38:17.453  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-30 06:38:17.453  5693  5739 I jxcore-log: 
,09-30 06:38:17.471  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-30 06:38:17.471  5693  5739 I jxcore-log: 
,09-30 06:38:17.480  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-30 06:38:17.480  5693  5739 I jxcore-log: 
,09-30 06:38:17.490  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-30 06:38:17.490  5693  5739 I jxcore-log: 
,09-30 06:38:17.499  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-30 06:38:17.499  5693  5739 I jxcore-log: 
,09-30 06:38:17.511  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-30 06:38:17.511  5693  5739 I jxcore-log: 
,09-30 06:38:17.521  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-30 06:38:17.521  5693  5739 I jxcore-log: 
,09-30 06:38:17.526  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-30 06:38:17.526  5693  5739 I jxcore-log: 
,09-30 06:38:17.546  5693  5739 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-30 06:38:17.548  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - INFO testUtils: 'BLE multiple advertisement supported'
09-30 06:38:17.548  5693  5739 I jxcore-log: 
,09-30 06:38:17.650  5693  5739 I jxcore-log: 2016-09-30 10:38:17 - DEBUG CoordinatedClient: 'connected to the test server'
09-30 06:38:17.650  5693  5739 I jxcore-log: 
,09-30 06:38:18.165  5693  5739 I jxcore-log: TAP version 13
09-30 06:38:18.165  5693  5739 I jxcore-log: 
,09-30 06:38:18.205  5693  5739 I jxcore-log: # setup
09-30 06:38:18.205  5693  5739 I jxcore-log: 
,09-30 06:38:19.226  5693  5739 I jxcore-log: # calling createNativeListener directly rejects
09-30 06:38:19.226  5693  5739 I jxcore-log: 
,09-30 06:38:19.254  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:19.254  5693  5739 I jxcore-log: 
,09-30 06:38:19.258  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'listening 48005'
09-30 06:38:19.258  5693  5739 I jxcore-log: 
,09-30 06:38:19.264  5693  5739 I jxcore-log: ok 1 Should throw
09-30 06:38:19.264  5693  5739 I jxcore-log: 
,09-30 06:38:19.274  5693  5739 I jxcore-log: # teardown
09-30 06:38:19.274  5693  5739 I jxcore-log: 
,09-30 06:38:19.359  5693  5739 I jxcore-log: # setup
09-30 06:38:19.359  5693  5739 I jxcore-log: 
,09-30 06:38:19.397  5693  5739 I jxcore-log: # emits incomingConnectionState
09-30 06:38:19.397  5693  5739 I jxcore-log: 
,09-30 06:38:19.443  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:19.443  5693  5739 I jxcore-log: 
,09-30 06:38:19.447  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'listening 37451'
09-30 06:38:19.447  5693  5739 I jxcore-log: 
,09-30 06:38:19.455  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:19.455  5693  5739 I jxcore-log: 
,09-30 06:38:19.457  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:19.457  5693  5739 I jxcore-log: 
,09-30 06:38:19.467  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new mux'
09-30 06:38:19.467  5693  5739 I jxcore-log: 
,09-30 06:38:19.473  5693  5739 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-30 06:38:19.473  5693  5739 I jxcore-log: 
,09-30 06:38:19.489  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:19.489  5693  5739 I jxcore-log: 
,09-30 06:38:19.490  5693  5739 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-30 06:38:19.490  5693  5739 I jxcore-log: 
,09-30 06:38:19.497  5693  5739 I jxcore-log: # teardown
09-30 06:38:19.497  5693  5739 I jxcore-log: 
,09-30 06:38:19.531  5693  5739 I jxcore-log: # setup
09-30 06:38:19.531  5693  5739 I jxcore-log: 
,09-30 06:38:19.576  5693  5739 I jxcore-log: # emits routerPortConnectionFailed
09-30 06:38:19.576  5693  5739 I jxcore-log: 
,09-30 06:38:19.677  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:19.677  5693  5739 I jxcore-log: 
,09-30 06:38:19.682  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'listening 47867'
09-30 06:38:19.682  5693  5739 I jxcore-log: 
,09-30 06:38:19.691  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:19.691  5693  5739 I jxcore-log: 
,09-30 06:38:19.696  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:19.696  5693  5739 I jxcore-log: 
,09-30 06:38:19.697  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new mux'
09-30 06:38:19.697  5693  5739 I jxcore-log: 
,09-30 06:38:19.726  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:19.726  5693  5739 I jxcore-log: 
,09-30 06:38:19.729  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:19.729  5693  5739 I jxcore-log: 
,09-30 06:38:19.733  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: ' $c@net.js:837:7
09-30 06:38:19.733  5693  5739 I jxcore-log: $09@net.js:829:13
09-30 06:38:19.733  5693  5739 I jxcore-log: '
09-30 06:38:19.733  5693  5739 I jxcore-log: 
,09-30 06:38:19.734  5693  5739 I jxcore-log: ok 4 tried to connect to right port
09-30 06:38:19.734  5693  5739 I jxcore-log: 
09-30 06:38:19.734  5693  5739 I jxcore-log: ok 5 failed due to refused connection
09-30 06:38:19.734  5693  5739 I jxcore-log: 
,09-30 06:38:19.735  5693  5739 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-30 06:38:19.735  5693  5739 I jxcore-log: 
,09-30 06:38:19.739  5693  5739 I jxcore-log: # teardown
09-30 06:38:19.739  5693  5739 I jxcore-log: 
,09-30 06:38:19.741  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:19.741  5693  5739 I jxcore-log: 
,09-30 06:38:19.767  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'mux close'
09-30 06:38:19.767  5693  5739 I jxcore-log: 
,09-30 06:38:19.770  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:19.770  5693  5739 I jxcore-log: 
,09-30 06:38:19.779  5693  5739 I jxcore-log: # setup
09-30 06:38:19.779  5693  5739 I jxcore-log: 
,09-30 06:38:19.865  5693  5739 I jxcore-log: # native server connections all up
09-30 06:38:19.865  5693  5739 I jxcore-log: 
,09-30 06:38:19.897  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:19.897  5693  5739 I jxcore-log: 
,09-30 06:38:19.900  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'listening 38510'
09-30 06:38:19.900  5693  5739 I jxcore-log: 
,09-30 06:38:19.907  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:19.907  5693  5739 I jxcore-log: 
,09-30 06:38:19.908  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:19.908  5693  5739 I jxcore-log: 
,09-30 06:38:19.909  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new mux'
09-30 06:38:19.909  5693  5739 I jxcore-log: 
,09-30 06:38:19.937  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:19.937  5693  5739 I jxcore-log: 
,09-30 06:38:19.940  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:19.940  5693  5739 I jxcore-log: 
,09-30 06:38:19.943  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:19.943  5693  5739 I jxcore-log: 
,09-30 06:38:19.946  5693  5739 I jxcore-log: 2016-09-30 10:38:19 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:19.946  5693  5739 I jxcore-log: 
,09-30 06:38:19.971  5693  5739 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-30 06:38:19.971  5693  5739 I jxcore-log: 
,09-30 06:38:19.972  5693  5739 I jxcore-log: ok 8 Send/recvd #1 should be same
09-30 06:38:19.972  5693  5739 I jxcore-log: 
09-30 06:38:19.975  5693  5739 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-30 06:38:19.975  5693  5739 I jxcore-log: 
,09-30 06:38:19.975  5693  5739 I jxcore-log: ok 10 Send/recvd #2 should be same
09-30 06:38:19.975  5693  5739 I jxcore-log: 
,09-30 06:38:19.979  5693  5739 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-30 06:38:19.979  5693  5739 I jxcore-log: 
,09-30 06:38:19.990  5693  5739 I jxcore-log: # teardown
09-30 06:38:19.990  5693  5739 I jxcore-log: 
,09-30 06:38:20.019  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:20.019  5693  5739 I jxcore-log: 
,09-30 06:38:20.021  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:20.021  5693  5739 I jxcore-log: 
,09-30 06:38:20.023  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'mux close'
09-30 06:38:20.023  5693  5739 I jxcore-log: 
,09-30 06:38:20.027  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:20.027  5693  5739 I jxcore-log: 
,09-30 06:38:20.038  5693  5739 I jxcore-log: # setup
09-30 06:38:20.038  5693  5739 I jxcore-log: 
,09-30 06:38:20.078  5693  5739 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-30 06:38:20.078  5693  5739 I jxcore-log: 
,09-30 06:38:20.133  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:20.133  5693  5739 I jxcore-log: 
,09-30 06:38:20.138  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'listening 38633'
09-30 06:38:20.138  5693  5739 I jxcore-log: 
,09-30 06:38:20.146  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:20.146  5693  5739 I jxcore-log: 
,09-30 06:38:20.148  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:20.148  5693  5739 I jxcore-log: 
,09-30 06:38:20.153  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new mux'
09-30 06:38:20.153  5693  5739 I jxcore-log: 
,09-30 06:38:20.164  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:20.164  5693  5739 I jxcore-log: 
,09-30 06:38:20.168  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:20.168  5693  5739 I jxcore-log: 
,09-30 06:38:20.180  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:20.180  5693  5739 I jxcore-log: 
,09-30 06:38:20.193  5693  5739 I jxcore-log: ok 12 socket shouldn't close until after stream
09-30 06:38:20.193  5693  5739 I jxcore-log: 
,09-30 06:38:20.194  5693  5739 I jxcore-log: ok 13 incoming remains open
09-30 06:38:20.194  5693  5739 I jxcore-log: 
,09-30 06:38:20.200  5693  5739 I jxcore-log: # teardown
09-30 06:38:20.200  5693  5739 I jxcore-log: 
,09-30 06:38:20.246  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'mux close'
09-30 06:38:20.246  5693  5739 I jxcore-log: 
,09-30 06:38:20.250  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:20.250  5693  5739 I jxcore-log: 
,09-30 06:38:20.257  5693  5739 I jxcore-log: # setup
09-30 06:38:20.257  5693  5739 I jxcore-log: 
,09-30 06:38:20.359  5693  5739 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-30 06:38:20.359  5693  5739 I jxcore-log: 
,09-30 06:38:20.390  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:20.390  5693  5739 I jxcore-log: 
,09-30 06:38:20.394  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'listening 44330'
09-30 06:38:20.394  5693  5739 I jxcore-log: 
,09-30 06:38:20.400  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:20.400  5693  5739 I jxcore-log: 
,09-30 06:38:20.402  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:20.402  5693  5739 I jxcore-log: 
,09-30 06:38:20.403  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new mux'
09-30 06:38:20.403  5693  5739 I jxcore-log: 
,09-30 06:38:20.414  5693  5739 I jxcore-log: ok 14 we should not have gotten an error
09-30 06:38:20.414  5693  5739 I jxcore-log: 
,09-30 06:38:20.419  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:20.419  5693  5739 I jxcore-log: 
,09-30 06:38:20.423  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:20.423  5693  5739 I jxcore-log: 
,09-30 06:38:20.432  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:20.432  5693  5739 I jxcore-log: 
,09-30 06:38:20.434  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:20.434  5693  5739 I jxcore-log: 
,09-30 06:38:20.441  5693  5739 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-30 06:38:20.441  5693  5739 I jxcore-log: 
,09-30 06:38:20.442  5693  5739 I jxcore-log: ok 16 incoming is cleaned up
09-30 06:38:20.442  5693  5739 I jxcore-log: 
,09-30 06:38:20.446  5693  5739 I jxcore-log: # teardown
09-30 06:38:20.446  5693  5739 I jxcore-log: 
,09-30 06:38:20.511  5693  5739 I jxcore-log: # setup
09-30 06:38:20.511  5693  5739 I jxcore-log: 
,09-30 06:38:20.558  5693  5739 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-30 06:38:20.558  5693  5739 I jxcore-log: 
,09-30 06:38:20.604  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:20.604  5693  5739 I jxcore-log: 
,09-30 06:38:20.607  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'listening 44572'
09-30 06:38:20.607  5693  5739 I jxcore-log: 
,09-30 06:38:20.614  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:20.614  5693  5739 I jxcore-log: 
,09-30 06:38:20.616  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:20.616  5693  5739 I jxcore-log: 
,09-30 06:38:20.619  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new mux'
09-30 06:38:20.619  5693  5739 I jxcore-log: 
,09-30 06:38:20.629  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:20.629  5693  5739 I jxcore-log: 
,09-30 06:38:20.631  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:20.631  5693  5739 I jxcore-log: 
,09-30 06:38:20.643  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:20.643  5693  5739 I jxcore-log: 
,09-30 06:38:20.651  5693  5739 I jxcore-log: ok 17 stream was closed
09-30 06:38:20.651  5693  5739 I jxcore-log: 
,09-30 06:38:20.651  5693  5739 I jxcore-log: ok 18 incoming should survive
09-30 06:38:20.651  5693  5739 I jxcore-log: 
09-30 06:38:20.651  5693  5739 I jxcore-log: ok 19 mux should have no streams
09-30 06:38:20.651  5693  5739 I jxcore-log: 
,09-30 06:38:20.657  5693  5739 I jxcore-log: # teardown
09-30 06:38:20.657  5693  5739 I jxcore-log: 
,09-30 06:38:20.722  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'mux close'
09-30 06:38:20.722  5693  5739 I jxcore-log: 
,09-30 06:38:20.737  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:20.737  5693  5739 I jxcore-log: 
,09-30 06:38:20.748  5693  5739 I jxcore-log: # setup
09-30 06:38:20.748  5693  5739 I jxcore-log: 
,09-30 06:38:20.819  5693  5739 I jxcore-log: # native server - closing the whole server cleans everything up
09-30 06:38:20.819  5693  5739 I jxcore-log: 
,09-30 06:38:20.872  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:20.872  5693  5739 I jxcore-log: 
,09-30 06:38:20.880  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'listening 38383'
09-30 06:38:20.880  5693  5739 I jxcore-log: 
,09-30 06:38:20.888  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:20.888  5693  5739 I jxcore-log: 
,09-30 06:38:20.890  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:20.890  5693  5739 I jxcore-log: 
,09-30 06:38:20.891  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new mux'
09-30 06:38:20.891  5693  5739 I jxcore-log: 
,09-30 06:38:20.902  5693  5739 I jxcore-log: ok 20 we should not have gotten an error
09-30 06:38:20.902  5693  5739 I jxcore-log: 
,09-30 06:38:20.908  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:20.908  5693  5739 I jxcore-log: 
,09-30 06:38:20.912  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:20.912  5693  5739 I jxcore-log: 
,09-30 06:38:20.922  5693  5739 I jxcore-log: ok 21 Buffers are identical
09-30 06:38:20.922  5693  5739 I jxcore-log: 
,09-30 06:38:20.924  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:20.924  5693  5739 I jxcore-log: 
,09-30 06:38:20.927  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'mux close'
09-30 06:38:20.927  5693  5739 I jxcore-log: 
,09-30 06:38:20.930  5693  5739 I jxcore-log: ok 22 native server is nulled out
09-30 06:38:20.930  5693  5739 I jxcore-log: 
,09-30 06:38:20.930  5693  5739 I jxcore-log: ok 23 native server should be closed
09-30 06:38:20.930  5693  5739 I jxcore-log: 
09-30 06:38:20.931  5693  5739 I jxcore-log: ok 24 incoming has been removed
09-30 06:38:20.931  5693  5739 I jxcore-log: 
09-30 06:38:20.931  5693  5739 I jxcore-log: ok 25 Incoming should be done
09-30 06:38:20.931  5693  5739 I jxcore-log: 
,09-30 06:38:20.932  5693  5739 I jxcore-log: ok 26 The mux object should be closed
09-30 06:38:20.932  5693  5739 I jxcore-log: 
,09-30 06:38:20.932  5693  5739 I jxcore-log: ok 27 The mux stream should be closed
09-30 06:38:20.932  5693  5739 I jxcore-log: 
09-30 06:38:20.933  5693  5739 I jxcore-log: 2016-09-30 10:38:20 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:20.933  5693  5739 I jxcore-log: 
,09-30 06:38:20.946  5693  5739 I jxcore-log: # teardown
09-30 06:38:20.946  5693  5739 I jxcore-log: 
,09-30 06:38:21.003  5693  5739 I jxcore-log: # setup
09-30 06:38:21.003  5693  5739 I jxcore-log: 
,09-30 06:38:21.034  5693  5739 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-30 06:38:21.034  5693  5739 I jxcore-log: 
,09-30 06:38:21.092  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:21.092  5693  5739 I jxcore-log: 
,09-30 06:38:21.097  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'listening 48894'
09-30 06:38:21.097  5693  5739 I jxcore-log: 
,09-30 06:38:21.129  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.129  5693  5739 I jxcore-log: 
,09-30 06:38:21.130  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.130  5693  5739 I jxcore-log: 
09-30 06:38:21.131  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.131  5693  5739 I jxcore-log: 
,09-30 06:38:21.134  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.134  5693  5739 I jxcore-log: 
,09-30 06:38:21.135  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.135  5693  5739 I jxcore-log: 
,09-30 06:38:21.136  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.136  5693  5739 I jxcore-log: 
,09-30 06:38:21.139  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.139  5693  5739 I jxcore-log: 
09-30 06:38:21.140  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.140  5693  5739 I jxcore-log: 
,09-30 06:38:21.141  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.141  5693  5739 I jxcore-log: 
,09-30 06:38:21.144  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.144  5693  5739 I jxcore-log: 
,09-30 06:38:21.145  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.145  5693  5739 I jxcore-log: 
,09-30 06:38:21.146  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.146  5693  5739 I jxcore-log: 
,09-30 06:38:21.149  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.149  5693  5739 I jxcore-log: 
,09-30 06:38:21.150  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.150  5693  5739 I jxcore-log: 
,09-30 06:38:21.153  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.153  5693  5739 I jxcore-log: 
,09-30 06:38:21.162  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.162  5693  5739 I jxcore-log: 
,09-30 06:38:21.163  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.163  5693  5739 I jxcore-log: 
,09-30 06:38:21.164  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.164  5693  5739 I jxcore-log: 
,09-30 06:38:21.166  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.166  5693  5739 I jxcore-log: 
,09-30 06:38:21.166  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.166  5693  5739 I jxcore-log: 
,09-30 06:38:21.167  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.167  5693  5739 I jxcore-log: 
,09-30 06:38:21.168  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.168  5693  5739 I jxcore-log: 
,09-30 06:38:21.168  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.168  5693  5739 I jxcore-log: 
,09-30 06:38:21.169  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.169  5693  5739 I jxcore-log: 
,09-30 06:38:21.170  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.170  5693  5739 I jxcore-log: 
,09-30 06:38:21.171  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.171  5693  5739 I jxcore-log: 
,09-30 06:38:21.171  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.171  5693  5739 I jxcore-log: 
,09-30 06:38:21.172  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:21.172  5693  5739 I jxcore-log: 
,09-30 06:38:21.173  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:21.173  5693  5739 I jxcore-log: 
,09-30 06:38:21.173  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new mux'
09-30 06:38:21.173  5693  5739 I jxcore-log: 
,09-30 06:38:21.226   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:21.229  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.229  5693  5739 I jxcore-log: 
,09-30 06:38:21.231  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.231  5693  5739 I jxcore-log: 
,09-30 06:38:21.232  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.232  5693  5739 I jxcore-log: 
,09-30 06:38:21.233  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.233  5693  5739 I jxcore-log: 
,09-30 06:38:21.234  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.234  5693  5739 I jxcore-log: 
,09-30 06:38:21.235  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.235  5693  5739 I jxcore-log: 
,09-30 06:38:21.236  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.236  5693  5739 I jxcore-log: 
09-30 06:38:21.237  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.237  5693  5739 I jxcore-log: 
,09-30 06:38:21.239  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.239  5693  5739 I jxcore-log: 
,09-30 06:38:21.240  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.240  5693  5739 I jxcore-log: 
,09-30 06:38:21.241  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.241  5693  5739 I jxcore-log: 
09-30 06:38:21.242  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.242  5693  5739 I jxcore-log: 
09-30 06:38:21.242  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.242  5693  5739 I jxcore-log: 
,09-30 06:38:21.243  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.243  5693  5739 I jxcore-log: 
09-30 06:38:21.244  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.244  5693  5739 I jxcore-log: 
09-30 06:38:21.245  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.245  5693  5739 I jxcore-log: 
,09-30 06:38:21.246  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.246  5693  5739 I jxcore-log: 
,09-30 06:38:21.247  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.247  5693  5739 I jxcore-log: 
09-30 06:38:21.248  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.248  5693  5739 I jxcore-log: 
,09-30 06:38:21.249  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.249  5693  5739 I jxcore-log: 
09-30 06:38:21.250  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.250  5693  5739 I jxcore-log: 
,09-30 06:38:21.250  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.250  5693  5739 I jxcore-log: 
09-30 06:38:21.251  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.251  5693  5739 I jxcore-log: 
,09-30 06:38:21.252  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.252  5693  5739 I jxcore-log: 
,09-30 06:38:21.253  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.253  5693  5739 I jxcore-log: 
,09-30 06:38:21.254  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.254  5693  5739 I jxcore-log: 
09-30 06:38:21.255  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.255  5693  5739 I jxcore-log: 
,09-30 06:38:21.256  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.256  5693  5739 I jxcore-log: 
09-30 06:38:21.256  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.256  5693  5739 I jxcore-log: 
09-30 06:38:21.257  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.257  5693  5739 I jxcore-log: 
,09-30 06:38:21.257  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.257  5693  5739 I jxcore-log: 
09-30 06:38:21.258  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.258  5693  5739 I jxcore-log: 
,09-30 06:38:21.259  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.259  5693  5739 I jxcore-log: 
,09-30 06:38:21.260  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.260  5693  5739 I jxcore-log: 
09-30 06:38:21.261  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.261  5693  5739 I jxcore-log: 
,09-30 06:38:21.262  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.262  5693  5739 I jxcore-log: 
09-30 06:38:21.262  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.262  5693  5739 I jxcore-log: 
,09-30 06:38:21.263  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.263  5693  5739 I jxcore-log: 
09-30 06:38:21.264  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.264  5693  5739 I jxcore-log: 
,09-30 06:38:21.265  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.265  5693  5739 I jxcore-log: 
09-30 06:38:21.266  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.266  5693  5739 I jxcore-log: 
,09-30 06:38:21.267  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.267  5693  5739 I jxcore-log: 
,09-30 06:38:21.267  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.267  5693  5739 I jxcore-log: 
09-30 06:38:21.268  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.268  5693  5739 I jxcore-log: 
,09-30 06:38:21.269  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.269  5693  5739 I jxcore-log: 
09-30 06:38:21.270  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.270  5693  5739 I jxcore-log: 
09-30 06:38:21.270  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.270  5693  5739 I jxcore-log: 
,09-30 06:38:21.271  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.271  5693  5739 I jxcore-log: 
,09-30 06:38:21.277  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.277  5693  5739 I jxcore-log: 
,09-30 06:38:21.279  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.279  5693  5739 I jxcore-log: 
,09-30 06:38:21.280  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.280  5693  5739 I jxcore-log: 
,09-30 06:38:21.281  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.281  5693  5739 I jxcore-log: 
09-30 06:38:21.282  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.282  5693  5739 I jxcore-log: 
,09-30 06:38:21.282  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.282  5693  5739 I jxcore-log: 
09-30 06:38:21.283  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.283  5693  5739 I jxcore-log: 
,09-30 06:38:21.284  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.284  5693  5739 I jxcore-log: 
,09-30 06:38:21.285  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.285  5693  5739 I jxcore-log: 
09-30 06:38:21.286  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.286  5693  5739 I jxcore-log: 
,09-30 06:38:21.287  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.287  5693  5739 I jxcore-log: 
09-30 06:38:21.287  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.287  5693  5739 I jxcore-log: 
09-30 06:38:21.288  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.288  5693  5739 I jxcore-log: 
,09-30 06:38:21.289  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.289  5693  5739 I jxcore-log: 
09-30 06:38:21.289  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.289  5693  5739 I jxcore-log: 
,09-30 06:38:21.290  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.290  5693  5739 I jxcore-log: 
,09-30 06:38:21.291  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.291  5693  5739 I jxcore-log: 
09-30 06:38:21.291  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.291  5693  5739 I jxcore-log: 
,09-30 06:38:21.292  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.292  5693  5739 I jxcore-log: 
,09-30 06:38:21.293  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.293  5693  5739 I jxcore-log: 
09-30 06:38:21.293  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.293  5693  5739 I jxcore-log: 
,09-30 06:38:21.294  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.294  5693  5739 I jxcore-log: 
,09-30 06:38:21.294  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.294  5693  5739 I jxcore-log: 
,09-30 06:38:21.295  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.295  5693  5739 I jxcore-log: 
09-30 06:38:21.296  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.296  5693  5739 I jxcore-log: 
,09-30 06:38:21.297  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.297  5693  5739 I jxcore-log: 
09-30 06:38:21.297  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.297  5693  5739 I jxcore-log: 
,09-30 06:38:21.298  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.298  5693  5739 I jxcore-log: 
09-30 06:38:21.299  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.299  5693  5739 I jxcore-log: 
,09-30 06:38:21.299  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.299  5693  5739 I jxcore-log: 
09-30 06:38:21.300  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:21.300  5693  5739 I jxcore-log: 
09-30 06:38:21.300  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:21.300  5693  5739 I jxcore-log: 
,09-30 06:38:21.344  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.344  5693  5739 I jxcore-log: 
,09-30 06:38:21.345  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.345  5693  5739 I jxcore-log: 
,09-30 06:38:21.346  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.346  5693  5739 I jxcore-log: 
09-30 06:38:21.347  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.347  5693  5739 I jxcore-log: 
,09-30 06:38:21.347  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.347  5693  5739 I jxcore-log: 
09-30 06:38:21.348  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.348  5693  5739 I jxcore-log: 
,09-30 06:38:21.349  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.349  5693  5739 I jxcore-log: 
09-30 06:38:21.349  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.349  5693  5739 I jxcore-log: 
,09-30 06:38:21.349  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.349  5693  5739 I jxcore-log: 
09-30 06:38:21.350  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.350  5693  5739 I jxcore-log: 
09-30 06:38:21.350  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.350  5693  5739 I jxcore-log: 
09-30 06:38:21.351  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.351  5693  5739 I jxcore-log: 
,09-30 06:38:21.351  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.351  5693  5739 I jxcore-log: 
09-30 06:38:21.351  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.351  5693  5739 I jxcore-log: 
,09-30 06:38:21.352  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.352  5693  5739 I jxcore-log: 
,09-30 06:38:21.353  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.353  5693  5739 I jxcore-log: 
09-30 06:38:21.353  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.353  5693  5739 I jxcore-log: 
09-30 06:38:21.354  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.354  5693  5739 I jxcore-log: 
,09-30 06:38:21.354  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.354  5693  5739 I jxcore-log: 
09-30 06:38:21.355  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.355  5693  5739 I jxcore-log: 
09-30 06:38:21.355  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.355  5693  5739 I jxcore-log: 
09-30 06:38:21.355  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.355  5693  5739 I jxcore-log: 
,09-30 06:38:21.356  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.356  5693  5739 I jxcore-log: 
09-30 06:38:21.356  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.356  5693  5739 I jxcore-log: 
,09-30 06:38:21.357  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.357  5693  5739 I jxcore-log: 
09-30 06:38:21.357  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.357  5693  5739 I jxcore-log: 
09-30 06:38:21.358  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.358  5693  5739 I jxcore-log: 
,09-30 06:38:21.358  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.358  5693  5739 I jxcore-log: 
09-30 06:38:21.359  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.359  5693  5739 I jxcore-log: 
,09-30 06:38:21.359  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.359  5693  5739 I jxcore-log: 
09-30 06:38:21.360  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.360  5693  5739 I jxcore-log: 
09-30 06:38:21.360  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.360  5693  5739 I jxcore-log: 
,09-30 06:38:21.360  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.360  5693  5739 I jxcore-log: 
09-30 06:38:21.361  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.361  5693  5739 I jxcore-log: 
09-30 06:38:21.361  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.361  5693  5739 I jxcore-log: 
,09-30 06:38:21.362  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.362  5693  5739 I jxcore-log: 
09-30 06:38:21.362  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.362  5693  5739 I jxcore-log: 
09-30 06:38:21.363  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.363  5693  5739 I jxcore-log: 
,09-30 06:38:21.363  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.363  5693  5739 I jxcore-log: 
09-30 06:38:21.363  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.363  5693  5739 I jxcore-log: 
09-30 06:38:21.364  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.364  5693  5739 I jxcore-log: 
,09-30 06:38:21.364  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.364  5693  5739 I jxcore-log: 
09-30 06:38:21.364  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.364  5693  5739 I jxcore-log: 
09-30 06:38:21.365  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.365  5693  5739 I jxcore-log: 
,09-30 06:38:21.366  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.366  5693  5739 I jxcore-log: 
,09-30 06:38:21.367  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.367  5693  5739 I jxcore-log: 
,09-30 06:38:21.369  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.369  5693  5739 I jxcore-log: 
,09-30 06:38:21.370  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.370  5693  5739 I jxcore-log: 
09-30 06:38:21.371  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:21.371  5693  5739 I jxcore-log: 
,09-30 06:38:21.371  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'mux close'
09-30 06:38:21.371  5693  5739 I jxcore-log: 
,09-30 06:38:21.373  5693  5739 I jxcore-log: ok 28 native server is nulled out
09-30 06:38:21.373  5693  5739 I jxcore-log: 
,09-30 06:38:21.373  5693  5739 I jxcore-log: ok 29 native server should be closed
09-30 06:38:21.373  5693  5739 I jxcore-log: 
09-30 06:38:21.374  5693  5739 I jxcore-log: ok 30 incoming has been removed
09-30 06:38:21.374  5693  5739 I jxcore-log: 
09-30 06:38:21.374  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.374  5693  5739 I jxcore-log: 
,09-30 06:38:21.375  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.375  5693  5739 I jxcore-log: 
09-30 06:38:21.375  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.375  5693  5739 I jxcore-log: 
09-30 06:38:21.375  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.375  5693  5739 I jxcore-log: 
,09-30 06:38:21.376  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.376  5693  5739 I jxcore-log: 
09-30 06:38:21.376  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.376  5693  5739 I jxcore-log: 
09-30 06:38:21.376  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.376  5693  5739 I jxcore-log: 
,09-30 06:38:21.376  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.376  5693  5739 I jxcore-log: 
09-30 06:38:21.377  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.377  5693  5739 I jxcore-log: 
,09-30 06:38:21.377  5693  5739 I jxcore-log: 2016-09-30 10:38:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:21.377  5693  5739 I jxcore-log: 
,09-30 06:38:21.449  5693  5739 I jxcore-log: # teardown
09-30 06:38:21.449  5693  5739 I jxcore-log: 
,09-30 06:38:21.526  5693  5739 I jxcore-log: # setup
09-30 06:38:21.526  5693  5739 I jxcore-log: 
,09-30 06:38:22.227   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:22.609   927  5985 D NetlinkSocketObserver: NeighborEvent{elapsedMs=345823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 06:38:23.229   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:23.291  5693  5739 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-30 06:38:23.291  5693  5739 I jxcore-log: 
,09-30 06:38:23.327  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:23.327  5693  5739 I jxcore-log: 
,09-30 06:38:23.333  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'listening 47444'
09-30 06:38:23.333  5693  5739 I jxcore-log: 
,09-30 06:38:23.345  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:23.345  5693  5739 I jxcore-log: 
,09-30 06:38:23.347  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:23.347  5693  5739 I jxcore-log: 
,09-30 06:38:23.350  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'new mux'
09-30 06:38:23.350  5693  5739 I jxcore-log: 
,09-30 06:38:23.358  5693  5739 I jxcore-log: ok 31 we should not have gotten an error
09-30 06:38:23.358  5693  5739 I jxcore-log: 
,09-30 06:38:23.362  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:23.362  5693  5739 I jxcore-log: 
,09-30 06:38:23.364  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:23.364  5693  5739 I jxcore-log: 
,09-30 06:38:23.371  5693  5739 I jxcore-log: ok 32 Buffers are identical
09-30 06:38:23.371  5693  5739 I jxcore-log: 
,09-30 06:38:23.372  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:23.372  5693  5739 I jxcore-log: 
,09-30 06:38:23.374  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'mux close'
09-30 06:38:23.374  5693  5739 I jxcore-log: 
,09-30 06:38:23.384  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:23.384  5693  5739 I jxcore-log: 
,09-30 06:38:23.385  5693  5739 I jxcore-log: ok 33 server should be fine
09-30 06:38:23.385  5693  5739 I jxcore-log: 
09-30 06:38:23.385  5693  5739 I jxcore-log: ok 34 server should be open
09-30 06:38:23.385  5693  5739 I jxcore-log: 
,09-30 06:38:23.386  5693  5739 I jxcore-log: ok 35 incoming has been removed
09-30 06:38:23.386  5693  5739 I jxcore-log: 
09-30 06:38:23.386  5693  5739 I jxcore-log: ok 36 The mux object should be closed
09-30 06:38:23.386  5693  5739 I jxcore-log: 
,09-30 06:38:23.387  5693  5739 I jxcore-log: ok 37 The mux stream should be closed
09-30 06:38:23.387  5693  5739 I jxcore-log: 
,09-30 06:38:23.392  5693  5739 I jxcore-log: # teardown
09-30 06:38:23.392  5693  5739 I jxcore-log: 
,09-30 06:38:23.429  5693  5739 I jxcore-log: # setup
09-30 06:38:23.429  5693  5739 I jxcore-log: 
,09-30 06:38:23.464  5693  5739 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-30 06:38:23.464  5693  5739 I jxcore-log: 
,09-30 06:38:23.494  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'creating native server'
09-30 06:38:23.494  5693  5739 I jxcore-log: 
,09-30 06:38:23.497  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'listening 46564'
09-30 06:38:23.497  5693  5739 I jxcore-log: 
,09-30 06:38:23.503  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'new incoming socket'
09-30 06:38:23.503  5693  5739 I jxcore-log: 
,09-30 06:38:23.504  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'creating incoming mux'
09-30 06:38:23.504  5693  5739 I jxcore-log: 
,09-30 06:38:23.505  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'new mux'
09-30 06:38:23.505  5693  5739 I jxcore-log: 
,09-30 06:38:23.511  5693  5739 I jxcore-log: ok 38 we should not have gotten an error
09-30 06:38:23.511  5693  5739 I jxcore-log: 
,09-30 06:38:23.514  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'new stream: '
09-30 06:38:23.514  5693  5739 I jxcore-log: 
,09-30 06:38:23.517  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'new outgoing socket'
09-30 06:38:23.517  5693  5739 I jxcore-log: 
,09-30 06:38:23.523  5693  5739 I jxcore-log: ok 39 Buffers are identical
09-30 06:38:23.523  5693  5739 I jxcore-log: 
,09-30 06:38:23.528  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'incoming socket timeout'
09-30 06:38:23.528  5693  5739 I jxcore-log: 
,09-30 06:38:23.530  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'stream close:'
09-30 06:38:23.530  5693  5739 I jxcore-log: 
,09-30 06:38:23.533  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'mux close'
09-30 06:38:23.533  5693  5739 I jxcore-log: 
,09-30 06:38:23.537  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG createNativeListener: 'incoming socket close'
09-30 06:38:23.537  5693  5739 I jxcore-log: 
,09-30 06:38:23.538  5693  5739 I jxcore-log: ok 40 server should be fine
09-30 06:38:23.538  5693  5739 I jxcore-log: 
09-30 06:38:23.538  5693  5739 I jxcore-log: ok 41 server should be open
09-30 06:38:23.538  5693  5739 I jxcore-log: 
09-30 06:38:23.538  5693  5739 I jxcore-log: ok 42 incoming has been removed
09-30 06:38:23.538  5693  5739 I jxcore-log: 
,09-30 06:38:23.539  5693  5739 I jxcore-log: ok 43 The mux object should be closed
09-30 06:38:23.539  5693  5739 I jxcore-log: 
09-30 06:38:23.539  5693  5739 I jxcore-log: ok 44 The mux stream should be closed
09-30 06:38:23.539  5693  5739 I jxcore-log: 
,09-30 06:38:23.546  5693  5739 I jxcore-log: # teardown
09-30 06:38:23.546  5693  5739 I jxcore-log: 
,09-30 06:38:23.622  5693  5739 I jxcore-log: # setup
09-30 06:38:23.622  5693  5739 I jxcore-log: 
,09-30 06:38:23.664  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-30 06:38:23.664  5693  5739 I jxcore-log: 
,09-30 06:38:23.822  5693  5739 I jxcore-log: 2016-09-30 10:38:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-30 06:38:23.822  5693  5739 I jxcore-log: 
,09-30 06:38:23.823  5693  5739 I jxcore-log: ok 45 Got right error
09-30 06:38:23.823  5693  5739 I jxcore-log: 
,09-30 06:38:23.828  5693  5739 I jxcore-log: # teardown
09-30 06:38:23.828  5693  5739 I jxcore-log: 
,09-30 06:38:23.904  5693  5739 I jxcore-log: # setup
09-30 06:38:23.904  5693  5739 I jxcore-log: 
,09-30 06:38:23.935  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-30 06:38:23.935  5693  5739 I jxcore-log: 
,09-30 06:38:24.045  5693  5739 I jxcore-log: 2016-09-30 10:38:24 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-30 06:38:24.045  5693  5739 I jxcore-log: 
,09-30 06:38:24.046  5693  5739 I jxcore-log: ok 46 Got socket hang up
09-30 06:38:24.046  5693  5739 I jxcore-log: 
,09-30 06:38:24.050  5693  5739 I jxcore-log: # teardown
09-30 06:38:24.050  5693  5739 I jxcore-log: 
,09-30 06:38:24.091  5693  5739 I jxcore-log: # setup
09-30 06:38:24.091  5693  5739 I jxcore-log: 
,09-30 06:38:24.139  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-30 06:38:24.139  5693  5739 I jxcore-log: 
,09-30 06:38:24.230   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:24.362  5693  5739 I jxcore-log: 2016-09-30 10:38:24 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-30 06:38:24.362  5693  5739 I jxcore-log: 
,09-30 06:38:24.363  5693  5739 I jxcore-log: ok 47 Got 500 as expected
09-30 06:38:24.363  5693  5739 I jxcore-log: 
,09-30 06:38:24.367  5693  5739 I jxcore-log: # teardown
09-30 06:38:24.367  5693  5739 I jxcore-log: 
,09-30 06:38:24.407  5693  5739 I jxcore-log: # setup
09-30 06:38:24.407  5693  5739 I jxcore-log: 
,09-30 06:38:24.453  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-30 06:38:24.453  5693  5739 I jxcore-log: 
,09-30 06:38:24.961   927  3066 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 06:38:25.230   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:25.798  5693  5739 I jxcore-log: ok 48 should be equal
09-30 06:38:25.798  5693  5739 I jxcore-log: 
,09-30 06:38:25.798  5693  5739 I jxcore-log: ok 49 revs are equal
09-30 06:38:25.798  5693  5739 I jxcore-log: 
,09-30 06:38:25.803  5693  5739 I jxcore-log: # teardown
09-30 06:38:25.803  5693  5739 I jxcore-log: 
,09-30 06:38:25.840  5693  5739 I jxcore-log: # setup
09-30 06:38:25.840  5693  5739 I jxcore-log: 
,09-30 06:38:26.231   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 06:38:26.775  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-30 06:38:26.775  5693  5739 I jxcore-log: 
,09-30 06:38:27.719  5693  5739 I jxcore-log: ok 50 should be equal
09-30 06:38:27.719  5693  5739 I jxcore-log: 
,09-30 06:38:27.719  5693  5739 I jxcore-log: ok 51 revs are equal
09-30 06:38:27.719  5693  5739 I jxcore-log: 
,09-30 06:38:27.724  5693  5739 I jxcore-log: # teardown
09-30 06:38:27.724  5693  5739 I jxcore-log: 
,09-30 06:38:28.650  5693  5739 I jxcore-log: # setup
09-30 06:38:28.650  5693  5739 I jxcore-log: 
,09-30 06:38:29.224  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-30 06:38:29.224  5693  5739 I jxcore-log: 
,09-30 06:38:30.051   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 06:38:30.557  5693  5739 I jxcore-log: ok 52 should be equal
09-30 06:38:30.557  5693  5739 I jxcore-log: 
09-30 06:38:30.557  5693  5739 I jxcore-log: ok 53 revs are equal
09-30 06:38:30.557  5693  5739 I jxcore-log: 
,09-30 06:38:30.723  5693  5739 I jxcore-log: ok 54 should be equal
09-30 06:38:30.723  5693  5739 I jxcore-log: 
09-30 06:38:30.723  5693  5739 I jxcore-log: ok 55 revs are equal
09-30 06:38:30.723  5693  5739 I jxcore-log: 
,09-30 06:38:30.907  5693  5739 I jxcore-log: ok 56 should be equal
09-30 06:38:30.907  5693  5739 I jxcore-log: 
09-30 06:38:30.908  5693  5739 I jxcore-log: ok 57 revs are equal
09-30 06:38:30.908  5693  5739 I jxcore-log: 
,09-30 06:38:30.915  5693  5739 I jxcore-log: # teardown
09-30 06:38:30.915  5693  5739 I jxcore-log: 
,09-30 06:38:31.122  5693  5739 I jxcore-log: # setup
09-30 06:38:31.122  5693  5739 I jxcore-log: 
,09-30 06:38:31.232   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:31.234  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-30 06:38:31.234  5693  5739 I jxcore-log: 
,09-30 06:38:31.807  5693  5739 I jxcore-log: 2016-09-30 10:38:31 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-30 06:38:31.807  5693  5739 I jxcore-log: 
,09-30 06:38:31.808  5693  5739 I jxcore-log: ok 58 Our rev is old so we should fail
09-30 06:38:31.808  5693  5739 I jxcore-log: 
,09-30 06:38:31.811  5693  5739 I jxcore-log: # teardown
09-30 06:38:31.811  5693  5739 I jxcore-log: 
,09-30 06:38:31.897  5693  5739 I jxcore-log: # setup
09-30 06:38:31.897  5693  5739 I jxcore-log: 
,09-30 06:38:31.914  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-30 06:38:31.914  5693  5739 I jxcore-log: 
,09-30 06:38:32.010  5693  5739 I jxcore-log: ok 59 confirm stop caused failure
09-30 06:38:32.010  5693  5739 I jxcore-log: 
,09-30 06:38:32.022  5693  5739 I jxcore-log: # teardown
09-30 06:38:32.022  5693  5739 I jxcore-log: 
,09-30 06:38:32.053  5693  5739 I jxcore-log: # setup
09-30 06:38:32.053  5693  5739 I jxcore-log: 
,09-30 06:38:32.100  5693  5739 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-30 06:38:32.100  5693  5739 I jxcore-log: 
,09-30 06:38:32.233   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:32.404  5693  5739 I jxcore-log: 2016-09-30 10:38:32 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-30 06:38:32.404  5693  5739 I jxcore-log: 
,09-30 06:38:32.405  5693  5739 I jxcore-log: ok 60 stop caused us to fail
09-30 06:38:32.405  5693  5739 I jxcore-log: 
,09-30 06:38:32.406  5693  5739 I jxcore-log: ok 61 We specifically failed on a stop before put
09-30 06:38:32.406  5693  5739 I jxcore-log: 
,09-30 06:38:32.411  5693  5739 I jxcore-log: # teardown
09-30 06:38:32.411  5693  5739 I jxcore-log: 
,09-30 06:38:32.460  5693  5739 I jxcore-log: # setup
09-30 06:38:32.460  5693  5739 I jxcore-log: 
,09-30 06:38:32.515  5693  5739 I jxcore-log: # #update - fail if stop is called
09-30 06:38:32.515  5693  5739 I jxcore-log: 
,09-30 06:38:32.663  5693  5739 I jxcore-log: ok 62 failed due to stop
09-30 06:38:32.663  5693  5739 I jxcore-log: 
,09-30 06:38:32.666  5693  5739 I jxcore-log: ok 63 failed due to stop
09-30 06:38:32.666  5693  5739 I jxcore-log: 
,09-30 06:38:32.677  5693  5739 I jxcore-log: # teardown
09-30 06:38:32.677  5693  5739 I jxcore-log: 
,09-30 06:38:32.716  5693  5739 I jxcore-log: # setup
09-30 06:38:32.716  5693  5739 I jxcore-log: 
,09-30 06:38:32.776  5693  5739 I jxcore-log: # #update - set seq for first time
09-30 06:38:32.776  5693  5739 I jxcore-log: 
,09-30 06:38:33.074   927  3079 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 06:38:33.231  5693  5739 I jxcore-log: ok 64 should be equal
09-30 06:38:33.231  5693  5739 I jxcore-log: 
,09-30 06:38:33.234   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:33.238  5693  5739 I jxcore-log: # teardown
09-30 06:38:33.238  5693  5739 I jxcore-log: 
,09-30 06:38:33.307  5693  5739 I jxcore-log: # setup
09-30 06:38:33.307  5693  5739 I jxcore-log: 
,09-30 06:38:33.343  5693  5739 I jxcore-log: # #update - Fail on bad seq value
09-30 06:38:33.343  5693  5739 I jxcore-log: 
,09-30 06:38:33.789  5693  5739 I jxcore-log: 2016-09-30 10:38:33 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-30 06:38:33.789  5693  5739 I jxcore-log: 
,09-30 06:38:33.791  5693  5739 I jxcore-log: ok 65 Expected bad seq error
09-30 06:38:33.791  5693  5739 I jxcore-log: 
,09-30 06:38:33.797  5693  5739 I jxcore-log: # teardown
09-30 06:38:33.797  5693  5739 I jxcore-log: 
,09-30 06:38:33.854  5693  5739 I jxcore-log: # setup
09-30 06:38:33.854  5693  5739 I jxcore-log: 
,09-30 06:38:33.901  5693  5739 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-30 06:38:33.901  5693  5739 I jxcore-log: 
,09-30 06:38:34.234   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:35.235   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:35.454  5693  5739 I jxcore-log: ok 66 Different promises
09-30 06:38:35.454  5693  5739 I jxcore-log: 
,09-30 06:38:35.457  5693  5739 I jxcore-log: ok 67 Timer was cancelled
09-30 06:38:35.457  5693  5739 I jxcore-log: 
,09-30 06:38:35.596  5693  5739 I jxcore-log: ok 68 should be equal
09-30 06:38:35.596  5693  5739 I jxcore-log: 
,09-30 06:38:35.603  5693  5739 I jxcore-log: # teardown
09-30 06:38:35.603  5693  5739 I jxcore-log: 
,09-30 06:38:36.125  5693  5739 I jxcore-log: # setup
09-30 06:38:36.125  5693  5739 I jxcore-log: 
,09-30 06:38:36.152  5693  5739 I jxcore-log: # #update - do we wait for blocked update
09-30 06:38:36.152  5693  5739 I jxcore-log: 
,09-30 06:38:36.236   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 06:38:36.272  5693  5739 I jxcore-log: ok 69 One go and one blocked
09-30 06:38:36.272  5693  5739 I jxcore-log: 
,09-30 06:38:36.273  5693  5739 I jxcore-log: ok 70 All blocked
09-30 06:38:36.273  5693  5739 I jxcore-log: 
09-30 06:38:36.273  5693  5739 I jxcore-log: ok 71 Still blocked
09-30 06:38:36.273  5693  5739 I jxcore-log: 
,09-30 06:38:36.650  5693  5739 I jxcore-log: ok 72 should be equal
09-30 06:38:36.650  5693  5739 I jxcore-log: 
,09-30 06:38:36.657  5693  5739 I jxcore-log: # teardown
09-30 06:38:36.657  5693  5739 I jxcore-log: 
,09-30 06:38:36.721  5693  5739 I jxcore-log: # setup
09-30 06:38:36.721  5693  5739 I jxcore-log: 
,09-30 06:38:37.013  5693  5739 I jxcore-log: # #update - test that we wait long enough
09-30 06:38:37.013  5693  5739 I jxcore-log: 
,09-30 06:38:38.547  5693  5739 I jxcore-log: ok 73 We waited long enough
09-30 06:38:38.547  5693  5739 I jxcore-log: 
,09-30 06:38:38.650  5693  5739 I jxcore-log: ok 74 should be equal
09-30 06:38:38.650  5693  5739 I jxcore-log: 
,09-30 06:38:38.656  5693  5739 I jxcore-log: # teardown
09-30 06:38:38.656  5693  5739 I jxcore-log: 
,09-30 06:38:39.693  5693  5739 I jxcore-log: # setup
09-30 06:38:39.693  5693  5739 I jxcore-log: 
,09-30 06:38:39.754  5693  5739 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-30 06:38:39.754  5693  5739 I jxcore-log: 
,09-30 06:38:40.179  5693  5739 I jxcore-log: ok 75 Should have gotten same timer promise
09-30 06:38:40.179  5693  5739 I jxcore-log: 
,09-30 06:38:40.179  5693  5739 I jxcore-log: ok 76 Still same timer promise
09-30 06:38:40.179  5693  5739 I jxcore-log: 
,09-30 06:38:40.959  5693  5739 I jxcore-log: ok 77 We waited long enough
09-30 06:38:40.959  5693  5739 I jxcore-log: 
,09-30 06:38:41.032  5693  5739 I jxcore-log: ok 78 should be equal
09-30 06:38:41.032  5693  5739 I jxcore-log: 
,09-30 06:38:41.039  5693  5739 I jxcore-log: # teardown
09-30 06:38:41.039  5693  5739 I jxcore-log: 
,09-30 06:38:41.113  5693  5739 I jxcore-log: # setup
09-30 06:38:41.113  5693  5739 I jxcore-log: 
,09-30 06:38:41.202  5693  5739 I jxcore-log: # Coordinated seq test
09-30 06:38:41.202  5693  5739 I jxcore-log: 
,09-30 06:38:41.208  5693  5739 I jxcore-log: 2016-09-30 10:38:41 - INFO CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
09-30 06:38:41.208  5693  5739 I jxcore-log: 
,09-30 06:38:41.260  5693  5739 I jxcore-log: # teardown
09-30 06:38:41.260  5693  5739 I jxcore-log: 
,09-30 06:38:41.350  5693  5739 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-30 06:38:41.351  5693  5739 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 06:38:41.351  5693  5739 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 06:38:41.351  5693  5739 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 06:38:41.367  5693  5739 I jxcore-log: # setup
09-30 06:38:41.367  5693  5739 I jxcore-log: 
,09-30 06:38:41.402  5693  5739 I jxcore-log: # closeAll can close even when connections open
09-30 06:38:41.402  5693  5739 I jxcore-log: 
,09-30 06:38:41.559  5693  5739 I jxcore-log: ok 79 not possible to connect to the server anymore
09-30 06:38:41.559  5693  5739 I jxcore-log: 
,09-30 06:38:41.572  5693  5739 I jxcore-log: # teardown
09-30 06:38:41.572  5693  5739 I jxcore-log: 
,09-30 06:38:41.644  5693  5739 I jxcore-log: # setup
09-30 06:38:41.644  5693  5739 I jxcore-log: 
,09-30 06:38:41.693  5693  5739 I jxcore-log: # closeAll with promise
09-30 06:38:41.693  5693  5739 I jxcore-log: 
,09-30 06:38:41.866  5693  5739 I jxcore-log: ok 80 not possible to connect to the server anymore
09-30 06:38:41.866  5693  5739 I jxcore-log: 
,09-30 06:38:41.873  5693  5739 I jxcore-log: # teardown
09-30 06:38:41.873  5693  5739 I jxcore-log: 
,09-30 06:38:41.914  5693  5739 I jxcore-log: # setup
09-30 06:38:41.914  5693  5739 I jxcore-log: 
,09-30 06:38:41.964  5693  5739 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
09-30 06:38:41.964  5693  5739 I jxcore-log: 
,09-30 06:38:42.113  5693  5739 I jxcore-log: ok 81 Got the right error
09-30 06:38:42.113  5693  5739 I jxcore-log: 
,09-30 06:38:42.132  5693  5739 I jxcore-log: # teardown
09-30 06:38:42.132  5693  5739 I jxcore-log: 
,09-30 06:38:42.161  5693  5739 I jxcore-log: # setup
09-30 06:38:42.161  5693  5739 I jxcore-log: 
,09-30 06:38:42.210  5693  5739 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-30 06:38:42.210  5693  5739 I jxcore-log: 
,09-30 06:38:42.389  5693  5739 I jxcore-log: # teardown
09-30 06:38:42.389  5693  5739 I jxcore-log: 
,09-30 06:38:42.436  5693  5739 I jxcore-log: # setup
09-30 06:38:42.436  5693  5739 I jxcore-log: 
,09-30 06:38:42.461  5693  5739 I jxcore-log: # onPeerLost calls jxcore
09-30 06:38:42.461  5693  5739 I jxcore-log: 
,09-30 06:38:42.492  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 06:38:42.493  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1122e35 added. We now have 3 listener(s)
,09-30 06:38:42.494  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 06:38:42.494  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 06:38:42.494  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 06:38:42.495  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 06:38:42.495  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d002ca added. We now have 4 listener(s)
,09-30 06:38:42.495  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:38:42.496  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 06:38:42.500  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:38:42.507  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:38:42.507  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:38:42.507  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:38:42.507  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:38:42.507  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:38:42.507  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:38:42.507  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:38:42.507  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:38:42.510  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 06:38:42.510  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 06:38:42.510  5693  5739 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
,09-30 06:38:42.510  5693  5739 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-30 06:38:42.515  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:38:42.519  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:38:44.514  5693  5739 I jxcore-log: onPeerLost
09-30 06:38:44.514  5693  5739 I jxcore-log: 
,09-30 06:38:44.517  5693  5739 I jxcore-log: 2016-09-30 10:38:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:44.517  5693  5739 I jxcore-log: 
,09-30 06:38:44.536  5693  5739 I jxcore-log: # teardown
09-30 06:38:44.536  5693  5739 I jxcore-log: 
,09-30 06:38:44.545  5693  5739 I jxcore-log: ok 82 check if callback was fired by onPeerLost
09-30 06:38:44.545  5693  5739 I jxcore-log: 
,09-30 06:38:44.546  5693  5739 I jxcore-log: ok 83 check if peerAvailable is false
09-30 06:38:44.546  5693  5739 I jxcore-log: 
,09-30 06:38:44.553  5693  5739 I jxcore-log: 2016-09-30 10:38:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 06:38:44.553  5693  5739 I jxcore-log: 
,09-30 06:38:44.554  5693  5739 I jxcore-log: 2016-09-30 10:38:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 06:38:44.554  5693  5739 I jxcore-log: 
,09-30 06:38:44.560  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:38:44.560  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:38:44.560  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:38:44.560  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:38:44.560  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:38:44.560  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:38:44.560  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:38:44.560  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:38:44.562  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:38:44.563  5693  5739 I jxcore-log: 2016-09-30 10:38:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 06:38:44.563  5693  5739 I jxcore-log: 
,09-30 06:38:44.564  5693  5739 I jxcore-log: 2016-09-30 10:38:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 06:38:44.564  5693  5739 I jxcore-log: 
,09-30 06:38:44.569  5693  5739 I jxcore-log: 2016-09-30 10:38:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:44.569  5693  5739 I jxcore-log: 
09-30 06:38:44.570  5693  5739 I jxcore-log: # setup
09-30 06:38:44.570  5693  5739 I jxcore-log: 
,09-30 06:38:44.965   927  3066 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 06:38:44.998  5693  5739 I jxcore-log: # onPeerDiscovered calls jxcore
09-30 06:38:44.998  5693  5739 I jxcore-log: 
,09-30 06:38:45.053  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 06:38:45.053  5693  5739 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aebf58 added. We now have 4 listener(s)
,09-30 06:38:45.055  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 06:38:45.055  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 06:38:45.055  5693  5739 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 06:38:45.055  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 06:38:45.056  5693  5739 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c478b1 added. We now have 5 listener(s)
09-30 06:38:45.056  5693  5739 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 06:38:45.057  5693  5739 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 06:38:45.064  5693  5739 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 06:38:45.070  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:38:45.070  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:38:45.070  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:38:45.070  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:38:45.070  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:38:45.070  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:38:45.070  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:38:45.070  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:38:45.072  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:38:45.073  5693  5739 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 06:38:45.073  5693  5739 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-30 06:38:45.077  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:38:45.082  5693  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 06:38:46.237   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:47.075  5693  5739 I jxcore-log: onPeerDiscovered
09-30 06:38:47.075  5693  5739 I jxcore-log: 
,09-30 06:38:47.078  5693  5739 I jxcore-log: 2016-09-30 10:38:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:47.078  5693  5739 I jxcore-log: 
,09-30 06:38:47.090  5693  5739 I jxcore-log: # teardown
09-30 06:38:47.090  5693  5739 I jxcore-log: 
,09-30 06:38:47.096  5693  5739 I jxcore-log: ok 84 check if callback was fired by onPeerDiscovered
09-30 06:38:47.096  5693  5739 I jxcore-log: 
,09-30 06:38:47.097  5693  5739 I jxcore-log: ok 85 check if peerAvailable is true
09-30 06:38:47.097  5693  5739 I jxcore-log: 
,09-30 06:38:47.126  5693  5739 I jxcore-log: 2016-09-30 10:38:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 06:38:47.126  5693  5739 I jxcore-log: 
,09-30 06:38:47.127  5693  5739 I jxcore-log: 2016-09-30 10:38:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 06:38:47.127  5693  5739 I jxcore-log: 
,09-30 06:38:47.135  5693  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 06:38:47.135  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 06:38:47.135  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 06:38:47.135  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 06:38:47.135  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 06:38:47.135  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 06:38:47.135  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 06:38:47.135  5693  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 06:38:47.138  5693  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 06:38:47.140  5693  5739 I jxcore-log: 2016-09-30 10:38:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 06:38:47.140  5693  5739 I jxcore-log: 
,09-30 06:38:47.143  5693  5739 I jxcore-log: 2016-09-30 10:38:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 06:38:47.143  5693  5739 I jxcore-log: 
,09-30 06:38:47.148  5693  5739 I jxcore-log: 2016-09-30 10:38:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 06:38:47.148  5693  5739 I jxcore-log: 
,09-30 06:38:47.152  5693  5739 I jxcore-log: # setup
09-30 06:38:47.152  5693  5739 I jxcore-log: 
,09-30 06:38:47.238   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:47.562  5693  5739 I jxcore-log: # Call of onCheckpointReached handler on a single db change,
09-30 06:38:47.562  5693  5739 I jxcore-log: 
,09-30 06:38:48.239   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:48.568  5693  5739 I jxcore-log: # teardown
09-30 06:38:48.568  5693  5739 I jxcore-log: 
,09-30 06:38:49.028  5693  5739 I jxcore-log: # setup
09-30 06:38:49.028  5693  5739 I jxcore-log: 
,09-30 06:38:49.074  5693  5739 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
09-30 06:38:49.074  5693  5739 I jxcore-log: 
,09-30 06:38:49.240   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:49.392  5693  5739 I jxcore-log: # teardown
09-30 06:38:49.392  5693  5739 I jxcore-log: 
,09-30 06:38:49.484  5693  5739 I jxcore-log: # setup
09-30 06:38:49.484  5693  5739 I jxcore-log: 
,09-30 06:38:49.564  5693  5739 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
09-30 06:38:49.564  5693  5739 I jxcore-log: 
,09-30 06:38:50.240   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 06:38:50.871  5693  5739 I jxcore-log: ok 86 the checkpointReached handler should be called once. Called 1 time(s)
09-30 06:38:50.871  5693  5739 I jxcore-log: 
,09-30 06:38:50.887  5693  5739 I jxcore-log: # teardown
09-30 06:38:50.887  5693  5739 I jxcore-log: 
,09-30 06:38:50.975  5693  5739 I jxcore-log: # setup
09-30 06:38:50.975  5693  5739 I jxcore-log: 
,09-30 06:38:51.021  5693  5739 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
09-30 06:38:51.021  5693  5739 I jxcore-log: 
,09-30 06:38:51.241   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 06:38:51.592  5693  5739 I jxcore-log: # teardown
09-30 06:38:51.592  5693  5739 I jxcore-log: 
,09-30 06:38:51.660  5693  5739 I jxcore-log: # setup
09-30 06:38:51.660  5693  5739 I jxcore-log: 
,09-30 06:38:51.695  5693  5739 I jxcore-log: # test defaultDirectory
09-30 06:38:51.695  5693  5739 I jxcore-log: 
,09-30 06:38:51.754  5693  5739 I jxcore-log: ok 87 should be equal
09-30 06:38:51.754  5693  5739 I jxcore-log: 
,09-30 06:38:51.756  5693  5739 I jxcore-log: ok 88 should be equal
09-30 06:38:51.756  5693  5739 I jxcore-log: 
,09-30 06:38:51.760  5693  5739 I jxcore-log: ok 89 should be equal
09-30 06:38:51.760  5693  5739 I jxcore-log: 
,09-30 06:38:51.776  5693  5739 I jxcore-log: # teardown
09-30 06:38:51.776  5693  5739 I jxcore-log: 
,09-30 06:38:51.824  5693  5739 I jxcore-log: # setup
09-30 06:38:51.824  5693  5739 I jxcore-log: 
,09-30 06:38:51.859  5693  5739 I jxcore-log: # test defaultAdapter
09-30 06:38:51.859  5693  5739 I jxcore-log: 
,09-30 06:38:51.892  5693  5739 I jxcore-log: ok 90 should be equal
09-30 06:38:51.892  5693  5739 I jxcore-log: 
,09-30 06:38:51.893  5693  5739 I jxcore-log: ok 91 should be equal
09-30 06:38:51.893  5693  5739 I jxcore-log: 
09-30 06:38:51.895  5693  5739 I jxcore-log: ok 92 should be equal
09-30 06:38:51.895  5693  5739 I jxcore-log: 
09-30 06:38:51.896  5693  5739 I jxcore-log: ok 93 should be equal
09-30 06:38:51.896  5693  5739 I jxcore-log: 
,09-30 06:38:51.898  5693  5739 I jxcore-log: ok 94 should be equal
09-30 06:38:51.898  5693  5739 I jxcore-log: 
,09-30 06:38:51.899  5693  5739 I jxcore-log: ok 95 should be equal
09-30 06:38:51.899  5693  5739 I jxcore-log: 
,09-30 06:38:52.022  5693  5739 I jxcore-log: ok 96 should be equal
09-30 06:38:52.022  5693  5739 I jxcore-log: 
,09-30 06:38:52.022  5693  5739 I jxcore-log: ok 97 should be equal
09-30 06:38:52.022  5693  5739 I jxcore-log: 
,09-30 06:38:52.029  5693  5739 I jxcore-log: # teardown
09-30 06:38:52.029  5693  5739 I jxcore-log: 
,09-30 06:38:52.080  5693  5739 I jxcore-log: # setup
09-30 06:38:52.080  5693  5739 I jxcore-log: 
,09-30 06:38:52.134  5693  5739 I jxcore-log: # enqueue and run in order
09-30 06:38:52.134  5693  5739 I jxcore-log: 
,09-30 06:38:52.273  5693  5739 I jxcore-log: ok 98 firstPromise setTimeout
09-30 06:38:52.273  5693  5739 I jxcore-log: 
,09-30 06:38:52.278  5693  5739 I jxcore-log: ok 99 firstPromise result
09-30 06:38:52.278  5693  5739 I jxcore-log: 
,09-30 06:38:52.280  5693  5739 I jxcore-log: ok 100 firstPromise testValue
09-30 06:38:52.280  5693  5739 I jxcore-log: 
,09-30 06:38:52.384  5693  5739 I jxcore-log: ok 101 secondPromise setTimeout
09-30 06:38:52.384  5693  5739 I jxcore-log: 
,09-30 06:38:52.387  5693  5739 I jxcore-log: ok 102 secondPromise result
09-30 06:38:52.387  5693  5739 I jxcore-log: 
,09-30 06:38:52.388  5693  5739 I jxcore-log: ok 103 secondPromise testValue
09-30 06:38:52.388  5693  5739 I jxcore-log: 
,09-30 06:38:52.391  5693  5739 I jxcore-log: ok 104 thirdPromise in promise
09-30 06:38:52.391  5693  5739 I jxcore-log: 
,09-30 06:38:52.394  5693  5739 I jxcore-log: ok 105 thirdPromise result
09-30 06:38:52.394  5693  5739 I jxcore-log: 
,09-30 06:38:52.396  5693  5739 I jxcore-log: ok 106 thirdPromise testValue
09-30 06:38:52.396  5693  5739 I jxcore-log: 
,09-30 06:38:52.405  5693  5739 I jxcore-log: # teardown
09-30 06:38:52.405  5693  5739 I jxcore-log: 
,09-30 06:38:52.450  5693  5739 I jxcore-log: # setup
09-30 06:38:52.450  5693  5739 I jxcore-log: 
,09-30 06:38:52.877  5693  5739 I jxcore-log: # enqueueAtTop and run backwards
09-30 06:38:52.877  5693  5739 I jxcore-log: 
,09-30 06:38:53.393  5693  5739 I jxcore-log: ok 107 thirdPromise - first to run
09-30 06:38:53.393  5693  5739 I jxcore-log: 
,09-30 06:38:53.395  5693  5739 I jxcore-log: ok 108 thirdPromise - in resolve
09-30 06:38:53.395  5693  5739 I jxcore-log: 
,09-30 06:38:53.396  5693  5739 I jxcore-log: ok 109 secondPromise - second to run
09-30 06:38:53.396  5693  5739 I jxcore-log: 
,09-30 06:38:53.398  5693  5739 I jxcore-log: ok 110 secondPromise - in catch
09-30 06:38:53.398  5693  5739 I jxcore-log: 
09-30 06:38:53.399  5693  5739 I jxcore-log: ok 111 firstPromise - third to run
09-30 06:38:53.399  5693  5739 I jxcore-log: 
,09-30 06:38:53.400  5693  5739 I jxcore-log: ok 112 firstPromise - in then
09-30 06:38:53.400  5693  5739 I jxcore-log: 
,09-30 06:38:53.401  5693  5739 I jxcore-log: ok 113 testing promises
09-30 06:38:53.401  5693  5739 I jxcore-log: 
,09-30 06:38:53.410  5693  5739 I jxcore-log: # teardown
09-30 06:38:53.410  5693  5739 I jxcore-log: 
,09-30 06:38:53.445  5693  5739 I jxcore-log: # setup
09-30 06:38:53.445  5693  5739 I jxcore-log: 
,09-30 06:38:53.488  5693  5739 I jxcore-log: # mix enqueue and enqueueAtTop
09-30 06:38:53.488  5693  5739 I jxcore-log: 
,09-30 06:38:53.547  5693  5739 I jxcore-log: ok 114 fourth
09-30 06:38:53.547  5693  5739 I jxcore-log: 
,09-30 06:38:53.550  5693  5739 I jxcore-log: ok 115 fourth
09-30 06:38:53.550  5693  5739 I jxcore-log: 
,09-30 06:38:53.552  5693  5739 I jxcore-log: ok 116 second
09-30 06:38:53.552  5693  5739 I jxcore-log: 
09-30 06:38:53.554  5693  5739 I jxcore-log: ok 117 secondPromise - in then
09-30 06:38:53.554  5693  5739 I jxcore-log: 
,09-30 06:38:53.657  5693  5739 I jxcore-log: ok 118 first
09-30 06:38:53.657  5693  5739 I jxcore-log: 
,09-30 06:38:53.662  5693  5739 I jxcore-log: ok 119 firstPromise - in catch
09-30 06:38:53.662  5693  5739 I jxcore-log: 
,09-30 06:38:53.664  5693  5739 I jxcore-log: ok 120 third
09-30 06:38:53.664  5693  5739 I jxcore-log: 
09-30 06:38:53.667  5693  5739 I jxcore-log: ok 121 thirdPromise - in then
09-30 06:38:53.667  5693  5739 I jxcore-log: 
,09-30 06:38:53.669  5693  5739 I jxcore-log: ok 122 testingPromises
09-30 06:38:53.669  5693  5739 I jxcore-log: 
,09-30 06:38:53.680  5693  5739 I jxcore-log: # teardown
09-30 06:38:53.680  5693  5739 I jxcore-log: 
,09-30 06:38:53.715  5693  5739 I jxcore-log: # setup
09-30 06:38:53.715  5693  5739 I jxcore-log: 
,09-30 06:38:53.842  5693  5739 I jxcore-log: # queues handled independently
09-30 06:38:53.842  5693  5739 I jxcore-log: 
,09-30 06:38:53.910  5693  5739 I jxcore-log: ok 123 all short operations completed before the long resolves
09-30 06:38:53.910  5693  5739 I jxcore-log: 
,09-30 06:38:53.916  5693  5739 I jxcore-log: # teardown
09-30 06:38:53.916  5693  5739 I jxcore-log: 
,09-30 06:38:53.978  5693  5739 I jxcore-log: # setup
09-30 06:38:53.978  5693  5739 I jxcore-log: 
,09-30 06:38:54.026  5693  5739 I jxcore-log: # basic
09-30 06:38:54.026  5693  5739 I jxcore-log: 
,09-30 06:38:54.071  5693  5739 I jxcore-log: ok 124 sane
09-30 06:38:54.071  5693  5739 I jxcore-log: 
,09-30 06:38:54.087  5693  5739 I jxcore-log: # teardown
09-30 06:38:54.087  5693  5739 I jxcore-log: 
,09-30 06:38:54.123  5693  5739 I jxcore-log: # setup
09-30 06:38:54.123  5693  5739 I jxcore-log: 
,09-30 06:38:54.168  5693  5739 I jxcore-log: # another
09-30 06:38:54.168  5693  5739 I jxcore-log: 
,09-30 06:38:54.201  5693  5739 I jxcore-log: ok 125 sane
09-30 06:38:54.201  5693  5739 I jxcore-log: 
,09-30 06:38:54.208  5693  5739 I jxcore-log: # teardown
09-30 06:38:54.208  5693  5739 I jxcore-log: 
,09-30 06:38:54.232  5693  5739 I jxcore-log: # setup
09-30 06:38:54.232  5693  5739 I jxcore-log: 
,09-30 06:38:54.306  5693  5739 I jxcore-log: # can pass data in setup
09-30 06:38:54.306  5693  5739 I jxcore-log: 
,09-30 06:38:54.344  5693  5739 I jxcore-log: ok 126 test participant has uuid
09-30 06:38:54.344  5693  5739 I jxcore-log: 
,09-30 06:38:54.346  5693  5739 I jxcore-log: ok 127 participant data matches
09-30 06:38:54.346  5693  5739 I jxcore-log: 
09-30 06:38:54.347  5693  5739 I jxcore-log: ok 128 test participant has uuid
09-30 06:38:54.347  5693  5739 I jxcore-log: 
,09-30 06:38:54.347  5693  5739 I jxcore-log: ok 129 participant data matches
09-30 06:38:54.347  5693  5739 I jxcore-log: 
09-30 06:38:54.348  5693  5739 I jxcore-log: ok 130 test participant has uuid
09-30 06:38:54.348  5693  5739 I jxcore-log: 
09-30 06:38:54.349  5693  5739 I jxcore-log: ok 131 participant data matches
09-30 06:38:54.349  5693  5739 I jxcore-log: 
09-30 06:38:54.349  5693  5739 I jxcore-log: ok 132 own UUID is found from the participants list
09-30 06:38:54.349  5693  5739 I jxcore-log: 
,09-30 06:38:54.359  5693  5739 I jxcore-log: # teardown
09-30 06:38:54.359  5693  5739 I jxcore-log: 
,09-30 06:38:54.468  5693  5739 I jxcore-log: # setup
09-30 06:38:54.468  5693  5739 I jxcore-log: 
,09-30 06:38:54.535  5693  5739 I jxcore-log: # test thali manager spies
09-30 06:38:54.535  5693  5739 I jxcore-log: 
,09-30 06:38:54.701  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 06:38:54.701  5693  5739 I jxcore-log: 
,09-30 06:38:54.706  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 06:38:54.706  5693  5739 I jxcore-log: 
,09-30 06:38:54.708  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 06:38:54.708  5693  5739 I jxcore-log: 
,09-30 06:38:54.724  5693  5739 I jxcore-log: ok 133 expressPouchDB was called once
09-30 06:38:54.724  5693  5739 I jxcore-log: 
09-30 06:38:54.725  5693  5739 I jxcore-log: ok 134 expressPouchDB was called with 2 arguments
09-30 06:38:54.725  5693  5739 I jxcore-log: 
09-30 06:38:54.725  5693  5739 I jxcore-log: ok 135 expressPouchDB was called with 'PouchDB' as 1-st argument
09-30 06:38:54.725  5693  5739 I jxcore-log: 
,09-30 06:38:54.726  5693  5739 I jxcore-log: ok 136 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-30 06:38:54.726  5693  5739 I jxcore-log: 
09-30 06:38:54.726  5693  5739 I jxcore-log: ok 137 PouchDB was called once
09-30 06:38:54.726  5693  5739 I jxcore-log: 
09-30 06:38:54.726  5693  5739 I jxcore-log: ok 138 PouchDB was called with 1 arguments
09-30 06:38:54.726  5693  5739 I jxcore-log: 
09-30 06:38:54.726  5693  5739 I jxcore-log: ok 139 PouchDB was called with 'dbName' as 1-st argument
09-30 06:38:54.726  5693  5739 I jxcore-log: 
09-30 06:38:54.726  5693  5739 I jxcore-log: ok 140 ThaliSendNotificationBasedOnReplication was called once
09-30 06:38:54.726  5693  5739 I jxcore-log: 
,09-30 06:38:54.727  5693  5739 I jxcore-log: ok 141 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-30 06:38:54.727  5693  5739 I jxcore-log: 
09-30 06:38:54.727  5693  5739 I jxcore-log: ok 142 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-30 06:38:54.727  5693  5739 I jxcore-log: 
09-30 06:38:54.727  5693  5739 I jxcore-log: ok 143 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-30 06:38:54.727  5693  5739 I jxcore-log: 
09-30 06:38:54.727  5693  5739 I jxcore-log: ok 144 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-30 06:38:54.727  5693  5739 I jxcore-log: 
09-30 06:38:54.728  5693  5739 I jxcore-log: ok 145 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-30 06:38:54.728  5693  5739 I jxcore-log: 
,09-30 06:38:54.728  5693  5739 I jxcore-log: ok 146 ThaliPullReplicationFromNotification was called once
09-30 06:38:54.728  5693  5739 I jxcore-log: 
09-30 06:38:54.728  5693  5739 I jxcore-log: ok 147 ThaliPullReplicationFromNotification was called with 4 arguments
09-30 06:38:54.728  5693  5739 I jxcore-log: 
09-30 06:38:54.729  5693  5739 I jxcore-log: ok 148 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-30 06:38:54.729  5693  5739 I jxcore-log: 
09-30 06:38:54.729  5693  5739 I jxcore-log: ok 149 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-30 06:38:54.729  5693  5739 I jxcore-log: 
,09-30 06:38:54.729  5693  5739 I jxcore-log: ok 150 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-30 06:38:54.729  5693  5739 I jxcore-log: 
09-30 06:38:54.729  5693  5739 I jxcore-log: ok 151 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-30 06:38:54.729  5693  5739 I jxcore-log: 
09-30 06:38:54.729  5693  5739 I jxcore-log: ok 152 Salti was called once
09-30 06:38:54.729  5693  5739 I jxcore-log: 
09-30 06:38:54.730  5693  5739 I jxcore-log: ok 153 Salti was called with 4 arguments
09-30 06:38:54.730  5693  5739 I jxcore-log: 
,09-30 06:38:54.730  5693  5739 I jxcore-log: ok 154 Salti was called with 'dbName' as 1-st argument
09-30 06:38:54.730  5693  5739 I jxcore-log: 
09-30 06:38:54.730  5693  5739 I jxcore-log: ok 155 Salti was called with 'acl' as 2-st argument
09-30 06:38:54.730  5693  5739 I jxcore-log: 
09-30 06:38:54.731  5693  5739 I jxcore-log: ok 156 Salti was called with 'thaliIdCallback' as 3-st argument
09-30 06:38:54.731  5693  5739 I jxcore-log: 
,09-30 06:38:54.731  5693  5739 I jxcore-log: ok 157 Salti was called with 'options' as 4-st argument
09-30 06:38:54.731  5693  5739 I jxcore-log: 
,09-30 06:38:54.732  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 06:38:54.732  5693  5739 I jxcore-log: 
,09-30 06:38:54.733  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 06:38:54.733  5693  5739 I jxcore-log: 
09-30 06:38:54.734  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 06:38:54.734  5693  5739 I jxcore-log: 
,09-30 06:38:54.736  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'start listening for advertisements'
09-30 06:38:54.736  5693  5739 I jxcore-log: 
,09-30 06:38:54.741  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'start update advertising and listening'
09-30 06:38:54.741  5693  5739 I jxcore-log: 
,09-30 06:38:54.767  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliWifiInfrastructure: 'listening 47886'
09-30 06:38:54.767  5693  5739 I jxcore-log: 
,09-30 06:38:54.769  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 06:38:54.769  5693  5739 I jxcore-log: 
,09-30 06:38:54.788  5693  5739 I jxcore-log: ok 158 ThaliMobile.start was called once
09-30 06:38:54.788  5693  5739 I jxcore-log: 
,09-30 06:38:54.789  5693  5739 I jxcore-log: ok 159 ThaliMobile.start was called with 2 arguments
09-30 06:38:54.789  5693  5739 I jxcore-log: 
09-30 06:38:54.789  5693  5739 I jxcore-log: ok 160 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 06:38:54.789  5693  5739 I jxcore-log: 
09-30 06:38:54.789  5693  5739 I jxcore-log: ok 161 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 06:38:54.789  5693  5739 I jxcore-log: 
,09-30 06:38:54.789  5693  5739 I jxcore-log: ok 162 ThaliMobile.startListeningForAdvertisements was called once
09-30 06:38:54.789  5693  5739 I jxcore-log: 
09-30 06:38:54.790  5693  5739 I jxcore-log: ok 163 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 06:38:54.790  5693  5739 I jxcore-log: 
09-30 06:38:54.790  5693  5739 I jxcore-log: ok 164 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 06:38:54.790  5693  5739 I jxcore-log: 
09-30 06:38:54.790  5693  5739 I jxcore-log: ok 165 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 06:38:54.790  5693  5739 I jxcore-log: 
,09-30 06:38:54.790  5693  5739 I jxcore-log: ok 166 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 06:38:54.790  5693  5739 I jxcore-log: 
09-30 06:38:54.790  5693  5739 I jxcore-log: ok 167 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 06:38:54.790  5693  5739 I jxcore-log: 
09-30 06:38:54.791  5693  5739 I jxcore-log: ok 168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 06:38:54.791  5693  5739 I jxcore-log: 
09-30 06:38:54.791  5693  5739 I jxcore-log: ok 169 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 06:38:54.791  5693  5739 I jxcore-log: 
,09-30 06:38:54.791  5693  5739 I jxcore-log: ok 170 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 06:38:54.791  5693  5739 I jxcore-log: 
09-30 06:38:54.791  5693  5739 I jxcore-log: ok 171 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 06:38:54.791  5693  5739 I jxcore-log: 
,09-30 06:38:54.792  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 06:38:54.792  5693  5739 I jxcore-log: 
09-30 06:38:54.793  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 06:38:54.793  5693  5739 I jxcore-log: 
,09-30 06:38:54.794  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 06:38:54.794  5693  5739 I jxcore-log: 
,09-30 06:38:54.796  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 06:38:54.796  5693  5739 I jxcore-log: 
,09-30 06:38:54.801  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 06:38:54.801  5693  5739 I jxcore-log: 
,09-30 06:38:54.803  5693  5739 I jxcore-log: 2016-09-30 10:38:54 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 06:38:54.803  5693  5739 I jxcore-log: 
,09-30 06:38:54.806  5693  5739 I jxcore-log: ok 172 ThaliMobile.stop was called once
09-30 06:38:54.806  5693  5739 I jxcore-log: 
,09-30 06:38:54.806  5693  5739 I jxcore-log: ok 173 ThaliMobile.stop was called with 0 arguments
09-30 06:38:54.806  5693  5739 I jxcore-log: 
09-30 06:38:54.806  5693  5739 I jxcore-log: ok 174 ThaliMobile.stopListeningForAdvertisements was called once
09-30 06:38:54.806  5693  5739 I jxcore-log: 
09-30 06:38:54.807  5693  5739 I jxcore-log: ok 175 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-30 06:38:54.807  5693  5739 I jxcore-log: 
09-30 06:38:54.807  5693  5739 I jxcore-log: ok 176 ThaliMobile.stopAdvertisingAndListening was called once
09-30 06:38:54.807  5693  5739 I jxcore-log: 
09-30 06:38:54.807  5693  5739 I jxcore-log: ok 177 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-30 06:38:54.807  5693  5739 I jxcore-log: 
09-30 06:38:54.807  5693  5739 I jxcore-log: ok 178 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-30 06:38:54.807  5693  5739 I jxcore-log: 
,09-30 06:38:54.807  5693  5739 I jxcore-log: ok 179 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-30 06:38:54.807  5693  5739 I jxcore-log: 
09-30 06:38:54.807  5693  5739 I jxcore-log: ok 180 ThaliPullReplicationFromNotification.prototype.stop was called once
09-30 06:38:54.807  5693  5739 I jxcore-log: 
09-30 06:38:54.808  5693  5739 I jxcore-log: ok 181 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-30 06:38:54.808  5693  5739 I jxcore-log: 
,09-30 06:38:54.816  5693  5739 I jxcore-log: # teardown
09-30 06:38:54.816  5693  5739 I jxcore-log: 
,09-30 06:38:54.876  5693  5739 I jxcore-log: # setup
09-30 06:38:54.876  5693  5739 I jxcore-log: 
,09-30 06:38:54.913  5693  5739 I jxcore-log: # test thali manager multiple starts and stops
09-30 06:38:54.913  5693  5739 I jxcore-log: 
,09-30 06:38:55.097  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 06:38:55.097  5693  5739 I jxcore-log: 
,09-30 06:38:55.103  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 06:38:55.103  5693  5739 I jxcore-log: 
,09-30 06:38:55.105  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 06:38:55.105  5693  5739 I jxcore-log: 
,09-30 06:38:55.125  5693  5739 I jxcore-log: ok 182 expressPouchDB was called once
09-30 06:38:55.125  5693  5739 I jxcore-log: 
09-30 06:38:55.126  5693  5739 I jxcore-log: ok 183 expressPouchDB was called with 2 arguments
09-30 06:38:55.126  5693  5739 I jxcore-log: 
,09-30 06:38:55.126  5693  5739 I jxcore-log: ok 184 expressPouchDB was called with 'PouchDB' as 1-st argument
09-30 06:38:55.126  5693  5739 I jxcore-log: 
09-30 06:38:55.126  5693  5739 I jxcore-log: ok 185 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-30 06:38:55.126  5693  5739 I jxcore-log: 
09-30 06:38:55.126  5693  5739 I jxcore-log: ok 186 PouchDB was called once
09-30 06:38:55.126  5693  5739 I jxcore-log: 
09-30 06:38:55.127  5693  5739 I jxcore-log: ok 187 PouchDB was called with 1 arguments
09-30 06:38:55.127  5693  5739 I jxcore-log: 
09-30 06:38:55.127  5693  5739 I jxcore-log: ok 188 PouchDB was called with 'dbName' as 1-st argument
09-30 06:38:55.127  5693  5739 I jxcore-log: 
09-30 06:38:55.127  5693  5739 I jxcore-log: ok 189 ThaliSendNotificationBasedOnReplication was called once
09-30 06:38:55.127  5693  5739 I jxcore-log: 
,09-30 06:38:55.127  5693  5739 I jxcore-log: ok 190 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-30 06:38:55.127  5693  5739 I jxcore-log: 
09-30 06:38:55.128  5693  5739 I jxcore-log: ok 191 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-30 06:38:55.128  5693  5739 I jxcore-log: 
09-30 06:38:55.128  5693  5739 I jxcore-log: ok 192 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-30 06:38:55.128  5693  5739 I jxcore-log: 
09-30 06:38:55.128  5693  5739 I jxcore-log: ok 193 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-30 06:38:55.128  5693  5739 I jxcore-log: 
09-30 06:38:55.128  5693  5739 I jxcore-log: ok 194 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-30 06:38:55.128  5693  5739 I jxcore-log: 
,09-30 06:38:55.129  5693  5739 I jxcore-log: ok 195 ThaliPullReplicationFromNotification was called once
09-30 06:38:55.129  5693  5739 I jxcore-log: 
09-30 06:38:55.129  5693  5739 I jxcore-log: ok 196 ThaliPullReplicationFromNotification was called with 4 arguments
09-30 06:38:55.129  5693  5739 I jxcore-log: 
09-30 06:38:55.129  5693  5739 I jxcore-log: ok 197 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-30 06:38:55.129  5693  5739 I jxcore-log: 
09-30 06:38:55.129  5693  5739 I jxcore-log: ok 198 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-30 06:38:55.129  5693  5739 I jxcore-log: 
09-30 06:38:55.129  5693  5739 I jxcore-log: ok 199 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-30 06:38:55.129  5693  5739 I jxcore-log: 
09-30 06:38:55.130  5693  5739 I jxcore-log: ok 200 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-30 06:38:55.130  5693  5739 I jxcore-log: 
,09-30 06:38:55.130  5693  5739 I jxcore-log: ok 201 Salti was called once
09-30 06:38:55.130  5693  5739 I jxcore-log: 
09-30 06:38:55.130  5693  5739 I jxcore-log: ok 202 Salti was called with 4 arguments
09-30 06:38:55.130  5693  5739 I jxcore-log: 
09-30 06:38:55.130  5693  5739 I jxcore-log: ok 203 Salti was called with 'dbName' as 1-st argument
09-30 06:38:55.130  5693  5739 I jxcore-log: 
09-30 06:38:55.130  5693  5739 I jxcore-log: ok 204 Salti was called with 'acl' as 2-st argument
09-30 06:38:55.130  5693  5739 I jxcore-log: 
09-30 06:38:55.130  5693  5739 I jxcore-log: ok 205 Salti was called with 'thaliIdCallback' as 3-st argument
09-30 06:38:55.130  5693  5739 I jxcore-log: 
,09-30 06:38:55.131  5693  5739 I jxcore-log: ok 206 Salti was called with 'options' as 4-st argument
09-30 06:38:55.131  5693  5739 I jxcore-log: 
09-30 06:38:55.132  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 06:38:55.132  5693  5739 I jxcore-log: 
,09-30 06:38:55.132  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 06:38:55.132  5693  5739 I jxcore-log: 
,09-30 06:38:55.133  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 06:38:55.133  5693  5739 I jxcore-log: 
,09-30 06:38:55.137  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start listening for advertisements'
09-30 06:38:55.137  5693  5739 I jxcore-log: 
,09-30 06:38:55.140  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start update advertising and listening'
09-30 06:38:55.140  5693  5739 I jxcore-log: 
,09-30 06:38:55.146  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliWifiInfrastructure: 'listening 41806'
09-30 06:38:55.146  5693  5739 I jxcore-log: 
,09-30 06:38:55.149  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 06:38:55.149  5693  5739 I jxcore-log: 
,09-30 06:38:55.184  5693  5739 I jxcore-log: ok 207 ThaliMobile.start was called once
09-30 06:38:55.184  5693  5739 I jxcore-log: 
,09-30 06:38:55.184  5693  5739 I jxcore-log: ok 208 ThaliMobile.start was called with 2 arguments
09-30 06:38:55.184  5693  5739 I jxcore-log: 
09-30 06:38:55.184  5693  5739 I jxcore-log: ok 209 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 06:38:55.184  5693  5739 I jxcore-log: 
09-30 06:38:55.184  5693  5739 I jxcore-log: ok 210 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 06:38:55.184  5693  5739 I jxcore-log: 
09-30 06:38:55.184  5693  5739 I jxcore-log: ok 211 ThaliMobile.startListeningForAdvertisements was called once
09-30 06:38:55.184  5693  5739 I jxcore-log: 
09-30 06:38:55.185  5693  5739 I jxcore-log: ok 212 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 06:38:55.185  5693  5739 I jxcore-log: 
09-30 06:38:55.185  5693  5739 I jxcore-log: ok 213 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 06:38:55.185  5693  5739 I jxcore-log: 
,09-30 06:38:55.185  5693  5739 I jxcore-log: ok 214 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 06:38:55.185  5693  5739 I jxcore-log: 
09-30 06:38:55.185  5693  5739 I jxcore-log: ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 06:38:55.185  5693  5739 I jxcore-log: 
09-30 06:38:55.185  5693  5739 I jxcore-log: ok 216 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 06:38:55.185  5693  5739 I jxcore-log: 
09-30 06:38:55.185  5693  5739 I jxcore-log: ok 217 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 06:38:55.185  5693  5739 I jxcore-log: 
09-30 06:38:55.186  5693  5739 I jxcore-log: ok 218 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 06:38:55.186  5693  5739 I jxcore-log: 
09-30 06:38:55.186  5693  5739 I jxcore-log: ok 219 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 06:38:55.186  5693  5739 I jxcore-log: 
,09-30 06:38:55.186  5693  5739 I jxcore-log: ok 220 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 06:38:55.186  5693  5739 I jxcore-log: 
09-30 06:38:55.187  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 06:38:55.187  5693  5739 I jxcore-log: 
,09-30 06:38:55.188  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 06:38:55.188  5693  5739 I jxcore-log: 
,09-30 06:38:55.190  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 06:38:55.190  5693  5739 I jxcore-log: 
,09-30 06:38:55.191  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 06:38:55.191  5693  5739 I jxcore-log: 
,09-30 06:38:55.195  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 06:38:55.195  5693  5739 I jxcore-log: 
,09-30 06:38:55.197  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 06:38:55.197  5693  5739 I jxcore-log: 
,09-30 06:38:55.202  5693  5739 I jxcore-log: ok 221 ThaliMobile.stop was called once
09-30 06:38:55.202  5693  5739 I jxcore-log: 
,09-30 06:38:55.203  5693  5739 I jxcore-log: ok 222 ThaliMobile.stop was called with 0 arguments
09-30 06:38:55.203  5693  5739 I jxcore-log: 
09-30 06:38:55.203  5693  5739 I jxcore-log: ok 223 ThaliMobile.stopListeningForAdvertisements was called once
09-30 06:38:55.203  5693  5739 I jxcore-log: 
09-30 06:38:55.203  5693  5739 I jxcore-log: ok 224 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-30 06:38:55.203  5693  5739 I jxcore-log: 
09-30 06:38:55.203  5693  5739 I jxcore-log: ok 225 ThaliMobile.stopAdvertisingAndListening was called once
09-30 06:38:55.203  5693  5739 I jxcore-log: 
,09-30 06:38:55.203  5693  5739 I jxcore-log: ok 226 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-30 06:38:55.203  5693  5739 I jxcore-log: 
09-30 06:38:55.203  5693  5739 I jxcore-log: ok 227 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-30 06:38:55.203  5693  5739 I jxcore-log: 
09-30 06:38:55.204  5693  5739 I jxcore-log: ok 228 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-30 06:38:55.204  5693  5739 I jxcore-log: 
09-30 06:38:55.204  5693  5739 I jxcore-log: ok 229 ThaliPullReplicationFromNotification.prototype.stop was called once
09-30 06:38:55.204  5693  5739 I jxcore-log: 
09-30 06:38:55.204  5693  5739 I jxcore-log: ok 230 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-30 06:38:55.204  5693  5739 I jxcore-log: 
,09-30 06:38:55.204  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 06:38:55.204  5693  5739 I jxcore-log: 
09-30 06:38:55.205  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 06:38:55.205  5693  5739 I jxcore-log: 
09-30 06:38:55.206  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 06:38:55.206  5693  5739 I jxcore-log: 
,09-30 06:38:55.208  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start listening for advertisements'
09-30 06:38:55.208  5693  5739 I jxcore-log: 
,09-30 06:38:55.210  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start update advertising and listening'
09-30 06:38:55.210  5693  5739 I jxcore-log: 
,09-30 06:38:55.214  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliWifiInfrastructure: 'listening 37397'
09-30 06:38:55.214  5693  5739 I jxcore-log: 
,09-30 06:38:55.216  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 06:38:55.216  5693  5739 I jxcore-log: 
,09-30 06:38:55.219  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 06:38:55.219  5693  5739 I jxcore-log: 
,09-30 06:38:55.219  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 06:38:55.219  5693  5739 I jxcore-log: 
,09-30 06:38:55.221  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 06:38:55.221  5693  5739 I jxcore-log: 
,09-30 06:38:55.223  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 06:38:55.223  5693  5739 I jxcore-log: 
,09-30 06:38:55.229  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 06:38:55.229  5693  5739 I jxcore-log: 
,09-30 06:38:55.231  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 06:38:55.231  5693  5739 I jxcore-log: 
,09-30 06:38:55.234  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 06:38:55.234  5693  5739 I jxcore-log: 
,09-30 06:38:55.234  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 06:38:55.234  5693  5739 I jxcore-log: 
09-30 06:38:55.235  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 06:38:55.235  5693  5739 I jxcore-log: 
,09-30 06:38:55.237  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start listening for advertisements'
09-30 06:38:55.237  5693  5739 I jxcore-log: 
,09-30 06:38:55.240  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start update advertising and listening'
09-30 06:38:55.240  5693  5739 I jxcore-log: 
,09-30 06:38:55.244  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliWifiInfrastructure: 'listening 49295'
09-30 06:38:55.244  5693  5739 I jxcore-log: 
,09-30 06:38:55.247  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 06:38:55.247  5693  5739 I jxcore-log: 
,09-30 06:38:55.250  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 06:38:55.250  5693  5739 I jxcore-log: 
,09-30 06:38:55.251  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 06:38:55.251  5693  5739 I jxcore-log: 
,09-30 06:38:55.252  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 06:38:55.252  5693  5739 I jxcore-log: 
,09-30 06:38:55.254  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 06:38:55.254  5693  5739 I jxcore-log: 
,09-30 06:38:55.258  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 06:38:55.258  5693  5739 I jxcore-log: 
,09-30 06:38:55.260  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 06:38:55.260  5693  5739 I jxcore-log: 
,09-30 06:38:55.263  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 06:38:55.263  5693  5739 I jxcore-log: 
,09-30 06:38:55.264  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 06:38:55.264  5693  5739 I jxcore-log: 
,09-30 06:38:55.264  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 06:38:55.264  5693  5739 I jxcore-log: 
,09-30 06:38:55.266  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start listening for advertisements'
09-30 06:38:55.266  5693  5739 I jxcore-log: 
,09-30 06:38:55.268  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start update advertising and listening'
09-30 06:38:55.268  5693  5739 I jxcore-log: 
,09-30 06:38:55.272  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliWifiInfrastructure: 'listening 40652'
09-30 06:38:55.272  5693  5739 I jxcore-log: 
,09-30 06:38:55.274  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 06:38:55.274  5693  5739 I jxcore-log: 
,09-30 06:38:55.278  5693  5739 I jxcore-log: ok 231 ThaliMobile.start was called once
09-30 06:38:55.278  5693  5739 I jxcore-log: 
,09-30 06:38:55.278  5693  5739 I jxcore-log: ok 232 ThaliMobile.start was called with 2 arguments
09-30 06:38:55.278  5693  5739 I jxcore-log: 
09-30 06:38:55.278  5693  5739 I jxcore-log: ok 233 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-30 06:38:55.278  5693  5739 I jxcore-log: 
,09-30 06:38:55.279  5693  5739 I jxcore-log: ok 234 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-30 06:38:55.279  5693  5739 I jxcore-log: 
09-30 06:38:55.279  5693  5739 I jxcore-log: ok 235 ThaliMobile.startListeningForAdvertisements was called once
09-30 06:38:55.279  5693  5739 I jxcore-log: 
09-30 06:38:55.279  5693  5739 I jxcore-log: ok 236 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-30 06:38:55.279  5693  5739 I jxcore-log: 
,09-30 06:38:55.279  5693  5739 I jxcore-log: ok 237 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-30 06:38:55.279  5693  5739 I jxcore-log: 
09-30 06:38:55.279  5693  5739 I jxcore-log: ok 238 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-30 06:38:55.279  5693  5739 I jxcore-log: 
09-30 06:38:55.279  5693  5739 I jxcore-log: ok 239 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-30 06:38:55.279  5693  5739 I jxcore-log: 
09-30 06:38:55.280  5693  5739 I jxcore-log: ok 240 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-30 06:38:55.280  5693  5739 I jxcore-log: 
09-30 06:38:55.280  5693  5739 I jxcore-log: ok 241 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 06:38:55.280  5693  5739 I jxcore-log: 
,09-30 06:38:55.280  5693  5739 I jxcore-log: ok 242 ThaliPullReplicationFromNotification.prototype.start was called once
09-30 06:38:55.280  5693  5739 I jxcore-log: 
09-30 06:38:55.280  5693  5739 I jxcore-log: ok 243 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-30 06:38:55.280  5693  5739 I jxcore-log: 
09-30 06:38:55.281  5693  5739 I jxcore-log: ok 244 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-30 06:38:55.281  5693  5739 I jxcore-log: 
09-30 06:38:55.281  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-30 06:38:55.281  5693  5739 I jxcore-log: 
,09-30 06:38:55.282  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-30 06:38:55.282  5693  5739 I jxcore-log: 
09-30 06:38:55.283  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-30 06:38:55.283  5693  5739 I jxcore-log: 
,09-30 06:38:55.285  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping advertising and listening'
09-30 06:38:55.285  5693  5739 I jxcore-log: 
,09-30 06:38:55.289  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping listening for advertisements'
09-30 06:38:55.289  5693  5739 I jxcore-log: 
,09-30 06:38:55.292  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'stopping ThaliMobile'
09-30 06:38:55.292  5693  5739 I jxcore-log: 
,09-30 06:38:55.297  5693  5739 I jxcore-log: # teardown
09-30 06:38:55.297  5693  5739 I jxcore-log: 
,09-30 06:38:55.366  5693  5739 I jxcore-log: # setup
09-30 06:38:55.366  5693  5739 I jxcore-log: 
,09-30 06:38:55.418  5693  5739 I jxcore-log: # test write
09-30 06:38:55.418  5693  5739 I jxcore-log: 
,09-30 06:38:55.601  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-30 06:38:55.601  5693  5739 I jxcore-log: 
,09-30 06:38:55.606  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-30 06:38:55.606  5693  5739 I jxcore-log: 
,09-30 06:38:55.607  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'creating express pouchdb instance'
09-30 06:38:55.607  5693  5739 I jxcore-log: 
,09-30 06:38:55.631  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-30 06:38:55.631  5693  5739 I jxcore-log: 
,09-30 06:38:55.633  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-30 06:38:55.633  5693  5739 I jxcore-log: 
,09-30 06:38:55.633  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting ThaliMobile'
09-30 06:38:55.633  5693  5739 I jxcore-log: 
,09-30 06:38:55.635  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start listening for advertisements'
09-30 06:38:55.635  5693  5739 I jxcore-log: 
,09-30 06:38:55.639  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'start update advertising and listening'
09-30 06:38:55.639  5693  5739 I jxcore-log: 
,09-30 06:38:55.645  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliWifiInfrastructure: 'listening 47882'
09-30 06:38:55.645  5693  5739 I jxcore-log: 
,09-30 06:38:55.649  5693  5739 I jxcore-log: 2016-09-30 10:38:55 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-30 06:38:55.649  5693  5739 I jxcore-log: 
,09-30 06:38:56.567  5693  5739 I jxcore-log: 2016-09-30 10:38:56 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-30 06:38:56.567  5693  5739 I jxcore-log: 
,09-30 06:38:56.595  5693  5739 I jxcore-log: 2016-09-30 10:38:56 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-30 06:38:56.595  5693  5739 I jxcore-log: 
,09-30 06:38:57.006  5693  5739 I jxcore-log: 2016-09-30 10:38:57 - ERROR thaliSendNotificationBasedOnReplication: 'Got an error on the replication change listener - {"name":"AssertionError","actual":null,"expected":true,"operator":"==","message":"If beacons werepreviously updated then there has to be a refresh timer for them.","stack":"ok@assert.js:126:1\nThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9\nPouchDBGenerator/PouchAlt.prototype.addListener/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:9"}'
09-30 06:38:57.006  5693  5739 I jxcore-log: 
,09-30 06:38:57.008  5693  5739 I jxcore-log: 2016-09-30 10:38:57 - ERROR TestsProcess: 'uncaught promise rejection, error: 'AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.', stack: 'ok@assert.js:126:1
09-30 06:38:57.008  5693  5739 I jxcore-log: ThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9
09-30 06:38:57.008  5693  5739 I jxcore-log: PouchDBGenerator/PouchAlt.prototype.addListener/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:9''
09-30 06:38:57.008  5693  5739 I jxcore-log: 
,09-30 06:38:57.009  5693  5739 I jxcore-log: 2016-09-30 10:38:57 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-30 06:38:57.009  5693  5739 I jxcore-log: 
,09-30 06:38:57.657  6039  6039 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-30 06:38:57.680  6039  6039 D AndroidRuntime: CheckJNI is OFF
,09-30 06:38:57.704  6039  6039 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-30 06:38:57.732  6039  6039 I Radio-JNI: register_android_hardware_Radio DONE
,09-30 06:38:57.748  6039  6039 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-30 06:38:57.756   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-30 06:38:57.757   927   940 I ActivityManager: Killing 5693:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-30 06:38:57.877   927  3901 I WindowState: WIN DEATH: Window{1c4cac5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-30 06:38:57.878   927  3311 D GraphicsStats: Buffer count: 2
09-30 06:38:57.878   927  3076 D WifiService: Client connection lost with reason: 4
,09-30 06:38:57.894   927   950 I art     : Starting a blocking GC Explicit
,09-30 06:38:57.912   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-30 06:38:57.912   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-30 06:38:57.913   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-30 06:38:57.913   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-30 06:38:57.913   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:38:57.913   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:38:57.913   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 06:38:57.913   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 06:38:57.913   927   940 I ActivityManager:   Force finishing activity ActivityRecord{8e9bfae u0 com.test.thalitest/.MainActivity t2}
,09-30 06:38:57.920   927   937 W ActivityManager: Spurious death for ProcessRecord{b42b3f4 0:com.test.thalitest/u0a77}, curProc for 5693: null
,09-30 06:38:57.925   927   945 W WindowManager: Attempted to add application window with unknown token Token{281d14f ActivityRecord{8e9bfae u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-30 06:38:57.925   927   945 W WindowManager: Token{281d14f ActivityRecord{8e9bfae u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{281d14f ActivityRecord{8e9bfae u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-30 06:38:57.925   927   945 W WindowManager: view not successfully added to wm, removing view
09-30 06:38:57.925   927   945 W WindowManager: Exception when adding starting window
09-30 06:38:57.925   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{4d702bf V.E...... R.....ID 0,0-0,0} not attached to window manager
09-30 06:38:57.925   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-30 06:38:57.925   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-30 06:38:57.925   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-30 06:38:57.925   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-30 06:38:57.925   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-30 06:38:57.925   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:38:57.925   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:38:57.925   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 06:38:57.925   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 06:38:57.984   927   950 I art     : Explicit concurrent mark sweep GC freed 68743(4MB) AllocSpace objects, 27(948KB) LOS objects, 33% free, 29MB/43MB, paused 1.472ms total 88.428ms
,09-30 06:38:58.003   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-30 06:38:58.005  6039  6039 I art     : System.exit called, status: 0
09-30 06:38:58.005  6039  6039 I AndroidRuntime: VM exiting with result code 0.
,09-30 06:38:58.011   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-30 06:38:58.018   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-30 06:38:58.022  5927  5927 D BluetoothMapAppObserver: onReceive
,09-30 06:38:58.022  5927  5927 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-30 06:38:58.022  3759  3759 I Keyboard.Facilitator: resetDictionaries() : en_US
09-30 06:38:58.027   927  3041 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-30 06:38:58.035  4195  4286 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-30 06:38:58.069  3866  3866 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-30 06:38:58.080  3759  6050 I Keyboard.Facilitator.DecoderInitializer: run()
,09-30 06:38:58.082  3499  6051 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-30 06:38:58.084  3672  3672 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-30 06:38:58.084  3672  3672 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-30 06:38:58.091   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-30 06:38:58.107  3759  6050 I Decoder : createOrResetDecoder
,09-30 06:38:58.109    17    17 W kworker/2:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 06:38:58.112    17    17 W kworker/2:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 06:38:58.136    17    17 W kworker/2:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 06:38:58.141  3952  6056 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-30 06:38:58.141  3952  6056 D AccountUtils: Clearing selected account for com.test.thalitest
,09-30 06:38:58.152  3672  3672 I ConfigService: onCreate
,09-30 06:38:58.153  3499  3523 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj5750FF985) - 
,09-30 06:38:58.155  3672  6058 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-30 06:38:58.155  3672  6058 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-30 06:38:58.164  3672  6058 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-30 06:38:58.166  3672  6058 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-30 06:38:58.174  3759  6050 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-30 06:38:58.196  3952  6056 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-30 06:38:58.223  3952  6056 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:38:58.223  3952  6056 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:38:58.223  3952  6056 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 06:38:58.224  3952  6056 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,--------- beginning of crash
09-30 06:38:58.240  3499  3523 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-30 06:38:58.240  3499  3523 E AndroidRuntime: Process: android.process.acore, PID: 3499
09-30 06:38:58.240  3499  3523 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 06:38:58.240  3499  3523 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 06:38:58.270  3499  3523 I Process : Sending signal. PID: 3499 SIG: 9
,09-30 06:38:58.303  3952  6064 I GMPM-SVC: App measurement is starting up
,09-30 06:38:58.306  3952  6064 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-30 06:38:58.307  3952  6064 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-30 06:38:58.511   381   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
