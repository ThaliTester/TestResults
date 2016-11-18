#### Test 9215228616bd023_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-18 07:32:50.918   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-18 07:32:52.112  5699  5699 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-18 07:32:52.118  5699  5699 D AndroidRuntime: CheckJNI is OFF
11-18 07:32:52.144  5699  5699 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-18 07:32:52.176  5699  5699 I Radio-JNI: register_android_hardware_Radio DONE
11-18 07:32:52.191  5699  5699 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-18 07:32:52.195   928  3871 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-18 07:32:52.241   928  3871 I ActivityManager: Start proc 5708:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-18 07:32:52.246  5699  5699 D AndroidRuntime: Shutting down VM
,11-18 07:32:52.585   928  3158 I WindowManager: Screenshot max retries 4 of Token{cd0338d ActivityRecord{d36c24 u0 com.test.thalitest/.MainActivity t8}} appWin=Window{aa61bbc u0 Starting com.test.thalitest} drawState=4
,11-18 07:32:52.658  5708  5708 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-18 07:32:52.688  5708  5708 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-18 07:32:52.711  5708  5708 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 4419-4438)
,11-18 07:32:52.711  5708  5708 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 07:32:52.730  5708  5708 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {75d145b}
,11-18 07:32:52.730  5708  5708 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-18 07:32:52.731  5708  5708 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-18 07:32:52.734  5708  5708 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-18 07:32:52.735  5708  5708 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-18 07:32:52.763  5708  5708 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-18 07:32:52.771  5708  5708 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-18 07:32:52.771  5708  5708 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-18 07:32:52.771  5708  5708 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-18 07:32:52.771  5708  5708 I Adreno  : Build Date                       : 12/06/15
11-18 07:32:52.771  5708  5708 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-18 07:32:52.771  5708  5708 I Adreno  : Local Branch                     : mybranch17112971
11-18 07:32:52.771  5708  5708 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-18 07:32:52.771  5708  5708 I Adreno  : Remote Branch                    : NONE
11-18 07:32:52.771  5708  5708 I Adreno  : Reconstruct Branch               : NOTHING
,11-18 07:32:52.801   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b74f143:true
,11-18 07:32:52.833   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[35094]" dev="sockfs" ino=35094 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 07:32:52.833   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[35094]" dev="sockfs" ino=35094 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 07:32:52.844  5708  5708 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-18 07:32:52.852  5708  5708 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-18 07:32:52.876   951   951 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33070]" dev="sockfs" ino=33070 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 07:32:52.877  5708  5745 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-18 07:32:52.876   951   951 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33070]" dev="sockfs" ino=33070 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 07:32:52.879  3871  3871 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14280]" dev="sockfs" ino=14280 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 07:32:52.879  3871  3871 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14280]" dev="sockfs" ino=14280 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 07:32:52.882  5708  5732 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-18 07:32:52.915  5708  5745 I OpenGLRenderer: Initialized EGL, version 1.4
,11-18 07:32:52.985   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +400ms (total +769ms)
,11-18 07:32:53.010  5708  5708 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5708
,11-18 07:32:53.097  5708  5708 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-18 07:32:53.247  5708  5748 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -564917968
,11-18 07:32:53.251  5708  5748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-18 07:32:53.251  5708  5748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-18 07:32:53.251  5708  5748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-18 07:32:53.251  5708  5748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-18 07:32:53.251  5708  5748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-18 07:32:53.251  5708  5748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8723c9 added. We now have 1 listener(s)
,11-18 07:32:53.255  5708  5748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-18 07:32:53.255  5708  5748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-18 07:32:53.256  5708  5748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 07:32:53.256  5708  5748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-18 07:32:53.258  5708  5748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efd10fc added. We now have 1 listener(s)
,11-18 07:32:53.258  5708  5748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 07:32:53.262   928  2976 D WifiService: New client listening to asynchronous messages
,11-18 07:32:53.263  5708  5748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 07:32:53.263  5708  5748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-18 07:32:53.263  5708  5748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-18 07:32:53.263  5708  5748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-18 07:32:53.263  5708  5748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-18 07:32:53.263  5708  5748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-18 07:32:53.264  5708  5748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-18 07:32:53.265  5708  5748 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 07:32:53.390  5708  5708 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-18 07:32:53.665  5708  5754 W jxcore-log: Initializing JXcore engine
,11-18 07:32:53.665  5708  5754 W jxcore-log: JXcore engine is ready
,11-18 07:32:53.696  5754  5754 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12559 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-18 07:32:53.696  5754  5754 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13539]" dev="sockfs" ino=13539 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-18 07:32:53.696  5754  5754 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-18 07:32:53.696  5754  5754 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33042]" dev="sockfs" ino=33042 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-18 07:32:53.706  5708  5754 W jxcore-log: Starting JXcore engine
,11-18 07:32:53.765  5708  5754 W jxcore-log: Platform android
11-18 07:32:53.765  5708  5754 W jxcore-log: 
11-18 07:32:53.766  5708  5754 W jxcore-log: Process ARCH arm
11-18 07:32:53.766  5708  5754 W jxcore-log: 
,11-18 07:32:53.915  5708  5754 I jxcore-log: JXcore Cordova bridge is ready!
11-18 07:32:53.915  5708  5754 I jxcore-log: 
,11-18 07:32:53.915  5708  5754 W jxcore-log: JXcore engine is started
,11-18 07:32:53.921  5708  5748 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-18 07:32:53.925  5708  5708 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-18 07:32:59.856   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 07:33:03.577  5708  5754 I jxcore-log: 2016-11-18 12:33:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-18 07:33:03.577  5708  5754 I jxcore-log: 
,11-18 07:33:03.579  5708  5754 I jxcore-log: 2016-11-18 12:33:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-18 07:33:03.579  5708  5754 I jxcore-log: 
11-18 07:33:03.580  5708  5754 I jxcore-log: 2016-11-18 12:33:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-18 07:33:03.580  5708  5754 I jxcore-log: 
,11-18 07:33:03.585  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 07:33:03.585  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 07:33:03.587  5708  5754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 07:33:03.590  5708  5754 I jxcore-log: 2016-11-18 12:33:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-18 07:33:03.590  5708  5754 I jxcore-log: 
11-18 07:33:03.591  5708  5754 I jxcore-log: 2016-11-18 12:33:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-18 07:33:03.591  5708  5754 I jxcore-log: 
,11-18 07:33:03.841  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 07:33:03.842  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f225ea7 added. We now have 2 listener(s)
11-18 07:33:03.842  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:03.842  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 07:33:03.842  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 07:33:03.843  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 07:33:03.843  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a35f54 added. We now have 2 listener(s)
11-18 07:33:03.843  5708  5754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 07:33:03.843  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 07:33:03.844  5708  5754 D ExecuteNativeTests: Running unit tests
11-18 07:33:03.845  5708  5754 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 07:33:03.845   928   938 D WifiService: setWifiEnabled: true pid=5708, uid=10077
11-18 07:33:03.845   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 07:33:13.851  5708  5754 I com.test.thalitest.ThaliTestRunner: Running UT
,11-18 07:33:13.921  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 07:33:13.921  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d77aa1 added. We now have 3 listener(s)
11-18 07:33:13.922  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:13.922  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 07:33:13.922  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 07:33:13.922  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-18 07:33:13.922  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a274c6 added. We now have 3 listener(s)
11-18 07:33:13.922  5708  5754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 07:33:13.923  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 07:33:13.928  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-18 07:33:13.929  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 07:33:13.929  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 07:33:13.929  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 07:33:13.929  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 07:33:13.931  5708  5754 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-18 07:33:13.931  5708  5754 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-18 07:33:13.931  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-18 07:33:13.931  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 07:33:13.931  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 07:33:13.931  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 07:33:13.932  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,11-18 07:33:13.932  5708  5754 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-18 07:33:13.935  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-18 07:33:13.937  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-18 07:33:13.938  5708  5754 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-18 07:33:13.939  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 07:33:13.939  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 07:33:13.942  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 07:33:13.943  5708  5754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 07:33:13.944  5708  5754 D io.jxcore.node.ConnectivityMonitor: start: OK
11-18 07:33:13.944  5708  5754 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-18 07:33:13.944  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-18 07:33:13.944  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.944  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.944  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.944  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:13.944  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 07:33:13.944  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 07:33:13.944  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 07:33:13.945  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 07:33:13.946  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 07:33:13.946  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-18 07:33:13.946  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 07:33:13.946  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 07:33:13.946  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 07:33:13.946  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 07:33:13.946  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 07:33:13.946  5708  5756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 07:33:13.950  5708  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 07:33:13.951  5708  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 07:33:13.949  4630  4630 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[35124]" dev="sockfs" ino=35124 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:13.952  5708  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 07:33:13.952  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 07:33:13.952  5708  5756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 07:33:13.952  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 07:33:13.952  5708  5754 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 07:33:13.953  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 07:33:13.949  4630  4630 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[35124]" dev="sockfs" ino=35124 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:13.955  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.955  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 07:33:13.957  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 07:33:13.957  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 07:33:13.957  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-18 07:33:13.958  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.958  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.958  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 07:33:13.958  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 07:33:13.958  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:13.958  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
11-18 07:33:13.959  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 07:33:13.959  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:13.959  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.959  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 07:33:13.959  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:13.959  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.959  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.959  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.960  5708  5754 D BluetoothAdapter: STATE_ON
,11-18 07:33:13.962  4607  4839 D BtGatt.GattService: registerClient() - UUID=cf8ae8c0-e2c2-441e-a4a7-ccc98bf7b600
,11-18 07:33:13.963  4607  4680 D BtGatt.GattService: onClientRegistered() - UUID=cf8ae8c0-e2c2-441e-a4a7-ccc98bf7b600, clientIf=5
,11-18 07:33:13.964  5708  5718 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 07:33:13.966  4607  4682 D BtGatt.AdvertiseManager: message : 0
,11-18 07:33:13.969  4607  4682 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 07:33:13.985  4607  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 07:33:13.993  4607  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 07:33:13.994  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.994  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.994  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 07:33:13.994  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:13.994  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.995  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.995  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:13.995  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.995  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 07:33:13.995  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 07:33:13.995  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.996  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.996  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:13.996  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:13.996  5708  5754 I io.jxcore.node.ConnectionHelper: start: OK
11-18 07:33:13.997  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 07:33:13.997  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-18 07:33:13.997  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:13.997  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 07:33:13.998  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 07:33:13.998  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-18 07:33:13.998  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:13.998  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:13.999  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 07:33:13.999  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-18 07:33:13.999  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:13.999  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 07:33:13.999  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-18 07:33:13.999  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.003  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.003  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 07:33:14.003  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.003  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.004  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.004  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 07:33:14.499  5708  5754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-18 07:33:14.500  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-18 07:33:14.501  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-18 07:33:14.502  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-18 07:33:14.503  5708  5754 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-18 07:33:14.503  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 07:33:14.503  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 07:33:14.503  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 07:33:14.503  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 07:33:14.503  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 07:33:14.504  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 07:33:14.504  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 07:33:14.504  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 07:33:14.504  5708  5756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 07:33:14.504  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 07:33:14.504  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 07:33:14.504  5708  5756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 07:33:14.504  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 07:33:14.505  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 07:33:14.505  5708  5756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 07:33:14.505  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 07:33:14.506  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.506  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.506  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.507  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.508  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:14.508  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-18 07:33:14.509  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:14.509  5708  5754 D BluetoothLeScanner: could not find callback wrapper
11-18 07:33:14.509  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 07:33:14.509  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.509  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.509  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.510  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 07:33:14.510  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.511  4607  4682 D BtGatt.AdvertiseManager: message : 1
11-18 07:33:14.512  4607  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
11-18 07:33:14.524  4607  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 07:33:14.524  4607  4680 D BtGatt.GattService: Client app is not null!
11-18 07:33:14.526  4607  4829 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 07:33:14.527  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 07:33:14.527  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.527  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 07:33:14.527  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.527  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.528  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.528  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-18 07:33:14.528  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 07:33:14.529  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 07:33:14.529  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.532  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.532  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 07:33:14.532  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.532  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.533  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-18 07:33:14.533  5708  5708 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 07:33:14.537  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 07:33:14.537  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 07:33:14.537  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 07:33:14.537  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 07:33:14.537  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 07:33:14.538  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:14.538  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.538  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 07:33:14.538  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 07:33:14.538  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.538  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.538  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 07:33:14.538  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 07:33:14.540  5708  5754 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 07:33:14.540  5708  5754 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 07:33:14.540  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.540  5708  5754 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-18 07:33:14.540  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.540  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-18 07:33:14.540  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.540  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.540  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.540  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:14.540  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.541  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.541  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:14.541  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 07:33:14.541  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 07:33:14.541  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 07:33:14.542  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 07:33:14.543  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 07:33:14.543  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 07:33:14.543  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 07:33:14.543  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 07:33:14.543  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 07:33:14.543  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 07:33:14.544  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 07:33:14.544  5708  5759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 07:33:14.544  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 07:33:14.544  5708  5759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 07:33:14.549  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 07:33:14.549  5708  5754 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 07:33:14.549  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 07:33:14.549  4829  4829 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31364]" dev="sockfs" ino=31364 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:14.549  4829  4829 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31364]" dev="sockfs" ino=31364 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:14.550  5708  5759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 07:33:14.556  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.556  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 07:33:14.557  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 07:33:14.558  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 07:33:14.558  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-18 07:33:14.561  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.561  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.561  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 07:33:14.561  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 07:33:14.561  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:14.561  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
11-18 07:33:14.561  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:14.562  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 07:33:14.562  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.562  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 07:33:14.562  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 07:33:14.562  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.562  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.562  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.563  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:14.566  4607  4630 D BtGatt.GattService: registerClient() - UUID=78d6d2d9-d7ad-4308-8a1e-070039b7dc84
11-18 07:33:14.566  4607  4680 D BtGatt.GattService: onClientRegistered() - UUID=78d6d2d9-d7ad-4308-8a1e-070039b7dc84, clientIf=5
,11-18 07:33:14.567  5708  5718 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 07:33:14.568  4607  4682 D BtGatt.AdvertiseManager: message : 0
,11-18 07:33:14.571  4607  4682 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 07:33:14.582  4607  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 07:33:14.589  4607  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 07:33:14.589  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 07:33:14.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 07:33:14.592  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 07:33:14.592  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:14.593  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.593  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.593  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:14.594  5708  5754 I io.jxcore.node.ConnectionHelper: start: OK
11-18 07:33:14.594  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:14.594  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.594  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:14.594  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 07:33:14.594  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.594  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.594  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:14.595  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.595  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 07:33:14.595  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 07:33:14.595  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.595  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.595  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 07:33:14.595  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 07:33:14.598  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.598  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 07:33:14.598  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.599  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.599  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:14.599  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 07:33:15.100  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 07:33:15.100  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 07:33:15.100  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-18 07:33:15.100  5708  5708 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 07:33:15.100  5708  5754 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 07:33:15.100  5708  5754 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 07:33:15.101  5708  5754 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-18 07:33:15.101  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-18 07:33:15.101  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.102  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.102  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 07:33:15.103  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.104  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-18 07:33:15.104  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.105  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.105  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.107  4607  4682 D BtGatt.AdvertiseManager: message : 1
11-18 07:33:15.108  4607  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 07:33:15.121  4607  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 07:33:15.121  4607  4680 D BtGatt.GattService: Client app is not null!
11-18 07:33:15.122  4607  4630 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 07:33:15.123  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 07:33:15.123  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.123  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 07:33:15.123  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.123  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.124  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.124  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 07:33:15.124  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.124  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.124  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.124  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 07:33:15.124  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 07:33:15.125  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:15.125  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,11-18 07:33:15.125  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:15.125  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:15.125  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.125  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 07:33:15.126  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 07:33:15.126  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.126  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.126  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.128  5708  5754 D BluetoothAdapter: STATE_ON
,11-18 07:33:15.132  4607  4839 D BtGatt.GattService: registerClient() - UUID=781ed369-cd13-4184-8c67-6c7a6006a759
11-18 07:33:15.132  4607  4680 D BtGatt.GattService: onClientRegistered() - UUID=781ed369-cd13-4184-8c67-6c7a6006a759, clientIf=5
,11-18 07:33:15.133  5708  5718 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 07:33:15.135  4607  4682 D BtGatt.AdvertiseManager: message : 0
,11-18 07:33:15.139  4607  4682 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 07:33:15.153  4607  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 07:33:15.161  4607  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 07:33:15.162  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.162  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.162  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.162  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 07:33:15.163  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.163  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.163  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.163  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.163  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.163  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:15.163  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-18 07:33:15.163  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.163  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 07:33:15.163  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.163  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.163  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.164  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-18 07:33:15.164  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:15.164  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 07:33:15.164  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.164  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-18 07:33:15.164  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-18 07:33:15.164  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-18 07:33:15.164  5708  5754 I io.jxcore.node.ConnectionHelper: start: OK
11-18 07:33:15.164  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.164  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-18 07:33:15.165  5708  5754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-18 07:33:15.165  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 07:33:15.165  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 07:33:15.165  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 07:33:15.165  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 07:33:15.165  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 07:33:15.166  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 07:33:15.166  5708  5759 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-18 07:33:15.166  5708  5759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 07:33:15.166  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 07:33:15.166  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 07:33:15.166  5708  5759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 07:33:15.166  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 07:33:15.166  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 07:33:15.166  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 07:33:15.166  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 07:33:15.166  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 07:33:15.167  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.167  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.167  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.167  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.168  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:15.168  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 07:33:15.169  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:15.169  5708  5754 D BluetoothLeScanner: could not find callback wrapper
11-18 07:33:15.169  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 07:33:15.169  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.170  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.170  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.170  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 07:33:15.170  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.171  4607  4682 D BtGatt.AdvertiseManager: message : 1
11-18 07:33:15.172  4607  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 07:33:15.180  4607  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 07:33:15.180  4607  4680 D BtGatt.GattService: Client app is not null!
11-18 07:33:15.181  4607  4839 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 07:33:15.182  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 07:33:15.182  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.182  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 07:33:15.182  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.182  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.182  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.182  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 07:33:15.182  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 07:33:15.183  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 07:33:15.183  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.184  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.185  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:15.185  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.185  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.185  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 07:33:15.185  5708  5708 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 07:33:15.185  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 07:33:15.185  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 07:33:15.185  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 07:33:15.185  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 07:33:15.186  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:15.186  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.187  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 07:33:15.187  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 07:33:15.187  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-18 07:33:15.187  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.187  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.187  5708  5754 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-18 07:33:15.187  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 07:33:15.187  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.189  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.189  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.189  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-18 07:33:15.189  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.189  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.189  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:15.189  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-18 07:33:15.190  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-18 07:33:15.190  5708  5754 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-18 07:33:15.191  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-18 07:33:15.191  5708  5754 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-18 07:33:15.192  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-18 07:33:15.193  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 07:33:15.193  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 07:33:15.193  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 07:33:15.193  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 07:33:15.193  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 07:33:15.193  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 07:33:15.193  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 07:33:15.193  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 07:33:15.193  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 07:33:15.194  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 07:33:15.194  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 07:33:15.194  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 07:33:15.195  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-18 07:33:15.195  5708  5754 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-18 07:33:15.195  5708  5754 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 07:33:15.198  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-18 07:33:15.198  5708  5754 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-18 07:33:15.200  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-18 07:33:15.200  5708  5754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-18 07:33:15.201  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-18 07:33:15.201  5708  5754 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-18 07:33:15.201  5708  5754 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-18 07:33:15.201  5708  5754 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-18 07:33:15.201  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 07:33:15.201  5708  5754 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-18 07:33:15.202  5708  5754 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 07:33:15.202  5708  5754 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-18 07:33:15.202  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 07:33:15.202  5708  5754 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-18 07:33:15.202  5708  5754 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 07:33:15.202  5708  5754 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 07:33:15.202  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 07:33:15.202  5708  5754 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-18 07:33:15.203  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-18 07:33:15.203  5708  5754 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 07:33:15.203  5708  5754 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 07:33:15.203  5708  5754 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-18 07:33:15.203  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-18 07:33:15.203  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.203  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.203  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.203  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:15.203  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 07:33:15.204  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 07:33:15.204  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 07:33:15.205  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 07:33:15.205  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 07:33:15.205  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 07:33:15.205  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 07:33:15.205  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 07:33:15.205  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 07:33:15.205  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 07:33:15.205  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 07:33:15.205  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 07:33:15.205  5708  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 07:33:15.207  5708  5763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 07:33:15.209  4839  4839 W Binder_5: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33090]" dev="sockfs" ino=33090 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:15.209  4839  4839 W Binder_5: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33090]" dev="sockfs" ino=33090 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:15.211  5708  5763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 07:33:15.214  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 07:33:15.214  5708  5754 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 07:33:15.214  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 07:33:15.221  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.222  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 07:33:15.222  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-18 07:33:15.223  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 07:33:15.223  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-18 07:33:15.225  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.225  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.225  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 07:33:15.225  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 07:33:15.226  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:15.226  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
11-18 07:33:15.226  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:15.226  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:15.226  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.226  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 07:33:15.226  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:15.226  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.226  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.226  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.227  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:15.230  4607  4630 D BtGatt.GattService: registerClient() - UUID=d9866da7-4cd5-46fa-ac3b-cebca0d779c5
11-18 07:33:15.230  4607  4680 D BtGatt.GattService: onClientRegistered() - UUID=d9866da7-4cd5-46fa-ac3b-cebca0d779c5, clientIf=5
11-18 07:33:15.230  5708  5718 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 07:33:15.231  4607  4682 D BtGatt.AdvertiseManager: message : 0
11-18 07:33:15.234  4607  4682 D BtGatt.AdvertiseManager: starting multi advertising
11-18 07:33:15.243  4607  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-18 07:33:15.248  4607  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-18 07:33:15.248  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.248  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.248  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 07:33:15.248  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.249  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.249  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.249  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.249  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.249  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 07:33:15.250  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 07:33:15.250  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.251  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.251  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.251  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.251  5708  5754 I io.jxcore.node.ConnectionHelper: start: OK
11-18 07:33:15.251  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:15.251  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.251  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.252  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.252  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 07:33:15.252  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.254  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.254  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 07:33:15.254  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.254  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.255  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.255  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 07:33:15.752  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 07:33:15.752  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 07:33:15.752  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 07:33:15.752  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-18 07:33:15.753  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 07:33:15.753  5708  5763 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 07:33:15.753  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 07:33:15.753  5708  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 07:33:15.753  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 07:33:15.754  5708  5763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 07:33:15.754  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 07:33:15.754  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-18 07:33:15.754  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d77aa1 removed from the list
11-18 07:33:15.754  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-18 07:33:15.754  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-18 07:33:15.754  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 07:33:15.754  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 07:33:15.754  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 07:33:15.754  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 07:33:15.755  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 07:33:15.755  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.755  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.755  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.756  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.758  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:15.758  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 07:33:15.760  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:15.760  5708  5754 D BluetoothLeScanner: could not find callback wrapper
11-18 07:33:15.760  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-18 07:33:15.760  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.760  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.761  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.761  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 07:33:15.761  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.762  4607  4682 D BtGatt.AdvertiseManager: message : 1
11-18 07:33:15.763  4607  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 07:33:15.775  4607  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 07:33:15.776  4607  4680 D BtGatt.GattService: Client app is not null!
,11-18 07:33:15.777  4607  4829 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 07:33:15.778  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 07:33:15.778  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.778  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 07:33:15.778  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.778  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.778  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.779  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 07:33:15.779  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 07:33:15.779  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 07:33:15.780  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.781  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.782  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 07:33:15.782  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:15.782  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:15.782  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a274c6 removed from the list
11-18 07:33:15.782  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 07:33:15.782  5708  5754 D io.jxcore.node.ConnectivityMonitor: stop
11-18 07:33:15.782  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 07:33:15.782  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 07:33:15.782  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:15.783  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.783  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 07:33:15.783  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-18 07:33:15.783  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.783  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.783  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 07:33:15.783  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 07:33:15.786  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.786  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.787  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.787  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:15.787  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 07:33:15.919   592   592 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-18 07:33:15.919   592   592 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-18 07:33:16.288  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 07:33:19.857   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 07:33:20.787  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-18 07:33:20.789  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 07:33:20.789  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 07:33:20.790  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-18 07:33:20.795  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 07:33:20.797  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 07:33:20.797  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 07:33:20.797  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-18 07:33:20.797  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 07:33:20.797  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-18 07:33:20.797  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 07:33:20.798  5708  5764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 07:33:20.799  5708  5764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 07:33:20.803  4839  4839 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31384]" dev="sockfs" ino=31384 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 07:33:20.803  4839  4839 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31384]" dev="sockfs" ino=31384 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:20.800  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-18 07:33:20.801  5708  5754 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-18 07:33:20.802  5708  5754 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-18 07:33:20.802  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 07:33:20.803  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 07:33:20.803  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 07:33:20.805  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-18 07:33:20.805  5708  5764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 07:33:20.811  5708  5754 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-18 07:33:20.812  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 07:33:20.812  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 07:33:20.812  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 07:33:20.812  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 07:33:20.813  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 07:33:20.813  5708  5764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 07:33:20.813  5708  5764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 07:33:20.813  5708  5764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 07:33:20.813  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 07:33:20.814  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 07:33:20.814  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 07:33:20.814  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 07:33:20.814  5708  5754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d77aa1 not in the list
11-18 07:33:20.814  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 07:33:20.814  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 07:33:20.815  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 07:33:20.815  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 07:33:20.815  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 07:33:20.815  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:20.817  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:20.817  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:20.817  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:20.817  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:20.817  5708  5754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a274c6 not in the list
11-18 07:33:20.817  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 07:33:20.817  5708  5754 D io.jxcore.node.ConnectivityMonitor: stop
11-18 07:33:20.817  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 07:33:20.817  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:20.819  5708  5754 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-18 07:33:20.821  5708  5754 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-18 07:33:20.821  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 07:33:20.821  5708  5754 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-18 07:33:20.821  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 07:33:20.822  5708  5754 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-18 07:33:20.822  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-18 07:33:20.822  5708  5754 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-18 07:33:20.823  5708  5754 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-18 07:33:20.824  5708  5754 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-18 07:33:20.825  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-18 07:33:20.825  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-18 07:33:20.825  5708  5754 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-18 07:33:20.825  5708  5754 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-18 07:33:20.825  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 07:33:20.825  5708  5754 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-18 07:33:20.825  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 07:33:20.825  5708  5754 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-18 07:33:20.826  5708  5754 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-18 07:33:20.826  5708  5754 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-18 07:33:20.826  5708  5754 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-18 07:33:20.826  5708  5754 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-18 07:33:20.827  5708  5754 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-18 07:33:20.827  5708  5754 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-18 07:33:20.827  5708  5754 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-18 07:33:20.827  5708  5754 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-18 07:33:20.827  5708  5754 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-18 07:33:20.828  5708  5754 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-18 07:33:20.828  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 07:33:20.828  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfbd5e4 added. We now have 3 listener(s)
,11-18 07:33:20.830  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:20.830  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 07:33:20.830  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 07:33:20.830  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 07:33:20.830  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bdba4d added. We now have 3 listener(s)
,11-18 07:33:20.830  5708  5754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 07:33:20.831  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 07:33:20.833  5708  5754 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 07:33:20.834   928  3842 D WifiService: setWifiEnabled: true pid=5708, uid=10077
11-18 07:33:20.834   928  3842 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 07:33:20.835  5708  5754 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-18 07:33:20.838  5708  5754 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-18 07:33:20.838  5708  5754 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-18 07:33:20.841  5708  5754 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-18 07:33:20.841  5708  5754 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-18 07:33:20.846  4607  4676 D BluetoothAdapterState: Current state: ON, message: 23
11-18 07:33:20.846  4607  4676 D BluetoothAdapterProperties: Setting state to 13
11-18 07:33:20.846  4607  4676 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 07:33:20.847  5708  5754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 07:33:20.847  4607  4676 D BluetoothAdapterProperties: onBluetoothDisable()
,11-18 07:33:20.847  5708  5754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 07:33:20.847  5708  5754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 07:33:20.848  4607  4676 I BluetoothAdapterState: Entering PendingCommandState
,11-18 07:33:20.850  4607  4607 D BluetoothMapService: onReceive
11-18 07:33:20.850  4607  4607 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-18 07:33:20.850  4607  4607 D BluetoothMapService: STATE_TURNING_OFF
11-18 07:33:20.850  4607  4607 D BluetoothMapService: MAP Service closeService in
11-18 07:33:20.850  4607  4607 D BluetoothMapMasInstance0: MAP Service shutdown
11-18 07:33:20.850  4607  4607 D ObexServerSockets0: shutdown(block = true)
,11-18 07:33:20.851  4607  4607 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 07:33:20.851  4607  4607 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 07:33:20.851  4607  4823 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-18 07:33:20.851  4607  4842 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-18 07:33:20.852  4607  4841 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-18 07:33:20.852  4607  4607 I BtOppRfcommListener: stopping Accept Thread
11-18 07:33:20.853  4607  5329 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-18 07:33:20.853  4607  5329 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-18 07:33:20.863   928   941 I ActivityManager: Start proc 5767:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-18 07:33:20.863  4607  4680 D BluetoothAdapterProperties: Scan Mode:20
,11-18 07:33:20.864  4607  4676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-18 07:33:20.868  4607  4607 D HeadsetService: Received stop request...Stopping profile...
,11-18 07:33:20.870   928   928 D BluetoothHeadset: Proxy object disconnected
,11-18 07:33:20.870  4607  4607 D A2dpService: Received stop request...Stopping profile...
11-18 07:33:20.870  4607  4833 D A2dpStateMachine: Exit Disconnected: -1
11-18 07:33:20.871  3806  3822 D BluetoothHeadset: Proxy object disconnected
,11-18 07:33:20.871  3144  3157 D BluetoothHeadset: Proxy object disconnected
11-18 07:33:20.871  3144  3144 D HeadsetProfile: Bluetooth service disconnected
11-18 07:33:20.871   928   928 D BluetoothHeadset: Proxy object disconnected
11-18 07:33:20.871   928   928 D BluetoothHeadset: Proxy object disconnected
11-18 07:33:20.872   928   928 D BluetoothA2dp: Proxy object disconnected
11-18 07:33:20.872  3144  3144 D BluetoothA2dp: Proxy object disconnected
,11-18 07:33:20.874  4607  4607 D HidService: Received stop request...Stopping profile...
11-18 07:33:20.875  4607  4607 D HidService: Stopping Bluetooth HidService
11-18 07:33:20.876  3144  3144 D BluetoothInputDevice: Proxy object disconnected
11-18 07:33:20.876  3144  3144 D HidProfile: Bluetooth service disconnected
11-18 07:33:20.876  4607  4607 D HealthService: Received stop request...Stopping profile...
11-18 07:33:20.879  4607  4607 V BluetoothAdapterState: isTurningOff()=true
11-18 07:33:20.879  4607  4607 V BluetoothAdapterState: isTurningOn()=false
11-18 07:33:20.879  4607  4607 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:20.879  4607  4607 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:20.880  4607  4607 D PanService: Received stop request...Stopping profile...
,11-18 07:33:20.880  3144  3144 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-18 07:33:20.880  3144  3144 D PanProfile: Bluetooth service disconnected
,11-18 07:33:20.882  4607  4607 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-18 07:33:20.883  4607  4607 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-18 07:33:20.883  4607  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 07:33:20.883  4607  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 07:33:20.883  4607  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 07:33:20.883  4607  4680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-18 07:33:20.883  4607  4680 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-18 07:33:20.883  4607  4607 D BluetoothMapService: Received stop request...Stopping profile...
11-18 07:33:20.883  4607  4607 D BluetoothMapService: stop()
,11-18 07:33:20.884  4607  4607 D BluetoothMapAppObserver: deinitObservers()
11-18 07:33:20.884  4607  4607 D BluetoothMapAppObserver: removeReceiver()
11-18 07:33:20.885  3144  3144 D BluetoothMap: Proxy object disconnected,
11-18 07:33:20.885  3144  3144 D MapProfile: Bluetooth service disconnected
11-18 07:33:20.885  4607  4607 V BluetoothAdapterState: isTurningOff()=true
,11-18 07:33:20.885  4607  4607 V BluetoothAdapterState: isTurningOn()=false
11-18 07:33:20.886  4607  4607 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:20.886  4607  4607 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:20.887  4607  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 07:33:20.887  4607  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 07:33:20.887  4607  4607 D SapService: Received stop request...Stopping profile...
11-18 07:33:20.888  4607  4607 V SapService: stop()
11-18 07:33:20.888  4607  4797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 07:33:20.888  4607  4680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-18 07:33:20.888  4607  4797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 07:33:20.888  4607  4797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 07:33:20.889  4607  4797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 07:33:20.889  4607  4607 V BluetoothAdapterState: isTurningOff()=true
11-18 07:33:20.889  4607  4607 V BluetoothAdapterState: isTurningOn()=false
11-18 07:33:20.889  4607  4607 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:20.889  4607  4607 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:20.889  4607  4607 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-18 07:33:20.889  4607  4607 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-18 07:33:20.890  4607  4607 V BluetoothAdapterState: isTurningOff()=true
11-18 07:33:20.890  4607  4607 V BluetoothAdapterState: isTurningOn()=false
,11-18 07:33:20.890  4607  4607 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:20.890  4607  4607 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:20.890  4607  4680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-18 07:33:20.891  4607  4607 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-18 07:33:20.891  4607  4680 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-18 07:33:20.891  4607  4607 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-18 07:33:20.892  4607  4607 V BluetoothAdapterState: isTurningOff()=true
11-18 07:33:20.892  4607  4607 V BluetoothAdapterState: isTurningOn()=false
11-18 07:33:20.892  4607  4607 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:20.892  4607  4607 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:20.892  4607  4607 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-18 07:33:20.892  4607  4607 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-18 07:33:20.893  4607  4607 D BluetoothMapService: MAP Service closeService in
11-18 07:33:20.893  4607  4607 V BluetoothAdapterState: isTurningOff()=true
11-18 07:33:20.893  4607  4607 V BluetoothAdapterState: isTurningOn()=false
11-18 07:33:20.893  4607  4607 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:20.893  4607  4607 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:20.893  4607  4607 D BluetoothMapService: cleanup()
,11-18 07:33:20.893  4607  4607 D BluetoothMapService: MAP Service closeService in
11-18 07:33:20.893  4607  4607 V BluetoothAdapterState: isTurningOff()=true
11-18 07:33:20.894  4607  4607 V BluetoothAdapterState: isTurningOn()=false
11-18 07:33:20.894  4607  4607 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:20.894  4607  4607 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:20.894  4607  4676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-18 07:33:20.894  4607  4676 D BluetoothAdapterProperties: Setting state to 15
11-18 07:33:20.894  4607  4676 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-18 07:33:20.894  4607  4676 I BluetoothAdapterState: Entering BleOnState
11-18 07:33:20.896  3144  3987 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 07:33:20.897  3144  3156 D BluetoothPbap: onBluetoothStateChange: up=false
,11-18 07:33:20.901  3144  3157 D BluetoothPan: onBluetoothStateChange on: false
11-18 07:33:20.901  3806  4039 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 07:33:20.902   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 07:33:20.902   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-18 07:33:20.902  3144  3987 D BluetoothMap: onBluetoothStateChange: up=false
11-18 07:33:20.902   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 07:33:20.903  3144  3156 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-18 07:33:20.903  3144  3157 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 07:33:20.904   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 07:33:20.904  4607  4676 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-18 07:33:20.904  4607  4676 D BluetoothAdapterProperties: Setting state to 16
11-18 07:33:20.904  4607  4676 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-18 07:33:20.905  4607  4676 D BluetoothAdapterProperties: onBleDisable
11-18 07:33:20.905  4607  4676 I BluetoothAdapterState: Entering PendingCommandState
11-18 07:33:20.905  4607  4677 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-18 07:33:20.906  4607  4797 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-18 07:33:20.906  4607  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-18 07:33:20.908  4607  4680 D BluetoothAdapterProperties: Scan Mode:20
,11-18 07:33:20.912  5767  5767 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-18 07:33:20.927  5767  5767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 07:33:20.932   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dda538:true
11-18 07:33:20.932  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 07:33:20.945   928  3413 I ActivityManager: Start proc 5779:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-18 07:33:20.958  5767  5767 D LocalBluetoothProfileManager: Adding local MAP profile
,11-18 07:33:20.961  5767  5767 D BluetoothMap: Create BluetoothMap proxy object
,11-18 07:33:20.975  5767  5767 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-18 07:33:20.982  5779  5779 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-18 07:33:20.987  5767  5767 D DockEventReceiver: finishStartingService: stopping service
,11-18 07:33:20.996   928  3615 I ActivityManager: Killing 4995:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-18 07:33:21.114  4607  4680 I bt_hci  : shut_down
,11-18 07:33:21.118  4607  4684 D bt_hwcfg: hw_epilog_process
,11-18 07:33:21.118  4607  4684 I bt_vendor: low_power_mode_cb
,11-18 07:33:21.121  4607  4684 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-18 07:33:21.121  4607  4684 I bt_vendor: epilog_cb
11-18 07:33:21.121  4607  4684 I bt_hci  : epilog_finished_callback
,11-18 07:33:21.123  4607  4680 I bt_hci_h4: hal_close
,11-18 07:33:21.123  4607  4680 I bt_userial_vendor: device fd = 54 close
,11-18 07:33:21.195  5779  5779 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 07:33:21.195  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-18 07:33:21.196  5779  5779 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-18 07:33:21.196  5779  5779 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 07:33:21.196  5779  5779 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 07:33:21.196  5,779  5779 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 07:33:21.196  5779  5779 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.k.d(PG:583)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 0,7:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 07:33:21.196  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 07:33:21.209  5779  5779 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 07:33:21.209  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 07:33:21.210  5779  5779 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 07:33:21.210  5779  5779 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 07:33:21.210  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 07:33:21.225  5767  5767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-18 07:33:21.231  4607  4677 D bt_stack_manager: event_shut_down_stack finished.
,11-18 07:33:21.231  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 07:33:21.231  4607  4676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-18 07:33:21.234  4607  4676 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-18 07:33:21.234  4607  4607 D BtGatt.DebugUtils: handleDebugAction() action=null
11-18 07:33:21.235  4607  4607 D BtGatt.GattService: Received stop request...Stopping profile...
11-18 07:33:21.235  4607  4607 D BtGatt.GattService: stop()
11-18 07:33:21.235  4607  4607 D BtGatt.AdvertiseManager: advertise clients cleared
11-18 07:33:21.237  4607  4607 V BluetoothAdapterState: isTurningOff()=false
11-18 07:33:21.237  4607  4607 V BluetoothAdapterState: isTurningOn()=false
11-18 07:33:21.237  4607  4607 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:21.237  4607  4607 V BluetoothAdapterState: isBleTurningOff()=true
11-18 07:33:21.238  4607  4676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-18 07:33:21.238  4607  4676 D BluetoothAdapterProperties: Setting state to 10
11-18 07:33:21.238  4607  4676 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-18 07:33:21.238  4607  4676 I BluetoothAdapterState: Entering OffState
11-18 07:33:21.239   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-18 07:33:21.241  5767  5767 D DockEventReceiver: finishStartingService: stopping service
11-18 07:33:21.242   928  3413 I ActivityManager: Killing 5144:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-18 07:33:21.273  4607  4607 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-18 07:33:21.273  4607  4607 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-18 07:33:21.273  4607  4607 I BluetoothServiceJni: cleanupNative: return from cleanup
11-18 07:33:21.275  4607  4677 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-18 07:33:21.280  4607  4607 I art     : System.exit called, status: 0
,11-18 07:33:21.280  4607  4607 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-18 07:33:21.318  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 07:33:21.324   928  3413 I ActivityManager: Process com.android.bluetooth (pid 4607) has died
,11-18 07:33:21.348  5708  5765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 07:33:21.349  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 07:33:21.349  5708  5765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 07:33:21.349  5708  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 07:33:21.352  5708  5754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 07:33:21.363   928   945 I ActivityManager: Start proc 5812:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-18 07:33:21.405  5779  5811 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-18 07:33:21.419  5812  5812 D AdapterServiceConfig: Adding HeadsetService
,11-18 07:33:21.419  5812  5812 D AdapterServiceConfig: Adding A2dpService
11-18 07:33:21.419  5812  5812 D AdapterServiceConfig: Adding HidService
11-18 07:33:21.419  5812  5812 D AdapterServiceConfig: Adding HealthService
11-18 07:33:21.420  5812  5812 D AdapterServiceConfig: Adding PanService
11-18 07:33:21.420  5812  5812 D AdapterServiceConfig: Adding GattService
11-18 07:33:21.420  5812  5812 D AdapterServiceConfig: Adding BluetoothMapService
11-18 07:33:21.420  5812  5812 D AdapterServiceConfig: Adding SapService
,11-18 07:33:21.431   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77f64ac:true
,11-18 07:33:21.431  5812  5812 D BluetoothAdapterState: make() - Creating AdapterState
,11-18 07:33:21.434  5812  5812 I bt_bluedroid: init
,11-18 07:33:21.434  5812  5825 I BluetoothAdapterState: Entering OffState
,11-18 07:33:21.436  5812  5826 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-18 07:33:21.436  5812  5826 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-18 07:33:21.436  5812  5826 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-18 07:33:21.436  5812  5826 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-18 07:33:21.437  5812  5812 I bt_bluedroid: get_profile_interface socket
,11-18 07:33:21.438  5812  5829 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-18 07:33:21.438  5812  5812 I bt_bluedroid: get_profile_interface sdp
11-18 07:33:21.440  5812  5829 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 07:33:21.442  5812  5823 I bt_bluedroid: config_hci_snoop_log
,11-18 07:33:21.443   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-18 07:33:21.446  5812  5825 D BluetoothAdapterState: Current state: OFF, message: 0
,11-18 07:33:21.446  5812  5825 D BluetoothAdapterProperties: Setting state to 14
11-18 07:33:21.446  5812  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-18 07:33:21.448  5812  5825 D BluetoothBondStateMachine: make
,11-18 07:33:21.449  5812  5830 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-18 07:33:21.451  5812  5825 I BluetoothAdapterState: Entering PendingCommandState
,11-18 07:33:21.452  5812  5812 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-18 07:33:21.454  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
11-18 07:33:21.455  5812  5812 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-18 07:33:21.455  5812  5812 D BtGatt.GattService: Received start request. Starting profile...
11-18 07:33:21.455  5812  5812 D BtGatt.GattService: start()
11-18 07:33:21.456  5812  5812 I bt_bluedroid: get_profile_interface gatt
11-18 07:33:21.456  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
11-18 07:33:21.456  5812  5812 D BtGatt.AdvertiseManager: advertise manager created
,11-18 07:33:21.461  5812  5812 V BluetoothAdapterState: isTurningOff()=false
,11-18 07:33:21.461  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-18 07:33:21.461  5812  5812 V BluetoothAdapterState: isBleTurningOn()=true
11-18 07:33:21.461  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:21.461  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-18 07:33:21.462  5812  5825 I bt_bluedroid: bt_bluedroid
11-18 07:33:21.462  5812  5826 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-18 07:33:21.463  5812  5826 I bt_hci  : start_up
,11-18 07:33:21.467  5812  5826 I bt_vendor: alloc value 0xf41ab871
,11-18 07:33:21.467  5812  5826 I bt_vendor: init
11-18 07:33:21.467  5812  5826 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-18 07:33:21.468  5812  5826 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-18 07:33:21.483  5779  5803 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-18 07:33:21.495   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb0de2d:true
,11-18 07:33:21.576  5812  5826 D bt_hci  : start_up starting async portion
,11-18 07:33:21.577  5812  5833 I bt_hci  : event_finish_startup
11-18 07:33:21.577  5812  5833 I bt_hci_h4: hal_open
11-18 07:33:21.577  5812  5833 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-18 07:33:21.578  5812  5833 I bt_userial_vendor: device fd = 54 open
,11-18 07:33:21.576  5836  5836 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 07:33:21.590  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 07:33:21.592  5812  5833 D bt_hwcfg: Chipset BCM4358A3
,11-18 07:33:21.592  5812  5833 D bt_hwcfg: Target name = [BCM4358A3]
11-18 07:33:21.592  5812  5833 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-18 07:33:21.857  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 07:33:21.902  3579  5841 V NQFileLogger: [137] e.a: about to write to file
,11-18 07:33:21.905  3579  5841 V ProcessReports: [137] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-18 07:33:21.933  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-18 07:33:21.933  5812  5833 D bt_hwcfg: Settlement delay -- 100 ms
11-18 07:33:21.934  5812  5833 I bt_hwcfg: Setting fw settlement delay to 100 
,11-18 07:33:22.058  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 07:33:22.058  5812  5833 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-18 07:33:22.059  5812  5833 I bt_hwcfg: vendor lib fwcfg completed
11-18 07:33:22.059  5812  5833 I bt_vendor: firmware callback
11-18 07:33:22.059  5812  5833 I bt_hci  : firmware_config_callback
,11-18 07:33:22.064  5812  5843 I bt_btu  : btu_task pending for preload complete event
11-18 07:33:22.064  5812  5843 I bt_btu_task: Bluetooth chip preload is complete
11-18 07:33:22.064  5812  5843 I bt_btu  : btu_task received preload complete event
,11-18 07:33:22.067  5812  5843 I         : BTE_InitTraceLevels -- TRC_HCI
,11-18 07:33:22.067  5812  5843 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-18 07:33:22.067  5812  5843 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-18 07:33:22.067  5812  5843 I         : BTE_InitTraceLevels -- TRC_AVDT
11-18 07:33:22.067  5812  5843 I         : BTE_InitTraceLevels -- TRC_AVRC
11-18 07:33:22.067  5812  5843 I         : BTE_InitTraceLevels -- TRC_A2D
11-18 07:33:22.067  5812  5843 I         : BTE_InitTraceLevels -- TRC_BNEP
11-18 07:33:22.068  5812  5843 I         : BTE_InitTraceLevels -- TRC_BTM
11-18 07:33:22.068  5812  5843 I         : BTE_InitTraceLevels -- TRC_GAP
,11-18 07:33:22.068  5812  5843 I         : BTE_InitTraceLevels -- TRC_PAN
11-18 07:33:22.068  5812  5843 I         : BTE_InitTraceLevels -- TRC_SDP
11-18 07:33:22.068  5812  5843 I         : BTE_InitTraceLevels -- TRC_GATT
11-18 07:33:22.068  5812  5843 I         : BTE_InitTraceLevels -- TRC_SMP
11-18 07:33:22.068  5812  5843 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-18 07:33:22.068  5812  5843 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-18 07:33:22.140  5812  5843 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4129549
,11-18 07:33:22.140  5812  5843 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4129549 
,11-18 07:33:22.161  5812  5829 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-18 07:33:22.163  5812  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-18 07:33:22.163  5812  5829 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-18 07:33:22.166  5812  5829 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 07:33:22.169  5812  5829 D BluetoothAdapterProperties: Scan Mode:20
,11-18 07:33:22.170  5812  5829 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 07:33:22.170  5812  5829 D bt_hci  : do_postload posting postload work item
11-18 07:33:22.170  5812  5833 I bt_hci  : event_postload
11-18 07:33:22.170  5812  5833 I bt_vendor: sco_config_cb
11-18 07:33:22.170  5812  5833 I bt_hci  : sco_config_callback postload finished.
,11-18 07:33:22.172  5812  5829 D bt_bte_conf: Device ID record 1 : primary
11-18 07:33:22.172  5812  5829 D bt_bte_conf:   vendorId            = 000f
11-18 07:33:22.172  5812  5829 D bt_bte_conf:   vendorIdSource      = 0001
11-18 07:33:22.172  5812  5829 D bt_bte_conf:   product             = 1200
11-18 07:33:22.173  5812  5829 D bt_bte_conf:   version             = 1436
11-18 07:33:22.173  5812  5829 D bt_bte_conf:   clientExecutableURL = 
11-18 07:33:22.173  5812  5829 D bt_bte_conf:   serviceDescription  = 
11-18 07:33:22.173  5812  5829 D bt_bte_conf:   documentationURL    = 
11-18 07:33:22.173  5812  5829 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-18 07:33:22.173  5812  5826 D bt_stack_manager: event_start_up_stack finished
,11-18 07:33:22.174  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-18 07:33:22.174  5812  5825 D BluetoothAdapterProperties: Setting state to 15
11-18 07:33:22.174  5812  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-18 07:33:22.176  5812  5825 I BluetoothAdapterState: Entering BleOnState
,11-18 07:33:22.180  5812  5833 I bt_vendor: low_power_mode_cb
,11-18 07:33:22.182  5812  5825 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-18 07:33:22.182  5812  5825 D BluetoothAdapterProperties: Setting state to 11
11-18 07:33:22.182  5812  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-18 07:33:22.191  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
,11-18 07:33:22.191  5812  5812 D HeadsetService: Received start request. Starting profile...
,11-18 07:33:22.195  5812  5812 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-18 07:33:22.198  5812  5812 D HeadsetStateMachine: make
,11-18 07:33:22.207  5812  5825 I BluetoothAdapterState: Entering PendingCommandState
,11-18 07:33:22.208  5812  5812 D HeadsetStateMachine: max_hf_connections = 1
,11-18 07:33:22.208  5812  5812 I bt_bluedroid: get_profile_interface handsfree
,11-18 07:33:22.208  5812  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-18 07:33:22.210  5812  5829 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-18 07:33:22.212  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
,11-18 07:33:22.213  5812  5812 D A2dpService: Received start request. Starting profile...
,11-18 07:33:22.214  5812  5812 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-18 07:33:22.214  5812  5812 I bt_bluedroid: get_profile_interface avrcp
,11-18 07:33:22.219  5812  5812 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-18 07:33:22.219  5812  5812 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-18 07:33:22.219  5812  5812 D A2dpStateMachine: make
,11-18 07:33:22.221  5812  5812 I bt_bluedroid: get_profile_interface a2dp
,11-18 07:33:22.223  5812  5851 D A2dpStateMachine: Enter Disconnected: -2
11-18 07:33:22.223  5812  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-18 07:33:22.223  5812  5812 I BluetoothHidServiceJni: classInitNative: succeeds
,11-18 07:33:22.224  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
,11-18 07:33:22.226  5767  5767 D BluetoothInputDevice: Proxy object connected
11-18 07:33:22.226  5812  5812 D HidService: Received start request. Starting profile...
11-18 07:33:22.226  5812  5812 I bt_bluedroid: get_profile_interface hidhost
11-18 07:33:22.226  5812  5812 D HidService: setHidService(): set to: null
11-18 07:33:22.226  5812  5829 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf410a56d
11-18 07:33:22.226  5812  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-18 07:33:22.226  5767  5767 D HidProfile: Bluetooth service connected
,11-18 07:33:22.228  5812  5812 I BluetoothHealthServiceJni: classInitNative: succeeds
11-18 07:33:22.229  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
11-18 07:33:22.229  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 07:33:22.229  5812  5812 D HealthService: Received start request. Starting profile...
,11-18 07:33:22.231  5812  5812 I bt_bluedroid: get_profile_interface health
11-18 07:33:22.232  5812  5812 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-18 07:33:22.233  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
,11-18 07:33:22.234  5767  5767 D BluetoothPan: BluetoothPAN Proxy object connected
,11-18 07:33:22.234  5812  5812 D PanService: Received start request. Starting profile...
11-18 07:33:22.234  5812  5812 D BluetoothPanServiceJni: initializeNative(L110): pan
11-18 07:33:22.234  5812  5812 I bt_bluedroid: get_profile_interface pan
11-18 07:33:22.234  5767  5767 D PanProfile: Bluetooth service connected
11-18 07:33:22.235  5812  5829 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-18 07:33:22.238  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
,11-18 07:33:22.239  5812  5812 D BluetoothMapService: Received start request. Starting profile...
,11-18 07:33:22.239  5812  5812 D BluetoothMapService: start()
11-18 07:33:22.242  5767  5767 D BluetoothMap: Proxy object connected
11-18 07:33:22.243  5767  5767 D MapProfile: Bluetooth service connected
11-18 07:33:22.243  5767  5767 D BluetoothMap: getConnectedDevices()
11-18 07:33:22.243  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-18 07:33:22.244  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-18 07:33:22.244  5812  5812 D BluetoothMapAppObserver: createReceiver()
11-18 07:33:22.246  5812  5812 D BluetoothMapAppObserver: initObservers()
11-18 07:33:22.246  5812  5812 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-18 07:33:22.251  5812  5812 V SapService: SapBinder()
,11-18 07:33:22.252  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
11-18 07:33:22.252  5812  5812 D SapService: Received start request. Starting profile...
11-18 07:33:22.252  5812  5812 V SapService: start()
11-18 07:33:22.253  5767  5767 D BluetoothMap: Bluetooth is Not enabled
,11-18 07:33:22.254  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-18 07:33:22.254  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-18 07:33:22.254  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:22.254  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 07:33:22.255  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-18 07:33:22.255  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-18 07:33:22.255  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:22.255  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:22.255  5812  5848 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-18 07:33:22.255  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-18 07:33:22.255  5812  5812 V BluetoothAdapterState: isTurningOn()=true
,11-18 07:33:22.255  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:22.255  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:22.256  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-18 07:33:22.256  5812  5812 V BluetoothAdapterState: isTurningOn()=true
,11-18 07:33:22.256  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:22.256  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:22.256  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-18 07:33:22.256  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-18 07:33:22.257  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:22.257  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-18 07:33:22.257  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-18 07:33:22.257  5812  5812 V BluetoothAdapterState: isTurningOn()=true
,11-18 07:33:22.257  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:22.257  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 07:33:22.258  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-18 07:33:22.258  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-18 07:33:22.258  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-18 07:33:22.258  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 07:33:22.258  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-18 07:33:22.258  5812  5825 D BluetoothAdapterProperties: ScanMode =  20
11-18 07:33:22.258  5812  5825 D BluetoothAdapterProperties: State =  11
,11-18 07:33:22.259  5812  5825 D BluetoothAdapterProperties: Setting state to 12
11-18 07:33:22.259  5812  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-18 07:33:22.259  5812  5825 I BluetoothAdapterState: Entering OnState
11-18 07:33:22.259  3144  3987 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 07:33:22.261  5812  5829 D BluetoothAdapterProperties: Scan Mode:21
11-18 07:33:22.262  5812  5829 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-18 07:33:22.263  3144  3156 D BluetoothPbap: onBluetoothStateChange: up=true
,11-18 07:33:22.264  3144  3144 D BluetoothA2dp: Proxy object connected
11-18 07:33:22.264  3144  3987 D BluetoothPan: onBluetoothStateChange on: true
11-18 07:33:22.266  3144  3144 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 07:33:22.266  3144  3144 D PanProfile: Bluetooth service connected
11-18 07:33:22.266  3806  3822 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-18 07:33:22.267  5767  5778 D BluetoothMap: onBluetoothStateChange: up=true
,11-18 07:33:22.267  5767  5777 D BluetoothPan: onBluetoothStateChange on: true
11-18 07:33:22.267  5767  5778 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 07:33:22.268   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 07:33:22.268   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 07:33:22.268  3144  3156 D BluetoothMap: onBluetoothStateChange: up=true
11-18 07:33:22.270   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 07:33:22.270  3144  3144 D BluetoothMap: Proxy object connected
11-18 07:33:22.270  3144  3144 D MapProfile: Bluetooth service connected
11-18 07:33:22.270  3144  3144 D BluetoothMap: getConnectedDevices()
11-18 07:33:22.270  5767  5777 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-18 07:33:22.270  3144  3157 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-18 07:33:22.271  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-18 07:33:22.272  5812  5812 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-18 07:33:22.272  3144  3987 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 07:33:22.272   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 07:33:22.272  3144  3144 D BluetoothInputDevice: Proxy object connected
11-18 07:33:22.272  3144  3144 D HidProfile: Bluetooth service connected
11-18 07:33:22.273   928   928 D BluetoothA2dp: Proxy object connected
11-18 07:33:22.274  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 07:33:22.277   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-18 07:33:22.278  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 07:33:22.279  5767  5767 D LocalBluetoothProfileManager: Adding local A2DP profile
11-18 07:33:22.279  5812  5812 D ObexServerSockets: Succeed to create listening sockets 
11-18 07:33:22.279  5812  5812 D ObexServerSockets0: startAccept()
11-18 07:33:22.279  5812  5812 D ObexServerSockets0: prepareForNewConnect()
,11-18 07:33:22.281  5812  5812 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-18 07:33:22.282  5812  5812 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-18 07:33:22.282  5812  5859 D ObexServerSockets0: Accepting socket connection...
11-18 07:33:22.282  5812  5858 D ObexServerSockets0: Accepting socket connection...
11-18 07:33:22.282  5812  5812 D BluetoothMapService: onReceive
,11-18 07:33:22.282  5812  5812 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 07:33:22.282  5812  5812 D BluetoothMapService: STATE_ON
,11-18 07:33:22.283  5767  5767 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-18 07:33:22.285  5812  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 07:33:22.287  5812  5860 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-18 07:33:22.287  5812  5860 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-18 07:33:22.289  5767  5767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 07:33:22.292  5767  5767 D BluetoothA2dp: Proxy object connected
,11-18 07:33:22.298  3579  3579 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 07:33:22.299  5767  5767 D DockEventReceiver: finishStartingService: stopping service
,11-18 07:33:22.305  5767  5767 D BluetoothPbap: Proxy object connected
11-18 07:33:22.305  3144  3144 D BluetoothPbap: Proxy object connected
,11-18 07:33:22.305  3144  3144 D PbapServerProfile: Bluetooth service connected
11-18 07:33:22.305  5767  5767 D PbapServerProfile: Bluetooth service connected
,11-18 07:33:22.313  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-18 07:33:22.313  5812  5812 D ObexServerSockets0: prepareForNewConnect()
11-18 07:33:22.315  5812  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 07:33:22.330  5812  5868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 07:33:22.331  5812  5868 I BtOppRfcommListener: Accept thread started.
,11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 07:33:22.359  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 07:33:22.361  5708  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 07:33:22.362  5708  5754 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-18 07:33:22.363   928  3155 D WifiService: setWifiEnabled: false pid=5708, uid=10077
,11-18 07:33:22.363   928  3155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 07:33:22.364   928  2975 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-18 07:33:22.364   928  2975 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-18 07:33:22.364   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 07:33:22.364   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 07:33:22.364  5708  5754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 07:33:22.369   928   945 D BluetoothHeadset: Proxy object connected
,11-18 07:33:22.369   928   928 D BluetoothHeadset: Proxy object connected
11-18 07:33:22.369   928   945 D BluetoothHeadset: Proxy object connected
11-18 07:33:22.369  3806  4039 D BluetoothHeadset: Proxy object connected
,11-18 07:33:22.370  3144  3157 D BluetoothHeadset: Proxy object connected
,11-18 07:33:22.370  3144  3144 D HeadsetProfile: Bluetooth service connected
11-18 07:33:22.370   928   945 D BluetoothHeadset: Proxy object connected
11-18 07:33:22.371   928   928 D BluetoothHeadset: Proxy object connected
11-18 07:33:22.371   928   928 D BluetoothHeadset: Proxy object connected
,11-18 07:33:22.373  3144  3987 D BluetoothHeadset: Proxy object connected
11-18 07:33:22.373  3144  3144 D HeadsetProfile: Bluetooth service connected
,11-18 07:33:22.374   928  5404 D DhcpClient: Clearing IP address
11-18 07:33:22.375   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-18 07:33:22.382   508   922 D CommandListener: Setting iface cfg
,11-18 07:33:22.382  3579  5460 V NativeCrypto: Read error: ssl=0x7f9a385700: I/O error during system call, Connection timed out
,11-18 07:33:22.384  3579  5460 V NativeCrypto: SSL shutdown failed: ssl=0x7f9a385700: I/O error during system call, Broken pipe
,11-18 07:33:22.386   928   939 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-18 07:33:22.386   928  5402 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-18 07:33:22.387  5767  5778 D BluetoothHeadset: Proxy object connected
11-18 07:33:22.388   928  5405 D DhcpClient: Receive thread stopped
11-18 07:33:22.394   928  5402 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-18 07:33:22.394  5767  5767 D HeadsetProfile: Bluetooth service connected
11-18 07:33:22.394   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-18 07:33:22.394   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-18 07:33:22.395   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-18 07:33:22.398   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-18 07:33:22.398   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-18 07:33:22.403   590   590 E Parcel  : Reading a NULL string not supported here.
,11-18 07:33:22.404   928   928 D RttService: SCAN_AVAILABLE : 1
,11-18 07:33:22.405   928  2977 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-18 07:33:22.405   928  3084 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 07:33:22.407  3774  3916 W QCNEJ   : |CORE| network lost: 100
11-18 07:33:22.407  3774  3916 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-18 07:33:22.417   928  2975 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-18 07:33:22.431   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 07:33:22.435   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 07:33:22.457   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 07:33:22.457   508   922 D CommandListener: Clearing all IP addresses on wlan0
11-18 07:33:22.458   928  2977 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-18 07:33:22.458   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-18 07:33:22.459   928   945 D Tethering: MasterInitialState.processMessage what=3
11-18 07:33:22.461   928  2975 D DhcpClient: doQuit
11-18 07:33:22.461   928  2975 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-18 07:33:22.462  3467  3467 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-18 07:33:22.463   928  5404 D DhcpClient: onQuitting
11-18 07:33:22.465  5316  5316 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5add6f7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-18 07:33:22.467  4948  4948 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-18 07:33:22.470  3759  3759 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-18 07:33:22.470  5062  5086 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-18 07:33:22.470  5062  5086 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 07:33:22.470  5062  5086 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-18 07:33:22.471  5062  5086 E SarControlService: no key has been found,reset the power
11-18 07:33:22.471  5062  5097 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 07:33:22.471  5062  5097 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 07:33:22.471  5062  5097 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 07:33:22.472  5087  5087 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 07:33:22.472  5087  5087 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 07:33:22.473  3759  3759 D SystemUpdateService: onCreate
11-18 07:33:22.475  5062  5097 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 07:33:22.475  5062  5097 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 07:33:22.475  5062  5097 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 07:33:22.477  5087  5087 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 07:33:22.477  5087  5087 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 07:33:22.477  3759  3759 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-18 07:33:22.480  3759  5877 I SystemUpdateService: active receiver: enabled
11-18 07:33:22.482  5087  5101 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@154d155 HexData = [00000000ea03000000000000ffffffff]
11-18 07:33:22.482  5087  5101 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 07:33:22.482  5087  5101 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-18 07:33:22.482  5087  5087 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 07:33:22.482  5062  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 07:33:22.483  3759  5877 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-18 07:33:22.487  3759  5877 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-18 07:33:22.487  3759  5877 I SystemUpdateService: now status is 0 (complete)
,11-18 07:33:22.487  3759  5877 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 07:33:22.487  3759  5877 I SystemUpdateService: file has been verified
11-18 07:33:22.488  3759  5877 I SystemUpdateService: OTA package size = 21989297
11-18 07:33:22.488  5087  5101 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@154d155 HexData = [00000000eb03000000000000ffffffff]
11-18 07:33:22.488  5087  5101 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 07:33:22.488  5087  5101 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-18 07:33:22.488  3759  3759 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-18 07:33:22.489  5087  5087 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 07:33:22.489  5062  5072 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-18 07:33:22.489  3467  3467 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-18 07:33:22.490  3759  5429 I iu.UploadsManager: num queued entries: 0
11-18 07:33:22.491  3759  5429 I iu.UploadsManager: num updated entries: 0
11-18 07:33:22.491  3759  5877 I SystemUpdateService: showing system update notification
,11-18 07:33:22.491  3759  5429 I iu.SyncManager: NEXT; no task
,11-18 07:33:22.496  3467  3467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-18 07:33:22.502  3759  3759 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-18 07:33:22.503  3759  3759 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-18 07:33:22.503  3759  3759 D SystemUpdateService: onDestroy
,11-18 07:33:22.514   928  3413 I ActivityManager: Start proc 5881:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-18 07:33:22.523   508   922 E Netd    : netlink response contains error (No such file or directory)
11-18 07:33:22.526   928  2977 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-18 07:33:22.526   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-18 07:33:22.531  3467  3467 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-18 07:33:22.546  3467  3467 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-18 07:33:22.551  5881  5881 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-18 07:33:22.552   928  2975 D wifi    : In wifi stop Hal
11-18 07:33:22.552   928  2975 D wifi    : halHandle = 0x7f83e03180, mVM = 0x7fa044d140, mCls = 0x100a02
11-18 07:33:22.552   928  3466 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-18 07:33:22.552   928  3466 D WifiHAL : Got a signal to exit!!!
11-18 07:33:22.552   928  3466 I WifiHAL : Exit wifi_event_loop
11-18 07:33:22.552  5036  5036 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 07:33:22.553   928  2975 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-18 07:33:22.553   928  2975 E WifiHAL : Event processing terminated
,11-18 07:33:22.553   928  2975 D wifi    : In wifi cleaned up handler
11-18 07:33:22.553   928  2975 I WifiHAL : Internal cleanup completed
11-18 07:33:22.554  4092  4227 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 07:33:22.556  5881  5881 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 07:33:22.563  5881  5881 D SprintDMHelper: simOperator: 
11-18 07:33:22.563  5881  5881 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 07:33:22.573   928  3466 D wifi    : set interface wlan0 flags (DOWN)
,11-18 07:33:22.573   928  2975 D WifiNative-HAL: HAL event thread stopped successfully
,11-18 07:33:22.576   928   939 I ActivityManager: Start proc 5893:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-18 07:33:22.637   508   922 E Netd    : netlink response contains error (No such file or directory)
,11-18 07:33:22.661  5036  5913 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-18 07:33:22.674   928  3856 I ActivityManager: Start proc 5914:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-18 07:33:22.676   928  3413 I ActivityManager: Killing 5480:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-18 07:33:22.711  5914  5914 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-18 07:33:22.719   928   938 I ActivityManager: Killing 5316:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-18 07:33:22.775   928   945 D Tethering: InitialState.processMessage what=4
,11-18 07:33:22.778   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 07:33:22.872  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 07:33:22.877  5708  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-18 07:33:22.880   928  3413 D WifiService: setWifiEnabled: true pid=5708, uid=10077
11-18 07:33:22.881   928  3413 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 07:33:22.882  5708  5754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 07:33:22.890   508   922 D SoftapController: Softap fwReload - Ok
,11-18 07:33:22.894   508   922 D CommandListener: Setting iface cfg
,11-18 07:33:22.895   508   922 D CommandListener: Trying to bring down wlan0
11-18 07:33:22.896   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-18 07:33:22.901   928  2975 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 07:33:23.391   928  3158 D WifiService: setWifiEnabled: true pid=5708, uid=10077
,11-18 07:33:23.393   928  3158 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 07:33:23.496   928  2975 D wifi    : set interface wlan0 flags (UP)
11-18 07:33:23.497   928  2975 I WifiHAL : Initializing wifi
,11-18 07:33:23.497   928  2975 I WifiHAL : Creating socket
,11-18 07:33:23.504   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-18 07:33:23.512   928  2975 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-18 07:33:23.513   928  2975 D wifi    : Did set static halHandle = 0x7f83e03180
11-18 07:33:23.513   928  2975 D wifi    : halHandle = 0x7f83e03180, mVM = 0x7fa044d140, mCls = 0x1992
11-18 07:33:23.513   928  2975 D wifi    : array field set
11-18 07:33:23.514   928  2975 I WifiNative-HAL: interface[0] = wlan0
11-18 07:33:23.515   928  5931 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547673354624
11-18 07:33:23.515   928  5931 D wifi    : waitForHalEvents called, vm = 0x7fa044d140, obj = 0x1992, env = 0x7f83e7d780
,11-18 07:33:23.581  5932  5932 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-18 07:33:23.603  5932  5932 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 07:33:23.616   928  2975 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-18 07:33:23.632  5932  5932 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 07:33:23.632  5932  5932 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-18 07:33:23.649   928  2975 D WifiConfigStore: Loading config and enabling all networks 
,11-18 07:33:23.661   928  2975 D WifiConfigStore: loaded 0 passpoint configs
,11-18 07:33:23.662   928  2975 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-18 07:33:23.662   928  2975 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-18 07:33:23.663   928  2975 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-18 07:33:23.664   928  2975 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-18 07:33:23.665   928  2975 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-18 07:33:23.665   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-18 07:33:23.665   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-18 07:33:23.669   928  2975 D WifiNative-HAL: Setting external_sim to 1
,11-18 07:33:23.669  5036  5036 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 07:33:23.669   928  2975 D wifi    : setting dfs flag to true, 0x7f89baea60
11-18 07:33:23.670   928  2975 D WifiStateMachine: Setting OUI to DA-A1-19
11-18 07:33:23.670   928  2975 D wifi    : setting scan oui 0x7f89baea60
11-18 07:33:23.670   928  2975 D WifiHAL : Sending mac address OUI
,11-18 07:33:23.674   928  2975 E native  : do suspend false
,11-18 07:33:23.681   928  2975 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-18 07:33:23.681   928   928 D RttService: SCAN_AVAILABLE : 3
11-18 07:33:23.681   928  3084 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 07:33:23.685   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-18 07:33:23.686   508   922 D CommandListener: Setting iface cfg
,11-18 07:33:23.689   928  2974 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-18 07:33:23.689   928  2974 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-18 07:33:23.694   928  2974 D WifiNative-HAL: p2pGetDeviceAddress
,11-18 07:33:23.698   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=225425 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
11-18 07:33:23.698   928  2974 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 07:33:23.908  5708  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 07:33:23.917  5708  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 07:33:23.921  5708  5754 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 07:33:23.922   928  3615 D WifiService: setWifiEnabled: true pid=5708, uid=10077
11-18 07:33:23.922   928  3615 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 07:33:23.923  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 07:33:23.923  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 07:33:23.923  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 07:33:23.923  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfbd5e4 removed from the list
11-18 07:33:23.923  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-18 07:33:23.923  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bdba4d removed from the list
11-18 07:33:23.923  5708  5754 D io.jxcore.node.ConnectivityMonitor: stop
11-18 07:33:23.926  5708  5754 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-18 07:33:23.928  5708  5754 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-18 07:33:23.929  5708  5754 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-18 07:33:23.931  5708  5754 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-18 07:33:23.933  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-18 07:33:23.934  5708  5754 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-18 07:33:23.935  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-18 07:33:23.935  5708  5754 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-18 07:33:23.938  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-18 07:33:23.941  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-18 07:33:23.941  5708  5754 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e17c609 Bundle[{}]
11-18 07:33:23.942  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-18 07:33:23.942  5708  5754 I io.jxcore.node.LifeCycleMonitor: start: OK
11-18 07:33:23.942  5708  5754 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-18 07:33:23.942  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-18 07:33:23.943  5708  5754 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-18 07:33:23.943  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-18 07:33:23.943  5708  5754 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-18 07:33:23.943  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-18 07:33:23.944  5708  5754 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-18 07:33:23.944  5708  5754 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-18 07:33:23.945  5708  5754 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-18 07:33:23.946  5708  5754 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-18 07:33:23.948  5708  5754 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-18 07:33:23.949  5708  5754 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-18 07:33:23.950  5708  5754 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-18 07:33:23.951  5708  5754 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-18 07:33:23.952  5708  5754 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-18 07:33:23.954  5708  5754 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-18 07:33:23.955  5708  5754 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-18 07:33:23.955  5708  5754 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-18 07:33:23.957  5708  5754 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-18 07:33:23.958  5708  5754 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-18 07:33:23.959  5708  5754 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-18 07:33:23.959  5708  5754 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,11-18 07:33:23.960  5708  5754 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-18 07:33:23.961  5708  5754 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-18 07:33:23.961  5708  5754 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-18 07:33:23.961  5708  5754 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-18 07:33:23.962  5708  5754 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-18 07:33:23.963  5708  5754 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-18 07:33:23.963  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 07:33:23.963  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179d213 added. We now have 3 listener(s)
,11-18 07:33:23.965  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:23.965  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 07:33:23.965  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 07:33:23.965  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 07:33:23.965  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c926c50 added. We now have 3 listener(s)
11-18 07:33:23.966  5708  5754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 07:33:23.966  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 07:33:23.971  5708  5754 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-18 07:33:23.972  5708  5754 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-18 07:33:23.972  5708  5754 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-18 07:33:23.972  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-18 07:33:23.973  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:23.973  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:23.973  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:23.973  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:23.973  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 07:33:23.973  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 07:33:23.973  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 07:33:23.973  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-18 07:33:23.976  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 07:33:23.977  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 07:33:23.977  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 07:33:23.977  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 07:33:23.977  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 07:33:23.977  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-18 07:33:23.977  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 07:33:23.977  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 07:33:23.977  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 07:33:23.977  5708  5944 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 07:33:23.980  5708  5944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 07:33:23.979  5822  5822 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31524]" dev="sockfs" ino=31524 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:23.981  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 07:33:23.982  5708  5754 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 07:33:23.982  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 07:33:23.982  5708  5944 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 07:33:23.979  5822  5822 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31524]" dev="sockfs" ino=31524 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 07:33:23.986  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:23.986  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 07:33:23.987  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 07:33:23.987  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 07:33:23.987  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 07:33:23.989  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:23.989  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:23.989  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 07:33:23.989  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 07:33:23.989  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:23.989  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
11-18 07:33:23.989  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:23.989  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:23.989  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:23.989  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 07:33:23.989  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 07:33:23.990  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:23.990  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:23.990  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:23.990  5708  5754 D BluetoothAdapter: STATE_ON
,11-18 07:33:23.993  5812  5823 D BtGatt.GattService: registerClient() - UUID=47b0a2f9-afb4-40f3-ba3a-551a0f23a3c5
11-18 07:33:23.994  5812  5829 D BtGatt.GattService: onClientRegistered() - UUID=47b0a2f9-afb4-40f3-ba3a-551a0f23a3c5, clientIf=5
,11-18 07:33:23.995  5708  5718 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 07:33:23.997  5812  5831 D BtGatt.AdvertiseManager: message : 0
,11-18 07:33:23.999  5812  5831 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 07:33:24.003  5812  5829 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 07:33:24.005  5812  5829 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 07:33:24.005  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:24.005  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.005  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 07:33:24.005  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.006  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.006  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.006  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.006  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.006  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 07:33:24.007  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 07:33:24.007  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:24.008  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.008  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.008  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:24.008  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.009  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.009  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.009  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 07:33:24.010  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.012  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 07:33:24.012  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 07:33:24.013  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.013  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.013  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:24.013  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 07:33:24.514  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 07:33:24.514  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 07:33:24.514  5708  5708 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 07:33:25.920   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:26.745  5932  5932 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 07:33:26.750  5932  5932 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 07:33:26.756  5932  5932 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 07:33:26.812   928  2975 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-18 07:33:26.813   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-18 07:33:26.813   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 07:33:26.825   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-18 07:33:26.860   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-18 07:33:26.862  5932  5932 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-18 07:33:26.876   928  3413 I ActivityManager: Killing 4690:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-18 07:33:26.921   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:27.298  5932  5932 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-18 07:33:27.331  5932  5932 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-18 07:33:27.332  5932  5932 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-18 07:33:27.342   928  2975 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 07:33:27.342   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 07:33:27.343   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-18 07:33:27.358   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 07:33:27.368   508   922 D CommandListener: Setting iface cfg
,11-18 07:33:27.374   928  2975 D WifiStateMachine: Start Dhcp Watchdog 2
,11-18 07:33:27.380   928  5951 D DhcpClient: Receive thread started
,11-18 07:33:27.385   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 07:33:27.385   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-18 07:33:27.385   928  2977 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-18 07:33:27.466   928  2975 E native  : do suspend false
,11-18 07:33:27.479   928  5950 D DhcpClient: Broadcasting DHCPDISCOVER
,11-18 07:33:27.511  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-18 07:33:27.511  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 07:33:27.511  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 07:33:27.511  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 07:33:27.511  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 07:33:27.512  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 07:33:27.512  5708  5944 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 07:33:27.512  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 07:33:27.512  5708  5944 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 07:33:27.512  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 07:33:27.512  5708  5944 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 07:33:27.512  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 07:33:27.512  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 07:33:27.512  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-18 07:33:27.512  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 07:33:27.512  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 07:33:27.512  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.512  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.513  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:27.513  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.514  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:27.514  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-18 07:33:27.516  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:27.516  5708  5754 D BluetoothLeScanner: could not find callback wrapper
11-18 07:33:27.516  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-18 07:33:27.516  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.516  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.516  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.517  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 07:33:27.517  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.518  5812  5831 D BtGatt.AdvertiseManager: message : 1
11-18 07:33:27.519  5812  5831 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 07:33:27.534  5812  5829 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 07:33:27.535  5812  5829 D BtGatt.GattService: Client app is not null!
11-18 07:33:27.537  5812  5856 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 07:33:27.538  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 07:33:27.538  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.538  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 07:33:27.538  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.539  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.539  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.539  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-18 07:33:27.539  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 07:33:27.540  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 07:33:27.542  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.544  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.544  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:27.544  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.544  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.544  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 07:33:27.544  5708  5708 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 07:33:27.544  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 07:33:27.545  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 07:33:27.545  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 07:33:27.545  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 07:33:27.545  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:27.545  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.545  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 07:33:27.545  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 07:33:27.545  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.545  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.546  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 07:33:27.546  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.548  5708  5754 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-18 07:33:27.548  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 07:33:27.548  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.548  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.548  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.548  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.549  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:27.549  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 07:33:27.549  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-18 07:33:27.549  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-18 07:33:27.549  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 07:33:27.549  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-18 07:33:27.552  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 07:33:27.556  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 07:33:27.556  5708  5754 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 07:33:27.556  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 07:33:27.561  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.561  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 07:33:27.562  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 07:33:27.563  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 07:33:27.563  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-18 07:33:27.566  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-18 07:33:27.569  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-18 07:33:27.569  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.569  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 07:33:27.570  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 07:33:27.570  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 07:33:27.570  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 07:33:27.571  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.571  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:27.574  5812  5822 D BtGatt.GattService: registerClient() - UUID=cbd1283f-2a57-4d8d-8609-fecd0aa8354a
11-18 07:33:27.574  5812  5829 D BtGatt.GattService: onClientRegistered() - UUID=cbd1283f-2a57-4d8d-8609-fecd0aa8354a, clientIf=5
11-18 07:33:27.575  5708  5718 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-18 07:33:27.576  5812  5823 D BtGatt.GattService: start scan with filters
11-18 07:33:27.579  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-18 07:33:27.579  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.579  5812  5832 D BtGatt.ScanManager: handling starting scan
11-18 07:33:27.579  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 07:33:27.580  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.581  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 07:33:27.581  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:27.581  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 07:33:27.581  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 07:33:27.581  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 07:33:27.581  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.581  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.581  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-18 07:33:27.582  5812  5832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef49c2
11-18 07:33:27.582  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 07:33:27.582  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.585  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.585  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 07:33:27.585  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.585  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:27.585  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.587  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.587  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.587  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.587  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:27.588  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 07:33:27.588  5812  5829 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-18 07:33:27.589  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:27.589  5812  5832 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-18 07:33:27.594  5812  5829 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-18 07:33:27.594  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:27.594  5812  5832 D BtGatt.ScanManager: Starting BLE batch scan
11-18 07:33:27.594  5812  5832 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-18 07:33:27.602  5812  5829 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-18 07:33:27.602  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:27.608  5812  5829 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-18 07:33:27.608  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 07:33:27.922   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:28.088  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-18 07:33:28.089  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 07:33:28.089  5708  5708 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 07:33:28.923   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:29.159   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-18 07:33:29.327   928  5950 D DhcpClient: Broadcasting DHCPDISCOVER
,11-18 07:33:29.342   928  5951 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
,11-18 07:33:29.343   928  5950 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-18 07:33:29.349  5812  5812 D BtGatt.ScanManager: awakened up at time 231076
11-18 07:33:29.350   928  5950 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-18 07:33:29.352  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 07:33:29.374   928  5951 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-18 07:33:29.374   928  5950 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-18 07:33:29.378   508   922 D CommandListener: Setting iface cfg
,11-18 07:33:29.382  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-18 07:33:29.382  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 07:33:29.383  5812  5829 D BtGatt.GattService: current time is 231109911869
,11-18 07:33:29.383   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[]
11-18 07:33:29.384  5812  5829 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -40, 59, 48, -73, 85, 115, 1, -128, -60, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 81, 34, 97, 112, -14, -5, 1, -128, -75, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
11-18 07:33:29.387   928  5950 D DhcpClient: Scheduling renewal in 86399s
,11-18 07:33:29.390  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-18 07:33:29.392  5812  5829 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
,11-18 07:33:29.392  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-18 07:33:29.392  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,11-18 07:33:29.396   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_NONE]
,11-18 07:33:29.397   928  2975 D WifiConfigStore: No blacklist allowed without epno enabled
11-18 07:33:29.397  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 4. Current thread: Thread[main,5,main], id: 1
,11-18 07:33:29.398   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-18 07:33:29.398  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=73:55:B7:30:3B:D8, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=229611171557}
11-18 07:33:29.398  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=73:55:B7:30:3B:D8, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=229611171557}
,11-18 07:33:29.400  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
,11-18 07:33:29.401  5708  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-18 07:33:29.401  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 5]
11-18 07:33:29.401   928  2975 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-18 07:33:29.401  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5]
11-18 07:33:29.402  5708  5708 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 5]
,11-18 07:33:29.402  5708  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
11-18 07:33:29.402  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [<no peer name> A8:81:95:E9:5F:6F 5]
11-18 07:33:29.403  5708  5708 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 5], added - the peer count is 1
11-18 07:33:29.404  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=230311171557}
11-18 07:33:29.404  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=230311171557}
11-18 07:33:29.404  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=229611171557}
11-18 07:33:29.404  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=229611171557}
11-18 07:33:29.405  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
,11-18 07:33:29.405  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-18 07:33:29.405  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-72, mTimestampNanos=229361171557}
11-18 07:33:29.405  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-72, mTimestampNanos=229361171557}
11-18 07:33:29.406  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
11-18 07:33:29.406  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-18 07:33:29.406  5708  5708 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
11-18 07:33:29.407   928  2977 D ConnectivityService: Adding iface wlan0 to network 101
,11-18 07:33:29.446   928  2977 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-18 07:33:29.446   928  2977 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-18 07:33:29.447   928  2977 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-18 07:33:29.449   928  2977 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-18 07:33:29.450   928  2977 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-18 07:33:29.455   928  2977 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 07:33:29.458   928  2977 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-18 07:33:29.459   928  2977 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-18 07:33:29.459   928  2977 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-18 07:33:29.459   928  2977 D ConnectivityService:    accepting network in place of null
11-18 07:33:29.459   928  2975 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-18 07:33:29.459   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 07:33:29.459   928  2977 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 07:33:29.478   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 07:33:29.487   928  5949 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231213, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-18 07:33:29.499   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 07:33:29.503   928  2977 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-18 07:33:29.503  3774  3916 W QCNEJ   : |CORE| network available: 101
11-18 07:33:29.503   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-18 07:33:29.504   928  2977 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-18 07:33:29.504   928   945 D Tethering: MasterInitialState.processMessage what=3
11-18 07:33:29.507  3774  3916 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-18 07:33:29.508  3774  3916 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-18 07:33:29.508  3774  3916 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-18 07:33:29.517  5062  5086 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-18 07:33:29.518  5062  5086 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 07:33:29.518  5062  5086 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-18 07:33:29.518  5062  5086 E SarControlService: no key has been found,reset the power
11-18 07:33:29.518  5062  5097 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 07:33:29.518  5062  5097 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 07:33:29.518  5062  5097 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 07:33:29.518  5087  5087 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-18 07:33:29.519  5087  5087 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 07:33:29.520  4948  4948 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-18 07:33:29.521  5062  5097 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 07:33:29.521  5062  5097 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 07:33:29.521  5062  5097 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 07:33:29.522  5087  5087 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 07:33:29.522  5087  5087 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-18 07:33:29.524  3759  3759 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-18 07:33:29.525  5087  5101 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@154d155 HexData = [00000000ec03000000000000ffffffff]
11-18 07:33:29.525  5087  5101 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 07:33:29.525  5087  5101 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-18 07:33:29.525  5087  5087 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 07:33:29.526  5062  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 07:33:29.527  5087  5101 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@154d155 HexData = [00000000ed03000000000000ffffffff]
11-18 07:33:29.527  5087  5101 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 07:33:29.527  5087  5101 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-18 07:33:29.528  5087  5087 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 07:33:29.528  5062  5072 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-18 07:33:29.532  3759  3759 D SystemUpdateService: onCreate
,11-18 07:33:29.536  3759  3759 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 07:33:29.546  3759  3759 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-18 07:33:29.550  3759  5962 I SystemUpdateService: active receiver: enabled
,11-18 07:33:29.553  3759  5429 I iu.UploadsManager: num queued entries: 0
,11-18 07:33:29.553  3759  5429 I iu.UploadsManager: num updated entries: 0
11-18 07:33:29.554  3759  5429 I iu.SyncManager: NEXT; no task
,11-18 07:33:29.557   928  5948 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-18 07:33:29.560  3759  3759 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-18 07:33:29.562  3759  3759 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 07:33:29.563  5881  5881 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 07:33:29.567  5881  5881 D SprintDMHelper: simOperator: 
,11-18 07:33:29.567  5881  5881 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 07:33:29.587  3759  5962 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 07:33:29.600  3759  5962 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-18 07:33:29.600  3759  5962 I SystemUpdateService: now status is 0 (complete)
,11-18 07:33:29.601  3759  5962 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-18 07:33:29.601  3759  5962 I SystemUpdateService: file has been verified
11-18 07:33:29.601  3759  5962 I SystemUpdateService: OTA package size = 21989297
,11-18 07:33:29.609  3759  5962 I SystemUpdateService: showing system update notification
,11-18 07:33:29.617  3759  3759 D SystemUpdateService: onDestroy
,11-18 07:33:29.639   928  5948 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Nov 2016 12:33:29 GMT], X-Android-Received-Millis=[1479472409638], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479472409606]}
,11-18 07:33:29.640   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-18 07:33:29.640   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-18 07:33:29.640   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-18 07:33:29.641   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 07:33:29.720  5036  5967 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-18 07:33:29.888  5812  5812 D BtGatt.ScanManager: awakened up at time 231615
,11-18 07:33:29.890  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 07:33:29.905  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 07:33:29.905  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:29.907  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-18 07:33:29.924   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:30.411  5812  5812 D BtGatt.ScanManager: awakened up at time 232137
,11-18 07:33:30.417  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 07:33:30.428  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 07:33:30.428  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:30.429  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-18 07:33:30.503   928  2977 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-18 07:33:30.588  5708  5754 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-18 07:33:30.588  5708  5754 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-18 07:33:30.588  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-18 07:33:30.589  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:30.589  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.589  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 07:33:30.590  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:30.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
,11-18 07:33:30.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.590  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.591  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 07:33:30.591  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 07:33:30.591  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:30.591  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.591  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.594  5708  5754 D BluetoothAdapter: STATE_ON
,11-18 07:33:30.595  5812  5849 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 07:33:30.596  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 07:33:30.597  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 07:33:30.598  5708  5754 D BluetoothAdapter: STATE_ON
,11-18 07:33:30.600  5812  5823 D BtGatt.GattService: stopScan() - queue size =1
11-18 07:33:30.606  5812  5857 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 07:33:30.607  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 07:33:30.607  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.607  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 07:33:30.607  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.607  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 07:33:30.607  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:30.607  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.607  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 07:33:30.608  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 07:33:30.608  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 07:33:30.608  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 07:33:30.608  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.609  5708  5754 D BluetoothAdapter: STATE_ON
,11-18 07:33:30.610  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-18 07:33:30.610  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:30.610  5812  5829 E BtGatt.ContextMap: Context not found for ID 5
,11-18 07:33:30.614  5812  5823 D BtGatt.GattService: registerClient() - UUID=246ba965-9426-4ca6-822b-c85272a4d642
11-18 07:33:30.615  5812  5829 D BtGatt.GattService: onClientRegistered() - UUID=246ba965-9426-4ca6-822b-c85272a4d642, clientIf=5
,11-18 07:33:30.616  5708  5718 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-18 07:33:30.617  5812  5856 D BtGatt.GattService: start scan with filters
,11-18 07:33:30.621  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-18 07:33:30.621  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.621  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 07:33:30.621  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.621  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.621  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:30.621  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:30.621  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.621  5708  5754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 07:33:30.621  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 07:33:30.621  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 07:33:30.621  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 07:33:30.622  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 07:33:30.622  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.622  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.622  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 07:33:30.623  5812  5829 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-18 07:33:30.623  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:30.623  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 07:33:30.623  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 07:33:30.623  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 07:33:30.623  5812  5832 D BtGatt.ScanManager: stopping BLe Batch
11-18 07:33:30.623  5708  5974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 07:33:30.624  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 07:33:30.624  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-18 07:33:30.624  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-18 07:33:30.624  5708  5974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 07:33:30.625  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 07:33:30.625  5708  5754 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-18 07:33:30.626  5857  5857 W Binder_5: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33533]" dev="sockfs" ino=33533 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 07:33:30.626  5857  5857 W Binder_5: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33533]" dev="sockfs" ino=33533 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 07:33:30.629  5708  5974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 07:33:30.630  5812  5829 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-18 07:33:30.630  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:30.630  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 07:33:30.633  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:30.633  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.633  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.633  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 07:33:30.633  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 07:33:30.633  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 07:33:30.633  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
,11-18 07:33:30.634  5708  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:30.634  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:30.634  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.634  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 07:33:30.634  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 07:33:30.634  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.634  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.634  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:30.635  5708  5754 D BluetoothAdapter: STATE_ON
,11-18 07:33:30.636  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-18 07:33:30.636  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 07:33:30.638  5812  5857 D BtGatt.GattService: registerClient() - UUID=f648e340-d033-4ea7-9b78-b0884afe60a9
11-18 07:33:30.638  5812  5832 D BtGatt.ScanManager: handling starting scan
11-18 07:33:30.638  5812  5829 D BtGatt.GattService: onClientRegistered() - UUID=f648e340-d033-4ea7-9b78-b0884afe60a9, clientIf=6
,11-18 07:33:30.639  5708  5719 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-18 07:33:30.640  5812  5831 D BtGatt.AdvertiseManager: message : 0
,11-18 07:33:30.644  5812  5829 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-18 07:33:30.644  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:30.644  5812  5831 D BtGatt.AdvertiseManager: starting multi advertising
11-18 07:33:30.644  5812  5832 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 07:33:30.650  5812  5829 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-18 07:33:30.651  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:30.651  5812  5832 D BtGatt.ScanManager: Starting BLE batch scan
11-18 07:33:30.651  5812  5832 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 07:33:30.659  5812  5829 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-18 07:33:30.666  5812  5829 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-18 07:33:30.666  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 07:33:30.669  5812  5829 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-18 07:33:30.670  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:30.670  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.670  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 07:33:30.670  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.670  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.670  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.671  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.671  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.671  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.671  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.671  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.671  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-18 07:33:30.671  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-18 07:33:30.671  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 07:33:30.672  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 07:33:30.672  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.674  5812  5829 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-18 07:33:30.674  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:30.674  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.674  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.674  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:30.675  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started = , true. Current thread: Thread[main,5,main], id: 1
,11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-18 07:33:30.675  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-18 07:33:30.675  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-18 07:33:30.675  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.678  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.678  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-18 07:33:30.678  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.678  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-18 07:33:30.678  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:30.678  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-18 07:33:30.924   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-18 07:33:31.179  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-18 07:33:31.179  5708  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 07:33:31.180  5708  5708 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 07:33:33.436   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 07:33:33.678  5708  5754 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-18 07:33:33.679  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 07:33:33.679  5708  5754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 07:33:33.679  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 07:33:33.679  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-18 07:33:33.680  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 07:33:33.680  5708  5974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 07:33:33.680  5708  5974 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 07:33:33.680  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 07:33:33.680  5708  5754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 07:33:33.680  5708  5974 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 07:33:33.680  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 07:33:33.681  5708  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-18 07:33:33.681  5708  5754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179d213 removed from the list
11-18 07:33:33.681  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 07:33:33.681  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 07:33:33.681  5708  5754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 07:33:33.681  5708  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 07:33:33.681  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 07:33:33.681  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 07:33:33.684  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.684  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.685  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:33.685  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-18 07:33:33.685  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.687  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:33.688  5812  5823 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 07:33:33.688  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-18 07:33:33.689  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 07:33:33.690  5708  5754 D BluetoothAdapter: STATE_ON
11-18 07:33:33.692  5812  5856 D BtGatt.GattService: stopScan() - queue size =1
,11-18 07:33:33.694  5812  5857 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 07:33:33.695  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 07:33:33.695  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:33.695  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 07:33:33.696  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.696  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.696  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.696  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-18 07:33:33.696  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.698  5812  5812 D BtGatt.ScanManager: awakened up at time 235425
,11-18 07:33:33.698  5812  5831 D BtGatt.AdvertiseManager: message : 1
11-18 07:33:33.700  5812  5831 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-18 07:33:33.718  5812  5829 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-18 07:33:33.718  5812  5829 D BtGatt.GattService: Client app is not null!
,11-18 07:33:33.719  5812  5822 D BtGatt.GattService: unregisterClient() - clientIf=6
11-18 07:33:33.719  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 07:33:33.720  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.720  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 07:33:33.720  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.720  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 07:33:33.720  5708  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.720  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-18 07:33:33.720  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 07:33:33.726  5708  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 07:33:33.727  5708  5754 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,11-18 07:33:33.727  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.729  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.729  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:33.729  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.729  5708  5754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 07:33:33.729  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-18 07:33:33.729  5708  5754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c926c50 removed from the list
11-18 07:33:33.729  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 07:33:33.729  5708  5754 D io.jxcore.node.ConnectivityMonitor: stop
11-18 07:33:33.730  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 07:33:33.730  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 07:33:33.730  5812  5829 D BtGatt.GattService: current time is 235456816156
11-18 07:33:33.730  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:33.730  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.730  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 07:33:33.730  5812  5829 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 122, -120, 43, 39, 69, 69, 1, -128, -50, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -77, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -74, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -76, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 07:33:33.730  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-18 07:33:33.730  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.730  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.730  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-18 07:33:33.730  5708  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-18 07:33:33.730  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.731  5812  5829 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
11-18 07:33:33.731  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-18 07:33:33.731  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-18 07:33:33.731  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 07:33:33.731  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-18 07:33:33.731  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 07:33:33.731  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 07:33:33.731  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 07:33:33.731  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-18 07:33:33.731  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-18 07:33:33.731  5708  5754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-18 07:33:33.731  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-18 07:33:33.732  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 07:33:33.732  5812  5829 E BtGatt.ContextMap: Context not found for ID 5
11-18 07:33:33.732  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-18 07:33:33.733  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-18 07:33:33.733  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.734  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.734  5708  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.734  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.734  5708  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 07:33:33.734  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 07:33:33.734  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 07:33:33.734  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 07:33:33.734  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.734  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-18 07:33:33.734  5708  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 07:33:33.734  5708  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 07:33:33.735  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-18 07:33:33.737  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-18 07:33:33.738  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-18 07:33:33.739  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,11-18 07:33:33.740  5708  5754 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
11-18 07:33:33.741  5812  5829 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-18 07:33:33.741  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:33.741  5812  5832 D BtGatt.ScanManager: stopping BLe Batch
,11-18 07:33:33.747  5812  5829 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-18 07:33:33.747  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 07:33:33.747  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 07:33:33.752  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-18 07:33:33.752  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 07:33:34.235  5708  5708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 07:33:35.745  5708  5754 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-18 07:33:35.883  5708  5976 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 07:33:35.883  5708  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 07:33:35.925   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:36.470   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 07:33:36.689  5708  5976 W !!      : call onHalfStreamCopied
,11-18 07:33:36.689  5708  5976 I testCopyDataAndClose: closing input stream
,11-18 07:33:36.925   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 07:33:37.452  5708  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 07:33:37.459   928  2977 D ConnectivityService: handlePromptUnvalidated 101
,11-18 07:33:37.926   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:38.702   928  2975 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-18 07:33:38.927   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:39.857   928  2975 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 15 -> obsolete
,11-18 07:33:39.928   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:40.929   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-18 07:33:41.243  5708  5754 I StreamCopyingThreadTest: Starting test: testRun
,11-18 07:33:41.249  5708  5977 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-18 07:33:41.249  5708  5977 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 07:33:46.255  5708  5978 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-18 07:33:46.258  5708  5754 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-18 07:33:46.404  5708  5979 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 07:33:46.404  5708  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 07:33:48.039  5708  5979 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 07:33:48.039  5708  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 07:33:48.039  5708  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 07:33:48.039  5708  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 07:33:48.039  5708  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 07:33:48.039  5708  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-18 07:33:48.039  5708  5979 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 07:33:48.039  5708  5979 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-18 07:33:48.040  5708  5979 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 07:33:48.040  5708  5979 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 07:33:48.040  5708  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 07:33:50.931   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:51.768  5708  5754 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-18 07:33:51.771  5708  5980 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 07:33:51.771  5708  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 07:33:51.771  5708  5980 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-18 07:33:51.771  5708  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 07:33:51.772  5708  5980 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 07:33:51.772  5708  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 07:33:51.772  5708  5980 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 07:33:51.772  5708  5980 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 07:33:51.772  5708  5980 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-18 07:33:51.772  5708  5980 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 07:33:51.772  5708  5980 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 07:33:51.773  5708  5980 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 07:33:51.773  5708  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-18 07:33:51.774  5708  5754 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-18 07:33:51.774  5708  5754 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-18 07:33:51.775  5708  5754 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-18 07:33:51.777  5708  5981 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 07:33:51.777  5708  5981 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 07:33:51.778  5708  5981 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-18 07:33:51.778  5708  5981 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 07:33:51.778  5708  5981 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 07:33:51.778  5708  5981 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-18 07:33:51.779  5708  5981 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 07:33:51.779  5708  5981 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 07:33:51.780  5708  5754 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-18 07:33:51.780  5708  5754 E com.test.thalitest.ThaliTestRunner: 
11-18 07:33:51.780  5708  5754 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 07:33:51.780  5708  5754 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.783  5708,  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTe,stRunner: Expected: is <true>
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.,java:268)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:51.783  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	,at java.lang.reflect.Method.invoke(Native Method)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	,at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268),
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	,at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
,11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:51.784  5708  5754 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 07:33:51.786  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG UnitTest_app: 'Running unit tests'
11-18 07:33:51.786  5708  5754 I jxcore-log: 
11-18 07:33:51.786  5708  5754 I jxcore-log: *Native tests were executed*
11-18 07:33:51.786  5708  5754 I jxcore-log: 
11-18 07:33:51.786  5708  5754 I jxcore-log: Total number of executed tests:  82
11-18 07:33:51.786  5708  5754 I jxcore-log: 
11-18 07:33:51.786  5708  5754 I jxcore-log: Number of passed tests:  79
11-18 07:33:51.786  5708  5754 I jxcore-log: 
11-18 07:33:51.786  5708  5754 I jxcore-log: Number of failed tests:  3
11-18 07:33:51.786  5708  5754 I jxcore-log: 
11-18 07:33:51.787  5708  5754 I jxcore-log: Number of ignored tests:  0
11-18 07:33:51.787  5708  5754 I jxcore-log: 
11-18 07:33:51.787  5708  5754 I jxcore-log: Total duration:  37861
11-18 07:33:51.787  5708  5754 I jxcore-log: 
11-18 07:33:51.787  5708  5754 I jxcore-log: Failed to execute UT.
11-18 07:33:51.787  5708  5754 I jxcore-log: 
11-18 07:33:51.787  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-18 07:33:51.787  5708  5754 I jxcore-log: 
11-18 07:33:51.788  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-18 07:33:51.788  5708  5754 I jxcore-log: 
11-18 07:33:51.791  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on",,"cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 07:33:51.791  5708  5754 I jxcore-log: 
11-18 07:33:51.791  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 07:33:51.791  5708  5754 I jxcore-log: 
11-18 07:33:51.793  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 07:33:51.793  5708  5754 I jxcore-log: 
11-18 07:33:51.793  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 07:33:51.793  5708  5754 I jxcore-log: 
11-18 07:33:51.794  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 07:33:51.794  5708  5754 I jxcore-log: 
11-18 07:33:51.794  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 07:33:51.794  5708  5754 I jxcore-log: 
11-18 07:33:51.794  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.794  5708  5754 I jxcore-log: 
11-18 07:33:51.795  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 07:33:51.795  5708  5754 I jxcore-log: 
11-18 07:33:51.795  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 07:33:51.795  5708  5754 I jxcore-log: 
11-18 07:33:51.795  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.795  5708  5754 I jxcore-log: 
11-18 07:33:51.796  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 07:33:51.796  5708  5754 I jxcore-log: 
11-18 07:33:51.796  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 07:33:51.796  5708  5754 I jxcore-log: 
11-18 07:33:51.796  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.796  5708  5754 I jxcore-log: 
11-18 07:33:51.796  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 07:33:51.796  5708  5754 I jxcore-log: 
11-18 07:33:51.796  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.796  5708  5754 I jxcore-log: 
11-18 07:33:51.797  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 07:33:51.797  5708  5754 I jxcore-log: 
11-18 07:33:51.797  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 07:33:51.797  5708  5754 I jxcore-log: 
11-18 07:33:51.797  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 07:33:51.797  5708  5754 I jxcore-log: 
11-18 07:33:51.797  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.797  5708  5754 I jxcore-log: 
11-18 07:33:51.797  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 07:33:51.797  5708  5754 I jxcore-log: 
11-18 07:33:51.798  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 07:33:51.798  5708  5754 I jxcore-log: 
11-18 07:33:51.798  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 07:33:51.798  5708  5754 I jxcore-log: 
11-18 07:33:51.798  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 07:33:51.798  5708  5754 I jxcore-log: 
11-18 07:33:51.798  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-18 07:33:51.798  5708  5754 I jxcore-log: 
11-18 07:33:51.798  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 07:33:51.798  5708  5754 I jxcore-log: 
11-18 07:33:51.799  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-18 07:33:51.799  5708  5754 I jxcore-log: 
11-18 07:33:51.799  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 07:33:51.799  5708  5754 I jxcore-log: 
11-18 07:33:51.800  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 07:33:51.800  5708  5754 I jxcore-log: 
11-18 07:33:51.800  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 07:33:51.800  5708  5754 I jxcore-log: 
11-18 07:33:51.801  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.801  5708  5754 I jxcore-log: 
11-18 07:33:51.801  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-18 07:33:51.801  5708  5754 I jxcore-log: 
11-18 07:33:51.801  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 07:33:51.801  5708  5754 I jxcore-log: 
11-18 07:33:51.801  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.801  5708  5754 I jxcore-log: 
11-18 07:33:51.802  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"A8:81:95:E9:5F:6F-5","peerAvailable":true,"pleaseConnect":false}]'
11-18 07:33:51.802  5708  5754 I jxcore-log: 
11-18 07:33:51.802  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8:81:95:E9:5F:6F-5","peerAvailable":true,"pleaseConnect":false}'
11-18 07:33:51.802  5708  5754 I jxcore-log: 
11-18 07:33:51.802  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
11-18 07:33:51.802  5708  5754 I jxcore-log: 
11-18 07:33:51.802  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-18 07:33:51.802  5708  5754 I jxcore-log: 
11-18 07:33:51.803  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 07:33:51.803  5708  5754 I jxcore-log: 
11-18 07:33:51.803  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.803  5708  5754 I jxcore-log: 
11-18 07:33:51.803  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 07:33:51.803  5708  5754 I jxcore-log: 
11-18 07:33:51.803  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 07:33:51.803  5708  5754 I jxcore-log: 
11-18 07:33:51.808  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-18 07:33:51.808  5708  5754 I jxcore-log: 
11-18 07:33:51.808  5708  5754 I jxcore-log: 2016-11-18 12:33:51 - WARN testUtils: 'myNameCallback not set!'
11-18 07:33:51.808  5708  5754 I jxcore-log: 
11-18 07:33:51.814  5708  5708 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-18 07:33:51.932   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:52.933   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:53.844  5708  5754 I jxcore-log: 2016-11-18 12:33:53 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-18 07:33:53.844  5708  5754 I jxcore-log: 
,11-18 07:33:53.847  5708  5754 I jxcore-log: 2016-11-18 12:33:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-18 07:33:53.847  5708  5754 I jxcore-log: 
,11-18 07:33:53.934   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:54.186  5708  5754 I jxcore-log: 2016-11-18 12:33:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-18 07:33:54.186  5708  5754 I jxcore-log: 
,11-18 07:33:54.199  5708  5754 I jxcore-log: 2016-11-18 12:33:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-18 07:33:54.199  5708  5754 I jxcore-log: 
,11-18 07:33:54.936   592   592 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 07:33:55.305  5708  5754 I jxcore-log: 2016-11-18 12:33:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-18 07:33:55.305  5708  5754 I jxcore-log: 
,11-18 07:33:55.470  5708  5754 I jxcore-log: 2016-11-18 12:33:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-18 07:33:55.470  5708  5754 I jxcore-log: 
,11-18 07:33:55.475  5708  5754 I jxcore-log: 2016-11-18 12:33:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-18 07:33:55.475  5708  5754 I jxcore-log: 
,11-18 07:33:55.487  5708  5754 I jxcore-log: 2016-11-18 12:33:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-18 07:33:55.487  5708  5754 I jxcore-log: 
,11-18 07:33:55.936   592   592 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-18 07:33:55.977  5708  5754 I jxcore-log: 2016-11-18 12:33:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-18 07:33:55.977  5708  5754 I jxcore-log: 
,11-18 07:33:56.022  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-18 07:33:56.022  5708  5754 I jxcore-log: 
,11-18 07:33:56.035  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-18 07:33:56.035  5708  5754 I jxcore-log: 
,11-18 07:33:56.039  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-18 07:33:56.039  5708  5754 I jxcore-log: 
,11-18 07:33:56.313  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-18 07:33:56.313  5708  5754 I jxcore-log: 
,11-18 07:33:56.438  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-18 07:33:56.438  5708  5754 I jxcore-log: 
,11-18 07:33:56.530   928  5949 D NetlinkSocketObserver: NeighborEvent{elapsedMs=258256, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-18 07:33:56.813  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-18 07:33:56.813  5708  5754 I jxcore-log: 
,11-18 07:33:56.819  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-18 07:33:56.819  5708  5754 I jxcore-log: 
,11-18 07:33:56.824  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-18 07:33:56.824  5708  5754 I jxcore-log: 
,11-18 07:33:56.827  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-18 07:33:56.827  5708  5754 I jxcore-log: 
,11-18 07:33:56.832  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-18 07:33:56.832  5708  5754 I jxcore-log: 
,11-18 07:33:56.869  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-18 07:33:56.869  5708  5754 I jxcore-log: 
,11-18 07:33:56.876  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-18 07:33:56.876  5708  5754 I jxcore-log: 
,11-18 07:33:56.905  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-18 07:33:56.905  5708  5754 I jxcore-log: 
,11-18 07:33:56.943  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-18 07:33:56.943  5708  5754 I jxcore-log: 
,11-18 07:33:56.951  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-18 07:33:56.951  5708  5754 I jxcore-log: 
,11-18 07:33:56.957  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-18 07:33:56.957  5708  5754 I jxcore-log: 
,11-18 07:33:56.974  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-18 07:33:56.974  5708  5754 I jxcore-log: 
,11-18 07:33:56.988  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-18 07:33:56.988  5708  5754 I jxcore-log: 
,11-18 07:33:56.995  5708  5754 I jxcore-log: 2016-11-18 12:33:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-18 07:33:56.995  5708  5754 I jxcore-log: 
,11-18 07:33:57.000  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-18 07:33:57.000  5708  5754 I jxcore-log: 
,11-18 07:33:57.013  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-18 07:33:57.013  5708  5754 I jxcore-log: 
,11-18 07:33:57.031  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-18 07:33:57.031  5708  5754 I jxcore-log: 
,11-18 07:33:57.045  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-18 07:33:57.045  5708  5754 I jxcore-log: 
,11-18 07:33:57.056  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-18 07:33:57.056  5708  5754 I jxcore-log: 
,11-18 07:33:57.069  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-18 07:33:57.069  5708  5754 I jxcore-log: 
,11-18 07:33:57.079  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-18 07:33:57.079  5708  5754 I jxcore-log: 
,11-18 07:33:57.092  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-18 07:33:57.092  5708  5754 I jxcore-log: 
,11-18 07:33:57.102  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-18 07:33:57.102  5708  5754 I jxcore-log: 
,11-18 07:33:57.109  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-18 07:33:57.109  5708  5754 I jxcore-log: 
,11-18 07:33:57.130  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-18 07:33:57.130  5708  5754 I jxcore-log: 
,11-18 07:33:57.137  5708  5754 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-18 07:33:57.138  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - INFO testUtils: 'BLE multiple advertisement supported'
11-18 07:33:57.138  5708  5754 I jxcore-log: 
,11-18 07:33:57.292  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - DEBUG CoordinatedClient: 'connected to the test server'
11-18 07:33:57.292  5708  5754 I jxcore-log: 
,11-18 07:33:57.500  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-18 07:33:57.500  5708  5754 I jxcore-log: 
,11-18 07:33:57.503  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - DEBUG CoordinatedClient: 'test client failed'
11-18 07:33:57.503  5708  5754 I jxcore-log: 
,11-18 07:33:57.507  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-18 07:33:57.507  5708  5754 I jxcore-log: 
,11-18 07:33:57.513  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-18 07:33:57.513  5708  5754 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-18 07:33:57.513  5708  5754 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-18 07:33:57.513  5708  5754 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-18 07:33:57.513  5708  5754 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-18 07:33:57.513  5708  5754 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-18 07:33:57.513  5708  5754 I jxcore-log: 
,11-18 07:33:57.515  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-18 07:33:57.515  5708  5754 I jxcore-log: 
,11-18 07:33:57.519  5708  5754 I jxcore-log: 2016-11-18 12:33:57 - ERROR runTests: 'Test client failed: Native unit tests failed
11-18 07:33:57.519  5708  5754 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-18 07:33:57.519  5708  5754 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-18 07:33:57.519  5708  5754 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-18 07:33:57.519  5708  5754 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-18 07:33:57.519  5708  5754 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-18 07:33:57.519  5708  5754 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
11-18 07:33:57.519  5708  5754 I jxcore-log: 
,11-18 07:33:58.049  5990  5990 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-18 07:33:58.055  5990  5990 D AndroidRuntime: CheckJNI is OFF
,11-18 07:33:58.088  5990  5990 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-18 07:33:58.122  5990  5990 I Radio-JNI: register_android_hardware_Radio DONE
,11-18 07:33:58.138  5990  5990 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-18 07:33:58.146   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-18 07:33:58.147   928   941 I ActivityManager: Killing 5708:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-18 07:33:58.255   928  3155 I WindowState: WIN DEATH: Window{fa4b133 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-18 07:33:58.255   928  2976 D WifiService: Client connection lost with reason: 4
11-18 07:33:58.255   928  3158 D GraphicsStats: Buffer count: 2
,11-18 07:33:58.286   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-18 07:33:58.287   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-18 07:33:58.287   928   952 I art     : Starting a blocking GC Explicit
11-18 07:33:58.287   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-18 07:33:58.287   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-18 07:33:58.287   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:58.287   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:58.287   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 07:33:58.287   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-18 07:33:58.290   928   941 I ActivityManager:   Force finishing activity ActivityRecord{d36c24 u0 com.test.thalitest/.MainActivity t8}
,11-18 07:33:58.297   928  3842 W ActivityManager: Spurious death for ProcessRecord{67e901d 0:com.test.thalitest/u0a77}, curProc for 5708: null
,11-18 07:33:58.301   928   946 W WindowManager: Attempted to add application window with unknown token Token{cd0338d ActivityRecord{d36c24 u0 com.test.thalitest/.MainActivity t8 f}}.  Aborting.
,11-18 07:33:58.301   928   946 W WindowManager: Token{cd0338d ActivityRecord{d36c24 u0 com.test.thalitest/.MainActivity t8 f}} already running, starting window not displayed. Unable to add window -- token Token{cd0338d ActivityRecord{d36c24 u0 com.test.thalitest/.MainActivity t8 f}} is not valid; is your activity running?
11-18 07:33:58.301   928   946 W WindowManager: view not successfully added to wm, removing view
11-18 07:33:58.301   928   946 W WindowManager: Exception when adding starting window
11-18 07:33:58.301   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{ce09a8c V.E...... R.....ID 0,0-0,0} not attached to window manager
11-18 07:33:58.301   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-18 07:33:58.301   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-18 07:33:58.301   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-18 07:33:58.301   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-18 07:33:58.301   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-18 07:33:58.301   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:58.301   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:58.301   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 07:33:58.301   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-18 07:33:58.371   928   952 I art     : Explicit concurrent mark sweep GC freed 70531(4MB) AllocSpace objects, 15(484KB) LOS objects, 33% free, 29MB/43MB, paused 1.498ms total 83.260ms
,11-18 07:33:58.390   928   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-18 07:33:58.392  5990  5990 I art     : System.exit called, status: 0
,11-18 07:33:58.392  5990  5990 I AndroidRuntime: VM exiting with result code 0.
,11-18 07:33:58.397   928   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-18 07:33:58.407   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-18 07:33:58.410  3691  3691 I Keyboard.Facilitator: resetDictionaries() : en_US
11-18 07:33:58.410  5812  5812 D BluetoothMapAppObserver: onReceive
,11-18 07:33:58.411  5812  5812 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-18 07:33:58.414   928  2951 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-18 07:33:58.416  4092  4196 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-18 07:33:58.445  3691  6001 I Keyboard.Facilitator.DecoderInitializer: run()
,11-18 07:33:58.461  3806  3806 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-18 07:33:58.465  3400  6002 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-18 07:33:58.478  3691  6001 I Decoder : createOrResetDecoder
,11-18 07:33:58.482  3579  3579 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-18 07:33:58.482  3579  3579 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-18 07:33:58.489   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-18 07:33:58.496    17    17 W kworker/2:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 07:33:58.499    17    17 W kworker/2:0: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 07:33:58.513    17    17 W kworker/2:0: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 07:33:58.504  3759  6007 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-18 07:33:58.504  3759  6007 D AccountUtils: Clearing selected account for com.test.thalitest
11-18 07:33:58.507   928   940 E PackageManager: Failed to write settings, restoring backup
11-18 07:33:58.507   928   940 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-18 07:33:58.507   928   940 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-18 07:33:58.507   928   940 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-18 07:33:58.507   928   940 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-18 07:33:58.507   928   940 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
11-18 07:33:58.507   928   940 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
11-18 07:33:58.507   928   940 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
11-18 07:33:58.507   928   940 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
11-18 07:33:58.507   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
11-18 07:33:58.507   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-18 07:33:58.507   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-18 07:33:58.507   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:58.507   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:58.507   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 07:33:58.507   928   940 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-18 07:33:58.507   928   940 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-18 07:33:58.507   928   940 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-18 07:33:58.507   928   940 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-18 07:33:58.507   928   940 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-18 07:33:58.507   928   940 E PackageManager: 	... 12 more
,11-18 07:33:58.522   928  3155 I ActivityManager: Start proc 6010:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-18 07:33:58.523  3836  3954 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-18 07:33:58.523  3836  3954 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3836
11-18 07:33:58.523  3836  3954 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:58.523  3836  3954 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 07:33:58.527   928  3158 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-18 07:33:58.527   928  6017 E DropBoxManagerService: Can't write: system_app_crash
11-18 07:33:58.527   928  6017 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 07:33:58.527   928  6017 E DropBoxManagerService: 	... 5 more
,11-18 07:33:58.530  3836  3954 I Process : Sending signal. PID: 3836 SIG: 9
,11-18 07:33:58.547  3579  3579 I ConfigService: onCreate
,11-18 07:33:58.550  3400  3424 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj59F2789E9) - 
,11-18 07:33:58.551  3579  6023 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 07:33:58.551  3579  6023 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 07:33:58.552  3579  6023 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-18 07:33:58.554  3579  6023 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-18 07:33:58.564  3691  6001 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-18 07:33:58.580  3759  6007 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-18 07:33:58.602  3759  6007 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:58.602  3759  6007 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:58.602  3759  6007 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 07:33:58.603  3759  6007 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-18 07:33:58.635  3400  3424 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-18 07:33:58.635  3400  3424 E AndroidRuntime: Process: android.process.acore, PID: 3400
11-18 07:33:58.635  3400  3424 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 07:33:58.635  3400  3424 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 07:33:58.658   928  3155 I WindowState: WIN DEATH: Window{6393533 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-18 07:33:58.658   928  3594 D GraphicsStats: Buffer count: 1
,11-18 07:33:58.658   928  2950 W InputDispatcher: channel '6393533 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-18 07:33:58.659   928  2950 E InputDispatcher: channel '6393533 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
11-18 07:33:58.659   928  3155 W InputDispatcher: Attempted to unregister already unregistered input channel '6393533 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-18 07:33:58.659  3400  3424 I Process : Sending signal. PID: 3400 SIG: 9
,11-18 07:33:58.664   928  3842 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3836) has died
11-18 07:33:58.664   928  3842 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-18 07:33:58.679  3759  6029 I GMPM-SVC: App measurement is starting up
,11-18 07:33:58.682  3759  6029 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-18 07:33:58.683  3759  6029 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-18 07:33:58.884   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
