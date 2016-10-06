#### Test 882670588545989_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
,10-06 10:45:00.752   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-06 10:45:00.753   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
10-06 10:45:01.233  5608  5608 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-06 10:45:01.239  5608  5608 D AndroidRuntime: CheckJNI is OFF
10-06 10:45:01.268  5608  5608 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-06 10:45:01.304  5608  5608 I Radio-JNI: register_android_hardware_Radio DONE
10-06 10:45:01.321  5608  5608 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-06 10:45:01.327   928  3744 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-06 10:45:01.379   928  3744 I ActivityManager: Start proc 5617:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-06 10:45:01.383  5608  5608 D AndroidRuntime: Shutting down VM
,10-06 10:45:01.722   928  3155 I WindowManager: Screenshot max retries 4 of Token{ceb10be ActivityRecord{ae1ab79 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{70850b1 u0 Starting com.test.thalitest} drawState=4
,10-06 10:45:01.807  5617  5617 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-06 10:45:01.844  5617  5617 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-06 10:45:01.866  5617  5617 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 147-164)
,10-06 10:45:01.867  5617  5617 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-06 10:45:01.884  5617  5617 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3129abb}
,10-06 10:45:01.884  5617  5617 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-06 10:45:01.884  5617  5617 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-06 10:45:01.888  5617  5617 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-06 10:45:01.889  5617  5617 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-06 10:45:01.918  5617  5617 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-06 10:45:01.926   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-06 10:45:01.927  5617  5617 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-06 10:45:01.927  5617  5617 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-06 10:45:01.927  5617  5617 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-06 10:45:01.927  5617  5617 I Adreno  : Build Date                       : 12/06/15
10-06 10:45:01.927  5617  5617 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-06 10:45:01.927  5617  5617 I Adreno  : Local Branch                     : mybranch17112971
10-06 10:45:01.927  5617  5617 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-06 10:45:01.927  5617  5617 I Adreno  : Remote Branch                    : NONE
10-06 10:45:01.927  5617  5617 I Adreno  : Reconstruct Branch               : NOTHING
,10-06 10:45:01.958   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@45e9c9c:true
,10-06 10:45:01.991  2941  2941 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[29358]" dev="sockfs" ino=29358 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-06 10:45:01.991  2941  2941 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[29358]" dev="sockfs" ino=29358 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-06 10:45:02.001  5617  5617 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-06 10:45:02.011  5617  5617 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-06 10:45:02.034  2941  2941 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33948]" dev="sockfs" ino=33948 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-06 10:45:02.036  5617  5654 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-06 10:45:02.034  2941  2941 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33948]" dev="sockfs" ino=33948 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-06 10:45:02.038  3769  3769 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14855]" dev="sockfs" ino=14855 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-06 10:45:02.038  3769  3769 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14855]" dev="sockfs" ino=14855 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-06 10:45:02.042  5617  5641 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-06 10:45:02.065  5617  5654 I OpenGLRenderer: Initialized EGL, version 1.4
,10-06 10:45:02.135   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +410ms (total +786ms)
,10-06 10:45:02.183  5617  5617 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5617
,10-06 10:45:02.308  5617  5617 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-06 10:45:02.393  5617  5656 D jxcore_app_log: JniHelper::setJavaVM(0xf4f3c000), pthread_self() = -584845008
,10-06 10:45:02.397  5617  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-06 10:45:02.397  5617  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-06 10:45:02.397  5617  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-06 10:45:02.397  5617  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-06 10:45:02.397  5617  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-06 10:45:02.397  5617  5656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87bad29 added. We now have 1 listener(s)
,10-06 10:45:02.400  5617  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-06 10:45:02.400  5617  5656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:45:02.401  5617  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:45:02.401  5617  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-06 10:45:02.403  5617  5656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a4b1dc added. We now have 1 listener(s)
10-06 10:45:02.403  5617  5656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-06 10:45:02.407   928  2969 D WifiService: New client listening to asynchronous messages
10-06 10:45:02.408  5617  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-06 10:45:02.408  5617  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-06 10:45:02.408  5617  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-06 10:45:02.408  5617  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-06 10:45:02.408  5617  5656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-06 10:45:02.409  5617  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:45:02.410  5617  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-06 10:45:02.413  5617  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-06 10:45:02.413  5617  5656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:45:02.413  5617  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:02.413  5617  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:02.413  5617  5656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:02.413  5617  5656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:02.413  5617  5656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:02.413  5617  5656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:02.413  5617  5656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:02.414  5617  5656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-06 10:45:02.414  5617  5656 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:45:02.414  5617  5656 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-06 10:45:02.509  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:02.513  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:02.515  5617  5617 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-06 10:45:02.704  5617  5663 W jxcore-log: Initializing JXcore engine
,10-06 10:45:02.704  5617  5663 W jxcore-log: JXcore engine is ready
,10-06 10:45:02.728  5663  5663 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12962 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
10-06 10:45:02.728  5663  5663 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15476]" dev="sockfs" ino=15476 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-06 10:45:02.728  5663  5663 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-06 10:45:02.728  5663  5663 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33483]" dev="sockfs" ino=33483 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-06 10:45:02.737  5617  5663 W jxcore-log: Starting JXcore engine
,10-06 10:45:02.796  5617  5663 W jxcore-log: Platform android
10-06 10:45:02.796  5617  5663 W jxcore-log: 
,10-06 10:45:02.796  5617  5663 W jxcore-log: Process ARCH arm
10-06 10:45:02.796  5617  5663 W jxcore-log: 
,10-06 10:45:02.895  5617  5663 I jxcore-log: JXcore Cordova bridge is ready!
10-06 10:45:02.895  5617  5663 I jxcore-log: 
,10-06 10:45:02.895  5617  5663 W jxcore-log: JXcore engine is started
,10-06 10:45:02.904  5617  5656 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-06 10:45:02.910  5617  5617 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-06 10:45:06.700   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-06 10:45:09.729   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-06 10:45:10.754   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:11.755   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:12.756   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:12.773  5617  5663 I jxcore-log: 2016-10-06 14:45:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-06 10:45:12.773  5617  5663 I jxcore-log: 
,10-06 10:45:12.775  5617  5663 I jxcore-log: 2016-10-06 14:45:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-06 10:45:12.775  5617  5663 I jxcore-log: 
,10-06 10:45:12.779  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:45:12.779  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:12.779  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:12.779  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:12.779  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:12.779  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:12.779  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:12.779  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-06 10:45:12.780  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-06 10:45:12.782  5617  5663 I jxcore-log: 2016-10-06 14:45:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-06 10:45:12.782  5617  5663 I jxcore-log: 
,10-06 10:45:12.783  5617  5663 I jxcore-log: 2016-10-06 14:45:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-06 10:45:12.783  5617  5663 I jxcore-log: 
,10-06 10:45:13.041  5617  5663 I jxcore-log: 2016-10-06 14:45:13 - DEBUG UnitTest_app: 'Running unit tests'
10-06 10:45:13.041  5617  5663 I jxcore-log: 
,10-06 10:45:13.042  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-06 10:45:13.042  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d41c833 added. We now have 2 listener(s)
10-06 10:45:13.043  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:45:13.043  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:45:13.043  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-06 10:45:13.043  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:45:13.043  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a73f7f0 added. We now have 2 listener(s)
,10-06 10:45:13.043  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:45:13.044  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-06 10:45:13.046  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-06 10:45:13.049  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:45:13.049  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:13.049  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:13.049  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:13.049  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:13.049  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:13.049  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:13.049  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:13.050  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:13.050  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:45:13.050  5617  5663 D executeNativeTests: Running unit tests
10-06 10:45:13.055  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:13.063  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:13.092  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-06 10:45:13.092  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e added. We now have 3 listener(s)
10-06 10:45:13.092  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:45:13.092  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-06 10:45:13.092  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-06 10:45:13.093  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:45:13.093  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f added. We now have 3 listener(s)
,10-06 10:45:13.093  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:45:13.093  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-06 10:45:13.094  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:45:13.097  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:45:13.097  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:13.097  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:13.097  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:13.097  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:13.097  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:13.097  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:13.097  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:13.098  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:13.098  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-06 10:45:13.099  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-06 10:45:13.099  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-06 10:45:13.099  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-06 10:45:13.099  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-06 10:45:13.100  5617  5663 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-06 10:45:13.100  5617  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-06 10:45:13.100  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-06 10:45:13.100  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-06 10:45:13.100  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-06 10:45:13.100  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-06 10:45:13.100  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:13.101  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:13.101  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:13.101  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:13.101  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:13.101  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:45:13.102  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:13.102  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:45:13.102  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e removed from the list
10-06 10:45:13.102  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:13.102  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f removed from the list
10-06 10:45:13.103  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:13.108  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:13.109  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:13.109  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:13.109  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:13.110  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:13.110  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-06 10:45:13.110  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:13.110  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:13.110  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
,10-06 10:45:13.111  5617  5663 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-06 10:45:13.111  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:13.111  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:13.111  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:13.111  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-06 10:45:13.111  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:13.111  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:13.111  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:13.112  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
,10-06 10:45:13.112  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:13.112  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:13.112  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:13.112  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:13.112  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:13.112  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:13.112  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:13.112  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-06 10:45:13.112  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:13.112  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:13.112  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-06 10:45:13.115  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-06 10:45:13.116  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-06 10:45:13.116  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-06 10:45:13.116  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-06 10:45:13.116  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:13.116  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_,STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:13.116  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:13.116  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:13.116  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:13.116  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:13.116  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:13.116  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:13.116  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:13.116  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:13.116  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:13.116  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:13.116  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:13.116  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:13.116  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:13.117  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:13.117  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:13.117  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:13.117  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:13.117  5617  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-06 10:45:13.118  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:45:13.120  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:45:13.120  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:13.120  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:13.120  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:13.120  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:13.120  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:13.120  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:13.120  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:13.121  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:13.121  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:45:13.121  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:45:13.121  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-06 10:45:13.122  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-06 10:45:13.122  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:45:13.122  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-06 10:45:13.124  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-06 10:45:13.124  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-06 10:45:13.125  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:13.129  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:13.130  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-06 10:45:13.132  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-06 10:45:13.133  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-06 10:45:13.136  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-06 10:45:13.138  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-06 10:45:13.139  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-06 10:45:13.139  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-06 10:45:13.139  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-06 10:45:13.139  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-06 10:45:13.140  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-06 10:45:13.140  5617  5663 D BluetoothAdapter: STATE_ON
10-06 10:45:13.144  4582  4852 D BtGatt.GattService: registerClient() - UUID=53c380ff-9e8a-4f1a-9f82-c2cf0a9ef469
10-06 10:45:13.145  4582  4667 D BtGatt.GattService: onClientRegistered() - UUID=53c380ff-9e8a-4f1a-9f82-c2cf0a9ef469, clientIf=5
10-06 10:45:13.146  5617  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-06 10:45:13.147  4582  4603 D BtGatt.GattService: start scan with filters
10-06 10:45:13.151  4582  4671 D BtGatt.ScanManager: handling starting scan
10-06 10:45:13.151  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-06 10:45:13.151  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-06 10:45:13.151  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:45:13.151  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-06 10:45:13.151  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-06 10:45:13.151  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-06 10:45:13.151  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-06 10:45:13.152  4582  4671 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:45:13.152  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-06 10:45:13.153  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-06 10:45:13.153  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-06 10:45:13.153  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-06 10:45:13.154  5617  5663 I io.jxcore.node.ConnectionHelper: start: OK
10-06 10:45:13.161  4582  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-06 10:45:13.161  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:13.162  4582  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-06 10:45:13.169  4582  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-06 10:45:13.169  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:13.170  4582  4671 D BtGatt.ScanManager: Starting BLE batch scan
10-06 10:45:13.170  4582  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-06 10:45:13.181  4582  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-06 10:45:13.181  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:13.187  4582  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-06 10:45:13.187  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:45:13.655  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-06 10:45:13.655  5617  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:45:13.656  5617  5617 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-06 10:45:13.758   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:14.759   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:15.760   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-06 10:45:18.158  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:45:18.159  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:18.159  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-06 10:45:18.159  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:18.159  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-06 10:45:18.159  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:18.159  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-06 10:45:18.159  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-06 10:45:18.159  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-06 10:45:18.160  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-06 10:45:18.160  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-06 10:45:18.160  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-06 10:45:18.161  5617  5663 D BluetoothAdapter: STATE_ON
,10-06 10:45:18.162  4582  4852 D BtGatt.GattService: stopScan() - queue size =1
10-06 10:45:18.163  4582  4603 D BtGatt.GattService: unregisterClient() - clientIf=5
10-06 10:45:18.164  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-06 10:45:18.165  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-06 10:45:18.165  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-06 10:45:18.165  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:45:18.165  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-06 10:45:18.165  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-06 10:45:18.166  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-06 10:45:18.166  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-06 10:45:18.168  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:45:18.169  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-06 10:45:18.169  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-06 10:45:18.170  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-06 10:45:18.170  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-06 10:45:18.171  4582  4582 D BtGatt.ScanManager: awakened up at time 236469
,10-06 10:45:18.173  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:45:18.176  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-06 10:45:18.176  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:18.176  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:18.176  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:45:18.176  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:45:18.177  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:45:18.177  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:18.177  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
,10-06 10:45:18.177  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:18.177  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:18.177  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,10-06 10:45:18.177  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:18.180  4582  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-06 10:45:18.180  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:18.181  4582  4671 D BtGatt.ScanManager: stopping BLe Batch
,10-06 10:45:18.191  4582  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-06 10:45:18.191  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:45:18.191  4582  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-06 10:45:18.215  4582  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
10-06 10:45:18.215  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:45:18.216  4582  4667 D BtGatt.GattService: current time is 236514434113
,10-06 10:45:18.217  4582  4667 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -79, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -90, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-06 10:45:18.218  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-06 10:45:18.220  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-06 10:45:18.220  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-06 10:45:18.220  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-06 10:45:18.221  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-06 10:45:18.221  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-06 10:45:18.678  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-06 10:45:20.761   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:21.762   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:22.763   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:23.179  5617  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-06 10:45:23.184  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-06 10:45:23.196  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:45:23.196  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:23.196  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:23.196  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:23.196  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:23.196  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:23.196  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:23.196  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-06 10:45:23.202  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-06 10:45:23.202  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:45:23.203  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:45:23.203  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-06 10:45:23.203  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-06 10:45:23.203  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:45:23.203  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-06 10:45:23.207  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:23.211  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-06 10:45:23.211  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-06 10:45:23.214  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:23.219  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-06 10:45:23.220  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-06 10:45:23.221  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-06 10:45:23.227  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-06 10:45:23.227  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-06 10:45:23.227  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-06 10:45:23.228  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-06 10:45:23.228  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-06 10:45:23.229  5617  5663 D BluetoothAdapter: STATE_ON
,10-06 10:45:23.233  4582  4603 D BtGatt.GattService: registerClient() - UUID=9c1b90de-6831-43ef-b3d1-83e8a5db3f2b
10-06 10:45:23.234  4582  4667 D BtGatt.GattService: onClientRegistered() - UUID=9c1b90de-6831-43ef-b3d1-83e8a5db3f2b, clientIf=5
,10-06 10:45:23.234  5617  5627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-06 10:45:23.235  4582  4600 D BtGatt.GattService: start scan with filters
,10-06 10:45:23.239  4582  4671 D BtGatt.ScanManager: handling starting scan
10-06 10:45:23.240  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-06 10:45:23.240  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-06 10:45:23.241  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:45:23.241  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-06 10:45:23.241  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-06 10:45:23.241  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-06 10:45:23.241  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-06 10:45:23.246  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-06 10:45:23.246  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-06 10:45:23.247  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-06 10:45:23.249  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-06 10:45:23.249  4582  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-06 10:45:23.250  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:23.250  4582  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-06 10:45:23.254  5617  5663 I io.jxcore.node.ConnectionHelper: start: OK
10-06 10:45:23.259  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:45:23.259  5617  5663 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-06 10:45:23.259  4582  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-06 10:45:23.259  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:23.259  4582  4671 D BtGatt.ScanManager: Starting BLE batch scan
10-06 10:45:23.259  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:23.259  4582  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-06 10:45:23.259  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-06 10:45:23.259  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:23.260  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-06 10:45:23.260  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:23.260  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-06 10:45:23.260  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-06 10:45:23.260  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-06 10:45:23.260  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-06 10:45:23.260  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-06 10:45:23.260  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-06 10:45:23.261  5617  5663 D BluetoothAdapter: STATE_ON
10-06 10:45:23.262  4582  4603 D BtGatt.GattService: stopScan() - queue size =1
10-06 10:45:23.263  4582  4832 D BtGatt.GattService: unregisterClient() - clientIf=5
10-06 10:45:23.264  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-06 10:45:23.264  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-06 10:45:23.264  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-06 10:45:23.264  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:45:23.264  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-06 10:45:23.264  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-06 10:45:23.264  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-06 10:45:23.264  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-06 10:45:23.267  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:45:23.267  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-06 10:45:23.267  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-06 10:45:23.267  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-06 10:45:23.267  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-06 10:45:23.268  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:45:23.269  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:23.269  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:23.269  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:45:23.269  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:45:23.269  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:23.269  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:45:23.269  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:23.269  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-06 10:45:23.269  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:23.269  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:23.269  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:23.269  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:23.270  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:23.270  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:23.272  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:23.272  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:23.272  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:23.272  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:23.273  5617  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-06 10:45:23.274  4582  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-06 10:45:23.274  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:23.275  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:45:23.281  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:45:23.281  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:23.281  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:23.281  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:23.281  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:23.281  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:23.281  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:23.281  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-06 10:45:23.281  4582  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-06 10:45:23.281  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:45:23.284  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-06 10:45:23.284  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:45:23.284  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:45:23.285  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-06 10:45:23.285  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-06 10:45:23.286  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:45:23.286  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-06 10:45:23.289  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:23.289  4582  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-06 10:45:23.290  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:23.290  4582  4671 D BtGatt.ScanManager: stopping BLe Batch
10-06 10:45:23.291  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-06 10:45:23.291  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-06 10:45:23.292  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:23.294  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-06 10:45:23.295  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-06 10:45:23.295  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-06 10:45:23.296  4582  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-06 10:45:23.296  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:45:23.296  4582  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-06 10:45:23.299  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-06 10:45:23.299  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-06 10:45:23.299  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-06 10:45:23.299  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-06 10:45:23.299  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-06 10:45:23.300  5617  5663 D BluetoothAdapter: STATE_ON
10-06 10:45:23.302  4582  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-06 10:45:23.302  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:45:23.303  4582  4603 D BtGatt.GattService: registerClient() - UUID=9fba4b35-c9c2-4bbf-be76-47c2d02ba3b6
,10-06 10:45:23.303  4582  4667 D BtGatt.GattService: onClientRegistered() - UUID=9fba4b35-c9c2-4bbf-be76-47c2d02ba3b6, clientIf=5
10-06 10:45:23.303  5617  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-06 10:45:23.304  4582  4832 D BtGatt.GattService: start scan with filters
,10-06 10:45:23.306  4582  4671 D BtGatt.ScanManager: handling starting scan
10-06 10:45:23.307  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-06 10:45:23.307  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-06 10:45:23.307  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:45:23.307  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-06 10:45:23.307  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-06 10:45:23.307  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-06 10:45:23.307  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-06 10:45:23.310  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-06 10:45:23.310  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-06 10:45:23.310  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-06 10:45:23.311  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-06 10:45:23.312  4582  4667 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-06 10:45:23.312  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:23.313  4582  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-06 10:45:23.314  5617  5663 I io.jxcore.node.ConnectionHelper: start: OK
,10-06 10:45:23.318  4582  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-06 10:45:23.318  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:23.318  4582  4671 D BtGatt.ScanManager: Starting BLE batch scan
10-06 10:45:23.318  4582  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-06 10:45:23.328  4582  4667 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-06 10:45:23.328  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:45:23.333  4582  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-06 10:45:23.334  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:45:23.765   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:23.812  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-06 10:45:23.812  5617  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:45:23.812  5617  5617 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-06 10:45:24.766   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:24.842   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-06 10:45:24.846   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-06 10:45:25.766   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-06 10:45:27.871   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-06 10:45:27.876   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-06 10:45:28.314  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:45:28.314  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:28.315  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-06 10:45:28.315  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:28.315  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-06 10:45:28.315  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:28.316  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-06 10:45:28.316  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-06 10:45:28.316  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-06 10:45:28.316  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-06 10:45:28.316  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-06 10:45:28.316  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-06 10:45:28.318  5617  5663 D BluetoothAdapter: STATE_ON
,10-06 10:45:28.321  4582  4603 D BtGatt.GattService: stopScan() - queue size =1
,10-06 10:45:28.323  4582  4600 D BtGatt.GattService: unregisterClient() - clientIf=5
10-06 10:45:28.324  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-06 10:45:28.324  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-06 10:45:28.324  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-06 10:45:28.325  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:45:28.325  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-06 10:45:28.325  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-06 10:45:28.325  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-06 10:45:28.325  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-06 10:45:28.329  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:45:28.329  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-06 10:45:28.330  4582  4582 D BtGatt.ScanManager: awakened up at time 246628
10-06 10:45:28.330  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-06 10:45:28.330  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-06 10:45:28.330  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-06 10:45:28.331  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:45:28.333  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:45:28.333  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:45:28.333  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:45:28.335  4582  4667 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-06 10:45:28.335  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:28.335  4582  4671 D BtGatt.ScanManager: stopping BLe Batch
,10-06 10:45:28.341  4582  4667 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-06 10:45:28.341  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:28.342  4582  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-06 10:45:28.360  4582  4667 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-06 10:45:28.360  4582  4667 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:45:28.360  4582  4667 D BtGatt.GattService: current time is 246659155814
10-06 10:45:28.361  4582  4667 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -78, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-06 10:45:28.361  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-06 10:45:28.361  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-06 10:45:28.361  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-06 10:45:28.361  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-06 10:45:28.362  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-06 10:45:28.362  4582  4667 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-06 10:45:28.834  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-06 10:45:28.834  5617  5617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:28.834  5617  5617 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-06 10:45:33.335  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:45:33.335  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.335  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.336  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.336  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.336  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:45:33.336  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-06 10:45:33.336  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.336  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.337  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.337  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.337  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:33.338  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.339  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.342  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.342  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.342  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.343  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
,10-06 10:45:33.346  5617  5663 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-06 10:45:33.349  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:45:33.349  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.349  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.349  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.349  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.350  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.350  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-06 10:45:33.350  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.350  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.350  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.350  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.350  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.351  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.351  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.351  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:33.354  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.354  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.354  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.354  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
,10-06 10:45:33.356  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-06 10:45:33.357  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:45:33.357  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.357  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.357  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.357  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.358  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.358  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-06 10:45:33.358  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.358  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.358  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.358  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.358  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.359  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.359  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:33.359  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.362  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.362  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.362  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.362  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
,10-06 10:45:33.363  5617  5663 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-06 10:45:33.364  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:33.364  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.364  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-06 10:45:33.364  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.364  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.364  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.365  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:33.365  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.365  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:45:33.365  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.365  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.365  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.365  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.366  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.366  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:33.368  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.368  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.368  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.369  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.370  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-06 10:45:33.371  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:45:33.371  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.371  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.371  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.372  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.372  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.372  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:33.372  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.372  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:45:33.372  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.372  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.373  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.373  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.373  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.373  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:33.375  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-06 10:45:33.375  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.375  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.376  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.377  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-06 10:45:33.377  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-06 10:45:33.377  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-06 10:45:33.378  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-06 10:45:33.378  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-06 10:45:33.378  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-06 10:45:33.378  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-06 10:45:33.379  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-06 10:45:33.379  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-06 10:45:33.379  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:33.379  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.379  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.379  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.379  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:33.380  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.380  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:33.380  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.380  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.380  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.380  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.380  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.380  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.380  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.380  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.382  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.382  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.383  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.383  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.384  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-06 10:45:33.384  5617  5663 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,10-06 10:45:33.385  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-06 10:45:33.390  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-06 10:45:33.391  5617  5663 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-06 10:45:33.391  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-06 10:45:33.391  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,10-06 10:45:33.391  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-06 10:45:33.391  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,10-06 10:45:33.393  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-06 10:45:33.394  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-06 10:45:33.394  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-06 10:45:33.394  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-06 10:45:33.394  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-06 10:45:33.394  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-06 10:45:33.394  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,10-06 10:45:33.394  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-06 10:45:33.394  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-06 10:45:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-06 10:45:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-06 10:45:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-06 10:45:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-06 10:45:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-06 10:45:33.395  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-06 10:45:33.396  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-06 10:45:33.396  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-06 10:45:33.396  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-06 10:45:33.396  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-06 10:45:33.397  5617  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-06 10:45:33.397  5617  5663 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-06 10:45:33.397  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-06 10:45:33.397  5617  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-06 10:45:33.397  5617  5663 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,10-06 10:45:33.398  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-06 10:45:33.398  5617  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-06 10:45:33.398  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-06 10:45:33.403  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-06 10:45:33.404  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-06 10:45:33.404  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,10-06 10:45:33.408  4600  4600 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32386]" dev="sockfs" ino=32386 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-06 10:45:33.411  4600  4600 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32386]" dev="sockfs" ino=32386 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-06 10:45:33.406  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-06 10:45:33.406  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-06 10:45:33.406  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-06 10:45:33.406  5617  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-06 10:45:33.406  5617  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-06 10:45:33.406  5617  5663 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,10-06 10:45:33.406  5617  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-06 10:45:33.406  5617  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-06 10:45:33.406  5617  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-06 10:45:33.408  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:33.408  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.408  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.408  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.408  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.408  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.408  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:33.408  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-06 10:45:33.409  5617  5664 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-06 10:45:33.409  5617  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-06 10:45:33.409  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.409  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.409  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.409  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.410  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.410  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.410  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.410  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.410  5617  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
10-06 10:45:33.410  5617  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
10-06 10:45:33.410  5617  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
10-06 10:45:33.411  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.411  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.411  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.411  5617  5663 E org.thaliproject.,p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.412  5617  5664 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-06 10:45:33.412  5617  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-06 10:45:33.412  5617  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
10-06 10:45:33.413  5617  5663 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-06 10:45:33.413  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:33.414  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.414  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.414  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.414  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.414  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.414  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:33.414  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.414  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.414  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.414  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.414  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.414  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.414  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.414  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.416  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.417  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-06 10:45:33.417  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.417  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.418  5617  5663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-06 10:45:33.418  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:33.418  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.418  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.418  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.418  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.419  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.419  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:33.419  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.419  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.419  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.419  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.419  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.419  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.419  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:33.419  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.421  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.421  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.421  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.421  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.422  5617  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,10-06 10:45:33.422  5617  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-06 10:45:33.422  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-06 10:45:33.422  5617  5663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,10-06 10:45:33.422  5617  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-06 10:45:33.422  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-06 10:45:33.422  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-06 10:45:33.422  5617  5663 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-06 10:45:33.422  5617  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-06 10:45:33.422  5617  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-06 10:45:33.423  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-06 10:45:33.423  5617  5663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-06 10:45:33.423  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:33.423  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:33.423  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:33.423  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.423  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.423  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:33.423  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:33.423  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.423  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.423  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.423  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.423  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.423  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.424  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.424  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:33.425  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:33.425  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:33.425  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.425  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.425  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:33.425  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.425  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:33.426  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:33.426  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:33.426  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:33.426  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:33.426  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:33.426  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:33.426  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:35.767   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:36.770   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:37.771   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:38.427  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:45:38.427  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
,10-06 10:45:38.427  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:38.427  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:38.427  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:38.428  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:38.428  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
,10-06 10:45:38.428  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:38.428  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-06 10:45:38.428  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:38.429  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-06 10:45:38.429  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.429  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:38.429  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:38.430  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
,10-06 10:45:38.430  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:38.430  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.430  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:38.431  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.431  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.431  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.432  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.435  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:38.436  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-06 10:45:38.436  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:38.437  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
,10-06 10:45:38.442  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-06 10:45:38.443  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-06 10:45:38.447  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-06 10:45:38.449  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-06 10:45:38.449  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-06 10:45:38.449  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-06 10:45:38.449  5617  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-06 10:45:38.449  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-06 10:45:38.449  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-06 10:45:38.449  5617  5617 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-06 10:45:38.450  5617  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-06 10:45:38.450  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:38.451  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-06 10:45:38.451  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-06 10:45:38.451  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-06 10:45:38.451  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.451  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-06 10:45:38.451  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-06 10:45:38.451  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:38.451  5617  5617 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-06 10:45:38.451  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:38.451  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-06 10:45:38.452  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-06 10:45:38.452  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-06 10:45:38.452  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:38.452  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:38.451  4832  4832 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33528]" dev="sockfs" ino=33528 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-06 10:45:38.455  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:45:38.455  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.455  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-06 10:45:38.455  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:38.455  5617  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-06 10:45:38.455  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:45:38.455  5617  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-06 10:45:38.455  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:38.455  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:38.455  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-06 10:45:38.451  4832  4832 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33528]" dev="sockfs" ino=33528 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-06 10:45:38.455  5617  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-06 10:45:38.455  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:38.455  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.455  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.455  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-06 10:45:38.456  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:38.456  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:45:38.456  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.456  5617  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-06 10:45:38.456  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:38.456  5617  5617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:38.456  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.456  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.456  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.456  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:38.458  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:38.458  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:38.458  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:38.458  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
,10-06 10:45:38.460  5617  5663 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-06 10:45:38.460  5617  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-06 10:45:38.460  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-06 10:45:38.461  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-06 10:45:38.461  5617  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-06 10:45:38.461  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:45:38.461  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:38.461  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:38.461  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-06 10:45:38.461  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.461  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.461  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:38.462  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:38.462  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:45:38.462  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.462  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:38.462  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.462  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.462  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.462  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.464  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:38.464  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-06 10:45:38.464  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:38.464  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.469  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:38.469  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:38.469  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:38.469  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:38.469  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.469  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.469  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:38.469  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
,10-06 10:45:38.469  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:38.469  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.469  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:38.469  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.469  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.469  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.469  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.470  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:38.470  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:38.470  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:45:38.471  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.472  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:45:38.472  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:45:38.472  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:45:38.472  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:45:38.472  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.472  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:38.472  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:45:38.472  5617  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6f689e not in the list
10-06 10:45:38.472  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:38.472  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.472  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:38.472  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.472  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.472  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:45:38.472  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:38.473  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:45:38.473  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:45:38.473  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:45:38.474  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@583df7f not in the list
10-06 10:45:38.475  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-06 10:45:38.475  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-06 10:45:38.475  5617  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-06 10:45:38.475  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-06 10:45:38.475  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-06 10:45:38.475  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-06 10:45:38.477  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-06 10:45:38.477  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-06 10:45:38.479  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-06 10:45:38.479  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-06 10:45:38.479  5617  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-06 10:45:38.479  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-06 10:45:38.479  5617  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-06 10:45:38.479  5617  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-06 10:45:38.480  5617  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-06 10:45:38.480  5617  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-06 10:45:38.480  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-06 10:45:38.480  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-06 10:45:38.480  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,10-06 10:45:38.481  5617  5663 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-06 10:45:38.482  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-06 10:45:38.482  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8224849 added. We now have 3 listener(s)
10-06 10:45:38.482  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:45:38.483  5617  5663 D BluetoothAdapter: enable(): BT is already enabled..!
10-06 10:45:38.483   928  3741 D WifiService: setWifiEnabled: true pid=5617, uid=10077
10-06 10:45:38.484   928  3741 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-06 10:45:38.538  4582  4808 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-06 10:45:38.539  4582  4830 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-06 10:45:38.772   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:38.956  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-06 10:45:39.773   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:40.773   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-06 10:45:41.930   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-06 10:45:43.489  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-06 10:45:43.489  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a15354e added. We now have 4 listener(s)
10-06 10:45:43.490  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-06 10:45:43.502  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:45:43.502  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a15354e removed from the list
,10-06 10:45:43.502  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:45:43.503  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:43.503  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:45:43.505  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-06 10:45:43.505  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@999a66f added. We now have 4 listener(s)
10-06 10:45:43.505  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:45:43.508  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:45:43.509  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@999a66f removed from the list
10-06 10:45:43.509  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,10-06 10:45:43.509  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:45:43.509  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:45:43.511  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-06 10:45:43.511  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ffbdf7c added. We now have 4 listener(s)
10-06 10:45:43.512  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:45:43.515   928  3769 D WifiService: setWifiEnabled: false pid=5617, uid=10077
10-06 10:45:43.515   928  3769 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-06 10:45:43.519   928  2959 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-06 10:45:43.519   928  2959 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-06 10:45:43.520   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-06 10:45:43.520   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-06 10:45:43.525  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-06 10:45:43.526  4582  4663 D BluetoothAdapterState: Current state: ON, message: 23
10-06 10:45:43.528  4582  4663 D BluetoothAdapterProperties: Setting state to 13
10-06 10:45:43.529  4582  4663 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-06 10:45:43.529  4582  4663 D BluetoothAdapterProperties: onBluetoothDisable()
,10-06 10:45:43.533  4582  4663 I BluetoothAdapterState: Entering PendingCommandState
,10-06 10:45:43.534  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.534  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:45:43.534  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.534  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.534  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:43.534  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.534  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:43.534  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:43.534  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:43.535  4582  4667 D BluetoothAdapterProperties: Scan Mode:20
10-06 10:45:43.535  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-06 10:45:43.535  4582  4663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-06 10:45:43.535  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-06 10:45:43.535  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:45:43.537  4582  4582 D HeadsetService: Received stop request...Stopping profile...
10-06 10:45:43.538  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.539   928  5359 D DhcpClient: Clearing IP address
10-06 10:45:43.539   509   923 D CommandListener: Clearing all IP addresses on wlan0
10-06 10:45:43.541  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:43.542   509   923 D CommandListener: Setting iface cfg
,10-06 10:45:43.543   928   928 D BluetoothHeadset: Proxy object disconnected
,10-06 10:45:43.543   928   928 D BluetoothHeadset: Proxy object disconnected
10-06 10:45:43.543   928   928 D BluetoothHeadset: Proxy object disconnected
10-06 10:45:43.543  3118  3132 D BluetoothHeadset: Proxy object disconnected
10-06 10:45:43.543  4582  4582 D A2dpService: Received stop request...Stopping profile...
10-06 10:45:43.543  3776  3802 D BluetoothHeadset: Proxy object disconnected
10-06 10:45:43.544  4582  4835 D A2dpStateMachine: Exit Disconnected: -1
10-06 10:45:43.544  3578  5415 V NativeCrypto: Read error: ssl=0x7f6529b800: I/O error during system call, Connection timed out
10-06 10:45:43.545  3118  3118 D HeadsetProfile: Bluetooth service disconnected
10-06 10:45:43.545  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.545   928  5360 D DhcpClient: Receive thread stopped
10-06 10:45:43.546  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:43.546  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.546  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.546  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:43.546  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.546  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:43.546  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:43.546  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:43.546   928   928 D BluetoothA2dp: Proxy object disconnected
10-06 10:45:43.546  3118  3118 D BluetoothA2dp: Proxy object disconnected
10-06 10:45:43.547  4582  4582 D HidService: Received stop request...Stopping profile...
10-06 10:45:43.547  4582  4582 D HidService: Stopping Bluetooth HidService
10-06 10:45:43.548  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.548  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:43.549  3118  3118 D BluetoothInputDevice: Proxy object disconnected
10-06 10:45:43.549  3118  3118 D HidProfile: Bluetooth service disconnected
10-06 10:45:43.550  4582  4582 D HealthService: Received stop request...Stopping profile...
10-06 10:45:43.551  4582  4582 V BluetoothAdapterState: isTurningOff()=true
10-06 10:45:43.551  4582  4582 V BluetoothAdapterState: isTurningOn()=false
10-06 10:45:43.552  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.552  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:43.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:43.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:43.552  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:43.552  5617  5617 V io.jxcore.node.ConnectivityMonitor,:     - active network type is Wi-Fi: true
10-06 10:45:43.552  4582  4582 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:43.553  4582  4582 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:43.554  4582  4582 D PanService: Received stop request...Stopping profile...
10-06 10:45:43.554  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.554  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:43.555  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-06 10:45:43.555  3118  3118 D PanProfile: Bluetooth service disconnected
10-06 10:45:43.555  3578  5415 V NativeCrypto: SSL shutdown failed: ssl=0x7f6529b800: I/O error during system call, Broken pipe
10-06 10:45:43.556  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.557   928  3418 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-06 10:45:43.557   928  5357 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-06 10:45:43.558  4582  4582 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-06 10:45:43.558  4582  4582 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-06 10:45:43.558  4582  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:45:43.558  4582  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:45:43.559  4582  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:45:43.559  4582  4582 V BluetoothAdapterState: isTurningOff()=true
10-06 10:45:43.559  4582  4582 V BluetoothAdapterState: isTurningOn()=false
10-06 10:45:43.559  4582  4582 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:43.559  4582  4582 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:43.559  4582  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-06 10:45:43.559  4582  4667 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-06 10:45:43.560  4582  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:45:43.560  4582  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:45:43.560  4582  4582 V BluetoothAdapterState: isTurningOff()=true
10-06 10:45:43.560  4582  4582 V BluetoothAdapterState: isTurningOn()=false
10-06 10:45:43.560  4582  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-06 10:45:43.560  4582  4808 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-06 10:45:43.560  4582  4808 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-06 10:45:43.560  4582  4808 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-06 10:45:43.560  4582  4808 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-06 10:45:43.560  4582  4582 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:43.560  4582  4582 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:43.561  4582  4582 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-06 10:45:43.561  4582  4667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-06 10:45:43.561  4582  4582 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-06 10:45:43.562   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-06 10:45:43.562   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-06 10:45:43.562  4582  4582 D BluetoothMapService: Received stop request..,.Stopping profile...
10-06 10:45:43.562  4582  4582 D BluetoothMapService: stop()
10-06 10:45:43.562   928  5357 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-06 10:45:43.563  4582  4582 D BluetoothMapAppObserver: deinitObservers()
10-06 10:45:43.563  4582  4582 D BluetoothMapAppObserver: removeReceiver()
10-06 10:45:43.564   536   536 E Parcel  : Reading a NULL string not supported here.
10-06 10:45:43.567   928   928 D RttService: SCAN_AVAILABLE : 1
10-06 10:45:43.567   928  3074 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-06 10:45:43.568  4582  4582 V BluetoothAdapterState: isTurningOff()=true
10-06 10:45:43.568  4582  4582 V BluetoothAdapterState: isTurningOn()=false
10-06 10:45:43.569  4582  4582 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:43.569  4582  4582 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:43.569  4582  4582 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-06 10:45:43.569  4582  4667 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-06 10:45:43.570  4582  4582 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-06 10:45:43.570  4582  4582 D SapService: Received stop request...Stopping profile...
10-06 10:45:43.570  4582  4582 V SapService: stop()
10-06 10:45:43.571   928  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-06 10:45:43.572  4582  4582 V BluetoothAdapterState: isTurningOff()=true
10-06 10:45:43.572  4582  4582 V BluetoothAdapterState: isTurningOn()=false
10-06 10:45:43.572  4582  4582 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:43.572  4582  4582 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:43.572  4582  4582 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-06 10:45:43.572  4582  4582 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-06 10:45:43.573  3737  3899 W QCNEJ   : |CORE| network lost: 100
10-06 10:45:43.574  3737  3899 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-06 10:45:43.579  4582  4582 D BluetoothMapService: MAP Service closeService in
10-06 10:45:43.579  4582  4582 D BluetoothMapMasInstance0: MAP Service shutdown
10-06 10:45:43.579  4582  4582 D ObexServerSockets0: shutdown(block = true)
10-06 10:45:43.580  4582  4582 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-06 10:45:43.580  4582  4582 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-06 10:45:43.580  4582  4830 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-06 10:45:43.580  4582  4855 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-06 10:45:43.580  4582  4854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-06 10:45:43.581  4582  4582 V BluetoothAdapterState: isTurningOff()=true
10-06 10:45:43.581  4582  4582 V BluetoothAdapterState: isTurningOn()=false
10-06 10:45:43.581  4582  4582 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:43.581  4582  4582 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:43.581  4582  4582 D BluetoothMapService: cleanup()
10-06 10:45:43.581  4582  4582 D BluetoothMapService: MAP Service closeService in
10-06 10:45:43.582  4582  4582 V BluetoothAdapterState: isTurningOff()=true
10-06 10:45:43.582  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.582  4582  4582 V BluetoothAdapterState: isTurningOn()=false
10-06 10:45:43.582  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:43.582  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.582  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.582  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:43.582  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.582  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:43.582  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:43.582  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:43.582  4582  4582 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:43.582  4582  4582 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:43.583  4582  4582 I BtOppRfcommListener: stopping Accept Thread
10-06 10:45:43.583  4582  4663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-06 10:45:43.583  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.583  4582  5323 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-06 10:45:43.583  4582  4663 D BluetoothAdapterProperties: Setting state to 15
10-06 10:45:43.583  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:43.583  4582  4663 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-06 10:45:43.583  4582  5323 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-06 10:45:43.583  4582  4663 I BluetoothAdapterState: Entering BleOnState
10-06 10:45:43.585  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.585  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:43.585  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.585  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.585  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:43.585  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.585  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:43.585  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:43.585  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:43.586  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.586  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:43.587   928  2959 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-06 10:45:43.588  3118  3118 D BluetoothMap: Proxy object disconnected
10-06 10:45:43.588  3118  3118 D MapProfile: Bluetooth service disconnected
10-06 10:45:43.589  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.589  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:43.589  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.589  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.589  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:43.589  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.589  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:43.589  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:43.589  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:43.590  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.590  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:43.593   928   941 I ActivityManager: Start proc 5677:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-06 10:45:43.594  3118  3132 D BluetoothA2dp: onBluetoothStateChange: up=false
10-06 10:45:43.595  3118  3975 D BluetoothMap: onBluetoothStateChange: up=false
10-06 10:45:43.596  3118  3131 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-06 10:45:43.597  3118  3979 D BluetoothPbap: onBluetoothStateChange: up=false
10-06 10:45:43.598  3118  3132 D BluetoothPan: onBluetoothStateChange on: false
10-06 10:45:43.599   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:45:43.599  3776  3808 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-06 10:45:43.600   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:45:43.600  3118  3975 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:45:43.600   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-06 10:45:43.600   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:45:43.600  4582  4663 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-06 10:45:43.601  4582  4663 D BluetoothAdapterProperties: Setting state to 16
10-06 10:45:43.601  4582  4663 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-06 10:45:43.601   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-06 10:45:43.602  4582  4663 D BluetoothAdapterProperties: onBleDisable
10-06 10:45:43.602  4582  4663 I BluetoothAdapterState: Entering PendingCommandState
10-06 10:45:43.602  4582  4664 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-06 10:45:43.603  4582  4667 D BluetoothAdapterProperties: Scan Mode:20
10-06 10:45:43.603  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.604   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-06 10:45:43.605  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.607  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.608  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.609  4582  4808 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-06 10:45:43.609  4582  4808 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:45:43.610  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.613  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.625   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-06 10:45:43.626   509   923 D CommandListener: Clearing all IP addresses on wlan0
10-06 10:45:43.627   509   923 D TetherController: Setting IP forward enable = 0
10-06 10:45:43.627   928  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-06 10:45:43.627   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-06 10:45:43.631   928  2959 D DhcpClient: doQuit
,10-06 10:45:43.631   928  2959 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-06 10:45:43.632  3443  3443 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-06 10:45:43.632   928  5359 D DhcpClient: onQuitting
10-06 10:45:43.633   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-06 10:45:43.639  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.640  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:43.640  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.640  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.640  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:43.640  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.640  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:43.640  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:43.640  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:43.636  5261  5261 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@938c357 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-06 10:45:43.640  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.640  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:43.642  5031  5044 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-06 10:45:43.642  5031  5044 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-06 10:45:43.642  5031  5044 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-06 10:45:43.642  5031  5044 E SarControlService: no key has been found,reset the power
10-06 10:45:43.642  5031  5069 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-06 10:45:43.642  5031  5069 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-06 10:45:43.642  5031  5069 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-06 10:45:43.643  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-06 10:45:43.643  5057  5057 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-06 10:45:43.643  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.643  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:43.643  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.643  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.643  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:43.643  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.643  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:43.643  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:43.643  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:43.644  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.644  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:43.644  5031  5069 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-06 10:45:43.645  5031  5069 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-06 10:45:43.645  5031  5069 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-06 10:45:43.645  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-06 10:45:43.645  5057  5057 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-06 10:45:43.646  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.646  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:43.646  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:43.646  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:43.646  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:43.646  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:43.646  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:43.646  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:43.646  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:43.646  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:43.646  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:43.648  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:43.648  5057  5071 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e998b5 HexData = [00000000ea03000000000000ffffffff]
10-06 10:45:43.648  5057  5071 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-06 10:45:43.648  5057  5071 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-06 10:45:43.648  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-06 10:45:43.649  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.649  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-06 10:45:43.650  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:43.656  5057  5071 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e998b5 HexData = [00000000eb03000000000000ffffffff]
,10-06 10:45:43.656  5057  5071 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-06 10:45:43.656  5057  5071 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-06 10:45:43.656  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-06 10:45:43.657  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-06 10:45:43.660  3443  3443 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-06 10:45:43.663  5677  5677 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-06 10:45:43.665  3443  3443 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-06 10:45:43.674  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-06 10:45:43.679   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ae481c4:true
,10-06 10:45:43.681  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-06 10:45:43.690   509   923 E Netd    : netlink response contains error (No such file or directory)
,10-06 10:45:43.690   509   923 D TetherController: Setting IP forward enable = 0
10-06 10:45:43.693   928  2973 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-06 10:45:43.693   928  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-06 10:45:43.694   928  3769 I ActivityManager: Start proc 5700:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-06 10:45:43.698  3443  3443 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-06 10:45:43.702  5677  5677 D LocalBluetoothProfileManager: Adding local MAP profile
,10-06 10:45:43.706  5677  5677 D BluetoothMap: Create BluetoothMap proxy object
,10-06 10:45:43.717  5677  5677 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-06 10:45:43.722  3443  3443 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-06 10:45:43.736  5700  5700 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-06 10:45:43.740  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,10-06 10:45:43.742   928  3769 I ActivityManager: Killing 4995:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-06 10:45:43.816  4582  4667 I bt_hci  : shut_down
,10-06 10:45:43.820  4582  4672 D bt_hwcfg: hw_epilog_process
,10-06 10:45:43.820  4582  4672 I bt_vendor: low_power_mode_cb
,10-06 10:45:43.822  4582  4672 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-06 10:45:43.822  4582  4672 I bt_vendor: epilog_cb
10-06 10:45:43.822  4582  4672 I bt_hci  : epilog_finished_callback
,10-06 10:45:43.824  4406  4406 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-06 10:45:43.824   928  2959 D wifi    : In wifi stop Hal
10-06 10:45:43.824   928  2959 D wifi    : halHandle = 0x7f63a4d680, mVM = 0x7f8008d140, mCls = 0x100a02
10-06 10:45:43.825   928  3442 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-06 10:45:43.825   928  3442 D WifiHAL : Got a signal to exit!!!
10-06 10:45:43.825   928  3442 I WifiHAL : Exit wifi_event_loop
10-06 10:45:43.825  4582  4667 I bt_hci_h4: hal_close
10-06 10:45:43.826   928  2959 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-06 10:45:43.826   928  2959 E WifiHAL : Event processing terminated
10-06 10:45:43.826   928  2959 D wifi    : In wifi cleaned up handler
10-06 10:45:43.826   928  2959 I WifiHAL : Internal cleanup completed
,10-06 10:45:43.826  4582  4667 I bt_userial_vendor: device fd = 54 close
,10-06 10:45:43.827  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:43.829  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:43.832  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:43.838  3707  4178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-06 10:45:43.854   928  3442 D wifi    : set interface wlan0 flags (DOWN)
,10-06 10:45:43.855   928  2959 D WifiNative-HAL: HAL event thread stopped successfully
,10-06 10:45:43.932  4582  4664 D bt_stack_manager: event_shut_down_stack finished.
,10-06 10:45:43.932  4582  4663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-06 10:45:43.934  4582  4582 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-06 10:45:43.934  4582  4663 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-06 10:45:43.934  4582  4582 D BtGatt.GattService: Received stop request...Stopping profile...
10-06 10:45:43.934  4582  4582 D BtGatt.GattService: stop()
,10-06 10:45:43.935  4582  4582 D BtGatt.AdvertiseManager: advertise clients cleared
,10-06 10:45:43.936  4582  4582 V BluetoothAdapterState: isTurningOff()=false
10-06 10:45:43.936  4582  4582 V BluetoothAdapterState: isTurningOn()=false
,10-06 10:45:43.936  4582  4582 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:43.936  4582  4582 V BluetoothAdapterState: isBleTurningOff()=true
10-06 10:45:43.937  4582  4663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-06 10:45:43.937  4582  4663 D BluetoothAdapterProperties: Setting state to 10
,10-06 10:45:43.937  4582  4663 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-06 10:45:43.937  4582  4663 I BluetoothAdapterState: Entering OffState
,10-06 10:45:43.939   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-06 10:45:43.945  4582  4582 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-06 10:45:43.945  4582  4582 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-06 10:45:43.945  4582  4582 I BluetoothServiceJni: cleanupNative: return from cleanup
10-06 10:45:43.947  4582  4664 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-06 10:45:43.950  4582  4582 I art     : System.exit called, status: 0
,10-06 10:45:43.950  4582  4582 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-06 10:45:43.975  5700  5700 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.File.exists(File.java:361)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-06 10:45:43.975  5700  5700 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-06 10:45:43.975  5700  5700 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-06 10:45:43.975  5700  5700 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.e.b(PG:170)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-06 10:45:43.975  5700  5700 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.k.d(PG:583)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.e.b(PG:170)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-06 10:45:43.975  5700  5700 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.File.exists(File.java:361)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-06 10:45:43.975  5700  5700 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.File.exists(File.java:361)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-06 10:45:43.975  5700  5700 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:45:43.975  5700  5700 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-06 10:45:43.979  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-06 10:45:43.981   928   939 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
10-06 10:45:43.982   928   939 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
10-06 10:45:43.982   928   939 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
10-06 10:45:43.982   928   939 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
10-06 10:45:43.982   928   939 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
10-06 10:45:44.005   928   939 I ActivityManager: Start proc 5734:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
10-06 10:45:44.005   928  3417 W ActivityManager: Spurious death for ProcessRecord{693c48b 5734:com.android.bluetooth/1002}, curProc for 4582: null
10-06 10:45:44.006  5677  5677 D DockEventReceiver: finishStartingService: stopping service
10-06 10:45:44.008   928  3762 I ActivityManager: Killing 5387:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-06 10:45:44.057   928   945 D Tethering: InitialState.processMessage what=4
10-06 10:45:44.060   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-06 10:45:44.084  5734  5734 D AdapterServiceConfig: Adding HeadsetService
10-06 10:45:44.085  5734  5734 D AdapterServiceConfig: Adding A2dpService
10-06 10:45:44.085  5734  5734 D AdapterServiceConfig: Adding HidService
10-06 10:45:44.085  5734  5734 D AdapterServiceConfig: Adding HealthService
10-06 10:45:44.085  5734  5734 D AdapterServiceConfig: Adding PanService
10-06 10:45:44.085  5734  5734 D AdapterServiceConfig: Adding GattService
10-06 10:45:44.085  5734  5734 D AdapterServiceConfig: Adding BluetoothMapService
10-06 10:45:44.085  5734  5734 D AdapterServiceConfig: Adding SapService
10-06 10:45:44.087   928  3744 I ActivityManager: Killing 5402:com.android.chrome/u0a39 (adj 15): empty #17
,10-06 10:45:44.147  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-06 10:45:44.159  4005  4005 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-06 10:45:44.163  4005  4005 D SystemUpdateService: onCreate
,10-06 10:45:44.167  4005  4005 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-06 10:45:44.177  4005  4005 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-06 10:45:44.181  4005  5385 I iu.UploadsManager: num queued entries: 0
,10-06 10:45:44.181  4005  5385 I iu.UploadsManager: num updated entries: 0
,10-06 10:45:44.183  4005  4005 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-06 10:45:44.186  4005  4005 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-06 10:45:44.192  4005  5746 I SystemUpdateService: active receiver: enabled
,10-06 10:45:44.194  4005  5385 I iu.SyncManager: NEXT; no task
,10-06 10:45:44.197   928  3762 I ActivityManager: Start proc 5748:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-06 10:45:44.201  4005  5746 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-06 10:45:44.203  4005  5746 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-06 10:45:44.203  4005  5746 I SystemUpdateService: now status is 0 (complete)
10-06 10:45:44.203  4005  5746 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-06 10:45:44.203  4005  5746 I SystemUpdateService: file has been verified
10-06 10:45:44.204  4005  5746 I SystemUpdateService: OTA package size = 21989297
,10-06 10:45:44.240  5748  5748 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-06 10:45:44.243  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-06 10:45:44.244  4005  5746 I SystemUpdateService: showing system update notification
,10-06 10:45:44.250  5748  5748 D SprintDMHelper: simOperator: 
10-06 10:45:44.250  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-06 10:45:44.262   928  3418 I ActivityManager: Start proc 5760:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-06 10:45:44.285  4005  4005 D SystemUpdateService: onDestroy
,10-06 10:45:44.287   928  3198 I ActivityManager: Killing 5419:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-06 10:45:44.363  4406  5774 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-06 10:45:44.368   928  3824 I ActivityManager: Start proc 5775:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-06 10:45:44.371   928  3824 I ActivityManager: Killing 5261:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-06 10:45:44.409  5700  5720 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-06 10:45:44.441  5775  5775 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-06 10:45:44.487   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@470818d:true
,10-06 10:45:44.628   928  3418 I ActivityManager: Killing 4678:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-06 10:45:44.676   928  3744 I ActivityManager: Start proc 5789:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-06 10:45:44.708  5789  5789 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-06 10:45:44.715   928  3198 I ActivityManager: Killing 5478:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-06 10:45:48.538   928  3417 D WifiService: setWifiEnabled: true pid=5617, uid=10077
10-06 10:45:48.538   928  3417 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-06 10:45:48.547   509   923 D SoftapController: Softap fwReload - Ok
,10-06 10:45:48.551   509   923 D CommandListener: Setting iface cfg
,10-06 10:45:48.552   509   923 D CommandListener: Trying to bring down wlan0
,10-06 10:45:48.554   509   923 D CommandListener: Clearing all IP addresses on wlan0
,10-06 10:45:48.559   928  2959 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-06 10:45:49.130   928  2959 D wifi    : set interface wlan0 flags (UP)
,10-06 10:45:49.134   928  2959 I WifiHAL : Initializing wifi
10-06 10:45:49.134   928  2959 I WifiHAL : Creating socket
10-06 10:45:49.137   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-06 10:45:49.140   928  2959 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-06 10:45:49.140   928  2959 D wifi    : Did set static halHandle = 0x7f63a4d680
10-06 10:45:49.140   928  2959 D wifi    : halHandle = 0x7f63a4d680, mVM = 0x7f8008d140, mCls = 0x18b2
10-06 10:45:49.140   928  2959 D wifi    : array field set
10-06 10:45:49.140   928  2959 I WifiNative-HAL: interface[0] = wlan0
10-06 10:45:49.143   928  5809 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547132593792
10-06 10:45:49.143   928  5809 D wifi    : waitForHalEvents called, vm = 0x7f8008d140, obj = 0x18b2, env = 0x7f63a58b40
,10-06 10:45:49.232  5810  5810 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-06 10:45:49.244   928  2959 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-06 10:45:49.250  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:49.252  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:49.255  5810  5810 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-06 10:45:49.255  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:49.275  5810  5810 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-06 10:45:49.275  5810  5810 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-06 10:45:49.290   928  2959 D WifiConfigStore: Loading config and enabling all networks 
,10-06 10:45:49.290  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:49.290  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:49.290  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:49.290  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:49.290  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:49.290  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:49.290  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:49.290  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:49.290  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:49.291  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:49.291  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:49.292  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:49.292  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:49.292  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:49.292  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:49.292  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:49.292  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:49.292  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:49.292  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:49.292  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:49.292  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:49.292  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-06 10:45:49.293  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:49.294  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:49.294  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:49.294  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:49.294  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:49.294  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:49.294  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:49.294  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:49.294  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:49.294  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:49.294  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-06 10:45:49.301   928  2959 D WifiConfigStore: loaded 0 passpoint configs
,10-06 10:45:49.301   928  2959 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-06 10:45:49.301   928  2959 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-06 10:45:49.302   928  2959 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-06 10:45:49.303   928  2959 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-06 10:45:49.303   928  2959 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,10-06 10:45:49.304   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-06 10:45:49.304   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-06 10:45:49.307   928  2959 D WifiNative-HAL: Setting external_sim to 1
,10-06 10:45:49.307  4406  4406 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-06 10:45:49.307   928  2959 D wifi    : setting dfs flag to true, 0x7f63a49240
10-06 10:45:49.307   928  2959 D WifiStateMachine: Setting OUI to DA-A1-19
10-06 10:45:49.307   928  2959 D wifi    : setting scan oui 0x7f63a49240
10-06 10:45:49.307   928  2959 D WifiHAL : Sending mac address OUI
,10-06 10:45:49.311   928  2959 E native  : do suspend false
,10-06 10:45:49.318   928  2959 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-06 10:45:49.318   928   928 D RttService: SCAN_AVAILABLE : 3
10-06 10:45:49.318   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-06 10:45:49.319   928  3074 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-06 10:45:49.319   509   923 D CommandListener: Setting iface cfg
,10-06 10:45:49.323   928  2948 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-06 10:45:49.324   928  2948 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-06 10:45:49.331   928  2948 D WifiNative-HAL: p2pGetDeviceAddress
,10-06 10:45:49.336   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267634 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
10-06 10:45:49.336   928  2948 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-06 10:45:52.535  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-06 10:45:52.546  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-06 10:45:52.552  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-06 10:45:52.557  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-06 10:45:52.586   928  2959 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-06 10:45:52.587   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-06 10:45:52.587   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-06 10:45:52.600   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-06 10:45:52.639   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-06 10:45:52.641  5810  5810 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-06 10:45:53.078  5810  5810 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-06 10:45:53.112  5810  5810 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-06 10:45:53.112  5810  5810 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-06 10:45:53.120   928  2959 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-06 10:45:53.120   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-06 10:45:53.120   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-06 10:45:53.135   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-06 10:45:53.145   509   923 D CommandListener: Setting iface cfg
,10-06 10:45:53.150   928  2959 D WifiStateMachine: Start Dhcp Watchdog 2
,10-06 10:45:53.158   928  5816 D DhcpClient: Receive thread started
,10-06 10:45:53.162   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-06 10:45:53.163   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-06 10:45:53.163   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-06 10:45:53.250   928  2959 E native  : do suspend false
,10-06 10:45:53.264   928  5815 D DhcpClient: Broadcasting DHCPDISCOVER
,10-06 10:45:53.287   928  5816 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,10-06 10:45:53.288   928  5815 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
,10-06 10:45:53.290   928  5815 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-06 10:45:53.303   928  5816 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-06 10:45:53.304   928  5815 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-06 10:45:53.306   509   923 D CommandListener: Setting iface cfg
10-06 10:45:53.310   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-06 10:45:53.315   928  5815 D DhcpClient: Scheduling renewal in 86399s
,10-06 10:45:53.327   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-06 10:45:53.328   928  2959 D WifiConfigStore: No blacklist allowed without epno enabled
,10-06 10:45:53.330   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-06 10:45:53.333   928  2959 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-06 10:45:53.338   928  2973 D ConnectivityService: Adding iface wlan0 to network 101
,10-06 10:45:53.382   928  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-06 10:45:53.383   928  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-06 10:45:53.386   928  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-06 10:45:53.389   928  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-06 10:45:53.391   928  2973 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-06 10:45:53.396   928  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-06 10:45:53.401   928  2973 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-06 10:45:53.401   928  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-06 10:45:53.401   928  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-06 10:45:53.401   928  2973 D ConnectivityService:    accepting network in place of null
10-06 10:45:53.401   928  2959 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-06 10:45:53.401   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-06 10:45:53.402   928  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-06 10:45:53.412   928  5814 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271709, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-06 10:45:53.424   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-06 10:45:53.444   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-06 10:45:53.448   928  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-06 10:45:53.448  3737  3899 W QCNEJ   : |CORE| network available: 101
10-06 10:45:53.448   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-06 10:45:53.449   928  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-06 10:45:53.450   928   945 D Tethering: MasterInitialState.processMessage what=3
10-06 10:45:53.453  3737  3899 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-06 10:45:53.454  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.454  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:53.454  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:53.454  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:53.454  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:53.454  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:53.454  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:53.454  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:53.454  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:53.454  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.454  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:53.454  3737  3899 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-06 10:45:53.455  3737  3899 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-06 10:45:53.457  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.457  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:53.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:53.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:53.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:53.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:53.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:53.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:53.457  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:53.457  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.457  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetwork,Changed: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-06 10:45:53.459  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-06 10:45:53.460  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:53.460  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:53.460  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:53.460  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:45:53.460  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:53.460  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:53.460  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:45:53.460  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:45:53.460  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.460  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:45:53.461  5031  5044 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-06 10:45:53.461  5031  5044 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-06 10:45:53.461  5031  5044 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-06 10:45:53.461  5031  5044 E SarControlService: no key has been found,reset the power
,10-06 10:45:53.463  4005  4005 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-06 10:45:53.463  5031  5069 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-06 10:45:53.464  5031  5069 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-06 10:45:53.464  5031  5069 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-06 10:45:53.465  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-06 10:45:53.465  5057  5057 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-06 10:45:53.466  5031  5069 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-06 10:45:53.467  5031  5069 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-06 10:45:53.467  5031  5069 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-06 10:45:53.467  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-06 10:45:53.467  5057  5057 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-06 10:45:53.470  4005  4005 D SystemUpdateService: onCreate
10-06 10:45:53.472  5057  5071 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e998b5 HexData = [00000000ec03000000000000ffffffff]
10-06 10:45:53.473  5057  5071 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-06 10:45:53.473  5057  5071 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-06 10:45:53.473  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-06 10:45:53.473  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-06 10:45:53.475  5057  5071 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e998b5 HexData = [00000000ed03000000000000ffffffff]
10-06 10:45:53.475  5057  5071 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-06 10:45:53.475  5057  5071 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-06 10:45:53.476  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-06 10:45:53.476  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-06 10:45:53.476  4005  4005 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-06 10:45:53.484   928  5813 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-06 10:45:53.489  4005  4005 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-06 10:45:53.497  4005  5385 I iu.UploadsManager: num queued entries: 0
10-06 10:45:53.497  4005  5385 I iu.UploadsManager: num updated entries: 0
,10-06 10:45:53.498  4005  5826 I SystemUpdateService: active receiver: enabled
,10-06 10:45:53.500  4005  4005 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-06 10:45:53.501  4005  4005 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-06 10:45:53.503  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-06 10:45:53.507  5748  5748 D SprintDMHelper: simOperator: 
,10-06 10:45:53.507  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-06 10:45:53.532  4005  5385 I iu.SyncManager: NEXT; no task
,10-06 10:45:53.533  4005  5826 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-06 10:45:53.540   928  5813 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 06 Oct 2016 14:45:53 GMT], X-Android-Received-Millis=[1475765153539], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475765153506]}
,10-06 10:45:53.540   928  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-06 10:45:53.540   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-06 10:45:53.540   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-06 10:45:53.541   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-06 10:45:53.543   928  3744 D WifiService: setWifiEnabled: false pid=5617, uid=10077
,10-06 10:45:53.543   928  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-06 10:45:53.545   928  2959 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-06 10:45:53.545   928  2959 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-06 10:45:53.545   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-06 10:45:53.545   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-06 10:45:53.550  4005  5826 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-06 10:45:53.550  4005  5826 I SystemUpdateService: now status is 0 (complete)
10-06 10:45:53.550  4005  5826 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-06 10:45:53.551  4005  5826 I SystemUpdateService: file has been verified
10-06 10:45:53.551  4005  5826 I SystemUpdateService: OTA package size = 21989297
,10-06 10:45:53.553   928  5815 D DhcpClient: Clearing IP address
10-06 10:45:53.553   509   923 D CommandListener: Clearing all IP addresses on wlan0
,10-06 10:45:53.554   509   923 D CommandListener: Setting iface cfg
10-06 10:45:53.556  4005  5826 I SystemUpdateService: showing system update notification
,10-06 10:45:53.562   928  3417 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
10-06 10:45:53.563   928  5813 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-06 10:45:53.563   928  5813 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-06 10:45:53.566   928  5816 D DhcpClient: Receive thread stopped
10-06 10:45:53.568   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-06 10:45:53.568   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-06 10:45:53.573   928  5813 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,10-06 10:45:53.574   536   536 E Parcel  : Reading a NULL string not supported here.
10-06 10:45:53.575   928   928 D RttService: SCAN_AVAILABLE : 1
10-06 10:45:53.575   928  3074 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-06 10:45:53.576   928  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-06 10:45:53.577  3737  3899 W QCNEJ   : |CORE| network lost: 101
10-06 10:45:53.579  3737  3899 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-06 10:45:53.580   928  2959 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-06 10:45:53.584   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-06 10:45:53.588  4005  4005 D SystemUpdateService: onDestroy
,10-06 10:45:53.603   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-06 10:45:53.622   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-06 10:45:53.622   509   923 D CommandListener: Clearing all IP addresses on wlan0
,10-06 10:45:53.623   928  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-06 10:45:53.623   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-06 10:45:53.625   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-06 10:45:53.628   928  2959 D DhcpClient: doQuit
,10-06 10:45:53.628   928  5815 D DhcpClient: onQuitting
10-06 10:45:53.628   928  2959 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-06 10:45:53.629  5810  5810 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-06 10:45:53.633  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.633  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:53.633  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:53.633  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:53.633  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:53.633  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:53.633  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:53.633  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:53.633  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:53.633  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.633  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:53.636  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.636  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:53.636  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:53.636  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:53.636  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:53.636  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:53.636  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:53.636  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:53.636  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-06 10:45:53.636  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.636  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:53.637  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-06 10:45:53.637  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:53.637  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:53.637  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:53.637  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:53.637  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:45:53.637  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:53.637  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:53.637  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-06 10:45:53.637  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:45:53.637  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:53.639  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:53.640  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:53.640  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:53.641  5031  5044 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-06 10:45:53.641  5031  5044 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-06 10:45:53.641  5031  5044 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-06 10:45:53.641  5031  5044 E SarControlService: no key has been found,reset the power
10-06 10:45:53.642  5031  5069 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-06 10:45:53.643  4005  4005 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-06 10:45:53.643  5031  5069 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-06 10:45:53.643  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-06 10:45:53.644  5031  5069 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-06 10:45:53.644  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-06 10:45:53.644  5057  5057 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-06 10:45:53.645  5031  5069 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-06 10:45:53.645  5031  5069 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-06 10:45:53.646  5031  5069 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-06 10:45:53.646  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-06 10:45:53.646  5057  5057 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-06 10:45:53.647  5810  5810 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-06 10:45:53.649  4005  4005 D SystemUpdateService: onCreate
10-06 10:45:53.652  5057  5071 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e998b5 HexData = [00000000ee03000000000000ffffffff]
10-06 10:45:53.652  5057  5071 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-06 10:45:53.652  5057  5071 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-06 10:45:53.653  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-06 10:45:53.653  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-06 10:45:53.653  4005  4005 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-06 10:45:53.656  5057  5071 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e998b5 HexData = [00000000ef03000000000000ffffffff]
10-06 10:45:53.656  5057  5071 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-06 10:45:53.656  5057  5071 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-06 10:45:53.657  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-06 10:45:53.657  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-06 10:45:53.660  4005  5844 I SystemUpdateService: active receiver: enabled
10-06 10:45:53.662  4005  4005 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-06 10:45:53.667  4005  5385 I iu.UploadsManager: num queued entries: 0
,10-06 10:45:53.668  4005  5385 I iu.UploadsManager: num updated entries: 0
10-06 10:45:53.669  4005  5385 I iu.SyncManager: NEXT; no task
,10-06 10:45:53.671  4005  4005 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-06 10:45:53.672  4005  4005 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-06 10:45:53.673  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-06 10:45:53.678  5748  5748 D SprintDMHelper: simOperator: 
,10-06 10:45:53.678  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-06 10:45:53.680  5810  5810 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-06 10:45:53.681  4005  5844 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-06 10:45:53.686   509   923 E Netd    : netlink response contains error (No such file or directory)
,10-06 10:45:53.687   928  2973 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-06 10:45:53.687   928  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-06 10:45:53.688  5810  5810 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-06 10:45:53.689  4005  5844 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-06 10:45:53.689  4005  5844 I SystemUpdateService: now status is 0 (complete)
10-06 10:45:53.689  4005  5844 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-06 10:45:53.689  4005  5844 I SystemUpdateService: file has been verified
10-06 10:45:53.689  4005  5844 I SystemUpdateService: OTA package size = 21989297
,10-06 10:45:53.695  4005  5844 I SystemUpdateService: showing system update notification
,10-06 10:45:53.712  4005  4005 D SystemUpdateService: onDestroy
,10-06 10:45:53.793   928  2959 D wifi    : In wifi stop Hal
,10-06 10:45:53.793   928  2959 D wifi    : halHandle = 0x7f63a4d680, mVM = 0x7f8008d140, mCls = 0x18b2
10-06 10:45:53.794   928  5809 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-06 10:45:53.794   928  5809 D WifiHAL : Got a signal to exit!!!
10-06 10:45:53.794   928  5809 I WifiHAL : Exit wifi_event_loop
,10-06 10:45:53.796  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:53.796  4406  4406 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-06 10:45:53.797   928  2959 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-06 10:45:53.797   928  2959 E WifiHAL : Event processing terminated
10-06 10:45:53.797   928  2959 D wifi    : In wifi cleaned up handler
10-06 10:45:53.797   928  2959 I WifiHAL : Internal cleanup completed
10-06 10:45:53.797  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:53.798  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:53.799  3707  4178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-06 10:45:53.822   928  5809 D wifi    : set interface wlan0 flags (DOWN)
,10-06 10:45:53.822   928  2959 D WifiNative-HAL: HAL event thread stopped successfully
,10-06 10:45:54.030   928   945 D Tethering: InitialState.processMessage what=4
,10-06 10:45:54.038   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-06 10:45:54.449   928  2973 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-06 10:45:55.775   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:56.776   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:57.777   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:58.544  4406  5830 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,10-06 10:45:58.545  4406  5830 I Babel   : connection state changed from DISCONNECTED to CONNECTED
10-06 10:45:58.548  4406  5830 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-06 10:45:58.574   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b94b268:true
,10-06 10:45:58.575  5734  5734 D BluetoothAdapterState: make() - Creating AdapterState
,10-06 10:45:58.579  5734  5734 I bt_bluedroid: init
,10-06 10:45:58.579  5734  5849 I BluetoothAdapterState: Entering OffState
,10-06 10:45:58.583  5734  5850 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-06 10:45:58.583  5734  5850 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-06 10:45:58.583  5734  5850 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-06 10:45:58.583  5734  5850 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-06 10:45:58.584  5734  5734 I bt_bluedroid: get_profile_interface socket
,10-06 10:45:58.587  5734  5734 I bt_bluedroid: get_profile_interface sdp
,10-06 10:45:58.587  5734  5853 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-06 10:45:58.589  5734  5853 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-06 10:45:58.594  5734  5744 I bt_bluedroid: config_hci_snoop_log
,10-06 10:45:58.596   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-06 10:45:58.602  5734  5849 D BluetoothAdapterState: Current state: OFF, message: 0
,10-06 10:45:58.602  5734  5849 D BluetoothAdapterProperties: Setting state to 14
,10-06 10:45:58.603  5734  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-06 10:45:58.605  5734  5849 D BluetoothBondStateMachine: make
10-06 10:45:58.607  5734  5854 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-06 10:45:58.611  5734  5849 I BluetoothAdapterState: Entering PendingCommandState
,10-06 10:45:58.613  5734  5734 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-06 10:45:58.616  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:45:58.617  5734  5734 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-06 10:45:58.618  5734  5734 D BtGatt.GattService: Received start request. Starting profile...
,10-06 10:45:58.619  5734  5734 D BtGatt.GattService: start()
10-06 10:45:58.619  5734  5734 I bt_bluedroid: get_profile_interface gatt
,10-06 10:45:58.621  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
,10-06 10:45:58.622  5734  5734 D BtGatt.AdvertiseManager: advertise manager created
,10-06 10:45:58.629  5734  5734 V BluetoothAdapterState: isTurningOff()=false
,10-06 10:45:58.629  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-06 10:45:58.629  5734  5734 V BluetoothAdapterState: isBleTurningOn()=true
,10-06 10:45:58.629  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:58.629  5734  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-06 10:45:58.631  5734  5849 I bt_bluedroid: bt_bluedroid
,10-06 10:45:58.631  5734  5850 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-06 10:45:58.632  5734  5850 I bt_hci  : start_up
,10-06 10:45:58.639  5734  5850 I bt_vendor: alloc value 0xf3b78871
,10-06 10:45:58.639  5734  5850 I bt_vendor: init
10-06 10:45:58.639  5734  5850 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-06 10:45:58.639  5734  5850 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-06 10:45:58.752  5734  5850 D bt_hci  : start_up starting async portion
,10-06 10:45:58.752  5734  5857 I bt_hci  : event_finish_startup
10-06 10:45:58.753  5734  5857 I bt_hci_h4: hal_open
10-06 10:45:58.753  5734  5857 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-06 10:45:58.756  5734  5857 I bt_userial_vendor: device fd = 54 open
,10-06 10:45:58.751  5858  5858 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-06 10:45:58.770  5734  5857 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-06 10:45:58.773  5734  5857 D bt_hwcfg: Chipset BCM4358A3
,10-06 10:45:58.773  5734  5857 D bt_hwcfg: Target name = [BCM4358A3]
,10-06 10:45:58.773  5734  5857 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-06 10:45:58.778   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:45:59.163  5734  5857 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-06 10:45:59.163  5734  5857 D bt_hwcfg: Settlement delay -- 100 ms
10-06 10:45:59.163  5734  5857 I bt_hwcfg: Setting fw settlement delay to 100 
,10-06 10:45:59.298  5734  5857 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-06 10:45:59.299  5734  5857 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-06 10:45:59.301  5734  5857 I bt_hwcfg: vendor lib fwcfg completed
,10-06 10:45:59.301  5734  5857 I bt_vendor: firmware callback
10-06 10:45:59.302  5734  5857 I bt_hci  : firmware_config_callback
,10-06 10:45:59.311  5734  5860 I bt_btu  : btu_task pending for preload complete event
,10-06 10:45:59.311  5734  5860 I bt_btu_task: Bluetooth chip preload is complete
,10-06 10:45:59.312  5734  5860 I bt_btu  : btu_task received preload complete event
,10-06 10:45:59.318  5734  5860 I         : BTE_InitTraceLevels -- TRC_HCI
10-06 10:45:59.319  5734  5860 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-06 10:45:59.319  5734  5860 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-06 10:45:59.319  5734  5860 I         : BTE_InitTraceLevels -- TRC_AVDT
10-06 10:45:59.319  5734  5860 I         : BTE_InitTraceLevels -- TRC_AVRC
10-06 10:45:59.319  5734  5860 I         : BTE_InitTraceLevels -- TRC_A2D
10-06 10:45:59.319  5734  5860 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-06 10:45:59.319  5734  5860 I         : BTE_InitTraceLevels -- TRC_BTM
10-06 10:45:59.320  5734  5860 I         : BTE_InitTraceLevels -- TRC_GAP
10-06 10:45:59.320  5734  5860 I         : BTE_InitTraceLevels -- TRC_PAN
10-06 10:45:59.320  5734  5860 I         : BTE_InitTraceLevels -- TRC_SDP
,10-06 10:45:59.320  5734  5860 I         : BTE_InitTraceLevels -- TRC_GATT
10-06 10:45:59.320  5734  5860 I         : BTE_InitTraceLevels -- TRC_SMP
10-06 10:45:59.320  5734  5860 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-06 10:45:59.320  5734  5860 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-06 10:45:59.400  5734  5860 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3af6549
,10-06 10:45:59.400  5734  5860 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3af6549 
,10-06 10:45:59.416  5734  5853 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-06 10:45:59.418  5734  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-06 10:45:59.418  5734  5853 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-06 10:45:59.420  5734  5853 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-06 10:45:59.422  5734  5853 D BluetoothAdapterProperties: Scan Mode:20
10-06 10:45:59.422  5734  5853 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-06 10:45:59.422  5734  5853 D bt_hci  : do_postload posting postload work item
10-06 10:45:59.423  5734  5857 I bt_hci  : event_postload
10-06 10:45:59.423  5734  5857 I bt_vendor: sco_config_cb
10-06 10:45:59.423  5734  5857 I bt_hci  : sco_config_callback postload finished.
,10-06 10:45:59.427  5734  5853 D bt_bte_conf: Device ID record 1 : primary
,10-06 10:45:59.427  5734  5853 D bt_bte_conf:   vendorId            = 000f
10-06 10:45:59.427  5734  5853 D bt_bte_conf:   vendorIdSource      = 0001
10-06 10:45:59.427  5734  5853 D bt_bte_conf:   product             = 1200
10-06 10:45:59.427  5734  5853 D bt_bte_conf:   version             = 1436
10-06 10:45:59.427  5734  5853 D bt_bte_conf:   clientExecutableURL = 
,10-06 10:45:59.428  5734  5853 D bt_bte_conf:   serviceDescription  = 
10-06 10:45:59.428  5734  5853 D bt_bte_conf:   documentationURL    = 
10-06 10:45:59.428  5734  5853 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-06 10:45:59.428  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:59.428  5734  5850 D bt_stack_manager: event_start_up_stack finished
10-06 10:45:59.429  5734  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-06 10:45:59.429  5734  5849 D BluetoothAdapterProperties: Setting state to 15
10-06 10:45:59.429  5734  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-06 10:45:59.430  5734  5857 I bt_vendor: low_power_mode_cb
10-06 10:45:59.430  5734  5849 I BluetoothAdapterState: Entering BleOnState
10-06 10:45:59.431  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:59.435  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:59.436  5734  5849 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-06 10:45:59.436  5734  5849 D BluetoothAdapterProperties: Setting state to 11
,10-06 10:45:59.436  5734  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-06 10:45:59.446  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
,10-06 10:45:59.448  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:59.448  5734  5734 D HeadsetService: Received start request. Starting profile...
10-06 10:45:59.451  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:59.453  5734  5734 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-06 10:45:59.453  5734  5734 D HeadsetStateMachine: make
10-06 10:45:59.453  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:45:59.460  5734  5849 I BluetoothAdapterState: Entering PendingCommandState
,10-06 10:45:59.466  5734  5734 D HeadsetStateMachine: max_hf_connections = 1
,10-06 10:45:59.466  5734  5734 I bt_bluedroid: get_profile_interface handsfree
10-06 10:45:59.466  5734  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-06 10:45:59.466  5734  5853 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,10-06 10:45:59.469  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
,10-06 10:45:59.470  5734  5734 D A2dpService: Received start request. Starting profile...
,10-06 10:45:59.471  5734  5734 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-06 10:45:59.471  5734  5734 I bt_bluedroid: get_profile_interface avrcp
,10-06 10:45:59.477  5734  5734 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-06 10:45:59.477  5734  5734 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-06 10:45:59.477  5734  5734 D A2dpStateMachine: make
10-06 10:45:59.478  5734  5734 I bt_bluedroid: get_profile_interface a2dp
,10-06 10:45:59.479  5734  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-06 10:45:59.480  5734  5870 D A2dpStateMachine: Enter Disconnected: -2
,10-06 10:45:59.481  5734  5734 I BluetoothHidServiceJni: classInitNative: succeeds
,10-06 10:45:59.482  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
,10-06 10:45:59.483  5734  5734 D HidService: Received start request. Starting profile...
,10-06 10:45:59.483  5677  5677 D BluetoothInputDevice: Proxy object connected
10-06 10:45:59.483  5734  5734 I bt_bluedroid: get_profile_interface hidhost
10-06 10:45:59.484  5734  5734 D HidService: setHidService(): set to: null
10-06 10:45:59.484  5734  5853 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ad756d
10-06 10:45:59.484  5734  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-06 10:45:59.484  5677  5677 D HidProfile: Bluetooth service connected
,10-06 10:45:59.484  5734  5734 I BluetoothHealthServiceJni: classInitNative: succeeds
10-06 10:45:59.485  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:45:59.486  5734  5734 D HealthService: Received start request. Starting profile...
,10-06 10:45:59.487  5734  5734 I bt_bluedroid: get_profile_interface health
,10-06 10:45:59.488  5734  5734 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-06 10:45:59.489  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
,10-06 10:45:59.490  5677  5677 D BluetoothPan: BluetoothPAN Proxy object connected
,10-06 10:45:59.491  5734  5734 D PanService: Received start request. Starting profile...
10-06 10:45:59.491  5677  5677 D PanProfile: Bluetooth service connected
10-06 10:45:59.491  5734  5734 D BluetoothPanServiceJni: initializeNative(L110): pan
10-06 10:45:59.491  5734  5734 I bt_bluedroid: get_profile_interface pan
10-06 10:45:59.492  5734  5853 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-06 10:45:59.494  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:45:59.495  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-06 10:45:59.496  5734  5734 D BluetoothMapService: Received start request. Starting profile...
,10-06 10:45:59.496  5734  5734 D BluetoothMapService: start()
,10-06 10:45:59.499  5734  5734 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-06 10:45:59.500  5734  5734 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-06 10:45:59.500  5734  5734 D BluetoothMapAppObserver: createReceiver()
10-06 10:45:59.501  5734  5734 D BluetoothMapAppObserver: initObservers()
10-06 10:45:59.501  5734  5734 D BluetoothMapAppObserver: getEnabledAccountItems()
10-06 10:45:59.505  5677  5677 D BluetoothMap: Proxy object connected
10-06 10:45:59.506  5677  5677 D MapProfile: Bluetooth service connected
10-06 10:45:59.506  5677  5677 D BluetoothMap: getConnectedDevices()
,10-06 10:45:59.507  5677  5677 D BluetoothMap: Bluetooth is Not enabled
,10-06 10:45:59.507  5734  5734 V SapService: SapBinder()
10-06 10:45:59.507  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:45:59.508  5734  5734 D SapService: Received start request. Starting profile...
10-06 10:45:59.508  5734  5734 V SapService: start()
,10-06 10:45:59.511  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-06 10:45:59.511  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-06 10:45:59.511  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:59.511  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:59.511  5734  5868 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-06 10:45:59.511  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-06 10:45:59.511  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-06 10:45:59.511  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
,10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:59.512  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:59.513  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-06 10:45:59.513  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-06 10:45:59.513  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:59.513  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:59.513  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-06 10:45:59.513  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-06 10:45:59.513  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:59.514  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
,10-06 10:45:59.514  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-06 10:45:59.514  5734  5734 V BluetoothAdapterState: isTurningOn()=true
,10-06 10:45:59.514  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:45:59.514  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:45:59.515  5734  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-06 10:45:59.515  5734  5849 D BluetoothAdapterProperties: ScanMode =  20
,10-06 10:45:59.515  5734  5849 D BluetoothAdapterProperties: State =  11
,10-06 10:45:59.516  5734  5853 D BluetoothAdapterProperties: Scan Mode:21
10-06 10:45:59.516  5734  5849 D BluetoothAdapterProperties: Setting state to 12
10-06 10:45:59.516  5734  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-06 10:45:59.516  5617  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-06 10:45:59.517  3118  3132 D BluetoothA2dp: onBluetoothStateChange: up=true
10-06 10:45:59.517  5734  5849 I BluetoothAdapterState: Entering OnState
10-06 10:45:59.519  5734  5853 D BluetoothAdapterProperties: Discoverable Timeout:120
10-06 10:45:59.520  3118  3131 D BluetoothMap: onBluetoothStateChange: up=true
10-06 10:45:59.520  3118  3118 D BluetoothA2dp: Proxy object connected
10-06 10:45:59.520  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:59.520  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:59.520  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:59.520  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:59.520  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:59.520  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:59.520  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:59.520  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:59.521  3118  3975 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-06 10:45:59.522  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:59.523  3118  3979 D BluetoothPbap: onBluetoothStateChange: up=true
10-06 10:45:59.524  3118  3118 D BluetoothMap: Proxy object connected
10-06 10:45:59.524  3118  3118 D MapProfile: Bluetooth service connected
10-06 10:45:59.524  3118  3118 D BluetoothMap: getConnectedDevices()
10-06 10:45:59.525  3118  3132 D BluetoothPan: onBluetoothStateChange on: true
,10-06 10:45:59.526  3118  3118 D BluetoothInputDevice: Proxy object connected
10-06 10:45:59.526   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:45:59.526  3118  3118 D HidProfile: Bluetooth service connected
10-06 10:45:59.526  3776  3808 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:45:59.527  5734  5734 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-06 10:45:59.527  5677  5687 D BluetoothPan: onBluetoothStateChange on: true
,10-06 10:45:59.527   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-06 10:45:59.527  5677  5690 D BluetoothPbap: onBluetoothStateChange: up=true
10-06 10:45:59.527  5734  5734 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-06 10:45:59.527  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:59.527  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:59.527  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:59.527  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:59.527  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:59.527  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:59.527  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:59.527  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:59.529  3118  3131 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:45:59.529  5734  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-06 10:45:59.529   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-06 10:45:59.530   928   928 D BluetoothA2dp: Proxy object connected
10-06 10:45:59.530  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
10-06 10:45:59.530  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:59.530  5677  5687 D BluetoothMap: onBluetoothStateChange: up=true
10-06 10:45:59.530  3118  3118 D PanProfile: Bluetooth service connected
10-06 10:45:59.530  5677  5690 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-06 10:45:59.530   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:45:59.533   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-06 10:45:59.534  5677  5677 D LocalBluetoothProfileManager: Adding local A2DP profile
10-06 10:45:59.534  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:45:59.534  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:45:59.534  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:45:59.534  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:45:59.534  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:45:59.534  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:45:59.534  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:45:59.534  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:45:59.535  5734  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-06 10:45:59.537  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:45:59.537  5617  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-06 10:45:59.538  5734  5734 D ObexServerSockets: Succeed to create listening sockets 
,10-06 10:45:59.538  5734  5734 D ObexServerSockets0: startAccept()
10-06 10:45:59.539  5734  5734 D ObexServerSockets0: prepareForNewConnect()
10-06 10:45:59.539  5677  5677 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-06 10:45:59.540  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:59.541  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:59.543  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:45:59.543  5734  5734 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-06 10:45:59.543  5734  5734 D BluetoothSdpJni: SDP Create record success - handle: 0
10-06 10:45:59.544  5734  5734 D BluetoothMapService: onReceive
10-06 10:45:59.544  5734  5877 D ObexServerSockets0: Accepting socket connection...
10-06 10:45:59.544  5734  5734 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-06 10:45:59.544  5734  5734 D BluetoothMapService: STATE_ON
10-06 10:45:59.544  5734  5878 D ObexServerSockets0: Accepting socket connection...
,10-06 10:45:59.545  5734  5879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-06 10:45:59.546  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-06 10:45:59.548  5677  5677 D BluetoothA2dp: Proxy object connected
,10-06 10:45:59.548  5734  5879 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-06 10:45:59.548  5734  5879 D BluetoothSdpJni: SDP Create record success - handle: 1
10-06 10:45:59.552  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-06 10:45:59.556  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,10-06 10:45:59.558  5677  5677 D BluetoothPbap: Proxy object connected
10-06 10:45:59.559  5677  5677 D PbapServerProfile: Bluetooth service connected
,10-06 10:45:59.564  3118  3118 D BluetoothPbap: Proxy object connected
,10-06 10:45:59.564  3118  3118 D PbapServerProfile: Bluetooth service connected
10-06 10:45:59.565  5734  5883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-06 10:45:59.577  5734  5734 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-06 10:45:59.577  5734  5734 D ObexServerSockets0: prepareForNewConnect()
,10-06 10:45:59.581  5734  5887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-06 10:45:59.583  5734  5887 I BtOppRfcommListener: Accept thread started.
,10-06 10:45:59.627   928   928 D BluetoothHeadset: Proxy object connected
,10-06 10:45:59.627   928   928 D BluetoothHeadset: Proxy object connected
10-06 10:45:59.627   928   928 D BluetoothHeadset: Proxy object connected
,10-06 10:45:59.628  3118  3979 D BluetoothHeadset: Proxy object connected
10-06 10:45:59.628  3118  3118 D HeadsetProfile: Bluetooth service connected
10-06 10:45:59.628  3776  4035 D BluetoothHeadset: Proxy object connected
,10-06 10:45:59.629  3118  3132 D BluetoothHeadset: Proxy object connected
10-06 10:45:59.630  3118  3118 D HeadsetProfile: Bluetooth service connected
10-06 10:45:59.630   928   945 D BluetoothHeadset: Proxy object connected
,10-06 10:45:59.642  5677  5687 D BluetoothHeadset: Proxy object connected
,10-06 10:45:59.644  5677  5677 D HeadsetProfile: Bluetooth service connected
,10-06 10:45:59.779   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:46:00.780   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-06 10:46:01.408   928  2973 D ConnectivityService: handlePromptUnvalidated 101
,10-06 10:46:03.557  5734  5849 D BluetoothAdapterState: Current state: ON, message: 23
,10-06 10:46:03.558  5734  5849 D BluetoothAdapterProperties: Setting state to 13
10-06 10:46:03.558  5734  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-06 10:46:03.559  5734  5849 D BluetoothAdapterProperties: onBluetoothDisable()
,10-06 10:46:03.562  5734  5849 I BluetoothAdapterState: Entering PendingCommandState
,10-06 10:46:03.568  5734  5734 D BluetoothMapService: onReceive
10-06 10:46:03.568  5734  5734 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-06 10:46:03.568  5734  5734 D BluetoothMapService: STATE_TURNING_OFF
,10-06 10:46:03.569  5734  5734 D BluetoothMapService: MAP Service closeService in
10-06 10:46:03.569  5734  5734 D BluetoothMapMasInstance0: MAP Service shutdown
10-06 10:46:03.569  5734  5734 D ObexServerSockets0: shutdown(block = true)
10-06 10:46:03.570  5734  5877 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-06 10:46:03.571  5734  5853 D BluetoothAdapterProperties: Scan Mode:20
,10-06 10:46:03.570  5734  5734 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-06 10:46:03.571  5734  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-06 10:46:03.572  5734  5734 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-06 10:46:03.572  5734  5864 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-06 10:46:03.573  5734  5878 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-06 10:46:03.575  5734  5734 I BtOppRfcommListener: stopping Accept Thread
10-06 10:46:03.575  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:46:03.575  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:03.575  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:03.575  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:03.575  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:46:03.575  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:46:03.575  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:03.575  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:03.575  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:46:03.575  5734  5887 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-06 10:46:03.576  5734  5887 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-06 10:46:03.576  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:46:03.576  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-06 10:46:03.576  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:46:03.582  5734  5734 D HeadsetService: Received stop request...Stopping profile...
10-06 10:46:03.583  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:46:03.583  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:03.583  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:03.583  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:03.583  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:46:03.583  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:46:03.583  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:03.583  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:03.583  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:46:03.584  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:46:03.584  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:46:03.588  5677  5690 D BluetoothHeadset: Proxy object disconnected
10-06 10:46:03.588   928   928 D BluetoothHeadset: Proxy object disconnected
10-06 10:46:03.588   928   928 D BluetoothHeadset: Proxy object disconnected
10-06 10:46:03.588   928,   928 D BluetoothHeadset: Proxy object disconnected
10-06 10:46:03.588  3118  3975 D BluetoothHeadset: Proxy object disconnected
10-06 10:46:03.589  5734  5734 D A2dpService: Received stop request...Stopping profile...
10-06 10:46:03.589  5734  5870 D A2dpStateMachine: Exit Disconnected: -1
10-06 10:46:03.589  3776  3802 D BluetoothHeadset: Proxy object disconnected
10-06 10:46:03.590  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:46:03.590  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:03.590  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:03.590  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:03.590  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:46:03.590  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-06 10:46:03.590  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:03.590  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:03.590  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:46:03.592   928   928 D BluetoothA2dp: Proxy object disconnected
10-06 10:46:03.593  5617  5617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-06 10:46:03.593  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:46:03.595  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:03.596  3118  3118 D HeadsetProfile: Bluetooth service disconnected
,10-06 10:46:03.596  3118  3118 D BluetoothA2dp: Proxy object disconnected
10-06 10:46:03.597  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:03.597  5734  5734 D HidService: Received stop request...Stopping profile...
10-06 10:46:03.597  5734  5734 D HidService: Stopping Bluetooth HidService
10-06 10:46:03.599  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:03.599  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-06 10:46:03.599  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-06 10:46:03.599  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:03.599  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:03.600  3118  3118 D BluetoothInputDevice: Proxy object disconnected
10-06 10:46:03.600  3118  3118 D HidProfile: Bluetooth service disconnected
,10-06 10:46:03.601  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,10-06 10:46:03.601  5734  5734 D HealthService: Received stop request...Stopping profile...
10-06 10:46:03.602  5677  5677 D HeadsetProfile: Bluetooth service disconnected
10-06 10:46:03.603  5677  5677 D BluetoothA2dp: Proxy object disconnected
10-06 10:46:03.603  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-06 10:46:03.603  5677  5677 D BluetoothInputDevice: Proxy object disconnected
10-06 10:46:03.603  5677  5677 D HidProfile: Bluetooth service disconnected
10-06 10:46:03.603  5734  5734 D PanService: Received stop request...Stopping profile...
10-06 10:46:03.605  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-06 10:46:03.605  3118  3118 D PanProfile: Bluetooth service disconnected
,10-06 10:46:03.607  5734  5734 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-06 10:46:03.608  5734  5734 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-06 10:46:03.608  5734  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,10-06 10:46:03.608  5734  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:46:03.608  5734  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:46:03.608  5734  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:46:03.609  5734  5853 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-06 10:46:03.609  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-06 10:46:03.609  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-06 10:46:03.609  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:03.609  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:03.611  5734  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-06 10:46:03.611  5734  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-06 10:46:03.611  5734  5860 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-06 10:46:03.611  5734  5734 D BluetoothMapService: Received stop request...Stopping profile...
10-06 10:46:03.612  5734  5860 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-06 10:46:03.612  5734  5734 D BluetoothMapService: stop()
10-06 10:46:03.612  5734  5860 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-06 10:46:03.612  5734  5860 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-06 10:46:03.612  5734  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-06 10:46:03.612  5734  5734 D BluetoothMapAppObserver: deinitObservers()
10-06 10:46:03.612  5734  5734 D BluetoothMapAppObserver: removeReceiver()
10-06 10:46:03.614  5677  5677 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-06 10:46:03.614  5677  5677 D PanProfile: Bluetooth service disconnected
,10-06 10:46:03.614  5677  5677 D BluetoothMap: Proxy object disconnected
10-06 10:46:03.614  5677  5677 D MapProfile: Bluetooth service disconnected
10-06 10:46:03.614  3118  3118 D BluetoothMap: Proxy object disconnected
10-06 10:46:03.614  3118  3118 D MapProfile: Bluetooth service disconnected
10-06 10:46:03.616  5734  5734 D SapService: Received stop request...Stopping profile...
,10-06 10:46:03.616  5734  5734 V SapService: stop()
,10-06 10:46:03.617  5734  5734 V BluetoothAdapterState: isTurningOff()=true
,10-06 10:46:03.617  5734  5734 V BluetoothAdapterState: isTurningOn()=false
,10-06 10:46:03.617  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:03.617  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:03.617  5734  5734 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-06 10:46:03.617  5734  5734 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-06 10:46:03.618  5734  5853 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-06 10:46:03.619  3118  3118 D BluetoothPbap: Proxy object disconnected
,10-06 10:46:03.620  3118  3118 D PbapServerProfile: Bluetooth service disconnected
10-06 10:46:03.620  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-06 10:46:03.620  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-06 10:46:03.620  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:03.620  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:03.620  5734  5734 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-06 10:46:03.620  5734  5853 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-06 10:46:03.621  5734  5734 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-06 10:46:03.621  5677  5677 D BluetoothPbap: Proxy object disconnected
,10-06 10:46:03.621  5677  5677 D PbapServerProfile: Bluetooth service disconnected
10-06 10:46:03.621  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-06 10:46:03.621  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-06 10:46:03.621  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:03.621  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:03.622  5734  5734 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-06 10:46:03.622  5734  5734 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-06 10:46:03.623  5734  5734 D BluetoothMapService: MAP Service closeService in
,10-06 10:46:03.623  5734  5734 V BluetoothAdapterState: isTurningOff()=true
,10-06 10:46:03.623  5734  5734 V BluetoothAdapterState: isTurningOn()=false
,10-06 10:46:03.623  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:03.623  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:03.623  5734  5734 D BluetoothMapService: cleanup()
10-06 10:46:03.623  5734  5734 D BluetoothMapService: MAP Service closeService in
10-06 10:46:03.624  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-06 10:46:03.624  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-06 10:46:03.624  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:03.624  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:03.625  5734  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-06 10:46:03.625  5734  5849 D BluetoothAdapterProperties: Setting state to 15
,10-06 10:46:03.625  5734  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-06 10:46:03.626  5734  5849 I BluetoothAdapterState: Entering BleOnState
10-06 10:46:03.626  3118  3979 D BluetoothA2dp: onBluetoothStateChange: up=false
10-06 10:46:03.626  3118  3132 D BluetoothMap: onBluetoothStateChange: up=false
10-06 10:46:03.627  3118  3975 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-06 10:46:03.628  3118  3131 D BluetoothPbap: onBluetoothStateChange: up=false
10-06 10:46:03.628  3118  3979 D BluetoothPan: onBluetoothStateChange on: false
10-06 10:46:03.629   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-06 10:46:03.629  3776  3808 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:46:03.629  5677  5687 D BluetoothPan: onBluetoothStateChange on: false
10-06 10:46:03.630  5677  5690 D BluetoothA2dp: onBluetoothStateChange: up=false
10-06 10:46:03.630   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:46:03.631  5677  5687 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:46:03.631  5677  5690 D BluetoothPbap: onBluetoothStateChange: up=false
10-06 10:46:03.632  3118  3132 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:46:03.632   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-06 10:46:03.632  5677  5687 D BluetoothMap: onBluetoothStateChange: up=false
10-06 10:46:03.633  5677  5690 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-06 10:46:03.633   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-06 10:46:03.633  5734  5849 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-06 10:46:03.633  5734  5849 D BluetoothAdapterProperties: Setting state to 16
10-06 10:46:03.634  5734  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-06 10:46:03.634  5734  5849 D BluetoothAdapterProperties: onBleDisable
10-06 10:46:03.634  5734  5849 I BluetoothAdapterState: Entering PendingCommandState
10-06 10:46:03.635  5734  5850 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-06 10:46:03.636  5734  5860 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-06 10:46:03.636  5734  5860 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-06 10:46:03.636  5734  5853 D BluetoothAdapterProperties: Scan Mode:20
10-06 10:46:03.637  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:46:03.637  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-06 10:46:03.638  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:03.639  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:03.641  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:03.642  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:03.643  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-06 10:46:03.643  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:03.651  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,10-06 10:46:03.846  5734  5853 I bt_hci  : shut_down
,10-06 10:46:03.857  5734  5857 D bt_hwcfg: hw_epilog_process
,10-06 10:46:03.857  5734  5857 I bt_vendor: low_power_mode_cb
,10-06 10:46:03.859  5734  5857 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-06 10:46:03.860  5734  5857 I bt_vendor: epilog_cb
10-06 10:46:03.860  5734  5857 I bt_hci  : epilog_finished_callback
,10-06 10:46:03.863  5734  5853 I bt_hci_h4: hal_close
,10-06 10:46:03.864  5734  5853 I bt_userial_vendor: device fd = 54 close
,10-06 10:46:03.972  5734  5850 D bt_stack_manager: event_shut_down_stack finished.
,10-06 10:46:03.973  5734  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-06 10:46:03.978  5734  5734 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-06 10:46:03.977  5734  5849 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-06 10:46:03.979  5734  5734 D BtGatt.GattService: Received stop request...Stopping profile...
,10-06 10:46:03.979  5734  5734 D BtGatt.GattService: stop()
10-06 10:46:03.980  5734  5734 D BtGatt.AdvertiseManager: advertise clients cleared
,10-06 10:46:03.984  5734  5734 V BluetoothAdapterState: isTurningOff()=false
,10-06 10:46:03.984  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-06 10:46:03.984  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:03.984  5734  5734 V BluetoothAdapterState: isBleTurningOff()=true
10-06 10:46:03.985  5734  5849 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-06 10:46:03.985  5734  5849 D BluetoothAdapterProperties: Setting state to 10
10-06 10:46:03.986  5734  5849 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-06 10:46:03.987  5734  5849 I BluetoothAdapterState: Entering OffState
,10-06 10:46:03.988   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-06 10:46:04.004  5734  5734 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-06 10:46:04.007  5734  5734 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-06 10:46:04.008  5734  5734 I BluetoothServiceJni: cleanupNative: return from cleanup
10-06 10:46:04.009  5734  5850 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-06 10:46:04.017  5734  5734 I art     : System.exit called, status: 0
,10-06 10:46:04.017  5734  5734 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-06 10:46:04.049   928  3198 I ActivityManager: Process com.android.bluetooth (pid 5734) has died
,10-06 10:46:08.554  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,10-06 10:46:08.554  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:46:08.559  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:46:08.559  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ffbdf7c removed from the list
10-06 10:46:08.560  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,10-06 10:46:08.560  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:08.560  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:08.562  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:08.562  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b13585a added. We now have 4 listener(s)
,10-06 10:46:08.563  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-06 10:46:08.564  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:46:08.565  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b13585a removed from the list
10-06 10:46:08.565  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,10-06 10:46:08.565  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:08.566  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:46:08.568  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:08.568  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc43a8b added. We now have 4 listener(s)
,10-06 10:46:08.568  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-06 10:46:13.578  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:46:13.608   928   945 I ActivityManager: Start proc 5895:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-06 10:46:13.674  5895  5895 D AdapterServiceConfig: Adding HeadsetService
10-06 10:46:13.674  5895  5895 D AdapterServiceConfig: Adding A2dpService
10-06 10:46:13.674  5895  5895 D AdapterServiceConfig: Adding HidService
10-06 10:46:13.674  5895  5895 D AdapterServiceConfig: Adding HealthService
,10-06 10:46:13.675  5895  5895 D AdapterServiceConfig: Adding PanService
,10-06 10:46:13.675  5895  5895 D AdapterServiceConfig: Adding GattService
10-06 10:46:13.675  5895  5895 D AdapterServiceConfig: Adding BluetoothMapService
10-06 10:46:13.675  5895  5895 D AdapterServiceConfig: Adding SapService
,10-06 10:46:13.687  5895  5895 D BluetoothAdapterState: make() - Creating AdapterState
,10-06 10:46:13.687   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b4c6c41:true
,10-06 10:46:13.690  5895  5895 I bt_bluedroid: init
,10-06 10:46:13.691  5895  5907 I BluetoothAdapterState: Entering OffState
,10-06 10:46:13.693  5895  5908 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-06 10:46:13.694  5895  5908 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-06 10:46:13.694  5895  5908 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-06 10:46:13.694  5895  5908 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-06 10:46:13.695  5895  5895 I bt_bluedroid: get_profile_interface socket
,10-06 10:46:13.699  5895  5911 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-06 10:46:13.700  5895  5911 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-06 10:46:13.697  5895  5895 I bt_bluedroid: get_profile_interface sdp
,10-06 10:46:13.718  5895  5906 I bt_bluedroid: config_hci_snoop_log
,10-06 10:46:13.722   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-06 10:46:13.725  5895  5907 D BluetoothAdapterState: Current state: OFF, message: 0
10-06 10:46:13.725  5895  5907 D BluetoothAdapterProperties: Setting state to 14
10-06 10:46:13.725  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-06 10:46:13.727  5895  5907 D BluetoothBondStateMachine: make
,10-06 10:46:13.729  5895  5912 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-06 10:46:13.731  5895  5907 I BluetoothAdapterState: Entering PendingCommandState
,10-06 10:46:13.732  5895  5895 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-06 10:46:13.735  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:46:13.735  5895  5895 D BtGatt.DebugUtils: handleDebugAction() action=null
10-06 10:46:13.736  5895  5895 D BtGatt.GattService: Received start request. Starting profile...
10-06 10:46:13.736  5895  5895 D BtGatt.GattService: start()
10-06 10:46:13.736  5895  5895 I bt_bluedroid: get_profile_interface gatt
,10-06 10:46:13.737  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:46:13.737  5895  5895 D BtGatt.AdvertiseManager: advertise manager created
,10-06 10:46:13.743  5895  5895 V BluetoothAdapterState: isTurningOff()=false
10-06 10:46:13.743  5895  5895 V BluetoothAdapterState: isTurningOn()=false
10-06 10:46:13.743  5895  5895 V BluetoothAdapterState: isBleTurningOn()=true
10-06 10:46:13.743  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
,10-06 10:46:13.743  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-06 10:46:13.745  5895  5907 I bt_bluedroid: bt_bluedroid
,10-06 10:46:13.745  5895  5908 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-06 10:46:13.746  5895  5908 I bt_hci  : start_up
,10-06 10:46:13.752  5895  5908 I bt_vendor: alloc value 0xf3bed871
10-06 10:46:13.752  5895  5908 I bt_vendor: init
10-06 10:46:13.752  5895  5908 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,10-06 10:46:13.752  5895  5908 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-06 10:46:13.861  5895  5908 D bt_hci  : start_up starting async portion
10-06 10:46:13.861  5895  5915 I bt_hci  : event_finish_startup
10-06 10:46:13.861  5895  5915 I bt_hci_h4: hal_open
,10-06 10:46:13.861  5895  5915 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-06 10:46:13.861  5916  5916 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-06 10:46:13.864  5895  5915 I bt_userial_vendor: device fd = 54 open
,10-06 10:46:13.878  5895  5915 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-06 10:46:13.881  5895  5915 D bt_hwcfg: Chipset BCM4358A3
,10-06 10:46:13.881  5895  5915 D bt_hwcfg: Target name = [BCM4358A3]
10-06 10:46:13.882  5895  5915 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-06 10:46:14.338  5895  5915 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-06 10:46:14.339  5895  5915 D bt_hwcfg: Settlement delay -- 100 ms
10-06 10:46:14.339  5895  5915 I bt_hwcfg: Setting fw settlement delay to 100 
,10-06 10:46:14.473  5895  5915 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-06 10:46:14.473  5895  5915 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-06 10:46:14.475  5895  5915 I bt_hwcfg: vendor lib fwcfg completed
,10-06 10:46:14.475  5895  5915 I bt_vendor: firmware callback
10-06 10:46:14.475  5895  5915 I bt_hci  : firmware_config_callback
,10-06 10:46:14.484  5895  5918 I bt_btu  : btu_task pending for preload complete event
10-06 10:46:14.485  5895  5918 I bt_btu_task: Bluetooth chip preload is complete
,10-06 10:46:14.485  5895  5918 I bt_btu  : btu_task received preload complete event
,10-06 10:46:14.493  5895  5918 I         : BTE_InitTraceLevels -- TRC_HCI
,10-06 10:46:14.493  5895  5918 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-06 10:46:14.493  5895  5918 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-06 10:46:14.493  5895  5918 I         : BTE_InitTraceLevels -- TRC_AVDT
10-06 10:46:14.493  5895  5918 I         : BTE_InitTraceLevels -- TRC_AVRC
10-06 10:46:14.493  5895  5918 I         : BTE_InitTraceLevels -- TRC_A2D
,10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_BNEP
10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_BTM
10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_GAP
10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_PAN
10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_SDP
10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_GATT
,10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_SMP
10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-06 10:46:14.494  5895  5918 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-06 10:46:14.577  5895  5918 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b6b549
10-06 10:46:14.578  5895  5918 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b6b549 
,10-06 10:46:14.587  5895  5911 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-06 10:46:14.588  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-06 10:46:14.589  5895  5911 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-06 10:46:14.593  5895  5911 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-06 10:46:14.597  5895  5911 D BluetoothAdapterProperties: Scan Mode:20
,10-06 10:46:14.597  5895  5911 D BluetoothAdapterProperties: Discoverable Timeout:120
10-06 10:46:14.597  5895  5911 D bt_hci  : do_postload posting postload work item
10-06 10:46:14.597  5895  5915 I bt_hci  : event_postload
10-06 10:46:14.598  5895  5915 I bt_vendor: sco_config_cb
10-06 10:46:14.598  5895  5915 I bt_hci  : sco_config_callback postload finished.
,10-06 10:46:14.602  5895  5911 D bt_bte_conf: Device ID record 1 : primary
,10-06 10:46:14.602  5895  5911 D bt_bte_conf:   vendorId            = 000f
10-06 10:46:14.602  5895  5911 D bt_bte_conf:   vendorIdSource      = 0001
10-06 10:46:14.602  5895  5911 D bt_bte_conf:   product             = 1200
10-06 10:46:14.603  5895  5911 D bt_bte_conf:   version             = 1436
10-06 10:46:14.603  5895  5911 D bt_bte_conf:   clientExecutableURL = 
,10-06 10:46:14.603  5895  5911 D bt_bte_conf:   serviceDescription  = 
10-06 10:46:14.603  5895  5911 D bt_bte_conf:   documentationURL    = 
10-06 10:46:14.603  5895  5911 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-06 10:46:14.603  5895  5908 D bt_stack_manager: event_start_up_stack finished
10-06 10:46:14.604  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-06 10:46:14.604  5895  5907 D BluetoothAdapterProperties: Setting state to 15
10-06 10:46:14.605  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-06 10:46:14.606  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:14.608  5895  5907 I BluetoothAdapterState: Entering BleOnState
10-06 10:46:14.608  5895  5915 I bt_vendor: low_power_mode_cb
10-06 10:46:14.609  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:14.612  5895  5907 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-06 10:46:14.612  5895  5907 D BluetoothAdapterProperties: Setting state to 11
10-06 10:46:14.612  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-06 10:46:14.618  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
,10-06 10:46:14.622  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:14.623  5895  5895 D HeadsetService: Received start request. Starting profile...
10-06 10:46:14.625  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:14.626  5895  5895 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-06 10:46:14.626  5895  5895 D HeadsetStateMachine: make
,10-06 10:46:14.636  5895  5907 I BluetoothAdapterState: Entering PendingCommandState
,10-06 10:46:14.638  5895  5895 D HeadsetStateMachine: max_hf_connections = 1
10-06 10:46:14.639  5895  5895 I bt_bluedroid: get_profile_interface handsfree
,10-06 10:46:14.639  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,10-06 10:46:14.639  5895  5911 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
10-06 10:46:14.642  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:46:14.642  5895  5895 D A2dpService: Received start request. Starting profile...
10-06 10:46:14.643  5895  5895 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-06 10:46:14.643  5895  5895 I bt_bluedroid: get_profile_interface avrcp
,10-06 10:46:14.649  5895  5895 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-06 10:46:14.649  5895  5895 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-06 10:46:14.649  5895  5895 D A2dpStateMachine: make
10-06 10:46:14.650  5895  5895 I bt_bluedroid: get_profile_interface a2dp
10-06 10:46:14.651  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-06 10:46:14.653  5895  5926 D A2dpStateMachine: Enter Disconnected: -2
,10-06 10:46:14.653  5895  5895 I BluetoothHidServiceJni: classInitNative: succeeds
10-06 10:46:14.653  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:46:14.654  5895  5895 D HidService: Received start request. Starting profile...
10-06 10:46:14.654  5895  5895 I bt_bluedroid: get_profile_interface hidhost
10-06 10:46:14.654  5895  5911 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b4c56d
10-06 10:46:14.654  5895  5895 D HidService: setHidService(): set to: null
10-06 10:46:14.654  5895  5911 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-06 10:46:14.655  5895  5895 I BluetoothHealthServiceJni: classInitNative: succeeds
10-06 10:46:14.656  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:46:14.657  5895  5895 D HealthService: Received start request. Starting profile...
,10-06 10:46:14.658  5895  5895 I bt_bluedroid: get_profile_interface health
,10-06 10:46:14.659  5895  5895 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-06 10:46:14.659  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:46:14.660  5895  5895 D PanService: Received start request. Starting profile...
10-06 10:46:14.660  5895  5895 D BluetoothPanServiceJni: initializeNative(L110): pan
10-06 10:46:14.660  5895  5895 I bt_bluedroid: get_profile_interface pan
10-06 10:46:14.661  5895  5911 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-06 10:46:14.664  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
,10-06 10:46:14.664  5895  5895 D BluetoothMapService: Received start request. Starting profile...
10-06 10:46:14.664  5895  5895 D BluetoothMapService: start()
10-06 10:46:14.664  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-06 10:46:14.667  5895  5895 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-06 10:46:14.668  5895  5895 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-06 10:46:14.668  5895  5895 D BluetoothMapAppObserver: createReceiver()
10-06 10:46:14.669  5895  5895 D BluetoothMapAppObserver: initObservers()
10-06 10:46:14.670  5895  5895 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-06 10:46:14.676  5895  5895 V SapService: SapBinder()
,10-06 10:46:14.676  5895  5895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
10-06 10:46:14.677  5895  5895 D SapService: Received start request. Starting profile...
10-06 10:46:14.677  5895  5895 V SapService: start()
,10-06 10:46:14.678  5895  5895 V BluetoothAdapterState: isTurningOff()=false
10-06 10:46:14.678  5895  5895 V BluetoothAdapterState: isTurningOn()=true
,10-06 10:46:14.678  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:14.678  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isTurningOff()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isTurningOn()=true
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:14.679  5895  5924 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isTurningOff()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isTurningOn()=true
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isTurningOff()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isTurningOn()=true
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
,10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isTurningOff()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isTurningOn()=true
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:14.679  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:14.680  5895  5895 V BluetoothAdapterState: isTurningOff()=false
10-06 10:46:14.680  5895  5895 V BluetoothAdapterState: isTurningOn()=true
10-06 10:46:14.680  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:14.680  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
10-06 10:46:14.680  5895  5895 V BluetoothAdapterState: isTurningOff()=false
10-06 10:46:14.680  5895  5895 V BluetoothAdapterState: isTurningOn()=true
10-06 10:46:14.680  5895  5895 V BluetoothAdapterState: isBleTurningOn()=false
10-06 10:46:14.681  5895  5895 V BluetoothAdapterState: isBleTurningOff()=false
,10-06 10:46:14.681  5895  5907 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-06 10:46:14.681  5895  5907 D BluetoothAdapterProperties: ScanMode =  20
10-06 10:46:14.681  5895  5907 D BluetoothAdapterProperties: State =  11
10-06 10:46:14.681  5895  5907 D BluetoothAdapterProperties: Setting state to 12
10-06 10:46:14.681  5895  5907 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-06 10:46:14.682  5895  5907 I BluetoothAdapterState: Entering OnState
10-06 10:46:14.682  3118  3975 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-06 10:46:14.685  5895  5911 D BluetoothAdapterProperties: Scan Mode:21
,10-06 10:46:14.685  5895  5911 D BluetoothAdapterProperties: Discoverable Timeout:120
10-06 10:46:14.685  3118  3131 D BluetoothMap: onBluetoothStateChange: up=true
10-06 10:46:14.686  5617  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-06 10:46:14.686  3118  3118 D BluetoothA2dp: Proxy object connected
10-06 10:46:14.688  3118  3975 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-06 10:46:14.689  3118  3118 D BluetoothMap: Proxy object connected
10-06 10:46:14.689  3118  3118 D MapProfile: Bluetooth service connected
10-06 10:46:14.689  3118  3118 D BluetoothMap: getConnectedDevices()
,10-06 10:46:14.690  3118  3132 D BluetoothPbap: onBluetoothStateChange: up=true
,10-06 10:46:14.692  3118  3118 D BluetoothInputDevice: Proxy object connected
,10-06 10:46:14.692  3118  3118 D HidProfile: Bluetooth service connected
10-06 10:46:14.692  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:14.692  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:14.692  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:14.692  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:46:14.692  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:14.692  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:14.692  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:14.692  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:46:14.693  3118  3979 D BluetoothPan: onBluetoothStateChange on: true
10-06 10:46:14.694   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-06 10:46:14.694  3776  4035 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:46:14.694  5895  5895 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-06 10:46:14.695  5677  5687 D BluetoothPan: onBluetoothStateChange on: true
10-06 10:46:14.695  5895  5895 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-06 10:46:14.695  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-06 10:46:14.696  5895  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-06 10:46:14.698  5895  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-06 10:46:14.698  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:14.698  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:14.698  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:14.698  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:46:14.698  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:14.698  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:14.698  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:14.698  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:46:14.698  5677  5690 D BluetoothA2dp: onBluetoothStateChange: up=true
10-06 10:46:14.699  5895  5895 D ObexServerSockets: Succeed to create listening sockets 
10-06 10:46:14.699  5895  5895 D ObexServerSockets0: startAccept()
10-06 10:46:14.699  5895  5895 D ObexServerSockets0: prepareForNewConnect()
10-06 10:46:14.700  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:46:14.700   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:46:14.701  5677  5687 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:46:14.701  5895  5895 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-06 10:46:14.701  5895  5895 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-06 10:46:14.701  5677  5690 D BluetoothPbap: onBluetoothStateChange: up=true
10-06 10:46:14.701  5895  5933 D ObexServerSockets0: Accepting socket connection...
10-06 10:46:14.702  5677  5677 D BluetoothA2dp: Proxy object connected
10-06 10:46:14.702  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
10-06 10:46:14.702  5895  5934 D ObexServerSockets0: Accepting socket connection...
10-06 10:46:14.702  3118  3118 D PanProfile: Bluetooth service connected
10-06 10:46:14.704  3118  3131 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:46:14.704   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-06 10:46:14.704   928   928 D BluetoothA2dp: Proxy object connected
10-06 10:46:14.705  5677  5687 D BluetoothMap: onBluetoothStateChange: up=true
10-06 10:46:14.706  5677  5687 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-06 10:46:14.707   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-06 10:46:14.708   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-06 10:46:14.709  5895  5895 D BluetoothMapService: onReceive
10-06 10:46:14.709  5895  5895 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-06 10:46:14.709  5895  5895 D BluetoothMapService: STATE_ON
,10-06 10:46:14.709  5617  5617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-06 10:46:14.711  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:14.712  5677  5677 D BluetoothPan: BluetoothPAN Proxy object connected
10-06 10:46:14.712  5677  5677 D PanProfile: Bluetooth service connected
,10-06 10:46:14.712  5677  5677 D BluetoothMap: Proxy object connected
10-06 10:46:14.712  5677  5677 D MapProfile: Bluetooth service connected
10-06 10:46:14.712  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:14.712  5677  5677 D BluetoothMap: getConnectedDevices()
10-06 10:46:14.713  5677  5677 D BluetoothInputDevice: Proxy object connected
10-06 10:46:14.714  5677  5677 D HidProfile: Bluetooth service connected
10-06 10:46:14.715  5895  5935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-06 10:46:14.717  5895  5935 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-06 10:46:14.717  5895  5935 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-06 10:46:14.720  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-06 10:46:14.726  5677  5677 D DockEventReceiver: finishStartingService: stopping service
10-06 10:46:14.726  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-06 10:46:14.733  5677  5677 D BluetoothPbap: Proxy object connected
10-06 10:46:14.733  5677  5677 D PbapServerProfile: Bluetooth service connected
,10-06 10:46:14.733  5895  5895 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-06 10:46:14.733  5895  5895 D ObexServerSockets0: prepareForNewConnect()
10-06 10:46:14.734  3118  3118 D BluetoothPbap: Proxy object connected
10-06 10:46:14.734  3118  3118 D PbapServerProfile: Bluetooth service connected
,10-06 10:46:14.743  5895  5939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-06 10:46:14.754  5895  5943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-06 10:46:14.755  5895  5943 I BtOppRfcommListener: Accept thread started.
,10-06 10:46:14.795  5677  5690 D BluetoothHeadset: Proxy object connected
,10-06 10:46:14.795   928   928 D BluetoothHeadset: Proxy object connected
10-06 10:46:14.796   928   928 D BluetoothHeadset: Proxy object connected
10-06 10:46:14.796   928   928 D BluetoothHeadset: Proxy object connected
10-06 10:46:14.796  3776  3802 D BluetoothHeadset: Proxy object connected
10-06 10:46:14.796  3118  3132 D BluetoothHeadset: Proxy object connected
10-06 10:46:14.796  3118  3118 D HeadsetProfile: Bluetooth service connected
,10-06 10:46:14.796  3776  3808 D BluetoothHeadset: Proxy object connected
,10-06 10:46:14.798  5677  5677 D HeadsetProfile: Bluetooth service connected
,10-06 10:46:14.801   928   945 D BluetoothHeadset: Proxy object connected
,10-06 10:46:14.801  5677  5687 D BluetoothHeadset: Proxy object connected
10-06 10:46:14.802  5677  5677 D HeadsetProfile: Bluetooth service connected
,10-06 10:46:14.804  3118  3979 D BluetoothHeadset: Proxy object connected
10-06 10:46:14.804  3118  3118 D HeadsetProfile: Bluetooth service connected
,10-06 10:46:14.808   928   945 D BluetoothHeadset: Proxy object connected
,10-06 10:46:18.595  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:18.595  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:18.595  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:18.595  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-06 10:46:18.595  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:18.595  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:18.595  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:18.595  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-06 10:46:18.600  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-06 10:46:18.601  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:46:18.602  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc43a8b removed from the list
10-06 10:46:18.602  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:46:18.602  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-06 10:46:18.602  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:18.605  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-06 10:46:18.605  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee57768 added. We now have 4 listener(s)
10-06 10:46:18.606  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-06 10:46:18.609   928  3741 D WifiService: setWifiEnabled: false pid=5617, uid=10077
,10-06 10:46:18.610   928  3741 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-06 10:46:20.781   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:46:21.782   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:46:22.783   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:46:23.620  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:46:23.621   928  3744 D WifiService: setWifiEnabled: true pid=5617, uid=10077
10-06 10:46:23.621   928  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-06 10:46:23.630   509   923 D SoftapController: Softap fwReload - Ok
,10-06 10:46:23.636   509   923 D CommandListener: Setting iface cfg
10-06 10:46:23.636   509   923 D CommandListener: Trying to bring down wlan0
,10-06 10:46:23.637   509   923 D CommandListener: Clearing all IP addresses on wlan0
,10-06 10:46:23.640   928  2959 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-06 10:46:23.784   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:46:24.245   928  2959 D wifi    : set interface wlan0 flags (UP)
,10-06 10:46:24.246   928  2959 I WifiHAL : Initializing wifi
10-06 10:46:24.247   928  2959 I WifiHAL : Creating socket
,10-06 10:46:24.253   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-06 10:46:24.254   928  2959 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-06 10:46:24.254   928  2959 D wifi    : Did set static halHandle = 0x7f63a4d680
10-06 10:46:24.254   928  2959 D wifi    : halHandle = 0x7f63a4d680, mVM = 0x7f8008d140, mCls = 0x101512
10-06 10:46:24.254   928  2959 D wifi    : array field set
,10-06 10:46:24.255   928  2959 I WifiNative-HAL: interface[0] = wlan0
,10-06 10:46:24.257   928  5948 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547132593792
,10-06 10:46:24.258   928  5948 D wifi    : waitForHalEvents called, vm = 0x7f8008d140, obj = 0x101512, env = 0x7f650fe080
,10-06 10:46:24.324  5949  5949 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-06 10:46:24.347  5949  5949 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-06 10:46:24.360   928  2959 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-06 10:46:24.368  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:46:24.372  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:46:24.387  5949  5949 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-06 10:46:24.388  5949  5949 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-06 10:46:24.404   928  2959 D WifiConfigStore: Loading config and enabling all networks 
,10-06 10:46:24.409  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:24.409  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:24.409  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:24.409  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:24.409  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:24.409  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:24.409  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:24.409  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:46:24.411  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:46:24.414  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:24.414  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:24.414  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:24.414  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:24.414  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:24.414  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:24.414  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:24.414  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-06 10:46:24.416  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:46:24.417   928  2959 D WifiConfigStore: loaded 0 passpoint configs
10-06 10:46:24.417   928  2959 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-06 10:46:24.417   928  2959 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-06 10:46:24.418   928  2959 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-06 10:46:24.419   928  2959 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-06 10:46:24.420   928  2959 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-06 10:46:24.420   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-06 10:46:24.420   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-06 10:46:24.423   928  2959 D WifiNative-HAL: Setting external_sim to 1
,10-06 10:46:24.423  4406  4406 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-06 10:46:24.424   928  2959 D wifi    : setting dfs flag to true, 0x7f60070e20
10-06 10:46:24.424   928  2959 D WifiStateMachine: Setting OUI to DA-A1-19
10-06 10:46:24.424   928  2959 D wifi    : setting scan oui 0x7f60070e20
10-06 10:46:24.425   928  2959 D WifiHAL : Sending mac address OUI
,10-06 10:46:24.429   928  2959 E native  : do suspend false
,10-06 10:46:24.441   928  2959 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-06 10:46:24.441   928   928 D RttService: SCAN_AVAILABLE : 3
10-06 10:46:24.441   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-06 10:46:24.442   928  3074 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-06 10:46:24.443   509   923 D CommandListener: Setting iface cfg
,10-06 10:46:24.448   928  2948 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
10-06 10:46:24.448   928  2948 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-06 10:46:24.463   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302761 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
10-06 10:46:24.466   928  2948 D WifiNative-HAL: p2pGetDeviceAddress
10-06 10:46:24.466   928  2948 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-06 10:46:24.786   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:46:25.787   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-06 10:46:27.608  5949  5949 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-06 10:46:27.613  5949  5949 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-06 10:46:27.618  5949  5949 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-06 10:46:27.623  5949  5949 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-06 10:46:27.673   928  2959 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-06 10:46:27.675   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-06 10:46:27.676   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-06 10:46:27.687   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-06 10:46:27.721   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-06 10:46:27.724  5949  5949 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-06 10:46:28.155  5949  5949 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-06 10:46:28.188  5949  5949 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-06 10:46:28.190  5949  5949 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-06 10:46:28.201   928  2959 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-06 10:46:28.201   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-06 10:46:28.201   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-06 10:46:28.216   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-06 10:46:28.228   509   923 D CommandListener: Setting iface cfg
,10-06 10:46:28.234   928  2959 D WifiStateMachine: Start Dhcp Watchdog 3
,10-06 10:46:28.240   928  5954 D DhcpClient: Receive thread started
,10-06 10:46:28.245   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-06 10:46:28.245   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-06 10:46:28.245   928  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-06 10:46:28.326   928  2959 E native  : do suspend false
,10-06 10:46:28.337   928  5953 D DhcpClient: Broadcasting DHCPDISCOVER
,10-06 10:46:28.643  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:28.643  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:28.643  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:28.643  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:28.643  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:28.643  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:28.643  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:28.643  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-06 10:46:28.648  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-06 10:46:28.649  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-06 10:46:28.649  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee57768 removed from the list
10-06 10:46:28.649  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:46:28.649  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.649  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:46:28.655  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-06 10:46:28.656  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-06 10:46:28.659  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c13ef69 Bundle[{}]
10-06 10:46:28.661  5617  5663 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-06 10:46:28.661  5617  5663 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-06 10:46:28.663  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-06 10:46:28.663  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-06 10:46:28.664  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-06 10:46:28.665  5617  5663 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-06 10:46:28.672  5617  5663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
,10-06 10:46:28.673  5617  5663 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-06 10:46:28.673  5617  5663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
10-06 10:46:28.674  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-06 10:46:28.674  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@485b781 added. We now have 3 listener(s)
,10-06 10:46:28.676  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.677  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.677  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.677  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.677  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99ea026 added. We now have 4 listener(s)
10-06 10:46:28.677  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-06 10:46:28.678  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-06 10:46:28.682  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-06 10:46:28.685  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:46:28.685  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:28.685  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:28.685  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:28.685  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:28.685  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:28.685  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:28.685  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-06 10:46:28.687  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-06 10:46:28.688  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:46:28.688  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-06 10:46:28.688  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64ea214 added. We now have 4 listener(s)
10-06 10:46:28.690  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.690  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.690  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-06 10:46:28.690  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.690  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:28.690  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4554abd added. We now have 5 listener(s)
10-06 10:46:28.691  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:46:28.691  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:46:28.691  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:46:28.691  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:46:28.691  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.691  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.691  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:46:28.691  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.691  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.691  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@485b781 removed from the list
10-06 10:46:28.691  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.691  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99ea026 removed from the list
10-06 10:46:28.693  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:28.693  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
,10-06 10:46:28.693  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.694  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.694  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:46:28.695  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:46:28.695  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.695  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.695  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99ea026 not in the list
,10-06 10:46:28.696  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.696  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:46:28.697  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.697  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:46:28.697  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.697  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4554abd removed from the list
10-06 10:46:28.697  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.697  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.697  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.697  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.697  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.697  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64ea214 removed from the list
,10-06 10:46:28.698  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-06 10:46:28.698  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4498b2 added. We now have 3 listener(s)
10-06 10:46:28.700  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.700  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.700  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.700  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.700  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f677003 added. We now have 4 listener(s)
10-06 10:46:28.700  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:46:28.701  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-06 10:46:28.704  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-06 10:46:28.707  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:46:28.707  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:28.707  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:28.707  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:28.707  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:28.707  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:28.707  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:28.707  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-06 10:46:28.709  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-06 10:46:28.709  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:46:28.709  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-06 10:46:28.709  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@690d5b9 added. We now have 4 listener(s)
10-06 10:46:28.710  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:28.710  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.711  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.711  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.711  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.711  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df8dfe added. We now have 5 listener(s)
10-06 10:46:28.711  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:46:28.711  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:46:28.711  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-06 10:46:28.711  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-06 10:46:28.711  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:46:28.711  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-06 10:46:28.711  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-06 10:46:28.714  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-06 10:46:28.714  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-06 10:46:28.717  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-06 10:46:28.718  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-06 10:46:28.718  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-06 10:46:28.721  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-06 10:46:28.721  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-06 10:46:28.721  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-06 10:46:28.721  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-06 10:46:28.721  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-06 10:46:28.722  5617  5663 D BluetoothAdapter: STATE_ON
,10-06 10:46:28.725  5895  5906 D BtGatt.GattService: registerClient() - UUID=8ef8093c-5269-47bc-abb0-9c1ec05d5ea5
,10-06 10:46:28.725  5895  5911 D BtGatt.GattService: onClientRegistered() - UUID=8ef8093c-5269-47bc-abb0-9c1ec05d5ea5, clientIf=5
,10-06 10:46:28.726  5617  5627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-06 10:46:28.727  5895  5905 D BtGatt.GattService: start scan with filters
10-06 10:46:28.730  5895  5914 D BtGatt.ScanManager: handling starting scan
10-06 10:46:28.730  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-06 10:46:28.731  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-06 10:46:28.731  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:46:28.731  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-06 10:46:28.731  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-06 10:46:28.731  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-06 10:46:28.731  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-06 10:46:28.732  5895  5914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7ec09a2
,10-06 10:46:28.734  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-06 10:46:28.734  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-06 10:46:28.734  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-06 10:46:28.735  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-06 10:46:28.737  5617  5663 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-06 10:46:28.737  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-06 10:46:28.737  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-06 10:46:28.737  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.738  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-06 10:46:28.738  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.738  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-06 10:46:28.738  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-06 10:46:28.738  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-06 10:46:28.738  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-06 10:46:28.738  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-06 10:46:28.738  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-06 10:46:28.739  5617  5663 D BluetoothAdapter: STATE_ON
10-06 10:46:28.739  5895  5922 D BtGatt.GattService: stopScan() - queue size =1
,10-06 10:46:28.740  5895  5911 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-06 10:46:28.740  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.740  5895  5931 D BtGatt.GattService: unregisterClient() - clientIf=5
10-06 10:46:28.740  5895  5914 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-06 10:46:28.741  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-06 10:46:28.741  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-06 10:46:28.741  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-06 10:46:28.741  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:46:28.741  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-06 10:46:28.741  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-06 10:46:28.741  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-06 10:46:28.741  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-06 10:46:28.742  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-06 10:46:28.742  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-06 10:46:28.742  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-06 10:46:28.742  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-06 10:46:28.743  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-06 10:46:28.743  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-06 10:46:28.745  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:46:28.745  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:46:28.745  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-06 10:46:28.746  5895  5911 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-06 10:46:28.746  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:46:28.747  5895  5914 D BtGatt.ScanManager: Starting BLE batch scan
10-06 10:46:28.747  5895  5914 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-06 10:46:28.747   928  5954 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-06 10:46:28.748   928  5953 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
10-06 10:46:28.748  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-06 10:46:28.748  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-06 10:46:28.748  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:46:28.748  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.748  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.748  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:46:28.748  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.748  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.749  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4498b2 removed from the list
10-06 10:46:28.749  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.749   928  5953 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
10-06 10:46:28.749  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f677003 removed from the list
,10-06 10:46:28.749  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:46:28.749  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.749  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.749  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.750  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:46:28.750  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.750  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.750  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f677003 not in the list
10-06 10:46:28.750  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.750  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:46:28.751  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.752  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:46:28.752  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.752  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df8dfe removed from the list
10-06 10:46:28.752  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.752  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.752  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.752  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.752  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.752  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@690d5b9 removed from the list
10-06 10:46:28.753  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-06 10:46:28.753  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a28c0a added. We now have 3 listener(s)
,10-06 10:46:28.754  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.754  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.754  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.755  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.755  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cdc7b added. We now have 4 listener(s)
10-06 10:46:28.755  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:46:28.756  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-06 10:46:28.757  5895  5911 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-06 10:46:28.757  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:46:28.759  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-06 10:46:28.762   928  5954 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-06 10:46:28.762   928  5953 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-06 10:46:28.763   509   923 D CommandListener: Setting iface cfg
10-06 10:46:28.764  5895  5911 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-06 10:46:28.764  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:46:28.765   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-06 10:46:28.765  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:46:28.765  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:28.765  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:28.765  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:28.765  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:28.765  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-06 10:46:28.765  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-06 10:46:28.765  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-06 10:46:28.767   928  5953 D DhcpClient: Scheduling renewal in 86399s
,10-06 10:46:28.768  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-06 10:46:28.768  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:46:28.768  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-06 10:46:28.768  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7aa82f1 added. We now have 4 listener(s)
10-06 10:46:28.769  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.770  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.770  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.770  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.770  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee55ed6 added. We now have 5 listener(s)
10-06 10:46:28.770  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:46:28.770  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:46:28.771  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:46:28.771  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-06 10:46:28.771  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-06 10:46:28.771  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-06 10:46:28.771  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-06 10:46:28.771  5895  5911 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-06 10:46:28.771  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:28.771  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.773  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:28.773  5895  5914 D BtGatt.ScanManager: stopping BLe Batch
10-06 10:46:28.774   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-06 10:46:28.775   928  2959 D WifiConfigStore: No blacklist allowed without epno enabled
10-06 10:46:28.775  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-06 10:46:28.775  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-06 10:46:28.775   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-06 10:46:28.776   928  2959 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-06 10:46:28.779  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-06 10:46:28.780  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-06 10:46:28.780  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-06 10:46:28.780   928  2973 D ConnectivityService: Adding iface wlan0 to network 102
,10-06 10:46:28.783  5895  5911 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-06 10:46:28.783  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.783  5895  5914 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-06 10:46:28.787  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-06 10:46:28.788  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-06 10:46:28.788  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-06 10:46:28.788  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-06 10:46:28.788  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-06 10:46:28.788  5895  5911 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-06 10:46:28.788  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:46:28.789  5617  5663 D BluetoothAdapter: STATE_ON
10-06 10:46:28.791  5895  5905 D BtGatt.GattService: registerClient() - UUID=7aaeaa1e-5a58-4bb3-ad5b-84f0688440ce
10-06 10:46:28.792  5895  5911 D BtGatt.GattService: onClientRegistered() - UUID=7aaeaa1e-5a58-4bb3-ad5b-84f0688440ce, clientIf=5
,10-06 10:46:28.795  5617  5627 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-06 10:46:28.796  5895  5922 D BtGatt.GattService: start scan with filters
10-06 10:46:28.798  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-06 10:46:28.798  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-06 10:46:28.798  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:46:28.798  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-06 10:46:28.798  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-06 10:46:28.798  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-06 10:46:28.798  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-06 10:46:28.798  5895  5914 D BtGatt.ScanManager: handling starting scan
10-06 10:46:28.804  5895  5911 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-06 10:46:28.805  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.805  5895  5914 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-06 10:46:28.805  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-06 10:46:28.805  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-06 10:46:28.805  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-06 10:46:28.805   928  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-06 10:46:28.805   928  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
10-06 10:46:28.806  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-06 10:46:28.806   928  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
10-06 10:46:28.807   928  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
10-06 10:46:28.808  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:46:28.808  5617  5663 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-06 10:46:28.808  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:46:28.808  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:46:28.808  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-06 10:46:28.809  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.809  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.809  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-06 10:46:28.809  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.809  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.809  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a28c0a removed from the list
10-06 10:46:28.809  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.809  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cdc7b removed from the list
10-06 10:46:28.809  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:46:28.809   928  2973 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-06 10:46:28.809  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:46:28.810  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.810  5895  5911 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-06 10:46:28.810  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-06 10:46:28.810  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.810  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.810  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:46:28.810  5895  5914 D BtGatt.ScanManager: Starting BLE batch scan
10-06 10:46:28.810  5895  5914 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-06 10:46:28.813  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:46:28.813  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.813  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.814  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cdc7b not in the list
10-06 10:46:28.814  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-06 10:46:28.814  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-06 10:46:28.814  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-06 10:46:28.814  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-06 10:46:28.814  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-06 10:46:28.815  5617  5663 D BluetoothAdapter: STATE_ON
,10-06 10:46:28.816  5895  5905 D BtGatt.GattService: stopScan() - queue size =1
10-06 10:46:28.817   928  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-06 10:46:28.819  5895  5922 D BtGatt.GattService: unregisterClient() - clientIf=5
10-06 10:46:28.819  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-06 10:46:28.819  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-06 10:46:28.819  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-06 10:46:28.819  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:46:28.819  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-06 10:46:28.819  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-06 10:46:28.819  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-06 10:46:28.820  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-06 10:46:28.821  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:46:28.821  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-06 10:46:28.821  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-06 10:46:28.821  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-06 10:46:28.821  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-06 10:46:28.821  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.821  5895  5911 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-06 10:46:28.822  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:46:28.822   928  2973 D ConnectivityService: scheduleUnvalidatedPrompt 102
10-06 10:46:28.822   928  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-06 10:46:28.822   928  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-06 10:46:28.822   928  2959 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-06 10:46:28.822   928  2973 D ConnectivityService:    accepting network in place of null
10-06 10:46:28.822   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-06 10:46:28.822  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.823  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-06 10:46:28.823  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.823  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee55ed6 removed from the list
10-06 10:46:28.823  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:46:28.823  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.823  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:46:28.823  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.823  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:46:28.823   928  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-06 10:46:28.823  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-06 10:46:28.823  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.823  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.823  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7aa82f1 removed from the list
10-06 10:46:28.824  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-06 10:46:28.824  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab09262 added. We now have 3 listener(s)
10-06 10:46:28.825  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.825  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.826  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.826  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3945ff3 added. We now have 4 listener(s)
10-06 10:46:28.826  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:46:28.826  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-06 10:46:28.828  5895  5911 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-06 10:46:28.828  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.829  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:46:28.832  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:46:28.832  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:28.832  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:28.832  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:28.832  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:28.832  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:46:28.832  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:46:28.832  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:46:28.833  5895  5911 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-06 10:46:28.833  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.833  5895  5914 D BtGatt.ScanManager: stopping BLe Batch
10-06 10:46:28.835  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:46:28.836  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:46:28.836  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-06 10:46:28.836  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b359f29 added. We now have 4 listener(s)
10-06 10:46:28.837  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.837  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.837  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.838  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.838  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0972ae added. We now have 5 listener(s)
10-06 10:46:28.838  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:28.838  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-06 10:46:28.838  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:46:28.838  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-06 10:46:28.838  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-06 10:46:28.838  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:46:28.838  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-06 10:46:28.839  5895  5911 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-06 10:46:28.839  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.840  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-06 10:46:28.840  5895  5914 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-06 10:46:28.840  5617  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-06 10:46:28.841  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-06 10:46:28.844  5895  5911 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-06 10:46:28.844  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:46:28.845  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-06 10:46:28.846  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-06 10:46:28.846  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-06 10:46:28.847   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-06 10:46:28.848  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-06 10:46:28.848   928  5952 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
10-06 10:46:28.849  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-06 10:46:28.849  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-06 10:46:28.849  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-06 10:46:28.849  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-06 10:46:28.849  5617  5663 D BluetoothAdapter: STATE_ON
,10-06 10:46:28.851  5895  5905 D BtGatt.GattService: registerClient() - UUID=5b2381fe-93bb-4f3d-94f7-c053f3225cd9
,10-06 10:46:28.851  5895  5911 D BtGatt.GattService: onClientRegistered() - UUID=5b2381fe-93bb-4f3d-94f7-c053f3225cd9, clientIf=5
,10-06 10:46:28.851  5617  5628 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-06 10:46:28.852  5895  5906 D BtGatt.GattService: start scan with filters
10-06 10:46:28.854  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-06 10:46:28.854  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-06 10:46:28.854  5895  5914 D BtGatt.ScanManager: handling starting scan
,10-06 10:46:28.854  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:46:28.854  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-06 10:46:28.854  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-06 10:46:28.854  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-06 10:46:28.854  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-06 10:46:28.856  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-06 10:46:28.856  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-06 10:46:28.856  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-06 10:46:28.857  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-06 10:46:28.859  5895  5911 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-06 10:46:28.859  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.859  5895  5914 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-06 10:46:28.860  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:46:28.860  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:46:28.860  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:46:28.860  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.860  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.861  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-06 10:46:28.861  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.861  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.861  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab09262 removed from the list
10-06 10:46:28.861  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.861  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3945ff3 removed from the list
10-06 10:46:28.861  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:46:28.861  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:46:28.861  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.862  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-06 10:46:28.862  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.862  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:46:28.862  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:46:28.862  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.862  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.863  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3945ff3 not in the list
10-06 10:46:28.863  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-06 10:46:28.863  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-06 10:46:28.863  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-06 10:46:28.863  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-06 10:46:28.863  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-06 10:46:28.863  5617  5663 D BluetoothAdapter: STATE_ON
,10-06 10:46:28.863  5895  5911 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-06 10:46:28.863  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.864  5895  5914 D BtGatt.ScanManager: Starting BLE batch scan
10-06 10:46:28.864  5895  5914 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-06 10:46:28.864  5895  5906 D BtGatt.GattService: stopScan() - queue size =1
,10-06 10:46:28.864  5895  5922 D BtGatt.GattService: unregisterClient() - clientIf=5
10-06 10:46:28.864  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-06 10:46:28.864  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-06 10:46:28.864  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-06 10:46:28.865  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-06 10:46:28.865  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-06 10:46:28.865  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-06 10:46:28.865  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-06 10:46:28.865  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-06 10:46:28.866  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:46:28.866  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-06 10:46:28.866  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-06 10:46:28.866  5617  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-06 10:46:28.866  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-06 10:46:28.866  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.866   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-06 10:46:28.867  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.867  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-06 10:46:28.867  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.867  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0972ae removed from the list
10-06 10:46:28.867  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:46:28.867  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.867  5617  5617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-06 10:46:28.867  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.867  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.867  5617  5617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-06 10:46:28.867  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.867  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.867  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b359f29 removed from the list
10-06 10:46:28.868  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-06 10:46:28.868  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fe0bba added. We now have 3 listener(s)
,10-06 10:46:28.869  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.869  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-06 10:46:28.869  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.869  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.869  3737  3899 W QCNEJ   : |CORE| network available: 102
10-06 10:46:28.869  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@499da6b added. We now have 4 listener(s)
10-06 10:46:28.869  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-06 10:46:28.870   928  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-06 10:46:28.870   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-06 10:46:28.870  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-06 10:46:28.871  3737  3899 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-06 10:46:28.871   928  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-06 10:46:28.872  3737  3899 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-06 10:46:28.873  3737  3899 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-06 10:46:28.873   928   945 D Tethering: MasterInitialState.processMessage what=3
10-06 10:46:28.873  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-06 10:46:28.877  5895  5911 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-06 10:46:28.877  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:46:28.879  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:28.879  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:28.879  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:28.879  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:28.879  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:28.879  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:46:28.879  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:46:28.879  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-06 10:46:28.881  5617  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-06 10:46:28.881  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:28.881  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:28.881  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:28.881  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:28.881  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:46:28.881  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:46:28.881  5617  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-06 10:46:28.882  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-06 10:46:28.883  5895  5911 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-06 10:46:28.883  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.883  5031  5044 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-06 10:46:28.883  5031  5044 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-06 10:46:28.883  5031  5044 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-06 10:46:28.884  5031  5044 E SarControlService: no key has been found,reset the power
,10-06 10:46:28.884  5031  5069 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-06 10:46:28.884  5031  5069 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-06 10:46:28.884  5031  5069 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-06 10:46:28.884  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-06 10:46:28.885  5057  5057 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-06 10:46:28.885  5617  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:46:28.885  5617  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
10-06 10:46:28.885  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-06 10:46:28.885  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2110a61 added. We now have 4 listener(s)
10-06 10:46:28.885  5031  5069 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-06 10:46:28.885  5031  5069 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-06 10:46:28.886  5031  5069 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-06 10:46:28.886  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-06 10:46:28.886  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-06 10:46:28.886  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-06 10:46:28.887  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-06 10:46:28.887  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a712986 added. We now have 5 listener(s)
10-06 10:46:28.887  5617  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-06 10:46:28.887  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-06 10:46:28.887  5057  5057 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-06 10:46:28.887  5617  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-06 10:46:28.887  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:46:28.887  5617  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-06 10:46:28.887  5617  5617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-06 10:46:28.887  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-06 10:46:28.887  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-06 10:46:28.887  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-06 10:46:28.887  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-06 10:46:28.887  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-06 10:46:28.887  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-06 10:46:28.887  5617  5617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-06 10:46:28.887  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.887  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.887  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-06 10:46:28.887  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.887  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.887  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fe0bba removed from the list
,10-06 10:46:28.887  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.887  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@499da6b removed from the list
10-06 10:46:28.888  5617  5663 D io.jxcore.node.ConnectivityMonitor: stop
10-06 10:46:28.888  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.888  4005  4005 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-06 10:46:28.888  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.888  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.888  5895  5911 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-06 10:46:28.888  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.888  5895  5914 D BtGatt.ScanManager: stopping BLe Batch
10-06 10:46:28.889  5617  5617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-06 10:46:28.890  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:46:28.890  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.890  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.890  5617  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@499da6b not in the list
10-06 10:46:28.890  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.890  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.891  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-06 10:46:28.891  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-06 10:46:28.891  5617  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-06 10:46:28.891  5617  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a712986 removed from the list
10-06 10:46:28.891  5617  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-06 10:46:28.891  5617  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-06 10:46:28.891  5617  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-06 10:46:28.891  5617  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-06 10:46:28.891  5617  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-06 10:46:28.891  5617  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2110a61 removed from the list
10-06 10:46:28.892  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-06 10:46:28.892  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivi,ty: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-06 10:46:28.892  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-06 10:46:28.892  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-06 10:46:28.892  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-06 10:46:28.892  4005  4005 D SystemUpdateService: onCreate
10-06 10:46:28.893  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-06 10:46:28.894  5895  5911 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-06 10:46:28.894  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-06 10:46:28.894  5895  5914 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-06 10:46:28.896  5057  5071 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e998b5 HexData = [00000000f003000000000000ffffffff]
10-06 10:46:28.896  5057  5071 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-06 10:46:28.896  5057  5071 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-06 10:46:28.896  5057  5071 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5e998b5 HexData = [00000000f103000000000000ffffffff]
10-06 10:46:28.896  5057  5071 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-06 10:46:28.896  5057  5071 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-06 10:46:28.896  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-06 10:46:28.897  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-06 10:46:28.897  5057  5057 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-06 10:46:28.897  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-06 10:46:28.898  4005  4005 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-06 10:46:28.898  5895  5911 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-06 10:46:28.898  5895  5911 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-06 10:46:28.907  4005  4005 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-06 10:46:28.916  4005  5964 I SystemUpdateService: active receiver: enabled
,10-06 10:46:28.918  4005  4005 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-06 10:46:28.919  4005  4005 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-06 10:46:28.921  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-06 10:46:28.924  5748  5748 D SprintDMHelper: simOperator: 
,10-06 10:46:28.924  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-06 10:46:28.930  4005  5385 I iu.UploadsManager: num queued entries: 0
,10-06 10:46:28.935  4005  5385 I iu.UploadsManager: num updated entries: 0
,10-06 10:46:28.943  4005  5385 I iu.SyncManager: NEXT; no task
,10-06 10:46:28.946  4005  5964 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-06 10:46:28.958  4005  5964 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-06 10:46:28.958  4005  5964 I SystemUpdateService: now status is 0 (complete)
10-06 10:46:28.958  4005  5964 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-06 10:46:28.958  4005  5964 I SystemUpdateService: file has been verified
10-06 10:46:28.959  4005  5964 I SystemUpdateService: OTA package size = 21989297
,10-06 10:46:28.964  4005  5964 I SystemUpdateService: showing system update notification
,10-06 10:46:28.973  4005  4005 D SystemUpdateService: onDestroy
,10-06 10:46:29.043  4406  5969 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-06 10:46:29.206   928  3741 D ConnectivityService: reportNetworkConnectivity(102, true) by 10012
,10-06 10:46:29.218   928  3744 D ConnectivityService: reportNetworkConnectivity(102, true) by 10012
,10-06 10:46:29.221   928   938 D ConnectivityService: reportNetworkConnectivity(102, true) by 10012
,10-06 10:46:29.246  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-06 10:46:29.323  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-06 10:46:29.368  5617  5617 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-06 10:46:29.392   928  5951 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-06 10:46:29.449   928  5951 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 06 Oct 2016 14:46:29 GMT], X-Android-Received-Millis=[1475765189447], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475765189422]}
,10-06 10:46:29.451   928  5951 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Forcing reevaluation for UID 10012
10-06 10:46:29.451   928  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-06 10:46:29.451   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,10-06 10:46:29.452   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-06 10:46:29.452   928  5951 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-06 10:46:29.456   928  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-06 10:46:29.480   928  5951 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 06 Oct 2016 14:46:29 GMT], X-Android-Received-Millis=[1475765189479], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475765189457]}
,10-06 10:46:29.480   928  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-06 10:46:29.481   928  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,10-06 10:46:31.036  5617  5976 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-06 10:46:31.036  5617  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:31.834  5617  5976 W !!      : call onHalfStreamCopied
,10-06 10:46:31.835  5617  5976 I testCopyDataAndClose: closing input stream
,10-06 10:46:32.608  5617  5976 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-06 10:46:32.608  5617  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-06 10:46:32.609  5617  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-06 10:46:36.386  5617  5977 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-06 10:46:36.386  5617  5977 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:36.828   928  2973 D ConnectivityService: handlePromptUnvalidated 102
,10-06 10:46:38.386  5617  5663 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 176. Connection data: Peer properties: [null null].
10-06 10:46:38.386  5617  5663 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:38.386  5617  5663 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 176, name: My test thread name)
,10-06 10:46:38.462  5617  5977 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-06 10:46:38.462  5617  5977 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-06 10:46:38.462  5617  5977 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,10-06 10:46:38.544  5617  5978 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-06 10:46:38.544  5617  5978 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:39.466   928  2959 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-06 10:46:40.162  5617  5978 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-06 10:46:40.162  5617  5978 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:40.162  5617  5978 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-06 10:46:40.162  5617  5978 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:40.162  5617  5978 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-06 10:46:40.163  5617  5978 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-06 10:46:40.163  5617  5978 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-06 10:46:40.163  5617  5978 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-06 10:46:40.163  5617  5978 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-06 10:46:40.163  5617  5978 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-06 10:46:40.163  5617  5978 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-06 10:46:43.889  5617  5979 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-06 10:46:43.889  5617  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: My test thread name). Connection data: Peer properties: [null null].
10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-06 10:46:43.890  5617  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-06 10:46:43.892  5617  5663 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-06 10:46:43.894  5617  5980 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-06 10:46:43.894  5617  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-06 10:46:43.895  5617  5980 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 184, thread name: My test thread name): Test exception.
10-06 10:46:43.895  5617  5980 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-06 10:46:43.895  5617  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-06 10:46:43.895  5617  5980 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-06 10:46:43.895  5617  5980 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-06 10:46:43.895  5617  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-06 10:46:43.900  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-06 10:46:43.900  5617  5663 I jxcore-log: 
,10-06 10:46:43.900  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-06 10:46:43.900  5617  5663 I jxcore-log: 
10-06 10:46:43.901  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-06 10:46:43.901  5617  5663 I jxcore-log: 
10-06 10:46:43.901  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-06 10:46:43.901  5617  5663 I jxcore-log: 
10-06 10:46:43.901  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG UnitTest_app: 'Total duration:  90806'
10-06 10:46:43.901  5617  5663 I jxcore-log: 
,10-06 10:46:43.904  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-06 10:46:43.904  5617  5663 I jxcore-log: 
,10-06 10:46:43.907  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.907  5617  5663 I jxcore-log: 
,10-06 10:46:43.908  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.908  5617  5663 I jxcore-log: 
10-06 10:46:43.908  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.908  5617  5663 I jxcore-log: 
10-06 10:46:43.908  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.908  5617  5663 I jxcore-log: 
10-06 10:46:43.909  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-06 10:46:43.909  5617  5663 I jxcore-log: 
10-06 10:46:43.909  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-06 10:46:43.909  5617  5663 I jxcore-log: 
10-06 10:46:43.909  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.909  5617  5663 I jxcore-log: 
,10-06 10:46:43.910  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.910  5617  5663 I jxcore-log: 
10-06 10:46:43.910  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-06 10:46:43.910  5617  5663 I jxcore-log: 
10-06 10:46:43.910  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-06 10:46:43.910  5617  5663 I jxcore-log: 
10-06 10:46:43.910  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-06 10:46:43.910  5617  5663 I jxcore-log: 
10-06 10:46:43.911  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.911  5617  5663 I jxcore-log: 
10-06 10:46:43.911  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.911  5617  5663 I jxcore-log: 
,10-06 10:46:43.911  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.911  5617  5663 I jxcore-log: 
10-06 10:46:43.911  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.911  5617  5663 I jxcore-log: 
10-06 10:46:43.912  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.912  5617  5663 I jxcore-log: 
10-06 10:46:43.912  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.912  5617  5663 I jxcore-log: 
,10-06 10:46:43.912  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.912  5617  5663 I jxcore-log: 
10-06 10:46:43.913  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.913  5617  5663 I jxcore-log: 
10-06 10:46:43.913  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.913  5617  5663 I jxcore-log: 
10-06 10:46:43.913  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.913  5617  5663 I jxcore-log: 
10-06 10:46:43.914  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.914  5617  5663 I jxcore-log: 
10-06 10:46:43.914  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.914  5617  5663 I jxcore-log: 
,10-06 10:46:43.915  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.915  5617  5663 I jxcore-log: 
10-06 10:46:43.916  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.916  5617  5663 I jxcore-log: 
,10-06 10:46:43.916  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.916  5617  5663 I jxcore-log: 
,10-06 10:46:43.916  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.916  5617  5663 I jxcore-log: 
10-06 10:46:43.916  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.916  5617  5663 I jxcore-log: 
10-06 10:46:43.917  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.917  5617  5663 I jxcore-log: 
10-06 10:46:43.917  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.917  5617  5663 I jxcore-log: 
10-06 10:46:43.917  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.917  5617  5663 I jxcore-log: 
,10-06 10:46:43.917  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.917  5617  5663 I jxcore-log: 
10-06 10:46:43.917  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.917  5617  5663 I jxcore-log: 
10-06 10:46:43.918  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.918  5617  5663 I jxcore-log: 
10-06 10:46:43.918  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.918  5617  5663 I jxcore-log: 
10-06 10:46:43.918  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.918  5617  5663 I jxcore-log: 
10-06 10:46:43.918  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.918  5617  5663 I jxcore-log: 
10-06 10:46:43.918  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-06 10:46:43.918  5617  5663 I jxcore-log: 
10-06 10:46:43.919  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.919  5617  5663 I jxcore-log: 
10-06 10:46:43.919  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.919  5617  5663 I jxcore-log: 
,10-06 10:46:43.919  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.919  5617  5663 I jxcore-log: 
10-06 10:46:43.919  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.919  5617  5663 I jxcore-log: 
10-06 10:46:43.920  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.920  5617  5663 I jxcore-log: 
10-06 10:46:43.920  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-06 10:46:43.920  5617  5663 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-06 10:46:43.920  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-06 10:46:43.920  5617  5663 I jxcore-log: 
10-06 10:46:43.920  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.920  5617  5663 I jxcore-log: 
10-06 10:46:43.920  5617  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-06 10:46:43.920  5617  5663 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-06 10:46:43.921  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.921  5617  5663 I jxcore-log: 
10-06 10:46:43.921  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.921  5617  5663 I jxcore-log: 
10-06 10:46:43.921  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-06 10:46:43.921  5617  5663 I jxcore-log: 
10-06 10:46:43.921  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-06 10:46:43.921  5617  5663 I jxcore-log: 
10-06 10:46:43.922  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-06 10:46:43.922  5617  5663 I jxcore-log: 
10-06 10:46:43.922  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-06 10:46:43.922  5617  5663 I jxcore-log: 
,10-06 10:46:43.923  5617  5617 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-06 10:46:43.927  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-06 10:46:43.927  5617  5663 I jxcore-log: 
10-06 10:46:43.927  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - WARN testUtils: 'myNameCallback not set!'
10-06 10:46:43.927  5617  5663 I jxcore-log: 
,10-06 10:46:43.928  5617  5663 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-06 10:46:43.929  5617  5663 I jxcore-log: 2016-10-06 14:46:43 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-06 10:46:43.929  5617  5663 I jxcore-log: 
,10-06 10:46:45.986  5617  5663 I jxcore-log: 2016-10-06 14:46:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-06 10:46:45.986  5617  5663 I jxcore-log: 
,10-06 10:46:46.330  5617  5663 I jxcore-log: 2016-10-06 14:46:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-06 10:46:46.330  5617  5663 I jxcore-log: 
,10-06 10:46:46.344  5617  5663 I jxcore-log: 2016-10-06 14:46:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-06 10:46:46.344  5617  5663 I jxcore-log: 
,10-06 10:46:47.457  5617  5663 I jxcore-log: 2016-10-06 14:46:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-06 10:46:47.457  5617  5663 I jxcore-log: 
,10-06 10:46:47.619  5617  5663 I jxcore-log: 2016-10-06 14:46:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-06 10:46:47.619  5617  5663 I jxcore-log: 
,10-06 10:46:47.623  5617  5663 I jxcore-log: 2016-10-06 14:46:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-06 10:46:47.623  5617  5663 I jxcore-log: 
,10-06 10:46:47.628  5617  5663 I jxcore-log: 2016-10-06 14:46:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-06 10:46:47.628  5617  5663 I jxcore-log: 
,10-06 10:46:48.168  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-06 10:46:48.168  5617  5663 I jxcore-log: 
,10-06 10:46:48.220  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-06 10:46:48.220  5617  5663 I jxcore-log: 
,10-06 10:46:48.233  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-06 10:46:48.233  5617  5663 I jxcore-log: 
,10-06 10:46:48.238  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-06 10:46:48.238  5617  5663 I jxcore-log: 
,10-06 10:46:48.519  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-06 10:46:48.519  5617  5663 I jxcore-log: 
,10-06 10:46:48.645  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-06 10:46:48.645  5617  5663 I jxcore-log: 
,10-06 10:46:48.878  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-06 10:46:48.878  5617  5663 I jxcore-log: 
,10-06 10:46:48.889  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-06 10:46:48.889  5617  5663 I jxcore-log: 
,10-06 10:46:48.893  5617  5663 I jxcore-log: 2016-10-06 14:46:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-06 10:46:48.893  5617  5663 I jxcore-log: 
,10-06 10:46:49.039  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-06 10:46:49.039  5617  5663 I jxcore-log: 
,10-06 10:46:49.047  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-06 10:46:49.047  5617  5663 I jxcore-log: 
,10-06 10:46:49.073  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-06 10:46:49.073  5617  5663 I jxcore-log: 
,10-06 10:46:49.109  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-06 10:46:49.109  5617  5663 I jxcore-log: 
,10-06 10:46:49.116  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-06 10:46:49.116  5617  5663 I jxcore-log: 
,10-06 10:46:49.122  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-06 10:46:49.122  5617  5663 I jxcore-log: 
,10-06 10:46:49.138  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-06 10:46:49.138  5617  5663 I jxcore-log: 
,10-06 10:46:49.143  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-06 10:46:49.143  5617  5663 I jxcore-log: 
,10-06 10:46:49.149  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-06 10:46:49.149  5617  5663 I jxcore-log: 
,10-06 10:46:49.154  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-06 10:46:49.154  5617  5663 I jxcore-log: 
,10-06 10:46:49.167  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-06 10:46:49.167  5617  5663 I jxcore-log: 
,10-06 10:46:49.188  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-06 10:46:49.188  5617  5663 I jxcore-log: 
,10-06 10:46:49.198  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-06 10:46:49.198  5617  5663 I jxcore-log: 
,10-06 10:46:49.209  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-06 10:46:49.209  5617  5663 I jxcore-log: 
,10-06 10:46:49.218  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-06 10:46:49.218  5617  5663 I jxcore-log: 
,10-06 10:46:49.230  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-06 10:46:49.230  5617  5663 I jxcore-log: 
,10-06 10:46:49.240  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-06 10:46:49.240  5617  5663 I jxcore-log: 
,10-06 10:46:49.245  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-06 10:46:49.245  5617  5663 I jxcore-log: 
,10-06 10:46:49.265  5617  5663 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-06 10:46:49.267  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - INFO testUtils: 'BLE multiple advertisement supported'
10-06 10:46:49.267  5617  5663 I jxcore-log: 
,10-06 10:46:49.418  5617  5663 I jxcore-log: 2016-10-06 14:46:49 - DEBUG CoordinatedClient: 'connected to the test server'
10-06 10:46:49.418  5617  5663 I jxcore-log: 
,10-06 10:46:49.935  5617  5663 I jxcore-log: TAP version 13
10-06 10:46:49.935  5617  5663 I jxcore-log: 
,10-06 10:46:49.976  5617  5663 I jxcore-log: # setup
10-06 10:46:49.976  5617  5663 I jxcore-log: 
,10-06 10:46:50.775  5617  5663 I jxcore-log: # calling createNativeListener directly rejects
10-06 10:46:50.775  5617  5663 I jxcore-log: 
,10-06 10:46:50.787   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-06 10:46:50.787   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-06 10:46:50.925  5617  5663 I jxcore-log: 2016-10-06 14:46:50 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:50.925  5617  5663 I jxcore-log: 
,10-06 10:46:50.931  5617  5663 I jxcore-log: 2016-10-06 14:46:50 - DEBUG createNativeListener: 'listening 37561'
10-06 10:46:50.931  5617  5663 I jxcore-log: 
,10-06 10:46:50.939  5617  5663 I jxcore-log: ok 1 Should throw
10-06 10:46:50.939  5617  5663 I jxcore-log: 
,10-06 10:46:50.951  5617  5663 I jxcore-log: # teardown
10-06 10:46:50.951  5617  5663 I jxcore-log: 
,10-06 10:46:51.103  5617  5663 I jxcore-log: # setup
10-06 10:46:51.103  5617  5663 I jxcore-log: 
,10-06 10:46:51.259  5617  5663 I jxcore-log: # emits incomingConnectionState
10-06 10:46:51.259  5617  5663 I jxcore-log: 
,10-06 10:46:51.429  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:51.429  5617  5663 I jxcore-log: 
,10-06 10:46:51.434  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'listening 41169'
10-06 10:46:51.434  5617  5663 I jxcore-log: 
,10-06 10:46:51.445  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:51.445  5617  5663 I jxcore-log: 
,10-06 10:46:51.449  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:51.449  5617  5663 I jxcore-log: 
,10-06 10:46:51.459  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'new mux'
10-06 10:46:51.459  5617  5663 I jxcore-log: 
,10-06 10:46:51.466  5617  5663 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-06 10:46:51.466  5617  5663 I jxcore-log: 
,10-06 10:46:51.483  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:51.483  5617  5663 I jxcore-log: 
,10-06 10:46:51.484  5617  5663 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-06 10:46:51.484  5617  5663 I jxcore-log: 
,10-06 10:46:51.492  5617  5663 I jxcore-log: # teardown
10-06 10:46:51.492  5617  5663 I jxcore-log: 
,10-06 10:46:51.566  5617  5663 I jxcore-log: # setup
10-06 10:46:51.566  5617  5663 I jxcore-log: 
,10-06 10:46:51.717  5617  5663 I jxcore-log: # emits routerPortConnectionFailed
10-06 10:46:51.717  5617  5663 I jxcore-log: 
,10-06 10:46:51.893  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:51.893  5617  5663 I jxcore-log: 
,10-06 10:46:51.895  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'listening 37041'
10-06 10:46:51.895  5617  5663 I jxcore-log: 
,10-06 10:46:51.902  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:51.902  5617  5663 I jxcore-log: 
,10-06 10:46:51.903  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:51.903  5617  5663 I jxcore-log: 
10-06 10:46:51.905  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'new mux'
10-06 10:46:51.905  5617  5663 I jxcore-log: 
,10-06 10:46:51.933  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:51.933  5617  5663 I jxcore-log: 
,10-06 10:46:51.935  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:51.935  5617  5663 I jxcore-log: 
,10-06 10:46:51.939  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: ' $c@net.js:837:7
10-06 10:46:51.939  5617  5663 I jxcore-log: $09@net.js:829:13
10-06 10:46:51.939  5617  5663 I jxcore-log: '
10-06 10:46:51.939  5617  5663 I jxcore-log: 
,10-06 10:46:51.940  5617  5663 I jxcore-log: ok 4 tried to connect to right port
10-06 10:46:51.940  5617  5663 I jxcore-log: 
10-06 10:46:51.941  5617  5663 I jxcore-log: ok 5 failed due to refused connection
10-06 10:46:51.941  5617  5663 I jxcore-log: 
10-06 10:46:51.941  5617  5663 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-06 10:46:51.941  5617  5663 I jxcore-log: 
10-06 10:46:51.945  5617  5663 I jxcore-log: # teardown
10-06 10:46:51.945  5617  5663 I jxcore-log: 
,10-06 10:46:51.947  5617  5663 I jxcore-log: 2016-10-06 14:46:51 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:51.947  5617  5663 I jxcore-log: 
,10-06 10:46:52.043  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'mux close'
10-06 10:46:52.043  5617  5663 I jxcore-log: 
10-06 10:46:52.048  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:52.048  5617  5663 I jxcore-log: 
,10-06 10:46:52.059  5617  5663 I jxcore-log: # setup
10-06 10:46:52.059  5617  5663 I jxcore-log: 
,10-06 10:46:52.200  5617  5663 I jxcore-log: # native server connections all up
10-06 10:46:52.200  5617  5663 I jxcore-log: 
,10-06 10:46:52.229  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:52.229  5617  5663 I jxcore-log: 
,10-06 10:46:52.232  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'listening 37183'
10-06 10:46:52.232  5617  5663 I jxcore-log: 
,10-06 10:46:52.239  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:52.239  5617  5663 I jxcore-log: 
,10-06 10:46:52.240  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:52.240  5617  5663 I jxcore-log: 
10-06 10:46:52.241  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new mux'
10-06 10:46:52.241  5617  5663 I jxcore-log: 
,10-06 10:46:52.269  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:52.269  5617  5663 I jxcore-log: 
,10-06 10:46:52.273  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:52.273  5617  5663 I jxcore-log: 
,10-06 10:46:52.276  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:52.276  5617  5663 I jxcore-log: 
,10-06 10:46:52.279  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:52.279  5617  5663 I jxcore-log: 
,10-06 10:46:52.304  5617  5663 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-06 10:46:52.304  5617  5663 I jxcore-log: 
,10-06 10:46:52.304  5617  5663 I jxcore-log: ok 8 Send/recvd #1 should be same
10-06 10:46:52.304  5617  5663 I jxcore-log: 
10-06 10:46:52.307  5617  5663 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-06 10:46:52.307  5617  5663 I jxcore-log: 
10-06 10:46:52.307  5617  5663 I jxcore-log: ok 10 Send/recvd #2 should be same
10-06 10:46:52.307  5617  5663 I jxcore-log: 
,10-06 10:46:52.311  5617  5663 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-06 10:46:52.311  5617  5663 I jxcore-log: 
,10-06 10:46:52.323  5617  5663 I jxcore-log: # teardown
10-06 10:46:52.323  5617  5663 I jxcore-log: 
,10-06 10:46:52.371  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:52.371  5617  5663 I jxcore-log: 
,10-06 10:46:52.373  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:52.373  5617  5663 I jxcore-log: 
,10-06 10:46:52.376  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'mux close'
10-06 10:46:52.376  5617  5663 I jxcore-log: 
,10-06 10:46:52.380  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:52.380  5617  5663 I jxcore-log: 
,10-06 10:46:52.391  5617  5663 I jxcore-log: # setup
10-06 10:46:52.391  5617  5663 I jxcore-log: 
,10-06 10:46:52.459  5617  5663 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-06 10:46:52.459  5617  5663 I jxcore-log: 
,10-06 10:46:52.495  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:52.495  5617  5663 I jxcore-log: 
,10-06 10:46:52.498  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'listening 46532'
10-06 10:46:52.498  5617  5663 I jxcore-log: 
,10-06 10:46:52.503  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:52.503  5617  5663 I jxcore-log: 
,10-06 10:46:52.504  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:52.504  5617  5663 I jxcore-log: 
,10-06 10:46:52.507  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new mux'
10-06 10:46:52.507  5617  5663 I jxcore-log: 
,10-06 10:46:52.518  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:52.518  5617  5663 I jxcore-log: 
,10-06 10:46:52.521  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:52.521  5617  5663 I jxcore-log: 
,10-06 10:46:52.534  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:52.534  5617  5663 I jxcore-log: 
,10-06 10:46:52.547  5617  5663 I jxcore-log: ok 12 socket shouldn't close until after stream
10-06 10:46:52.547  5617  5663 I jxcore-log: 
10-06 10:46:52.547  5617  5663 I jxcore-log: ok 13 incoming remains open
10-06 10:46:52.547  5617  5663 I jxcore-log: 
,10-06 10:46:52.554  5617  5663 I jxcore-log: # teardown
10-06 10:46:52.554  5617  5663 I jxcore-log: 
,10-06 10:46:52.608  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'mux close'
10-06 10:46:52.608  5617  5663 I jxcore-log: 
,10-06 10:46:52.612  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:52.612  5617  5663 I jxcore-log: 
,10-06 10:46:52.620  5617  5663 I jxcore-log: # setup
10-06 10:46:52.620  5617  5663 I jxcore-log: 
,10-06 10:46:52.670  5617  5663 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-06 10:46:52.670  5617  5663 I jxcore-log: 
,10-06 10:46:52.721  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:52.721  5617  5663 I jxcore-log: 
,10-06 10:46:52.724  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'listening 42438'
10-06 10:46:52.724  5617  5663 I jxcore-log: 
,10-06 10:46:52.732  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:52.732  5617  5663 I jxcore-log: 
,10-06 10:46:52.734  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:52.734  5617  5663 I jxcore-log: 
,10-06 10:46:52.735  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new mux'
10-06 10:46:52.735  5617  5663 I jxcore-log: 
,10-06 10:46:52.747  5617  5663 I jxcore-log: ok 14 we should not have gotten an error
10-06 10:46:52.747  5617  5663 I jxcore-log: 
,10-06 10:46:52.751  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:52.751  5617  5663 I jxcore-log: 
,10-06 10:46:52.755  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:52.755  5617  5663 I jxcore-log: 
,10-06 10:46:52.764  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:52.764  5617  5663 I jxcore-log: 
,10-06 10:46:52.766  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:52.766  5617  5663 I jxcore-log: 
,10-06 10:46:52.773  5617  5663 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-06 10:46:52.773  5617  5663 I jxcore-log: 
,10-06 10:46:52.774  5617  5663 I jxcore-log: ok 16 incoming is cleaned up
10-06 10:46:52.774  5617  5663 I jxcore-log: 
,10-06 10:46:52.779  5617  5663 I jxcore-log: # teardown
10-06 10:46:52.779  5617  5663 I jxcore-log: 
,10-06 10:46:52.857  5617  5663 I jxcore-log: # setup
10-06 10:46:52.857  5617  5663 I jxcore-log: 
,10-06 10:46:52.937  5617  5663 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-06 10:46:52.937  5617  5663 I jxcore-log: 
,10-06 10:46:52.972  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:52.972  5617  5663 I jxcore-log: 
,10-06 10:46:52.977  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'listening 47298'
10-06 10:46:52.977  5617  5663 I jxcore-log: 
,10-06 10:46:52.986  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:52.986  5617  5663 I jxcore-log: 
,10-06 10:46:52.987  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:52.987  5617  5663 I jxcore-log: 
,10-06 10:46:52.991  5617  5663 I jxcore-log: 2016-10-06 14:46:52 - DEBUG createNativeListener: 'new mux'
10-06 10:46:52.991  5617  5663 I jxcore-log: 
,10-06 10:46:53.006  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.006  5617  5663 I jxcore-log: 
,10-06 10:46:53.009  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.009  5617  5663 I jxcore-log: 
,10-06 10:46:53.024  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.024  5617  5663 I jxcore-log: 
,10-06 10:46:53.035  5617  5663 I jxcore-log: ok 17 stream was closed
10-06 10:46:53.035  5617  5663 I jxcore-log: 
,10-06 10:46:53.035  5617  5663 I jxcore-log: ok 18 incoming should survive
10-06 10:46:53.035  5617  5663 I jxcore-log: 
10-06 10:46:53.036  5617  5663 I jxcore-log: ok 19 mux should have no streams
10-06 10:46:53.036  5617  5663 I jxcore-log: 
,10-06 10:46:53.042  5617  5663 I jxcore-log: # teardown
10-06 10:46:53.042  5617  5663 I jxcore-log: 
,10-06 10:46:53.075  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.075  5617  5663 I jxcore-log: 
,10-06 10:46:53.088  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.088  5617  5663 I jxcore-log: 
,10-06 10:46:53.098  5617  5663 I jxcore-log: # setup
10-06 10:46:53.098  5617  5663 I jxcore-log: 
,10-06 10:46:53.160  5617  5663 I jxcore-log: # native server - closing the whole server cleans everything up
10-06 10:46:53.160  5617  5663 I jxcore-log: 
,10-06 10:46:53.208  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:53.208  5617  5663 I jxcore-log: 
,10-06 10:46:53.212  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'listening 48397'
10-06 10:46:53.212  5617  5663 I jxcore-log: 
,10-06 10:46:53.218  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.218  5617  5663 I jxcore-log: 
,10-06 10:46:53.219  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.219  5617  5663 I jxcore-log: 
,10-06 10:46:53.223  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.223  5617  5663 I jxcore-log: 
,10-06 10:46:53.233  5617  5663 I jxcore-log: ok 20 we should not have gotten an error
10-06 10:46:53.233  5617  5663 I jxcore-log: 
,10-06 10:46:53.244  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.244  5617  5663 I jxcore-log: 
,10-06 10:46:53.250  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.250  5617  5663 I jxcore-log: 
,10-06 10:46:53.264  5617  5663 I jxcore-log: ok 21 Buffers are identical
10-06 10:46:53.264  5617  5663 I jxcore-log: 
,10-06 10:46:53.269  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.269  5617  5663 I jxcore-log: 
,10-06 10:46:53.273  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.273  5617  5663 I jxcore-log: 
,10-06 10:46:53.278  5617  5663 I jxcore-log: ok 22 native server is nulled out
10-06 10:46:53.278  5617  5663 I jxcore-log: 
,10-06 10:46:53.279  5617  5663 I jxcore-log: ok 23 native server should be closed
10-06 10:46:53.279  5617  5663 I jxcore-log: 
10-06 10:46:53.279  5617  5663 I jxcore-log: ok 24 incoming has been removed
10-06 10:46:53.279  5617  5663 I jxcore-log: 
10-06 10:46:53.280  5617  5663 I jxcore-log: ok 25 Incoming should be done
10-06 10:46:53.280  5617  5663 I jxcore-log: 
,10-06 10:46:53.280  5617  5663 I jxcore-log: ok 26 The mux object should be closed
10-06 10:46:53.280  5617  5663 I jxcore-log: 
10-06 10:46:53.281  5617  5663 I jxcore-log: ok 27 The mux stream should be closed
10-06 10:46:53.281  5617  5663 I jxcore-log: 
,10-06 10:46:53.283  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.283  5617  5663 I jxcore-log: 
,10-06 10:46:53.302  5617  5663 I jxcore-log: # teardown
10-06 10:46:53.302  5617  5663 I jxcore-log: 
,10-06 10:46:53.329  5617  5663 I jxcore-log: # setup
10-06 10:46:53.329  5617  5663 I jxcore-log: 
,10-06 10:46:53.386  5617  5663 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-06 10:46:53.386  5617  5663 I jxcore-log: 
,10-06 10:46:53.436  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:53.436  5617  5663 I jxcore-log: 
,10-06 10:46:53.440  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'listening 39935'
10-06 10:46:53.440  5617  5663 I jxcore-log: 
,10-06 10:46:53.469  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.469  5617  5663 I jxcore-log: 
,10-06 10:46:53.470  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.470  5617  5663 I jxcore-log: 
10-06 10:46:53.471  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.471  5617  5663 I jxcore-log: 
,10-06 10:46:53.475  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.475  5617  5663 I jxcore-log: 
,10-06 10:46:53.476  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.476  5617  5663 I jxcore-log: 
10-06 10:46:53.477  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.477  5617  5663 I jxcore-log: 
,10-06 10:46:53.480  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.480  5617  5663 I jxcore-log: 
,10-06 10:46:53.481  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.481  5617  5663 I jxcore-log: 
,10-06 10:46:53.483  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.483  5617  5663 I jxcore-log: 
,10-06 10:46:53.487  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.487  5617  5663 I jxcore-log: 
,10-06 10:46:53.488  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.488  5617  5663 I jxcore-log: 
,10-06 10:46:53.489  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.489  5617  5663 I jxcore-log: 
,10-06 10:46:53.493  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.493  5617  5663 I jxcore-log: 
,10-06 10:46:53.494  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.494  5617  5663 I jxcore-log: 
,10-06 10:46:53.497  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.497  5617  5663 I jxcore-log: 
,10-06 10:46:53.500  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.500  5617  5663 I jxcore-log: 
,10-06 10:46:53.500  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.500  5617  5663 I jxcore-log: 
,10-06 10:46:53.502  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.502  5617  5663 I jxcore-log: 
,10-06 10:46:53.504  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.504  5617  5663 I jxcore-log: 
,10-06 10:46:53.505  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.505  5617  5663 I jxcore-log: 
,10-06 10:46:53.506  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.506  5617  5663 I jxcore-log: 
,10-06 10:46:53.514  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.514  5617  5663 I jxcore-log: 
,10-06 10:46:53.514  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.514  5617  5663 I jxcore-log: 
,10-06 10:46:53.515  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.515  5617  5663 I jxcore-log: 
,10-06 10:46:53.516  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.516  5617  5663 I jxcore-log: 
,10-06 10:46:53.516  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.516  5617  5663 I jxcore-log: 
,10-06 10:46:53.517  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.517  5617  5663 I jxcore-log: 
,10-06 10:46:53.518  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:53.518  5617  5663 I jxcore-log: 
,10-06 10:46:53.518  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:53.518  5617  5663 I jxcore-log: 
,10-06 10:46:53.519  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new mux'
10-06 10:46:53.519  5617  5663 I jxcore-log: 
,10-06 10:46:53.574  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.574  5617  5663 I jxcore-log: 
,10-06 10:46:53.576  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.576  5617  5663 I jxcore-log: 
,10-06 10:46:53.578  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.578  5617  5663 I jxcore-log: 
,10-06 10:46:53.579  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.579  5617  5663 I jxcore-log: 
,10-06 10:46:53.580  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.580  5617  5663 I jxcore-log: 
,10-06 10:46:53.581  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.581  5617  5663 I jxcore-log: 
,10-06 10:46:53.582  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.582  5617  5663 I jxcore-log: 
,10-06 10:46:53.583  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.583  5617  5663 I jxcore-log: 
10-06 10:46:53.585  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.585  5617  5663 I jxcore-log: 
,10-06 10:46:53.586  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.586  5617  5663 I jxcore-log: 
,10-06 10:46:53.587  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.587  5617  5663 I jxcore-log: 
10-06 10:46:53.587  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.587  5617  5663 I jxcore-log: 
,10-06 10:46:53.588  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.588  5617  5663 I jxcore-log: 
,10-06 10:46:53.589  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.589  5617  5663 I jxcore-log: 
,10-06 10:46:53.590  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.590  5617  5663 I jxcore-log: 
10-06 10:46:53.591  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.591  5617  5663 I jxcore-log: 
,10-06 10:46:53.592  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.592  5617  5663 I jxcore-log: 
,10-06 10:46:53.593  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.593  5617  5663 I jxcore-log: 
,10-06 10:46:53.594  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.594  5617  5663 I jxcore-log: 
10-06 10:46:53.595  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.595  5617  5663 I jxcore-log: 
,10-06 10:46:53.595  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.595  5617  5663 I jxcore-log: 
10-06 10:46:53.596  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.596  5617  5663 I jxcore-log: 
,10-06 10:46:53.597  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.597  5617  5663 I jxcore-log: 
10-06 10:46:53.598  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.598  5617  5663 I jxcore-log: 
,10-06 10:46:53.599  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.599  5617  5663 I jxcore-log: 
,10-06 10:46:53.600  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.600  5617  5663 I jxcore-log: 
10-06 10:46:53.601  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.601  5617  5663 I jxcore-log: 
,10-06 10:46:53.602  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.602  5617  5663 I jxcore-log: 
,10-06 10:46:53.602  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.602  5617  5663 I jxcore-log: 
10-06 10:46:53.603  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.603  5617  5663 I jxcore-log: 
,10-06 10:46:53.603  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.603  5617  5663 I jxcore-log: 
10-06 10:46:53.604  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.604  5617  5663 I jxcore-log: 
,10-06 10:46:53.605  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.605  5617  5663 I jxcore-log: 
10-06 10:46:53.606  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.606  5617  5663 I jxcore-log: 
,10-06 10:46:53.607  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.607  5617  5663 I jxcore-log: 
10-06 10:46:53.608  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.608  5617  5663 I jxcore-log: 
,10-06 10:46:53.608  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.608  5617  5663 I jxcore-log: 
10-06 10:46:53.609  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.609  5617  5663 I jxcore-log: 
,10-06 10:46:53.610  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.610  5617  5663 I jxcore-log: 
10-06 10:46:53.611  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.611  5617  5663 I jxcore-log: 
,10-06 10:46:53.612  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.612  5617  5663 I jxcore-log: 
,10-06 10:46:53.613  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.613  5617  5663 I jxcore-log: 
10-06 10:46:53.613  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.613  5617  5663 I jxcore-log: 
,10-06 10:46:53.614  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.614  5617  5663 I jxcore-log: 
10-06 10:46:53.615  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.615  5617  5663 I jxcore-log: 
,10-06 10:46:53.616  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.616  5617  5663 I jxcore-log: 
10-06 10:46:53.616  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.616  5617  5663 I jxcore-log: 
,10-06 10:46:53.617  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.617  5617  5663 I jxcore-log: 
,10-06 10:46:53.624  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.624  5617  5663 I jxcore-log: 
,10-06 10:46:53.626  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.626  5617  5663 I jxcore-log: 
,10-06 10:46:53.626  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.626  5617  5663 I jxcore-log: 
,10-06 10:46:53.627  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.627  5617  5663 I jxcore-log: 
10-06 10:46:53.628  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.628  5617  5663 I jxcore-log: 
10-06 10:46:53.629  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.629  5617  5663 I jxcore-log: 
,10-06 10:46:53.629  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.629  5617  5663 I jxcore-log: 
10-06 10:46:53.630  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.630  5617  5663 I jxcore-log: 
,10-06 10:46:53.632  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.632  5617  5663 I jxcore-log: 
,10-06 10:46:53.633  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.633  5617  5663 I jxcore-log: 
10-06 10:46:53.633  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.633  5617  5663 I jxcore-log: 
10-06 10:46:53.634  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.634  5617  5663 I jxcore-log: 
,10-06 10:46:53.634  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.634  5617  5663 I jxcore-log: 
10-06 10:46:53.635  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.635  5617  5663 I jxcore-log: 
,10-06 10:46:53.636  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.636  5617  5663 I jxcore-log: 
10-06 10:46:53.636  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.636  5617  5663 I jxcore-log: 
,10-06 10:46:53.637  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.637  5617  5663 I jxcore-log: 
,10-06 10:46:53.638  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.638  5617  5663 I jxcore-log: 
10-06 10:46:53.639  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.639  5617  5663 I jxcore-log: 
,10-06 10:46:53.639  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.639  5617  5663 I jxcore-log: 
,10-06 10:46:53.640  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.640  5617  5663 I jxcore-log: 
10-06 10:46:53.641  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.641  5617  5663 I jxcore-log: 
,10-06 10:46:53.641  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.641  5617  5663 I jxcore-log: 
,10-06 10:46:53.642  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.642  5617  5663 I jxcore-log: 
,10-06 10:46:53.643  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.643  5617  5663 I jxcore-log: 
10-06 10:46:53.644  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.644  5617  5663 I jxcore-log: 
,10-06 10:46:53.644  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.644  5617  5663 I jxcore-log: 
,10-06 10:46:53.645  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.645  5617  5663 I jxcore-log: 
10-06 10:46:53.646  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.646  5617  5663 I jxcore-log: 
10-06 10:46:53.646  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.646  5617  5663 I jxcore-log: 
,10-06 10:46:53.647  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:53.647  5617  5663 I jxcore-log: 
10-06 10:46:53.647  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:53.647  5617  5663 I jxcore-log: 
,10-06 10:46:53.692  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.692  5617  5663 I jxcore-log: 
,10-06 10:46:53.693  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.693  5617  5663 I jxcore-log: 
,10-06 10:46:53.694  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.694  5617  5663 I jxcore-log: 
10-06 10:46:53.695  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.695  5617  5663 I jxcore-log: 
10-06 10:46:53.695  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.695  5617  5663 I jxcore-log: 
,10-06 10:46:53.696  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.696  5617  5663 I jxcore-log: 
10-06 10:46:53.697  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.697  5617  5663 I jxcore-log: 
10-06 10:46:53.697  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.697  5617  5663 I jxcore-log: 
10-06 10:46:53.697  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.697  5617  5663 I jxcore-log: 
,10-06 10:46:53.698  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.698  5617  5663 I jxcore-log: 
10-06 10:46:53.698  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.698  5617  5663 I jxcore-log: 
10-06 10:46:53.699  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.699  5617  5663 I jxcore-log: 
10-06 10:46:53.699  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.699  5617  5663 I jxcore-log: 
,10-06 10:46:53.700  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.700  5617  5663 I jxcore-log: 
10-06 10:46:53.700  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.700  5617  5663 I jxcore-log: 
,10-06 10:46:53.701  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.701  5617  5663 I jxcore-log: 
10-06 10:46:53.701  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.701  5617  5663 I jxcore-log: 
,10-06 10:46:53.702  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.702  5617  5663 I jxcore-log: 
10-06 10:46:53.702  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.702  5617  5663 I jxcore-log: 
,10-06 10:46:53.703  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.703  5617  5663 I jxcore-log: 
10-06 10:46:53.703  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.703  5617  5663 I jxcore-log: 
,10-06 10:46:53.704  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.704  5617  5663 I jxcore-log: 
,10-06 10:46:53.704  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.704  5617  5663 I jxcore-log: 
10-06 10:46:53.704  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.704  5617  5663 I jxcore-log: 
,10-06 10:46:53.705  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.705  5617  5663 I jxcore-log: 
10-06 10:46:53.706  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.706  5617  5663 I jxcore-log: 
10-06 10:46:53.706  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.706  5617  5663 I jxcore-log: 
,10-06 10:46:53.706  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.706  5617  5663 I jxcore-log: 
10-06 10:46:53.707  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.707  5617  5663 I jxcore-log: 
,10-06 10:46:53.707  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.707  5617  5663 I jxcore-log: 
10-06 10:46:53.708  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.708  5617  5663 I jxcore-log: 
,10-06 10:46:53.708  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.708  5617  5663 I jxcore-log: 
10-06 10:46:53.709  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.709  5617  5663 I jxcore-log: 
,10-06 10:46:53.709  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.709  5617  5663 I jxcore-log: 
10-06 10:46:53.710  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.710  5617  5663 I jxcore-log: 
10-06 10:46:53.710  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.710  5617  5663 I jxcore-log: 
10-06 10:46:53.711  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.711  5617  5663 I jxcore-log: 
,10-06 10:46:53.711  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.711  5617  5663 I jxcore-log: 
10-06 10:46:53.711  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.711  5617  5663 I jxcore-log: 
,10-06 10:46:53.712  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.712  5617  5663 I jxcore-log: 
10-06 10:46:53.712  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.712  5617  5663 I jxcore-log: 
10-06 10:46:53.713  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.713  5617  5663 I jxcore-log: 
,10-06 10:46:53.713  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.713  5617  5663 I jxcore-log: 
10-06 10:46:53.714  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.714  5617  5663 I jxcore-log: 
10-06 10:46:53.715  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.715  5617  5663 I jxcore-log: 
10-06 10:46:53.716  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.716  5617  5663 I jxcore-log: 
10-06 10:46:53.716  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.716  5617  5663 I jxcore-log: 
,10-06 10:46:53.717  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.717  5617  5663 I jxcore-log: 
10-06 10:46:53.717  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:53.717  5617  5663 I jxcore-log: 
,10-06 10:46:53.719  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'mux close'
10-06 10:46:53.719  5617  5663 I jxcore-log: 
,10-06 10:46:53.721  5617  5663 I jxcore-log: ok 28 native server is nulled out
10-06 10:46:53.721  5617  5663 I jxcore-log: 
,10-06 10:46:53.722  5617  5663 I jxcore-log: ok 29 native server should be closed
10-06 10:46:53.722  5617  5663 I jxcore-log: 
10-06 10:46:53.722  5617  5663 I jxcore-log: ok 30 incoming has been removed
10-06 10:46:53.722  5617  5663 I jxcore-log: 
,10-06 10:46:53.723  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.723  5617  5663 I jxcore-log: 
,10-06 10:46:53.724  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.724  5617  5663 I jxcore-log: 
,10-06 10:46:53.725  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.725  5617  5663 I jxcore-log: 
10-06 10:46:53.725  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.725  5617  5663 I jxcore-log: 
10-06 10:46:53.726  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.726  5617  5663 I jxcore-log: 
10-06 10:46:53.726  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.726  5617  5663 I jxcore-log: 
,10-06 10:46:53.726  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.726  5617  5663 I jxcore-log: 
10-06 10:46:53.726  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.726  5617  5663 I jxcore-log: 
10-06 10:46:53.726  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.726  5617  5663 I jxcore-log: 
10-06 10:46:53.727  5617  5663 I jxcore-log: 2016-10-06 14:46:53 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:53.727  5617  5663 I jxcore-log: 
,10-06 10:46:53.799  5617  5663 I jxcore-log: # teardown
10-06 10:46:53.799  5617  5663 I jxcore-log: 
,10-06 10:46:53.855  5617  5663 I jxcore-log: # setup
10-06 10:46:53.855  5617  5663 I jxcore-log: 
,10-06 10:46:55.568  5617  5663 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-06 10:46:55.568  5617  5663 I jxcore-log: 
,10-06 10:46:55.604  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:55.604  5617  5663 I jxcore-log: 
,10-06 10:46:55.610  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'listening 40136'
10-06 10:46:55.610  5617  5663 I jxcore-log: 
,10-06 10:46:55.618  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:55.618  5617  5663 I jxcore-log: 
,10-06 10:46:55.620  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:55.620  5617  5663 I jxcore-log: 
,10-06 10:46:55.622  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'new mux'
10-06 10:46:55.622  5617  5663 I jxcore-log: 
,10-06 10:46:55.631  5617  5663 I jxcore-log: ok 31 we should not have gotten an error
10-06 10:46:55.631  5617  5663 I jxcore-log: 
,10-06 10:46:55.634  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:55.634  5617  5663 I jxcore-log: 
,10-06 10:46:55.637  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:55.637  5617  5663 I jxcore-log: 
,10-06 10:46:55.644  5617  5663 I jxcore-log: ok 32 Buffers are identical
10-06 10:46:55.644  5617  5663 I jxcore-log: 
,10-06 10:46:55.645  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:55.645  5617  5663 I jxcore-log: 
,10-06 10:46:55.647  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'mux close'
10-06 10:46:55.647  5617  5663 I jxcore-log: 
,10-06 10:46:55.657  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:55.657  5617  5663 I jxcore-log: 
,10-06 10:46:55.658  5617  5663 I jxcore-log: ok 33 server should be fine
10-06 10:46:55.658  5617  5663 I jxcore-log: 
10-06 10:46:55.658  5617  5663 I jxcore-log: ok 34 server should be open
10-06 10:46:55.658  5617  5663 I jxcore-log: 
10-06 10:46:55.658  5617  5663 I jxcore-log: ok 35 incoming has been removed
10-06 10:46:55.658  5617  5663 I jxcore-log: 
10-06 10:46:55.659  5617  5663 I jxcore-log: ok 36 The mux object should be closed
10-06 10:46:55.659  5617  5663 I jxcore-log: 
10-06 10:46:55.659  5617  5663 I jxcore-log: ok 37 The mux stream should be closed
10-06 10:46:55.659  5617  5663 I jxcore-log: 
,10-06 10:46:55.664  5617  5663 I jxcore-log: # teardown
10-06 10:46:55.664  5617  5663 I jxcore-log: 
,10-06 10:46:55.715  5617  5663 I jxcore-log: # setup
10-06 10:46:55.715  5617  5663 I jxcore-log: 
,10-06 10:46:55.752  5617  5663 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-06 10:46:55.752  5617  5663 I jxcore-log: 
,10-06 10:46:55.786  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'creating native server'
10-06 10:46:55.786  5617  5663 I jxcore-log: 
,10-06 10:46:55.791  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'listening 43840'
10-06 10:46:55.791  5617  5663 I jxcore-log: 
,10-06 10:46:55.797  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'new incoming socket'
10-06 10:46:55.797  5617  5663 I jxcore-log: 
,10-06 10:46:55.799  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'creating incoming mux'
10-06 10:46:55.799  5617  5663 I jxcore-log: 
10-06 10:46:55.801  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'new mux'
10-06 10:46:55.801  5617  5663 I jxcore-log: 
,10-06 10:46:55.809  5617  5663 I jxcore-log: ok 38 we should not have gotten an error
10-06 10:46:55.809  5617  5663 I jxcore-log: 
,10-06 10:46:55.813  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'new stream: '
10-06 10:46:55.813  5617  5663 I jxcore-log: 
,10-06 10:46:55.816  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'new outgoing socket'
10-06 10:46:55.816  5617  5663 I jxcore-log: 
,10-06 10:46:55.825  5617  5663 I jxcore-log: ok 39 Buffers are identical
10-06 10:46:55.825  5617  5663 I jxcore-log: 
,10-06 10:46:55.830  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'incoming socket timeout'
10-06 10:46:55.830  5617  5663 I jxcore-log: 
,10-06 10:46:55.832  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'stream close:'
10-06 10:46:55.832  5617  5663 I jxcore-log: 
,10-06 10:46:55.834  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'mux close'
10-06 10:46:55.834  5617  5663 I jxcore-log: 
,10-06 10:46:55.840  5617  5663 I jxcore-log: 2016-10-06 14:46:55 - DEBUG createNativeListener: 'incoming socket close'
10-06 10:46:55.840  5617  5663 I jxcore-log: 
,10-06 10:46:55.841  5617  5663 I jxcore-log: ok 40 server should be fine
10-06 10:46:55.841  5617  5663 I jxcore-log: 
,10-06 10:46:55.841  5617  5663 I jxcore-log: ok 41 server should be open
10-06 10:46:55.841  5617  5663 I jxcore-log: 
10-06 10:46:55.842  5617  5663 I jxcore-log: ok 42 incoming has been removed
10-06 10:46:55.842  5617  5663 I jxcore-log: 
,10-06 10:46:55.842  5617  5663 I jxcore-log: ok 43 The mux object should be closed
10-06 10:46:55.842  5617  5663 I jxcore-log: 
10-06 10:46:55.843  5617  5663 I jxcore-log: ok 44 The mux stream should be closed
10-06 10:46:55.843  5617  5663 I jxcore-log: 
,10-06 10:46:55.849  5617  5663 I jxcore-log: # teardown
10-06 10:46:55.849  5617  5663 I jxcore-log: 
,10-06 10:46:55.887  5617  5663 I jxcore-log: # setup
10-06 10:46:55.887  5617  5663 I jxcore-log: 
,10-06 10:46:55.917  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-06 10:46:55.917  5617  5663 I jxcore-log: 
,10-06 10:46:56.084  5617  5663 I jxcore-log: 2016-10-06 14:46:56 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-06 10:46:56.084  5617  5663 I jxcore-log: 
,10-06 10:46:56.084  5617  5663 I jxcore-log: ok 45 Got right error
10-06 10:46:56.084  5617  5663 I jxcore-log: 
,10-06 10:46:56.089  5617  5663 I jxcore-log: # teardown
10-06 10:46:56.089  5617  5663 I jxcore-log: 
,10-06 10:46:56.148  5617  5663 I jxcore-log: # setup
10-06 10:46:56.148  5617  5663 I jxcore-log: 
,10-06 10:46:56.176  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-06 10:46:56.176  5617  5663 I jxcore-log: 
,10-06 10:46:56.273  5617  5663 I jxcore-log: 2016-10-06 14:46:56 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-06 10:46:56.273  5617  5663 I jxcore-log: 
,10-06 10:46:56.274  5617  5663 I jxcore-log: ok 46 Got socket hang up
10-06 10:46:56.274  5617  5663 I jxcore-log: 
,10-06 10:46:56.279  5617  5663 I jxcore-log: # teardown
10-06 10:46:56.279  5617  5663 I jxcore-log: 
,10-06 10:46:56.313  5617  5663 I jxcore-log: # setup
10-06 10:46:56.313  5617  5663 I jxcore-log: 
,10-06 10:46:56.368  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-06 10:46:56.368  5617  5663 I jxcore-log: 
,10-06 10:46:56.534  5617  5663 I jxcore-log: 2016-10-06 14:46:56 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-06 10:46:56.534  5617  5663 I jxcore-log: 
,10-06 10:46:56.535  5617  5663 I jxcore-log: ok 47 Got 500 as expected
10-06 10:46:56.535  5617  5663 I jxcore-log: 
,10-06 10:46:56.540  5617  5663 I jxcore-log: # teardown
10-06 10:46:56.540  5617  5663 I jxcore-log: 
,10-06 10:46:56.572  5617  5663 I jxcore-log: # setup
10-06 10:46:56.572  5617  5663 I jxcore-log: 
,10-06 10:46:56.612  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-06 10:46:56.612  5617  5663 I jxcore-log: 
,10-06 10:46:58.013  5617  5663 I jxcore-log: ok 48 should be equal
10-06 10:46:58.013  5617  5663 I jxcore-log: 
,10-06 10:46:58.013  5617  5663 I jxcore-log: ok 49 revs are equal
10-06 10:46:58.013  5617  5663 I jxcore-log: 
,10-06 10:46:58.018  5617  5663 I jxcore-log: # teardown
10-06 10:46:58.018  5617  5663 I jxcore-log: 
,10-06 10:46:58.055  5617  5663 I jxcore-log: # setup
10-06 10:46:58.055  5617  5663 I jxcore-log: 
,10-06 10:46:58.951  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-06 10:46:58.951  5617  5663 I jxcore-log: 
,10-06 10:46:59.667  5617  5663 I jxcore-log: ok 50 should be equal
10-06 10:46:59.667  5617  5663 I jxcore-log: 
,10-06 10:46:59.667  5617  5663 I jxcore-log: ok 51 revs are equal
10-06 10:46:59.667  5617  5663 I jxcore-log: 
,10-06 10:46:59.673  5617  5663 I jxcore-log: # teardown
10-06 10:46:59.673  5617  5663 I jxcore-log: 
,10-06 10:46:59.718  5617  5663 I jxcore-log: # setup
10-06 10:46:59.718  5617  5663 I jxcore-log: 
,10-06 10:46:59.795  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-06 10:46:59.795  5617  5663 I jxcore-log: 
,10-06 10:47:00.309  5617  5663 I jxcore-log: ok 52 should be equal
10-06 10:47:00.309  5617  5663 I jxcore-log: 
,10-06 10:47:00.309  5617  5663 I jxcore-log: ok 53 revs are equal
10-06 10:47:00.309  5617  5663 I jxcore-log: 
,10-06 10:47:00.493  5617  5663 I jxcore-log: ok 54 should be equal
10-06 10:47:00.493  5617  5663 I jxcore-log: 
,10-06 10:47:00.495  5617  5663 I jxcore-log: ok 55 revs are equal
10-06 10:47:00.495  5617  5663 I jxcore-log: 
,10-06 10:47:00.698  5617  5663 I jxcore-log: ok 56 should be equal
10-06 10:47:00.698  5617  5663 I jxcore-log: 
,10-06 10:47:00.699  5617  5663 I jxcore-log: ok 57 revs are equal
10-06 10:47:00.699  5617  5663 I jxcore-log: 
,10-06 10:47:00.708  5617  5663 I jxcore-log: # teardown
10-06 10:47:00.708  5617  5663 I jxcore-log: 
,10-06 10:47:00.760  5617  5663 I jxcore-log: # setup
10-06 10:47:00.760  5617  5663 I jxcore-log: 
,10-06 10:47:01.196  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-06 10:47:01.196  5617  5663 I jxcore-log: 
,10-06 10:47:02.644  5617  5663 I jxcore-log: 2016-10-06 14:47:02 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-06 10:47:02.644  5617  5663 I jxcore-log: 
,10-06 10:47:02.645  5617  5663 I jxcore-log: ok 58 Our rev is old so we should fail
10-06 10:47:02.645  5617  5663 I jxcore-log: 
,10-06 10:47:02.649  5617  5663 I jxcore-log: # teardown
10-06 10:47:02.649  5617  5663 I jxcore-log: 
,10-06 10:47:03.680  5617  5663 I jxcore-log: # setup
10-06 10:47:03.680  5617  5663 I jxcore-log: 
,10-06 10:47:03.959  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-06 10:47:03.959  5617  5663 I jxcore-log: 
,10-06 10:47:04.172  5617  5663 I jxcore-log: ok 59 confirm stop caused failure
10-06 10:47:04.172  5617  5663 I jxcore-log: 
,10-06 10:47:04.184  5617  5663 I jxcore-log: # teardown
10-06 10:47:04.184  5617  5663 I jxcore-log: 
,10-06 10:47:04.216  5617  5663 I jxcore-log: # setup
10-06 10:47:04.216  5617  5663 I jxcore-log: 
,10-06 10:47:04.264  5617  5663 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-06 10:47:04.264  5617  5663 I jxcore-log: 
,10-06 10:47:04.561  5617  5663 I jxcore-log: 2016-10-06 14:47:04 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-06 10:47:04.561  5617  5663 I jxcore-log: 
,10-06 10:47:04.562  5617  5663 I jxcore-log: ok 60 stop caused us to fail
10-06 10:47:04.562  5617  5663 I jxcore-log: 
,10-06 10:47:04.563  5617  5663 I jxcore-log: ok 61 We specifically failed on a stop before put
10-06 10:47:04.563  5617  5663 I jxcore-log: 
,10-06 10:47:04.568  5617  5663 I jxcore-log: # teardown
10-06 10:47:04.568  5617  5663 I jxcore-log: 
,10-06 10:47:04.643  5617  5663 I jxcore-log: # setup
10-06 10:47:04.643  5617  5663 I jxcore-log: 
,10-06 10:47:04.698  5617  5663 I jxcore-log: # #update - fail if stop is called
10-06 10:47:04.698  5617  5663 I jxcore-log: 
,10-06 10:47:04.811  5617  5663 I jxcore-log: ok 62 failed due to stop
10-06 10:47:04.811  5617  5663 I jxcore-log: 
,10-06 10:47:04.812  5617  5663 I jxcore-log: ok 63 failed due to stop
10-06 10:47:04.812  5617  5663 I jxcore-log: 
,10-06 10:47:04.820  5617  5663 I jxcore-log: # teardown
10-06 10:47:04.820  5617  5663 I jxcore-log: 
,10-06 10:47:04.903  5617  5663 I jxcore-log: # setup
10-06 10:47:04.903  5617  5663 I jxcore-log: 
,10-06 10:47:04.941  5617  5663 I jxcore-log: # #update - set seq for first time
10-06 10:47:04.941  5617  5663 I jxcore-log: 
,10-06 10:47:05.395  5617  5663 I jxcore-log: ok 64 should be equal
10-06 10:47:05.395  5617  5663 I jxcore-log: 
,10-06 10:47:05.403  5617  5663 I jxcore-log: # teardown
10-06 10:47:05.403  5617  5663 I jxcore-log: 
,10-06 10:47:05.447  5617  5663 I jxcore-log: # setup
10-06 10:47:05.447  5617  5663 I jxcore-log: 
,10-06 10:47:05.491  5617  5663 I jxcore-log: # #update - Fail on bad seq value
10-06 10:47:05.491  5617  5663 I jxcore-log: 
,10-06 10:47:05.788   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:05.892  5617  5663 I jxcore-log: 2016-10-06 14:47:05 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-06 10:47:05.892  5617  5663 I jxcore-log: 
,10-06 10:47:05.894  5617  5663 I jxcore-log: ok 65 Expected bad seq error
10-06 10:47:05.894  5617  5663 I jxcore-log: 
,10-06 10:47:05.898  5617  5663 I jxcore-log: # teardown
10-06 10:47:05.898  5617  5663 I jxcore-log: 
,10-06 10:47:05.970  5617  5663 I jxcore-log: # setup
10-06 10:47:05.970  5617  5663 I jxcore-log: 
,10-06 10:47:06.005  5617  5663 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-06 10:47:06.005  5617  5663 I jxcore-log: 
,10-06 10:47:06.361  5617  5663 I jxcore-log: ok 66 Different promises
10-06 10:47:06.361  5617  5663 I jxcore-log: 
,10-06 10:47:06.364  5617  5663 I jxcore-log: ok 67 Timer was cancelled
10-06 10:47:06.364  5617  5663 I jxcore-log: 
,10-06 10:47:06.507  5617  5663 I jxcore-log: ok 68 should be equal
10-06 10:47:06.507  5617  5663 I jxcore-log: 
,10-06 10:47:06.514  5617  5663 I jxcore-log: # teardown
10-06 10:47:06.514  5617  5663 I jxcore-log: 
,10-06 10:47:06.789   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:07.790   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:08.184  5617  5663 I jxcore-log: # setup
10-06 10:47:08.184  5617  5663 I jxcore-log: 
,10-06 10:47:08.326  5617  5663 I jxcore-log: # #update - do we wait for blocked update
10-06 10:47:08.326  5617  5663 I jxcore-log: 
,10-06 10:47:08.782   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-06 10:47:08.791   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:08.825  5617  5663 I jxcore-log: ok 69 One go and one blocked
10-06 10:47:08.825  5617  5663 I jxcore-log: 
,10-06 10:47:08.826  5617  5663 I jxcore-log: ok 70 All blocked
10-06 10:47:08.826  5617  5663 I jxcore-log: 
10-06 10:47:08.827  5617  5663 I jxcore-log: ok 71 Still blocked
10-06 10:47:08.827  5617  5663 I jxcore-log: 
,10-06 10:47:09.208  5617  5663 I jxcore-log: ok 72 should be equal
10-06 10:47:09.208  5617  5663 I jxcore-log: 
,10-06 10:47:09.215  5617  5663 I jxcore-log: # teardown
10-06 10:47:09.215  5617  5663 I jxcore-log: 
,10-06 10:47:09.740  5617  5663 I jxcore-log: # setup
10-06 10:47:09.740  5617  5663 I jxcore-log: 
,10-06 10:47:09.792   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:10.406  5617  5663 I jxcore-log: # #update - test that we wait long enough
10-06 10:47:10.406  5617  5663 I jxcore-log: 
,10-06 10:47:10.792   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-06 10:47:12.498  5617  5663 I jxcore-log: ok 73 We waited long enough
10-06 10:47:12.498  5617  5663 I jxcore-log: 
,10-06 10:47:12.651  5617  5663 I jxcore-log: ok 74 should be equal
10-06 10:47:12.651  5617  5663 I jxcore-log: 
,10-06 10:47:12.659  5617  5663 I jxcore-log: # teardown
10-06 10:47:12.659  5617  5663 I jxcore-log: 
,10-06 10:47:13.205  5617  5663 I jxcore-log: # setup
10-06 10:47:13.205  5617  5663 I jxcore-log: 
,10-06 10:47:13.339  5617  5663 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-06 10:47:13.339  5617  5663 I jxcore-log: 
,10-06 10:47:13.906  5617  5663 I jxcore-log: ok 75 Should have gotten same timer promise
10-06 10:47:13.906  5617  5663 I jxcore-log: 
,10-06 10:47:13.907  5617  5663 I jxcore-log: ok 76 Still same timer promise
10-06 10:47:13.907  5617  5663 I jxcore-log: 
,10-06 10:47:14.682  5617  5663 I jxcore-log: ok 77 We waited long enough
10-06 10:47:14.682  5617  5663 I jxcore-log: 
,10-06 10:47:14.752  5617  5663 I jxcore-log: ok 78 should be equal
10-06 10:47:14.752  5617  5663 I jxcore-log: 
,10-06 10:47:14.759  5617  5663 I jxcore-log: # teardown
10-06 10:47:14.759  5617  5663 I jxcore-log: 
,10-06 10:47:14.879  5617  5663 I jxcore-log: # setup
10-06 10:47:14.879  5617  5663 I jxcore-log: 
,10-06 10:47:14.933  5617  5663 I jxcore-log: # Coordinated seq test
10-06 10:47:14.933  5617  5663 I jxcore-log: 
,10-06 10:47:15.141  5617  5663 I jxcore-log: 2016-10-06 14:47:15 - DEBUG thaliWifiInfrastructure: 'listening 39207'
10-06 10:47:15.141  5617  5663 I jxcore-log: 
,10-06 10:47:15.793   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:16.794   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:17.111  5617  5663 I jxcore-log: ok 79 should be equal
10-06 10:47:17.111  5617  5663 I jxcore-log: 
,10-06 10:47:17.795   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:18.262  5617  5663 I jxcore-log: 2016-10-06 14:47:18 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
10-06 10:47:18.262  5617  5663 I jxcore-log: 
,10-06 10:47:18.796   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:19.797   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:20.027  5617  5663 I jxcore-log: ok 80 should be equal
10-06 10:47:20.027  5617  5663 I jxcore-log: 
,10-06 10:47:20.043  5617  5663 I jxcore-log: # teardown
10-06 10:47:20.043  5617  5663 I jxcore-log: 
,10-06 10:47:20.798   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-06 10:47:28.784   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-06 10:47:30.800   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:31.801   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:32.803   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:33.804   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:34.805   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:35.806   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-06 10:47:49.865   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-06 10:47:50.808   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:51.809   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:52.811   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:52.892   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-06 10:47:53.812   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:54.814   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:47:55.814   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-06 10:48:08.788   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-06 10:48:11.059   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-06 10:48:14.085   928  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-06 10:48:15.815   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:48:16.817   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:48:17.818   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:48:18.820   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:48:19.821   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-06 10:48:20.060  5617  5663 I jxcore-log: 2016-10-06 14:48:20 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-06 10:48:20.060  5617  5663 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-06 10:48:20.060  5617  5663 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-06 10:48:20.060  5617  5663 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-06 10:48:20.060  5617  5663 I jxcore-log:     at $9@timers.js:120:1
10-06 10:48:20.060  5617  5663 I jxcore-log: ''
10-06 10:48:20.060  5617  5663 I jxcore-log: 
,10-06 10:48:20.063  5617  5663 I jxcore-log: 2016-10-06 14:48:20 - DEBUG CoordinatedClient: 'test client failed'
10-06 10:48:20.063  5617  5663 I jxcore-log: 
,10-06 10:48:20.074  5617  5663 I jxcore-log: 2016-10-06 14:48:20 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-06 10:48:20.074  5617  5663 I jxcore-log: 
,10-06 10:48:20.079  5617  5663 I jxcore-log: 2016-10-06 14:48:20 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-06 10:48:20.079  5617  5663 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-06 10:48:20.079  5617  5663 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-06 10:48:20.079  5617  5663 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-06 10:48:20.079  5617  5663 I jxcore-log:     at $9@timers.js:120:1
10-06 10:48:20.079  5617  5663 I jxcore-log: ''
10-06 10:48:20.079  5617  5663 I jxcore-log: 
,10-06 10:48:20.080  5617  5663 I jxcore-log: 2016-10-06 14:48:20 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-06 10:48:20.080  5617  5663 I jxcore-log: 
,10-06 10:48:20.152   928  2938 W InputDispatcher: channel '75064cc com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-06 10:48:20.153   928  2938 E InputDispatcher: channel '75064cc com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
10-06 10:48:20.166   928  2969 D WifiService: Client connection lost with reason: 4
10-06 10:48:20.166   928  3744 I WindowState: WIN DEATH: Window{75064cc u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-06 10:48:20.166   928  3762 D GraphicsStats: Buffer count: 2
10-06 10:48:20.166   928  3744 W InputDispatcher: Attempted to unregister already unregistered input channel '75064cc com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-06 10:48:20.167   928  3769 I ActivityManager: Process com.test.thalitest (pid 5617) has died
10-06 10:48:20.167   529   529 I Zygote  : Process 5617 exited cleanly (139)
,10-06 10:48:20.194   928  3769 I ActivityManager: Start proc 5993:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-06 10:48:20.515   928  3762 I WindowManager: Screenshot max retries 4 of Token{ceb10be ActivityRecord{ae1ab79 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{7e08e33 u0 Starting com.test.thalitest} drawState=4
,10-06 10:48:20.559  5991  5991 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-06 10:48:20.574  5991  5991 D AndroidRuntime: CheckJNI is OFF
,10-06 10:48:20.596  5993  5993 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-06 10:48:20.597  5991  5991 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-06 10:48:20.620  5993  5993 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-06 10:48:20.624  5991  5991 I Radio-JNI: register_android_hardware_Radio DONE
,10-06 10:48:20.626  5993  5993 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8922-8924)
,10-06 10:48:20.626  5993  5993 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-06 10:48:20.634  5993  5993 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fb5b4a}
,10-06 10:48:20.635  5993  5993 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-06 10:48:20.635  5993  5993 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-06 10:48:20.638  5993  5993 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-06 10:48:20.639  5993  5993 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-06 10:48:20.641  5991  5991 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-06 10:48:20.647   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-06 10:48:20.647   928   941 I ActivityManager: Killing 5993:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-06 10:48:20.772   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-06 10:48:20.772   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-06 10:48:20.776   928   941 E ActivityManager: Failure starting process com.test.thalitest
10-06 10:48:20.776   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-06 10:48:20.776   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:48:20.776   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:48:20.776   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-06 10:48:20.776   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-06 10:48:20.776   928   952 I art     : Starting a blocking GC Explicit
,10-06 10:48:20.781   928   941 I ActivityManager:   Force finishing activity ActivityRecord{ae1ab79 u0 com.test.thalitest/.MainActivity t2}
10-06 10:48:20.798   928   946 W WindowManager: Failed looking up window
10-06 10:48:20.798   928   946 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@77391a2 does not exist
10-06 10:48:20.798   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-06 10:48:20.798   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-06 10:48:20.798   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-06 10:48:20.798   928   946 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-06 10:48:20.798   928   946 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-06 10:48:20.798   928   946 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-06 10:48:20.798   928   946 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-06 10:48:20.798   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:48:20.798   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:48:20.798   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-06 10:48:20.798   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-06 10:48:20.799   928  3155 W ActivityManager: Spurious death for ProcessRecord{1d25ee 0:com.test.thalitest/u0a77}, curProc for 5993: null
,10-06 10:48:20.822   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-06 10:48:20.873   928   952 I art     : Explicit concurrent mark sweep GC freed 81365(5MB) AllocSpace objects, 40(1400KB) LOS objects, 33% free, 29MB/43MB, paused 1.382ms total 96.685ms
,10-06 10:48:20.895   928   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-06 10:48:20.899  5991  5991 I art     : System.exit called, status: 0
,10-06 10:48:20.899  5991  5991 I AndroidRuntime: VM exiting with result code 0.
,10-06 10:48:20.915   928   952 I ActivityManager: Start proc 6019:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-06 10:48:20.915   928   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-06 10:48:20.924   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-06 10:48:20.926  3658  3658 I Keyboard.Facilitator: resetDictionaries() : en_US
10-06 10:48:20.927  5895  5895 D BluetoothMapAppObserver: onReceive
10-06 10:48:20.927  5895  5895 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-06 10:48:20.939  3707  4076 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-06 10:48:20.942   928  2939 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-06 10:48:20.958  3658  6031 I Keyboard.Facilitator.DecoderInitializer: run()
,10-06 10:48:20.963  3401  6032 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-06 10:48:20.969  3776  3776 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-06 10:48:20.970  3658  6031 I Decoder : createOrResetDecoder
,10-06 10:48:20.994    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-06 10:48:20.998    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-06 10:48:21.008    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-06 10:48:21.018   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-06 10:48:21.035   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,10-06 10:48:21.035   928   940 E PackageManager: Failed to write settings, restoring backup
10-06 10:48:21.035   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-06 10:48:21.035   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-06 10:48:21.035   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-06 10:48:21.035   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-06 10:48:21.035   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-06 10:48:21.035   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:48:21.035   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:48:21.035   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-06 10:48:21.041   928   941 E DropBoxManagerService: Can't write: system_server_wtf
10-06 10:48:21.041   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-06 10:48:21.041   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-06 10:48:21.041   928   941 E DropBoxManagerService: 	... 13 more
,10-06 10:48:21.042  3812  3941 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-06 10:48:21.053  3578  3578 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,10-06 10:48:21.054  3578  3578 D AndroidRuntime: Shutting down VM
--------- beginning of crash
10-06 10:48:21.054  3578  3578 E AndroidRuntime: FATAL EXCEPTION: main
10-06 10:48:21.054  3578  3578 E AndroidRuntime: Process: com.google.process.gapps, PID: 3578
10-06 10:48:21.054  3578  3578 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-06 10:48:21.054  3578  3578 E AndroidRuntime: 	... 8 more
,10-06 10:48:21.056   928  3769 I ActivityManager: Start proc 6038:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,10-06 10:48:21.057  3812  3941 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-06 10:48:21.057  3812  3941 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3812
10-06 10:48:21.057  3812  3941 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:48:21.057  3812  3941 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-06 10:48:21.067  3401  6032 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-06 10:48:21.067   928  6050 E DropBoxManagerService: Can't write: system_app_crash
10-06 10:48:21.067   928  6050 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-06 10:48:21.067   928  6050 E DropBoxManagerService: 	... 5 more
10-06 10:48:21.067  3578  3578 I Process : Sending signal. PID: 3578 SIG: 9
10-06 10:48:21.068   928   941 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2708)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: Can't write: system_app_crash
10-06 10:48:21.068   928  6049 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-06 10:48:21.068   928  6049 E DropBoxManagerService: 	... 5 more
10-06 10:48:21.069   928   941 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
10-06 10:48:21.069   928   941 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
10-06 10:48:21.069   928   941 W Broad,castQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-06 10:48:21.069   928   941 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-06 10:48:21.076  3401  6032 E AndroidRuntime: Process: android.process.acore, PID: 3401
10-06 10:48:21.076  3401  6032 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-06 10:48:21.076  3401  6032 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-06 10:48:21.098   928  2969 D WifiService: Client connection lost with reason: 4
10-06 10:48:21.101   385   483 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Cannot send after transport endpoint shutdown
10-06 10:48:21.101   385   483 E SurfaceFlinger: eventControl(0, 0) failed Cannot send after transport endpoint shutdown
10-06 10:48:21.101   928   941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
10-06 10:48:21.102   928   941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 11000ms
10-06 10:48:21.102   928   941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
10-06 10:48:21.102   928   941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,10-06 10:48:21.113   928   941 I ActivityManager: Start proc 6052:com.google.process.gapps/u0a12 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
10-06 10:48:21.114   928  3418 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-06 10:48:21.120   928  3744 W ActivityManager: Spurious death for ProcessRecord{1577c36 6052:com.google.process.gapps/u0a12}, curProc for 3578: null
10-06 10:48:21.123  3812  3941 I Process : Sending signal. PID: 3812 SIG: 9
10-06 10:48:21.122   928  6063 E DropBoxManagerService: Can't write: system_app_crash
10-06 10:48:21.122   928  6063 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-06 10:48:21.122   928  6063 E DropBoxManagerService: 	... 5 more
10-06 10:48:21.124  3401  6032 I Process : Sending signal. PID: 3401 SIG: 9
,10-06 10:48:21.161   928  3824 D GraphicsStats: Buffer count: 1
,10-06 10:48:21.161   928  3741 I WindowState: WIN DEATH: Window{cbf5cdf u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-06 10:48:21.162   928  3769 I ActivityManager: Process android.process.acore (pid 3401) has died
10-06 10:48:21.162   928  3769 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-06 10:48:21.169   928  3198 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3812) has died
10-06 10:48:21.169   928  3198 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-06 10:48:21.170   928  3198 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-06 10:48:21.185   928   941 I ActivityManager: Start proc 6066:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-06 10:48:21.409   385   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
