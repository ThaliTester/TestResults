#### Test 87463757ce3bfc1_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-30 08:02:25.176   541   541 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-30 08:02:25.177   541   541 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 08:02:26.267  5670  5670 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-30 08:02:26.273  5670  5670 D AndroidRuntime: CheckJNI is OFF
09-30 08:02:26.302  5670  5670 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-30 08:02:26.338  5670  5670 I Radio-JNI: register_android_hardware_Radio DONE
09-30 08:02:26.355  5670  5670 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-30 08:02:26.361   927  3852 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-30 08:02:26.401   927  3852 I ActivityManager: Start proc 5679:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-30 08:02:26.427  5670  5670 D AndroidRuntime: Shutting down VM
,09-30 08:02:26.735   927  3915 I WindowManager: Screenshot max retries 4 of Token{30fb91c ActivityRecord{dd4628f u0 com.test.thalitest/.MainActivity t2}} appWin=Window{dcc1487 u0 Starting com.test.thalitest} drawState=2
,09-30 08:02:26.800  5679  5679 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-30 08:02:26.830   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:02:26.835  5679  5679 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-30 08:02:26.859  5679  5679 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 51-70)
09-30 08:02:26.859  5679  5679 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 08:02:26.880  5679  5679 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {effed21}
,09-30 08:02:26.880  5679  5679 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-30 08:02:26.881  5679  5679 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-30 08:02:26.886  5679  5679 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-30 08:02:26.887  5679  5679 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-30 08:02:26.920  5679  5679 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-30 08:02:26.937  5679  5679 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-30 08:02:26.938  5679  5679 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-30 08:02:26.938  5679  5679 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-30 08:02:26.938  5679  5679 I Adreno  : Build Date                       : 12/06/15
09-30 08:02:26.938  5679  5679 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-30 08:02:26.938  5679  5679 I Adreno  : Local Branch                     : mybranch17112971
09-30 08:02:26.938  5679  5679 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-30 08:02:26.938  5679  5679 I Adreno  : Remote Branch                    : NONE
09-30 08:02:26.938  5679  5679 I Adreno  : Reconstruct Branch               : NOTHING
,09-30 08:02:26.983   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@466f6aa:true
,09-30 08:02:27.012  4285  4285 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27306]" dev="sockfs" ino=27306 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 08:02:27.012  4285  4285 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[27306]" dev="sockfs" ino=27306 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 08:02:27.026  5679  5679 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-30 08:02:27.035  5679  5679 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-30 08:02:27.055  4285  4285 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33529]" dev="sockfs" ino=33529 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 08:02:27.055  4285  4285 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33529]" dev="sockfs" ino=33529 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-30 08:02:27.059  5679  5716 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-30 08:02:27.059  3912  3912 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[27318]" dev="sockfs" ino=27318 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-30 08:02:27.059  3912  3912 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[27318]" dev="sockfs" ino=27318 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-30 08:02:27.066  5679  5703 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-30 08:02:27.086  5679  5716 I OpenGLRenderer: Initialized EGL, version 1.4
,09-30 08:02:27.147   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +409ms (total +770ms)
,09-30 08:02:27.190  5679  5679 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5679
,09-30 08:02:27.287  5679  5679 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-30 08:02:27.422  5679  5718 D jxcore_app_log: JniHelper::setJavaVM(0xf50bc000), pthread_self() = -563873488
,09-30 08:02:27.429  5679  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-30 08:02:27.429  5679  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-30 08:02:27.429  5679  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-30 08:02:27.429  5679  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-30 08:02:27.429  5679  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-30 08:02:27.430  5679  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39a1de added. We now have 1 listener(s)
,09-30 08:02:27.434  5679  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-30 08:02:27.435  5679  5718 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:02:27.436  5679  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:02:27.437  5679  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-30 08:02:27.447  5679  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@808a1d5 added. We now have 1 listener(s)
09-30 08:02:27.447  5679  5718 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:02:27.452   927  3038 D WifiService: New client listening to asynchronous messages
,09-30 08:02:27.452  5679  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:02:27.452  5679  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-30 08:02:27.453  5679  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-30 08:02:27.453  5679  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-30 08:02:27.453  5679  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-30 08:02:27.455  5679  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:02:27.455  5679  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-30 08:02:27.460  5679  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-30 08:02:27.460  5679  5718 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:02:27.460  5679  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:02:27.460  5679  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:02:27.460  5679  5718 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:02:27.460  5679  5718 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:02:27.460  5679  5718 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:27.460  5679  5718 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:02:27.460  5679  5718 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:02:27.460  5679  5718 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-30 08:02:27.460  5679  5718 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:02:27.461  5679  5718 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-30 08:02:27.463  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:02:27.465  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:02:27.481  5679  5679 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-30 08:02:27.777  5679  5725 W jxcore-log: Initializing JXcore engine
,09-30 08:02:27.777  5679  5725 W jxcore-log: JXcore engine is ready
,09-30 08:02:27.799  5725  5725 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12506 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-30 08:02:27.799  5725  5725 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15390]" dev="sockfs" ino=15390 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-30 08:02:27.799  5725  5725 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-30 08:02:27.799  5725  5725 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33510]" dev="sockfs" ino=33510 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
09-30 08:02:27.810  5679  5725 W jxcore-log: Starting JXcore engine
,09-30 08:02:27.865  5679  5725 W jxcore-log: Platform android
09-30 08:02:27.865  5679  5725 W jxcore-log: 
,09-30 08:02:27.865  5679  5725 W jxcore-log: Process ARCH arm
09-30 08:02:27.865  5679  5725 W jxcore-log: 
,09-30 08:02:27.963  5679  5725 I jxcore-log: JXcore Cordova bridge is ready!
09-30 08:02:27.963  5679  5725 I jxcore-log: 
,09-30 08:02:27.963  5679  5725 W jxcore-log: JXcore engine is started
,09-30 08:02:27.973  5679  5718 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-30 08:02:27.980  5679  5679 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-30 08:02:28.072   927  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 08:02:32.872   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:02:35.178   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:36.179   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:37.181   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:37.501  5679  5725 I jxcore-log: 2016-09-30 12:02:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 08:02:37.501  5679  5725 I jxcore-log: 
,09-30 08:02:37.503  5679  5725 I jxcore-log: 2016-09-30 12:02:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 08:02:37.503  5679  5725 I jxcore-log: 
,09-30 08:02:37.507  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:02:37.507  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:02:37.507  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:02:37.507  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:02:37.507  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:02:37.507  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:37.507  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:02:37.507  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:02:37.509  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:02:37.510  5679  5725 I jxcore-log: 2016-09-30 12:02:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 08:02:37.510  5679  5725 I jxcore-log: 
,09-30 08:02:37.512  5679  5725 I jxcore-log: 2016-09-30 12:02:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 08:02:37.512  5679  5725 I jxcore-log: 
,09-30 08:02:37.757  5679  5725 I jxcore-log: 2016-09-30 12:02:37 - DEBUG UnitTest_app: 'Running unit tests'
09-30 08:02:37.757  5679  5725 I jxcore-log: 
,09-30 08:02:37.758  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:02:37.758  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bd9aa3 added. We now have 2 listener(s)
09-30 08:02:37.759  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:02:37.759  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 08:02:37.759  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:02:37.759  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:02:37.759  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6eab1a0 added. We now have 2 listener(s)
09-30 08:02:37.759  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:02:37.760  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 08:02:37.762  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:02:37.765  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:02:37.765  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:02:37.765  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:02:37.765  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:02:37.765  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:02:37.765  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:37.765  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:02:37.765  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:02:37.766  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:37.766  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:02:37.766  5679  5725 D executeNativeTests: Running unit tests
,09-30 08:02:37.772  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:02:37.777  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:02:37.802  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 08:02:37.803  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce added. We now have 3 listener(s)
,09-30 08:02:37.803  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:02:37.803  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:02:37.803  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 08:02:37.803  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:02:37.803  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef added. We now have 3 listener(s)
09-30 08:02:37.803  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:02:37.804  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 08:02:37.805  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:02:37.807  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:02:37.807  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:02:37.807  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:02:37.807  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:02:37.807  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:02:37.807  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:37.807  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:02:37.807  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:02:37.808  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:37.808  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 08:02:37.810  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 08:02:37.810  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:02:37.810  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:02:37.810  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:02:37.810  5679  5725 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-30 08:02:37.811  5679  5725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 08:02:37.811  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 08:02:37.811  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:02:37.811  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:02:37.811  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:02:37.811  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:37.811  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:37.811  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:37.812  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:37.812  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:37.812  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:02:37.812  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:37.812  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:02:37.812  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce removed from the list
09-30 08:02:37.812  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:37.812  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef removed from the list
09-30 08:02:37.813  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:02:37.813  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:37.813  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:37.814  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:37.814  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:37.815  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:37.815  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:37.815  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:37.815  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
,09-30 08:02:37.815  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:02:37.816  5679  5725 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-30 08:02:37.816  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:37.816  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:37.816  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:37.816  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:37.816  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:37.816  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:37.816  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:37.816  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:37.816  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:37.816  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:37.816  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:37.816  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:37.816  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:02:37.816  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:37.816  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:37.817  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:37.817  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:37.817  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:37.817  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
,09-30 08:02:37.819  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 08:02:37.819  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 08:02:37.819  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 08:02:37.819  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 08:02:37.819  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 08:02:37.819  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 08:02:37.819  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-30 08:02:37.819  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 08:02:37.820  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 08:02:37.820  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:37.820  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:37.820  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:37.820  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:02:37.820  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:37.820  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:37.820  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:37.820  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:37.820  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:02:37.821  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:37.821  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:37.821  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:37.821  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:37.821  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:37.821  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:02:37.821  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:37.821  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:37.821  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:37.822  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:37.822  5679  5725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 08:02:37.823  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:02:37.825  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:02:37.825  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:02:37.825  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:02:37.825  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:02:37.825  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:02:37.825  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:37.825  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:02:37.825  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:02:37.829  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:37.830  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:02:37.830  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:02:37.830  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:02:37.830  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:02:37.830  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:02:37.830  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 08:02:37.833  5679  5725 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 08:02:37.833  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 08:02:37.835  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:02:37.837  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 08:02:37.837  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:02:37.838  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 08:02:37.839  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:02:37.840  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-30 08:02:37.842  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-30 08:02:37.842  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 08:02:37.842  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:02:37.842  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:02:37.843  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:02:37.843  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:02:37.843  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:02:37.845  4659  4681 D BtGatt.GattService: registerClient() - UUID=7b58db2a-4a91-48e9-8447-b79ef9f4a69f
09-30 08:02:37.846  4659  4726 D BtGatt.GattService: onClientRegistered() - UUID=7b58db2a-4a91-48e9-8447-b79ef9f4a69f, clientIf=5
09-30 08:02:37.846  5679  5689 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:02:37.847  4659  4887 D BtGatt.GattService: start scan with filters
09-30 08:02:37.851  4659  4730 D BtGatt.ScanManager: handling starting scan
09-30 08:02:37.851  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 08:02:37.852  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:02:37.852  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:02:37.852  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:02:37.852  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:02:37.852  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:02:37.852  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 08:02:37.854  4659  4730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
09-30 08:02:37.856  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:02:37.857  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:02:37.857  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:02:37.859  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:02:37.860  5679  5725 I io.jxcore.node.ConnectionHelper: start: OK
09-30 08:02:37.862  4659  4726 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:02:37.862  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:37.862  4659  4730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 08:02:37.868  4659  4726 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:02:37.868  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:37.869  4659  4730 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:02:37.869  4659  4730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 08:02:37.880  4659  4726 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:02:37.881  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:37.887  4659  4726 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 08:02:37.887  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:02:38.182   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:38.360  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 08:02:38.361  5679  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 08:02:38.361  5679  5679 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 08:02:38.935   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:02:38.941   927  3039 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-30 08:02:39.183   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:40.184   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 08:02:41.952   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:02:42.864  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:02:42.864  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:42.864  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 08:02:42.864  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:42.864  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 08:02:42.865  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:02:42.865  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 08:02:42.865  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:02:42.865  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 08:02:42.865  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:02:42.866  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:02:42.866  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:02:42.867  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:02:42.868  4659  4887 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:02:42.870  4659  4898 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 08:02:42.871  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 08:02:42.872  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:02:42.872  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:02:42.872  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:02:42.872  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:02:42.872  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:02:42.872  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:02:42.872  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 08:02:42.876  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 08:02:42.877  4659  4659 D BtGatt.ScanManager: awakened up at time 236089
09-30 08:02:42.877  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:02:42.877  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:02:42.877  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:02:42.878  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 08:02:42.880  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:02:42.883  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:42.883  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:02:42.883  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:42.883  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:02:42.883  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:02:42.883  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:02:42.883  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:42.884  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:42.884  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:42.884  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:42.884  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:42.884  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:02:42.885  4659  4726 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:02:42.885  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:42.885  4659  4730 D BtGatt.ScanManager: stopping BLe Batch
,09-30 08:02:42.896  4659  4726 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 08:02:42.896  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:42.896  4659  4730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 08:02:42.925  4659  4726 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-30 08:02:42.925  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:42.925  4659  4726 D BtGatt.GattService: current time is 236137841160
09-30 08:02:42.926  4659  4726 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -76, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -75, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -76, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -52, 11, 57, -70, 107, -17, 1, 0, -99, 29, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 37, -47, 14, -113, 116, -46, 1, -128, -74, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 08:02:42.928  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 08:02:42.929  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 08:02:42.929  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 08:02:42.929  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 08:02:42.930  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 08:02:42.930  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,09-30 08:02:42.930  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 08:02:43.383  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:02:44.982   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:02:44.989   927  3039 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-30 08:02:45.185   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:46.186   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:47.188   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:47.886  5679  5725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 08:02:47.893  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:02:47.904  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:02:47.904  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:02:47.904  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:02:47.904  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:02:47.904  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:02:47.904  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:47.904  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:02:47.904  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:02:47.909  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:02:47.909  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:02:47.910  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:02:47.910  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:02:47.910  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:02:47.910  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:02:47.910  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 08:02:47.914  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:02:47.916  5679  5725 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 08:02:47.916  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 08:02:47.919  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:02:47.922  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:02:47.923  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:02:47.924  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 08:02:47.929  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 08:02:47.929  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:02:47.930  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:02:47.930  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:02:47.930  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:02:47.931  5679  5725 D BluetoothAdapter: STATE_ON
,09-30 08:02:47.934  4659  4887 D BtGatt.GattService: registerClient() - UUID=ab43b64b-412b-4bc3-a4a0-3cd6c0ff8d39
,09-30 08:02:47.935  4659  4726 D BtGatt.GattService: onClientRegistered() - UUID=ab43b64b-412b-4bc3-a4a0-3cd6c0ff8d39, clientIf=5
09-30 08:02:47.935  5679  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:02:47.936  4659  4898 D BtGatt.GattService: start scan with filters
,09-30 08:02:47.941  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 08:02:47.941  4659  4730 D BtGatt.ScanManager: handling starting scan
09-30 08:02:47.941  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:02:47.941  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 08:02:47.941  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-30 08:02:47.942  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:02:47.942  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:02:47.942  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 08:02:47.946  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:02:47.946  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-30 08:02:47.946  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:02:47.949  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:02:47.950  4659  4726 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:02:47.951  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:47.951  4659  4730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 08:02:47.952  5679  5725 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 08:02:47.955  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:02:47.955  5679  5725 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 08:02:47.956  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:47.956  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 08:02:47.956  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:47.956  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:02:47.956  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:47.956  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-30 08:02:47.956  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:02:47.956  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:02:47.956  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:02:47.956  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-30 08:02:47.956  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:02:47.957  5679  5725 D BluetoothAdapter: STATE_ON
,09-30 08:02:47.958  4659  4898 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:02:47.958  4659  4726 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 08:02:47.958  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:47.958  4659  4730 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:02:47.958  4659  4730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:02:47.959  4659  4677 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 08:02:47.959  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 08:02:47.959  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:02:47.959  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:02:47.959  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:02:47.959  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:02:47.959  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:02:47.959  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:02:47.959  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 08:02:47.961  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:02:47.962  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:02:47.962  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:02:47.962  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:02:47.962  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 08:02:47.962  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:02:47.964  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:47.964  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:47.964  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:02:47.964  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:47.964  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
,09-30 08:02:47.964  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:47.964  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:02:47.964  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:47.964  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:47.964  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:02:47.965  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:47.965  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 08:02:47.965  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:47.965  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:47.966  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:47.966  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:47.966  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:47.966  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:47.967  5679  5725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 08:02:47.970  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:02:47.971  4659  4726 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:02:47.971  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:02:47.974  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:02:47.974  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:02:47.974  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:02:47.974  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:02:47.974  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:02:47.974  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:47.974  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:02:47.974  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:02:47.976  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:02:47.977  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:02:47.977  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:02:47.977  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:02:47.977  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:02:47.977  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:02:47.977  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 08:02:47.979  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:02:47.980  4659  4726 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 08:02:47.980  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:47.981  5679  5725 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 08:02:47.981  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 08:02:47.983  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:02:47.985  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:02:47.986  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:02:47.986  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 08:02:47.986  4659  4726 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:02:47.986  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:47.987  4659  4730 D BtGatt.ScanManager: stopping BLe Batch
,09-30 08:02:47.990  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 08:02:47.990  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:02:47.990  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:02:47.990  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:02:47.990  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:02:47.991  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:02:47.991  4659  4726 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 08:02:47.991  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:47.992  4659  4730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 08:02:47.993  4659  4677 D BtGatt.GattService: registerClient() - UUID=ea455033-f6a2-4388-b553-782588b84253
09-30 08:02:47.993  4659  4726 D BtGatt.GattService: onClientRegistered() - UUID=ea455033-f6a2-4388-b553-782588b84253, clientIf=5
,09-30 08:02:47.993  5679  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:02:47.993  4659  4681 D BtGatt.GattService: start scan with filters
09-30 08:02:47.996  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 08:02:47.996  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:02:47.996  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 08:02:47.996  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:02:47.996  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-30 08:02:47.996  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-30 08:02:47.996  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 08:02:47.997  4659  4726 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 08:02:47.997  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:47.998  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:02:47.998  4659  4730 D BtGatt.ScanManager: handling starting scan
09-30 08:02:47.998  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:02:47.998  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:02:48.000  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:02:48.002  5679  5725 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 08:02:48.004  4659  4726 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:02:48.004  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:02:48.005  4659  4730 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 08:02:48.010  4659  4726 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 08:02:48.010  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:48.010  4659  4730 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:02:48.010  4659  4730 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 08:02:48.019  4659  4726 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:02:48.019  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:02:48.024  4659  4726 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 08:02:48.024  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:02:48.190   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:48.500  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 08:02:48.500  5679  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:02:48.500  5679  5679 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 08:02:49.192   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:02:50.193   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 08:02:51.036   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:02:51.044   927  3039 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 54
,09-30 08:02:53.002  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:02:53.003  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:02:53.003  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 08:02:53.003  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:53.003  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 08:02:53.004  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:02:53.004  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-30 08:02:53.004  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 08:02:53.004  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:02:53.004  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:02:53.005  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-30 08:02:53.005  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:02:53.007  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:02:53.008  4659  4898 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:02:53.010  4659  4887 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 08:02:53.010  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-30 08:02:53.011  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:02:53.011  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:02:53.011  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:02:53.011  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:02:53.011  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,09-30 08:02:53.012  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:02:53.012  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 08:02:53.014  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:02:53.014  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:02:53.015  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:02:53.015  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:02:53.015  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:02:53.016  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:02:53.017  4659  4659 D BtGatt.ScanManager: awakened up at time 246229
,09-30 08:02:53.019  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 08:02:53.019  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 08:02:53.019  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:02:53.023  4659  4726 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:02:53.023  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:53.023  4659  4730 D BtGatt.ScanManager: stopping BLe Batch
,09-30 08:02:53.031  4659  4726 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 08:02:53.031  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:53.031  4659  4730 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 08:02:53.053  4659  4726 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-30 08:02:53.053  4659  4726 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:02:53.053  4659  4726 D BtGatt.GattService: current time is 246265742285
,09-30 08:02:53.054  4659  4726 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -76, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -77, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -52, 11, 57, -70, 107, -17, 1, 0, -98, 33, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 116, -43, -111, -91, -20, -29, 1, -128, -78, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 08:02:53.054  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 08:02:53.054  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 08:02:53.054  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-30 08:02:53.054  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-30 08:02:53.055  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 08:02:53.055  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-30 08:02:53.055  4659  4726 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-30 08:02:53.520  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:02:53.520  5679  5679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:53.520  5679  5679 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 08:02:54.061   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:02:54.066   927  3039 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-30 08:02:58.020  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:02:58.021  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:58.021  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:58.021  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:02:58.021  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.021  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:02:58.022  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.022  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.022  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:02:58.022  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.022  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.022  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.024  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.024  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:02:58.029  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:58.029  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:58.029  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:02:58.029  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
,09-30 08:02:58.031  5679  5725 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-30 08:02:58.032  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:02:58.033  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:58.033  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:58.033  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.033  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:02:58.033  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.033  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.034  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.034  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.034  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.034  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.034  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:02:58.034  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.035  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.035  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.038  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:58.038  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:58.039  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.039  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
,09-30 08:02:58.040  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 08:02:58.040  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:58.040  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:58.040  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 08:02:58.041  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.041  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.041  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.041  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.041  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.041  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.041  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.041  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.041  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:02:58.041  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.041  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.041  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:02:58.043  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:58.043  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:02:58.043  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.043  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.044  5679  5725 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-30 08:02:58.044  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:58.044  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:58.044  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 08:02:58.044  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.044  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.044  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.044  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.044  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.045  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:02:58.045  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.045  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.045  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.045  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.045  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.045  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.046  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:02:58.046  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:58.046  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.046  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.047  5679  5725 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-30 08:02:58.047  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:02:58.047  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:58.047  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:58.048  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.048  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.048  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.048  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:02:58.048  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.048  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.048  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.048  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.048  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.048  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.048  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.048  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.050  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:58.050  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:58.050  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.050  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.051  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 08:02:58.051  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:02:58.051  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:02:58.051  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-30 08:02:58.051  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:02:58.051  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:02:58.051  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 08:02:58.051  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:02:58.052  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:02:58.052  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:58.052  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:02:58.052  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:58.052  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.052  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.052  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.052  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:02:58.052  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.052  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.052  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.052  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.052  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.052  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.053  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.053  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:02:58.054  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:02:58.054  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:58.054  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.054  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.055  5679  5725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:02:58.055  5679  5725 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 08:02:58.055  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 08:02:58.058  5679  5725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:02:58.059  5679  5725 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 08:02:58.059  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-30 08:02:58.060  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 08:02:58.060  5679  5725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-30 08:02:58.061  5679  5725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 08:02:58.061  5679  5725 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-30 08:02:58.061  5679  5725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:02:58.061  5679  5725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 08:02:58.061  5679  5725 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-30 08:02:58.061  5679  5725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:02:58.061  5679  5725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 08:02:58.061  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-30 08:02:58.065  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-30 08:02:58.065  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-30 08:02:58.065  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-30 08:02:58.066  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-30 08:02:58.066  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-30 08:02:58.066  5679  5725 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-30 08:02:58.066  5679  5725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:02:58.067  5679  5725 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-30 08:02:58.067  5679  5726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-30 08:02:58.067  5679  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-30 08:02:58.067  5679  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-30 08:02:58.067  5679  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,09-30 08:02:58.068  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:58.068  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:58.068  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:58.068  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.068  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.068  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.068  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.068  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-30 08:02:58.069  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.069  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.069  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.069  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.069  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.069  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.069  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.069  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.070  5679  5726 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-30 08:02:58.070  5679  5726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:02:58.071  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
,09-30 08:02:58.071  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-30 08:02:58.071  5679  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
,09-30 08:02:58.069  4898  4898 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33892]" dev="sockfs" ino=33892 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-30 08:02:58.069  4898  4898 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33892]" dev="sockfs" ino=33892 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-30 08:02:58.072  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:02:58.073  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:58.073  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.073  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.074  5679  5725 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-30 08:02:58.074  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:58.074  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:58.074  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:58.075  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.075  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:02:58.075  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.075  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.075  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.075  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.075  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.075  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.075  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.075  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.075  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.075  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:02:58.076  5679  5726 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
09-30 08:02:58.076  5679  5726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-30 08:02:58.076  5679  5726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-30 08:02:58.077  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:58.077  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:58.077  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.077  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.078  5679  5725 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-30 08:02:58.078  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:58.078  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:02:58.078  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:58.078  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.078  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.078  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.079  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.079  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.079  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.079  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.079  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.079  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.079  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.079  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.079  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.080  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:02:58.080  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:02:58.080  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.080  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.081  5679  5725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-30 08:02:58.081  5679  5725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-30 08:02:58.081  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 08:02:58.081  5679  5725 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-30 08:02:58.081  5679  5725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 08:02:58.081  5679  5725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-30 08:02:58.081  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-30 08:02:58.081  5679  5725 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-30 08:02:58.081  5679  5725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 08:02:58.081  5679  5725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 08:02:58.082  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 08:02:58.082  5679  5725 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-30 08:02:58.082  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:02:58.082  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:02:58.082  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:02:58.082  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.082  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:02:58.082  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.082  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.082  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.082  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.082  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.082  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:02:58.082  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.082  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.082  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.082  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.083  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:02:58.083  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:02:58.084  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.084  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.084  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:02:58.084  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.084  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:02:58.084  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:02:58.085  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:02:58.085  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:02:58.085  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:02:58.085  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:02:58.085  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:02:58.085  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:03:00.106   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:03:00.194   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:01.195   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:02.196   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:03.085  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:03:03.086  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.086  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:03:03.086  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.086  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.086  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:03:03.087  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:03:03.087  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:03:03.087  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:03:03.087  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:03:03.088  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:03:03.088  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:03:03.088  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.088  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:03:03.088  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:03:03.088  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.089  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.089  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:03:03.089  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.089  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.089  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.089  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.093  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:03:03.093  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:03:03.093  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:03:03.093  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.097  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-30 08:03:03.099  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:03:03.102  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-30 08:03:03.104  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-30 08:03:03.104  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,09-30 08:03:03.104  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-30 08:03:03.105  5679  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,09-30 08:03:03.107  5679  5728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:03:03.109  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-30 08:03:03.109  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-30 08:03:03.109  5679  5679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-30 08:03:03.109  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:03:03.110  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-30 08:03:03.110  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-30 08:03:03.110  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-30 08:03:03.110  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:03:03.110  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 08:03:03.110  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-30 08:03:03.111  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:03:03.111  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:03:03.111  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:03:03.111  5679  5679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-30 08:03:03.111  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:03:03.111  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:03:03.111  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.111  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.113  5679  5728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-30 08:03:03.113  5679  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-30 08:03:03.113  5679  5728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-30 08:03:03.114  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 08:03:03.114  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.114  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:03:03.114  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:03:03.114  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:03:03.114  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:03:03.115  5679  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-30 08:03:03.115  5679  5679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:03:03.109  4887  4887 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32093]" dev="sockfs" ino=32093 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 08:03:03.109  4887  4887 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32093]" dev="sockfs" ino=32093 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 08:03:03.115  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:03:03.115  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 08:03:03.115  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:03:03.115  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.115  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.116  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:03:03.116  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:03:03.116  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.116  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.116  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:03:03.116  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.116  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.116  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:03:03.117  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:03:03.119  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:03:03.119  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:03:03.119  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.119  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.121  5679  5725 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-30 08:03:03.122  5679  5725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 08:03:03.122  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 08:03:03.122  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:03:03.122  5679  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:03:03.123  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:03:03.123  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:03:03.123  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 08:03:03.123  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:03:03.123  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.123  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.123  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:03:03.124  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:03:03.124  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.124  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.124  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:03:03.124  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.124  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:03:03.125  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.125  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.126  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:03:03.126  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:03:03.126  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.126  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.132  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:03:03.132  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:03:03.132  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:03:03.132  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:03:03.132  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:03:03.132  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.132  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:03:03.132  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:03:03.132  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.132  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.132  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:03:03.132  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.132  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.133  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.133  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.134  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:03:03.134  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:03:03.134  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.134  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
,09-30 08:03:03.135  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:03:03.135  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:03:03.135  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:03:03.136  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:03:03.136  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.136  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.136  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:03:03.136  5679  5725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2221dce not in the list
09-30 08:03:03.136  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.136  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.136  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:03:03.136  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.136  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.136  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:03.136  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:03.137  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:03:03.137  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:03:03.138  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:03.138  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8efa4ef not in the list
09-30 08:03:03.139  5679  5725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-30 08:03:03.139  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 08:03:03.139  5679  5725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-30 08:03:03.139  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 08:03:03.139  5679  5725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-30 08:03:03.139  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 08:03:03.142  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 08:03:03.142  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-30 08:03:03.143  5679  5725 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-30 08:03:03.143  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 08:03:03.143  5679  5725 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-30 08:03:03.143  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 08:03:03.143  5679  5725 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-30 08:03:03.144  5679  5725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-30 08:03:03.144  5679  5725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-30 08:03:03.144  5679  5725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-30 08:03:03.146  5679  5725 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-30 08:03:03.146  5679  5725 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-30 08:03:03.146  5679  5725 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-30 08:03:03.146  5679  5725 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-30 08:03:03.147  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:03:03.147  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c99b039 added. We now have 3 listener(s)
09-30 08:03:03.147  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:03:03.149  5679  5725 D BluetoothAdapter: enable(): BT is already enabled..!
,09-30 08:03:03.149   927  3915 D WifiService: setWifiEnabled: true pid=5679, uid=10077
09-30 08:03:03.149   927  3915 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:03:03.196   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:03.200  4659  4859 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-30 08:03:03.200  4659  4885 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-30 08:03:03.615  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:03:04.197   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:05.198   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 08:03:08.075   927  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 08:03:08.155  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:03:08.156  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@637967e added. We now have 4 listener(s)
09-30 08:03:08.156  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:03:08.168  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:03:08.169  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@637967e removed from the list
09-30 08:03:08.169  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:03:08.169  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:03:08.169  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:08.172  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:03:08.172  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f9a7df added. We now have 4 listener(s)
,09-30 08:03:08.172  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:03:08.175  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:08.175  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f9a7df removed from the list
09-30 08:03:08.175  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:03:08.175  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:08.175  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:08.177  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:03:08.177  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ec9c2c added. We now have 4 listener(s)
09-30 08:03:08.177  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:03:08.182   927  3912 D WifiService: setWifiEnabled: false pid=5679, uid=10077
09-30 08:03:08.182   927  3912 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:03:08.190   927  3037 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 08:03:08.191   927  3037 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 08:03:08.191   927  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 08:03:08.191   927  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:03:08.202  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-30 08:03:08.202  4659  4722 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 08:03:08.202  4659  4722 D BluetoothAdapterProperties: Setting state to 13
09-30 08:03:08.203  4659  4722 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 08:03:08.203  4659  4722 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 08:03:08.205  4659  4722 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:03:08.212  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:03:08.212  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:03:08.212  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.212  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.212  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:08.212  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.212  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:08.212  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:03:08.212  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:03:08.213  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.213  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:08.214  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 08:03:08.214  4659  4659 D BluetoothMapService: onReceive
09-30 08:03:08.214  4659  4659 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-30 08:03:08.214  4659  4659 D BluetoothMapService: STATE_TURNING_OFF
09-30 08:03:08.215  4659  4659 D BluetoothMapService: MAP Service closeService in
09-30 08:03:08.215  4659  4659 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 08:03:08.215  4659  4659 D ObexServerSockets0: shutdown(block = true)
09-30 08:03:08.216  4659  4659 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 08:03:08.216  4659  4900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,09-30 08:03:08.216  4659  4659 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 08:03:08.216  4659  4885 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 08:03:08.217  4659  4901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 08:03:08.218   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-30 08:03:08.219   927  5424 D DhcpClient: Clearing IP address
09-30 08:03:08.220  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.221   506   920 D CommandListener: Setting iface cfg
09-30 08:03:08.224  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:08.225   927  5427 D DhcpClient: Receive thread stopped
09-30 08:03:08.226  4659  4659 I BtOppRfcommListener: stopping Accept Thread
09-30 08:03:08.226  4659  5388 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 08:03:08.226  4659  5388 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 08:03:08.228  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.228  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.228  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.228  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.228  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:08.228  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.228  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:08.228  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:03:08.228  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:03:08.229  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:03:08.230  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:08.232  3644  5480 V NativeCrypto: Read error: ssl=0x7f6e4ce380: I/O error during system call, Connection timed out
09-30 08:03:08.232   927   940 I ActivityManager: Start proc 5732:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-30 08:03:08.234  4659  4726 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:03:08.234  3644  5480 V NativeCrypto: SSL shutdown failed: ssl=0x7f6e4ce380: I/O error during system call, Broken pipe
09-30 08:03:08.235  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.236  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.236  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.236  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.236  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:08.236  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.236  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:08.236  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:03:08.236  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:03:08.237   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 08:03:08.237   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-30 08:03:08.237  4659  4722 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 08:03:08.239   539   539 E Parcel  : Reading a NULL string not supported here.
09-30 08:03:08.239  4659  4659 D HeadsetService: Received stop request...Stopping profile...
09-30 08:03:08.241  3182  3193 D BluetoothHeadset: Proxy object disconnected
09-30 08:03:08.241  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.241  4659  4659 D A2dpService: Received stop request...Stopping profile...
09-30 08:03:08.241  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:08.241  3857  4120 D BluetoothHeadset: Proxy object disconnected
09-30 08:03:08.241  4659  4892 D A2dpStateMachine: Exit Disconnected: -1
09-30 08:03:08.242   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 08:03:08.242   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 08:03:08.242   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 08:03:08.244  4659  4659 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:08.244  4659  4659 V BluetoothAdapterState: isTurningOn()=false
,09-30 08:03:08.244  4659  4659 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:08.244  4659  4659 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:08.244   927   927 D RttService: SCAN_AVAILABLE : 1
09-30 08:03:08.245   927   927 D BluetoothA2dp: Proxy object disconnected
09-30 08:03:08.245   927  3147 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 08:03:08.245  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.245   927  3039 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-30 08:03:08.245  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.245  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.245  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.245  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:08.245  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.245  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:08.245  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:08.245  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:03:08.246  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.246  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:08.246   927  3037 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-30 08:03:08.247  3809  3965 W QCNEJ   : |CORE| network lost: 100
09-30 08:03:08.247  3809  3965 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 08:03:08.247  4659  4659 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 08:03:08.247  4659  4659 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-30 08:03:08.247  3182  3182 D HeadsetProfile: Bluetooth service disconnected
09-30 08:03:08.247  4659  4859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:08.247  3182  3182 D BluetoothA2dp: Proxy object disconnected
09-30 08:03:08.247  4659  4859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:08.247  4659  4859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:08.248  4659  4659 D HidService: Received stop request...Stopping profile...
09-30 08:03:08.248  4659  4659 D HidService: Stopping Bluetooth HidService
09-30 08:03:08.248  4659  4726 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 08:03:08.249  4659  4726 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-30 08:03:08.249  3182  3182 D BluetoothInputDevice: Proxy object disconnected
09-30 08:03:08.249  3182  3182 D HidProfile: Bluetooth service disconnected
09-30 08:03:08.249  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.249   927  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 08:03:08.249  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.249  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.249  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.249  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:08.249  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.249  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:08.249  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:08.249  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:08.250  4659  4659 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:08.250  4659  4659 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:08.250  4659  4659 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:08.250  4659  4659 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:08.250  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.250  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:08.253  4659  4859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 08:03:08.253  4659  4859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:08.253  4659  4859 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 08:03:08.253  4659  4859 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 08:03:08.253  4659  4726 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 08:03:08.253  4659  4859 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 08:03:08.253  4659  4859 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 08:03:08.254  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.254  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.254  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.254  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.254  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:08.254  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.254  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:08.254  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:08.254  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:08.254  4659  4659 D HealthService: Received stop request...Stopping profile...
09-30 08:03:08.254  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.254  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:08.257  4659  4659 D PanService: Received stop request...Stopping profile...
,09-30 08:03:08.257  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.258  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:08.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:08.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:08.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:03:08.259  4659  4659 D BluetoothMapService: Received stop request...Stopping profile...
09-30 08:03:08.259  4659  4659 D BluetoothMapService: stop()
,09-30 08:03:08.260  4659  4659 D BluetoothMapAppObserver: deinitObservers()
,09-30 08:03:08.262  4659  4659 D BluetoothMapAppObserver: removeReceiver()
09-30 08:03:08.264  4659  4659 V BluetoothAdapterState: isTurningOff()=true
,09-30 08:03:08.264  4659  4659 V BluetoothAdapterState: isTurningOn()=false
,09-30 08:03:08.264  4659  4659 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:08.264  4659  4659 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:08.264  4659  4659 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 08:03:08.265  4659  4659 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 08:03:08.265  4659  4726 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 08:03:08.265  4659  4659 D SapService: Received stop request...Stopping profile...
09-30 08:03:08.265  4659  4659 V SapService: stop()
09-30 08:03:08.267  4659  4659 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:08.267  4659  4659 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:08.267  4659  4659 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:08.267  4659  4659 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:08.267  4659  4659 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 08:03:08.267  4659  4726 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 08:03:08.267  4659  4659 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 08:03:08.267  4659  4659 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:08.267  4659  4659 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:08.268  4659  4659 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:08.268  4659  4659 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:08.268  4659  4659 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 08:03:08.268  4659  4659 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-30 08:03:08.269  4659  4659 D BluetoothMapService: MAP Service closeService in
09-30 08:03:08.269  4659  4659 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:08.269  4659  4659 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:08.269  4659  4659 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:08.269  4659  4659 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:08.269  4659  4659 D BluetoothMapService: cleanup()
09-30 08:03:08.269  4659  4659 D BluetoothMapService: MAP Service closeService in
09-30 08:03:08.269  4659  4659 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:08.269  4659  4659 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:08.269  4659  4659 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:08.270  4659  4659 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:03:08.270  4659  4722 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 08:03:08.270  4659  4722 D BluetoothAdapterProperties: Setting state to 15
09-30 08:03:08.270  4659  4722 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 08:03:08.270  4659  4722 I BluetoothAdapterState: Entering BleOnState
09-30 08:03:08.271  3182  4033 D BluetoothPan: onBluetoothStateChange on: false
09-30 08:03:08.273   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:03:08.273   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:03:08.274  3182  3193 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 08:03:08.274  3857  3890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:03:08.275  3182  3197 D BluetoothMap: onBluetoothStateChange: up=false
09-30 08:03:08.275  3182  4033 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 08:03:08.276  3182  3193 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 08:03:08.277   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:03:08.277  3182  3197 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:03:08.278   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:03:08.278  4659  4722 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 08:03:08.278  4659  4722 D BluetoothAdapterProperties: Setting state to 16
09-30 08:03:08.278  4659  4722 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 08:03:08.278   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 08:03:08.279  4659  4722 D BluetoothAdapterProperties: onBleDisable
09-30 08:03:08.279  4659  4722 I BluetoothAdapterState: Entering PendingCommandState
09-30 08:03:08.279  4659  4723 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 08:03:08.280  4659  4859 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 08:03:08.280  4659  4859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 08:03:08.281  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.282  4659  4726 D BluetoothAdapterProperties: Scan Mode:20
,09-30 08:03:08.283  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.284  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.286  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.286  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.287  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.288  5732  5732 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-30 08:03:08.296   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:03:08.296   506   920 D CommandListener: Clearing all IP addresses on wlan0
,09-30 08:03:08.297   506   920 D TetherController: Setting IP forward enable = 0
09-30 08:03:08.298   927  3039 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-30 08:03:08.298   927  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 08:03:08.300   927  3037 D DhcpClient: doQuit
09-30 08:03:08.300   927  3037 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 08:03:08.301  3514  3514 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 08:03:08.301   927  5424 D DhcpClient: onQuitting
09-30 08:03:08.305   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-30 08:03:08.306  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:03:08.306  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.306  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.306  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.306  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:08.306  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.306  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:08.306  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:08.306  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:08.307  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.307  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:08.309  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.309  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.309  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.309  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.309  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:08.309  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.309  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:08.309  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:08.309  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:08.309  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.309  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:08.310  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.311  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:08.311  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:08.311  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:08.311  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:08.311  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:08.311  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:08.311  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:08.311  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:08.311  5312  5312 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMon,itor@cf30c1d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-30 08:03:08.311  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:08.311  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:08.312  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.314  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.315  5096  5109 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 08:03:08.315  5096  5109 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 08:03:08.315  5096  5109 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 08:03:08.316  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.318  5096  5109 E SarControlService: no key has been found,reset the power
09-30 08:03:08.318  5096  5134 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 08:03:08.318  5096  5134 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 08:03:08.318  5096  5134 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 08:03:08.319  5122  5122 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:03:08.319  5122  5122 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 08:03:08.320  3514  3514 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 08:03:08.321  5096  5134 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 08:03:08.321  5096  5134 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 08:03:08.321  5096  5134 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 08:03:08.322  5122  5122 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:03:08.322  5122  5122 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 08:03:08.322  5122  5136 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e11cf2b HexData = [00000000ea03000000000000ffffffff]
09-30 08:03:08.322  5122  5136 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 08:03:08.323  5122  5136 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-30 08:03:08.323  5122  5122 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:03:08.323  3514  3514 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-30 08:03:08.323  5096  5106 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 08:03:08.326  5122  5136 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e11cf2b HexData = [00000000eb03000000000000ffffffff]
09-30 08:03:08.326  5122  5136 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:03:08.326  5122  5136 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-30 08:03:08.327  5122  5122 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:03:08.327  5096  5107 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 08:03:08.328  5732  5732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 08:03:08.335   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38b1e12:true
09-30 08:03:08.337  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:03:08.344   506   920 E Netd    : netlink response contains error (No such file or directory)
,09-30 08:03:08.344   506   920 D TetherController: Setting IP forward enable = 0
09-30 08:03:08.345   927  3039 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-30 08:03:08.353   927  3658 I ActivityManager: Start proc 5762:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-30 08:03:08.356  3514  3514 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 08:03:08.365  3514  3514 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-30 08:03:08.364  5732  5732 D LocalBluetoothProfileManager: Adding local MAP profile
,09-30 08:03:08.367  5732  5732 D BluetoothMap: Create BluetoothMap proxy object
,09-30 08:03:08.375  5732  5732 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-30 08:03:08.381  5732  5732 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:03:08.397  5762  5762 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-30 08:03:08.399   927  3912 I ActivityManager: Killing 5060:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-30 08:03:08.469   927  3037 D wifi    : In wifi stop Hal
,09-30 08:03:08.470   927  3037 D wifi    : halHandle = 0x7f6ce08a40, mVM = 0x7f8944d140, mCls = 0x100a02
09-30 08:03:08.470   927  3513 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 08:03:08.470   927  3513 D WifiHAL : Got a signal to exit!!!
,09-30 08:03:08.470   927  3513 I WifiHAL : Exit wifi_event_loop
09-30 08:03:08.471  4508  4508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:03:08.471   927  3037 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 08:03:08.471   927  3037 E WifiHAL : Event processing terminated
09-30 08:03:08.471   927  3037 D wifi    : In wifi cleaned up handler
09-30 08:03:08.471   927  3037 I WifiHAL : Internal cleanup completed
09-30 08:03:08.472  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.472  3782  4256 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:03:08.473  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:08.475  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:08.487  4659  4726 I bt_hci  : shut_down
,09-30 08:03:08.490   927  3513 D wifi    : set interface wlan0 flags (DOWN)
,09-30 08:03:08.491   927  3037 D WifiNative-HAL: HAL event thread stopped successfully
09-30 08:03:08.491  4659  4731 D bt_hwcfg: hw_epilog_process
09-30 08:03:08.491  4659  4731 I bt_vendor: low_power_mode_cb
,09-30 08:03:08.494  4659  4731 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 08:03:08.494  4659  4731 I bt_vendor: epilog_cb
09-30 08:03:08.494  4659  4731 I bt_hci  : epilog_finished_callback
,09-30 08:03:08.496  4659  4726 I bt_hci_h4: hal_close
09-30 08:03:08.497  4659  4726 I bt_userial_vendor: device fd = 54 close
,09-30 08:03:08.606  4659  4723 D bt_stack_manager: event_shut_down_stack finished.
,09-30 08:03:08.606  4659  4722 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 08:03:08.607  4659  4722 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 08:03:08.608  4659  4659 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 08:03:08.608  4659  4659 D BtGatt.GattService: Received stop request...Stopping profile...
,09-30 08:03:08.608  4659  4659 D BtGatt.GattService: stop()
09-30 08:03:08.609  4659  4659 D BtGatt.AdvertiseManager: advertise clients cleared
09-30 08:03:08.610  4659  4659 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:08.610  4659  4659 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:08.610  4659  4659 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:08.610  4659  4659 V BluetoothAdapterState: isBleTurningOff()=true
09-30 08:03:08.610  4659  4722 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 08:03:08.611  4659  4722 D BluetoothAdapterProperties: Setting state to 10
09-30 08:03:08.611  4659  4722 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-30 08:03:08.611  4659  4722 I BluetoothAdapterState: Entering OffState
,09-30 08:03:08.611  5762  5762 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:03:08.611  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 08:03:08.612  5762  5762 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:03:08.612  5762  5762 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:03:08.612  5762  5762 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:03:08.612  5762  5762 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.k.d(PG:583)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:03:08.612  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:03:08.612   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-30 08:03:08.619  4659  4659 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-30 08:03:08.619  4659  4659 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 08:03:08.619  4659  4659 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 08:03:08.621  4659  4723 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-30 08:03:08.626  4659  4659 I art     : System.exit called, status: 0
09-30 08:03:08.626  4659  4659 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-30 08:03:08.642  5762  5762 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:03:08.642  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:03:08.643  5762  5762 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:03:08.643  5762  5762 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:03:08.643  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:03:08.648  5732  5732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 08:03:08.676  5732  5732 D DockEventReceiver: finishStartingService: stopping service
09-30 08:03:08.677   927  3658 I ActivityManager: Killing 5455:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
09-30 08:03:08.694   927   944 D Tethering: InitialState.processMessage what=4
,09-30 08:03:08.709   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 08:03:08.710   927   937 I ActivityManager: Process com.android.bluetooth (pid 4659) has died
,09-30 08:03:08.713  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:03:08.725   927  3912 I ActivityManager: Start proc 5796:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-30 08:03:08.789  5796  5796 D AdapterServiceConfig: Adding HeadsetService
,09-30 08:03:08.789  5796  5796 D AdapterServiceConfig: Adding A2dpService
09-30 08:03:08.789  5796  5796 D AdapterServiceConfig: Adding HidService
09-30 08:03:08.789  5796  5796 D AdapterServiceConfig: Adding HealthService
09-30 08:03:08.789  5796  5796 D AdapterServiceConfig: Adding PanService
,09-30 08:03:08.789  5796  5796 D AdapterServiceConfig: Adding GattService
09-30 08:03:08.790  5796  5796 D AdapterServiceConfig: Adding BluetoothMapService
09-30 08:03:08.790  5796  5796 D AdapterServiceConfig: Adding SapService
09-30 08:03:08.794   927  3215 I ActivityManager: Killing 5467:com.android.chrome/u0a39 (adj 15): empty #17
,09-30 08:03:08.813  4067  4067 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 08:03:08.816  4067  4067 D SystemUpdateService: onCreate
,09-30 08:03:08.819  4067  4067 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 08:03:08.827  4067  4067 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 08:03:08.838  4067  5808 I SystemUpdateService: active receiver: enabled
,09-30 08:03:08.840  4067  5452 I iu.UploadsManager: num queued entries: 0
,09-30 08:03:08.840  4067  5452 I iu.UploadsManager: num updated entries: 0
,09-30 08:03:08.852  4067  4067 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 08:03:08.853  4067  4067 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 08:03:08.856  4067  5808 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-30 08:03:08.841  4067  5452 I iu.SyncManager: NEXT; no task
,09-30 08:03:08.858  4067  5808 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-30 08:03:08.858  4067  5808 I SystemUpdateService: now status is 0 (complete)
09-30 08:03:08.858  4067  5808 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-30 08:03:08.858  4067  5808 I SystemUpdateService: file has been verified
,09-30 08:03:08.859  4067  5808 I SystemUpdateService: OTA package size = 21989297
,09-30 08:03:08.867   927   937 I ActivityManager: Start proc 5810:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-30 08:03:08.878  4067  5808 I SystemUpdateService: showing system update notification
,09-30 08:03:08.900  5810  5810 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-30 08:03:08.903  5810  5810 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:03:08.915  5810  5810 D SprintDMHelper: simOperator: 
,09-30 08:03:08.915  5810  5810 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 08:03:08.927   927  3915 I ActivityManager: Start proc 5822:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-30 08:03:08.929  4067  4067 D SystemUpdateService: onDestroy
,09-30 08:03:08.931   927  3658 I ActivityManager: Killing 5484:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-30 08:03:09.029  4508  5836 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 08:03:09.034   927  3221 I ActivityManager: Start proc 5837:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-30 08:03:09.036   927  3221 I ActivityManager: Killing 5312:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-30 08:03:09.058  5762  5789 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-30 08:03:09.087  5837  5837 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-30 08:03:09.108   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ef2e40:true
,09-30 08:03:09.289   927  3221 I ActivityManager: Killing 4737:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-30 08:03:09.330   927   937 I ActivityManager: Start proc 5851:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-30 08:03:09.361  5851  5851 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-30 08:03:09.368   927  3622 I ActivityManager: Killing 5542:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-30 08:03:13.216   927  3853 D WifiService: setWifiEnabled: true pid=5679, uid=10077
09-30 08:03:13.217   927  3853 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:03:13.225   506   920 D SoftapController: Softap fwReload - Ok
,09-30 08:03:13.230   506   920 D CommandListener: Setting iface cfg
,09-30 08:03:13.231   506   920 D CommandListener: Trying to bring down wlan0
09-30 08:03:13.232   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-30 08:03:13.236   927  3037 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 08:03:13.813   927  3037 D wifi    : set interface wlan0 flags (UP)
09-30 08:03:13.816   927  3037 I WifiHAL : Initializing wifi
09-30 08:03:13.816   927  3037 I WifiHAL : Creating socket
,09-30 08:03:13.817   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 08:03:13.821   927  3037 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-30 08:03:13.821   927  3037 D wifi    : Did set static halHandle = 0x7f6ce08a40
,09-30 08:03:13.822   927  3037 D wifi    : halHandle = 0x7f6ce08a40, mVM = 0x7f8944d140, mCls = 0x198a
09-30 08:03:13.822   927  3037 D wifi    : array field set
09-30 08:03:13.822   927  3037 I WifiNative-HAL: interface[0] = wlan0
09-30 08:03:13.823   927  5869 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547287501376
09-30 08:03:13.824   927  5869 D wifi    : waitForHalEvents called, vm = 0x7f8944d140, obj = 0x198a, env = 0x7f6e205480
,09-30 08:03:13.896  5870  5870 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 08:03:13.909  5870  5870 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 08:03:13.924   927  3037 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 08:03:13.927  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:13.928  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:13.929  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:13.960  5870  5870 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 08:03:13.960  5870  5870 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 08:03:13.975   927  3037 D WifiConfigStore: Loading config and enabling all networks 
,09-30 08:03:13.977  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:13.977  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:13.977  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:13.977  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:13.977  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:13.977  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:13.977  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:13.977  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:13.977  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:13.977  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:13.977  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:13.978  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:03:13.979  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:13.979  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:13.979  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:13.979  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:13.979  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:13.979  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:13.979  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:13.979  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:13.979  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:13.979  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:13.980  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:13.980  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:13.980  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:13.980  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:13.980  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:13.980  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:13.980  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:13.980  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:13.980  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:13.980  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:13.980  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:03:13.990   927  3037 D WifiConfigStore: loaded 0 passpoint configs
09-30 08:03:13.990   927  3037 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 08:03:13.991   927  3037 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 08:03:13.992   927  3037 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 08:03:13.993   927  3037 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 08:03:13.993   927  3037 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 08:03:13.993   927  3037 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-30 08:03:13.993   927  3037 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 08:03:13.996   927  3037 D WifiNative-HAL: Setting external_sim to 1
,09-30 08:03:13.996  4508  4508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 08:03:13.996   927  3037 D wifi    : setting dfs flag to true, 0x7f700148a0
09-30 08:03:13.997   927  3037 D WifiStateMachine: Setting OUI to DA-A1-19
,09-30 08:03:13.997   927  3037 D wifi    : setting scan oui 0x7f700148a0
09-30 08:03:13.997   927  3037 D WifiHAL : Sending mac address OUI
,09-30 08:03:14.001   927  3037 E native  : do suspend false
,09-30 08:03:14.009   927  3037 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-30 08:03:14.009   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 08:03:14.010   927   927 D RttService: SCAN_AVAILABLE : 3
09-30 08:03:14.010   927  3147 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 08:03:14.010   506   920 D CommandListener: Setting iface cfg
,09-30 08:03:14.014   927  3036 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-30 08:03:14.014   927  3036 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 08:03:14.022   927  3036 D WifiNative-HAL: p2pGetDeviceAddress
09-30 08:03:14.022   927  3036 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 08:03:14.026   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267238 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-30 08:03:17.185  5870  5870 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:03:17.190  5870  5870 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:03:17.197  5870  5870 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:03:17.202  5870  5870 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:03:17.273   927  3037 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 08:03:17.274   927  3037 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-30 08:03:17.274   927  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:03:17.289   927  3037 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 08:03:17.327   927  3037 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 08:03:17.329  5870  5870 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 08:03:17.797  5870  5870 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 08:03:17.850  5870  5870 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-30 08:03:17.852  5870  5870 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 08:03:17.864   927  3037 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 08:03:17.865   927  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 08:03:17.865   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 08:03:17.883   927  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:03:17.894   506   920 D CommandListener: Setting iface cfg
,09-30 08:03:17.899   927  3037 D WifiStateMachine: Start Dhcp Watchdog 2
,09-30 08:03:17.905   927  5876 D DhcpClient: Receive thread started
,09-30 08:03:17.910   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 08:03:17.910   927  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 08:03:17.910   927  3039 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-30 08:03:17.997   927  3037 E native  : do suspend false
,09-30 08:03:18.021   927  5875 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 08:03:18.063   927  5876 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-30 08:03:18.065   927  5875 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-30 08:03:18.067   927  5875 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 08:03:18.079   927  5876 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 08:03:18.080   927  5875 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-30 08:03:18.083   506   920 D CommandListener: Setting iface cfg
,09-30 08:03:18.088   927  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 08:03:18.095   927  5875 D DhcpClient: Scheduling renewal in 86399s
,09-30 08:03:18.107   927  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 08:03:18.109   927  3037 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 08:03:18.110   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 08:03:18.111   927  3039 D ConnectivityService: Adding iface wlan0 to network 101
09-30 08:03:18.118   927  3037 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 08:03:18.167   927  3039 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 08:03:18.168   927  3039 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-30 08:03:18.171   927  3039 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-30 08:03:18.173   927  3039 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-30 08:03:18.176   927  3039 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-30 08:03:18.182   927  3039 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 08:03:18.187   927  3039 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-30 08:03:18.187   927  3039 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-30 08:03:18.187   927  3039 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-30 08:03:18.187   927  3039 D ConnectivityService:    accepting network in place of null
09-30 08:03:18.187   927  3037 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 08:03:18.187   927  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 08:03:18.188   927  3039 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 08:03:18.210   927  5874 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271422, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 08:03:18.213   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:03:18.222   927  3221 D WifiService: setWifiEnabled: false pid=5679, uid=10077
,09-30 08:03:18.222   927  3221 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:03:18.225   927  3037 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-30 08:03:18.225   927  3037 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 08:03:18.225   927  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 08:03:18.225   927  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:03:18.232   927  5875 D DhcpClient: Clearing IP address
,09-30 08:03:18.237   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 08:03:18.237   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-30 08:03:18.239   506   920 D CommandListener: Setting iface cfg
,09-30 08:03:18.248   927  3039 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 08:03:18.248   927  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 08:03:18.249  3809  3965 W QCNEJ   : |CORE| network available: 101
09-30 08:03:18.250   927  3039 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-30 08:03:18.251   927   944 D Tethering: MasterInitialState.processMessage what=3
09-30 08:03:18.251  3809  3965 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 08:03:18.253  3809  3965 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 08:03:18.253  3809  3965 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 08:03:18.258   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 08:03:18.258   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-30 08:03:18.258  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.258  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:18.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:18.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:18.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:18.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:18.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:18.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:03:18.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:03:18.258  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:03:18.258  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:18.260  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.260  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:18.260  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:18.260  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:18.260  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:18.260  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:18.260  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:18.260  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:18.260  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:03:18.261  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.261  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:18.261  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:18.261  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:18.261  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:18.261  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:18.261  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:18.261  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:18.261  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:03:18.262   539   539 E Parcel  : Reading a NULL string not supported here.
09-30 08:03:18.265   927  5876 D DhcpClient: Receive thread stopped
,09-30 08:03:18.267   927  3039 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-30 08:03:18.268  3809  3965 W QCNEJ   : |CORE| network lost: 101
09-30 08:03:18.268   927  3037 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-30 08:03:18.269  3809  3965 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 08:03:18.269   927   927 D RttService: SCAN_AVAILABLE : 1
09-30 08:03:18.269   927  3147 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 08:03:18.271  4067  4067 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 08:03:18.272   927  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 08:03:18.275  4067  4067 D SystemUpdateService: onCreate
,09-30 08:03:18.281  4067  4067 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 08:03:18.296   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:03:18.296  4067  5888 I SystemUpdateService: active receiver: enabled
,09-30 08:03:18.298  4067  4067 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 08:03:18.300  4067  4067 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 08:03:18.302  5810  5810 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:03:18.306  5810  5810 D SprintDMHelper: simOperator: 
09-30 08:03:18.306  5810  5810 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 08:03:18.323   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:03:18.323   927  3039 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 08:03:18.323   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-30 08:03:18.323   927  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:03:18.326   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-30 08:03:18.327  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.328  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:18.328  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:18.328  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:18.328  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:18.328  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:18.328  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:18.328  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:18.328  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:18.328  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:03:18.328  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:18.328   927  3037 D DhcpClient: doQuit
09-30 08:03:18.328   927  3037 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 08:03:18.328   927  5875 D DhcpClient: onQuitting
09-30 08:03:18.329  5870  5870 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 08:03:18.329  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.329  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:18.329  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:18.329  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:18.329  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:18.329  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:18.329  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:18.329  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:18.329  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:18.329  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.330  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:03:18.332  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:03:18.333  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:18.333  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:18.333  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:18.333  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:18.333  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:18.333  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:18.333  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:18.333  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:18.333  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.333  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:18.335  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.335  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:18.335  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:18.335  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:18.335  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:18.335  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:18.335  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:18.335  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:18.335  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:18.335  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:18.335  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:03:18.336  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:18.337  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:18.343  4067  4067 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 08:03:18.344  4067  4067 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 08:03:18.346  4067  5888 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 08:03:18.349  5870  5870 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-30 08:03:18.353  5870  5870 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-30 08:03:18.357  4067  5888 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 08:03:18.357  4067  5888 I SystemUpdateService: now status is 0 (complete)
09-30 08:03:18.357  4067  5888 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-30 08:03:18.358  4067  5888 I SystemUpdateService: file has been verified
09-30 08:03:18.358  4067  5888 I SystemUpdateService: OTA package size = 21989297
,09-30 08:03:18.361  4067  4067 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 08:03:18.363  4067  4067 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 08:03:18.365  5810  5810 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-30 08:03:18.369  5810  5810 D SprintDMHelper: simOperator: 
09-30 08:03:18.369  5810  5810 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 08:03:18.381   506   920 E Netd    : netlink response contains error (No such file or directory)
09-30 08:03:18.382   927  3039 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-30 08:03:18.387  4067  5888 I SystemUpdateService: showing system update notification
,09-30 08:03:18.389  5870  5870 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 08:03:18.395  5870  5870 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 08:03:18.406  4067  5902 I SystemUpdateService: active receiver: enabled
,09-30 08:03:18.409  4067  5902 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 08:03:18.411  4067  5902 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-30 08:03:18.411  4067  5902 I SystemUpdateService: now status is 0 (complete)
,09-30 08:03:18.411  4067  5902 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 08:03:18.411  4067  5902 I SystemUpdateService: file has been verified
09-30 08:03:18.411  4067  5902 I SystemUpdateService: OTA package size = 21989297
,09-30 08:03:18.416  4067  5902 I SystemUpdateService: showing system update notification
,09-30 08:03:18.426  4067  4067 D SystemUpdateService: onDestroy
,09-30 08:03:18.497   927  3037 D wifi    : In wifi stop Hal
,09-30 08:03:18.497   927  3037 D wifi    : halHandle = 0x7f6ce08a40, mVM = 0x7f8944d140, mCls = 0x198a
09-30 08:03:18.497   927  5869 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 08:03:18.497   927  5869 D WifiHAL : Got a signal to exit!!!
09-30 08:03:18.497   927  5869 I WifiHAL : Exit wifi_event_loop
09-30 08:03:18.498   927  3037 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 08:03:18.498   927  3037 E WifiHAL : Event processing terminated
09-30 08:03:18.498   927  3037 D wifi    : In wifi cleaned up handler
09-30 08:03:18.498  4508  4508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:03:18.498   927  3037 I WifiHAL : Internal cleanup completed
09-30 08:03:18.500  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:18.501  3782  4256 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:03:18.501  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:18.501  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:18.521   927  5869 D wifi    : set interface wlan0 flags (DOWN)
09-30 08:03:18.521   927  3037 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 08:03:18.728   927   944 D Tethering: InitialState.processMessage what=4
,09-30 08:03:18.736   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 08:03:19.249   927  3039 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-30 08:03:20.199   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:21.200   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:22.201   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:23.202   927  5873 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-30 08:03:23.202   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:23.204   927  3039 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 08:03:23.258   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39b5f8a:true
,09-30 08:03:23.259  5796  5796 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 08:03:23.265  5796  5796 I bt_bluedroid: init
,09-30 08:03:23.266  5796  5903 I BluetoothAdapterState: Entering OffState
,09-30 08:03:23.269  5796  5904 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 08:03:23.270  5796  5904 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 08:03:23.270  5796  5904 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 08:03:23.270  5796  5904 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-30 08:03:23.271  5796  5796 I bt_bluedroid: get_profile_interface socket
,09-30 08:03:23.274  5796  5907 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 08:03:23.275  5796  5796 I bt_bluedroid: get_profile_interface sdp
,09-30 08:03:23.278  5796  5907 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 08:03:23.282  5796  5807 I bt_bluedroid: config_hci_snoop_log
,09-30 08:03:23.283   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 08:03:23.288  5796  5903 D BluetoothAdapterState: Current state: OFF, message: 0
,09-30 08:03:23.288  5796  5903 D BluetoothAdapterProperties: Setting state to 14
09-30 08:03:23.288  5796  5903 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-30 08:03:23.290  5796  5903 D BluetoothBondStateMachine: make
,09-30 08:03:23.293  5796  5908 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 08:03:23.296  5796  5903 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:03:23.297  5796  5796 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 08:03:23.312  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:23.313  5796  5796 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 08:03:23.314  5796  5796 D BtGatt.GattService: Received start request. Starting profile...
,09-30 08:03:23.314  5796  5796 D BtGatt.GattService: start()
09-30 08:03:23.314  5796  5796 I bt_bluedroid: get_profile_interface gatt
,09-30 08:03:23.315  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:23.316  5796  5796 D BtGatt.AdvertiseManager: advertise manager created
,09-30 08:03:23.322  5796  5796 V BluetoothAdapterState: isTurningOff()=false
,09-30 08:03:23.322  5796  5796 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:23.322  5796  5796 V BluetoothAdapterState: isBleTurningOn()=true
,09-30 08:03:23.322  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:23.322  5796  5903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 08:03:23.324  5796  5903 I bt_bluedroid: bt_bluedroid
09-30 08:03:23.324  5796  5904 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-30 08:03:23.325  5796  5904 I bt_hci  : start_up
,09-30 08:03:23.331  5796  5904 I bt_vendor: alloc value 0xf3d38871
,09-30 08:03:23.332  5796  5904 I bt_vendor: init
09-30 08:03:23.332  5796  5904 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 08:03:23.332  5796  5904 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 08:03:23.443  5796  5904 D bt_hci  : start_up starting async portion
,09-30 08:03:23.444  5796  5911 I bt_hci  : event_finish_startup
09-30 08:03:23.444  5796  5911 I bt_hci_h4: hal_open
,09-30 08:03:23.444  5796  5911 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 08:03:23.442  5912  5912 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-30 08:03:23.446  5796  5911 I bt_userial_vendor: device fd = 54 open
,09-30 08:03:23.459  5796  5911 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 08:03:23.461  5796  5911 D bt_hwcfg: Chipset BCM4358A3
,09-30 08:03:23.461  5796  5911 D bt_hwcfg: Target name = [BCM4358A3]
09-30 08:03:23.461  5796  5911 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 08:03:23.841  5796  5911 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 08:03:23.842  5796  5911 D bt_hwcfg: Settlement delay -- 100 ms
,09-30 08:03:23.842  5796  5911 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 08:03:23.975  5796  5911 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 08:03:23.976  5796  5911 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 08:03:23.977  5796  5911 I bt_hwcfg: vendor lib fwcfg completed
09-30 08:03:23.977  5796  5911 I bt_vendor: firmware callback
09-30 08:03:23.977  5796  5911 I bt_hci  : firmware_config_callback
,09-30 08:03:23.986  5796  5914 I bt_btu  : btu_task pending for preload complete event
,09-30 08:03:23.986  5796  5914 I bt_btu_task: Bluetooth chip preload is complete
09-30 08:03:23.986  5796  5914 I bt_btu  : btu_task received preload complete event
,09-30 08:03:23.995  5796  5914 I         : BTE_InitTraceLevels -- TRC_HCI
09-30 08:03:23.995  5796  5914 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 08:03:23.995  5796  5914 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-30 08:03:23.995  5796  5914 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-30 08:03:23.995  5796  5914 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 08:03:23.995  5796  5914 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 08:03:23.995  5796  5914 I         : BTE_InitTraceLevels -- TRC_BNEP
09-30 08:03:23.996  5796  5914 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 08:03:23.996  5796  5914 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 08:03:23.996  5796  5914 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 08:03:23.996  5796  5914 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 08:03:23.996  5796  5914 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 08:03:23.996  5796  5914 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 08:03:23.996  5796  5914 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 08:03:23.996  5796  5914 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 08:03:24.078  5796  5914 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cb6549
,09-30 08:03:24.078  5796  5914 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cb6549 
,09-30 08:03:24.100  5796  5907 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 08:03:24.101  5796  5907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 08:03:24.102  5796  5907 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 08:03:24.104  5796  5907 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 08:03:24.106  5796  5907 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:03:24.106  5796  5907 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 08:03:24.107  5796  5907 D bt_hci  : do_postload posting postload work item
,09-30 08:03:24.107  5796  5911 I bt_hci  : event_postload
09-30 08:03:24.107  5796  5911 I bt_vendor: sco_config_cb
,09-30 08:03:24.107  5796  5911 I bt_hci  : sco_config_callback postload finished.
,09-30 08:03:24.111  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:24.114  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:24.116  5796  5911 I bt_vendor: low_power_mode_cb
09-30 08:03:24.116  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:24.118  5796  5907 D bt_bte_conf: Device ID record 1 : primary
09-30 08:03:24.118  5796  5907 D bt_bte_conf:   vendorId            = 000f
09-30 08:03:24.118  5796  5907 D bt_bte_conf:   vendorIdSource      = 0001
09-30 08:03:24.118  5796  5907 D bt_bte_conf:   product             = 1200
09-30 08:03:24.118  5796  5907 D bt_bte_conf:   version             = 1436
09-30 08:03:24.118  5796  5907 D bt_bte_conf:   clientExecutableURL = 
09-30 08:03:24.118  5796  5907 D bt_bte_conf:   serviceDescription  = 
09-30 08:03:24.118  5796  5907 D bt_bte_conf:   documentationURL    = 
09-30 08:03:24.118  5796  5907 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 08:03:24.118  5796  5904 D bt_stack_manager: event_start_up_stack finished
,09-30 08:03:24.119  5796  5903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-30 08:03:24.119  5796  5903 D BluetoothAdapterProperties: Setting state to 15
09-30 08:03:24.119  5796  5903 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 08:03:24.120  5796  5903 I BluetoothAdapterState: Entering BleOnState
,09-30 08:03:24.124  5796  5903 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 08:03:24.125  5796  5903 D BluetoothAdapterProperties: Setting state to 11
09-30 08:03:24.125  5796  5903 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 08:03:24.130  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:24.132  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:24.132  5796  5796 D HeadsetService: Received start request. Starting profile...
,09-30 08:03:24.134  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:24.134  5796  5796 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 08:03:24.134  5796  5796 D HeadsetStateMachine: make
09-30 08:03:24.136  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:24.144  5796  5903 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:03:24.145  5796  5796 D HeadsetStateMachine: max_hf_connections = 1
09-30 08:03:24.145  5796  5796 I bt_bluedroid: get_profile_interface handsfree
09-30 08:03:24.145  5796  5907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 08:03:24.145  5796  5907 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-30 08:03:24.148  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:24.149  5796  5796 D A2dpService: Received start request. Starting profile...
,09-30 08:03:24.150  5796  5796 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 08:03:24.150  5796  5796 I bt_bluedroid: get_profile_interface avrcp
,09-30 08:03:24.155  5796  5796 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 08:03:24.156  5796  5796 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 08:03:24.156  5796  5796 D A2dpStateMachine: make
09-30 08:03:24.157  5796  5796 I bt_bluedroid: get_profile_interface a2dp
,09-30 08:03:24.157  5796  5907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 08:03:24.162  5796  5922 D A2dpStateMachine: Enter Disconnected: -2
,09-30 08:03:24.163  5796  5796 I BluetoothHidServiceJni: classInitNative: succeeds
09-30 08:03:24.164  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 08:03:24.165  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:24.166  5732  5732 D BluetoothInputDevice: Proxy object connected
,09-30 08:03:24.168  5796  5796 D HidService: Received start request. Starting profile...
09-30 08:03:24.168  5796  5796 I bt_bluedroid: get_profile_interface hidhost
09-30 08:03:24.168  5796  5796 D HidService: setHidService(): set to: null
09-30 08:03:24.168  5796  5907 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c9756d
09-30 08:03:24.168  5796  5907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 08:03:24.168  5796  5796 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 08:03:24.169  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
09-30 08:03:24.170  5796  5796 D HealthService: Received start request. Starting profile...
09-30 08:03:24.170  5732  5732 D HidProfile: Bluetooth service connected
09-30 08:03:24.171  5796  5796 I bt_bluedroid: get_profile_interface health
,09-30 08:03:24.171  5796  5796 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 08:03:24.172  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:24.173  5732  5732 D BluetoothPan: BluetoothPAN Proxy object connected
,09-30 08:03:24.173  5796  5796 D PanService: Received start request. Starting profile...
09-30 08:03:24.174  5796  5796 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 08:03:24.174  5732  5732 D PanProfile: Bluetooth service connected
09-30 08:03:24.174  5796  5796 I bt_bluedroid: get_profile_interface pan
,09-30 08:03:24.177  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:24.178  5732  5732 D BluetoothMap: Proxy object connected
09-30 08:03:24.178  5796  5796 D BluetoothMapService: Received start request. Starting profile...
09-30 08:03:24.178  5796  5796 D BluetoothMapService: start()
09-30 08:03:24.179  5732  5732 D MapProfile: Bluetooth service connected
09-30 08:03:24.179  5732  5732 D BluetoothMap: getConnectedDevices()
09-30 08:03:24.179  5732  5732 D BluetoothMap: Bluetooth is Not enabled
09-30 08:03:24.180  5796  5907 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 08:03:24.181  5796  5796 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-30 08:03:24.182  5796  5796 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-30 08:03:24.182  5796  5796 D BluetoothMapAppObserver: createReceiver()
09-30 08:03:24.183  5796  5796 D BluetoothMapAppObserver: initObservers()
09-30 08:03:24.183  5796  5796 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 08:03:24.189  5796  5796 V SapService: SapBinder()
09-30 08:03:24.189  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:24.190  5796  5796 D SapService: Received start request. Starting profile...
09-30 08:03:24.190  5796  5796 V SapService: start()
,09-30 08:03:24.192  5796  5796 V BluetoothAdapterState: isTurningOff()=false
,09-30 08:03:24.192  5796  5796 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:24.192  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:24.192  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:24.192  5796  5796 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:24.192  5796  5796 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:24.192  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 08:03:24.192  5796  5920 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 08:03:24.192  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:24.193  5796  5796 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:24.193  5796  5796 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:24.193  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:24.193  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:24.193  5796  5796 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:24.193  5796  5796 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:24.193  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:24.193  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:03:24.194  5796  5796 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:24.194  5796  5796 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:24.194  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:24.194  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:24.194  5796  5796 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:24.194  5796  5796 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:24.194  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:24.194  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:03:24.195  5796  5796 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:24.195  5796  5796 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:24.195  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:24.195  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:03:24.196  5796  5903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-30 08:03:24.196  5796  5903 D BluetoothAdapterProperties: ScanMode =  20
09-30 08:03:24.196  5796  5903 D BluetoothAdapterProperties: State =  11
09-30 08:03:24.197  5796  5903 D BluetoothAdapterProperties: Setting state to 12
09-30 08:03:24.197  5796  5903 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 08:03:24.197  5796  5903 I BluetoothAdapterState: Entering OnState
09-30 08:03:24.198  3182  3193 D BluetoothPan: onBluetoothStateChange on: true
09-30 08:03:24.198  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-30 08:03:24.198  5796  5907 D BluetoothAdapterProperties: Scan Mode:21
,09-30 08:03:24.198  5796  5907 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 08:03:24.200   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:24.200  3182  3182 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 08:03:24.200  3182  3182 D PanProfile: Bluetooth service connected
,09-30 08:03:24.200  5732  5744 D BluetoothPbap: onBluetoothStateChange: up=true
,09-30 08:03:24.201   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:24.202  5732  5743 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 08:03:24.202  3182  3197 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 08:03:24.203  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:24.203  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:24.203  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:24.203  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:24.203  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:24.203  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:24.203  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:24.203  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:24.203   541   541 I ServiceManager: Waiting for service AtCmdFwd...
09-30 08:03:24.203  3182  3182 D BluetoothInputDevice: Proxy object connected
09-30 08:03:24.204  3182  3182 D HidProfile: Bluetooth service connected
09-30 08:03:24.204  3857  3887 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:24.204  3182  4033 D BluetoothMap: onBluetoothStateChange: up=true
,09-30 08:03:24.205  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:24.206  3182  3193 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:24.206  3182  3182 D BluetoothMap: Proxy object connected
09-30 08:03:24.206  3182  3182 D MapProfile: Bluetooth service connected
09-30 08:03:24.206  3182  3182 D BluetoothMap: getConnectedDevices()
09-30 08:03:24.206  3182  4033 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 08:03:24.208  5732  5744 D BluetoothMap: onBluetoothStateChange: up=true
09-30 08:03:24.208   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 08:03:24.208  5796  5796 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 08:03:24.209  5796  5796 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 08:03:24.209  3182  3197 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 08:03:24.209  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:24.209  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:24.209  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:24.209  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:24.209  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:24.209  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:24.209  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:24.209  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:03:24.210  5796  5796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:03:24.210   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:24.211  5732  5743 D BluetoothPan: onBluetoothStateChange on: true
09-30 08:03:24.212  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:03:24.213   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 08:03:24.213  5796  5796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:03:24.215  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:24.215  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:24.215  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:24.215  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:24.215  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:24.215  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:24.215  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:24.215  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:24.216  5796  5796 D ObexServerSockets: Succeed to create listening sockets 
,09-30 08:03:24.216  5796  5796 D ObexServerSockets0: startAccept()
09-30 08:03:24.216  5796  5796 D ObexServerSockets0: prepareForNewConnect()
09-30 08:03:24.217  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:24.217  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 08:03:24.218  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:24.219  5796  5929 D ObexServerSockets0: Accepting socket connection...
09-30 08:03:24.219  5732  5732 D LocalBluetoothProfileManager: Adding local A2DP profile
09-30 08:03:24.218  5796  5796 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 08:03:24.219  5796  5796 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 08:03:24.219  5796  5930 D ObexServerSockets0: Accepting socket connection...
,09-30 08:03:24.220  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:24.220   927   927 D BluetoothA2dp: Proxy object connected
09-30 08:03:24.221  5796  5796 D BluetoothMapService: onReceive
09-30 08:03:24.221  5796  5796 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 08:03:24.221  5796  5796 D BluetoothMapService: STATE_ON
09-30 08:03:24.222  3182  3182 D BluetoothA2dp: Proxy object connected
09-30 08:03:24.222  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:24.222  5732  5732 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-30 08:03:24.224  5796  5931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:03:24.225  5796  5931 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-30 08:03:24.225  5796  5931 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-30 08:03:24.230  5732  5732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 08:03:24.232  5732  5732 D BluetoothA2dp: Proxy object connected
,09-30 08:03:24.235  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 08:03:24.237  5732  5732 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:03:24.242  5732  5732 D BluetoothPbap: Proxy object connected
,09-30 08:03:24.243  5732  5732 D PbapServerProfile: Bluetooth service connected
,09-30 08:03:24.248  5796  5796 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 08:03:24.248  5796  5796 D ObexServerSockets0: prepareForNewConnect()
09-30 08:03:24.249  3182  3182 D BluetoothPbap: Proxy object connected
09-30 08:03:24.249  3182  3182 D PbapServerProfile: Bluetooth service connected
,09-30 08:03:24.252  5796  5935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:03:24.265  5796  5939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:03:24.266  5796  5939 I BtOppRfcommListener: Accept thread started.
,09-30 08:03:24.302  3182  3197 D BluetoothHeadset: Proxy object connected
,09-30 08:03:24.302  3182  3182 D HeadsetProfile: Bluetooth service connected
09-30 08:03:24.302  3857  4120 D BluetoothHeadset: Proxy object connected
09-30 08:03:24.302   927   927 D BluetoothHeadset: Proxy object connected
09-30 08:03:24.302   927   927 D BluetoothHeadset: Proxy object connected
09-30 08:03:24.302   927   927 D BluetoothHeadset: Proxy object connected
09-30 08:03:24.304  3857  3890 D BluetoothHeadset: Proxy object connected
,09-30 08:03:24.307  3182  3193 D BluetoothHeadset: Proxy object connected
,09-30 08:03:24.307  3182  3182 D HeadsetProfile: Bluetooth service connected
,09-30 08:03:24.310   927   944 D BluetoothHeadset: Proxy object connected
,09-30 08:03:24.325  5732  5744 D BluetoothHeadset: Proxy object connected
,09-30 08:03:24.327  5732  5732 D HeadsetProfile: Bluetooth service connected
,09-30 08:03:25.203   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 08:03:26.190   927  3039 D ConnectivityService: handlePromptUnvalidated 101
,09-30 08:03:28.239  5796  5903 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 08:03:28.240  5796  5903 D BluetoothAdapterProperties: Setting state to 13
09-30 08:03:28.240  5796  5903 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 08:03:28.241  5796  5903 D BluetoothAdapterProperties: onBluetoothDisable()
,09-30 08:03:28.243  5796  5903 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:03:28.247  5796  5796 D BluetoothMapService: onReceive
,09-30 08:03:28.247  5796  5796 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 08:03:28.247  5796  5796 D BluetoothMapService: STATE_TURNING_OFF
09-30 08:03:28.249  5796  5907 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:03:28.249  5796  5903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-30 08:03:28.250  5796  5796 D BluetoothMapService: MAP Service closeService in
09-30 08:03:28.251  5796  5796 D BluetoothMapMasInstance0: MAP Service shutdown
,09-30 08:03:28.251  5796  5796 D ObexServerSockets0: shutdown(block = true)
09-30 08:03:28.252  5796  5796 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-30 08:03:28.254  5796  5930 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 08:03:28.253  5796  5929 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-30 08:03:28.256  5796  5796 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 08:03:28.257  5796  5916 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 08:03:28.258  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:28.258  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:28.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:28.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:28.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:28.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:28.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:28.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:28.258  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:03:28.259  5796  5796 I BtOppRfcommListener: stopping Accept Thread
,09-30 08:03:28.259  5796  5939 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 08:03:28.259  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:28.259  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:03:28.260  5796  5939 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 08:03:28.262  5796  5796 D HeadsetService: Received stop request...Stopping profile...
09-30 08:03:28.263  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:28.263  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:28.263  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:28.263  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:28.263  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:28.263  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:28.263  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:28.263  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:28.263  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:28.263  3182  4033 D BluetoothHeadset: Proxy object disconnected
,09-30 08:03:28.264  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:28.264  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:28.264  3857  3887 D BluetoothHeadset: Proxy object disconnected
,09-30 08:03:28.264  5796  5796 D A2dpService: Received stop request...Stopping profile...
09-30 08:03:28.265  5796  5922 D A2dpStateMachine: Exit Disconnected: -1
,09-30 08:03:28.265   927   927 D BluetoothHeadset: Proxy object disconnected
,09-30 08:03:28.265   927   927 D BluetoothHeadset: Proxy object disconnected
,09-30 08:03:28.265   927   927 D BluetoothHeadset: Proxy object disconnected
09-30 08:03:28.265  5732  5743 D BluetoothHeadset: Proxy object disconnected
09-30 08:03:28.267   927   927 D BluetoothA2dp: Proxy object disconnected
09-30 08:03:28.267  5732  5732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 08:03:28.268  5796  5796 D HidService: Received stop request...Stopping profile...
09-30 08:03:28.268  5796  5796 D HidService: Stopping Bluetooth HidService
09-30 08:03:28.269  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:28.270  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:28.270  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:28.270  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:28.270  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:28.270  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:03:28.270  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:28.270  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:28.270  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:28.270  5732  5732 D HeadsetProfile: Bluetooth service disconnected
09-30 08:03:28.270  5732  5732 D BluetoothA2dp: Proxy object disconnected
09-30 08:03:28.270  5679  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:03:28.270  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:28.272  3182  3182 D HeadsetProfile: Bluetooth service disconnected
09-30 08:03:28.272  3182  3182 D BluetoothA2dp: Proxy object disconnected
09-30 08:03:28.273  3182  3182 D BluetoothInputDevice: Proxy object disconnected
09-30 08:03:28.273  3182  3182 D HidProfile: Bluetooth service disconnected
09-30 08:03:28.274  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:28.275  5796  5796 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:28.275  5796  5796 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:28.276  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:28.276  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:28.276  5732  5732 D DockEventReceiver: finishStartingService: stopping service
09-30 08:03:28.276  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:28.277  5732  5732 D BluetoothInputDevice: Proxy object disconnected
09-30 08:03:28.277  5732  5732 D HidProfile: Bluetooth service disconnected
09-30 08:03:28.277  5796  5796 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-30 08:03:28.278  5796  5796 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 08:03:28.278  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:28.278  5796  5796 D HealthService: Received stop request...Stopping profile...
09-30 08:03:28.279  5796  5796 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:28.279  5796  5796 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:28.279  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:28.279  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:28.280  5796  5907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 08:03:28.280  5796  5914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:28.280  5796  5914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:28.280  5796  5914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:28.280  5796  5796 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:28.280  5796  5796 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:28.280  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:28.280  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:28.281  5796  5907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 08:03:28.281  5796  5914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:28.281  5796  5907 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 08:03:28.281  5796  5914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:28.281  5796  5914 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 08:03:28.281  5796  5914 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 08:03:28.281  5796  5914 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 08:03:28.281  5796  5914 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-30 08:03:28.284  5796  5796 D PanService: Received stop request...Stopping profile...
,09-30 08:03:28.285  5732  5732 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-30 08:03:28.285  5732  5732 D PanProfile: Bluetooth service disconnected
09-30 08:03:28.285  3182  3182 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 08:03:28.285  3182  3182 D PanProfile: Bluetooth service disconnected
09-30 08:03:28.289  5796  5796 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 08:03:28.289  5796  5796 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 08:03:28.289  5796  5907 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 08:03:28.290  5796  5796 D BluetoothMapService: Received stop request...Stopping profile...
09-30 08:03:28.290  5796  5796 D BluetoothMapService: stop()
09-30 08:03:28.291  5796  5796 D BluetoothMapAppObserver: deinitObservers()
09-30 08:03:28.291  5796  5796 D BluetoothMapAppObserver: removeReceiver()
09-30 08:03:28.292  3182  3182 D BluetoothMap: Proxy object disconnected
,09-30 08:03:28.292  5732  5732 D BluetoothMap: Proxy object disconnected
09-30 08:03:28.292  3182  3182 D MapProfile: Bluetooth service disconnected
09-30 08:03:28.292  5732  5732 D MapProfile: Bluetooth service disconnected
09-30 08:03:28.294  5796  5796 D SapService: Received stop request...Stopping profile...
09-30 08:03:28.294  5796  5796 V SapService: stop()
,09-30 08:03:28.295  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:03:28.295  5796  5796 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:28.296  5796  5796 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:28.296  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:28.296  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:28.296  5796  5796 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 08:03:28.296  5796  5907 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 08:03:28.296  5796  5796 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-30 08:03:28.296  5796  5796 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:28.296  5796  5796 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:28.296  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:28.297  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:28.297  5796  5796 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 08:03:28.297  5796  5796 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-30 08:03:28.298  5796  5796 D BluetoothMapService: MAP Service closeService in
,09-30 08:03:28.298  5796  5796 V BluetoothAdapterState: isTurningOff()=true
,09-30 08:03:28.299  5796  5796 V BluetoothAdapterState: isTurningOn()=false
,09-30 08:03:28.299  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:28.299  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:28.299  5796  5796 D BluetoothMapService: cleanup()
09-30 08:03:28.299  5796  5796 D BluetoothMapService: MAP Service closeService in
09-30 08:03:28.300  3182  3182 D BluetoothPbap: Proxy object disconnected
09-30 08:03:28.300  3182  3182 D PbapServerProfile: Bluetooth service disconnected
09-30 08:03:28.301  5796  5796 V BluetoothAdapterState: isTurningOff()=true
09-30 08:03:28.302  5796  5796 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:28.302  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:28.303  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:03:28.303  5796  5903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 08:03:28.303  5796  5903 D BluetoothAdapterProperties: Setting state to 15
09-30 08:03:28.303  5796  5903 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 08:03:28.303  5732  5732 D BluetoothPbap: Proxy object disconnected
09-30 08:03:28.303  5732  5732 D PbapServerProfile: Bluetooth service disconnected
09-30 08:03:28.304  5796  5903 I BluetoothAdapterState: Entering BleOnState
09-30 08:03:28.305  3182  4033 D BluetoothPan: onBluetoothStateChange on: false
09-30 08:03:28.306   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 08:03:28.306  5732  5744 D BluetoothPbap: onBluetoothStateChange: up=false
,09-30 08:03:28.307   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:03:28.307  5732  5743 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 08:03:28.309  3182  3197 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 08:03:28.309  3857  4120 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 08:03:28.310  3182  3193 D BluetoothMap: onBluetoothStateChange: up=false
,09-30 08:03:28.310  3182  4033 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:03:28.310  3182  3197 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 08:03:28.311  5732  5744 D BluetoothMap: onBluetoothStateChange: up=false
09-30 08:03:28.311  5732  5743 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:03:28.312   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:03:28.312  3182  3193 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:03:28.312   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:03:28.312  5732  5744 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:03:28.313  5732  5743 D BluetoothPan: onBluetoothStateChange on: false
09-30 08:03:28.313  5796  5903 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 08:03:28.314  5796  5903 D BluetoothAdapterProperties: Setting state to 16
09-30 08:03:28.314  5796  5903 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 08:03:28.314  5796  5903 D BluetoothAdapterProperties: onBleDisable
09-30 08:03:28.314  5796  5903 I BluetoothAdapterState: Entering PendingCommandState
09-30 08:03:28.314  5796  5904 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 08:03:28.316  5796  5914 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 08:03:28.316  5796  5914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:03:28.316  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:28.318  5732  5732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 08:03:28.319  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:28.320  5796  5907 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:03:28.320  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:28.322  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:28.325  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:28.325  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:03:28.326  5732  5732 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:03:28.327  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:28.531  5796  5907 I bt_hci  : shut_down
,09-30 08:03:28.535  5796  5911 D bt_hwcfg: hw_epilog_process
,09-30 08:03:28.536  5796  5911 I bt_vendor: low_power_mode_cb
,09-30 08:03:28.538  5796  5911 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 08:03:28.538  5796  5911 I bt_vendor: epilog_cb
09-30 08:03:28.538  5796  5911 I bt_hci  : epilog_finished_callback
,09-30 08:03:28.540  5796  5907 I bt_hci_h4: hal_close
,09-30 08:03:28.540  5796  5907 I bt_userial_vendor: device fd = 54 close
,09-30 08:03:28.653  5796  5904 D bt_stack_manager: event_shut_down_stack finished.
,09-30 08:03:28.653  5796  5903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 08:03:28.658  5796  5796 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 08:03:28.658  5796  5903 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 08:03:28.658  5796  5796 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 08:03:28.658  5796  5796 D BtGatt.GattService: stop()
09-30 08:03:28.658  5796  5796 D BtGatt.AdvertiseManager: advertise clients cleared
,09-30 08:03:28.660  5796  5796 V BluetoothAdapterState: isTurningOff()=false
,09-30 08:03:28.660  5796  5796 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:28.660  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:28.660  5796  5796 V BluetoothAdapterState: isBleTurningOff()=true
09-30 08:03:28.661  5796  5903 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 08:03:28.661  5796  5903 D BluetoothAdapterProperties: Setting state to 10
09-30 08:03:28.661  5796  5903 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 08:03:28.662  5796  5903 I BluetoothAdapterState: Entering OffState
,09-30 08:03:28.663   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-30 08:03:28.671  5796  5796 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 08:03:28.671  5796  5796 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 08:03:28.671  5796  5796 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-30 08:03:28.672  5796  5904 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 08:03:28.677  5796  5796 I art     : System.exit called, status: 0
,09-30 08:03:28.678  5796  5796 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 08:03:28.701   927  3912 I ActivityManager: Process com.android.bluetooth (pid 5796) has died
,09-30 08:03:33.238  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:03:33.238  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:03:33.242  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:03:33.243  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ec9c2c removed from the list
,09-30 08:03:33.243  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:03:33.243  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:33.243  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:03:33.246  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:03:33.246  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb29c8a added. We now have 4 listener(s)
09-30 08:03:33.246  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:03:33.248  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:33.248  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb29c8a removed from the list
,09-30 08:03:33.248  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:03:33.248  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:33.249  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:33.250  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:03:33.250  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7ae2fb added. We now have 4 listener(s)
09-30 08:03:33.251  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:03:38.261  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:38.300   927   944 I ActivityManager: Start proc 5947:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 08:03:38.395  5947  5947 D AdapterServiceConfig: Adding HeadsetService
,09-30 08:03:38.396  5947  5947 D AdapterServiceConfig: Adding A2dpService
09-30 08:03:38.396  5947  5947 D AdapterServiceConfig: Adding HidService
09-30 08:03:38.396  5947  5947 D AdapterServiceConfig: Adding HealthService
09-30 08:03:38.396  5947  5947 D AdapterServiceConfig: Adding PanService
,09-30 08:03:38.396  5947  5947 D AdapterServiceConfig: Adding GattService
09-30 08:03:38.396  5947  5947 D AdapterServiceConfig: Adding BluetoothMapService
09-30 08:03:38.396  5947  5947 D AdapterServiceConfig: Adding SapService
,09-30 08:03:38.409   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fcced8:true
09-30 08:03:38.410  5947  5947 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 08:03:38.414  5947  5947 I bt_bluedroid: init
09-30 08:03:38.414  5947  5959 I BluetoothAdapterState: Entering OffState
,09-30 08:03:38.417  5947  5960 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-30 08:03:38.417  5947  5960 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 08:03:38.417  5947  5960 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 08:03:38.417  5947  5960 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 08:03:38.418  5947  5947 I bt_bluedroid: get_profile_interface socket
,09-30 08:03:38.419  5947  5963 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-30 08:03:38.420  5947  5947 I bt_bluedroid: get_profile_interface sdp
,09-30 08:03:38.421  5947  5963 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 08:03:38.424  5947  5958 I bt_bluedroid: config_hci_snoop_log
,09-30 08:03:38.425   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 08:03:38.429  5947  5959 D BluetoothAdapterState: Current state: OFF, message: 0
09-30 08:03:38.429  5947  5959 D BluetoothAdapterProperties: Setting state to 14
09-30 08:03:38.429  5947  5959 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 08:03:38.431  5947  5959 D BluetoothBondStateMachine: make
,09-30 08:03:38.433  5947  5964 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 08:03:38.436  5947  5959 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:03:38.438  5947  5947 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-30 08:03:38.440  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:38.440  5947  5947 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 08:03:38.441  5947  5947 D BtGatt.GattService: Received start request. Starting profile...
09-30 08:03:38.441  5947  5947 D BtGatt.GattService: start()
09-30 08:03:38.441  5947  5947 I bt_bluedroid: get_profile_interface gatt
,09-30 08:03:38.442  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:38.442  5947  5947 D BtGatt.AdvertiseManager: advertise manager created
,09-30 08:03:38.447  5947  5947 V BluetoothAdapterState: isTurningOff()=false
,09-30 08:03:38.447  5947  5947 V BluetoothAdapterState: isTurningOn()=false
09-30 08:03:38.447  5947  5947 V BluetoothAdapterState: isBleTurningOn()=true
09-30 08:03:38.447  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:38.447  5947  5959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 08:03:38.448  5947  5959 I bt_bluedroid: bt_bluedroid
,09-30 08:03:38.449  5947  5960 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 08:03:38.449  5947  5960 I bt_hci  : start_up
,09-30 08:03:38.454  5947  5960 I bt_vendor: alloc value 0xf3d88871
09-30 08:03:38.454  5947  5960 I bt_vendor: init
09-30 08:03:38.454  5947  5960 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 08:03:38.454  5947  5960 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 08:03:38.565  5947  5960 D bt_hci  : start_up starting async portion
09-30 08:03:38.565  5947  5967 I bt_hci  : event_finish_startup
09-30 08:03:38.566  5947  5967 I bt_hci_h4: hal_open
,09-30 08:03:38.566  5947  5967 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-30 08:03:38.562  5968  5968 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:03:38.569  5947  5967 I bt_userial_vendor: device fd = 54 open
,09-30 08:03:38.584  5947  5967 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 08:03:38.588  5947  5967 D bt_hwcfg: Chipset BCM4358A3
,09-30 08:03:38.588  5947  5967 D bt_hwcfg: Target name = [BCM4358A3]
09-30 08:03:38.589  5947  5967 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 08:03:39.113  5947  5967 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 08:03:39.114  5947  5967 D bt_hwcfg: Settlement delay -- 100 ms
09-30 08:03:39.114  5947  5967 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 08:03:39.247  5947  5967 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 08:03:39.248  5947  5967 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-30 08:03:39.249  5947  5967 I bt_hwcfg: vendor lib fwcfg completed
,09-30 08:03:39.250  5947  5967 I bt_vendor: firmware callback
09-30 08:03:39.250  5947  5967 I bt_hci  : firmware_config_callback
,09-30 08:03:39.260  5947  5970 I bt_btu  : btu_task pending for preload complete event
09-30 08:03:39.260  5947  5970 I bt_btu_task: Bluetooth chip preload is complete
09-30 08:03:39.260  5947  5970 I bt_btu  : btu_task received preload complete event
,09-30 08:03:39.267  5947  5970 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 08:03:39.267  5947  5970 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 08:03:39.268  5947  5970 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 08:03:39.268  5947  5970 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 08:03:39.268  5947  5970 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-30 08:03:39.268  5947  5970 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 08:03:39.268  5947  5970 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 08:03:39.268  5947  5970 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 08:03:39.269  5947  5970 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 08:03:39.269  5947  5970 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 08:03:39.269  5947  5970 I         : BTE_InitTraceLevels -- TRC_SDP
,09-30 08:03:39.269  5947  5970 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 08:03:39.269  5947  5970 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 08:03:39.269  5947  5970 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 08:03:39.269  5947  5970 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 08:03:39.364  5947  5970 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d06549
09-30 08:03:39.364  5947  5970 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d06549 
,09-30 08:03:39.379  5947  5963 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 08:03:39.382  5947  5963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 08:03:39.382  5947  5963 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-30 08:03:39.385  5947  5963 D BluetoothAdapterProperties: Name is: Nexus 6P
09-30 08:03:39.387  5947  5963 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:03:39.387  5947  5963 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 08:03:39.387  5947  5963 D bt_hci  : do_postload posting postload work item
09-30 08:03:39.388  5947  5967 I bt_hci  : event_postload
09-30 08:03:39.388  5947  5967 I bt_vendor: sco_config_cb
09-30 08:03:39.388  5947  5967 I bt_hci  : sco_config_callback postload finished.
,09-30 08:03:39.393  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:39.394  5947  5963 D bt_bte_conf: Device ID record 1 : primary
09-30 08:03:39.394  5947  5963 D bt_bte_conf:   vendorId            = 000f
09-30 08:03:39.394  5947  5963 D bt_bte_conf:   vendorIdSource      = 0001
09-30 08:03:39.394  5947  5963 D bt_bte_conf:   product             = 1200
09-30 08:03:39.394  5947  5963 D bt_bte_conf:   version             = 1436
09-30 08:03:39.394  5947  5963 D bt_bte_conf:   clientExecutableURL = 
09-30 08:03:39.394  5947  5963 D bt_bte_conf:   serviceDescription  = 
,09-30 08:03:39.394  5947  5963 D bt_bte_conf:   documentationURL    = 
09-30 08:03:39.394  5947  5963 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 08:03:39.395  5947  5960 D bt_stack_manager: event_start_up_stack finished
09-30 08:03:39.395  5947  5959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 08:03:39.396  5947  5959 D BluetoothAdapterProperties: Setting state to 15
09-30 08:03:39.396  5947  5959 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 08:03:39.397  5947  5959 I BluetoothAdapterState: Entering BleOnState
09-30 08:03:39.400  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:39.401  5947  5967 I bt_vendor: low_power_mode_cb
09-30 08:03:39.402  5947  5959 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 08:03:39.403  5947  5959 D BluetoothAdapterProperties: Setting state to 11
09-30 08:03:39.403  5947  5959 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 08:03:39.409  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:39.412  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:39.413  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:39.413  5947  5947 D HeadsetService: Received start request. Starting profile...
,09-30 08:03:39.416  5947  5947 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 08:03:39.416  5947  5947 D HeadsetStateMachine: make
,09-30 08:03:39.428  5947  5959 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:03:39.433  5947  5947 D HeadsetStateMachine: max_hf_connections = 1
09-30 08:03:39.433  5947  5947 I bt_bluedroid: get_profile_interface handsfree
,09-30 08:03:39.433  5947  5963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 08:03:39.433  5947  5963 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-30 08:03:39.439  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:39.440  5947  5947 D A2dpService: Received start request. Starting profile...
09-30 08:03:39.440  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:03:39.440  5947  5947 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 08:03:39.441  5947  5947 I bt_bluedroid: get_profile_interface avrcp
,09-30 08:03:39.447  5947  5947 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 08:03:39.448  5947  5947 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 08:03:39.448  5947  5947 D A2dpStateMachine: make
,09-30 08:03:39.449  5947  5947 I bt_bluedroid: get_profile_interface a2dp
,09-30 08:03:39.450  5947  5963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 08:03:39.452  5947  5978 D A2dpStateMachine: Enter Disconnected: -2
09-30 08:03:39.453  5947  5947 I BluetoothHidServiceJni: classInitNative: succeeds
,09-30 08:03:39.453  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
09-30 08:03:39.454  5947  5947 D HidService: Received start request. Starting profile...
,09-30 08:03:39.454  5947  5947 I bt_bluedroid: get_profile_interface hidhost
09-30 08:03:39.455  5947  5963 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ce756d
09-30 08:03:39.455  5947  5947 D HidService: setHidService(): set to: null
,09-30 08:03:39.455  5947  5963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 08:03:39.455  5947  5947 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 08:03:39.456  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
09-30 08:03:39.456  5947  5947 D HealthService: Received start request. Starting profile...
,09-30 08:03:39.458  5947  5947 I bt_bluedroid: get_profile_interface health
,09-30 08:03:39.459  5947  5947 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 08:03:39.459  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
09-30 08:03:39.460  5947  5947 D PanService: Received start request. Starting profile...
09-30 08:03:39.460  5947  5947 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 08:03:39.460  5947  5947 I bt_bluedroid: get_profile_interface pan
09-30 08:03:39.461  5947  5963 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-30 08:03:39.462  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:39.463  5947  5947 D BluetoothMapService: Received start request. Starting profile...
09-30 08:03:39.463  5947  5947 D BluetoothMapService: start()
09-30 08:03:39.466  5947  5947 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 08:03:39.467  5947  5947 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 08:03:39.467  5947  5947 D BluetoothMapAppObserver: createReceiver()
09-30 08:03:39.469  5947  5947 D BluetoothMapAppObserver: initObservers()
09-30 08:03:39.469  5947  5947 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 08:03:39.476  5947  5947 V SapService: SapBinder()
,09-30 08:03:39.476  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:03:39.476  5947  5947 D SapService: Received start request. Starting profile...
09-30 08:03:39.476  5947  5947 V SapService: start()
,09-30 08:03:39.478  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:39.479  5947  5976 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isTurningOff()=false
,09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:39.479  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-30 08:03:39.480  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:03:39.481  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:03:39.481  5947  5959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 08:03:39.481  5947  5959 D BluetoothAdapterProperties: ScanMode =  20
09-30 08:03:39.481  5947  5959 D BluetoothAdapterProperties: State =  11
09-30 08:03:39.481  5947  5959 D BluetoothAdapterProperties: Setting state to 12
,09-30 08:03:39.481  5947  5959 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 08:03:39.482  5947  5959 I BluetoothAdapterState: Entering OnState
09-30 08:03:39.482  3182  3197 D BluetoothPan: onBluetoothStateChange on: true
,09-30 08:03:39.486  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 08:03:39.486  5947  5963 D BluetoothAdapterProperties: Scan Mode:21
09-30 08:03:39.486  5947  5963 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 08:03:39.487   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:39.487  5732  5743 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 08:03:39.487  3182  3182 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 08:03:39.488  3182  3182 D PanProfile: Bluetooth service connected
,09-30 08:03:39.490   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 08:03:39.491  5732  5744 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 08:03:39.493  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:39.493  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:39.493  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:39.493  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:39.493  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:39.493  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:39.493  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:39.493  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:39.493  3182  4033 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 08:03:39.494  5947  5947 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 08:03:39.495  5947  5947 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 08:03:39.495  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:39.495  3857  3890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:39.496  3182  3193 D BluetoothMap: onBluetoothStateChange: up=true
09-30 08:03:39.497  5947  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:03:39.497  3182  4033 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:39.498  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:39.498  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:39.498  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:39.498  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:39.498  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:39.498  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:39.498  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:39.498  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:39.498  3182  3197 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 08:03:39.499  5947  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:03:39.499  5732  5743 D BluetoothMap: onBluetoothStateChange: up=true
09-30 08:03:39.500  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:03:39.501  5947  5947 D ObexServerSockets: Succeed to create listening sockets 
,09-30 08:03:39.501  5947  5947 D ObexServerSockets0: startAccept()
09-30 08:03:39.501  5947  5947 D ObexServerSockets0: prepareForNewConnect()
09-30 08:03:39.503  5947  5947 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-30 08:03:39.503  5947  5947 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-30 08:03:39.504  5732  5744 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:39.504  5947  5983 D ObexServerSockets0: Accepting socket connection...
09-30 08:03:39.504  5947  5984 D ObexServerSockets0: Accepting socket connection...
09-30 08:03:39.504  3182  3182 D BluetoothInputDevice: Proxy object connected
09-30 08:03:39.505  3182  3182 D HidProfile: Bluetooth service connected
09-30 08:03:39.505   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 08:03:39.505  5732  5732 D BluetoothInputDevice: Proxy object connected
09-30 08:03:39.505  5732  5732 D HidProfile: Bluetooth service connected
09-30 08:03:39.506  3182  3197 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 08:03:39.506   927   927 D BluetoothA2dp: Proxy object connected
09-30 08:03:39.507   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:03:39.507  3182  3182 D BluetoothMap: Proxy object connected
09-30 08:03:39.507  3182  3182 D MapProfile: Bluetooth service connected
09-30 08:03:39.507  3182  3182 D BluetoothMap: getConnectedDevices()
,09-30 08:03:39.507  5732  5743 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 08:03:39.507  5732  5732 D BluetoothMap: Proxy object connected
09-30 08:03:39.507  5732  5732 D MapProfile: Bluetooth service connected
09-30 08:03:39.508  3182  3182 D BluetoothA2dp: Proxy object connected
09-30 08:03:39.509  5732  5744 D BluetoothPan: onBluetoothStateChange on: true
09-30 08:03:39.507  5732  5732 D BluetoothMap: getConnectedDevices()
09-30 08:03:39.511   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,09-30 08:03:39.511  5679  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 08:03:39.512  5947  5947 D BluetoothMapService: onReceive
,09-30 08:03:39.512  5947  5947 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 08:03:39.512  5947  5947 D BluetoothMapService: STATE_ON
09-30 08:03:39.513  5732  5732 D BluetoothA2dp: Proxy object connected
09-30 08:03:39.513  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:39.514  5947  5987 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:03:39.514  5732  5732 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 08:03:39.514  5732  5732 D PanProfile: Bluetooth service connected
09-30 08:03:39.516  5947  5987 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 08:03:39.516  5947  5987 D BluetoothSdpJni: SDP Create record success - handle: 1
09-30 08:03:39.516  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:39.518  5732  5732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 08:03:39.523  5732  5732 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:03:39.529  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:03:39.532  5732  5732 D BluetoothPbap: Proxy object connected
,09-30 08:03:39.532  5732  5732 D PbapServerProfile: Bluetooth service connected
09-30 08:03:39.532  3182  3182 D BluetoothPbap: Proxy object connected
09-30 08:03:39.532  3182  3182 D PbapServerProfile: Bluetooth service connected
09-30 08:03:39.532  5947  5947 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 08:03:39.533  5947  5947 D ObexServerSockets0: prepareForNewConnect()
,09-30 08:03:39.535  5947  5989 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:03:39.552  5947  5995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:03:39.553  5947  5995 I BtOppRfcommListener: Accept thread started.
,09-30 08:03:39.590  3182  4033 D BluetoothHeadset: Proxy object connected
09-30 08:03:39.590  3182  3182 D HeadsetProfile: Bluetooth service connected
,09-30 08:03:39.590  3857  3887 D BluetoothHeadset: Proxy object connected
09-30 08:03:39.590   927   927 D BluetoothHeadset: Proxy object connected
09-30 08:03:39.590   927   927 D BluetoothHeadset: Proxy object connected
09-30 08:03:39.590   927   927 D BluetoothHeadset: Proxy object connected
,09-30 08:03:39.591  5732  5986 D BluetoothHeadset: Proxy object connected
,09-30 08:03:39.591   927   944 D BluetoothHeadset: Proxy object connected
09-30 08:03:39.592  5732  5732 D HeadsetProfile: Bluetooth service connected
,09-30 08:03:39.597  3857  4120 D BluetoothHeadset: Proxy object connected
,09-30 08:03:39.599  3182  3193 D BluetoothHeadset: Proxy object connected
,09-30 08:03:39.599  3182  3182 D HeadsetProfile: Bluetooth service connected
,09-30 08:03:39.604  5732  5743 D BluetoothHeadset: Proxy object connected
,09-30 08:03:39.605  5732  5732 D HeadsetProfile: Bluetooth service connected
,09-30 08:03:39.607   927   944 D BluetoothHeadset: Proxy object connected
,09-30 08:03:43.276  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:43.276  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:43.276  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:43.276  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:03:43.276  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:43.276  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:43.276  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:43.276  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:03:43.282  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:03:43.282  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:43.283  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7ae2fb removed from the list
09-30 08:03:43.283  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:03:43.283  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:43.283  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:03:43.285  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:03:43.285  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d4f18 added. We now have 4 listener(s)
09-30 08:03:43.285  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:03:43.289   927  3735 D WifiService: setWifiEnabled: false pid=5679, uid=10077
,09-30 08:03:43.289   927  3735 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:03:45.205   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:46.206   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:47.208   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:48.209   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:03:48.301  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:48.302   927  3215 D WifiService: setWifiEnabled: true pid=5679, uid=10077
09-30 08:03:48.302   927  3215 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:03:48.310   506   920 D SoftapController: Softap fwReload - Ok
,09-30 08:03:48.316   506   920 D CommandListener: Setting iface cfg
09-30 08:03:48.316   506   920 D CommandListener: Trying to bring down wlan0
09-30 08:03:48.318   506   920 D CommandListener: Clearing all IP addresses on wlan0
,09-30 08:03:48.323   927  3037 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 08:03:49.005   927  3037 D wifi    : set interface wlan0 flags (UP)
,09-30 08:03:49.008   927  3037 I WifiHAL : Initializing wifi
09-30 08:03:49.009   927  3037 I WifiHAL : Creating socket
,09-30 08:03:49.015   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 08:03:49.018   927  3037 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-30 08:03:49.018   927  3037 D wifi    : Did set static halHandle = 0x7f6ce08a40
09-30 08:03:49.018   927  3037 D wifi    : halHandle = 0x7f6ce08a40, mVM = 0x7f8944d140, mCls = 0x10168a
09-30 08:03:49.018   927  3037 D wifi    : array field set
,09-30 08:03:49.018   927  3037 I WifiNative-HAL: interface[0] = wlan0
09-30 08:03:49.020   927  6000 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547287501376
09-30 08:03:49.020   927  6000 D wifi    : waitForHalEvents called, vm = 0x7f8944d140, obj = 0x10168a, env = 0x7f6e206b00
,09-30 08:03:49.086  6001  6001 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 08:03:49.110  6001  6001 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 08:03:49.122   927  3037 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 08:03:49.134  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:03:49.137  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:03:49.143  6001  6001 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 08:03:49.143  6001  6001 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 08:03:49.157   927  3037 D WifiConfigStore: Loading config and enabling all networks 
,09-30 08:03:49.163  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:49.163  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:49.163  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:49.163  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:49.163  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:49.163  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:49.163  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:49.163  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:03:49.167  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:03:49.169  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:49.169  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:49.169  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:49.169  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:49.169  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:49.169  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:03:49.169  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:03:49.169  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:03:49.171  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:03:49.174   927  3037 D WifiConfigStore: loaded 0 passpoint configs
09-30 08:03:49.174   927  3037 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 08:03:49.175   927  3037 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-30 08:03:49.176   927  3037 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 08:03:49.177   927  3037 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 08:03:49.177   927  3037 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 08:03:49.177   927  3037 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 08:03:49.177   927  3037 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 08:03:49.180   927  3037 D WifiNative-HAL: Setting external_sim to 1
,09-30 08:03:49.181  4508  4508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:03:49.181   927  3037 D wifi    : setting dfs flag to true, 0x7f6fd69e20
09-30 08:03:49.181   927  3037 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 08:03:49.182   927  3037 D wifi    : setting scan oui 0x7f6fd69e20
09-30 08:03:49.182   927  3037 D WifiHAL : Sending mac address OUI
,09-30 08:03:49.186   927  3037 E native  : do suspend false
,09-30 08:03:49.194   927  3037 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 08:03:49.195   927   927 D RttService: SCAN_AVAILABLE : 3
09-30 08:03:49.195   927  3147 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-30 08:03:49.195   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-30 08:03:49.196   506   920 D CommandListener: Setting iface cfg
,09-30 08:03:49.200   927  3036 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-30 08:03:49.200   927  3036 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 08:03:49.210   541   541 I ServiceManager: Waiting for service AtCmdFwd...
09-30 08:03:49.211   927  3036 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 08:03:49.217   927  3036 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-30 08:03:49.217   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302429 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-30 08:03:50.211   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 08:03:52.380  6001  6001 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-30 08:03:52.382  6001  6001 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-30 08:03:52.383  6001  6001 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-30 08:03:52.385  6001  6001 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:03:52.433   927  3037 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 08:03:52.434   927  3037 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 08:03:52.434   927  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:03:52.447   927  3037 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 08:03:52.479   927  3037 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 08:03:52.481  6001  6001 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 08:03:52.903  6001  6001 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 08:03:52.940  6001  6001 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 08:03:52.941  6001  6001 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 08:03:52.948   927  3037 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-30 08:03:52.948   927  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:03:52.948   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 08:03:52.967   927  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:03:52.978   506   920 D CommandListener: Setting iface cfg
,09-30 08:03:52.983   927  3037 D WifiStateMachine: Start Dhcp Watchdog 3
,09-30 08:03:52.989   927  6006 D DhcpClient: Receive thread started
,09-30 08:03:52.993   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:03:52.993   927  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 08:03:52.993   927  3039 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-30 08:03:53.074   927  3037 E native  : do suspend false
,09-30 08:03:53.089   927  6005 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 08:03:53.102   927  6006 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-30 08:03:53.103   927  6005 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-30 08:03:53.105   927  6005 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 08:03:53.120   927  6006 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 08:03:53.121   927  6005 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 08:03:53.123   506   920 D CommandListener: Setting iface cfg
09-30 08:03:53.128   927  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 08:03:53.132   927  6005 D DhcpClient: Scheduling renewal in 86399s
,09-30 08:03:53.147   927  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-30 08:03:53.150   927  3037 D WifiConfigStore: No blacklist allowed without epno enabled
,09-30 08:03:53.151   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-30 08:03:53.153   927  3037 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-30 08:03:53.155   927  3039 D ConnectivityService: Adding iface wlan0 to network 102
,09-30 08:03:53.210   927  3039 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-30 08:03:53.210   927  3039 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-30 08:03:53.214   927  3039 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-30 08:03:53.216   927  3039 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-30 08:03:53.217   927  3039 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-30 08:03:53.225   927  3039 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:03:53.230   927  3039 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-30 08:03:53.230   927  3039 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-30 08:03:53.230   927  3039 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-30 08:03:53.230   927  3037 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 08:03:53.230   927  3039 D ConnectivityService:    accepting network in place of null
09-30 08:03:53.230   927  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 08:03:53.231   927  3039 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 08:03:53.244   927  6004 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306456, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 08:03:53.254   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:03:53.276   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:03:53.279   927  3039 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-30 08:03:53.279  3809  3965 W QCNEJ   : |CORE| network available: 102
09-30 08:03:53.279   927  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:03:53.281   927  3039 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-30 08:03:53.282   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-30 08:03:53.283  3809  3965 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 08:03:53.284  3809  3965 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 08:03:53.285  3809  3965 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 08:03:53.289  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:53.289  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:53.289  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:53.289  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:53.289  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:53.289  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:53.289  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:03:53.289  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:03:53.292  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:03:53.297  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:53.297  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:53.297  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:53.297  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:53.297  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:53.297  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:53.297  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:03:53.297  5679  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:03:53.299  5679  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:03:53.301  5096  5109 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-30 08:03:53.301  5096  5109 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 08:03:53.301  5096  5109 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 08:03:53.301  5096  5109 E SarControlService: no key has been found,reset the power
09-30 08:03:53.302  5096  5134 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 08:03:53.302  5096  5134 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 08:03:53.302  5096  5134 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-30 08:03:53.303  5122  5122 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:03:53.303  5122  5122 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 08:03:53.305  5096  5134 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 08:03:53.305  5096  5134 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 08:03:53.306  5096  5134 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 08:03:53.306  4067  4067 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 08:03:53.308  5122  5122 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-30 08:03:53.308  5122  5122 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-30 08:03:53.310  5122  5136 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e11cf2b HexData = [00000000ec03000000000000ffffffff]
09-30 08:03:53.311  5122  5136 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 08:03:53.311  5122  5136 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-30 08:03:53.311  5122  5122 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:03:53.311  5096  5107 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-30 08:03:53.312  4067  4067 D SystemUpdateService: onCreate
,09-30 08:03:53.314  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:03:53.314  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:03:53.314  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:03:53.314  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:03:53.314  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:03:53.314  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:53.314  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:03:53.314  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:03:53.315   927  6003 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-30 08:03:53.316  5122  5136 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e11cf2b HexData = [00000000ed03000000000000ffffffff]
09-30 08:03:53.316  5122  5136 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:03:53.316  5122  5136 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-30 08:03:53.316  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:03:53.316  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:03:53.316  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d4f18 removed from the list
09-30 08:03:53.316  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:03:53.316  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:03:53.316  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:03:53.317  5122  5122 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:03:53.317  5096  5106 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 08:03:53.317  4067  4067 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 08:03:53.320  5679  6017 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-30 08:03:53.320  5679  6017 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 08:03:53.329  4067  4067 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 08:03:53.333  4067  5452 I iu.UploadsManager: num queued entries: 0
09-30 08:03:53.333  4067  5452 I iu.UploadsManager: num updated entries: 0
09-30 08:03:53.334  4067  5452 I iu.SyncManager: NEXT; no task
,09-30 08:03:53.337  4067  6016 I SystemUpdateService: active receiver: enabled
,09-30 08:03:53.339  4067  4067 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 08:03:53.340  4067  4067 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 08:03:53.342  5810  5810 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:03:53.345  5810  5810 D SprintDMHelper: simOperator: 
,09-30 08:03:53.345  5810  5810 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 08:03:53.367   927  6003 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 12:03:53 GMT], X-Android-Received-Millis=[1475237033366], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475237033339]}
,09-30 08:03:53.367   927  3039 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 08:03:53.368   927  3039 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-30 08:03:53.368   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 08:03:53.369   927  3039 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 08:03:53.375  4067  6016 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 08:03:53.382  4067  6016 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 08:03:53.383  4067  6016 I SystemUpdateService: now status is 0 (complete)
09-30 08:03:53.383  4067  6016 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 08:03:53.383  4067  6016 I SystemUpdateService: file has been verified
09-30 08:03:53.383  4067  6016 I SystemUpdateService: OTA package size = 21989297
,09-30 08:03:53.390  4067  6016 I SystemUpdateService: showing system update notification
,09-30 08:03:53.399  4067  4067 D SystemUpdateService: onDestroy
,09-30 08:03:53.476  4508  6022 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 08:03:56.014   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:03:56.332  5679  6029 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-30 08:03:56.332  5679  6017 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-30 08:03:56.333  5679  6017 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-30 08:03:56.333  5679  6029 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 08:03:56.334  5679  6017 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 08:03:56.334  5679  6029 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:03:56.336  5679  6017 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 08:03:56.336  5679  6029 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:03:56.339  5679  6031 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:03:56.339  5679  6031 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:03:56.340  5679  6017 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-30 08:03:56.340  5679  6029 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 08:03:56.344  5679  6032 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:03:56.344  5679  6032 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 08:03:56.344  5679  6033 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:03:56.344  5679  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:03:56.346  5679  6033 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:03:56.346  5679  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:03:56.346  5679  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:03:56.346  5679  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:03:56.347  5679  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:03:56.347  5679  6034 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:03:56.347  5679  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:03:56.347  5679  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:03:56.348  5679  6031 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 152, thread name: OutgoingSocketThread/Sender): Socket closed
,09-30 08:03:56.348  5679  6034 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:03:56.348  5679  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:03:56.348  5679  6034 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:03:56.348  5679  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:03:56.348  5679  6031 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 152, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:03:56.348  5679  6031 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 08:03:56.348  5679  6034 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:03:56.348  5679  6034 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 08:03:56.348  5679  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:03:56.348  5679  6031 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 08:03:56.348  5679  6033 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:03:56.348  5679  6031 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 08:03:56.348  5679  6034 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:03:56.348  5679  6033 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:03:56.349  5679  6034 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:03:56.349  5679  6031 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 152, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:03:56.349  5679  6031 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 08:03:56.349  5679  6033 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 08:03:56.349  5679  6034 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 08:03:56.349  5679  6034 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 08:03:56.349  5679  6034 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:03:56.349  5679  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 08:03:56.349  5679  6033 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:03:56.349  5679  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 08:03:56.351  5679  6032 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 153, thread name: IncomingSocketThread/Sender): Socket closed
09-30 08:03:56.351  5679  6032 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 153, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:03:56.351  5679  6032 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 08:03:56.351  5679  6032 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 08:03:56.351  5679  6032 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 08:03:56.352  5679  6032 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 153, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:03:56.352  5679  6032 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 08:03:59.332  5679  5725 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-30 08:03:59.333  5679  5725 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-30 08:03:59.339  5679  5725 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f7e7bff Bundle[{}]
,09-30 08:03:59.340  5679  5725 I io.jxcore.node.LifeCycleMonitor: start: OK
09-30 08:03:59.340  5679  5725 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-30 08:03:59.341  5679  5725 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-30 08:03:59.341  5679  5725 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-30 08:03:59.342  5679  5725 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-30 08:03:59.343  5679  5725 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-30 08:03:59.350  5679  5725 I System.out: Running OutgoingSocketThread
,09-30 08:03:59.352  5679  6035 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-30 08:03:59.353  5679  6035 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 08:04:01.236   927  3039 D ConnectivityService: handlePromptUnvalidated 102
,09-30 08:04:02.057   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:04:02.364  5679  6036 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-30 08:04:02.365  5679  6035 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-30 08:04:02.365  5679  6036 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 08:04:02.365  5679  6035 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-30 08:04:02.365  5679  6036 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 08:04:02.365  5679  6035 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:04:02.367  5679  6035 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 08:04:02.367  5679  6036 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 08:04:02.370  5679  6038 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:04:02.370  5679  6038 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 08:04:02.371  5679  6035 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-30 08:04:02.372  5679  6036 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 08:04:02.373  5679  6039 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:04:02.373  5679  6039 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:02.374  5679  6040 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:04:02.374  5679  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:02.376  5679  6041 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:04:02.376  5679  6041 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 08:04:02.377  5679  6041 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:04:02.377  5679  6041 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:04:02.377  5679  6041 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:04:02.377  5679  6041 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:04:02.377  5679  6041 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:04:02.377  5679  6041 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:04:02.377  5679  6040 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:04:02.377  5679  6040 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-30 08:04:02.378  5679  6041 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:04:02.378  5679  6040 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:04:02.378  5679  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 08:04:02.378  5679  6041 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:04:02.378  5679  6041 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:04:02.378  5679  6041 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 08:04:02.378  5679  6041 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:04:02.378  5679  6041 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 08:04:02.378  5679  6038 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 164, thread name: IncomingSocketThread/Sender): Socket closed
09-30 08:04:02.379  5679  6038 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 164, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:04:02.379  5679  6038 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 08:04:02.379  5679  6038 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 08:04:02.379  5679  6038 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 08:04:02.379  5679  6038 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:04:02.379  5679  6038 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 08:04:02.379  5679  6039 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 165, thread name: OutgoingSocketThread/Sender): Socket closed
09-30 08:04:02.380  5679  6039 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:04:02.380  5679  6039 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 08:04:02.380  5679  6039 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 08:04:02.380  5679  6039 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 08:04:02.380  5679  6039 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:04:02.380  5679  6039 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 08:04:04.212   927  3037 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-30 08:04:05.086   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:04:05.363  5679  5725 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-30 08:04:05.365  5679  5725 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-30 08:04:05.365  5679  5725 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-30 08:04:05.372  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 08:04:05.372  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a42d71 added. We now have 3 listener(s)
,09-30 08:04:05.375  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 08:04:05.376  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.376  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:04:05.376  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:04:05.376  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325f756 added. We now have 4 listener(s)
09-30 08:04:05.376  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.377  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:04:05.384  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:04:05.390  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:04:05.390  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:04:05.390  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:04:05.390  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:04:05.390  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:04:05.390  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.390  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:04:05.390  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:04:05.392  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.393  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:04:05.393  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 08:04:05.393  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a444c4 added. We now have 4 listener(s)
09-30 08:04:05.395  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:04:05.395  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.395  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 08:04:05.395  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:04:05.395  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77d2fad added. We now have 5 listener(s)
09-30 08:04:05.395  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.395  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:04:05.396  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:04:05.396  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:04:05.396  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:04:05.396  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.396  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:04:05.396  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.396  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.396  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a42d71 removed from the list
09-30 08:04:05.396  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:04:05.396  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.396  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325f756 removed from the list
09-30 08:04:05.396  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:04:05.396  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:04:05.397  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.397  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.399  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.399  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.399  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.399  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325f756 not in the list
,09-30 08:04:05.399  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.399  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.399  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.400  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.401  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.401  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.401  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77d2fad removed from the list
09-30 08:04:05.401  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:04:05.401  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.401  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.401  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.401  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.401  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a444c4 removed from the list
09-30 08:04:05.402  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:04:05.402  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a232e2 added. We now have 3 listener(s)
09-30 08:04:05.403  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 08:04:05.403  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.403  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:04:05.404  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:04:05.404  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5cb673 added. We now have 4 listener(s)
09-30 08:04:05.404  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.405  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 08:04:05.408  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:04:05.412  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:04:05.412  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:04:05.412  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:04:05.412  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:04:05.412  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:04:05.412  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.412  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:04:05.412  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:04:05.414  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.414  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:04:05.414  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 08:04:05.414  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46a19a9 added. We now have 4 listener(s)
,09-30 08:04:05.417  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:04:05.417  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 08:04:05.418  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:04:05.418  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:04:05.418  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b49b2e added. We now have 5 listener(s)
09-30 08:04:05.418  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.418  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:04:05.418  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.418  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:04:05.418  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:04:05.418  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:04:05.418  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 08:04:05.422  5679  5725 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 08:04:05.423  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 08:04:05.423  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:04:05.426  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:04:05.426  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:04:05.426  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 08:04:05.429  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 08:04:05.429  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:04:05.429  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:04:05.429  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:04:05.429  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:04:05.430  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:04:05.432  5947  5985 D BtGatt.GattService: registerClient() - UUID=3e2b32b4-ae8c-418f-9586-0e4c758dd7ba
09-30 08:04:05.433  5947  5963 D BtGatt.GattService: onClientRegistered() - UUID=3e2b32b4-ae8c-418f-9586-0e4c758dd7ba, clientIf=5
,09-30 08:04:05.433  5679  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 08:04:05.434  5947  5958 D BtGatt.GattService: start scan with filters
,09-30 08:04:05.437  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 08:04:05.437  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:04:05.438  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 08:04:05.438  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:04:05.438  5947  5966 D BtGatt.ScanManager: handling starting scan
09-30 08:04:05.438  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:04:05.438  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:04:05.438  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 08:04:05.439  5947  5966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663b7a0
,09-30 08:04:05.441  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:04:05.441  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:04:05.441  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 08:04:05.442  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:04:05.445  5679  5725 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 08:04:05.445  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 08:04:05.445  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-30 08:04:05.445  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.445  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:04:05.445  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.445  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 08:04:05.445  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:04:05.445  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:04:05.445  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:04:05.445  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:04:05.445  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:04:05.446  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:04:05.447  5947  5963 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:04:05.447  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:04:05.447  5947  5958 D BtGatt.GattService: stopScan() - queue size =1
,09-30 08:04:05.448  5947  5966 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 08:04:05.448  5947  5975 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 08:04:05.448  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-30 08:04:05.448  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:04:05.448  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:04:05.448  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 08:04:05.448  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:04:05.448  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:04:05.448  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:04:05.449  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 08:04:05.450  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:04:05.450  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-30 08:04:05.450  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:04:05.450  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:04:05.450  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:04:05.451  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:04:05.452  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:04:05.452  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:04:05.452  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 08:04:05.454  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:04:05.455  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:04:05.455  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:04:05.455  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:04:05.455  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:04:05.455  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.455  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.455  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:04:05.455  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.455  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 08:04:05.455  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a232e2 removed from the list
,09-30 08:04:05.455  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.455  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5cb673 removed from the list
09-30 08:04:05.456  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:04:05.456  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.456  5947  5966 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:04:05.456  5947  5966 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:04:05.456  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.456  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:04:05.457  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.457  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.457  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.457  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5cb673 not in the list
09-30 08:04:05.457  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.457  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.458  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.458  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.458  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.459  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b49b2e removed from the list
09-30 08:04:05.459  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:04:05.459  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.459  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.459  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.459  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.459  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46a19a9 removed from the list
09-30 08:04:05.459  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:04:05.459  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8733c3a added. We now have 3 listener(s)
09-30 08:04:05.461  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:04:05.461  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.461  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 08:04:05.461  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:04:05.461  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44680eb added. We now have 4 listener(s)
09-30 08:04:05.461  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:04:05.462  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 08:04:05.464  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:04:05.466  5947  5963 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:04:05.466  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:04:05.469  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:04:05.469  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:04:05.469  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:04:05.469  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:04:05.469  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:04:05.469  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.469  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:04:05.469  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:04:05.471  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:04:05.471  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:04:05.471  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 08:04:05.471  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.471  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:04:05.471  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90a54e1 added. We now have 4 listener(s)
09-30 08:04:05.472  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:04:05.473  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.473  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:04:05.473  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:04:05.473  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@648e206 added. We now have 5 listener(s)
09-30 08:04:05.473  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.473  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:04:05.473  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.474  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:04:05.474  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:04:05.474  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:04:05.474  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:04:05.474  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 08:04:05.476  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.477  5679  5725 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 08:04:05.477  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 08:04:05.478  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:04:05.478  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.478  5947  5966 D BtGatt.ScanManager: stopping BLe Batch
,09-30 08:04:05.482  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:04:05.483  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:04:05.483  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 08:04:05.483  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 08:04:05.483  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.484  5947  5966 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 08:04:05.487  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 08:04:05.487  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:04:05.487  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-30 08:04:05.487  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:04:05.487  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:04:05.488  5679  5725 D BluetoothAdapter: STATE_ON
,09-30 08:04:05.490  5947  5963 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-30 08:04:05.490  5947  5958 D BtGatt.GattService: registerClient() - UUID=01858f60-8cd5-4d94-a8a3-b341ec1b6949
09-30 08:04:05.490  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.490  5947  5963 D BtGatt.GattService: onClientRegistered() - UUID=01858f60-8cd5-4d94-a8a3-b341ec1b6949, clientIf=5
09-30 08:04:05.490  5679  5690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:04:05.491  5947  5985 D BtGatt.GattService: start scan with filters
,09-30 08:04:05.493  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 08:04:05.493  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:04:05.493  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:04:05.493  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:04:05.493  5947  5966 D BtGatt.ScanManager: handling starting scan
09-30 08:04:05.493  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-30 08:04:05.493  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:04:05.494  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 08:04:05.496  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 08:04:05.496  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:04:05.496  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:04:05.497  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:04:05.500  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:04:05.500  5947  5963 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:04:05.500  5679  5725 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-30 08:04:05.500  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.500  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:04:05.500  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:04:05.500  5947  5966 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 08:04:05.500  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:04:05.500  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:04:05.500  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.500  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:04:05.500  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:04:05.500  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.500  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8733c3a removed from the list
09-30 08:04:05.500  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:04:05.500  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44680eb removed from the list
09-30 08:04:05.500  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:04:05.500  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:04:05.501  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.501  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-30 08:04:05.501  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.501  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:04:05.502  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.502  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.502  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.503  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44680eb not in the list
09-30 08:04:05.503  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:04:05.503  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:04:05.503  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:04:05.503  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:04:05.503  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 08:04:05.503  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:04:05.504  5947  5958 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:04:05.504  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:04:05.504  5947  5957 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 08:04:05.504  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.504  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 08:04:05.504  5947  5966 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:04:05.504  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:04:05.504  5947  5966 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:04:05.504  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:04:05.505  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:04:05.505  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:04:05.505  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,09-30 08:04:05.505  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:04:05.505  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 08:04:05.506  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:04:05.506  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:04:05.506  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:04:05.506  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:04:05.506  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:04:05.507  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:04:05.508  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.508  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.508  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.508  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:04:05.508  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@648e206 removed from the list
09-30 08:04:05.508  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:04:05.508  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:04:05.508  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:04:05.509  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.509  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.509  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.509  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.509  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90a54e1 removed from the list
09-30 08:04:05.509  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:04:05.510  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9811892 added. We now have 3 listener(s)
,09-30 08:04:05.511  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 08:04:05.511  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.512  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:04:05.512  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:04:05.512  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4602263 added. We now have 4 listener(s)
09-30 08:04:05.512  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.512  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:04:05.515  5947  5963 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 08:04:05.515  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.515  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:04:05.519  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:04:05.519  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:04:05.519  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:04:05.519  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:04:05.519  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:04:05.519  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.519  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:04:05.519  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:04:05.519  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 08:04:05.519  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:04:05.522  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.522  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:04:05.522  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:04:05.522  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9fbf19 added. We now have 4 listener(s)
,09-30 08:04:05.523  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 08:04:05.524  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.524  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:04:05.524  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:04:05.524  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2942bde added. We now have 5 listener(s)
09-30 08:04:05.524  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.524  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:04:05.524  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:04:05.524  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:04:05.524  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:04:05.524  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 08:04:05.524  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.525  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:04:05.525  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.526  5947  5966 D BtGatt.ScanManager: stopping BLe Batch
09-30 08:04:05.526  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.527  5679  5725 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 08:04:05.527  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 08:04:05.531  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:04:05.531  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:04:05.531  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 08:04:05.531  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 08:04:05.532  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.532  5947  5966 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 08:04:05.534  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 08:04:05.534  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:04:05.534  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:04:05.534  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:04:05.534  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:04:05.535  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:04:05.536  5947  5963 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 08:04:05.536  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.537  5947  5975 D BtGatt.GattService: registerClient() - UUID=4a6de6e6-1a81-4df0-911b-202e5917a5aa
,09-30 08:04:05.537  5947  5963 D BtGatt.GattService: onClientRegistered() - UUID=4a6de6e6-1a81-4df0-911b-202e5917a5aa, clientIf=5
09-30 08:04:05.537  5679  5689 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:04:05.537  5947  5985 D BtGatt.GattService: start scan with filters
,09-30 08:04:05.539  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 08:04:05.539  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:04:05.539  5947  5966 D BtGatt.ScanManager: handling starting scan
09-30 08:04:05.539  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:04:05.540  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:04:05.540  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:04:05.540  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:04:05.540  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 08:04:05.542  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:04:05.542  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:04:05.542  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:04:05.543  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:04:05.544  5947  5963 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 08:04:05.544  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.544  5947  5966 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 08:04:05.549  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 08:04:05.549  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.549  5947  5966 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:04:05.549  5947  5966 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:04:05.550  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:04:05.550  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:04:05.550  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:04:05.550  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:04:05.550  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:04:05.550  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:04:05.550  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.550  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.550  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9811892 removed from the list
09-30 08:04:05.550  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.550  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4602263 removed from the list
09-30 08:04:05.550  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:04:05.550  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:04:05.551  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:04:05.551  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 08:04:05.551  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.551  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:04:05.552  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.552  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.552  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.552  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4602263 not in the list
09-30 08:04:05.552  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:04:05.552  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:04:05.552  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 08:04:05.552  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:04:05.552  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:04:05.553  5679  5725 D BluetoothAdapter: STATE_ON
09-30 08:04:05.553  5947  5958 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:04:05.554  5947  5957 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 08:04:05.554  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 08:04:05.554  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:04:05.554  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:04:05.554  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:04:05.554  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:04:05.554  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:04:05.554  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-30 08:04:05.554  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 08:04:05.555  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:04:05.555  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:04:05.555  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:04:05.555  5679  5725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:04:05.555  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:04:05.556  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.556  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.556  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.556  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.556  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2942bde removed from the list
09-30 08:04:05.556  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 08:04:05.556  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:04:05.556  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.556  5679  5679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:04:05.556  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.557  5679  5679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:04:05.557  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.557  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.557  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9fbf19 removed from the list
09-30 08:04:05.557  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:04:05.557  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3327ea added. We now have 3 listener(s)
09-30 08:04:05.558  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:04:05.559  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.559  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 08:04:05.559  5947  5963 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:04:05.559  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.559  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:04:05.559  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ed7adb added. We now have 4 listener(s)
09-30 08:04:05.559  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.559  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 08:04:05.561  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:04:05.564  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 08:04:05.564  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.565  5679  5725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:04:05.565  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:04:05.565  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:04:05.565  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:04:05.565  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:04:05.565  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.565  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:04:05.565  5679  5725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:04:05.566  5679  5725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:04:05.567  5679  5725 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 08:04:05.567  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:04:05.567  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c13851 added. We now have 4 listener(s)
,09-30 08:04:05.568  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:04:05.569  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:04:05.569  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 08:04:05.569  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:04:05.569  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.569  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@513d8b6 added. We now have 5 listener(s)
09-30 08:04:05.569  5679  5725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:04:05.569  5679  5725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:04:05.569  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:04:05.570  5679  5725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:04:05.570  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:04:05.570  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.570  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:04:05.570  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:04:05.570  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.570  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3327ea removed from the list
,09-30 08:04:05.570  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.570  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ed7adb removed from the list
09-30 08:04:05.570  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:04:05.570  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.570  5947  5966 D BtGatt.ScanManager: stopping BLe Batch
09-30 08:04:05.571  5679  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:04:05.572  5679  5725 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:04:05.572  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:04:05.572  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.573  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:04:05.575  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:04:05.575  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.575  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.575  5679  5725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ed7adb not in the list
09-30 08:04:05.575  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.575  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.576  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 08:04:05.576  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:04:05.576  5947  5966 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 08:04:05.577  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:04:05.577  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:04:05.577  5679  5725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:04:05.577  5679  5725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@513d8b6 removed from the list
09-30 08:04:05.577  5679  5725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:04:05.577  5679  5725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:04:05.577  5679  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:04:05.577  5679  5725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:04:05.577  5679  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:04:05.577  5679  5725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c13851 removed from the list
,09-30 08:04:05.578  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-30 08:04:05.578  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-30 08:04:05.578  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-30 08:04:05.579  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:04:05.579  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-30 08:04:05.579  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:04:05.580  5947  5963 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 08:04:05.580  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:04:05.953  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:04:06.009  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:04:06.058  5679  5679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:04:07.728  5679  6042 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 08:04:07.728  5679  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:08.547  5679  6042 W !!      : call onHalfStreamCopied
,09-30 08:04:08.547  5679  6042 I testCopyDataAndClose: closing input stream
,09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 08:04:09.331  5679  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 08:04:13.109  5679  6043 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:04:13.109  5679  6043 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:15.109  5679  5725 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 188. Connection data: Peer properties: [null null].
09-30 08:04:15.109  5679  5725 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:15.109  5679  5725 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 188, name: My test thread name)
,09-30 08:04:15.115  5679  6043 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 08:04:15.115  5679  6043 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:04:15.115  5679  6043 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-30 08:04:15.211   541   541 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 08:04:15.212   541   541 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 08:04:15.260  5679  6044 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 08:04:15.260  5679  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:16.882  5679  6044 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 08:04:16.882  5679  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 08:04:16.883  5679  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 08:04:20.625  5679  6045 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:04:20.625  5679  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:04:20.626  5679  6045 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:04:20.626  5679  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:20.626  5679  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:04:20.626  5679  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:04:20.626  5679  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:04:20.626  5679  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 08:04:20.626  5679  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:04:20.627  5679  6045 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:04:20.627  5679  6045 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 08:04:20.627  5679  6045 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:04:20.627  5679  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-30 08:04:20.629  5679  5725 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:04:20.631  5679  6046 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:04:20.631  5679  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:04:20.632  5679  6046 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
09-30 08:04:20.632  5679  6046 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:04:20.632  5679  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 08:04:20.632  5679  6046 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-30 08:04:20.632  5679  6046 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:04:20.632  5679  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 08:04:20.637  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-30 08:04:20.637  5679  5725 I jxcore-log: 
,09-30 08:04:20.638  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-30 08:04:20.638  5679  5725 I jxcore-log: 
09-30 08:04:20.638  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-30 08:04:20.638  5679  5725 I jxcore-log: 
09-30 08:04:20.638  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-30 08:04:20.638  5679  5725 I jxcore-log: 
09-30 08:04:20.639  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Total duration:  102833'
09-30 08:04:20.639  5679  5725 I jxcore-log: 
,09-30 08:04:20.640  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Failures: 
09-30 08:04:20.640  5679  5725 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-30 08:04:20.640  5679  5725 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
09-30 08:04:20.640  5679  5725 I jxcore-log:      but: was ""
09-30 08:04:20.640  5679  5725 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-30 08:04:20.640  5679  5725 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-30 08:04:20.640  5679  5725 I jxcore-log:      but: was ""
09-30 08:04:20.640  5679  5725 I jxcore-log: '
09-30 08:04:20.640  5679  5725 I jxcore-log: 
09-30 08:04:20.640  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-30 08:04:20.640  5679  5725 I jxcore-log: 
09-30 08:04:20.642  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-30 08:04:20.642  5679  5725 I jxcore-log: 
,09-30 08:04:20.644  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.644  5679  5725 I jxcore-log: 
09-30 08:04:20.645  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.645  5679  5725 I jxcore-log: 
,09-30 08:04:20.645  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.645  5679  5725 I jxcore-log: 
09-30 08:04:20.646  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.646  5679  5725 I jxcore-log: 
09-30 08:04:20.646  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 08:04:20.646  5679  5725 I jxcore-log: 
09-30 08:04:20.646  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:04:20.646  5679  5725 I jxcore-log: 
09-30 08:04:20.647  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.647  5679  5725 I jxcore-log: 
09-30 08:04:20.647  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.647  5679  5725 I jxcore-log: 
09-30 08:04:20.647  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 08:04:20.647  5679  5725 I jxcore-log: 
09-30 08:04:20.647  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:04:20.647  5679  5725 I jxcore-log: 
09-30 08:04:20.648  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:04:20.648  5679  5725 I jxcore-log: 
09-30 08:04:20.648  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.648  5679  5725 I jxcore-log: 
09-30 08:04:20.648  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.648  5679  5725 I jxcore-log: 
09-30 08:04:20.649  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.649  5679  5725 I jxcore-log: 
09-30 08:04:20.649  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.649  5679  5725 I jxcore-log: 
09-30 08:04:20.649  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.649  5679  5725 I jxcore-log: 
09-30 08:04:20.649  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.649  5679  5725 I jxcore-log: 
09-30 08:04:20.650  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04,:20.650  5679  5725 I jxcore-log: 
09-30 08:04:20.650  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.650  5679  5725 I jxcore-log: 
09-30 08:04:20.650  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.650  5679  5725 I jxcore-log: 
09-30 08:04:20.650  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.650  5679  5725 I jxcore-log: 
09-30 08:04:20.651  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.651  5679  5725 I jxcore-log: 
09-30 08:04:20.652  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.652  5679  5725 I jxcore-log: 
,09-30 08:04:20.653  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.653  5679  5725 I jxcore-log: 
09-30 08:04:20.653  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.653  5679  5725 I jxcore-log: 
09-30 08:04:20.653  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.653  5679  5725 I jxcore-log: 
09-30 08:04:20.653  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.653  5679  5725 I jxcore-log: 
,09-30 08:04:20.653  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.653  5679  5725 I jxcore-log: 
09-30 08:04:20.654  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.654  5679  5725 I jxcore-log: 
09-30 08:04:20.654  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.654  5679  5725 I jxcore-log: 
09-30 08:04:20.654  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.654  5679  5725 I jxcore-log: 
,09-30 08:04:20.654  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.654  5679  5725 I jxcore-log: 
09-30 08:04:20.655  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.655  5679  5725 I jxcore-log: 
09-30 08:04:20.655  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.655  5679  5725 I jxcore-log: 
09-30 08:04:20.655  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.655  5679  5725 I jxcore-log: 
,09-30 08:04:20.655  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.655  5679  5725 I jxcore-log: 
09-30 08:04:20.656  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:04:20.656  5679  5725 I jxcore-log: 
09-30 08:04:20.656  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.656  5679  5725 I jxcore-log: 
09-30 08:04:20.656  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 08:04:20.656  5679  5725 I jxcore-log: 
09-30 08:04:20.656  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.656  5679  5725 I jxcore-log: 
,09-30 08:04:20.656  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.656  5679  5725 I jxcore-log: 
09-30 08:04:20.657  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.657  5679  5725 I jxcore-log: 
09-30 08:04:20.657  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.657  5679  5725 I jxcore-log: 
09-30 08:04:20.657  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.657  5679  5725 I jxcore-log: 
09-30 08:04:20.657  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:04:20.657  5679  5725 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,09-30 08:04:20.658  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.658  5679  5725 I jxcore-log: 
09-30 08:04:20.658  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.658  5679  5725 I jxcore-log: 
09-30 08:04:20.658  5679  5725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:04:20.658  5679  5725 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,09-30 08:04:20.658  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:04:20.658  5679  5725 I jxcore-log: 
09-30 08:04:20.658  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:04:20.658  5679  5725 I jxcore-log: 
09-30 08:04:20.659  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:04:20.659  5679  5725 I jxcore-log: 
09-30 08:04:20.659  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:04:20.659  5679  5725 I jxcore-log: 
,09-30 08:04:20.664  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-30 08:04:20.664  5679  5725 I jxcore-log: 
09-30 08:04:20.664  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - WARN testUtils: 'myNameCallback not set!'
09-30 08:04:20.664  5679  5725 I jxcore-log: 
,09-30 08:04:20.666  5679  5725 I jxcore-log: 2016-09-30 12:04:20 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-30 08:04:20.666  5679  5725 I jxcore-log: 
,09-30 08:04:20.668  5679  5679 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-30 08:04:22.646  5679  5725 I jxcore-log: 2016-09-30 12:04:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-30 08:04:22.646  5679  5725 I jxcore-log: 
,09-30 08:04:22.973  5679  5725 I jxcore-log: 2016-09-30 12:04:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-30 08:04:22.973  5679  5725 I jxcore-log: 
,09-30 08:04:22.987  5679  5725 I jxcore-log: 2016-09-30 12:04:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-30 08:04:22.987  5679  5725 I jxcore-log: 
,09-30 08:04:23.225   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:04:24.067  5679  5725 I jxcore-log: 2016-09-30 12:04:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-30 08:04:24.067  5679  5725 I jxcore-log: 
,09-30 08:04:24.224  5679  5725 I jxcore-log: 2016-09-30 12:04:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-30 08:04:24.224  5679  5725 I jxcore-log: 
,09-30 08:04:24.229  5679  5725 I jxcore-log: 2016-09-30 12:04:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-30 08:04:24.229  5679  5725 I jxcore-log: 
,09-30 08:04:24.234  5679  5725 I jxcore-log: 2016-09-30 12:04:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-30 08:04:24.234  5679  5725 I jxcore-log: 
,09-30 08:04:24.763  5679  5725 I jxcore-log: 2016-09-30 12:04:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-30 08:04:24.763  5679  5725 I jxcore-log: 
,09-30 08:04:24.814  5679  5725 I jxcore-log: 2016-09-30 12:04:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-30 08:04:24.814  5679  5725 I jxcore-log: 
,09-30 08:04:24.826  5679  5725 I jxcore-log: 2016-09-30 12:04:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-30 08:04:24.826  5679  5725 I jxcore-log: 
,09-30 08:04:24.831  5679  5725 I jxcore-log: 2016-09-30 12:04:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-30 08:04:24.831  5679  5725 I jxcore-log: 
,09-30 08:04:25.104  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-30 08:04:25.104  5679  5725 I jxcore-log: 
,09-30 08:04:25.227  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-30 08:04:25.227  5679  5725 I jxcore-log: 
,09-30 08:04:25.458  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-30 08:04:25.458  5679  5725 I jxcore-log: 
,09-30 08:04:25.467  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-30 08:04:25.467  5679  5725 I jxcore-log: 
,09-30 08:04:25.471  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-30 08:04:25.471  5679  5725 I jxcore-log: 
,09-30 08:04:25.604  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-30 08:04:25.604  5679  5725 I jxcore-log: 
,09-30 08:04:25.612  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-30 08:04:25.612  5679  5725 I jxcore-log: 
,09-30 08:04:25.638  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-30 08:04:25.638  5679  5725 I jxcore-log: 
,09-30 08:04:25.672  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-30 08:04:25.672  5679  5725 I jxcore-log: 
,09-30 08:04:25.678  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-30 08:04:25.678  5679  5725 I jxcore-log: 
,09-30 08:04:25.683  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-30 08:04:25.683  5679  5725 I jxcore-log: 
,09-30 08:04:25.697  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-30 08:04:25.697  5679  5725 I jxcore-log: 
,09-30 08:04:25.701  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-30 08:04:25.701  5679  5725 I jxcore-log: 
,09-30 08:04:25.706  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-30 08:04:25.706  5679  5725 I jxcore-log: 
,09-30 08:04:25.710  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-30 08:04:25.710  5679  5725 I jxcore-log: 
,09-30 08:04:25.722  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-30 08:04:25.722  5679  5725 I jxcore-log: 
,09-30 08:04:25.741  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-30 08:04:25.741  5679  5725 I jxcore-log: 
,09-30 08:04:25.749  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-30 08:04:25.749  5679  5725 I jxcore-log: 
,09-30 08:04:25.760  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-30 08:04:25.760  5679  5725 I jxcore-log: 
,09-30 08:04:25.769  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-30 08:04:25.769  5679  5725 I jxcore-log: 
,09-30 08:04:25.781  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-30 08:04:25.781  5679  5725 I jxcore-log: 
,09-30 08:04:25.790  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-30 08:04:25.790  5679  5725 I jxcore-log: 
,09-30 08:04:25.795  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-30 08:04:25.795  5679  5725 I jxcore-log: 
,09-30 08:04:25.816  5679  5725 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-30 08:04:25.817  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - INFO testUtils: 'BLE multiple advertisement supported'
09-30 08:04:25.817  5679  5725 I jxcore-log: 
,09-30 08:04:25.912  5679  5725 I jxcore-log: 2016-09-30 12:04:25 - DEBUG CoordinatedClient: 'connected to the test server'
09-30 08:04:25.912  5679  5725 I jxcore-log: 
,09-30 08:04:26.004  5679  5725 I jxcore-log: 2016-09-30 12:04:26 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: '%s''
09-30 08:04:26.004  5679  5725 I jxcore-log: 
,09-30 08:04:26.004  5679  5725 I jxcore-log: 2016-09-30 12:04:26 - DEBUG CoordinatedClient: 'test client failed'
09-30 08:04:26.004  5679  5725 I jxcore-log: 
,09-30 08:04:26.006  5679  5725 I jxcore-log: 2016-09-30 12:04:26 - DEBUG CoordinatedClient: 'test client disconnected'
09-30 08:04:26.006  5679  5725 I jxcore-log: 
,09-30 08:04:26.006  5679  5725 I jxcore-log: 2016-09-30 12:04:26 - DEBUG CoordinatedClient: 'test client succeed'
09-30 08:04:26.006  5679  5725 I jxcore-log: 
09-30 08:04:26.007  5679  5725 I jxcore-log: 2016-09-30 12:04:26 - DEBUG CoordinatedThaliTape: 'all tests succeed'
09-30 08:04:26.007  5679  5725 I jxcore-log: 
,09-30 08:04:26.007  5679  5725 I jxcore-log: 2016-09-30 12:04:26 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
09-30 08:04:26.007  5679  5725 I jxcore-log: 
,09-30 08:04:26.244   927  3039 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:04:26.574  6055  6055 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-30 08:04:26.579  6055  6055 D AndroidRuntime: CheckJNI is OFF
,09-30 08:04:26.604  6055  6055 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-30 08:04:26.636  6055  6055 I Radio-JNI: register_android_hardware_Radio DONE
,09-30 08:04:26.651  6055  6055 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-30 08:04:26.661   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-30 08:04:26.662   927   940 I ActivityManager: Killing 5679:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-30 08:04:26.760   927  3853 I WindowState: WIN DEATH: Window{7825e5a u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-30 08:04:26.760   927  3038 D WifiService: Client connection lost with reason: 4
09-30 08:04:26.760   927  3735 D GraphicsStats: Buffer count: 2
,09-30 08:04:26.801   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-30 08:04:26.803   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-30 08:04:26.803   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-30 08:04:26.803   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-30 08:04:26.803   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:04:26.803   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:04:26.803   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:04:26.803   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 08:04:26.804   927   940 I ActivityManager:   Force finishing activity ActivityRecord{dd4628f u0 com.test.thalitest/.MainActivity t2}
,09-30 08:04:26.805   927   950 I art     : Starting a blocking GC Explicit
,09-30 08:04:26.810   927  3912 W ActivityManager: Spurious death for ProcessRecord{19e4788 0:com.test.thalitest/u0a77}, curProc for 5679: null
,09-30 08:04:26.817   927   945 W WindowManager: Attempted to add application window with unknown token Token{30fb91c ActivityRecord{dd4628f u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-30 08:04:26.818   927   945 W WindowManager: Token{30fb91c ActivityRecord{dd4628f u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{30fb91c ActivityRecord{dd4628f u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-30 08:04:26.818   927   945 W WindowManager: view not successfully added to wm, removing view
09-30 08:04:26.818   927   945 W WindowManager: Exception when adding starting window
09-30 08:04:26.818   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{f1de0a3 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-30 08:04:26.818   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-30 08:04:26.818   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-30 08:04:26.818   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-30 08:04:26.818   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-30 08:04:26.818   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-30 08:04:26.818   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:04:26.818   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:04:26.818   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:04:26.818   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 08:04:26.888   927   950 I art     : Explicit concurrent mark sweep GC freed 56100(3MB) AllocSpace objects, 15(500KB) LOS objects, 33% free, 29MB/43MB, paused 1.394ms total 82.203ms
,09-30 08:04:26.910   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-30 08:04:26.913  6055  6055 I art     : System.exit called, status: 0
,09-30 08:04:26.913  6055  6055 I AndroidRuntime: VM exiting with result code 0.
,09-30 08:04:26.933   927   950 I ActivityManager: Start proc 6065:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-30 08:04:26.934   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-30 08:04:26.945   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-30 08:04:26.947  3725  3725 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-30 08:04:26.949  5947  5947 D BluetoothMapAppObserver: onReceive
09-30 08:04:26.949  5947  5947 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-30 08:04:26.959   927  3003 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-30 08:04:26.960  3782  4143 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-30 08:04:26.995  3460  6078 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-30 08:04:26.995    28    28 W kworker/2:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:04:26.991  3725  6076 I Keyboard.Facilitator.DecoderInitializer: run()
,09-30 08:04:27.002    28    28 W kworker/2:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:04:27.010  3857  3857 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-30 08:04:27.015    28    28 W kworker/2:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:04:27.022  3644  3644 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-30 08:04:27.023  3644  3644 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-30 08:04:27.023  3644  3644 E AndroidRuntime: FATAL EXCEPTION: main
09-30 08:04:27.023  3644  3644 E AndroidRuntime: Process: com.google.process.gapps, PID: 3644
09-30 08:04:27.023  3644  3644 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-30 08:04:27.023  3644  3644 E AndroidRuntime: 	... 8 more
,09-30 08:04:27.025  3725  6076 I Decoder : createOrResetDecoder
,09-30 08:04:27.029   927  6085 E DropBoxManagerService: Can't write: system_app_crash
09-30 08:04:27.029   927  6085 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:04:27.029   927  6085 E DropBoxManagerService: 	... 5 more
,09-30 08:04:27.034   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-30 08:04:27.035  3460  3481 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
09-30 08:04:27.035  3644  3644 I Process : Sending signal. PID: 3644 SIG: 9
09-30 08:04:27.035  3460  3481 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjD4AB2C9B7) - 
09-30 08:04:27.036  3460  3481 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-30 08:04:27.036  3460  3481 E AndroidRuntime: Process: android.process.acore, PID: 3460
09-30 08:04:27.036  3460  3481 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:04:27.036  3460  3481 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 08:04:27.040   927  6086 E DropBoxManagerService: Can't write: system_app_crash
09-30 08:04:27.040   927  6086 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:04:27.040   927  6086 E DropBoxManagerService: 	... 5 more
,09-30 08:04:27.041   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-30 08:04:27.042   927   939 E PackageManager: Failed to write settings, restoring backup
09-30 08:04:27.042   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-30 08:04:27.042   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-30 08:04:27.042   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-30 08:04:27.042   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-30 08:04:27.042   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-30 08:04:27.042   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:04:27.042   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:04:27.042   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:04:27.045   927   940 E DropBoxManagerService: Can't write: system_server_wtf
09-30 08:04:27.045   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 08:04:27.045   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:04:27.045   927   940 E DropBoxManagerService: 	... 13 more
,09-30 08:04:27.057  3893  4001 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-30 08:04:27.073   927  3038 D WifiService: Client connection lost with reason: 4
,09-30 08:04:27.084  3460  6078 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-30 08:04:27.085  3460  6078 I Process : Sending signal. PID: 3460 SIG: 9
09-30 08:04:27.086   927  3912 I ActivityManager: Start proc 6088:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-30 08:04:27.087   927  3658 I ActivityManager: Process com.google.process.gapps (pid 3644) has died
09-30 08:04:27.087  3893  4001 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-30 08:04:27.087  3893  4001 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3893
09-30 08:04:27.087  3893  4001 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:04:27.087  3893  4001 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:04:27.087   927  3658 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,09-30 08:04:27.088   927  3658 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 11000ms
09-30 08:04:27.088   927  3658 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,09-30 08:04:27.093   927  3221 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 08:04:27.096   927  6097 E DropBoxManagerService: Can't write: system_app_crash
09-30 08:04:27.096   927  6097 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:04:27.096   927  6097 E DropBoxManagerService: 	... 5 more
,09-30 08:04:27.101  3893  4001 I Process : Sending signal. PID: 3893 SIG: 9
,09-30 08:04:27.123   927  3735 I ActivityManager: Start proc 6103:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-30 08:04:27.194   927   938 D GraphicsStats: Buffer count: 1
09-30 08:04:27.194   927  3215 I WindowState: WIN DEATH: Window{ddfdf2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-30 08:04:27.200   927  3658 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3893) has died
,09-30 08:04:27.200   927  3658 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-30 08:04:27.202   927  3658 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 08:04:27.208   927   938 I ActivityManager: Process android.process.acore (pid 3460) has died
,09-30 08:04:27.209   927   938 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-30 08:04:27.221   927   940 I ActivityManager: Start proc 6115:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 08:04:27.398   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
