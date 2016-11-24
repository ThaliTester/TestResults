#### Test 9418709498bebf3_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
,11-24 06:19:15.758   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
11-24 06:19:16.215  5575  5575 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 06:19:16.220  5575  5575 D AndroidRuntime: CheckJNI is OFF
11-24 06:19:16.248  5575  5575 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 06:19:16.280  5575  5575 I Radio-JNI: register_android_hardware_Radio DONE
11-24 06:19:16.295  5575  5575 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 06:19:16.314   930  3102 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 06:19:16.370   930  3102 I ActivityManager: Start proc 5585:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 06:19:16.380  5575  5575 D AndroidRuntime: Shutting down VM
,11-24 06:19:16.716   930  3809 I WindowManager: Screenshot max retries 4 of Token{ead21f4 ActivityRecord{64507c7 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{d9528bf u0 Starting com.test.thalitest} drawState=2
,11-24 06:19:16.796  5585  5585 I CordovaLog: Changing log level to DEBUG(3)
,11-24 06:19:16.796  5585  5585 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 06:19:16.796  5585  5585 D CordovaActivity: CordovaActivity.onCreate()
,11-24 06:19:16.803  5585  5585 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-24 06:19:16.831  5585  5585 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-24 06:19:16.905  5585  5585 I LibraryLoader: Time to load native libraries: 69 ms (timestamps 1434-1503)
,11-24 06:19:16.905  5585  5585 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 06:19:16.942  5585  5585 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c669e74}
11-24 06:19:16.943  5585  5585 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 06:19:16.943  5585  5585 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 06:19:16.951  5585  5585 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 06:19:16.952  5585  5585 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 06:19:17.011  5585  5585 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 06:19:17.025  5585  5585 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 06:19:17.025  5585  5585 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 06:19:17.025  5585  5585 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 06:19:17.025  5585  5585 I Adreno  : Build Date                       : 12/06/15
11-24 06:19:17.025  5585  5585 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 06:19:17.025  5585  5585 I Adreno  : Local Branch                     : mybranch17112971
11-24 06:19:17.025  5585  5585 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 06:19:17.025  5585  5585 I Adreno  : Remote Branch                    : NONE
11-24 06:19:17.025  5585  5585 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 06:19:17.069   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b970b7:true
,11-24 06:19:17.092   410   410 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33945]" dev="sockfs" ino=33945 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 06:19:17.092   410   410 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33945]" dev="sockfs" ino=33945 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 06:19:17.108  5585  5585 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 06:19:17.116  5585  5585 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 06:19:17.120  5585  5585 D PluginManager: init()
,11-24 06:19:17.123  5585  5585 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 06:19:17.143  5585  5585 D CordovaActivity: Started the activity.
,11-24 06:19:17.143  5585  5585 D CordovaActivity: Resumed the activity.
,11-24 06:19:17.142   408   408 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31726]" dev="sockfs" ino=31726 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 06:19:17.142   408   408 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31726]" dev="sockfs" ino=31726 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 06:19:17.147  5585  5622 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 06:19:17.152  3510  3510 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33949]" dev="sockfs" ino=33949 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 06:19:17.152  3510  3510 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33949]" dev="sockfs" ino=33949 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 06:19:17.155  5585  5585 D CordovaActivity: Paused the activity.
,11-24 06:19:17.157  5585  5609 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 06:19:17.182  5585  5622 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 06:19:17.207  5585  5585 D CordovaActivity: Stopped the activity.
,11-24 06:19:17.278   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +555ms (total +941ms)
,11-24 06:19:17.283  5585  5585 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 06:19:17.310  5585  5585 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5585
,11-24 06:19:17.414  5585  5585 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 06:19:17.720  5585  5625 D jxcore_app_log: JniHelper::setJavaVM(0xf51bc000), pthread_self() = -582481616
,11-24 06:19:17.732  5585  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 06:19:17.732  5585  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 06:19:17.732  5585  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 06:19:17.732  5585  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 06:19:17.732  5585  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-24 06:19:17.732  5585  5625 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4070f15 added. We now have 1 listener(s)
,11-24 06:19:17.739  5585  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-24 06:19:17.740  5585  5625 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 06:19:17.742  5585  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:19:17.743  5585  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 06:19:17.747  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 06:19:17.748  5585  5625 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c563db8 added. We now have 1 listener(s)
11-24 06:19:17.748  5585  5625 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:19:17.753   930  2921 D WifiService: New client listening to asynchronous messages
,11-24 06:19:17.754  5585  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 06:19:17.754  5585  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 06:19:17.755  5585  5625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 06:19:17.755  5585  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 06:19:17.755  5585  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 06:19:17.755  5585  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 06:19:17.755  5585  5625 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 06:19:17.758  5585  5625 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 06:19:17.915  5585  5585 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 06:19:17.918  5585  5585 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-24 06:19:17.920  5585  5585 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 06:19:18.243  5585  5594 I art     : Background sticky concurrent mark sweep GC freed 76944(7MB) AllocSpace objects, 16(1076KB) LOS objects, 23% free, 25MB/32MB, paused 1.233ms total 258.720ms
,11-24 06:19:19.429  5585  5594 I art     : Background partial concurrent mark sweep GC freed 53228(5MB) AllocSpace objects, 2(1176KB) LOS objects, 36% free, 27MB/43MB, paused 1.458ms total 301.280ms
,11-24 06:19:21.666  5585  5632 W jxcore-log: Initializing JXcore engine
,11-24 06:19:21.666  5585  5632 W jxcore-log: JXcore engine is ready
,11-24 06:19:21.722  5632  5632 W Thread-62: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12056 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 06:19:21.722  5632  5632 W Thread-62: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12414]" dev="sockfs" ino=12414 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 06:19:21.722  5632  5632 W Thread-62: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2894 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 06:19:21.722  5632  5632 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33305]" dev="sockfs" ino=33305 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 06:19:21.739  5585  5632 W jxcore-log: Starting JXcore engine
,11-24 06:19:21.804  5585  5632 W jxcore-log: Platform android
11-24 06:19:21.804  5585  5632 W jxcore-log: 
,11-24 06:19:21.804  5585  5632 W jxcore-log: Process ARCH arm
11-24 06:19:21.804  5585  5632 W jxcore-log: 
,11-24 06:19:21.985  5585  5632 I jxcore-log: JXcore Cordova bridge is ready!
11-24 06:19:21.985  5585  5632 I jxcore-log: 
11-24 06:19:21.985  5585  5632 W jxcore-log: JXcore engine is started
,11-24 06:19:21.999  5585  5625 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 06:19:22.007  5585  5585 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 06:19:22.007  5585  5585 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 06:19:27.912   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 06:19:31.481  5585  5632 I jxcore-log: 2016-11-24 11:19:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 06:19:31.481  5585  5632 I jxcore-log: 
,11-24 06:19:31.482  5585  5632 I jxcore-log: 2016-11-24 11:19:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 06:19:31.482  5585  5632 I jxcore-log: 
,11-24 06:19:31.496  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 06:19:31.499  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 06:19:31.502  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 06:19:31.504  5585  5632 I jxcore-log: 2016-11-24 11:19:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 06:19:31.504  5585  5632 I jxcore-log: 
,11-24 06:19:31.506  5585  5632 I jxcore-log: 2016-11-24 11:19:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 06:19:31.506  5585  5632 I jxcore-log: 
,11-24 06:19:31.746  5585  5632 I jxcore-log: 2016-11-24 11:19:31 - DEBUG UnitTest_app: 'Running unit tests'
11-24 06:19:31.746  5585  5632 I jxcore-log: 
11-24 06:19:31.747  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 06:19:31.747  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f11bd added. We now have 2 listener(s)
11-24 06:19:31.747  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:19:31.748  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:19:31.748  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 06:19:31.748  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:19:31.748  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30053b2 added. We now have 2 listener(s)
11-24 06:19:31.748  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:19:31.748  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 06:19:31.749  5585  5632 D executeNativeTests: Running unit tests
,11-24 06:19:31.794  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 06:19:31.794  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 added. We now have 3 listener(s)
11-24 06:19:31.795  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:19:31.795  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 06:19:31.795  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:19:31.795  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:19:31.795  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 added. We now have 3 listener(s)
11-24 06:19:31.795  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:19:31.796  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 06:19:31.798  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 06:19:31.798  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 06:19:31.798  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 06:19:31.798  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 06:19:31.799  5585  5632 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 06:19:31.799  5585  5632 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-24 06:19:31.799  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 06:19:31.799  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 06:19:31.799  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 06:19:31.799  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 06:19:31.800  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:31.800  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:31.800  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:31.800  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 06:19:31.800  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 06:19:31.801  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:19:31.801  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 removed from the list
,11-24 06:19:31.801  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:31.801  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 removed from the list
11-24 06:19:31.801  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:31.801  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.801  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.802  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.802  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.802  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.802  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:31.802  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:31.802  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:31.802  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:31.803  5585  5632 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-24 06:19:31.803  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:31.804  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:31.804  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:31.804  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:31.804  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:31.804  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:31.804  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:31.804  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:31.804  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:31.804  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.804  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:31.805  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.805  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.805  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:31.805  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:31.805  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:31.805  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:19:31.805  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 06:19:31.808  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllO,utgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 06:19:31.809  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:31.809  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:31.809  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:31.809  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:31.809  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:31.809  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:31.809  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:31.809  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:31.809  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:31.809  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.809  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.810  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.810  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.810  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.810  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 06:19:31.810  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:31.810  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:31.810  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:31.811  5585  5632 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 06:19:31.812  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 06:19:31.812  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 06:19:31.817  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 06:19:31.819  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700",
11-24 06:19:31.819  5585  5632 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 06:19:31.819  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:19:31.819  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 06:19:31.819  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 06:19:31.819  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:19:31.819  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 06:19:31.821  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:19:31.822  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 06:19:31.822  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 06:19:31.822  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 06:19:31.822  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:19:31.824  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.825  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 06:19:31.825  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 06:19:31.826  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 06:19:31.826  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 06:19:31.827  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-24 06:19:31.828  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 06:19:31.828  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.828  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 06:19:31.828  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 06:19:31.828  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 06:19:31.828  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-24 06:19:31.828  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.829  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:19:31.831  4536  4770 D BtGatt.GattService: registerClient() - UUID=59ef31bc-3262-4f74-9e01-8f09e9daf17f
11-24 06:19:31.832  4536  4611 D BtGatt.GattService: onClientRegistered() - UUID=59ef31bc-3262-4f74-9e01-8f09e9daf17f, clientIf=5
,11-24 06:19:31.834  5585  5595 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 06:19:31.835  4536  4550 D BtGatt.GattService: start scan with filters
,11-24 06:19:31.843  4536  4620 D BtGatt.ScanManager: handling starting scan
11-24 06:19:31.843  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 06:19:31.843  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.843  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 06:19:31.843  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.843  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 06:19:31.844  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-24 06:19:31.844  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 06:19:31.844  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.844  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:19:31.844  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 06:19:31.844  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 06:19:31.845  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:19:31.845  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 06:19:31.845  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.845  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.845  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:31.845  4536  4620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:19:31.846  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:19:31.846  5585  5632 I io.jxcore.node.ConnectionHelper: start: OK
11-24 06:19:31.847  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 06:19:31.847  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 06:19:31.852  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:19:31.853  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:19:31.853  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 06:19:31.853  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:19:31.854  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 06:19:31.857  4536  4611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 06:19:31.857  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:31.858  4536  4620 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 06:19:31.867  4536  4611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 06:19:31.867  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:31.868  4536  4620 D BtGatt.ScanManager: Starting BLE batch scan
11-24 06:19:31.868  4536  4620 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 06:19:31.882  4536  4611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 06:19:31.882  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:31.890  4536  4611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 06:19:31.890  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:32.360  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 06:19:32.360  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:19:32.360  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 06:19:33.411   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 06:19:35.761   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:19:36.442   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 06:19:36.763   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:19:36.854  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 06:19:36.854  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:36.854  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 06:19:36.855  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:19:36.855  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 06:19:36.855  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:36.855  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 06:19:36.855  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 06:19:36.855  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.855  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 06:19:36.855  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 06:19:36.856  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.856  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.856  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.856  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 06:19:36.856  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.857  5585  5632 D BluetoothAdapter: STATE_ON
,11-24 06:19:36.858  4536  4770 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 06:19:36.858  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 06:19:36.859  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:19:36.859  4536  4620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:19:36.859  4536  4771 D BtGatt.GattService: stopScan() - queue size =1
11-24 06:19:36.860  4536  4549 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 06:19:36.861  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 06:19:36.861  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.861  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 06:19:36.861  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.861  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.861  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.861  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.862  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 06:19:36.862  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.862  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.862  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.862  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 06:19:36.862  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 06:19:36.863  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:19:36.863  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.865  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.865  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 06:19:36.865  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.865  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:36.865  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:36.865  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:19:36.865  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:19:36.865  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:19:36.866  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:36.866  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:36.866  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:36.866  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:19:36.866  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:36.866  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:36.866  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 06:19:36.866  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 06:19:36.866  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:19:36.866  4536  4536 D BtGatt.ScanManager: awakened up at time 191465
11-24 06:19:36.866  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 06:19:36.867  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 06:19:36.867  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:19:36.867  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 06:19:36.867  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:19:36.868  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:19:36.868  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 06:19:36.868  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:19:36.871  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:19:36.871  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:19:36.872  5585  5585 D org.thaliproject.p2p.bt,connectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 06:19:36.903  4536  4611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-24 06:19:36.903  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:36.904  4536  4611 D BtGatt.GattService: current time is 191502813659
11-24 06:19:36.904  4536  4611 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -89, 79, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 37, -47, 14, -113, 116, -46, 1, -128, -73, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -72, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -69, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -66, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -70, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -71, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 06:19:36.906  4536  4611 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
11-24 06:19:36.907  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 06:19:36.907  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 06:19:36.907  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 06:19:36.908  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 06:19:36.908  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10,, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 06:19:36.908  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 06:19:36.916  4536  4611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 06:19:36.916  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:36.916  4536  4620 D BtGatt.ScanManager: stopping BLe Batch
11-24 06:19:36.924  4536  4611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 06:19:36.924  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:36.924  4536  4620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:19:36.931  4536  4611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:19:36.931  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:37.371  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 06:19:37.765   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:19:38.767   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:19:39.769   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:19:40.770   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 06:19:41.871  5585  5632 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 06:19:41.874  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 06:19:41.875  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 06:19:41.891  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 06:19:41.895  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 06:19:41.896  5585  5632 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-24 06:19:41.896  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:19:41.896  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 06:19:41.896  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 06:19:41.896  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:19:41.896  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 06:19:41.904  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 06:19:41.904  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:19:41.904  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 06:19:41.904  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 06:19:41.911  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:19:41.912  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.912  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 06:19:41.913  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 06:19:41.913  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 06:19:41.914  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 06:19:41.921  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.921  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 06:19:41.921  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 06:19:41.921  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 06:19:41.921  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 06:19:41.922  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.923  5585  5632 D BluetoothAdapter: STATE_ON
,11-24 06:19:41.928  4536  4550 D BtGatt.GattService: registerClient() - UUID=fc5eb7a2-dbae-41b9-9009-f1ec7791eea3
,11-24 06:19:41.929  4536  4611 D BtGatt.GattService: onClientRegistered() - UUID=fc5eb7a2-dbae-41b9-9009-f1ec7791eea3, clientIf=5
,11-24 06:19:41.930  5585  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 06:19:41.930  4536  4770 D BtGatt.GattService: start scan with filters
,11-24 06:19:41.936  4536  4620 D BtGatt.ScanManager: handling starting scan
,11-24 06:19:41.937  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 06:19:41.937  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.937  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 06:19:41.938  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.938  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 06:19:41.938  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 06:19:41.938  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.938  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 06:19:41.938  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 06:19:41.938  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.939  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.939  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.939  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.940  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 06:19:41.941  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:41.946  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:41.946  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:19:41.946  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.946  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.946  5585  5632 I io.jxcore.node.ConnectionHelper: start: OK
11-24 06:19:41.947  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.948  4536  4611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 06:19:41.948  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:41.948  4536  4620 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 06:19:41.951  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:41.951  5585  5632 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 06:19:41.951  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:41.951  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 06:19:41.951  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:19:41.951  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 06:19:41.951  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:41.951  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 06:19:41.953  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.953  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.953  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 06:19:41.953  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:19:41.953  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 06:19:41.953  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.953  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 06:19:41.953  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 06:19:41.954  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.954  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.954  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.954  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 06:19:41.954  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.956  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:19:41.956  4536  4549 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 06:19:41.956  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 06:19:41.958  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:19:41.958  4536  4550 D BtGatt.GattService: stopScan() - queue size =1
11-24 06:19:41.959  4536  4770 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 06:19:41.960  4536  4611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.960  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.960  4536  4620 D BtGatt.ScanManager: Starting BLE batch scan
11-24 06:19:41.960  4536  4620 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 06:19:41.960  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.961  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.961  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.961  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 06:19:41.961  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 06:19:41.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:19:41.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:41.964  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.965  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:19:41.965  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.965  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.966  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:41.966  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:19:41.966  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:19:41.966  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:41.966  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:19:41.966  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:41.966  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:19:41.966  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:41.966  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:41.966  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 06:19:41.966  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:41.966  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.966  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 06:19:41.966  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 06:19:41.966  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 06:19:41.966  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.967  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.967  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.967  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:19:41.967  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.967  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.969  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.969  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.969  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:19:41.973  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.973  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.974  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.975  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.975  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.975  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:41.975  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:41.975  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:41.975  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:41.976  5585  5632 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 06:19:41.976  4536  4611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 06:19:41.976  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:41.979  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:19:41.979  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 06:19:41.983  4536  4611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 06:19:41.984  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 06:19:41.985  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 06:19:41.986  4536  4620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:19:41.988  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 06:19:41.988  5585  5632 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 06:19:41.988  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:19:41.988  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 06:19:41.988  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 06:19:41.988  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:19:41.989  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 06:19:41.992  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 06:19:41.992  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:19:41.993  4536  4611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:19:41.993  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:41.993  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 06:19:41.993  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 06:19:41.993  4536  4611 E BtGatt.ContextMap: Context not found for ID 5
11-24 06:19:41.997  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:41.997  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 06:19:41.997  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:19:41.998  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 06:19:41.998  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 06:19:41.998  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 06:19:42.001  4536  4611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 06:19:42.001  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:42.001  4536  4620 D BtGatt.ScanManager: stopping BLe Batch
,11-24 06:19:42.005  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:42.005  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 06:19:42.005  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 06:19:42.005  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 06:19:42.005  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 06:19:42.005  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:42.006  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:19:42.008  4536  4549 D BtGatt.GattService: registerClient() - UUID=6920f5dd-23fa-44d9-9776-c026008692ed
11-24 06:19:42.008  4536  4611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 06:19:42.008  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:42.008  4536  4620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:19:42.008  4536  4611 D BtGatt.GattService: onClientRegistered() - UUID=6920f5dd-23fa-44d9-9776-c026008692ed, clientIf=5
11-24 06:19:42.009  5585  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 06:19:42.009  4536  4771 D BtGatt.GattService: start scan with filters
11-24 06:19:42.014  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 06:19:42.014  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:42.014  4536  4611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:19:42.014  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:42.014  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 06:19:42.014  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:42.014  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 06:19:42.014  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 06:19:42.014  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.014  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 06:19:42.014  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 06:19:42.014  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.014  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.015  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.015  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.015  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 06:19:42.016  4536  4620 D BtGatt.ScanManager: handling starting scan
11-24 06:19:42.016  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:42.018  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:42.018  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:19:42.019  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:42.019  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:42.019  5585  5632 I io.jxcore.node.ConnectionHelper: start: OK
11-24 06:19:42.019  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.021  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.021  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.021  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:19:42.021  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:19:42.023  4536  4611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 06:19:42.023  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:42.023  4536  4620 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 06:19:42.029  4536  4611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 06:19:42.029  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:42.029  4536  4620 D BtGatt.ScanManager: Starting BLE batch scan
11-24 06:19:42.029  4536  4620 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 06:19:42.039  4536  4611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 06:19:42.039  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:42.044  4536  4611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 06:19:42.044  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:42.521   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 06:19:42.523  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 06:19:42.523  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:19:42.523  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 06:19:45.571   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 06:19:45.576   930  2922 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-24 06:19:47.021  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 06:19:47.022  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:47.022  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 06:19:47.022  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 06:19:47.022  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 06:19:47.023  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:47.023  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 06:19:47.023  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 06:19:47.023  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.023  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 06:19:47.023  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 06:19:47.024  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.024  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:47.025  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.025  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 06:19:47.025  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.028  5585  5632 D BluetoothAdapter: STATE_ON
,11-24 06:19:47.029  4536  4550 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 06:19:47.030  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 06:19:47.031  4536  4620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:19:47.032  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:19:47.034  4536  4549 D BtGatt.GattService: stopScan() - queue size =1
11-24 06:19:47.036  4536  4771 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 06:19:47.036  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 06:19:47.037  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.037  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 06:19:47.037  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:47.037  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.038  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.038  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.038  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 06:19:47.038  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.038  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.039  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:47.039  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 06:19:47.039  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 06:19:47.040  4536  4536 D BtGatt.ScanManager: awakened up at time 201638
11-24 06:19:47.040  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:19:47.040  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.045  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.045  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:19:47.045  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.045  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:47.046  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:19:47.046  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:19:47.046  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 06:19:47.046  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:19:47.046  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 06:19:47.046  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 06:19:47.047  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:19:47.047  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 06:19:47.047  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:19:47.047  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:19:47.047  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 06:19:47.047  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:19:47.050  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:19:47.050  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:19:47.051  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 06:19:47.072  4536  4611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-24 06:19:47.073  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:47.073  4536  4611 D BtGatt.GattService: current time is 201672033343
11-24 06:19:47.073  4536  4611 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -72, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -72, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -70, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -80, -54, -100, -120, -128, -10, 1, 0, -98, 93, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 116, 43, -120, 27, -33, -52, -88, -28, 88, -31, 95, 3, 3, -29, 27, 62, 119, -6, -93, 28, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -71, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -66, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 06:19:47.074  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 06:19:47.074  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 06:19:47.074  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-24 06:19:47.074  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 116, 43, -120, 27, -33, -52, -88, -28, 88, -31, 95, 3, 3, -29, 27, 62, 119, -6, -93, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-24 06:19:47.075  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 06:19:47.075  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 06:19:47.075  4536  4611 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-24 06:19:47.084  4536  4611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 06:19:47.084  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:47.084  4536  4620 D BtGatt.ScanManager: stopping BLe Batch
,11-24 06:19:47.091  4536  4611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 06:19:47.091  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:19:47.091  4536  4620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 06:19:47.098  4536  4611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:19:47.098  4536  4611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:19:47.550  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 06:19:47.550  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 06:19:47.551  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 06:19:47.692   930  5328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=202290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 06:19:47.918   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 06:19:48.606   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 06:19:48.613   930  2922 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-24 06:19:52.049  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 06:19:52.049  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:52.050  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.050  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.050  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 06:19:52.050  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:19:52.050  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.051  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:52.051  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.051  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.051  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.052  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 06:19:52.056  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.056  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.061  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.061  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.061  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.062  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.062  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.062  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:19:52.062  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.063  5585  5632 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-24 06:19:52.065  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 06:19:52.066  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 06:19:52.066  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.066  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 06:19:52.066  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.066  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list,
11-24 06:19:52.067  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:19:52.067  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.067  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:19:52.068  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.068  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.075  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.075  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.075  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.075  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.075  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.075  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.076  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
,11-24 06:19:52.079  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 06:19:52.079  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 06:19:52.080  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:52.080  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.080  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.080  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.080  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:52.080  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.081  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
,11-24 06:19:52.081  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.082  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.082  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.084  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.084  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.085  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.085  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 06:19:52.085  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.085  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.085  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.086  5585  5632 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 06:19:52.087  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 06:19:52.087  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:52.087  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.087  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.087  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.087  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
,11-24 06:19:52.088  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.088  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.088  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.088  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.088  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.092  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.092  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.092  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.092  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.092  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.092  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.093  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.094  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 06:19:52.094  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:52.095  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:52.095  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.095  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.095  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.095  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:52.095  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:19:52.095  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.095  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.096  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.096  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.099  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.099  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.099  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.099  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.099  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.099  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.099  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
,11-24 06:19:52.101  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-24 06:19:52.101  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 06:19:52.101  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 06:19:52.101  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 06:19:52.101  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 06:19:52.102  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 06:19:52.102  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 06:19:52.102  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 06:19:52.102  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 06:19:52.102  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:52.102  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:52.102  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.102  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.103  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.103  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
,11-24 06:19:52.103  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.103  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.103  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.103  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.103  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.106  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.106  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.107  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.107  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.107  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.107  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.107  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.108  5585  5632 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 06:19:52.109  5585  5632 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-24 06:19:52.109  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 06:19:52.113  5585  5632 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 06:19:52.113  5585  5632 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 06:19:52.114  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-24 06:19:52.115  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 06:19:52.116  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 06:19:52.116  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 06:19:52.116  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 06:19:52.116  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 06:19:52.116  5585  5632 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 06:19:52.116  5585  5632 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 06:19:52.116  5585  5632 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 06:19:52.116  5585  5632 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 06:19:52.117  5585  5632 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 06:19:52.117  5585  5632 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 06:19:52.117  5585  5632 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 06:19:52.117  5585  5632 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 06:19:52.117  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-24 06:19:52.125  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-24 06:19:52.126  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 06:19:52.127  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-24 06:19:52.132  4770  4770 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33357]" dev="sockfs" ino=33357 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 06:19:52.132  4770  4770 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33357]" dev="sockfs" ino=33357 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 06:19:52.128  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 06:19:52.128  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 06:19:52.128  5585  5632 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 06:19:52.128  5585  5632 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 06:19:52.129  5585  5632 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 06:19:52.129  5585  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-24 06:19:52.129  5585  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,11-24 06:19:52.129  5585  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 06:19:52.129  5585  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-24 06:19:52.130  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:52.130  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:52.130  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.130  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.130  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.130  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 06:19:52.131  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:52.131  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.132  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.132  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.132  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.132  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.132  5585  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-24 06:19:52.132  5585  5635 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 06:19:52.132  5585  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 06:19:52.132  5585  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-24 06:19:52.132  5585  5635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 06:19:52.132  5585  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
11-24 06:19:52.133  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.133  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.133  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.134  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.134  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.134  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.134  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.135  5585  5632 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 06:19:52.136  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:52.136  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:52.136  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 06:19:52.136  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.136  5585  5635 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-24 06:19:52.136  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.137  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:52.137  5585  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 06:19:52.137  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.137  5585  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-24 06:19:52.137  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
,11-24 06:19:52.137  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.137  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.137  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.139  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.139  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.139  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.139  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.139  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.139  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.139  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.140  5585  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-24 06:19:52.141  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:52.141  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:52.141  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.141  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.141  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.141  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:52.141  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.141  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.141  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.141  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.141  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.143  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.143  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.143  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.143  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.143  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:52.143  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.143  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
,11-24 06:19:52.144  5585  5632 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 06:19:52.144  5585  5632 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 06:19:52.144  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 06:19:52.144  5585  5632 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 06:19:52.144  5585  5632 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 06:19:52.144  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 06:19:52.145  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-24 06:19:52.145  5585  5632 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 06:19:52.145  5585  5632 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 06:19:52.145  5585  5632 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 06:19:52.145  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-24 06:19:52.145  5585  5632 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 06:19:52.145  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:52.145  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 06:19:52.145  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:52.145  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.145  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.145  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:52.145  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.145  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.145  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:52.146  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:52.146  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.147  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.147  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.147  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:52.147  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:52.148  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 06:19:52.148  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.148  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.148  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:52.148  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:52.149  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:52.149  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:52.149  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:52.149  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:19:57.152  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:19:57.152  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.152  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:57.153  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:57.153  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:57.153  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:57.153  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:57.153  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 06:19:57.154  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:57.154  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:57.155  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:57.155  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:19:57.155  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.155  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:57.155  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.156  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:57.161  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.161  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:57.162  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.162  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:57.162  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:57.162  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.162  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.165  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 06:19:57.166  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:19:57.166  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 06:19:57.173  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 06:19:57.175  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-24 06:19:57.175  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-24 06:19:57.175  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-24 06:19:57.176  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 06:19:57.176  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 06:19:57.176  5585  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 06:19:57.176  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 06:19:57.177  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:57.177  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 06:19:57.177  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 06:19:57.177  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-24 06:19:57.177  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 06:19:57.178  5585  5637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 06:19:57.179  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 06:19:57.179  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 06:19:57.179  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
,11-24 06:19:57.179  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.179  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 06:19:57.179  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 06:19:57.180  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.180  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 06:19:57.180  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 06:19:57.180  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:57.182  4771  4771 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29359]" dev="sockfs" ino=29359 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 06:19:57.182  4771  4771 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29359]" dev="sockfs" ino=29359 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 06:19:57.182  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.182  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:19:57.183  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.183  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.183  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.183  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:19:57.183  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 06:19:57.183  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 06:19:57.183  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:19:57.183  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:57.183  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 06:19:57.183  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 06:19:57.184  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-24 06:19:57.184  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:57.184  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.184  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.184  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:19:57.184  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.184  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.186  5585  5637 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 06:19:57.186  5585  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 06:19:57.186  5585  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-24 06:19:57.186  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.187  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.187  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 06:19:57.187  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.187  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:57.187  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 06:19:57.187  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:57.187  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.187  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.189  5585  5632 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 06:19:57.189  5585  5632 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 06:19:57.190  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 06:19:57.190  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 06:19:57.190  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 06:19:57.191  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:57.192  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:57.192  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:57.192  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:57.192  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 06:19:57.192  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:57.192  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.192  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.192  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:19:57.193  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.193  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.195  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.195  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.195  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:57.195  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:57.196  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:57.196  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.196  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.203  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:57.203  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:57.203  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 06:19:57.203  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:19:57.204  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:57.204  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:57.204  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.204  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.204  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:57.204  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:57.205  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.207  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.207  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.207  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.207  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:57.207  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:57.207  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.207  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.208  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:19:57.208  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:19:57.209  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:19:57.209  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 06:19:57.209  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:19:57.209  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@962bef3 not in the list
11-24 06:19:57.209  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.209  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.209  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:19:57.209  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.209  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.211  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.211  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:19:57.211  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:19:57.212  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:19:57.212  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:19:57.212  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:19:57.212  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82b87b0 not in the list
11-24 06:19:57.213  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-24 06:19:57.213  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 06:19:57.213  5585  5632 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 06:19:57.213  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 06:19:57.213  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 06:19:57.214  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-24 06:19:57.216  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 06:19:57.216  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-24 06:19:57.217  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 06:19:57.217  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 06:19:57.218  5585  5632 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 06:19:57.218  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 06:19:57.218  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 06:19:57.218  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-24 06:19:57.219  5585  5632 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 06:19:57.219  5585  5632 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 06:19:57.219  5585  5632 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-24 06:19:57.219  5585  5632 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 06:19:57.219  5585  5632 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 06:19:57.220  5585  5632 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 06:19:57.221  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:19:57.221  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30e5b99 added. We now have 3 listener(s)
11-24 06:19:57.221  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:19:57.224  5585  5632 D BluetoothAdapter: enable(): BT is already enabled..!
11-24 06:19:57.224   930  3861 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,11-24 06:19:57.224   930  3861 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 06:19:57.266  4536  4742 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-24 06:19:57.267  4536  4753 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 06:19:57.685  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 06:20:02.232  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 06:20:02.232  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e5bce5e added. We now have 4 listener(s)
11-24 06:20:02.233  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:20:02.248  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:02.249  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e5bce5e removed from the list
,11-24 06:20:02.249  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:20:02.250  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 06:20:02.251  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@abb23f added. We now have 4 listener(s)
11-24 06:20:02.251  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:20:02.254  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:20:02.255  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@abb23f removed from the list
11-24 06:20:02.255  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:20:02.256  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 06:20:02.257  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@524470c added. We now have 4 listener(s)
11-24 06:20:02.257  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:20:02.263   930  3689 D WifiService: setWifiEnabled: false pid=5585, uid=10077
11-24 06:20:02.263   930  3689 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 06:20:02.269   930  2920 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 06:20:02.270   930  2920 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 06:20:02.270   930  2920 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 06:20:02.270   930  2920 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 06:20:02.278  4536  4607 D BluetoothAdapterState: Current state: ON, message: 23
11-24 06:20:02.278  4536  4607 D BluetoothAdapterProperties: Setting state to 13
11-24 06:20:02.278  4536  4607 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 06:20:02.279  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:20:02.279  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 06:20:02.281  4536  4607 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 06:20:02.283  4536  4607 I BluetoothAdapterState: Entering PendingCommandState
,11-24 06:20:02.285  4536  4536 D BluetoothMapService: onReceive
,11-24 06:20:02.285  4536  4536 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-24 06:20:02.285  4536  4536 D BluetoothMapService: STATE_TURNING_OFF
,11-24 06:20:02.285  4536  4536 D BluetoothMapService: MAP Service closeService in
11-24 06:20:02.285  4536  4536 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 06:20:02.285  4536  4536 D ObexServerSockets0: shutdown(block = true)
11-24 06:20:02.286  4536  4536 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 06:20:02.287  4536  4795 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-24 06:20:02.287  4536  4753 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 06:20:02.287  4536  4796 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 06:20:02.286  4536  4536 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-24 06:20:02.289  4536  4536 I BtOppRfcommListener: stopping Accept Thread
11-24 06:20:02.289  4536  5271 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 06:20:02.291  4536  5271 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 06:20:02.292   930  5329 D DhcpClient: Clearing IP address
11-24 06:20:02.293  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:02.293   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 06:20:02.293  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 06:20:02.294  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:02.295  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 06:20:02.295  5585  5632 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-24 06:20:02.298  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:02.300   508   924 D CommandListener: Setting iface cfg
11-24 06:20:02.301  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:20:02.303   930  5330 D DhcpClient: Receive thread stopped
11-24 06:20:02.304  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:02.310   930   943 I ActivityManager: Start proc 5641:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 06:20:02.310  3517  5400 V NativeCrypto: Read error: ssl=0x7fa567a880: I/O error during system call, Connection timed out
11-24 06:20:02.311  4536  4611 D BluetoothAdapterProperties: Scan Mode:20
11-24 06:20:02.311  4536  4607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 06:20:02.312  3517  5400 V NativeCrypto: SSL shutdown failed: ssl=0x7fa567a880: I/O error during system call, Broken pipe
11-24 06:20:02.312   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 06:20:02.312   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 06:20:02.314  4536  4536 D HeadsetService: Received stop request...Stopping profile...
11-24 06:20:02.316   930   930 D RttService: SCAN_AVAILABLE : 1
11-24 06:20:02.316  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:02.316  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 06:20:02.316   930  3028 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 06:20:02.317  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:02.317  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 06:20:02.317   535   535 E Parcel  : Reading a NULL string not supported here.
,11-24 06:20:02.321  3085  5584 D BluetoothHeadset: Proxy object disconnected
,11-24 06:20:02.323  3085  3085 D HeadsetProfile: Bluetooth service disconnected
11-24 06:20:02.323   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:02.323   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:02.323  3757  3787 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:02.323   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:02.324   930  2922 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-24 06:20:02.324  4536  4536 D A2dpService: Received stop request...Stopping profile...
,11-24 06:20:02.325  4536  4778 D A2dpStateMachine: Exit Disconnected: -1
11-24 06:20:02.326   930   930 D BluetoothA2dp: Proxy object disconnected
11-24 06:20:02.326  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:02.326  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:02.326  3722  3862 W QCNEJ   : |CORE| network lost: 100
11-24 06:20:02.326  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:02.326  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:02.327  3722  3862 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 06:20:02.327  4536  4536 D HidService: Received stop request...Stopping profile...
11-24 06:20:02.327  4536  4536 D HidService: Stopping Bluetooth HidService
11-24 06:20:02.330  4536  4536 D HealthService: Received stop request...Stopping profile...
11-24 06:20:02.334  4536  4536 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 06:20:02.334  4536  4536 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 06:20:02.334  4536  4611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 06:20:02.334  4536  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:02.334  4536  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:02.334  4536  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:02.335  4536  4611 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 06:20:02.335  4536  4536 D PanService: Received stop request...Stopping profile...
11-24 06:20:02.337  4536  4536 D BluetoothMapService: Received stop request...Stopping profile...
11-24 06:20:02.337  4536  4536 D BluetoothMapService: stop()
11-24 06:20:02.338  4536  4536 D BluetoothMapAppObserver: deinitObservers()
11-24 06:20:02.338  4536  4536 D BluetoothMapAppObserver: removeReceiver()
,11-24 06:20:02.343  4536  4536 V BluetoothAdapterState: isTurningOff()=true
,11-24 06:20:02.343  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:02.343  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:02.343  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:02.343  4536  4536 D SapService: Received stop request...Stopping profile...
11-24 06:20:02.343  4536  4536 V SapService: stop()
,11-24 06:20:02.346  4536  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:02.346  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:02.346  4536  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:02.346  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:02.346  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:02.346  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:02.346  4536  4611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 06:20:02.346  4536  4742 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 06:20:02.346  4536  4536 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 06:20:02.346  4536  4742 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 06:20:02.346  4536  4742 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 06:20:02.346  4536  4536 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 06:20:02.346  4536  4742 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 06:20:02.347  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:02.347  4536  4536 V BluetoothAdapterState: isTurningOn()=false
,11-24 06:20:02.347  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:02.347  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:02.347  4536  4536 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 06:20:02.347  4536  4536 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 06:20:02.348  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:02.348  4536  4611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 06:20:02.348  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:02.348  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:02.348  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:02.348  4536  4611 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 06:20:02.348  4536  4536 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 06:20:02.348  4536  4536 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 06:20:02.349  4536  4536 D BluetoothMapService: MAP Service closeService in
11-24 06:20:02.349  4536  4536 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:02.349  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:02.349  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:02.349   930  2920 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 06:20:02.349  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:02.349  4536  4536 D BluetoothMapService: cleanup()
11-24 06:20:02.349  4536  4536 D BluetoothMapService: MAP Service closeService in
11-24 06:20:02.350  4536  4536 V BluetoothAdapterState: isTurningOff()=true
,11-24 06:20:02.350  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:02.350  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:02.350  4536  4536 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:02.350  4536  4607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 06:20:02.350  4536  4607 D BluetoothAdapterProperties: Setting state to 15
11-24 06:20:02.350  4536  4607 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 06:20:02.351  3085  3085 D BluetoothA2dp: Proxy object disconnected
11-24 06:20:02.351  3085  3935 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 06:20:02.352  3757  3993 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:02.352  4536  4607 I BluetoothAdapterState: Entering BleOnState
11-24 06:20:02.353  3085  3085 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 06:20:02.353  3085  3085 D PanProfile: Bluetooth service disconnected
11-24 06:20:02.353  3085  3085 D BluetoothMap: Proxy object disconnected
11-24 06:20:02.353  3085  3085 D MapProfile: Bluetooth service disconnected
11-24 06:20:02.353  3085  5584 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:02.353  3085  3935 D BluetoothPan: onBluetoothStateChange on: false
11-24 06:20:02.354  3085  3100 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 06:20:02.355   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 06:20:02.355   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:02.356  3085  5584 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 06:20:02.358   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:02.359  3085  3097 D BluetoothMap: onBluetoothStateChange: up=false
11-24 06:20:02.361   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:02.361  4536  4607 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-24 06:20:02.362  4536  4607 D BluetoothAdapterProperties: Setting state to 16
11-24 06:20:02.362  4536  4607 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 06:20:02.362  4536  4607 D BluetoothAdapterProperties: onBleDisable
11-24 06:20:02.362  4536  4607 I BluetoothAdapterState: Entering PendingCommandState
11-24 06:20:02.362  4536  4608 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 06:20:02.363  4536  4611 D BluetoothAdapterProperties: Scan Mode:20
11-24 06:20:02.364  4536  4742 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 06:20:02.364  4536  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:02.366  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:02.366  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 06:20:02.368  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:20:02.369   930  2920 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 06:20:02.373   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 06:20:02.394   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 06:20:02.394   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-24 06:20:02.395   508   924 D TetherController: Setting IP forward enable = 0
11-24 06:20:02.396   930  2922 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 06:20:02.396   930  2922 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 06:20:02.396  5641  5641 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-24 06:20:02.398   930  2920 D DhcpClient: doQuit
11-24 06:20:02.398   930  2920 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 06:20:02.398   930  5329 D DhcpClient: onQuitting
,11-24 06:20:02.399  3411  3411 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 06:20:02.399   930   947 D Tethering: MasterInitialState.processMessage what=3
11-24 06:20:02.401  5210  5210 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d8fbaa0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-24 06:20:02.403  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:02.403  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 06:20:02.404  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:02.404  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 06:20:02.405  4995  5018 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 06:20:02.405  4995  5018 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 06:20:02.405  4995  5018 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 06:20:02.405  4995  5018 E SarControlService: no key has been found,reset the power
11-24 06:20:02.405  4995  5030 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 06:20:02.405  4995  5030 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 06:20:02.405  4995  5030 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 06:20:02.406  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:20:02.406  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 06:20:02.407  5020  5020 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 06:20:02.411  4995  5030 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 06:20:02.411  4995  5030 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 06:20:02.411  4995  5030 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 06:20:02.413  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 06:20:02.413  5020  5020 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 06:20:02.415  5020  5034 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2576d86 HexData = [00000000ea03000000000000ffffffff]
11-24 06:20:02.415  5020  5034 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 06:20:02.415  5020  5034 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 06:20:02.415  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 06:20:02.416  4995  5005 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 06:20:02.422  5020  5034 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2576d86 HexData = [00000000eb03000000000000ffffffff]
,11-24 06:20:02.422  5020  5034 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 06:20:02.422  5020  5034 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 06:20:02.423  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 06:20:02.423  4995  5006 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 06:20:02.426  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 06:20:02.432   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e068d11:true
,11-24 06:20:02.432  3411  3411 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 06:20:02.434  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 06:20:02.438  3411  3411 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 06:20:02.447   930  3822 I ActivityManager: Start proc 5670:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 06:20:02.455  5641  5641 D LocalBluetoothProfileManager: Adding local MAP profile
,11-24 06:20:02.456   508   924 E Netd    : netlink response contains error (No such file or directory)
,11-24 06:20:02.457   508   924 D TetherController: Setting IP forward enable = 0
11-24 06:20:02.458  5641  5641 D BluetoothMap: Create BluetoothMap proxy object
,11-24 06:20:02.467  5641  5641 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 06:20:02.483  3411  3411 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 06:20:02.486  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,11-24 06:20:02.492  5670  5670 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 06:20:02.495   930  3829 I ActivityManager: Killing 4934:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-24 06:20:02.499  3411  3411 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 06:20:02.525   930  2920 D wifi    : In wifi stop Hal
,11-24 06:20:02.525  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 06:20:02.525   930  2920 D wifi    : halHandle = 0x7f8f19c080, mVM = 0x7fab80d140, mCls = 0x100a02
11-24 06:20:02.525   930  3408 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-24 06:20:02.525   930  3408 D WifiHAL : Got a signal to exit!!!
11-24 06:20:02.525   930  3408 I WifiHAL : Exit wifi_event_loop
11-24 06:20:02.526   930  2920 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 06:20:02.526   930  2920 E WifiHAL : Event processing terminated
11-24 06:20:02.526   930  2920 D wifi    : In wifi cleaned up handler
11-24 06:20:02.526   930  2920 I WifiHAL : Internal cleanup completed
,11-24 06:20:02.527  3986  4169 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 06:20:02.529  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:02.547   930  3408 D wifi    : set interface wlan0 flags (DOWN)
,11-24 06:20:02.547   930  2920 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 06:20:02.568  4536  4611 I bt_hci  : shut_down
,11-24 06:20:02.570  4536  4623 D bt_hwcfg: hw_epilog_process
,11-24 06:20:02.571  4536  4623 I bt_vendor: low_power_mode_cb
,11-24 06:20:02.574  4536  4623 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 06:20:02.574  4536  4623 I bt_vendor: epilog_cb
,11-24 06:20:02.574  4536  4623 I bt_hci  : epilog_finished_callback
,11-24 06:20:02.576  4536  4611 I bt_hci_h4: hal_close
11-24 06:20:02.577  4536  4611 I bt_userial_vendor: device fd = 54 close
,11-24 06:20:02.683  4536  4608 D bt_stack_manager: event_shut_down_stack finished.
,11-24 06:20:02.684  4536  4607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 06:20:02.686  4536  4607 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 06:20:02.686  4536  4536 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 06:20:02.686  4536  4536 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 06:20:02.687  4536  4536 D BtGatt.GattService: stop()
11-24 06:20:02.687  4536  4536 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 06:20:02.688  4536  4536 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:02.689  4536  4536 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:02.689  4536  4536 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:02.689  4536  4536 V BluetoothAdapterState: isBleTurningOff()=true
11-24 06:20:02.689  4536  4607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 06:20:02.689  4536  4607 D BluetoothAdapterProperties: Setting state to 10
11-24 06:20:02.689  4536  4607 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-24 06:20:02.691   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-24 06:20:02.692  4536  4607 I BluetoothAdapterState: Entering OffState
,11-24 06:20:02.698  4536  4536 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 06:20:02.698  4536  4536 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 06:20:02.698  4536  4536 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 06:20:02.700  4536  4608 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 06:20:02.705  4536  4536 I art     : System.exit called, status: 0
,11-24 06:20:02.705  4536  4536 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 06:20:02.739   930  3510 I ActivityManager: Process com.android.bluetooth (pid 4536) has died
,11-24 06:20:02.750   930   947 D Tethering: InitialState.processMessage what=4
,11-24 06:20:02.753   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 06:20:02.767  5670  5670 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 06:20:02.767  5670  5670 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 06:20:02.767  5670  5670 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 06:20:02.767  5670  5670 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 06:20:02.767  5670  5670 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 06:20:02.767  5670  5670 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:20:02.767  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 06:20:02.768  5670  5670 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 06:20:02.768  5670  5670 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:20:02.768  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 06:20:02.783  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 06:20:02.798   930  3834 I ActivityManager: Start proc 5705:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
11-24 06:20:02.799  5641  5641 D DockEventReceiver: finishStartingService: stopping service
11-24 06:20:02.802   930  3754 I ActivityManager: Killing 5355:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 06:20:02.879  5705  5705 D AdapterServiceConfig: Adding HeadsetService
11-24 06:20:02.879  5705  5705 D AdapterServiceConfig: Adding A2dpService
11-24 06:20:02.879  5705  5705 D AdapterServiceConfig: Adding HidService
11-24 06:20:02.879  5705  5705 D AdapterServiceConfig: Adding HealthService
11-24 06:20:02.880  5705  5705 D AdapterServiceConfig: Adding PanService
11-24 06:20:02.880  5705  5705 D AdapterServiceConfig: Adding GattService
11-24 06:20:02.880  5705  5705 D AdapterServiceConfig: Adding BluetoothMapService
11-24 06:20:02.880  5705  5705 D AdapterServiceConfig: Adding SapService
,11-24 06:20:02.883   930  3530 I ActivityManager: Killing 5368:com.android.chrome/u0a39 (adj 15): empty #17
,11-24 06:20:02.906  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 06:20:02.918  3656  3656 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 06:20:02.923  3656  3656 D SystemUpdateService: onCreate
,11-24 06:20:02.927  3656  3656 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 06:20:02.937  3656  3656 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 06:20:02.943  3656  5353 I iu.UploadsManager: num queued entries: 0
,11-24 06:20:02.944  3656  5353 I iu.UploadsManager: num updated entries: 0
,11-24 06:20:02.948  3656  3656 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 06:20:02.950  3656  3656 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 06:20:02.956  3656  5717 I SystemUpdateService: active receiver: enabled
11-24 06:20:02.963   930  3510 I ActivityManager: Start proc 5719:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-24 06:20:02.961  3656  5353 I iu.SyncManager: NEXT; no task
11-24 06:20:02.967  3656  5717 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-24 06:20:02.981  3656  5717 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-24 06:20:02.982  3656  5717 I SystemUpdateService: now status is 0 (complete)
11-24 06:20:02.982  3656  5717 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 06:20:02.982  3656  5717 I SystemUpdateService: file has been verified
11-24 06:20:02.983  3656  5717 I SystemUpdateService: OTA package size = 21989297
,11-24 06:20:02.997  5719  5719 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 06:20:03.002  5719  5719 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 06:20:03.016  5719  5719 D SprintDMHelper: simOperator: 
,11-24 06:20:03.016  5719  5719 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 06:20:03.019  3656  5717 I SystemUpdateService: showing system update notification
,11-24 06:20:03.028   930  3099 I ActivityManager: Start proc 5731:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 06:20:03.051  3656  3656 D SystemUpdateService: onDestroy
,11-24 06:20:03.052   930  3822 I ActivityManager: Killing 5385:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-24 06:20:03.128  4969  5745 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 06:20:03.137   930   941 I ActivityManager: Start proc 5746:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-24 06:20:03.139   930  3822 I ActivityManager: Killing 5210:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 06:20:03.190  5746  5746 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-24 06:20:03.376  5670  5693 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 06:20:03.389   930  3809 I ActivityManager: Killing 4634:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 06:20:03.408   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8bd6398:true
,11-24 06:20:03.439   930  3510 I ActivityManager: Start proc 5760:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 06:20:03.479  5760  5760 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 06:20:03.490   930  3822 I ActivityManager: Killing 5436:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 06:20:05.772   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 06:20:05.773   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 06:20:07.298   930  3754 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,11-24 06:20:07.299   930  3754 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 06:20:07.307   508   924 D SoftapController: Softap fwReload - Ok
,11-24 06:20:07.316   508   924 D CommandListener: Setting iface cfg
,11-24 06:20:07.316   508   924 D CommandListener: Trying to bring down wlan0
11-24 06:20:07.318   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-24 06:20:07.323   930  2920 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 06:20:08.005   930  2920 D wifi    : set interface wlan0 flags (UP)
,11-24 06:20:08.009   930  2920 I WifiHAL : Initializing wifi
11-24 06:20:08.009   930  2920 I WifiHAL : Creating socket
,11-24 06:20:08.013   930  2920 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 06:20:08.013   930  2920 D wifi    : Did set static halHandle = 0x7f8f19c080
11-24 06:20:08.013   930  2920 D wifi    : halHandle = 0x7f8f19c080, mVM = 0x7fab80d140, mCls = 0x1916
,11-24 06:20:08.013   930  2920 D wifi    : array field set
,11-24 06:20:08.013   930  2920 I WifiNative-HAL: interface[0] = wlan0
11-24 06:20:08.015   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 06:20:08.016   930  5778 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547861676160
11-24 06:20:08.016   930  5778 D wifi    : waitForHalEvents called, vm = 0x7fab80d140, obj = 0x1916, env = 0x7f9017a300
,11-24 06:20:08.077  5779  5779 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 06:20:08.091  5779  5779 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 06:20:08.117   930  2920 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 06:20:08.119  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:08.135  5779  5779 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 06:20:08.135  5779  5779 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 06:20:08.157   930  2920 D WifiConfigStore: Loading config and enabling all networks 
,11-24 06:20:08.158  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:08.158  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 06:20:08.158  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 06:20:08.159  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 06:20:08.172   930  2920 D WifiConfigStore: loaded 0 passpoint configs
11-24 06:20:08.173   930  2920 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 06:20:08.173   930  2920 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 06:20:08.175   930  2920 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 06:20:08.176   930  2920 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 06:20:08.177   930  2920 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,11-24 06:20:08.177   930  2920 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 06:20:08.177   930  2920 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 06:20:08.183   930  2920 D WifiNative-HAL: Setting external_sim to 1
,11-24 06:20:08.183  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 06:20:08.184   930  2920 D wifi    : setting dfs flag to true, 0x7f9430f3e0
11-24 06:20:08.184   930  2920 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 06:20:08.185   930  2920 D wifi    : setting scan oui 0x7f9430f3e0
,11-24 06:20:08.185   930  2920 D WifiHAL : Sending mac address OUI
,11-24 06:20:08.191   930  2920 E native  : do suspend false
,11-24 06:20:08.201   930  2920 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 06:20:08.202   930   930 D RttService: SCAN_AVAILABLE : 3
11-24 06:20:08.202   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 06:20:08.202   930  3028 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 06:20:08.203   508   924 D CommandListener: Setting iface cfg
,11-24 06:20:08.209   930  2919 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-24 06:20:08.209   930  2919 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 06:20:08.215   930  2919 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 06:20:08.215   930  2919 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 06:20:08.258   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=222857 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=43 mControllerEnergyUsed=163 }
,11-24 06:20:11.316  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 06:20:11.334  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 06:20:11.351  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 06:20:11.385   930  2920 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 06:20:11.386   930  2920 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 06:20:11.387   930  2920 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 06:20:11.402   930  2920 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 06:20:11.443   930  2920 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 06:20:11.446  5779  5779 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 06:20:11.894  5779  5779 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 06:20:11.940  5779  5779 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 06:20:11.942  5779  5779 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 06:20:11.952   930  2920 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 06:20:11.953   930  2920 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 06:20:11.953   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 06:20:11.972   930  2920 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 06:20:11.984   508   924 D CommandListener: Setting iface cfg
,11-24 06:20:11.989   930  2920 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 06:20:11.998   930  5785 D DhcpClient: Receive thread started
,11-24 06:20:12.002   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 06:20:12.002   930  2920 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 06:20:12.002   930  2922 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 06:20:12.098   930  2920 E native  : do suspend false
,11-24 06:20:12.127   930  5784 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 06:20:12.141   930  5785 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172616, domain null
,11-24 06:20:12.142   930  5784 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172616 seconds
,11-24 06:20:12.144   930  5784 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 06:20:12.161   930  5785 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 06:20:12.162   930  5784 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 06:20:12.165   508   924 D CommandListener: Setting iface cfg
,11-24 06:20:12.172   930  2920 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 06:20:12.174   930  5784 D DhcpClient: Scheduling renewal in 86399s
,11-24 06:20:12.200   930  2920 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 06:20:12.204   930  2920 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 06:20:12.205   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 06:20:12.207   930  2922 D ConnectivityService: Adding iface wlan0 to network 101
,11-24 06:20:12.228   930  2920 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 06:20:12.252   930  2922 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 06:20:12.253   930  2922 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 06:20:12.255   930  2922 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 06:20:12.258   930  2922 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 06:20:12.262   930  2922 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 06:20:12.270   930  2922 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 06:20:12.275   930  2922 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 06:20:12.276   930  2922 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 06:20:12.276   930  2922 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 06:20:12.276   930  2920 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 06:20:12.276   930  2922 D ConnectivityService:    accepting network in place of null
11-24 06:20:12.276   930  2920 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 06:20:12.276   930  2922 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 06:20:12.285   930  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=226884, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 06:20:12.297   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 06:20:12.304   930  3861 D WifiService: setWifiEnabled: false pid=5585, uid=10077
,11-24 06:20:12.304   930  3861 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 06:20:12.305   930  2920 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 06:20:12.305   930  2920 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 06:20:12.305   930  2920 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 06:20:12.306   930  2920 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 06:20:12.314   930  5784 D DhcpClient: Clearing IP address
,11-24 06:20:12.320   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 06:20:12.320   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-24 06:20:12.325   508   924 D CommandListener: Setting iface cfg
,11-24 06:20:12.334   930  5785 D DhcpClient: Receive thread stopped
,11-24 06:20:12.334   930  2922 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 06:20:12.334   930  2922 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 06:20:12.335   930  2922 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-24 06:20:12.336  3722  3862 W QCNEJ   : |CORE| network available: 101
,11-24 06:20:12.336   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 06:20:12.336   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 06:20:12.341  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:12.341  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 06:20:12.342  3722  3862 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 06:20:12.342   930  2922 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-24 06:20:12.343  3722  3862 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 06:20:12.344   930   930 D RttService: SCAN_AVAILABLE : 1
11-24 06:20:12.344  3722  3862 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-24 06:20:12.344   930   947 D Tethering: MasterInitialState.processMessage what=3
11-24 06:20:12.344   930  3028 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 06:20:12.345  3722  3862 W QCNEJ   : |CORE| network lost: 101
11-24 06:20:12.345  3722  3862 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 06:20:12.347   930  2920 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 06:20:12.348  3656  3656 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 06:20:12.349   535   535 E Parcel  : Reading a NULL string not supported here.
11-24 06:20:12.352  3656  3656 D SystemUpdateService: onCreate
,11-24 06:20:12.355   930  2920 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 06:20:12.362  3656  3656 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 06:20:12.366  3656  5796 I SystemUpdateService: active receiver: enabled
,11-24 06:20:12.370   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 06:20:12.371  3656  5796 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 06:20:12.379  3656  5796 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-24 06:20:12.379  3656  5796 I SystemUpdateService: now status is 0 (complete)
11-24 06:20:12.379  3656  5796 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 06:20:12.379  3656  5796 I SystemUpdateService: file has been verified
11-24 06:20:12.380  3656  5796 I SystemUpdateService: OTA package size = 21989297
,11-24 06:20:12.382  3656  3656 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 06:20:12.384  3656  3656 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 06:20:12.386  5719  5719 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 06:20:12.391   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 06:20:12.391   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-24 06:20:12.391  5719  5719 D SprintDMHelper: simOperator: 
11-24 06:20:12.392  5719  5719 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 06:20:12.392   930  2922 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 06:20:12.392   930  2922 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 06:20:12.395   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-24 06:20:12.396   930  2920 D DhcpClient: doQuit
11-24 06:20:12.396   930  2920 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 06:20:12.396   930  5784 D DhcpClient: onQuitting
,11-24 06:20:12.397  5779  5779 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 06:20:12.398  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:12.398  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 06:20:12.398  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:12.399  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 06:20:12.405  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:20:12.406  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 06:20:12.411  5779  5779 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 06:20:12.419  3656  3656 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 06:20:12.421  3656  3656 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 06:20:12.421  3656  5796 I SystemUpdateService: showing system update notification
,11-24 06:20:12.436  3656  3656 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 06:20:12.437  5779  5779 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-24 06:20:12.438  3656  3656 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 06:20:12.440  5719  5719 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 06:20:12.444  5719  5719 D SprintDMHelper: simOperator: 
11-24 06:20:12.444  5719  5719 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 06:20:12.454  5779  5779 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 06:20:12.456   508   924 E Netd    : netlink response contains error (No such file or directory)
11-24 06:20:12.461  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 06:20:12.462   930  2920 D wifi    : In wifi stop Hal
11-24 06:20:12.462   930  2920 D wifi    : halHandle = 0x7f8f19c080, mVM = 0x7fab80d140, mCls = 0x1916
,11-24 06:20:12.462   930  5778 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-24 06:20:12.462   930  5778 D WifiHAL : Got a signal to exit!!!
11-24 06:20:12.462   930  5778 I WifiHAL : Exit wifi_event_loop
11-24 06:20:12.463   930  2920 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-24 06:20:12.464   930  2920 E WifiHAL : Event processing terminated
11-24 06:20:12.464   930  2920 D wifi    : In wifi cleaned up handler
11-24 06:20:12.464   930  2920 I WifiHAL : Internal cleanup completed
11-24 06:20:12.464  3986  4169 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 06:20:12.465  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:12.473  3656  5807 I SystemUpdateService: active receiver: enabled
,11-24 06:20:12.484   930  5778 D wifi    : set interface wlan0 flags (DOWN)
11-24 06:20:12.485   930  2920 D WifiNative-HAL: HAL event thread stopped successfully
11-24 06:20:12.485  3656  5807 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 06:20:12.487  3656  5807 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-24 06:20:12.487  3656  5807 I SystemUpdateService: now status is 0 (complete)
11-24 06:20:12.487  3656  5807 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 06:20:12.487  3656  5807 I SystemUpdateService: file has been verified
11-24 06:20:12.487  3656  5807 I SystemUpdateService: OTA package size = 21989297
,11-24 06:20:12.492  3656  5807 I SystemUpdateService: showing system update notification
,11-24 06:20:12.502  3656  3656 D SystemUpdateService: onDestroy
,11-24 06:20:12.694   930   947 D Tethering: InitialState.processMessage what=4
,11-24 06:20:12.704   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 06:20:13.339   930  2922 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 06:20:15.775   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:16.778   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:17.291   930  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-24 06:20:17.293   930  2922 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 06:20:17.344   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ccbb204:true
,11-24 06:20:17.345  5705  5705 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 06:20:17.350  5705  5705 I bt_bluedroid: init
,11-24 06:20:17.350  5705  5809 I BluetoothAdapterState: Entering OffState
,11-24 06:20:17.354  5705  5810 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-24 06:20:17.354  5705  5810 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 06:20:17.355  5705  5810 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 06:20:17.355  5705  5810 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 06:20:17.356  5705  5705 I bt_bluedroid: get_profile_interface socket
,11-24 06:20:17.359  5705  5813 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 06:20:17.360  5705  5705 I bt_bluedroid: get_profile_interface sdp
11-24 06:20:17.362  5705  5813 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 06:20:17.368  5705  5716 I bt_bluedroid: config_hci_snoop_log
,11-24 06:20:17.369   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 06:20:17.376  5705  5809 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 06:20:17.377  5705  5809 D BluetoothAdapterProperties: Setting state to 14
11-24 06:20:17.377  5705  5809 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 06:20:17.379  5705  5809 D BluetoothBondStateMachine: make
,11-24 06:20:17.382  5705  5814 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 06:20:17.385  5705  5809 I BluetoothAdapterState: Entering PendingCommandState
,11-24 06:20:17.386  5705  5705 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 06:20:17.390  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:17.390  5705  5705 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 06:20:17.391  5705  5705 D BtGatt.GattService: Received start request. Starting profile...
,11-24 06:20:17.392  5705  5705 D BtGatt.GattService: start()
11-24 06:20:17.392  5705  5705 I bt_bluedroid: get_profile_interface gatt
11-24 06:20:17.393  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:17.393  5705  5705 D BtGatt.AdvertiseManager: advertise manager created
,11-24 06:20:17.401  5705  5705 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:17.401  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:17.401  5705  5705 V BluetoothAdapterState: isBleTurningOn()=true
,11-24 06:20:17.401  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 06:20:17.402  5705  5809 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-24 06:20:17.404  5705  5809 I bt_bluedroid: bt_bluedroid
,11-24 06:20:17.404  5705  5810 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 06:20:17.404  5705  5810 I bt_hci  : start_up
,11-24 06:20:17.412  5705  5810 I bt_vendor: alloc value 0xf3df8871
,11-24 06:20:17.412  5705  5810 I bt_vendor: init
11-24 06:20:17.412  5705  5810 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 06:20:17.412  5705  5810 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 06:20:17.525  5705  5810 D bt_hci  : start_up starting async portion
,11-24 06:20:17.525  5705  5817 I bt_hci  : event_finish_startup
11-24 06:20:17.525  5705  5817 I bt_hci_h4: hal_open
11-24 06:20:17.525  5705  5817 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 06:20:17.529  5705  5817 I bt_userial_vendor: device fd = 54 open
,11-24 06:20:17.522  5818  5818 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 06:20:17.550  5705  5817 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 06:20:17.553  5705  5817 D bt_hwcfg: Chipset BCM4358A3
,11-24 06:20:17.553  5705  5817 D bt_hwcfg: Target name = [BCM4358A3]
11-24 06:20:17.553  5705  5817 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 06:20:17.779   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:18.319  5705  5817 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 06:20:18.320  5705  5817 D bt_hwcfg: Settlement delay -- 100 ms
11-24 06:20:18.320  5705  5817 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 06:20:18.459  5705  5817 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 06:20:18.459  5705  5817 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-24 06:20:18.461  5705  5817 I bt_hwcfg: vendor lib fwcfg completed
11-24 06:20:18.462  5705  5817 I bt_vendor: firmware callback
11-24 06:20:18.462  5705  5817 I bt_hci  : firmware_config_callback
,11-24 06:20:18.474  5705  5820 I bt_btu  : btu_task pending for preload complete event
,11-24 06:20:18.474  5705  5820 I bt_btu_task: Bluetooth chip preload is complete
11-24 06:20:18.474  5705  5820 I bt_btu  : btu_task received preload complete event
,11-24 06:20:18.482  5705  5820 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 06:20:18.482  5705  5820 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 06:20:18.483  5705  5820 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 06:20:18.484  5705  5820 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 06:20:18.484  5705  5820 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 06:20:18.484  5705  5820 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 06:20:18.484  5705  5820 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 06:20:18.581  5705  5820 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d76549
,11-24 06:20:18.582  5705  5820 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d76549 
,11-24 06:20:18.602  5705  5813 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 06:20:18.605  5705  5813 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 06:20:18.606  5705  5813 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 06:20:18.609  5705  5813 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 06:20:18.612  5705  5813 D BluetoothAdapterProperties: Scan Mode:20
11-24 06:20:18.613  5705  5813 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 06:20:18.613  5705  5813 D bt_hci  : do_postload posting postload work item
11-24 06:20:18.613  5705  5817 I bt_hci  : event_postload
11-24 06:20:18.613  5705  5817 I bt_vendor: sco_config_cb
11-24 06:20:18.613  5705  5817 I bt_hci  : sco_config_callback postload finished.
,11-24 06:20:18.619  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:18.620  5705  5813 D bt_bte_conf: Device ID record 1 : primary
,11-24 06:20:18.621  5705  5813 D bt_bte_conf:   vendorId            = 000f
,11-24 06:20:18.621  5705  5813 D bt_bte_conf:   vendorIdSource      = 0001
,11-24 06:20:18.621  5705  5813 D bt_bte_conf:   product             = 1200
,11-24 06:20:18.621  5705  5813 D bt_bte_conf:   version             = 1436
11-24 06:20:18.621  5705  5813 D bt_bte_conf:   clientExecutableURL = 
11-24 06:20:18.621  5705  5813 D bt_bte_conf:   serviceDescription  = 
,11-24 06:20:18.621  5705  5813 D bt_bte_conf:   documentationURL    = 
11-24 06:20:18.621  5705  5813 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 06:20:18.622  5705  5810 D bt_stack_manager: event_start_up_stack finished
11-24 06:20:18.622  5705  5809 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 06:20:18.622  5705  5817 I bt_vendor: low_power_mode_cb
11-24 06:20:18.623  5705  5809 D BluetoothAdapterProperties: Setting state to 15
11-24 06:20:18.623  5705  5809 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 06:20:18.624  5705  5809 I BluetoothAdapterState: Entering BleOnState
,11-24 06:20:18.630  5705  5809 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 06:20:18.630  5705  5809 D BluetoothAdapterProperties: Setting state to 11
11-24 06:20:18.630  5705  5809 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 06:20:18.637  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:18.638  5705  5705 D HeadsetService: Received start request. Starting profile...
11-24 06:20:18.641  5705  5705 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 06:20:18.641  5705  5705 D HeadsetStateMachine: make
,11-24 06:20:18.646  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:18.658  5705  5705 D HeadsetStateMachine: max_hf_connections = 1
11-24 06:20:18.658  5705  5705 I bt_bluedroid: get_profile_interface handsfree
,11-24 06:20:18.659  5705  5813 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 06:20:18.661  5705  5813 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-24 06:20:18.662  5705  5809 I BluetoothAdapterState: Entering PendingCommandState
,11-24 06:20:18.665  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:18.665  5705  5705 D A2dpService: Received start request. Starting profile...
11-24 06:20:18.666  5705  5705 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-24 06:20:18.666  5705  5705 I bt_bluedroid: get_profile_interface avrcp
,11-24 06:20:18.673  5705  5705 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 06:20:18.673  5705  5705 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 06:20:18.673  5705  5705 D A2dpStateMachine: make
11-24 06:20:18.674  5705  5705 I bt_bluedroid: get_profile_interface a2dp
,11-24 06:20:18.676  5705  5813 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 06:20:18.677  5705  5828 D A2dpStateMachine: Enter Disconnected: -2
11-24 06:20:18.678  5705  5705 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 06:20:18.678  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:18.680  5705  5705 D HidService: Received start request. Starting profile...
11-24 06:20:18.680  5705  5705 I bt_bluedroid: get_profile_interface hidhost
11-24 06:20:18.680  5705  5705 D HidService: setHidService(): set to: null
11-24 06:20:18.680  5705  5813 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d5756d
11-24 06:20:18.680  5705  5813 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 06:20:18.681  5705  5705 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 06:20:18.682  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:18.682  5705  5705 D HealthService: Received start request. Starting profile...
,11-24 06:20:18.684  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 06:20:18.684  5705  5705 I bt_bluedroid: get_profile_interface health
,11-24 06:20:18.684  5641  5641 D BluetoothInputDevice: Proxy object connected
11-24 06:20:18.685  5641  5641 D HidProfile: Bluetooth service connected
11-24 06:20:18.687  5705  5705 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 06:20:18.688  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:18.689  5641  5641 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 06:20:18.689  5705  5705 D PanService: Received start request. Starting profile...
11-24 06:20:18.689  5641  5641 D PanProfile: Bluetooth service connected
11-24 06:20:18.689  5705  5705 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-24 06:20:18.690  5705  5705 I bt_bluedroid: get_profile_interface pan
11-24 06:20:18.690  5705  5813 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 06:20:18.692  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:18.693  5641  5641 D BluetoothMap: Proxy object connected
,11-24 06:20:18.694  5705  5705 D BluetoothMapService: Received start request. Starting profile...
11-24 06:20:18.694  5705  5705 D BluetoothMapService: start()
11-24 06:20:18.694  5641  5641 D MapProfile: Bluetooth service connected
11-24 06:20:18.694  5641  5641 D BluetoothMap: getConnectedDevices()
11-24 06:20:18.695  5641  5641 D BluetoothMap: Bluetooth is Not enabled
,11-24 06:20:18.696  5705  5705 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 06:20:18.698  5705  5705 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 06:20:18.698  5705  5705 D BluetoothMapAppObserver: createReceiver()
11-24 06:20:18.699  5705  5705 D BluetoothMapAppObserver: initObservers()
,11-24 06:20:18.699  5705  5705 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 06:20:18.705  5705  5705 V SapService: SapBinder()
11-24 06:20:18.705  5705  5705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:18.706  5705  5705 D SapService: Received start request. Starting profile...
11-24 06:20:18.706  5705  5705 V SapService: start()
11-24 06:20:18.707  5705  5705 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:18.707  5705  5705 V BluetoothAdapterState: isTurningOn()=true
,11-24 06:20:18.707  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:18.707  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:18.708  5705  5825 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isTurningOff()=false
,11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:18.708  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:18.709  5705  5705 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:18.709  5705  5705 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:18.709  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:18.709  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:18.709  5705  5705 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:18.709  5705  5705 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:18.709  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:18.709  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:18.710  5705  5705 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:18.710  5705  5705 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:18.710  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:18.710  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:18.710  5705  5809 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 06:20:18.710  5705  5809 D BluetoothAdapterProperties: ScanMode =  20
11-24 06:20:18.710  5705  5809 D BluetoothAdapterProperties: State =  11
11-24 06:20:18.712  5705  5813 D BluetoothAdapterProperties: Scan Mode:21
11-24 06:20:18.712  5705  5809 D BluetoothAdapterProperties: Setting state to 12
11-24 06:20:18.712  5705  5809 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-24 06:20:18.713  5705  5809 I BluetoothAdapterState: Entering OnState
11-24 06:20:18.713  3085  5584 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 06:20:18.714  5705  5813 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 06:20:18.714  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:18.718  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 06:20:18.720  3085  3085 D BluetoothInputDevice: Proxy object connected
11-24 06:20:18.720  3085  3085 D HidProfile: Bluetooth service connected
11-24 06:20:18.720  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 06:20:18.720  3757  3993 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:18.721  3085  3935 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:18.722  5641  5658 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 06:20:18.723  3085  3097 D BluetoothPan: onBluetoothStateChange on: true
11-24 06:20:18.724  5705  5705 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 06:20:18.724  3085  3085 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 06:20:18.724  3085  5584 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 06:20:18.724  5705  5705 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 06:20:18.724  3085  3085 D PanProfile: Bluetooth service connected
11-24 06:20:18.726  5705  5705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 06:20:18.726   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 06:20:18.727  5641  5651 D BluetoothPan: onBluetoothStateChange on: true
11-24 06:20:18.727   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 06:20:18.727  3085  3935 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 06:20:18.728  5705  5705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 06:20:18.729  5641  5658 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 06:20:18.730  5705  5705 D ObexServerSockets: Succeed to create listening sockets 
11-24 06:20:18.730  5705  5705 D ObexServerSockets0: startAccept()
,11-24 06:20:18.730  5705  5705 D ObexServerSockets0: prepareForNewConnect()
11-24 06:20:18.731  5641  5651 D BluetoothMap: onBluetoothStateChange: up=true
11-24 06:20:18.731   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:18.731  3085  3097 D BluetoothMap: onBluetoothStateChange: up=true
11-24 06:20:18.733  5705  5705 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 06:20:18.733  5705  5705 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-24 06:20:18.733   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:18.733  3085  3085 D BluetoothMap: Proxy object connected
11-24 06:20:18.734  3085  3085 D MapProfile: Bluetooth service connected
11-24 06:20:18.734  3085  3085 D BluetoothMap: getConnectedDevices()
11-24 06:20:18.735   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 06:20:18.736  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 06:20:18.736  5705  5833 D ObexServerSockets0: Accepting socket connection...
11-24 06:20:18.737  5641  5641 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-24 06:20:18.737  5705  5834 D ObexServerSockets0: Accepting socket connection...
11-24 06:20:18.738  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:20:18.738   930   930 D BluetoothA2dp: Proxy object connected
11-24 06:20:18.738  5705  5705 D BluetoothMapService: onReceive
11-24 06:20:18.738  3085  3085 D BluetoothA2dp: Proxy object connected
11-24 06:20:18.738  5705  5705 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 06:20:18.739  5705  5705 D BluetoothMapService: STATE_ON
,11-24 06:20:18.740  5641  5641 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 06:20:18.746  5705  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 06:20:18.748  5705  5837 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-24 06:20:18.748  5705  5837 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 06:20:18.749  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 06:20:18.753  5641  5641 D BluetoothA2dp: Proxy object connected
,11-24 06:20:18.758  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 06:20:18.760  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,11-24 06:20:18.765  5641  5641 D BluetoothPbap: Proxy object connected
,11-24 06:20:18.766  5641  5641 D PbapServerProfile: Bluetooth service connected
11-24 06:20:18.767  5705  5705 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 06:20:18.767  5705  5705 D ObexServerSockets0: prepareForNewConnect()
11-24 06:20:18.769  3085  3085 D BluetoothPbap: Proxy object connected
11-24 06:20:18.769  3085  3085 D PbapServerProfile: Bluetooth service connected
,11-24 06:20:18.777  5705  5841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 06:20:18.780   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:18.794  5705  5845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 06:20:18.796  5705  5845 I BtOppRfcommListener: Accept thread started.
,11-24 06:20:18.823  3085  3097 D BluetoothHeadset: Proxy object connected
11-24 06:20:18.823  3085  3085 D HeadsetProfile: Bluetooth service connected
11-24 06:20:18.823   930   930 D BluetoothHeadset: Proxy object connected
,11-24 06:20:18.823   930   930 D BluetoothHeadset: Proxy object connected
11-24 06:20:18.823  3757  3799 D BluetoothHeadset: Proxy object connected
11-24 06:20:18.823   930   930 D BluetoothHeadset: Proxy object connected
,11-24 06:20:18.827   930   947 D BluetoothHeadset: Proxy object connected
,11-24 06:20:18.831   930   947 D BluetoothHeadset: Proxy object connected
,11-24 06:20:18.834   930   947 D BluetoothHeadset: Proxy object connected
,11-24 06:20:18.844  5641  5658 D BluetoothHeadset: Proxy object connected
,11-24 06:20:18.845  5641  5641 D HeadsetProfile: Bluetooth service connected
,11-24 06:20:19.783   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:20.282   930  2922 D ConnectivityService: handlePromptUnvalidated 101
,11-24 06:20:20.784   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 06:20:22.325  5705  5809 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 06:20:22.326  5705  5809 D BluetoothAdapterProperties: Setting state to 13
,11-24 06:20:22.326  5705  5809 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 06:20:22.327  5705  5809 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 06:20:22.329  5705  5809 I BluetoothAdapterState: Entering PendingCommandState
11-24 06:20:22.333  5705  5705 D BluetoothMapService: onReceive
,11-24 06:20:22.333  5705  5705 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 06:20:22.333  5705  5705 D BluetoothMapService: STATE_TURNING_OFF
11-24 06:20:22.335  5705  5705 D BluetoothMapService: MAP Service closeService in
11-24 06:20:22.335  5705  5705 D BluetoothMapMasInstance0: MAP Service shutdown
,11-24 06:20:22.335  5705  5705 D ObexServerSockets0: shutdown(block = true)
11-24 06:20:22.337  5705  5705 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 06:20:22.338  5705  5813 D BluetoothAdapterProperties: Scan Mode:20
,11-24 06:20:22.340  5705  5809 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 06:20:22.340  5705  5833 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 06:20:22.341  5705  5705 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 06:20:22.341  5705  5834 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 06:20:22.342  5705  5822 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 06:20:22.343  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:22.343  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 06:20:22.345  5705  5705 I BtOppRfcommListener: stopping Accept Thread
11-24 06:20:22.345  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 06:20:22.345  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 06:20:22.346  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 06:20:22.347  5705  5845 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 06:20:22.347  5705  5845 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 06:20:22.348  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:22.357  5705  5705 D HeadsetService: Received stop request...Stopping profile...
,11-24 06:20:22.361  3085  3097 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:22.361   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:22.361   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:22.361  5705  5705 D A2dpService: Received stop request...Stopping profile...
11-24 06:20:22.361  3757  3787 D BluetoothHeadset: Proxy object disconnected
,11-24 06:20:22.362  5705  5828 D A2dpStateMachine: Exit Disconnected: -1
11-24 06:20:22.362  5641  5658 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:22.363   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 06:20:22.364   930   930 D BluetoothA2dp: Proxy object disconnected
,11-24 06:20:22.366  5705  5705 D HidService: Received stop request...Stopping profile...
11-24 06:20:22.366  5705  5705 D HidService: Stopping Bluetooth HidService
11-24 06:20:22.372  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 06:20:22.372  5641  5641 D DockEventReceiver: finishStartingService: stopping service
11-24 06:20:22.372  3085  3085 D HeadsetProfile: Bluetooth service disconnected
11-24 06:20:22.373  3085  3085 D BluetoothA2dp: Proxy object disconnected
11-24 06:20:22.373  3085  3085 D BluetoothInputDevice: Proxy object disconnected
,11-24 06:20:22.373  3085  3085 D HidProfile: Bluetooth service disconnected
,11-24 06:20:22.373  5641  5641 D HeadsetProfile: Bluetooth service disconnected
11-24 06:20:22.374  5641  5641 D BluetoothA2dp: Proxy object disconnected
,11-24 06:20:22.374  5641  5641 D BluetoothInputDevice: Proxy object disconnected
11-24 06:20:22.374  5641  5641 D HidProfile: Bluetooth service disconnected
,11-24 06:20:22.376  5705  5705 D HealthService: Received stop request...Stopping profile...
11-24 06:20:22.377  5705  5705 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:22.378  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:22.378  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:22.378  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 06:20:22.380  5705  5705 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 06:20:22.380  5705  5705 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 06:20:22.380  5705  5813 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 06:20:22.380  5705  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:22.380  5705  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 06:20:22.380  5705  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:22.381  5705  5813 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 06:20:22.381  5705  5705 D PanService: Received stop request...Stopping profile...
11-24 06:20:22.382  5705  5705 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:22.382  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:22.382  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:22.382  3085  3085 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 06:20:22.382  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:22.382  3085  3085 D PanProfile: Bluetooth service disconnected
,11-24 06:20:22.383  5641  5641 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 06:20:22.383  5641  5641 D PanProfile: Bluetooth service disconnected
11-24 06:20:22.383  5705  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:22.384  5705  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 06:20:22.384  5705  5705 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:22.384  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:22.384  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:22.384  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 06:20:22.384  5705  5813 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 06:20:22.384  5705  5820 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 06:20:22.384  5705  5705 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 06:20:22.384  5705  5820 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 06:20:22.384  5705  5820 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 06:20:22.384  5705  5705 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-24 06:20:22.384  5705  5820 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 06:20:22.385  5705  5813 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 06:20:22.388  5641  5641 D BluetoothPbap: Proxy object disconnected
11-24 06:20:22.389  5641  5641 D PbapServerProfile: Bluetooth service disconnected
11-24 06:20:22.389  3085  3085 D BluetoothPbap: Proxy object disconnected
,11-24 06:20:22.389  3085  3085 D PbapServerProfile: Bluetooth service disconnected
11-24 06:20:22.389  5705  5705 D BluetoothMapService: Received stop request...Stopping profile...
,11-24 06:20:22.389  5705  5705 D BluetoothMapService: stop()
11-24 06:20:22.391  5705  5705 D BluetoothMapAppObserver: deinitObservers()
11-24 06:20:22.391  5705  5705 D BluetoothMapAppObserver: removeReceiver()
,11-24 06:20:22.396  3085  3085 D BluetoothMap: Proxy object disconnected
11-24 06:20:22.396  5641  5641 D BluetoothMap: Proxy object disconnected
11-24 06:20:22.396  5641  5641 D MapProfile: Bluetooth service disconnected
11-24 06:20:22.396  3085  3085 D MapProfile: Bluetooth service disconnected
11-24 06:20:22.397  5705  5705 D SapService: Received stop request...Stopping profile...
11-24 06:20:22.397  5705  5705 V SapService: stop()
11-24 06:20:22.398  5705  5705 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:22.398  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:22.398  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:22.398  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:22.398  5705  5705 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-24 06:20:22.399  5705  5813 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 06:20:22.399  5705  5705 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 06:20:22.399  5705  5705 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:22.399  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:22.399  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:22.399  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 06:20:22.400  5705  5705 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 06:20:22.400  5705  5705 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 06:20:22.401  5705  5705 D BluetoothMapService: MAP Service closeService in
11-24 06:20:22.401  5705  5705 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:22.401  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:22.401  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:22.401  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:22.401  5705  5705 D BluetoothMapService: cleanup()
11-24 06:20:22.401  5705  5705 D BluetoothMapService: MAP Service closeService in
11-24 06:20:22.402  5705  5705 V BluetoothAdapterState: isTurningOff()=true
11-24 06:20:22.402  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:22.402  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:22.402  5705  5705 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:22.402  5705  5809 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 06:20:22.402  5705  5809 D BluetoothAdapterProperties: Setting state to 15
11-24 06:20:22.402  5705  5809 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-24 06:20:22.403  3085  3935 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 06:20:22.403  3757  3993 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:22.404  3085  5584 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:22.404  5641  5651 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 06:20:22.405  3085  3100 D BluetoothPan: onBluetoothStateChange on: false
11-24 06:20:22.406  5705  5809 I BluetoothAdapterState: Entering BleOnState
11-24 06:20:22.406  3085  3097 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 06:20:22.406   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 06:20:22.407  5641  5658 D BluetoothPan: onBluetoothStateChange on: false
,11-24 06:20:22.407  5641  5651 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:22.407   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:22.407  3085  3935 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 06:20:22.408  5641  5658 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 06:20:22.408  5641  5651 D BluetoothMap: onBluetoothStateChange: up=false
11-24 06:20:22.409   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:22.409  3085  5584 D BluetoothMap: onBluetoothStateChange: up=false
11-24 06:20:22.409   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 06:20:22.410  5641  5658 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 06:20:22.410  5705  5809 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 06:20:22.411  5705  5809 D BluetoothAdapterProperties: Setting state to 16
11-24 06:20:22.411  5705  5809 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 06:20:22.411  5705  5809 D BluetoothAdapterProperties: onBleDisable
11-24 06:20:22.411  5705  5809 I BluetoothAdapterState: Entering PendingCommandState
11-24 06:20:22.412  5705  5810 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 06:20:22.413  5705  5820 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 06:20:22.413  5705  5820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 06:20:22.416  5705  5813 D BluetoothAdapterProperties: Scan Mode:20
11-24 06:20:22.417  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:20:22.417  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 06:20:22.423  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 06:20:22.424  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 06:20:22.425  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,11-24 06:20:22.631  5705  5813 I bt_hci  : shut_down
,11-24 06:20:22.637  5705  5817 D bt_hwcfg: hw_epilog_process
11-24 06:20:22.638  5705  5817 I bt_vendor: low_power_mode_cb
,11-24 06:20:22.641  5705  5817 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 06:20:22.642  5705  5817 I bt_vendor: epilog_cb
11-24 06:20:22.642  5705  5817 I bt_hci  : epilog_finished_callback
,11-24 06:20:22.646  5705  5813 I bt_hci_h4: hal_close
,11-24 06:20:22.647  5705  5813 I bt_userial_vendor: device fd = 54 close
,11-24 06:20:22.757  5705  5810 D bt_stack_manager: event_shut_down_stack finished.
,11-24 06:20:22.758  5705  5809 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 06:20:22.764  5705  5809 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 06:20:22.764  5705  5705 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 06:20:22.766  5705  5705 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 06:20:22.767  5705  5705 D BtGatt.GattService: stop()
11-24 06:20:22.767  5705  5705 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 06:20:22.772  5705  5705 V BluetoothAdapterState: isTurningOff()=false
,11-24 06:20:22.772  5705  5705 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:22.772  5705  5705 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:22.772  5705  5705 V BluetoothAdapterState: isBleTurningOff()=true
11-24 06:20:22.773  5705  5809 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 06:20:22.773  5705  5809 D BluetoothAdapterProperties: Setting state to 10
11-24 06:20:22.774  5705  5809 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-24 06:20:22.775  5705  5809 I BluetoothAdapterState: Entering OffState
,11-24 06:20:22.777   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 06:20:22.795  5705  5705 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 06:20:22.795  5705  5705 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 06:20:22.795  5705  5810 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 06:20:22.798  5705  5705 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 06:20:22.804  5705  5705 I art     : System.exit called, status: 0
,11-24 06:20:22.806  5705  5705 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 06:20:22.834   930   940 I ActivityManager: Process com.android.bluetooth (pid 5705) has died
,11-24 06:20:25.788   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:26.792   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:27.324  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:20:27.324  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 06:20:27.330  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:27.330  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@524470c removed from the list
11-24 06:20:27.330  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:20:27.333  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 06:20:27.333  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb3335b added. We now have 4 listener(s)
11-24 06:20:27.333  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:20:27.337  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:20:27.337  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb3335b removed from the list
11-24 06:20:27.337  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:20:27.339  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:27.340  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f54c7f8 added. We now have 4 listener(s)
11-24 06:20:27.340  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 06:20:27.795   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:28.798   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:29.802   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:30.805   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 06:20:32.355  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:32.390   930   947 I ActivityManager: Start proc 5853:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 06:20:32.495  5853  5853 D AdapterServiceConfig: Adding HeadsetService
,11-24 06:20:32.495  5853  5853 D AdapterServiceConfig: Adding A2dpService
11-24 06:20:32.495  5853  5853 D AdapterServiceConfig: Adding HidService
11-24 06:20:32.495  5853  5853 D AdapterServiceConfig: Adding HealthService
11-24 06:20:32.496  5853  5853 D AdapterServiceConfig: Adding PanService
,11-24 06:20:32.496  5853  5853 D AdapterServiceConfig: Adding GattService
11-24 06:20:32.496  5853  5853 D AdapterServiceConfig: Adding BluetoothMapService
11-24 06:20:32.496  5853  5853 D AdapterServiceConfig: Adding SapService
,11-24 06:20:32.512   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29215ad:true
,11-24 06:20:32.512  5853  5853 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 06:20:32.516  5853  5853 I bt_bluedroid: init
11-24 06:20:32.516  5853  5865 I BluetoothAdapterState: Entering OffState
,11-24 06:20:32.520  5853  5866 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 06:20:32.520  5853  5866 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 06:20:32.520  5853  5866 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 06:20:32.520  5853  5866 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 06:20:32.521  5853  5853 I bt_bluedroid: get_profile_interface socket
,11-24 06:20:32.524  5853  5853 I bt_bluedroid: get_profile_interface sdp
,11-24 06:20:32.524  5853  5869 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 06:20:32.528  5853  5869 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 06:20:32.533  5853  5864 I bt_bluedroid: config_hci_snoop_log
,11-24 06:20:32.535   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 06:20:32.540  5853  5865 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 06:20:32.540  5853  5865 D BluetoothAdapterProperties: Setting state to 14
11-24 06:20:32.540  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 06:20:32.542  5853  5865 D BluetoothBondStateMachine: make
,11-24 06:20:32.545  5853  5870 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 06:20:32.548  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,11-24 06:20:32.549  5853  5853 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 06:20:32.551  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:32.552  5853  5853 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 06:20:32.553  5853  5853 D BtGatt.GattService: Received start request. Starting profile...
11-24 06:20:32.553  5853  5853 D BtGatt.GattService: start()
11-24 06:20:32.553  5853  5853 I bt_bluedroid: get_profile_interface gatt
,11-24 06:20:32.555  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:32.555  5853  5853 D BtGatt.AdvertiseManager: advertise manager created
,11-24 06:20:32.565  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:32.565  5853  5853 V BluetoothAdapterState: isTurningOn()=false
11-24 06:20:32.565  5853  5853 V BluetoothAdapterState: isBleTurningOn()=true
11-24 06:20:32.565  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 06:20:32.566  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 06:20:32.568  5853  5865 I bt_bluedroid: bt_bluedroid
,11-24 06:20:32.568  5853  5866 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 06:20:32.568  5853  5866 I bt_hci  : start_up
,11-24 06:20:32.574  5853  5866 I bt_vendor: alloc value 0xf3e6b871
,11-24 06:20:32.574  5853  5866 I bt_vendor: init
11-24 06:20:32.575  5853  5866 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 06:20:32.575  5853  5866 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 06:20:32.687  5853  5866 D bt_hci  : start_up starting async portion
11-24 06:20:32.688  5853  5873 I bt_hci  : event_finish_startup
11-24 06:20:32.688  5853  5873 I bt_hci_h4: hal_open
,11-24 06:20:32.688  5853  5873 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 06:20:32.686  5874  5874 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 06:20:32.690  5853  5873 I bt_userial_vendor: device fd = 54 open
,11-24 06:20:32.707  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 06:20:32.710  5853  5873 D bt_hwcfg: Chipset BCM4358A3
,11-24 06:20:32.710  5853  5873 D bt_hwcfg: Target name = [BCM4358A3]
11-24 06:20:32.710  5853  5873 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 06:20:33.522  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-24 06:20:33.522  5853  5873 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 06:20:33.522  5853  5873 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 06:20:33.657  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 06:20:33.657  5853  5873 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-24 06:20:33.659  5853  5873 I bt_hwcfg: vendor lib fwcfg completed
11-24 06:20:33.659  5853  5873 I bt_vendor: firmware callback
,11-24 06:20:33.659  5853  5873 I bt_hci  : firmware_config_callback
,11-24 06:20:33.669  5853  5876 I bt_btu  : btu_task pending for preload complete event
,11-24 06:20:33.669  5853  5876 I bt_btu_task: Bluetooth chip preload is complete
11-24 06:20:33.670  5853  5876 I bt_btu  : btu_task received preload complete event
,11-24 06:20:33.680  5853  5876 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 06:20:33.680  5853  5876 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 06:20:33.680  5853  5876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 06:20:33.680  5853  5876 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 06:20:33.680  5853  5876 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 06:20:33.680  5853  5876 I         : BTE_InitTraceLevels -- TRC_A2D
,11-24 06:20:33.680  5853  5876 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 06:20:33.681  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 06:20:33.681  5853  5876 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 06:20:33.681  5853  5876 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 06:20:33.681  5853  5876 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 06:20:33.681  5853  5876 I         : BTE_InitTraceLevels -- TRC_GATT
,11-24 06:20:33.681  5853  5876 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 06:20:33.681  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 06:20:33.682  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 06:20:33.780  5853  5876 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3de9549
,11-24 06:20:33.780  5853  5876 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3de9549 
,11-24 06:20:33.813  5853  5869 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 06:20:33.814  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 06:20:33.815  5853  5869 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-24 06:20:33.817  5853  5869 D BluetoothAdapterProperties: Name is: Nexus 6P
11-24 06:20:33.820  5853  5869 D BluetoothAdapterProperties: Scan Mode:20
11-24 06:20:33.820  5853  5869 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 06:20:33.820  5853  5869 D bt_hci  : do_postload posting postload work item
11-24 06:20:33.820  5853  5873 I bt_hci  : event_postload
11-24 06:20:33.821  5853  5873 I bt_vendor: sco_config_cb
11-24 06:20:33.821  5853  5873 I bt_hci  : sco_config_callback postload finished.
,11-24 06:20:33.823  5853  5869 D bt_bte_conf: Device ID record 1 : primary
,11-24 06:20:33.823  5853  5869 D bt_bte_conf:   vendorId            = 000f
11-24 06:20:33.823  5853  5869 D bt_bte_conf:   vendorIdSource      = 0001
11-24 06:20:33.823  5853  5869 D bt_bte_conf:   product             = 1200
11-24 06:20:33.823  5853  5869 D bt_bte_conf:   version             = 1436
11-24 06:20:33.823  5853  5869 D bt_bte_conf:   clientExecutableURL = 
,11-24 06:20:33.823  5853  5869 D bt_bte_conf:   serviceDescription  = 
11-24 06:20:33.823  5853  5869 D bt_bte_conf:   documentationURL    = 
11-24 06:20:33.823  5853  5869 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-24 06:20:33.824  5853  5866 D bt_stack_manager: event_start_up_stack finished
,11-24 06:20:33.824  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 06:20:33.824  5853  5865 D BluetoothAdapterProperties: Setting state to 15
11-24 06:20:33.824  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 06:20:33.825  5853  5865 I BluetoothAdapterState: Entering BleOnState
11-24 06:20:33.829  5853  5873 I bt_vendor: low_power_mode_cb
11-24 06:20:33.830  5853  5865 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 06:20:33.830  5853  5865 D BluetoothAdapterProperties: Setting state to 11
11-24 06:20:33.830  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 06:20:33.834  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:33.835  5853  5853 D HeadsetService: Received start request. Starting profile...
,11-24 06:20:33.838  5853  5853 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 06:20:33.838  5853  5853 D HeadsetStateMachine: make
,11-24 06:20:33.848  5853  5853 D HeadsetStateMachine: max_hf_connections = 1
,11-24 06:20:33.848  5853  5853 I bt_bluedroid: get_profile_interface handsfree
11-24 06:20:33.848  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 06:20:33.849  5853  5869 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 06:20:33.855  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:33.856  5853  5853 D A2dpService: Received start request. Starting profile...
11-24 06:20:33.856  5853  5853 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 06:20:33.857  5853  5853 I bt_bluedroid: get_profile_interface avrcp
11-24 06:20:33.857  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,11-24 06:20:33.863  5853  5853 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 06:20:33.864  5853  5853 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 06:20:33.864  5853  5853 D A2dpStateMachine: make
11-24 06:20:33.866  5853  5853 I bt_bluedroid: get_profile_interface a2dp
11-24 06:20:33.867  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-24 06:20:33.868  5853  5883 D A2dpStateMachine: Enter Disconnected: -2
,11-24 06:20:33.872  5853  5853 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 06:20:33.872  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:33.873  5853  5853 D HidService: Received start request. Starting profile...
11-24 06:20:33.873  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 06:20:33.873  5853  5853 I bt_bluedroid: get_profile_interface hidhost
,11-24 06:20:33.873  5853  5853 D HidService: setHidService(): set to: null
11-24 06:20:33.873  5853  5869 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3dca56d
11-24 06:20:33.873  5853  5853 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 06:20:33.873  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-24 06:20:33.874  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:33.874  5853  5853 D HealthService: Received start request. Starting profile...
,11-24 06:20:33.875  5853  5853 I bt_bluedroid: get_profile_interface health
11-24 06:20:33.876  5853  5881 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-24 06:20:33.876  5853  5853 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 06:20:33.877  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:33.878  5853  5853 D PanService: Received start request. Starting profile...
11-24 06:20:33.878  5853  5853 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 06:20:33.878  5853  5853 I bt_bluedroid: get_profile_interface pan
11-24 06:20:33.879  5853  5869 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 06:20:33.881  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:33.881  5853  5853 D BluetoothMapService: Received start request. Starting profile...
11-24 06:20:33.881  5853  5853 D BluetoothMapService: start()
,11-24 06:20:33.883  5853  5853 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 06:20:33.883  5853  5853 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 06:20:33.884  5853  5853 D BluetoothMapAppObserver: createReceiver()
,11-24 06:20:33.884  5853  5853 D BluetoothMapAppObserver: initObservers()
,11-24 06:20:33.885  5853  5853 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 06:20:33.888  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:33.888  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:33.888  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:33.888  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 06:20:33.889  5853  5853 V SapService: SapBinder()
11-24 06:20:33.889  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
11-24 06:20:33.890  5853  5853 D SapService: Received start request. Starting profile...
11-24 06:20:33.890  5853  5853 V SapService: start()
,11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:33.891  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 06:20:33.892  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 06:20:33.893  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 06:20:33.893  5853  5865 D BluetoothAdapterProperties: ScanMode =  20
11-24 06:20:33.893  5853  5865 D BluetoothAdapterProperties: State =  11
,11-24 06:20:33.893  5853  5865 D BluetoothAdapterProperties: Setting state to 12
,11-24 06:20:33.893  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 06:20:33.894  3085  3935 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 06:20:33.894  5853  5865 I BluetoothAdapterState: Entering OnState
11-24 06:20:33.894  5853  5869 D BluetoothAdapterProperties: Scan Mode:21
11-24 06:20:33.894  5853  5869 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 06:20:33.896  3757  3799 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:33.897  3085  3097 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:33.897  3085  3085 D BluetoothInputDevice: Proxy object connected
11-24 06:20:33.897  3085  3085 D HidProfile: Bluetooth service connected
,11-24 06:20:33.900  5641  5651 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 06:20:33.902  3085  5584 D BluetoothPan: onBluetoothStateChange on: true
11-24 06:20:33.903  3085  3935 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 06:20:33.904  3085  3085 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 06:20:33.905  3085  3085 D PanProfile: Bluetooth service connected
11-24 06:20:33.905   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 06:20:33.905  5641  5641 D BluetoothInputDevice: Proxy object connected
11-24 06:20:33.905  5641  5641 D HidProfile: Bluetooth service connected
,11-24 06:20:33.907  5641  5658 D BluetoothPan: onBluetoothStateChange on: true
,11-24 06:20:33.907   930   930 D BluetoothA2dp: Proxy object connected
11-24 06:20:33.907  3085  3085 D BluetoothA2dp: Proxy object connected
,11-24 06:20:33.910  5853  5853 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 06:20:33.910  5853  5853 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-24 06:20:33.911  5641  5658 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:33.912  5853  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 06:20:33.912   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:33.912  3085  3097 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 06:20:33.914  5853  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 06:20:33.914  5641  5651 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 06:20:33.916  5853  5853 D ObexServerSockets: Succeed to create listening sockets 
,11-24 06:20:33.916  5853  5853 D ObexServerSockets0: startAccept()
11-24 06:20:33.916  5641  5889 D BluetoothMap: onBluetoothStateChange: up=true
11-24 06:20:33.916  5853  5853 D ObexServerSockets0: prepareForNewConnect()
11-24 06:20:33.918   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:33.919  5853  5890 D ObexServerSockets0: Accepting socket connection...
11-24 06:20:33.918  5853  5853 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 06:20:33.919  5853  5853 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 06:20:33.919  5853  5891 D ObexServerSockets0: Accepting socket connection...
11-24 06:20:33.920  3085  3100 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 06:20:33.922   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 06:20:33.922  3085  3085 D BluetoothMap: Proxy object connected
11-24 06:20:33.922  3085  3085 D MapProfile: Bluetooth service connected
11-24 06:20:33.922  5641  5651 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 06:20:33.922  3085  3085 D BluetoothMap: getConnectedDevices()
11-24 06:20:33.924  5641  5641 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 06:20:33.924  5641  5641 D PanProfile: Bluetooth service connected
11-24 06:20:33.925  5641  5641 D BluetoothMap: Proxy object connected
11-24 06:20:33.925  5641  5641 D MapProfile: Bluetooth service connected
11-24 06:20:33.925  5641  5641 D BluetoothMap: getConnectedDevices()
,11-24 06:20:33.925   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 06:20:33.926  5853  5853 D BluetoothMapService: onReceive
,11-24 06:20:33.926  5853  5853 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-24 06:20:33.926  5853  5853 D BluetoothMapService: STATE_ON
11-24 06:20:33.927  5641  5641 D BluetoothA2dp: Proxy object connected
11-24 06:20:33.932  5853  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 06:20:33.934  5853  5895 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 06:20:33.934  5853  5895 D BluetoothSdpJni: SDP Create record success - handle: 1
11-24 06:20:33.934  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 06:20:33.940  5641  5641 D DockEventReceiver: finishStartingService: stopping service
11-24 06:20:33.941  3517  3517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 06:20:33.948  5641  5641 D BluetoothPbap: Proxy object connected
11-24 06:20:33.948  5641  5641 D PbapServerProfile: Bluetooth service connected
11-24 06:20:33.948  5853  5853 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 06:20:33.949  5853  5853 D ObexServerSockets0: prepareForNewConnect()
,11-24 06:20:33.953  3085  3085 D BluetoothPbap: Proxy object connected
11-24 06:20:33.953  3085  3085 D PbapServerProfile: Bluetooth service connected
,11-24 06:20:33.957  5853  5899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 06:20:33.966  5853  5903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 06:20:33.967  5853  5903 I BtOppRfcommListener: Accept thread started.
,11-24 06:20:33.999  3085  5584 D BluetoothHeadset: Proxy object connected
,11-24 06:20:33.999   930   930 D BluetoothHeadset: Proxy object connected
11-24 06:20:33.999   930   930 D BluetoothHeadset: Proxy object connected
11-24 06:20:34.000  3085  3085 D HeadsetProfile: Bluetooth service connected
11-24 06:20:34.000  3085  5892 D BluetoothHeadset: Proxy object connected
11-24 06:20:34.000  3757  3787 D BluetoothHeadset: Proxy object connected
,11-24 06:20:34.000  5641  5889 D BluetoothHeadset: Proxy object connected
,11-24 06:20:34.000   930   930 D BluetoothHeadset: Proxy object connected
11-24 06:20:34.002  3085  3085 D HeadsetProfile: Bluetooth service connected
11-24 06:20:34.002  5641  5641 D HeadsetProfile: Bluetooth service connected
,11-24 06:20:34.011  5641  5651 D BluetoothHeadset: Proxy object connected
11-24 06:20:34.013   930   947 D BluetoothHeadset: Proxy object connected
11-24 06:20:34.013  5641  5641 D HeadsetProfile: Bluetooth service connected
,11-24 06:20:34.020   930   947 D BluetoothHeadset: Proxy object connected
,11-24 06:20:34.023   930   947 D BluetoothHeadset: Proxy object connected
,11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:37.378  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 06:20:37.384  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 06:20:37.385  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 06:20:37.385  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f54c7f8 removed from the list
11-24 06:20:37.385  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:20:37.387  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:37.387  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd6e4d1 added. We now have 4 listener(s)
,11-24 06:20:37.387  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:37.392   930  3102 D WifiService: setWifiEnabled: false pid=5585, uid=10077
,11-24 06:20:37.392   930  3102 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 06:20:40.806   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:41.810   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:42.407  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 06:20:42.408   930  3099 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,11-24 06:20:42.408   930  3099 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-24 06:20:42.419   508   924 D SoftapController: Softap fwReload - Ok
,11-24 06:20:42.425   508   924 D CommandListener: Setting iface cfg
11-24 06:20:42.425   508   924 D CommandListener: Trying to bring down wlan0
,11-24 06:20:42.427   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-24 06:20:42.435   930  2920 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 06:20:42.811   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:43.227   930  2920 D wifi    : set interface wlan0 flags (UP)
11-24 06:20:43.229   930  2920 I WifiHAL : Initializing wifi
,11-24 06:20:43.229   930  2920 I WifiHAL : Creating socket
,11-24 06:20:43.240   930  2920 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 06:20:43.240   930  2920 D wifi    : Did set static halHandle = 0x7f8f19c080
11-24 06:20:43.240   930  2920 D wifi    : halHandle = 0x7f8f19c080, mVM = 0x7fab80d140, mCls = 0x2015c2
11-24 06:20:43.240   930  2920 D wifi    : array field set
11-24 06:20:43.240   930  2920 I WifiNative-HAL: interface[0] = wlan0
11-24 06:20:43.241   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 06:20:43.243   930  5909 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547861676160
,11-24 06:20:43.243   930  5909 D wifi    : waitForHalEvents called, vm = 0x7fab80d140, obj = 0x2015c2, env = 0x7f9017b380
,11-24 06:20:43.306  5910  5910 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 06:20:43.327  5910  5910 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 06:20:43.347   930  2920 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 06:20:43.375  5910  5910 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 06:20:43.375  5910  5910 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 06:20:43.395   930  2920 D WifiConfigStore: Loading config and enabling all networks 
,11-24 06:20:43.408   930  2920 D WifiConfigStore: loaded 0 passpoint configs
11-24 06:20:43.408   930  2920 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 06:20:43.409   930  2920 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 06:20:43.410   930  2920 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 06:20:43.411   930  2920 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 06:20:43.411   930  2920 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-24 06:20:43.412   930  2920 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 06:20:43.412   930  2920 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 06:20:43.415   930  2920 D WifiNative-HAL: Setting external_sim to 1
,11-24 06:20:43.416  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 06:20:43.416   930  2920 D wifi    : setting dfs flag to true, 0x7f9137a120
11-24 06:20:43.416   930  2920 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 06:20:43.416   930  2920 D wifi    : setting scan oui 0x7f9137a120
11-24 06:20:43.416   930  2920 D WifiHAL : Sending mac address OUI
,11-24 06:20:43.421   930  2920 E native  : do suspend false
,11-24 06:20:43.432   930  2920 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 06:20:43.432   930   930 D RttService: SCAN_AVAILABLE : 3
11-24 06:20:43.432   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 06:20:43.432   930  3028 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 06:20:43.433   508   924 D CommandListener: Setting iface cfg
,11-24 06:20:43.434   930  2919 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
11-24 06:20:43.434   930  2919 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 06:20:43.440   930  2919 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 06:20:43.440   930  2919 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 06:20:43.478   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=258076 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=36 mControllerEnergyUsed=136 }
,11-24 06:20:43.814   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:44.816   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:20:45.819   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 06:20:46.503  5910  5910 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 06:20:46.509  5910  5910 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 06:20:46.515  5910  5910 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 06:20:46.565   930  2920 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 06:20:46.567   930  2920 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 06:20:46.567   930  2920 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 06:20:46.584   930  2920 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 06:20:46.625   930  2920 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 06:20:46.628  5910  5910 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 06:20:47.086  5910  5910 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 06:20:47.134  5910  5910 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 06:20:47.134  5910  5910 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 06:20:47.145   930  2920 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 06:20:47.145   930  2920 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 06:20:47.145   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 06:20:47.168   930  2920 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 06:20:47.182   508   924 D CommandListener: Setting iface cfg
,11-24 06:20:47.189   930  2920 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 06:20:47.198   930  5915 D DhcpClient: Receive thread started
,11-24 06:20:47.203   930  2920 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 06:20:47.203   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 06:20:47.203   930  2922 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 06:20:47.307   930  2920 E native  : do suspend false
,11-24 06:20:47.330   930  5914 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 06:20:47.348   930  5915 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-24 06:20:47.349   930  5914 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-24 06:20:47.351   930  5914 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 06:20:47.381   930  5915 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 06:20:47.382   930  5914 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 06:20:47.386   508   924 D CommandListener: Setting iface cfg
,11-24 06:20:47.391   930  2920 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 06:20:47.400   930  5914 D DhcpClient: Scheduling renewal in 86399s
,11-24 06:20:47.413   930  2920 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 06:20:47.414   930  2920 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 06:20:47.415   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 06:20:47.417   930  2922 D ConnectivityService: Adding iface wlan0 to network 102
11-24 06:20:47.417   930  2920 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 06:20:47.433  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 06:20:47.438  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 06:20:47.439  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.439  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd6e4d1 removed from the list
11-24 06:20:47.439  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:20:47.444  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-24 06:20:47.445  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 06:20:47.447  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2a3db6a Bundle[{}]
11-24 06:20:47.448  5585  5632 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 06:20:47.448  5585  5632 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 06:20:47.449  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-24 06:20:47.450  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-24 06:20:47.450  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 06:20:47.451  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-24 06:20:47.459  5585  5632 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-24 06:20:47.460  5585  5632 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 06:20:47.460  5585  5632 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 171)
11-24 06:20:47.462  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.462  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dd4b36 added. We now have 3 listener(s)
11-24 06:20:47.464  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.464  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.464  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.464   930  2922 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 06:20:47.464  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.465  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7aa37 added. We now have 4 listener(s)
11-24 06:20:47.465   930  2922 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-24 06:20:47.465  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.467  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 06:20:47.468   930  2922 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 06:20:47.470  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.470   930  2922 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
11-24 06:20:47.470  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0a6ba4 added. We now have 4 listener(s)
,11-24 06:20:47.472  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.472  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.472  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.472  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 06:20:47.473  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@813fd0d added. We now have 5 listener(s)
11-24 06:20:47.473  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.473   930  2922 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
11-24 06:20:47.473  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:20:47.473  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:20:47.473  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 06:20:47.473  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.473  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.473  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.473  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dd4b36 removed from the list
11-24 06:20:47.474  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.474  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7aa37 removed from the list
11-24 06:20:47.474  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:20:47.474  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.475  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.476  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.476  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.476  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.476  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.477  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.477  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.477  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7aa37 not in the list
11-24 06:20:47.477  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.477  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.480   930  2922 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 06:20:47.481  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.482  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.482  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.482  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.482  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.482  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.482  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@813fd0d removed from the list
11-24 06:20:47.482  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.482  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.482  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.482  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0a6ba4 removed from the list
,11-24 06:20:47.482  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.483  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@caae4c2 added. We now have 3 listener(s)
11-24 06:20:47.484  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.484  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 06:20:47.484  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.484  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.484  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@682b2d3 added. We now have 4 listener(s)
11-24 06:20:47.484  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.484   930  2922 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-24 06:20:47.485   930  2922 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-24 06:20:47.485   930  2922 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 06:20:47.485   930  2922 D ConnectivityService:    accepting network in place of null
11-24 06:20:47.485  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 06:20:47.485   930  2920 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 06:20:47.485   930  2920 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 06:20:47.485   930  2922 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-24 06:20:47.486  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.486  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a549e10 added. We now have 4 listener(s)
,11-24 06:20:47.488  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.488  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.488  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 06:20:47.488  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.488  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e905d09 added. We now have 5 listener(s)
11-24 06:20:47.489  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.489  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:20:47.489  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 06:20:47.489  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 06:20:47.489  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:20:47.489  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 06:20:47.491  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 06:20:47.494  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 06:20:47.494  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 06:20:47.494  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 06:20:47.497  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.498  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 06:20:47.499  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 06:20:47.499   930  5913 D NetlinkSocketObserver: NeighborEvent{elapsedMs=262097, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-24 06:20:47.499  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 06:20:47.499  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 06:20:47.502  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.503  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 06:20:47.503  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 06:20:47.503  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 06:20:47.503  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 06:20:47.503  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.503  5585  5632 D BluetoothAdapter: STATE_ON
,11-24 06:20:47.506  5853  5893 D BtGatt.GattService: registerClient() - UUID=99de8852-9e12-4d32-a2db-1bdd17900a6a
,11-24 06:20:47.507  5853  5869 D BtGatt.GattService: onClientRegistered() - UUID=99de8852-9e12-4d32-a2db-1bdd17900a6a, clientIf=5
11-24 06:20:47.508  5585  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 06:20:47.508   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 06:20:47.508  5853  5864 D BtGatt.GattService: start scan with filters
,11-24 06:20:47.512  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 06:20:47.512  5853  5872 D BtGatt.ScanManager: handling starting scan
11-24 06:20:47.512  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.512  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 06:20:47.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 06:20:47.513  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 06:20:47.513  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.513  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 06:20:47.513  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 06:20:47.513  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.513  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.513  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.513  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.514  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 06:20:47.514  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.515  5853  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c12173f
,11-24 06:20:47.516  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.516  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:20:47.516  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.516  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.516  5585  5632 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 06:20:47.516  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 06:20:47.516  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 06:20:47.517  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.516  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.517  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:20:47.517  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.517  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 06:20:47.519  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.519  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.519  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.519  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 06:20:47.519  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:20:47.520  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.520  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 06:20:47.520  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 06:20:47.520  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.520  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.520  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.520  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 06:20:47.520  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.521  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:20:47.521  5853  5893 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 06:20:47.521  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 06:20:47.522  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:20:47.523  5853  5894 D BtGatt.GattService: stopScan() - queue size =1
11-24 06:20:47.523  5853  5888 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.524  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.525  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.525  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 06:20:47.525  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 06:20:47.525  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 06:20:47.526  5853  5869 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 06:20:47.526  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.526  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.526  5853  5872 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 06:20:47.527  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.527  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:20:47.527  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.527  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.527  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:20:47.527  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:20:47.527  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 06:20:47.527  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.528  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 06:20:47.528  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 06:20:47.528  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.528  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.528  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.528  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:20:47.528  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.528  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.529  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.529  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:20:47.529  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.529  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.529  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:20:47.529  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:20:47.529  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.530  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.530  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.530  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@caae4c2 removed from the list
11-24 06:20:47.530  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.530  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@682b2d3 removed from the list
11-24 06:20:47.530  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 06:20:47.530   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 06:20:47.530  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.530  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.531  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.531  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.531  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.531  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.531  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.531  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.531  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@682b2d3 not in the list
11-24 06:20:47.532  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.532  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.534  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.534   930  2922 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-24 06:20:47.534  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.534   930  2922 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 06:20:47.534  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.534  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.534  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.534  3722  3862 W QCNEJ   : |CORE| network available: 102
11-24 06:20:47.534  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.534  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e905d09 removed from the list
11-24 06:20:47.534  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.534  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.534  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.534  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a549e10 removed from the list
11-24 06:20:47.535  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 06:20:47.535  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.535  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.535  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e44a1a added. We now have 3 listener(s)
11-24 06:20:47.535  5853  5872 D BtGatt.ScanManager: Starting BLE batch scan
11-24 06:20:47.535  5853  5872 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 06:20:47.536   930  2922 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-24 06:20:47.536  5585  5632 D org.thal,iproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.536  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.536  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.536  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.536  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae3a94b added. We now have 4 listener(s)
11-24 06:20:47.537  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.537  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 06:20:47.538   930   947 D Tethering: MasterInitialState.processMessage what=3
11-24 06:20:47.539  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.539  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b861f28 added. We now have 4 listener(s)
11-24 06:20:47.541  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.541  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.542  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.542  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.542  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@689a441 added. We now have 5 listener(s)
11-24 06:20:47.542  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.542  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:20:47.543  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:20:47.543  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 06:20:47.543  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 06:20:47.543  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:20:47.543  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 06:20:47.545  4995  5018 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 06:20:47.545  4995  5018 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 06:20:47.545  4995  5018 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 06:20:47.545  4995  5018 E SarControlService: no key has been found,reset the power
11-24 06:20:47.545  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 06:20:47.546  4995  5030 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 06:20:47.546  4995  5030 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 06:20:47.547  3722  3862 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 06:20:47.547  3656  3656 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 06:20:47.548  4995  5030 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 06:20:47.548  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 06:20:47.548  5020  5020 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 06:20:47.549  3722  3862 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 06:20:47.549  3722  3862 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-24 06:20:47.550  4995  5030 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 06:20:47.550  4995  5030 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 06:20:47.551  4995  5030 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 06:20:47.551  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 06:20:47.551  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 06:20:47.551  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 06:20:47.551  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 06:20:47.551  5020  5020 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 06:20:47.553  5853  5869 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 06:20:47.553  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.554  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.554  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 06:20:47.555  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 06:20:47.555  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 06:20:47.555  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 06:20:47.557  5020  5034 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2576d86 HexData = [00000000ec03000000000000ffffffff]
11-24 06:20:47.557  5020  5034 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 06:20:47.557  5020  5034 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-24 06:20:47.558  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 06:20:47.558  4995  5006 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 06:20:47.559  3656  3656 D SystemUpdateService: onCreate
11-24 06:20:47.560  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.560  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 06:20:47.560  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 06:20:47.560  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 06:20:47.560  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.560  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 06:20:47.560  5020  5034 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2576d86 HexData = [00000000ed03000000000000ffffffff]
11-24 06:20:47.560  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 06:20:47.560  5020  5034 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 06:20:47.560  5020  5034 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-24 06:20:47.560  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.561  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:20:47.561  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 06:20:47.561  4995  5005 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 06:20:47.561  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:20:47.563  5853  5894 D BtGatt.GattService: registerClient() - UUID=f4d953be-5b0e-478e-ad38-7007120e8b39
11-24 06:20:47.564  3656  3656 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 06:20:47.565  5853  5869 D BtGatt.GattService: onClientRegistered() - UUID=f4d953be-5b0e-478e-ad38-7007120e8b39, clientIf=5
11-24 06:20:47.565  5585  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 06:20:47.565  5853  5863 D BtGatt.GattService: start scan with filters
,11-24 06:20:47.568  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:20:47.568  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:20:47.570  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 06:20:47.570  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.570  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 06:20:47.570  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.570  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 06:20:47.570  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.570  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 06:20:47.570  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.570  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 06:20:47.571  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 06:20:47.571  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.571  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.571  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.571  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.571  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 06:20:47.572  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.574  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.574  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:20:47.574  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.574  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.574  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.574  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 06:20:47.575  5585  5632 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 06:20:47.575  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:20:47.575  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 06:20:47.575  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:20:47.575  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:20:47.575  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 06:20:47.575  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.575  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.575  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 06:20:47.575  5853  5872 D BtGatt.ScanManager: stopping BLe Batch
11-24 06:20:47.575  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.575  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.575  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e44a1a removed from the list
11-24 06:20:47.575  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.575  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae3a94b removed from the list
11-24 06:20:47.575  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:20:47.575  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.575  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:20:47.575  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.575  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.575  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 06:20:47.575  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.575  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 06:20:47.575  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.577  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.577  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.577  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.577  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:20:47.577  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.577  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.577  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.577  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.577  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.577  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.577  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae3a94b not in the list
11-24 06:20:47.577  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 06:20:47.577  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.578  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 06:20:47.578  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 06:20:47.578  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.578  3656  3656 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-24 06:20:47.578  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.578  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.578  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 06:20:47.578  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.579  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:20:47.579  5853  5893 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 06:20:47.579  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 06:20:47.580  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:20:47.580  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 06:20:47.580  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.580  5853  5894 D BtGatt.GattService: stopScan() - queue size =0
11-24 06:20:47.580  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 06:20:47.581  3656  5353 I iu.UploadsManager: num queued entries: 0
,11-24 06:20:47.581  5853  5864 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 06:20:47.581  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.582  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.582  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.582  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 06:20:47.582  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 06:20:47.583  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 06:20:47.583   930  5912 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 06:20:47.586  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:20:47.586  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.586  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.587  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 06:20:47.587  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:20:47.587  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.587  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.587  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.587  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.587  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.587  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:20:47.587  5853  5872 D BtGatt.ScanManager: handling starting scan
11-24 06:20:47.587  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@689a441 removed from the list
11-24 06:20:47.587  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.587  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:20:47.587  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 06:20:47.587  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.587  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.587  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.587  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b861f28 removed from the list
11-24 06:20:47.587  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 06:20:47.587  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 06:20:47.588  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.588  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-24 06:20:47.588  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.588  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:20:47.588  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.588  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.588  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.588  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8a0272 added. We now have 3 listener(s)
11-24 06:20:47.589  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.589  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.589  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.589  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.589  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.589  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.590  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.590  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fadf6c3 added. We now have 4 listener(s)
11-24 06:20:47.590  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.590  3656  5925 I SystemUpdateService: active receiver: enabled
11-24 06:20:47.590  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 06:20:47.591  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.591  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13ab40 added. We now have 4 listener(s)
11-24 06:20:47.593  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.593  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.593  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.593  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.593  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60d9a79 added. We now have 5 listener(s)
11-24 06:20:47.593  5585  5632 D org.tha,liproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.593  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:20:47.593  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 06:20:47.593  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 06:20:47.593  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 06:20:47.593  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 06:20:47.594  3656  3656 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 06:20:47.595  5853  5869 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 06:20:47.595  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 06:20:47.595  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.596  5853  5872 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 06:20:47.596  3656  3656 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 06:20:47.597  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 06:20:47.598  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 06:20:47.598  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 06:20:47.598  5719  5719 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 06:20:47.601  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 06:20:47.601  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.601  5853  5872 D BtGatt.ScanManager: Starting BLE batch scan
11-24 06:20:47.601  5853  5872 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 06:20:47.602  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.602  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 06:20:47.603  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 06:20:47.603  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 06:20:47.603  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 06:20:47.606  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.606  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 06:20:47.607  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 06:20:47.607  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetoot,h.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 06:20:47.607  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 06:20:47.607  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.607  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:20:47.607  5719  5719 D SprintDMHelper: simOperator: 
11-24 06:20:47.608  5719  5719 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 06:20:47.595  3656  5353 I iu.UploadsManager: num updated entries: 0
11-24 06:20:47.614  5853  5894 D BtGatt.GattService: registerClient() - UUID=4c9e5f26-8927-467a-bfb6-bff4537a4c96
11-24 06:20:47.615  5853  5869 D BtGatt.GattService: onClientRegistered() - UUID=4c9e5f26-8927-467a-bfb6-bff4537a4c96, clientIf=5
11-24 06:20:47.615  5853  5869 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 06:20:47.615  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.615  5585  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 06:20:47.615  5853  5863 D BtGatt.GattService: start scan with filters
11-24 06:20:47.619  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 06:20:47.619  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.619  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 06:20:47.619  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.619  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 06:20:47.619  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 06:20:47.619  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.619  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 06:20:47.620  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 06:20:47.620  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.620  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.620  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.620  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.620  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 06:20:47.621  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.623  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 06:20:47.623  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.623  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.623  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:20:47.624  3656  5353 I iu.SyncManager: NEXT; no task
11-24 06:20:47.624  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.624  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.624  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.625  3656  5925 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-24 06:20:47.625  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:20:47.628  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.628  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.628  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.630  3656  5925 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 06:20:47.630  3656  5925 I SystemUpdateService: now status is 0 (complete)
11-24 06:20:47.630  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 06:20:47.630  3656  5925 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 06:20:47.630  3656  5925 I SystemUpdateService: file has been verified
11-24 06:20:47.630  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:20:47.630  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.630  3656  5925 I SystemUpdateService: OTA package size = 21989297
11-24 06:20:47.630  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:20:47.631  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:20:47.631  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:20:47.631  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.631  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.631  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:20:47.631  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.631  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.631  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.631  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8a0272 removed from the list
11-24 06:20:47.632  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.632  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fadf6c3 removed from the list
11-24 06:20:47.632  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:20:47.632  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.632  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:20:47.632  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.632  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.632  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 06:20:47.632  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 06:20:47.632  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 06:20:47.632  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.634  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.634  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.634  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.634  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.634  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.634  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.635  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fadf6c3 not in the list
11-24 06:20:47.635  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 06:20:47.635  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.635  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 06:20:47.635  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 06:20:47.635  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.636  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.636  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.636  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 06:20:47.636  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.637  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:20:47.637  5853  5864 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 06:20:47.637  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 06:20:47.638  5585  5632 D BluetoothAdapter: STATE_ON
11-24 06:20:47.639  5853  5894 D BtGatt.GattService: stopScan() - queue size =0
11-24 06:20:47.639  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 06:20:47.640  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.640  5853  5872 D BtGatt.ScanManager: stopping BLe Batch
11-24 06:20:47.640  5853  5893 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 06:20:47.640  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 06:20:47.640  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.640  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.641  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 06:20:47.642  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 06:20:47.642  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 06:20:47.643  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.644  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.644  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:20:47.644  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.644  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.644  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.644  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.645  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.645  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:20:47.645  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60d9a79 removed from the list
11-24 06:20:47.645  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 06:20:47.645  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.645  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 06:20:47.645  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.645  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.645  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 06:20:47.645  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.645  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 06:20:47.645  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.645  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13ab40 removed from the list
11-24 06:20:47.645  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.645  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.645  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 06:20:47.645  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.645  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.646  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.646  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b736dca added. We now have 3 listener(s)
11-24 06:20:47.646  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.646  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.646  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 06:20:47.647  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 06:20:47.647  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.647  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:20:47.648  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.648  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.648  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.648  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.648  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd57b3b added. We now have 4 listener(s)
11-24 06:20:47.648  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.649  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 06:20:47.650  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 06:20:47.650  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@413a258 added. We now have 4 listener(s)
,11-24 06:20:47.653  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:20:47.653  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.654  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 06:20:47.654  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 06:20:47.655  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 06:20:47.655  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 06:20:47.655  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe31fb1 added. We now have 5 listener(s)
11-24 06:20:47.655  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 06:20:47.655  5853  5872 D BtGatt.ScanManager: handling starting scan
11-24 06:20:47.655  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 06:20:47.655  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:20:47.655  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 06:20:47.655  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.655  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.655  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.655  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b736dca removed from the list
11-24 06:20:47.655  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.655  3656  5925 I SystemUpdateService: showing system update notification
11-24 06:20:47.655  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd57b3b removed from the list
11-24 06:20:47.655  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-24 06:20:47.656  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.656  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.657  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.657  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.657  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.657  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.658  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.658  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.658  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd57b3b not in the list
11-24 06:20:47.658  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.658  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.659  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.659  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.659  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 06:20:47.659  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 06:20:47.659  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 06:20:47.659  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 06:20:47.660  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe31fb1 removed from the list
11-24 06:20:47.660  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 06:20:47.660  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 06:20:47.660  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 06:20:47.660  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@413a258 removed from the list
11-24 06:20:47.660  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 06:20:47.660  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 06:20:47.661  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 06:20:47.661  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:20:47.661  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 06:20:47.661  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 06:20:47.661  5853  5869 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 06:20:47.661  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.661  5853  5872 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 06:20:47.666  3656  3656 D SystemUpdateService: onDestroy
11-24 06:20:47.667  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 06:20:47.667  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.667  5853  5872 D BtGatt.ScanManager: Starting BLE batch scan
11-24 06:20:47.667  5853  5872 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 06:20:47.677  5853  5869 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 06:20:47.677  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.679   930  5912 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 11:20:47 GMT], X-Android-Received-Millis=[1479986447678], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479986447651]}
11-24 06:20:47.680   930  2922 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 06:20:47.680   930  2922 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-24 06:20:47.681   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 06:20:47.682   930  2922 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 06:20:47.683  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 06:20:47.683  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.685  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 06:20:47.690  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:20:47.691  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.691  5853  5869 E BtGatt.ContextMap: Context not found for ID 5
,11-24 06:20:47.697  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 06:20:47.697  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.697  5853  5872 D BtGatt.ScanManager: stopping BLe Batch
,11-24 06:20:47.704  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 06:20:47.704  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 06:20:47.704  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 06:20:47.710  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 06:20:47.710  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 06:20:47.823  4969  5930 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 06:20:48.029  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 06:20:48.089  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 06:20:48.147  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 06:20:49.834  5585  5937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 06:20:49.834  5585  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 06:20:50.647  5585  5937 W !!      : call onHalfStreamCopied
11-24 06:20:50.647  5585  5937 I testCopyDataAndClose: closing input stream
,11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 06:20:51.431  5585  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 06:20:55.214  5585  5938 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: My test thread name). Connection data: Peer properties: [null null].
11-24 06:20:55.214  5585  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 06:20:55.491   930  2922 D ConnectivityService: handlePromptUnvalidated 102
,11-24 06:20:57.216  5585  5632 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 182. Connection data: Peer properties: [null null].
11-24 06:20:57.216  5585  5632 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 06:20:57.216  5585  5632 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 182, name: My test thread name)
,11-24 06:20:57.273  5585  5938 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 06:20:57.273  5585  5938 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: My test thread name). Connection data: Peer properties: [null null].
11-24 06:20:57.273  5585  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-24 06:20:57.357  5585  5939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 06:20:57.357  5585  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 06:20:58.452   930  2920 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-24 06:20:58.977  5585  5939 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 06:20:58.977  5585  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 06:20:58.978  5585  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 06:21:00.821   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:01.823   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:02.713  5585  5940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-24 06:21:02.713  5585  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 06:21:02.714  5585  5940 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 186, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 06:21:02.714  5585  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 06:21:02.714  5585  5940 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 06:21:02.714  5585  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 06:21:02.714  5585  5940 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 06:21:02.714  5585  5940 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 06:21:02.714  5585  5940 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 06:21:02.714  5585  5940 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 06:21:02.715  5585  5940 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 06:21:02.715  5585  5940 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-24 06:21:02.715  5585  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-24 06:21:02.718  5585  5632 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 06:21:02.721  5585  5941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: My test thread name). Connection data: Peer properties: [null null].
11-24 06:21:02.721  5585  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 06:21:02.722  5585  5941 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 190, thread name: My test thread name): Test exception.
,11-24 06:21:02.722  5585  5941 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 190, name: My test thread name). Connection data: Peer properties: [null null].
11-24 06:21:02.722  5585  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 06:21:02.722  5585  5941 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 06:21:02.722  5585  5941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: My test thread name). Connection data: Peer properties: [null null].
11-24 06:21:02.722  5585  5941 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 06:21:02.728  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 06:21:02.728  5585  5632 I jxcore-log: 
,11-24 06:21:02.729  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 06:21:02.729  5585  5632 I jxcore-log: 
11-24 06:21:02.729  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 06:21:02.729  5585  5632 I jxcore-log: 
11-24 06:21:02.729  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 06:21:02.729  5585  5632 I jxcore-log: 
11-24 06:21:02.730  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG UnitTest_app: 'Total duration:  90933'
11-24 06:21:02.730  5585  5632 I jxcore-log: 
11-24 06:21:02.732  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 06:21:02.732  5585  5632 I jxcore-log: 
,11-24 06:21:02.737  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 06:21:02.737  5585  5632 I jxcore-log: 
11-24 06:21:02.737  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 06:21:02.737  5585  5632 I jxcore-log: 
11-24 06:21:02.738  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 06:21:02.738  5585  5632 I jxcore-log: 
11-24 06:21:02.738  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 06:21:02.738  5585  5632 I jxcore-log: 
11-24 06:21:02.738  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 06:21:02.738  5585  5632 I jxcore-log: 
11-24 06:21:02.739  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 06:21:02.739  5585  5632 I jxcore-log: 
11-24 06:21:02.739  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 06:21:02.739  5585  5632 I jxcore-log: 
,11-24 06:21:02.739  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 06:21:02.739  5585  5632 I jxcore-log: 
11-24 06:21:02.740  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 06:21:02.740  5585  5632 I jxcore-log: 
11-24 06:21:02.740  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 06:21:02.740  5585  5632 I jxcore-log: 
,11-24 06:21:02.740  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 06:21:02.740  5585  5632 I jxcore-log: 
11-24 06:21:02.740  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 06:21:02.740  5585  5632 I jxcore-log: 
11-24 06:21:02.740  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 06:21:02.740  5585  5632 I jxcore-log: 
11-24 06:21:02.741  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 06:21:02.741  5585  5632 I jxcore-log: 
,11-24 06:21:02.741  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 06:21:02.741  5585  5632 I jxcore-log: 
11-24 06:21:02.741  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 06:21:02.741  5585  5632 I jxcore-log: 
11-24 06:21:02.741  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 06:21:02.741  5585  5632 I jxcore-log: 
11-24 06:21:02.741  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 06:21:02.741  5585  5632 I jxcore-log: 
11-24 06:21:02.742  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 06:21:02.742  5585  5632 I jxcore-log: 
11-24 06:21:02.742  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 06:21:02.742  5585  5632 I jxcore-log: 
,11-24 06:21:02.742  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 06:21:02.742  5585  5632 I jxcore-log: 
11-24 06:21:02.742  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 06:21:02.742  5585  5632 I jxcore-log: 
11-24 06:21:02.743  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 06:21:02.743  5585  5632 I jxcore-log: 
11-24 06:21:02.743  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 06:21:02.743  5585  5632 I jxcore-log: 
11-24 06:21:02.745  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-24 06:21:02.745  5585  5632 I jxcore-log: 
11-24 06:21:02.745  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 06:21:02.745  5585  5632 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-24 06:21:02.745  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 06:21:02.745  5585  5632 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 06:21:02.745  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 06:21:02.745  5585  5632 I jxcore-log: 
11-24 06:21:02.745  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 06:21:02.745  5585  5632 I jxcore-log: 
11-24 06:21:02.746  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 06:21:02.746  5585  5632 I jxcore-log: 
11-24 06:21:02.746  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 06:21:02.746  5585  5632 I jxcore-log: 
,11-24 06:21:02.746  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 06:21:02.746  5585  5632 I jxcore-log: 
11-24 06:21:02.746  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 06:21:02.746  5585  5632 I jxcore-log: 
11-24 06:21:02.751  5585  5585 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 06:21:02.751  5585  5585 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-24 06:21:02.751  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 06:21:02.751  5585  5632 I jxcore-log: 
11-24 06:21:02.752  5585  5632 I jxcore-log: 2016-11-24 11:21:02 - WARN testUtils: 'myNameCallback not set!'
11-24 06:21:02.752  5585  5632 I jxcore-log: 
,11-24 06:21:02.824   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:03.826   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:04.716  5585  5632 I jxcore-log: 2016-11-24 11:21:04 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 06:21:04.716  5585  5632 I jxcore-log: 
,11-24 06:21:04.717  5585  5632 I jxcore-log: 2016-11-24 11:21:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 06:21:04.717  5585  5632 I jxcore-log: 
,11-24 06:21:04.827   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:05.055  5585  5632 I jxcore-log: 2016-11-24 11:21:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 06:21:05.055  5585  5632 I jxcore-log: 
,11-24 06:21:05.066  5585  5632 I jxcore-log: 2016-11-24 11:21:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 06:21:05.066  5585  5632 I jxcore-log: 
,11-24 06:21:05.828   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 06:21:06.154  5585  5632 I jxcore-log: 2016-11-24 11:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 06:21:06.154  5585  5632 I jxcore-log: 
,11-24 06:21:06.340  5585  5632 I jxcore-log: 2016-11-24 11:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 06:21:06.340  5585  5632 I jxcore-log: 
,11-24 06:21:06.346  5585  5632 I jxcore-log: 2016-11-24 11:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 06:21:06.346  5585  5632 I jxcore-log: 
,11-24 06:21:06.351  5585  5632 I jxcore-log: 2016-11-24 11:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 06:21:06.351  5585  5632 I jxcore-log: 
,11-24 06:21:06.830  5585  5632 I jxcore-log: 2016-11-24 11:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 06:21:06.830  5585  5632 I jxcore-log: 
,11-24 06:21:06.874  5585  5632 I jxcore-log: 2016-11-24 11:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 06:21:06.874  5585  5632 I jxcore-log: 
,11-24 06:21:06.887  5585  5632 I jxcore-log: 2016-11-24 11:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 06:21:06.887  5585  5632 I jxcore-log: 
,11-24 06:21:06.892  5585  5632 I jxcore-log: 2016-11-24 11:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 06:21:06.892  5585  5632 I jxcore-log: 
,11-24 06:21:07.157  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 06:21:07.157  5585  5632 I jxcore-log: 
,11-24 06:21:07.281  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 06:21:07.281  5585  5632 I jxcore-log: 
,11-24 06:21:07.640  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 06:21:07.640  5585  5632 I jxcore-log: 
,11-24 06:21:07.648  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 06:21:07.648  5585  5632 I jxcore-log: 
,11-24 06:21:07.652  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 06:21:07.652  5585  5632 I jxcore-log: 
,11-24 06:21:07.657  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 06:21:07.657  5585  5632 I jxcore-log: 
,11-24 06:21:07.662  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 06:21:07.662  5585  5632 I jxcore-log: 
,11-24 06:21:07.689  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 06:21:07.689  5585  5632 I jxcore-log: 
,11-24 06:21:07.723  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 06:21:07.723  5585  5632 I jxcore-log: 
,11-24 06:21:07.729  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 06:21:07.729  5585  5632 I jxcore-log: 
,11-24 06:21:07.735  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 06:21:07.735  5585  5632 I jxcore-log: 
,11-24 06:21:07.748  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 06:21:07.748  5585  5632 I jxcore-log: 
,11-24 06:21:07.762  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 06:21:07.762  5585  5632 I jxcore-log: 
,11-24 06:21:07.767  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 06:21:07.767  5585  5632 I jxcore-log: 
,11-24 06:21:07.772  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 06:21:07.772  5585  5632 I jxcore-log: 
,11-24 06:21:07.783  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 06:21:07.783  5585  5632 I jxcore-log: 
,11-24 06:21:07.799  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 06:21:07.799  5585  5632 I jxcore-log: 
,11-24 06:21:07.812  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 06:21:07.812  5585  5632 I jxcore-log: 
,11-24 06:21:07.821  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 06:21:07.821  5585  5632 I jxcore-log: 
,11-24 06:21:07.833  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 06:21:07.833  5585  5632 I jxcore-log: 
,11-24 06:21:07.842  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 06:21:07.842  5585  5632 I jxcore-log: 
,11-24 06:21:07.854  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 06:21:07.854  5585  5632 I jxcore-log: 
,11-24 06:21:07.862  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 06:21:07.862  5585  5632 I jxcore-log: 
,11-24 06:21:07.868  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 06:21:07.868  5585  5632 I jxcore-log: 
,11-24 06:21:07.887  5585  5632 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 06:21:07.888  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 06:21:07.888  5585  5632 I jxcore-log: 
,11-24 06:21:07.918  5585  5632 I jxcore-log: 2016-11-24 11:21:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 06:21:07.918  5585  5632 I jxcore-log: 
,11-24 06:21:08.419  5585  5632 I jxcore-log: 2016-11-24 11:21:08 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 06:21:08.419  5585  5632 I jxcore-log: 
,11-24 06:21:25.830   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:26.831   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:27.468   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 06:21:27.833   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:28.834   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:29.835   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:21:30.836   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 06:21:55.837   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 06:21:55.837   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 06:22:07.473   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 06:22:10.838   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:11.839   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:12.841   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:13.843   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:14.844   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:15.845   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 06:22:20.847   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:21.848   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:22.850   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:23.851   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:24.852   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:25.853   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 06:22:27.474   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 06:22:35.854   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:36.855   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:37.856   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:38.858   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:39.860   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:40.860   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 06:22:55.862   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:56.863   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:57.865   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:58.866   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:22:59.867   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:23:00.868   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 06:23:07.476   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 06:23:20.870   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:23:21.871   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:23:22.873   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:23:23.875   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:23:24.876   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:23:25.878   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 06:23:27.477   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 06:23:47.479   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 06:23:50.878   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 06:23:50.879   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 06:23:57.831   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 06:24:00.862   930  2922 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 06:24:10.880   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:11.881   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:12.883   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:13.885   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:14.886   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:15.887   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 06:24:20.888   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:21.890   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:22.892   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:23.893   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:24.894   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 06:24:25.555  5585  5632 I jxcore-log: 2016-11-24 11:24:25 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 06:24:25.555  5585  5632 I jxcore-log: 
,11-24 06:24:25.850  5585  5632 I jxcore-log: 2016-11-24 11:24:25 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 06:24:25.850  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 06:24:25.850  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 06:24:25.850  5585  5632 I jxcore-log: emit@events.js:82:1
11-24 06:24:25.850  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 06:24:25.850  5585  5632 I jxcore-log: emit@events.js:82:1''
11-24 06:24:25.850  5585  5632 I jxcore-log: 
11-24 06:24:25.852  5585  5632 I jxcore-log: 2016-11-24 11:24:25 - DEBUG CoordinatedClient: 'test client failed'
11-24 06:24:25.852  5585  5632 I jxcore-log: 
,11-24 06:24:25.862  5585  5632 I jxcore-log: 2016-11-24 11:24:25 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 06:24:25.862  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 06:24:25.862  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 06:24:25.862  5585  5632 I jxcore-log: emit@events.js:82:1
11-24 06:24:25.862  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 06:24:25.862  5585  5632 I jxcore-log: emit@events.js:82:1''
11-24 06:24:25.862  5585  5632 I jxcore-log: 
,11-24 06:24:25.863  5585  5632 I jxcore-log: 2016-11-24 11:24:25 - DEBUG CoordinatedClient: 'test client failed'
11-24 06:24:25.863  5585  5632 I jxcore-log: 
,11-24 06:24:25.867  5585  5632 I jxcore-log: 2016-11-24 11:24:25 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 06:24:25.867  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 06:24:25.867  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 06:24:25.867  5585  5632 I jxcore-log: emit@events.js:82:1
11-24 06:24:25.867  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 06:24:25.867  5585  5632 I jxcore-log: emit@events.js:82:1''
11-24 06:24:25.867  5585  5632 I jxcore-log: 
,11-24 06:24:25.869  5585  5632 I jxcore-log: 2016-11-24 11:24:25 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 06:24:25.869  5585  5632 I jxcore-log: 
,11-24 06:24:25.895   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 06:24:26.558  5955  5955 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 06:24:26.588  5955  5955 D AndroidRuntime: CheckJNI is OFF
,11-24 06:24:26.611  5955  5955 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 06:24:26.643  5955  5955 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 06:24:26.659  5955  5955 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 06:24:26.675   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 06:24:26.675   930   943 I ActivityManager: Killing 5585:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 06:24:26.804   930  3809 D GraphicsStats: Buffer count: 2
,11-24 06:24:26.804   930  2921 D WifiService: Client connection lost with reason: 4
11-24 06:24:26.804   930  3689 I WindowState: WIN DEATH: Window{7e87af2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 06:24:26.827   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-24 06:24:26.831   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-24 06:24:26.832   930   953 I art     : Starting a blocking GC Explicit
,11-24 06:24:26.832   930   943 E ActivityManager: Failure starting process com.test.thalitest
11-24 06:24:26.832   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-24 06:24:26.832   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:24:26.832   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:24:26.832   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 06:24:26.832   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-24 06:24:26.833   930   943 I ActivityManager:   Force finishing activity ActivityRecord{64507c7 u0 com.test.thalitest/.MainActivity t10}
,11-24 06:24:26.844   930  3099 W ActivityManager: Spurious death for ProcessRecord{d97766b 0:com.test.thalitest/u0a77}, curProc for 5585: null
,11-24 06:24:26.847   930   948 W WindowManager: Attempted to add application window with unknown token Token{ead21f4 ActivityRecord{64507c7 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-24 06:24:26.848   930   948 W WindowManager: Token{ead21f4 ActivityRecord{64507c7 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{ead21f4 ActivityRecord{64507c7 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-24 06:24:26.848   930   948 W WindowManager: view not successfully added to wm, removing view
11-24 06:24:26.848   930   948 W WindowManager: Exception when adding starting window
11-24 06:24:26.848   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{b2e6412 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-24 06:24:26.848   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-24 06:24:26.848   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-24 06:24:26.848   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-24 06:24:26.848   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-24 06:24:26.848   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-24 06:24:26.848   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:24:26.848   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:24:26.848   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 06:24:26.848   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-24 06:24:26.923   930   953 I art     : Explicit concurrent mark sweep GC freed 101630(7MB) AllocSpace objects, 61(1816KB) LOS objects, 33% free, 29MB/43MB, paused 1.692ms total 91.313ms
,11-24 06:24:26.949   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 06:24:26.952  5955  5955 I art     : System.exit called, status: 0
,11-24 06:24:26.952  5955  5955 I AndroidRuntime: VM exiting with result code 0.
,11-24 06:24:26.965   930   953 I ActivityManager: Start proc 5965:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-24 06:24:26.966   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 06:24:26.972   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-24 06:24:26.977  5853  5853 D BluetoothMapAppObserver: onReceive
11-24 06:24:26.979  5853  5853 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 06:24:26.979  3641  3641 I Keyboard.Facilitator: resetDictionaries() : en_US
11-24 06:24:26.985   930  2874 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-24 06:24:26.985  3986  4135 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-24 06:24:27.007  3641  5977 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 06:24:27.021  3340  5978 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 06:24:27.024  3641  5977 I Decoder : createOrResetDecoder
,11-24 06:24:27.046  3757  3757 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 06:24:27.059  5555  5555 W kworker/1:3: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 06:24:27.065   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 06:24:27.066  5555  5555 W kworker/1:3: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 06:24:27.072  5555  5555 W kworker/1:3: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 06:24:27.078  3788  3880 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-24 06:24:27.079  3517  3517 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-24 06:24:27.079  3517  3517 E AndroidRuntime: FATAL EXCEPTION: main
11-24 06:24:27.079  3517  3517 E AndroidRuntime: Process: com.google.process.gapps, PID: 3517
11-24 06:24:27.079  3517  3517 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:130)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-24 06:24:27.079  3517  3517 E AndroidRuntime: 	... 8 more
,11-24 06:24:27.090   930  5984 E DropBoxManagerService: Can't write: system_app_crash
11-24 06:24:27.090   930  5984 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 06:24:27.090   930  5984 E DropBoxManagerService: 	... 5 more
,11-24 06:24:27.098  3340  3362 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj6A2F9790A) - 
11-24 06:24:27.098   930  3689 I ActivityManager: Start proc 5985:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-24 06:24:27.099  3788  3880 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 06:24:27.099  3788  3880 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3788
11-24 06:24:27.099  3788  3880 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:24:27.099  3788  3880 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 06:24:27.101  3517  3517 I Process : Sending signal. PID: 3517 SIG: 9
,11-24 06:24:27.103   930  3102 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1868)
11-24 06:24:27.104   930  3102 W ActivityManager: Application dead when creating service ServiceRecord{162734 u0 com.google.android.gms/.config.ConfigService}
,11-24 06:24:27.116   930  2921 D WifiService: Client connection lost with reason: 4
,11-24 06:24:27.118  3340  3362 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-24 06:24:27.118  3340  3362 E AndroidRuntime: Process: android.process.acore, PID: 3340
11-24 06:24:27.118  3340  3362 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 06:24:27.118  3340  3362 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 06:24:27.124  3340  5978 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-24 06:24:27.125  3340  5978 I Process : Sending signal. PID: 3340 SIG: 9
,11-24 06:24:27.135   930  3102 I ActivityManager: Process com.google.process.gapps (pid 3517) has died
11-24 06:24:27.136   930  3102 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
11-24 06:24:27.136   930  3102 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
11-24 06:24:27.136   930  3102 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 21000ms
,11-24 06:24:27.136   930  3102 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
11-24 06:24:27.137   930  3102 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 124000ms
11-24 06:24:27.138   930  3102 W ActivityManager: Exception when starting service com.google.android.gms/.config.ConfigService
11-24 06:24:27.138   930  3102 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-24 06:24:27.138   930  3102 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:985)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
11-24 06:24:27.138   930  3102 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,11-24 06:24:27.150   930   943 I ActivityManager: Start proc 5997:com.google.process.gapps/u0a12 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,11-24 06:24:27.156   930  3861 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 06:24:27.158   930  6007 E DropBoxManagerService: Can't write: system_app_crash
11-24 06:24:27.158   930  6007 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 06:24:27.158   930  6007 E DropBoxManagerService: 	... 5 more
11-24 06:24:27.159   930  6006 E DropBoxManagerService: Can't write: system_app_crash
11-24 06:24:27.159   930  6006 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 06:24:27.159   930  6006 E DropBoxManagerService: 	... 5 more
11-24 06:24:27.159   930  3530 W ActivityManager: Spurious death for ProcessRecord{bbd5b96 0:com.google.process.gapps/u0a12}, curProc for 3517: null
,11-24 06:24:27.162  3788  3880 I Process : Sending signal. PID: 3788 SIG: 9
,11-24 06:24:27.224   930  2873 W InputDispatcher: channel '9a0a69 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-24 06:24:27.224   930  2873 E InputDispatcher: channel '9a0a69 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
11-24 06:24:27.225   930  3754 D GraphicsStats: Buffer count: 1
11-24 06:24:27.225   930  3689 I WindowState: WIN DEATH: Window{9a0a69 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-24 06:24:27.225   930  3689 W InputDispatcher: Attempted to unregister already unregistered input channel '9a0a69 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-24 06:24:27.242   930  3829 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3788) has died
11-24 06:24:27.242   930  3829 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-24 06:24:27.243   930  3829 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 06:24:27.267   930   943 I ActivityManager: Start proc 6013:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 06:24:27.268   930  3099 I ActivityManager: Process android.process.acore (pid 3340) has died
11-24 06:24:27.268   930  3099 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-24 06:24:27.484   930  2920 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437

```
